# tochyodikwa-easy_webapp_andriod_studio
step1: create an empty project on android studio with minimum SDK set to "api level 23 Android 6.0 (marshmellow)"

step2: after your project loads go to android manifest tab, change it to code view and delete everything

step3: use the green "code" button to download the code on my gitbub page, select download zip after the download extract and locate "android manifest xml" folder 

step 4: open the "AndroidManifest.xml" file copy the contents of the code into the empty andriod manifest tab in android studio

step 5: locate the "javasourcefile" folder in your extracted zip folder, open the "MainActivity.java" file either in any suitable IDE of your chioce

step 6: go to the "MainActivity" tab in android studio delete everything then copy and paste the code from MainActivity.java into the empty main activity tab in android studio

step 7: locate the replace "put your website link here" with your website url when you see it in this code section below:


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

step 9: sign, compile and have fun testing it out
