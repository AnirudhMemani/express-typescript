# Express + Typescript setup which supports both ES6 syntax and JS Modules syntax

-   Note: This has nodemon already enabled

## Clone the repository

```
git clone https://github.com/AnirudhMemani/express-typescript
```

## Change directory into the repository

```
cd express-typescript
```

## Install npm packages

```
npm install
```

## Start the server

```
npm run dev
```

-   Note: If you want to server static assests to your build files add the following to package.json scripts:

```
"copy-assets": "copyfiles --error --up 1 src/<FolderName>/*.* dist",
"postbuild": "npm run copy-assets"
```

-   Change FolderName with the name of the folder which contains your static assests.
