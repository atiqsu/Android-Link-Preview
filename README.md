LeoCardz Link Preview for Android
=================================

This a version for Android of my web [Facebook Link Preview](http://lab.leocardz.com/facebook-link-preview-php--jquery/ "Facebook Link Preview").

It makes a preview from an url, grabbing all informations. Such as title, relevant texts and images.

For more information about this, please access [Android Link Preview](http://android.leocardz.com/android-link-preview/ "Android Link Preview").

For a sample app, please install it from [Android Link Preview on Google Play](https://play.google.com/store/apps/details?id=com.leocardz.link.preview&feature=search_result "Android Link Preview on Google Play").

In this project, I have added some libs.

Note - Required Libs: [jsoup](http://jsoup.org/ "jsoup") is a smart lib to crawl the htlm code. [UrlImageViewHelper](https://github.com/koush/UrlImageViewHelper "UrlImageViewHelper") is an optimized lib for url images.


## How to use with Gradle

Simply add the repository to your build.gradle file:
```groovy
repositories {
	jcenter()
	maven { url 'https://github.com/leonardocardoso/mvn-repo/raw/master/maven-deploy' }
}
```

And you can use the artifacts like this:
```groovy
dependencies {
	compile 'com.leocardz:link-preview:1.1@aar'
	// ...
}
```

Apps using Android Link Preview
=================================
1. [Unshorten It](https://play.google.com/store/apps/details?id=com.leocardz.url.unshortener&feature=search_result "Unshorten It")

2. [Webbox](https://play.google.com/store/apps/details?id=com.leocardz.webbox&feature=search_result "Webbox")

3. ...


Contact
=================================
If you are using this lib, let me know contacting me at android@leocardz.com then I add your app here in a list


License
=================================

    Copyright 2013 Leonardo Cardoso

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
