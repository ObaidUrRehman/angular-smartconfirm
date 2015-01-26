# Angular Smart Confirm

Angular smart confirm is a customizable UI component for angular that replaces the need to show a pop up confirm box where a user confirmation is required. This smart confirm shows the yes and no confirm buttons in-line. No more bothering the user with those pop-ups that can some times become a bit annoying.

![alt tag](http://obaidurrehman.github.io/angular-smartconfirm/demo/demo.gif)


    

## Setup

You need to include bootstrap and fontawesome css since smart confirm is dependent on it:

```
<link href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css" rel="stylesheet">
<link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">
```

In your document header include the following javascript.

```
<script src="/bower_components/angular-smartconfirm/src/angular-smartconfirm.js"></script>
```

## Usage
In your AngularJS app, you'll need to import the `angular-smartconfirm` module:

`angular.module('myModule', ['angular-smartconfirm']);`

Now you can use the `angular-smartconfirm` directive in the following manner:

`<angular-smartconfirm confirm="delete(item)"><i class="fa fa-close"></i></smart-confirm>`

## Properties
None at the moment. I  plan to add more customization options in later commits. Stuff like custom css styling etc.

## Demo

You can check out the demo [here](http://obaidurrehman.github.io/angular-smartconfirm/demo/smart-confirm.html)




