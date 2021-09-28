

## About

```
Boilerplate for Server Challenges

```

## Technologies

```
HTML

CSS

JEST - ignore if you aren't familiar with Testing

Browser-sync

run-os

```

## Scripts

AFTER LAUNCH, GO TO PUBLIC FOLDER IN DIRECTORY AND CLICK ON HTML FILE TO ACCESS YOUR PAGE

To launch live server: Chrome
```
npm start

```

To launch live server: Firefox  ** MUST HAVE FIREFOX DEV EDITION INSTALLED in C Drive
```
npm run start-fox

```

## Fixing Possible Browser-sync Erros 

change the directory at the end to the appropriate one for your target browser
```
 "browser-sync start --server --files '**/*.css, **/*.html, **/*.js, !node_modules/**/*' --directory --port 7777 --browser \"C:\\Program Files\\Firefox Developer Edition\\firefox.exe\""

```
## Folder Structure

Standard HTML, CSS, JS One page App

Built for Modular, Scalable apps

Incorporate BEM Methodologies or 7-1 Folder Structure if needed.