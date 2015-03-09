# Notepad++ WebEdit-Config-File-For-Bootstrap
A set of the most commonly used Bootstrap components and CSS combinations with hotkey shortcuts.

By default, WebEdit contains a Config file that has some tags. These are replaced by some snippets when you use the replace key. The replace key is set to Alt+Enter by default.

For example, writing *h1*, then pressing *Alt+Enter*, would result in: 

```html
<h1></h1>
```

If you would like to create an HTML file with Bootstrap resources loaded. All you need to do is type *bsHead* followed by *Alt+Enter*, this will result in:

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta name="description" content="Page meta description goes here">
	<meta name="keywords" content="keywords, goes, here">
	<meta name="author" content="Mohamed Elgharabawy">

	<title>Page Title</title>

	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
</head>
<body>
	
</body>
</html>
```

Another example for a Bootstrap commonly used task is creating rows and columns. Using this configuration file, if you wrote *bsRowCol12lg*, then pressed *Alt+Enter*, you would get the following:

```html
<div class="row">
	<div class="col-lg-12">
		
	</div>
</div>
```

**It is really as easy as that and it saves a lot of time!**

For a full list of the tags, kindly refer to the configuration file itself.

I have been using Bootstrap a lot recently and I needed something that would make creating all the usual website components faster. This configuration file has tags for forms, columns, navbars, .. etc.

## Setup

To get started using this, start your notepad++. If you have WebEdit plugin, go to WebEdit menu under the Plugins menu and select the Edit Config option. This will open the configuration file you currently have. Copy the contents of the configuration file I have included in this repository, and you are good to go! Remember to Load the configuration again for the new tags to be identified.

If you do not have WebEdit installed, install it first from the Plugins Manager under Plugins then carry on with the steps mentioned above.

### Issues & Requests

All inquiries are very welcomed!
