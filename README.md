```
npm install jspm@0.17.0-beta.13
npm install -g lite-server
./node_modules/.bin/jspm install
./node_modules/.bin/jspm bundle src/main.ts -wid
lite-server
```

## Current issues

* [ ] can't load external templates
    * probably related to this https://github.com/Microsoft/TypeScript/issues/6615
