$ npm install

> uws@9.14.0 install C:\Users\Kefir\first-assignment-stanislavchirva\node_modules\uws
> node-gyp rebuild > build_log.txt 2>&1 || exit 0

npm WARN front-camp-tasks@1.0.0 No repository field.

added 919 packages from 922 contributors and audited 8189 packages in 15.488s
found 6 vulnerabilities (1 low, 5 moderate)
  run `npm audit fix` to fix them, or `npm audit` for details

  
  
  
  $ npm test

> front-camp-tasks@1.0.0 test C:\Users\Kefir\first-assignment-stanislavchirva
> karma start ./karma.conf.js

13 09 2018 20:26:29.368:DEBUG [config]: Loading config C:\Users\Kefir\first-assi                         gnment-stanislavchirva\karma.conf.js
13 09 2018 20:26:29.368:DEBUG [karma]: Final config {
  "LOG_DISABLE": "OFF",
  "LOG_ERROR": "ERROR",
  "LOG_WARN": "WARN",
  "LOG_INFO": "INFO",
  "LOG_DEBUG": "DEBUG",
  "frameworks": [
    "jasmine"
  ],
  "protocol": "http:",
  "port": 9876,
  "listenAddress": "0.0.0.0",
  "hostname": "localhost",
  "httpsServerConfig": {},
  "basePath": "C:/Users/Kefir/first-assignment-stanislavchirva/src",
  "files": [
    {
      "pattern": "C:/Users/Kefir/first-assignment-stanislavchirva/src/**/*.spec.                         js",
      "served": true,
      "included": true,
      "watched": true,
      "nocache": false,
      "weight": [
        1,
        1,
        1,
        0,
        0,
        0
      ]
    }
  ],
  "browserConsoleLogOptions": {
    "level": "debug",
    "format": "%b %T: %m",
    "terminal": true
  },
  "customContextFile": null,
  "customDebugFile": null,
  "customClientContextFile": null,
  "exclude": [
    "C:/Users/Kefir/first-assignment-stanislavchirva/karma.conf.js"
  ],
  "logLevel": "DEBUG",
  "colors": true,
  "autoWatch": false,
  "autoWatchBatchDelay": 250,
  "restartOnFileChange": false,
  "usePolling": true,
  "reporters": [
    "kjhtml",
    "mocha"
  ],
  "singleRun": true,
  "browsers": [
    "ChromeHeadlessNoSandbox"
  ],
  "captureTimeout": 60000,
  "proxies": {},
  "proxyValidateSSL": true,
  "preprocessors": {
    "C:/Users/Kefir/first-assignment-stanislavchirva/src/**/*.spec.js": [
      "webpack"
    ]
  },
  "urlRoot": "/",
  "reportSlowerThan": 0,
  "loggers": [
    {
      "type": "console",
      "layout": {
        "type": "pattern",
        "pattern": "%[%d{DATE}:%p [%c]: %]%m"
      }
    }
  ],
  "transports": [
    "polling",
    "websocket"
  ],
  "forceJSONP": false,
  "plugins": [
    "karma-*",
    {
      "launcher:ChromeHeadlessNoSandbox": [
        "factory",
        null
      ]
    }
  ],
  "client": {
    "args": [],
    "useIframe": true,
    "runInParent": false,
    "captureConsole": true,
    "clearContext": false
  },
  "defaultClient": {
    "args": [],
    "useIframe": true,
    "runInParent": false,
    "captureConsole": true,
    "clearContext": false
  },
  "browserDisconnectTimeout": 2000,
  "browserDisconnectTolerance": 0,
  "browserNoActivityTimeout": 10000,
  "processKillTimeout": 2000,
  "concurrency": null,
  "failOnEmptyTestSuite": true,
  "retryLimit": 2,
  "detached": false,
  "crossOriginAttribute": true,
  "cmd": "start",
  "configFile": "C:\\Users\\Kefir\\first-assignment-stanislavchirva\\karma.conf.                         js",
  "webpack": {
    "mode": "development",
    "devtool": "eval"
  },
  "webpackServer": {
    "noInfo": true
  },
  "atomic_save": false,
  "customLaunchers": {
    "ChromeHeadlessNoSandbox": {
      "base": "ChromeHeadless",
      "flags": [
        "--no-sandbox"
      ]
    }
  }
}
13 09 2018 20:26:29.368:DEBUG [plugin]: Loading karma-* from C:\Users\Kefir\firs                         t-assignment-stanislavchirva\node_modules
13 09 2018 20:26:29.368:DEBUG [plugin]: Loading plugin C:\Users\Kefir\first-assi                         gnment-stanislavchirva\node_modules/karma-chrome-launcher.
13 09 2018 20:26:29.384:DEBUG [plugin]: Loading plugin C:\Users\Kefir\first-assi                         gnment-stanislavchirva\node_modules/karma-jasmine.
13 09 2018 20:26:29.384:DEBUG [plugin]: Loading plugin C:\Users\Kefir\first-assi                         gnment-stanislavchirva\node_modules/karma-jasmine-html-reporter.
13 09 2018 20:26:29.384:DEBUG [plugin]: Loading plugin C:\Users\Kefir\first-assi                         gnment-stanislavchirva\node_modules/karma-mocha-reporter.
13 09 2018 20:26:29.415:DEBUG [plugin]: Loading plugin C:\Users\Kefir\first-assi                         gnment-stanislavchirva\node_modules/karma-webpack.
13 09 2018 20:26:30.114:DEBUG [plugin]: Loading inlined plugin (defining launche                         r:ChromeHeadlessNoSandbox).
13 09 2018 20:26:30.275:DEBUG [web-server]: Instantiating middleware
13 09 2018 20:26:30.275:DEBUG [reporter]: Trying to load reporter: kjhtml
13 09 2018 20:26:30.275:DEBUG [reporter]: Trying to load color-version of report                         er: kjhtml (kjhtml_color)
13 09 2018 20:26:30.275:DEBUG [reporter]: Couldn't load color-version.
13 09 2018 20:26:30.275:DEBUG [reporter]: Trying to load reporter: mocha
13 09 2018 20:26:30.275:DEBUG [reporter]: Trying to load color-version of report                         er: mocha (mocha_color)
13 09 2018 20:26:30.275:DEBUG [reporter]: Couldn't load color-version.

