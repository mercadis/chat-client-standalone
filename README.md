# What is Chat Client Standalone

Chat client standalone is hello world chat prototype realized with [Angular 2](https://angular.io/) where you can send message over tab in web browser.

# Quick Start

## Prerequisites

Firstly you need to install [Nodejs](https://nodejs.org).
After, you need 2 tools :
> `npm install -g gulp tsd`

If you want testing in your favorite text editor, you need [wallaby.js](http://wallabyjs.com/) (you can use trial demo)

## Installation

>`npm install`

>`tsd install`

## Execution

### Start server

>`gulp serve`

Lunch browser `http:\\localhost:3000`

### Test

Lunch wallaby.js on your editor

## Technologies

### Tools

- Node.js
- Typescript
- TSD DefinitelyTyped

### Application

- Angular 2
  - RxJS 5
- Bootstrap 4

### Tests

- Jasmine
- Karma
- Wallaby.js

## Checklist

- [x] Display messages
- [x] Send message
- [x] Keep focus on input message
- [x] Save messages in LocalStorage
- [x] Nickname Command
- [x] Clean Command
- [x] Multi user (one per tab)
- [ ] Avartar
- [x] Smart scroll on new message
- [ ] Test e2e with angular 2
