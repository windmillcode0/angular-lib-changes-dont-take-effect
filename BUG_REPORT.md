# [TITLE HERE]

## Links to issue
*[Github]()

## Expected Behavior
consumer should recongize the changes in the lib and reload


## Current Behavior
consumer does not recognize the changes in the lib and reload



## Possible Solution
Simplyfy change detection logic with libraries




## Steps to Reproduce


1. Create consumer
2. create lib
<!-- in lib -->
3. ng build --watch
4. npm link
<!-- in consumer -->
5. npm link my-lib
6. npm run start
7. make changes in lib
8. consumer does not recognize the changes in the lib and reload

## Environment
Angular CLI: 17.2.0
Node: 20.11.0
Package Manager: npm 10.2.4
OS: win32 x64

Angular: 17.2.1
... animations, common, compiler, compiler-cli, core, forms
... platform-browser, platform-browser-dynamic, router

Package                         Version
---------------------------------------------------------
@angular-devkit/architect       0.1702.0
@angular-devkit/build-angular   17.2.0
@angular-devkit/core            17.2.0
@angular-devkit/schematics      17.2.0
@angular/cli                    17.2.0
@schematics/angular             17.2.0
rxjs                            7.8.1
typescript                      5.3.3
zone.js                         0.14.4

## Files


## Detailed Description

## Possible Implementation


## Additional Issues
