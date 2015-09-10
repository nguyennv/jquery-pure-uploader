# Introduction #

The following outlines how to add Pure Uploader to any element within the page. All content will be added to this element.

# Embedding Pure Uploader Into a Webpage #

```
<script lang="JavaScript" src="pure-uploader/jquery-1.4.2.js"></script>
<script lang="JavaScript" src="pure-uploader/jquery.pure-uploader-1.0.0.js"></script>
<link rel="stylesheet" href="pure-uploader/jquery.pure-uploader-1.0.0.css" />
```

# Example Usage #

```
$('#elem').pureUploader({
   'url': '/upload.jsp',
   'uploadAverageSpeed': true, // if true, displays the average speed, otherwise the speed at each tick is displayed.  
   'sizeLimit' : 2 * 1024 * 1024 // 2MB 
});
```