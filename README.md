sublime-grunt
=============

> Grunt commands and snippets for Sublime Text 3.

*__Please note:__ I am just starting to use Grunt and since I am a big beliver in __DRY__ I started to create snippets in this package whenever I had to look up some Grunt specific stuff while developing.*


Snippets
--------

*Grunt for Sublime Text* contains snippets for a wide range of Grunt plugins.

- [General](#general)
- [PHP_CodeSniffer](#php_codesniffer)
- [PHPUnit](#phpunit)
- [Sass](#sass)
- [Shell](#shell)

### General

Snippets for core functionality of Grunt.

<table>
    <thead>
        <tr>
            <th>Snippet</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>grunt-register</code></td>
            <td>Register task</td>
        </tr>
    </tbody>
</table>

### PHP_CodeSniffer

Snippets for [grunt-phpcs](https://github.com/SaschaGalley/grunt-phpcs).

<table>
    <thead>
        <tr>
            <th>Snippet</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>grunt-phpcs</code></td>
            <td>Base template for PHP_CodeSniffer tasks</td>
        </tr>
        <tr>
            <td><code>grunt-phpcs-checkstyle</code></td>
            <td>Execute PHP_CodeSniffer</td>
        </tr>
        <tr>
            <td><code>grunt-phpcs-checkstyle-symfony2</code></td>
            <td>Execute PHP_CodeSniffer with options for Symfony2 projects</td>
        </tr>
    </tbody>
</table>

### PHPUnit

Snippets for [grunt-phpunit](https://github.com/SaschaGalley/grunt-phpunit).

<table>
    <thead>
        <tr>
            <th>Snippet</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>grunt-phpunit</code></td>
            <td>Base tempplate for PHPUnit tasks</td>
        </tr>
        <tr>
            <td><code>grunt-phpunit-test</code></td>
            <td>Execute PHPUnit</td>
        </tr>
        <tr>
            <td><code>grunt-phpunit-coverage-clover</code></td>
            <td>Execute PHPUnit code coverage with clover output</td>
        </tr>
        <tr>
            <td><code>grunt-phpunit-coverage-html</code></td>
            <td>Execute PHPunit code coverage with HTML output</td>
        </tr>
        <tr>
            <td><code>grunt-phpunit-coverage-php</code></td>
            <td>Execute PHPUnit code coverage with serialized PHP output</td>
        </tr>
        <tr>
            <td><code>grunt-phpunit-coverage-text</code></td>
            <td>Execute PHPUnit code coverage with text output</td>
        </tr>
    </tbody>
</table>

### Sass

Snippets for [grunt-sass](https://github.com/sindresorhus/grunt-sass).

<table>
    <thead>
        <tr>
            <th>Snippet</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>grunt-sass</code></td>
            <td>Base template for Sass tasks</td>
        </tr>
        <tr>
            <td><code>grunt-sass-files</code></td>
            <td>Execute Sass with files array</td>
        </tr>
    </tbody>
</table>

### Shell

Snippets for [grunt-shell](https://www.npmjs.org/package/grunt-shell).

<table>
    <thead>
        <tr>
            <th>Snippet</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>grunt-shell</code></td>
            <td>Base template for shell tasks</td>
        </tr>
        <tr>
            <td><code>grunt-shell-foe</code></td>
            <td>Execute command and fail on error</td>
        </tr>
        <tr>
            <td><code>grunt-shell-stdout</code></td>
            <td>Execute command and print to stdout</td>
        </tr>
        <tr>
            <td><code>grunt-shell-stdout-foe</code></td>
            <td>Execute command and print to stdout and fail on error</td>
        </tr>
    </tbody>
</table>


Author
------

- [Florian Eckerstorfer](http://florian.ec) ([Twitter](http://twitter.com/Florian_), [App.net](http://app.net/florian))


License
-------

The MIT License (MIT)

Copyright (c) 2014 Florian Eckerstorfer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
