# Intro

A simple HackerNews clone. There are still many features not implemented due to complexities.

# Prerequisites
* NodeJS
* MongoDB

You need to add an index by running the following cmd in mgono shell:
```bash
> use hacknews
> db.users.ensureIndex({username:1}, {unique:true})
```
# Installation
```bash
git clone https://github.com/edwardwohaijun/Hacker-News-clone
cd Hacker-News-clone
npm install
npm run build(for development environment)
npm run ship(for production environment)
npm run start
```
Open browser, go to http://127.0.0.1:3030/HN
