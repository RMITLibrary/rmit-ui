### This repository resolves live here

[https://rmitlibrary.github.io/rmit-ui/](https://rmitlibrary.github.io/rmit-ui/)


### Development

Clone repo

## 2. Install dependencies

```bash
npm install
```

## 3. Start development server

```bash
npm run start
```
## Make your edits

Commit changes, make a pull request or

## Compile for live

```bash
hugo
```
Then rename the "public" folder as "docs" and push to GitHub

## What to edit.

### Content
```bash
/content/docs/bootstrap5/XXXXX.md 
```
for editing content, duplicate a file, edit the meta in the head and save.

### Styles
While the server is running, edit *.scss files in the
```bash
/assets/scss/
```
folder. Good idea to have a look across the scss files as there's an order to them. Start with _variables.scss and _global.scss

### Other folders
Shouldn't need to touch them, most of them just support the development environment

## Weird things

* Sidebar menu seems to be broken on local, works on live.

