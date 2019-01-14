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
https://googlechrome.github.io/lighthouse/viewer/?gist=d3a26bbc29160536445fbc88cef7e42e

### artillery.io
`artillery quick --count 100 -n 20 http://dev-with-matt.pantheonsite.io/vue-template/`    

```
All virtual users finished
Summary report @ 16:22:47(-0500) 2019-01-14
  Scenarios launched:  100
  Scenarios completed: 100
  Requests completed:  2000
  RPS sent: 491.4
  Request latency:
    min: 21.3
    max: 140.8
    median: 51.5
    p95: 89
    p99: 107.5
  Scenario counts:
    0: 100 (100%)
  Codes:
    200: 2000
```