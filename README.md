# tochyodikwa-easy_webapp_andriod_studio

EASY WAY TO CONVERT YOUR WEBSITE INTO A SIMPLE ANDROID APPLICATION 

Follow the steps below: 

step1: create an empty project in android studio IDE make sure the minimum SDK is set to "api level 23 Android 6.0 (marshmellow)"

step2: after your project loads go to android manifest tab, change it to code view and delete everything

step3: use the green "code" button to download the source codes on my gitbub page, download, extract and locate "android manifest xml" folder or click on the "android manifest xml" folder on my github page

step 4: open the "AndroidManifest.xml" file copy the contents of the code into the empty andriod manifest tab in android studio

step 5: locate the "java source file" folder on my github page or in your extracted zip folder, open the "MainActivity.java" file

step 6: go to the "MainActivity" tab in android studio delete everything then copy and paste the code from MainActivity.java into the empty main activity tab in android studio

step 7: locate and replace "put your website link here" with your website url when you see it in this code section below:


   @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        CustomWebViewClient client = new CustomWebViewClient(this);

        webView = findViewById(R.id.webView);
        webView.setWebViewClient(client);
        webView.getSettings().setJavaScriptEnabled(true);

        webView.loadUrl("put your website here");

step 8: replace package com.tochy.webapp; which is the first line of code on the MainActivity tab with your own package name
note: make sure to delete the android manifest xml and java source file folder if you want to load the project direclty into android studio

step 9: sign, compile and have fun testing it out
