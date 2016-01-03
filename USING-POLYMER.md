# Using Polymer elements
Polymer allows you to create custom elements but to use Polymer you don't have to create custom elements at all! You can entirely use Polymer element sets from the [Polymer Catalog](https://elements.polymer-project.org/) to get your job done.

## Creating files
Use the template below to create your files.

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Adding polyfill support. -->
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>

    <!-- Import elements to be used -->

  </head>
  <body>
    <!-- Use elements -->

  </body>
</html>
```

## Installing elements
The element needs to be installed in order to be used. The [Polymer Catalog]() contains <code>bower</code> command to install the element the element description.
To install <code>paper-card</code> element the command is:

```
bower install --save PolymerElements/paper-card
```

Add the following lines to your file

```html
<!-- Import elements to be used -->
<link rel="import" href="bower_components/paper-card/paper-card.html">
```

```html
<!-- Use elements -->
<paper-card heading="Hello World"></paper-card>
```
Start your web server and locate to your file.

You have successfully used Polymer elements. :)
