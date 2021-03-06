# Test

[![Build Status](https://travis-ci.org/wovert/TestTutorials.svg?branch=master)](https://travis-ci.org/wovert/TestTutorials)

[![codecov](https://codecov.io/gh/wovert/TestTutorials/branch/master/graph/badge.svg)](https://codecov.io/gh/wovert/TestTutorials)

## API 测试

### 单元测试

[chaijs.com](http://chaijs.com)

- BDD
- TDD

```sh
npm i chai --save-dev
# 执行test目录下所有测试用例
npm test
```

### 测试覆盖率

[istanbul](https://github.com/gotwarlost/istanbul)

```sh
npm i -g istanbul
vim package.json
  "cover": "istanbul cover_mocha --reporter test/mocha.js"
  # for windows
  "cover": "istanbul cover node_modules/mocha/bin/_mocha test/mocha.js"
```

Statements   : 100% ( 5/5 ) 声明
Branches     : 100% ( 0/0 ) 分支(if)
Functions    : 100% ( 0/0 )
Lines        : 100% ( 5/5 )

### 持续集成

- 频繁的将代码集成到主干
- 每次集成都通过自动化的构建来验证

- 尽早发现错误
- 防止分支大幅偏离主干

build:parsing

[https://travis-ci.org/dwyl/esta]

### 性能测试

[benchmark.js](https://benchmarkjs.com/)

[jsperf.com](https://jsperf.com)

## UI 测试

