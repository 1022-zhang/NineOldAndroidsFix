Nine Old Androids Fix
=================

> 注：该开源库原代码来源于JakeWharton 大神的 Nine Old Androids 动画库，本人仅针对AndroidStudio环境修改发布，原代码已停止更新
>



#### gradle依赖

```groovy
 compile 'com.nineoldandroids:library:2.4.0'
```

#### jar 依赖

将jar包：`nineoldandroids-2.4.0.jar` 置于libs目录



Nine Old Androids
=================

Android library for using the [Honeycomb (Android 3.0) animation API][1] on all
versions of the platform back to 1.0!

Note: `LayoutTransition` is present and it is not be possible to implement prior
to Android 3.0.



Usage
=====

The API is exactly the same as the [Honeycomb API][2], just change your imports
to use `com.nineoldandroids.XXX`.

Take a look at a few demos taken from the [platform ApiDemos][3] in the
`sample/` folder. You can also try it out on the [Play Store][4].

More information is available on [nineoldandroids.com][6].


Including In Your Project
-------------------------

This library is presented as a `.jar` file which you can include in the `libs/`
folder of your application. You can download the latest version from the
[GitHub downloads page][5].

If you are a Maven user you can easily include the library by specifying it as
a dependency:

    <dependency>
      <groupId>com.nineoldandroids</groupId>
      <artifactId>library</artifactId>
      <version>2.4.0</version>
    </dependency>

Developed By
Developed By
Developed By
============

* Jake Wharton - <jakewharton@gmail.com>



License
=======

    Copyright 2012 Jake Wharton
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
       http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

[1]: http://android-developers.blogspot.com/2011/02/animation-in-honeycomb.html
[1]: http://android-developers.blogspot.com/2011/02/animation-in-honeycomb.html
[1]: http://android-developers.blogspot.com/2011/02/animation-in-honeycomb.html
[2]: http://developer.android.com/reference/android/view/animation/package-summary.html
[3]: http://developer.android.com/resources/samples/ApiDemos/src/com/example/android/apis/animation/index.html
[4]: https://play.google.com/store/apps/details?id=com.jakewharton.nineoldandroids.sample
[5]: https://github.com/JakeWharton/NineOldAndroids/downloads
[6]: http://nineoldandroids.com