START:
(node:10928) DeprecationWarning: Tapable.plugin is deprecated. Use new API on `.                         hooks` instead
i ｢wdm｣: Hash: 13a2f03acc35403b1ae0
Version: webpack 4.16.5
Time: 11099ms
Built at: 2018-09-13 20:26:30
i ｢wdm｣: Compiled successfully.
i ｢wdm｣: Compiling...
i ｢wdm｣: wait until bundle finished: noop
i ｢wdm｣: wait until bundle finished: noop
i ｢wdm｣: wait until bundle finished: noop
i ｢wdm｣: wait until bundle finished: noop
i ｢wdm｣: wait until bundle finished: noop
i ｢wdm｣: wait until bundle finished: noop
i ｢wdm｣: wait until bundle finished: noop
i ｢wdm｣: Hash: 3932dd29088f2752d268
Version: webpack 4.16.5
Time: 11047ms
Built at: 2018-09-13 20:26:30
                    Asset      Size                     Chunks             Chunk                          Names
   getFlags/index.spec.js  5.75 KiB     getFlags/index.spec.js  [emitted]  getFl                         ags/index.spec.js
   isObject/index.spec.js  5.94 KiB     isObject/index.spec.js  [emitted]  isObj                         ect/index.spec.js
        max/index.spec.js  5.36 KiB          max/index.spec.js  [emitted]  max/i                         ndex.spec.js
        sum/index.spec.js  6.06 KiB          sum/index.spec.js  [emitted]  sum/i                         ndex.spec.js
sumElements/index.spec.js  6.19 KiB  sumElements/index.spec.js  [emitted]  sumEl                         ements/index.spec.js
   truncate/index.spec.js     6 KiB     truncate/index.spec.js  [emitted]  trunc                         ate/index.spec.js
 turnMeBaby/index.spec.js  5.58 KiB   turnMeBaby/index.spec.js  [emitted]  turnM                         eBaby/index.spec.js
    twoSums/index.spec.js  6.16 KiB      twoSums/index.spec.js  [emitted]  twoSu                         ms/index.spec.js
