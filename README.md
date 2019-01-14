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
https://googlechrome.github.io/lighthouse/viewer/?gist=19f46575081facd89846679da20b2fa1

### artillery.io
`artillery quick --count 100 -n 20 http://dev-with-matt.pantheonsite.io/vue-jsx/`    

```
All virtual users finished
Summary report @ 16:29:14(-0500) 2019-01-14
  Scenarios launched:  100
  Scenarios completed: 100
  Requests completed:  2000
  RPS sent: 496.28
  Request latency:
    min: 22.2
    max: 155.1
    median: 54.3
    p95: 87.9
    p99: 105.8
  Scenario counts:
    0: 100 (100%)
  Codes:
    200: 2000
```