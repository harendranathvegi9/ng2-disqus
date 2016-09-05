# Angular 2 Disqus [![npm](https://img.shields.io/npm/v/ng2-awesome-disqus.svg?maxAge=2592000?style=plastic)](https://github.com/MurhafSousli/ng2-awesome-disqus) [![Build Status](https://travis-ci.org/MurhafSousli/ng2-disqus.svg?branch=master)](https://travis-ci.org/MurhafSousli/ng2-disqus) [![npm](https://img.shields.io/npm/dt/ng2-awesome-disqus.svg?maxAge=2592000)](https://www.npmjs.com/package/ng2-awesome-disqus)


![Angular 2 Share Buttons cover](/assets/cover.PNG?raw=true "Optional Title")

Angular 2 Disqus comment system | [live demo](https://murhafsousli.github.io/ng2-awesome-disqus/)

## Installation

Install it with npm

`npm install ng2-awesome-disqus --save`

## Basic usage:

```
<disqus [shortname]="disqusShortname" [identifier]="pageIdentifier" ></disqus>
```

## Advanced usage:

It's highly recommended to read the official Disqus docs [JavaScript configuration variables](https://help.disqus.com/customer/portal/articles/472098-javascript-configuration-variables) before setting these inputs.

```
<disqus [shortname]="disqusShortname" [identifier]="pageIdentifier" 
    [url]="customUrl" [categoryId]="catId" [lang]="'en'"
      
    [removeOnDestroy]="true"
  ></disqus>
```

by default the component will reset Disqus configuration when it initializes again, to remove Disqus script completely on component destroy, set `[removeOnDestroy]="true"`

## Issues


If you identify any errors in this component, or have an idea for an improvement, please open an [issue](https://github.com/MurhafSousli/ng2-awesome-disqus/issues). I am excited to see what the community thinks of this project, and I would love your input!

## Author

 **Murhaf Sousli**

 - [github/murhafsousli](https://github.com/MurhafSousli)
 - [twitter/murhafsousli](https://twitter.com/MurhafSousli)

## License

[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](/LICENSE)