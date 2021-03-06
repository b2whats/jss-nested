## 2.4.1 / 2016-09-19

- allow "-" in refs
- better tests
- on index mutation

## 2.4.0 / 2016-09-13

- enable @media rules inside of regular rules

## 2.2.1 / 2016-09-07

- don't use es6 in tests.webpack.js, because it is loaded from jss without babelifying

## 2.2.0 / 2016-09-05

- upgrade jss to 5.5.0
- fix the order of extracted nested rules
- deprecate nesting level is higher than 1 (was never fully supported)
- warn if nesting level is too high
- migrate to mocha

## 2.1.0 / 2016-08-15

- allow `sheet.addRule` on attached sheet use nested rules

## 2.0.0 / 2016-07-31

- implelent local refs using $ref syntax #214
- update deps

## 1.0.3 / 2016-03-24

- update babel deps

## 1.0.2 / 2016-01-31

- docs
- update linter and lint
- fix nested rules within conditionals

## 1.0.1 / 2015-10-21

- fix peer dependency

## 1.0.0 / 2015-10-19

- support jss 3.0
- now plugin needs to be called middleware like

## 0.2.0 / 2015-09-21

- migrate to es6
- move examples to jss-examples repository
- simplify packaging

## 0.1.7 / 2014-02-06

- support nesting within a named rule

## 0.1.6 / 2014-01-31

- update jss to 1.0

## 0.1.0 / 2014-11-28

- first release in a separate repository for plugins
