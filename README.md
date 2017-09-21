Install dependencies:

```
Install Java JDK for ClosureCompiler, node LTE > 6.9.0, python for Selenium Webdriver
npm i -g angular-rollup webdriver-manager codelyzer rimraf
npm install
```

Run the build:
```
ngr build prod --closure --lazy --serve
```