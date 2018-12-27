# \<product-list\>
[![Build Status](https://travis-ci.com/jusolete/product-list.svg?branch=master)](https://travis-ci.com/jusolete/product-list)
## Install bower
```
$ npm i bower
```

## run bower install
```
$ npm i bower
```
## variables in product-list

```
products:Array // determines the products that will be displayed

serverUrl: String // determines the get request direction for the products 

language:Object   //determines the language of the button labels

searchLanguage:Object //determines the language of the search component label

filterValue:String //value recieved from on-search-product event from the productsearch-element it determines dynamic filter parameters for the dom-repeat

hiddenSearch:Boolean // true for hiding the search component default (false)



```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