Entrypoint getFlags/index.spec.js = getFlags/index.spec.js
Entrypoint isObject/index.spec.js = isObject/index.spec.js
Entrypoint max/index.spec.js = max/index.spec.js
Entrypoint sum/index.spec.js = sum/index.spec.js
Entrypoint sumElements/index.spec.js = sumElements/index.spec.js
Entrypoint truncate/index.spec.js = truncate/index.spec.js
Entrypoint turnMeBaby/index.spec.js = turnMeBaby/index.spec.js
Entrypoint twoSums/index.spec.js = twoSums/index.spec.js
[./src/getFlags/index.js] 314 bytes {getFlags/index.spec.js} [built]
[./src/getFlags/index.spec.js] 694 bytes {getFlags/index.spec.js} [built]
[./src/isObject/index.js] 397 bytes {isObject/index.spec.js} [built]
[./src/isObject/index.spec.js] 694 bytes {isObject/index.spec.js} [built]
[./src/max/index.js] 290 bytes {max/index.spec.js} [built]
[./src/max/index.spec.js] 418 bytes {max/index.spec.js} [built]
[./src/sum/index.js] 354 bytes {sum/index.spec.js} [built]
[./src/sum/index.spec.js] 783 bytes {sum/index.spec.js} [built]
[./src/sumElements/index.spec.js] 793 bytes {sumElements/index.spec.js} [built]
[./src/truncate/index.js] 520 bytes {truncate/index.spec.js} [built]
[./src/truncate/index.spec.js] 736 bytes {truncate/index.spec.js} [built]
[./src/turnMeBaby/index.js] 332 bytes {turnMeBaby/index.spec.js} [built]
[./src/turnMeBaby/index.spec.js] 502 bytes {turnMeBaby/index.spec.js} [built]
[./src/twoSums/index.js] 472 bytes {twoSums/index.spec.js} [built]
[./src/twoSums/index.spec.js] 893 bytes {twoSums/index.spec.js} [built]
    + 1 hidden module
