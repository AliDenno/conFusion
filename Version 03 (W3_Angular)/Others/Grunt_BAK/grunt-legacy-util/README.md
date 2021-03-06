# grunt-legacy-util
> deprecated utilities from grunt

[![Build Status: Linux](https://travis-ci.org/gruntjs/grunt-legacy-util.svg?branch=master)](https://travis-ci.org/gruntjs/grunt-legacy-util)
[![Build status: Windows](https://ci.appveyor.com/api/projects/status/63a5pjh5hy0wgtx0/branch/master?svg=true)](https://ci.appveyor.com/project/gruntjs/grunt-legacy-util/branch/master)
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.svg)](http://gruntjs.com/)

With the next major release of Grunt, we will no longer support these APIs.  Where possible, please use the recommended modules in their place.  If you would like to support or improve any of these APIs, please notify us when you have published a backwards compatible npm module&mdash;we will then recommend its usage here.

`grunt.util.namespace` use [getobject]  
`grunt.util.hooker` use [hooker]  
`grunt.util.async` use [async]  
`grunt.util._` use [lodash]  
`grunt.util.exit` use [exit]  
`grunt.util.callbackify`  
`grunt.util.error`  
`grunt.util.linefeed`  
`grunt.util.normalizelf`  
`grunt.util.kindOf` use [lodash]  
`grunt.util.toArray`
`grunt.util.repeat`  
`grunt.util.pluralize`  
`grunt.util.recurse` use [traverse]  
`grunt.util.spawn` use [require('child_process').spawn]  

[getobject]: https://www.npmjs.org/package/getobject
[hooker]: https://www.npmjs.org/package/hooker
[async]: https://www.npmjs.org/package/async
[lodash]: https://www.npmjs.org/package/lodash
[exit]: https://www.npmjs.org/package/exit
[traverse]: https://www.npmjs.org/package/traverse
[require('child_process').spawn]: https://nodejs.org/api/child_process.html#child_process_child_process_spawn_command_args_options
