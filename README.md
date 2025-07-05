# TypeScript decorator example

A simple TypeScript example that mimics how DBOS (or a similar durable execution engine) uses decorators like @Workflow and @Step to implement durable workflows.
This will not be fully durable (no real database), but it simulates the architecture and behavior using in-memory state. It shows you how decorators can be used to structure durable workflows.

## Add neccesary things to local files
* git clone https://github.com/spiritfx69/decorator
* cd decorator
* npm init -y
* npm install --save-dev typescript
* npx tsc -v                                                 // check TS version
* npm run build
* npm start

## Add local files to GitHub
* git status
* git add --all
* git commit -m "initial check-in"
* git push

## Extra info
* add to package.json
* "build": "tsc",
* "start": "node index.js",

## Reference
* [GitHub: Typescript Decorators Examples](https://github.com/arolson101/typescript-decorators/tree/master)
