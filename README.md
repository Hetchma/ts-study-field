# Project to leaning TypeScript
## Create package.json
```bash
npm init -y
```
## Install TypeScript
```bash
yarn add typescript
```

## Create tsconfig.json
```bash
./node_modules/.bin/tsc --init
```

## Create Working file
```bash
touch studyfile.ts
```

## Add compile script in package.json
```bash
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "tsc" : "tsc"
  },
```

## Compile working file
```bash
yarn tsc
```