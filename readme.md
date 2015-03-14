Gooy Angular Code Component
=======

[![GitHub version](https://badge.fury.io/gh/gooy%2Fgooy-angular-demo.svg?style=flat-square)](http://badge.fury.io/gh/gooy%2Fgooy-angular-demo)
[![Build Status](https://travis-ci.org/gooy/gooy-angular-demo.svg?branch=master&style=flat-square)](https://travis-ci.org/gooy/gooy-angular-demo)
[![Dependency Status](https://david-dm.org/gooy/gooy-angular-demo.svg?style=flat-square)](https://david-dm.org/gooy/gooy-angular-demo)
[![devDependency Status](https://david-dm.org/gooy/gooy-angular-demo/dev-status.svg?style=flat-square)](https://david-dm.org/gooy/gooy-angular-demo#info=devDependencies)  
[![ES6 format](https://img.shields.io/badge/JS_format-es6-orange.svg?style=flat-square)](http://www.ecmascript.org/)
[![JSPM](https://img.shields.io/badge/JSPM-gooy/gooy--angular--demo-db772b.svg?style=flat-square)](http://jspm.io)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](http://opensource.org/licenses/MIT)

Code component for [gooy-angular](http://github.com/gooy/gooy-angular).

## Installation

    jspm install gooy/gooy-angular-code

## Usage

Register it with the framework.


    gooy.withComponent("gooy-angular-code");


Add the `ui-code` attribute to a pre tag.  
The `beautify` attribute can also be added to beautify the code before it is hightlighted.


    <pre class="language--javascript" ui-code>
    function foo(){
        console.log("bar");
    }
    </pre>


A template tag can be used to supply inert html.  
the template tag itself will not be included in the code preview.


    <pre class="language--markup" ui-code beautify>
    <template>
       <input type="text" ng-model="name"/>
       <p>
           Name: {{name}}
       </p>
    </template>
    </pre>