i ｢wdm｣: Compiled successfully.
13 09 2018 20:26:30.589:INFO [karma]: Karma v2.0.5 server started at http://0.0.                         0.0:9876/
13 09 2018 20:26:30.589:INFO [launcher]: Launching browser ChromeHeadlessNoSandb                         ox with unlimited concurrency
13 09 2018 20:26:30.604:INFO [launcher]: Starting browser ChromeHeadless
13 09 2018 20:26:30.604:DEBUG [temp-dir]: Creating temp dir at C:\Users\Kefir\Ap                         pData\Local\Temp\karma-68747616
13 09 2018 20:26:30.604:DEBUG [launcher]: C:\Program Files (x86)\Google\Chrome\A                         pplication\chrome.exe --user-data-dir=C:\Users\Kefir\AppData\Local\Temp\karma-68                         747616 --no-default-browser-check --no-first-run --disable-default-apps --disabl                         e-popup-blocking --disable-translate --disable-background-timer-throttling --dis                         able-renderer-backgrounding --disable-device-discovery-notifications --no-sandbo                         x http://localhost:9876/?id=68747616 --headless --disable-gpu --remote-debugging                         -port=9222
13 09 2018 20:26:31.197:DEBUG [web-server]: serving: C:\Users\Kefir\first-assign                         ment-stanislavchirva\node_modules\karma\static/client.html
13 09 2018 20:26:31.224:DEBUG [web-server]: serving: C:\Users\Kefir\first-assign                         ment-stanislavchirva\node_modules\karma\static/karma.js
13 09 2018 20:26:31.322:DEBUG [karma]: A browser has connected on socket URLvUjF                         2Z2RcLdbcAAAA
13 09 2018 20:26:31.336:INFO [HeadlessChrome 0.0.0 (Windows 10 0.0.0)]: Connecte                         d on socket URLvUjF2Z2RcLdbcAAAA with id 68747616
13 09 2018 20:26:31.336:DEBUG [launcher]: ChromeHeadless (id 68747616) captured                          in 0.747 secs
13 09 2018 20:26:31.439:DEBUG [middleware:karma]: custom files null null null
13 09 2018 20:26:31.439:DEBUG [middleware:karma]: Serving static request /contex                         t.html
13 09 2018 20:26:31.439:DEBUG [web-server]: serving: C:\Users\Kefir\first-assign                         ment-stanislavchirva\node_modules\karma\static/context.html
13 09 2018 20:26:31.456:DEBUG [web-server]: serving: C:\Users\Kefir\first-assign                         ment-stanislavchirva\node_modules\karma\static/context.js
13 09 2018 20:26:31.463:DEBUG [middleware:source-files]: Requesting /absoluteC:/                         Users/Kefir/first-assignment-stanislavchirva/node_modules/karma-jasmine-html-rep                         orter/src/css/jasmine.css?f5ac32cb356912778e94e1573dbedd82ddd46209 /
13 09 2018 20:26:31.464:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/node_modules/karma-jasmine-html-reporter/src/c                         ss/jasmine.css
13 09 2018 20:26:31.465:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/node_modules/karma-jasmine-html-reporter/src/css/j                         asmine.css
13 09 2018 20:26:31.468:DEBUG [middleware:source-files]: Requesting /absoluteC:/                         Users/Kefir/first-assignment-stanislavchirva/node_modules/jasmine-core/lib/jasmi                         ne-core/jasmine.js?a1eb923d36d1ca53b93387cb5312668373ad9ef2 /
13 09 2018 20:26:31.468:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/node_modules/jasmine-core/lib/jasmine-core/jas                         mine.js
13 09 2018 20:26:31.469:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/node_modules/jasmine-core/lib/jasmine-core/jasmine                         .js
13 09 2018 20:26:31.472:DEBUG [middleware:source-files]: Requesting /absoluteC:/                         Users/Kefir/first-assignment-stanislavchirva/node_modules/karma-jasmine/lib/boot                         .js?945a38bf4e45ad2770eb94868231905a04a0bd3e /
13 09 2018 20:26:31.472:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/node_modules/karma-jasmine/lib/boot.js
13 09 2018 20:26:31.472:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/node_modules/karma-jasmine/lib/boot.js
13 09 2018 20:26:31.473:DEBUG [middleware:source-files]: Requesting /absoluteC:/                         Users/Kefir/first-assignment-stanislavchirva/node_modules/karma-jasmine/lib/adap                         ter.js?6cf71867f538f40db053c1775b2c56a83696375c /
13 09 2018 20:26:31.473:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/node_modules/karma-jasmine/lib/adapter.js
13 09 2018 20:26:31.474:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/node_modules/karma-jasmine/lib/adapter.js
13 09 2018 20:26:31.475:DEBUG [middleware:source-files]: Requesting /absoluteC:/                         Users/Kefir/first-assignment-stanislavchirva/node_modules/karma-jasmine-html-rep                         orter/src/lib/html.jasmine.reporter.js?fe3e5940f2ee3a7290bc04e8ecba5377ca31ccda                          /
13 09 2018 20:26:31.475:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/node_modules/karma-jasmine-html-reporter/src/l                         ib/html.jasmine.reporter.js
13 09 2018 20:26:31.475:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/node_modules/karma-jasmine-html-reporter/src/lib/h                         tml.jasmine.reporter.js
13 09 2018 20:26:31.477:DEBUG [middleware:source-files]: Requesting /absoluteC:/                         Users/Kefir/first-assignment-stanislavchirva/node_modules/karma-jasmine-html-rep                         orter/src/lib/adapter.js?7f379e63dd7e5a3815ade11a605abaf79b2b02bd /
13 09 2018 20:26:31.477:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/node_modules/karma-jasmine-html-reporter/src/l                         ib/adapter.js
13 09 2018 20:26:31.477:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/node_modules/karma-jasmine-html-reporter/src/lib/a                         dapter.js
13 09 2018 20:26:31.478:DEBUG [middleware:source-files]: Requesting /base/getFla                         gs/index.spec.js?1fda46e82d588b4df2330165edeec67f695d8057 /
13 09 2018 20:26:31.478:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/src/getFlags/index.spec.js
13 09 2018 20:26:31.478:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/src/getFlags/index.spec.js
13 09 2018 20:26:31.480:DEBUG [middleware:source-files]: Requesting /base/isObje                         ct/index.spec.js?617534a1d0042f99429c54b50fe66d6a971afe0e /
13 09 2018 20:26:31.480:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/src/isObject/index.spec.js
13 09 2018 20:26:31.480:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/src/isObject/index.spec.js
13 09 2018 20:26:31.482:DEBUG [middleware:source-files]: Requesting /base/max/in                         dex.spec.js?95dd940063655135367e3c2b9cf3c5c2db0684ee /
13 09 2018 20:26:31.482:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/src/max/index.spec.js
13 09 2018 20:26:31.482:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/src/max/index.spec.js
13 09 2018 20:26:31.483:DEBUG [middleware:source-files]: Requesting /base/sum/in                         dex.spec.js?25d7f415393913f6c6ef34a76a46c2adb35424b7 /
13 09 2018 20:26:31.483:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/src/sum/index.spec.js
13 09 2018 20:26:31.483:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/src/sum/index.spec.js
13 09 2018 20:26:31.485:DEBUG [middleware:source-files]: Requesting /base/sumEle                         ments/index.spec.js?259bb1fd9b690289507836388534a578f6c25575 /
13 09 2018 20:26:31.485:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/src/sumElements/index.spec.js
13 09 2018 20:26:31.485:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/src/sumElements/index.spec.js
13 09 2018 20:26:31.487:DEBUG [middleware:source-files]: Requesting /base/trunca                         te/index.spec.js?666088199bd906983bcb623e8101d79d016e3823 /
13 09 2018 20:26:31.487:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/src/truncate/index.spec.js
13 09 2018 20:26:31.487:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/src/truncate/index.spec.js
13 09 2018 20:26:31.488:DEBUG [middleware:source-files]: Requesting /base/turnMe                         Baby/index.spec.js?d05785734b20c09d1dfb1a8550e8538e25009bb5 /
13 09 2018 20:26:31.488:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/src/turnMeBaby/index.spec.js
13 09 2018 20:26:31.488:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/src/turnMeBaby/index.spec.js
13 09 2018 20:26:31.490:DEBUG [middleware:source-files]: Requesting /base/twoSum                         s/index.spec.js?68c6fef0e49c8a49f0fa4d71d0b6d80113004c32 /
13 09 2018 20:26:31.490:DEBUG [middleware:source-files]: Fetching C:/Users/Kefir                         /first-assignment-stanislavchirva/src/twoSums/index.spec.js
13 09 2018 20:26:31.490:DEBUG [web-server]: serving (cached): C:/Users/Kefir/fir                         st-assignment-stanislavchirva/src/twoSums/index.spec.js
HeadlessChrome 0.0.0 (Windows 10 0.0.0) sum:: should throw error if one of argum                         ents is Infinity FAILED
        Expected function to throw an exception.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sum/index.spec.js?:21:87)
            at <Jasmine>
        Expected function to throw an exception.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sum/index.spec.js?:22:88)
            at <Jasmine>
  sum::
    × should throw error if one of arguments is Infinity
