This is a template project for Android Studio that allows you to create an android webview application in minutes. You can use it to create a simple app for your website or as a starting point for your HTML5 based android app.

Getting started

Using a remote source
If you want to create an app that shows the content of a remote website

line 24 in MainActivity.java --> replace https://admstore.cz with your url

mWebView.loadUrl("https://admstore.cz");
open the MyWebViewClient.java file and replace admstore.cz on line 15 with your hostname

hostname = "admstore.cz";
Using a local source
If you want to create a local HTML5 android app

uncomment line 27 in MainActivity.java

mWebView.loadUrl("file:///android_asset/index.html");
put all your files (including your index.html) in the assets directory
