# Getting started with Polymer 1.0

## What is Polymer?
The Polymer is a library designed to make it easier and faster for developers to create great, reusable components for the modern web. [Read more...](https://www.polymer-project.org/1.0/docs/start/what-is-polymer.html)

## Getting Polymer library
The easiest way to install Polymer is through Bower, a package manager for the web. Rob Dodson, a developer advocate at Google has uploaded an excellent video for [Setting up Bower and Polymer](https://youtu.be/1rz334A8U7o).

If you already have Bower set up, you can check [Installing with Bower](https://www.polymer-project.org/1.0/docs/start/getting-the-code.html#using-bower).
Optionally, you can [Install Polymer from ZIP files](https://www.polymer-project.org/1.0/docs/start/getting-the-code.html#using-zip).

## Installing Polymer with Bower
Create <code>bower.json</code> file at the root of the project with the command:
```
bower init
```

Install Polymer with the command:
```
bower install --save polymer
```

It is mandatory to use <code>--save</code> flag with <code>bower install</code> because it updates <code>bower.json</code> file. This is done to exclude the dependencies while distributing and maintaining the source code. The dependencies can be easily fetched using the command:
```
bower install
```

Which grabs the dependencies listed in the <code>bower.json</code> file.

Add <code>.gitignore</code> file to ignore all the files and folder in <code>bower_components/</code> folder.