HeadlessChrome 0.0.0 (Windows 10 0.0.0) sum:: should throw error if at least one                          of arguments is not a number FAILED
        Expected function to throw an exception.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sum/index.spec.js?:14:82)
            at <Jasmine>
        Expected function to throw an exception.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sum/index.spec.js?:15:79)
            at <Jasmine>
        Expected function to throw an exception.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sum/index.spec.js?:16:77)
            at <Jasmine>
    × should throw error if at least one of arguments is not a number
HeadlessChrome 0.0.0 (Windows 10 0.0.0) sum:: should return sum of arguments if                          they are numbers FAILED
        Expected undefined to be 3.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sum/index.spec.js?:8:74)
            at <Jasmine>
        Expected undefined to be 5.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sum/index.spec.js?:9:74)
            at <Jasmine>
    × should return sum of arguments if they are numbers
HeadlessChrome 0.0.0 (Windows 10 0.0.0) sum:: should throw error if one of argum                         ents is NaN FAILED
        Expected function to throw an exception.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sum/index.spec.js?:27:82)
            at <Jasmine>
    × should throw error if one of arguments is NaN
HeadlessChrome 0.0.0 (Windows 10 0.0.0) getFlags:: Should return array of flags                          for passed array with any size FAILED
        Expected undefined to equal [ 1, 2, 3 ].
            at <Jasmine>
            at UserContext.it (webpack:///./src/getFlags/index.spec.js?:22:76)
            at <Jasmine>
        Expected undefined to equal [ 1, 2, 3, 4, 5, 6 ].
            at <Jasmine>
            at UserContext.it (webpack:///./src/getFlags/index.spec.js?:23:82)
            at <Jasmine>
        Expected undefined to equal [ 1, 2, 3, 4, 5, 6, 7, 8, 9 ].
            at <Jasmine>
            at UserContext.it (webpack:///./src/getFlags/index.spec.js?:24:88)
            at <Jasmine>
  getFlags::
    × Should return array of flags for passed array with any size
HeadlessChrome 0.0.0 (Windows 10 0.0.0) getFlags:: Should return array of flags                          FAILED
        Expected undefined to equal [ 1, 2, 3 ].
            at <Jasmine>
            at UserContext.it (webpack:///./src/getFlags/index.spec.js?:13:73)
            at <Jasmine>
    × Should return array of flags
HeadlessChrome 0.0.0 (Windows 10 0.0.0) isObject:: Should return false for primi                         tive values FAILED
        Expected undefined to equal false.
            at <Jasmine>
            at UserContext.it (webpack:///./src/isObject/index.spec.js?:23:71)
            at <Jasmine>
        Expected undefined to equal false.
            at <Jasmine>
            at UserContext.it (webpack:///./src/isObject/index.spec.js?:24:78)
            at <Jasmine>
        Expected undefined to equal false.
            at <Jasmine>
            at UserContext.it (webpack:///./src/isObject/index.spec.js?:25:74)
            at <Jasmine>
  isObject::
    × Should return false for primitive values
HeadlessChrome 0.0.0 (Windows 10 0.0.0) isObject:: Should return false for null                          FAILED
        Expected undefined to equal false.
            at <Jasmine>
            at UserContext.it (webpack:///./src/isObject/index.spec.js?:18:74)
            at <Jasmine>
    × Should return false for null
HeadlessChrome 0.0.0 (Windows 10 0.0.0) isObject:: Should return false for array                          literal [] FAILED
        Expected undefined to equal false.
            at <Jasmine>
            at UserContext.it (webpack:///./src/isObject/index.spec.js?:13:72)
            at <Jasmine>
    × Should return false for array literal []
HeadlessChrome 0.0.0 (Windows 10 0.0.0) isObject:: Should return true for object                          literal {} FAILED
        Expected undefined to equal true.
            at <Jasmine>
            at UserContext.it (webpack:///./src/isObject/index.spec.js?:8:72)
            at <Jasmine>
    × Should return true for object literal {}
HeadlessChrome 0.0.0 (Windows 10 0.0.0) truncate:: should truncate string FAILED
        Expected undefined to equal 'Some...'.
            at <Jasmine>
            at UserContext.eval (webpack:///./src/truncate/index.spec.js?:8:89)
            at <Jasmine>
  truncate::
    × should truncate string
HeadlessChrome 0.0.0 (Windows 10 0.0.0) truncate:: should not truncate string if                          it`s empty FAILED
        Expected undefined to equal ''.
            at <Jasmine>
            at UserContext.eval (webpack:///./src/truncate/index.spec.js?:13:72)
            at <Jasmine>
    × should not truncate string if it`s empty
HeadlessChrome 0.0.0 (Windows 10 0.0.0) truncate:: should not truncate string if                          second parameter "length" grater than string.length FAILED
        Expected undefined to equal 'Some very long text'.
            at <Jasmine>
            at UserContext.eval (webpack:///./src/truncate/index.spec.js?:23:95)
            at <Jasmine>
    × should not truncate string if second parameter "length" grater than string                         .length
HeadlessChrome 0.0.0 (Windows 10 0.0.0) truncate:: should allow to pass replacer                          FAILED
        Expected undefined to equal 'Hello wo***'.
            at <Jasmine>
            at UserContext.eval (webpack:///./src/truncate/index.spec.js?:18:93)
            at <Jasmine>
    × should allow to pass replacer
HeadlessChrome 0.0.0 (Windows 10 0.0.0) max:: Should ignore -Infinity/Infinity F                         AILED
        Expected undefined to be 1.
            at <Jasmine>
            at UserContext.it (webpack:///./src/max/index.spec.js?:13:83)
            at <Jasmine>
  max::
    × Should ignore -Infinity/Infinity
HeadlessChrome 0.0.0 (Windows 10 0.0.0) max:: Should return max number value fro                         m array FAILED
        Expected undefined to be 3.
            at <Jasmine>
            at UserContext.it (webpack:///./src/max/index.spec.js?:8:83)
            at <Jasmine>
    × Should return max number value from array
HeadlessChrome 0.0.0 (Windows 10 0.0.0) max:: Should ignore NaN FAILED
        Expected undefined to be 2.
            at <Jasmine>
            at UserContext.it (webpack:///./src/max/index.spec.js?:18:81)
            at <Jasmine>
    × Should ignore NaN
HeadlessChrome 0.0.0 (Windows 10 0.0.0) turnMeBaby:: should throw error if passe                         d not a string FAILED
        Expected undefined to equal Error: this is not a string.
            at <Jasmine>
            at UserContext.eval (webpack:///./src/turnMeBaby/index.spec.js?:15:7                         1)
            at <Jasmine>
  turnMeBaby::
    × should throw error if passed not a string
HeadlessChrome 0.0.0 (Windows 10 0.0.0) turnMeBaby:: should reverse string FAILE                         D
        Expected undefined to equal 'olleh'.
            at <Jasmine>
            at UserContext.eval (webpack:///./src/turnMeBaby/index.spec.js?:8:77                         )
            at <Jasmine>
        Expected undefined to equal 'txet gnol yrev emoS'.
            at <Jasmine>
            at UserContext.eval (webpack:///./src/turnMeBaby/index.spec.js?:9:91                         )
            at <Jasmine>
        Expected undefined to equal ''.
            at <Jasmine>
            at UserContext.eval (webpack:///./src/turnMeBaby/index.spec.js?:10:7                         2)
            at <Jasmine>
    × should reverse string
HeadlessChrome 0.0.0 (Windows 10 0.0.0) twoSums:: should return values of elemen                         ts which sum equals "base" parameter FAILED
        Expected undefined to equal [ 1, 2 ].
            at <Jasmine>
            at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:8:79)
            at <Jasmine>
  twoSums::
    × should return values of elements which sum equals "base" parameter
HeadlessChrome 0.0.0 (Windows 10 0.0.0) twoSums:: should return only first eleme                         nts which sum equals "base" parameter FAILED
        Expected undefined to equal [ 12, 3 ].
            at <Jasmine>
            at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:18:87)
            at <Jasmine>
    × should return only first elements which sum equals "base" parameter
HeadlessChrome 0.0.0 (Windows 10 0.0.0) twoSums:: should return values for not o                         rdered elements FAILED
        Expected undefined to equal [ 6, 1 ].
            at <Jasmine>
            at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:13:85)
            at <Jasmine>
    × should return values for not ordered elements
HeadlessChrome 0.0.0 (Windows 10 0.0.0) twoSums:: should correct work if "0" exi                         sted in the array FAILED
        Expected undefined to equal [ 0, 1 ].
            at <Jasmine>
            at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:23:79)
            at <Jasmine>
    × should correct work if "0" existed in the array
HeadlessChrome 0.0.0 (Windows 10 0.0.0) twoSums:: should correct work with negat                         ive values FAILED
        Expected undefined to equal [ -9, 4 ].
            at <Jasmine>
            at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:28:81)
            at <Jasmine>
    × should correct work with negative values
HeadlessChrome 0.0.0 (Windows 10 0.0.0) sumElements:: should convert string to n                         umber if it possible and return sum FAILED
        Expected undefined to be 3.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sumElements/index.spec.js?:14:87                         )
            at <Jasmine>
        Expected undefined to be 2.5.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sumElements/index.spec.js?:15:81                         )
            at <Jasmine>
        Expected undefined to be 25.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sumElements/index.spec.js?:16:85                         )
            at <Jasmine>
  sumElements::
    × should convert string to number if it possible and return sum
HeadlessChrome 0.0.0 (Windows 10 0.0.0) sumElements:: should ignore -Infinity/In                         finity FAILED
        Expected undefined to be 3.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sumElements/index.spec.js?:21:86                         )
            at <Jasmine>
    × should ignore -Infinity/Infinity
HeadlessChrome 0.0.0 (Windows 10 0.0.0) sumElements:: should ignore NaN FAILED
        Expected undefined to be 2.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sumElements/index.spec.js?:26:82                         )
            at <Jasmine>
    × should ignore NaN
HeadlessChrome 0.0.0 (Windows 10 0.0.0) sumElements:: should return sum of the a                         rray elements FAILED
        Expected undefined to be 3.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sumElements/index.spec.js?:8:76)
            at <Jasmine>
        Expected undefined to be 3.
            at <Jasmine>
            at UserContext.it (webpack:///./src/sumElements/index.spec.js?:9:78)
            at <Jasmine>
    × should return sum of the array elements

Finished in 0.069 secs / 0.024 secs @ 20:26:31 GMT+0300 (Финляндия (лето))

SUMMARY:
√ 0 tests completed
× 28 tests failed

FAILED TESTS:
  sum::
    × should throw error if one of arguments is Infinity
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected function to throw an exception.
        at <Jasmine>
        at UserContext.it (webpack:///./src/sum/index.spec.js?:21:87)
        at <Jasmine>

    × should throw error if at least one of arguments is not a number
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected function to throw an exception.
        at <Jasmine>
        at UserContext.it (webpack:///./src/sum/index.spec.js?:14:82)
        at <Jasmine>

    × should return sum of arguments if they are numbers
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to be 3.
        at <Jasmine>
        at UserContext.it (webpack:///./src/sum/index.spec.js?:8:74)
        at <Jasmine>

    × should throw error if one of arguments is NaN
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected function to throw an exception.
        at <Jasmine>
        at UserContext.it (webpack:///./src/sum/index.spec.js?:27:82)
        at <Jasmine>

  getFlags::
    × Should return array of flags for passed array with any size
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal [ 1, 2, 3 ].
        at <Jasmine>
        at UserContext.it (webpack:///./src/getFlags/index.spec.js?:22:76)
        at <Jasmine>

    × Should return array of flags
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal [ 1, 2, 3 ].
        at <Jasmine>
        at UserContext.it (webpack:///./src/getFlags/index.spec.js?:13:73)
        at <Jasmine>

  isObject::
    × Should return false for primitive values
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal false.
        at <Jasmine>
        at UserContext.it (webpack:///./src/isObject/index.spec.js?:23:71)
        at <Jasmine>

    × Should return false for null
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal false.
        at <Jasmine>
        at UserContext.it (webpack:///./src/isObject/index.spec.js?:18:74)
        at <Jasmine>

    × Should return false for array literal []
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal false.
        at <Jasmine>
        at UserContext.it (webpack:///./src/isObject/index.spec.js?:13:72)
        at <Jasmine>

    × Should return true for object literal {}
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal true.
        at <Jasmine>
        at UserContext.it (webpack:///./src/isObject/index.spec.js?:8:72)
        at <Jasmine>

  truncate::
    × should truncate string
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal 'Some...'.
        at <Jasmine>
        at UserContext.eval (webpack:///./src/truncate/index.spec.js?:8:89)
        at <Jasmine>

    × should not truncate string if it`s empty
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal ''.
        at <Jasmine>
        at UserContext.eval (webpack:///./src/truncate/index.spec.js?:13:72)
        at <Jasmine>

    × should not truncate string if second parameter "length" grater than string                         .length
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal 'Some very long text'.
        at <Jasmine>
        at UserContext.eval (webpack:///./src/truncate/index.spec.js?:23:95)
        at <Jasmine>

    × should allow to pass replacer
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal 'Hello wo***'.
        at <Jasmine>
        at UserContext.eval (webpack:///./src/truncate/index.spec.js?:18:93)
        at <Jasmine>

  max::
    × Should ignore -Infinity/Infinity
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to be 1.
        at <Jasmine>
        at UserContext.it (webpack:///./src/max/index.spec.js?:13:83)
        at <Jasmine>

    × Should return max number value from array
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to be 3.
        at <Jasmine>
        at UserContext.it (webpack:///./src/max/index.spec.js?:8:83)
        at <Jasmine>

    × Should ignore NaN
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to be 2.
        at <Jasmine>
        at UserContext.it (webpack:///./src/max/index.spec.js?:18:81)
        at <Jasmine>

  turnMeBaby::
    × should throw error if passed not a string
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal Error: this is not a string.
        at <Jasmine>
        at UserContext.eval (webpack:///./src/turnMeBaby/index.spec.js?:15:71)
        at <Jasmine>

    × should reverse string
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal 'olleh'.
        at <Jasmine>
        at UserContext.eval (webpack:///./src/turnMeBaby/index.spec.js?:8:77)
        at <Jasmine>

  twoSums::
    × should return values of elements which sum equals "base" parameter
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal [ 1, 2 ].
        at <Jasmine>
        at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:8:79)
        at <Jasmine>

    × should return only first elements which sum equals "base" parameter
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal [ 12, 3 ].
        at <Jasmine>
        at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:18:87)
        at <Jasmine>

    × should return values for not ordered elements
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal [ 6, 1 ].
        at <Jasmine>
        at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:13:85)
        at <Jasmine>

    × should correct work if "0" existed in the array
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal [ 0, 1 ].
        at <Jasmine>
        at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:23:79)
        at <Jasmine>

    × should correct work with negative values
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to equal [ -9, 4 ].
        at <Jasmine>
        at UserContext.eval (webpack:///./src/twoSums/index.spec.js?:28:81)
        at <Jasmine>

  sumElements::
    × should convert string to number if it possible and return sum
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to be 3.
        at <Jasmine>
        at UserContext.it (webpack:///./src/sumElements/index.spec.js?:14:87)
        at <Jasmine>

    × should ignore -Infinity/Infinity
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to be 3.
        at <Jasmine>
        at UserContext.it (webpack:///./src/sumElements/index.spec.js?:21:86)
        at <Jasmine>

    × should ignore NaN
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to be 2.
        at <Jasmine>
        at UserContext.it (webpack:///./src/sumElements/index.spec.js?:26:82)
        at <Jasmine>

    × should return sum of the array elements
      HeadlessChrome 0.0.0 (Windows 10 0.0.0)
    Expected undefined to be 3.
        at <Jasmine>
        at UserContext.it (webpack:///./src/sumElements/index.spec.js?:8:76)
        at <Jasmine>

13 09 2018 20:26:31.606:DEBUG [karma]: Run complete, exiting.
13 09 2018 20:26:31.607:DEBUG [launcher]: Disconnecting all browsers
13 09 2018 20:26:31.611:DEBUG [launcher]: Process ChromeHeadless exited with cod                         e 0
13 09 2018 20:26:31.611:DEBUG [temp-dir]: Cleaning temp dir C:\Users\Kefir\AppDa                         ta\Local\Temp\karma-68747616
13 09 2018 20:26:31.736:DEBUG [launcher]: Finished all browsers
npm ERR! Test failed.  See above for more details.
