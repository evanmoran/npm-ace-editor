npm-ace-editor
==============

An npm module for Ace. The version of the module will match the version of the released source.

The `ace-editor` module:

    require('ace-editor');

For syntax highlighting download the [mode and theme here](https://github.com/ajaxorg/ace-builds/tree/master/src-min-noconflict):

Example Ace usage to get you going:

HTML:

    <div id="the-code">
      function foo(items) {
        var x = "All this is syntax highlighted";
        return x;
      }
    </div>

Javascript:

    var editor1 = ace.edit("the-code");
    editor1.setTheme("ace/theme/solarized_light");
    editor1.session.setMode("ace/mode/javascript");

The paths above will be determined by where you include the mode and theme.

For more info about Ace see [the website](http://ace.ajax.org/).

Also, take a look at [the OJ AceEditor plugin](http://github.com/ojjs/oj.AceEditor). It makes using Ace much easier.
