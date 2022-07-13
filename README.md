# Puppeteer-simple-cli

## Status

Puppeteer-simple-cli is a really simple puppeteer tool for End to End test.

### Get Started

```
npm i -g puppeteer-simple-cli
```

#### Basic usage

##### Information

```
$psc
```

##### Create a project

```
$psc init <project-name>
```

##### Update puppeteer-simple-cli-cores

```
$psc update
```

##### Start testing

```
npm run test
```

##### create src/main.config.js and addition config

```
module.exports = {
    targetURL: '', // It's your target URL
    pipelines: [
        {
            name: 'stepName',
            path: 'your script path',
            retry: 0, // number of retries
            reload: false // true is page reload
        }
    ],
    config: { headless: false, slowMo: 50, defaultViewport: null },
    retry: 1
};
```

## License

[MIT](https://github.com/tienmi/puppeteer-simple-cli-cores/blob/main/LICENSE)
