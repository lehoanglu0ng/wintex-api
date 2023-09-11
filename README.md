## Tech stack

- Node.js > v14
- JavaScript
- Supported OS: macOS, Linux, Windows
- Automation tool: Newman, Postman

## Installing

```bash
npm install -g newman
npm install -g newman-reporter-htmlextra
```

## Execute tests on TEST environment
```bash
newman run Wintex.postman_collection.json -e Wintex_TEST.postman_environment.json -r htmlextra
```

## Execute tests on UAT environment
```bash
newman run Wintex.postman_collection.json -e Wintex_UAT.postman_environment.json -r htmlextra
```

## Execute tests on PROD environment
```bash
newman run Wintex.postman_collection.json -e Wintex_PROD.postman_environment.json -r htmlextra
```

## View Newman report in ./newman folder