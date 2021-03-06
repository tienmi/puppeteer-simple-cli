# Puppeteer-simple-cli

Puppeteer-simple-cli is a really simple puppeteer tool for End to End test. Integrate lint-related tools and preset a high-maintenance test architecture.

### Get Started

```
npm i -g puppeteer-simple-cli
```

#### Basic usage

##### Information

```
psc
```

##### Create a project

```
psc init <project-name>
```

##### Update puppeteer-simple-cli-cores

```
psc update
```

##### Start testing

```
npm run test
```

##### Create src/main.config.js and addition config

```
module.exports = {
    targetURL: '', // It's your target URL
    pipelines: [ // Execute your situation in order
        {
            title: 'Situation description',
            path: 'Your script path'
        }
    ],
    config: { headless: false, slowMo: 50, defaultViewport: null }, // Puppeteer config
    retry: 1,  // Number of retries
    getClientLog: false // Whether to accept client log
};
```

## License

[MIT](https://github.com/tienmi/puppeteer-simple-cli-cores/blob/main/LICENSE)
