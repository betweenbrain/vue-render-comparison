# vue-render-benchmark

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Initial test results
### [Lighthouse](https://developers.google.com/web/tools/lighthouse/)
https://googlechrome.github.io/lighthouse/viewer/?gist=b447587374efe8d179d7dd87f6adf71d

### artillery.io
`artillery quick --count 100 -n 20 http://dev-with-matt.pantheonsite.io/vue-create-element/`    

```
All virtual users finished
Summary report @ 16:28:29(-0500) 2019-01-14
  Scenarios launched:  100
  Scenarios completed: 100
  Requests completed:  2000
  RPS sent: 497.51
  Request latency:
    min: 21.6
    max: 143.2
    median: 52.8
    p95: 86.9
    p99: 111.4
  Scenario counts:
    0: 100 (100%)
  Codes:
    200: 2000
```