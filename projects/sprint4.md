---
title: Create-Basic-App CLI
layout: page
---


## What it does

Create-basic-app is a CLI tool for you to quickly bootstrap a new project boilerplate. By inputting different commands to the create-basic-app CLI in your terminal you can generate different starter codes for JavaScript-based or Python-based applications. This CLI was created to help developers quickly get started with their amazing and important tasks at hand and reduce the initial boilerplate code developers need to write.

For the JavaScript-based templates, you can generally generate a full-stack app or a rest API (Node/Express for backend in both cases) and in both cases, you have the extra option of including NoSQL starter code (MongoDB for database and mongoose as ODM) or SQL starter code (PostgreSQL for database and sequelize as ORM). For the python templates, you can generally generate a Flask API template or a Django API template. In both cases, you have the extra option of including SQL starter code

## How we built it

We built it using Node.JS and several npm modules.


## Challenge we ran into

We didn't run into serious challenges when creating the project. But during final testing, we realised npm was ignoring our template .gitignore files when our CLI was installed globally and that was causing generation errors. We fixed the issue by saving the files as "gitignore" and renaming them to ".gitignore" after template generation.

## Try it out

[Create-Basic-App](https://github.com/david-osas/create-basic-app)