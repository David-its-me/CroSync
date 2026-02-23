# CroSync


## Install and run

Install lates nvm version from the [nvm windows GitHub releases](https://github.com/coreybutler/nvm-windows) page. Download the .exe file and start the installation.

```
nvm install latest
nvm use <your-latest-version>
```
```
npm install --legacy-peer-deps
```

```
npm run
```
## Git

Make sure to get LF endings under Windows. 
The proper way to get LF endings in Windows is to first set core.autocrlf to false:

```
git config core.autocrlf false
```

You need to do this if you are using msysgit, because it sets it to true in its system settings.
Now git won’t do any line ending normalization. 

And set core.eol to lf:

```
git config core.eol lf
```