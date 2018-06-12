SuperFreeze
===========

We are moving to GitLab!
------------------------

All development is made at https://gitlab.com/SuperFreezeApp/SuperFreeze/. 
However, the GitHub repository will serve as a mirror. You may open issues and pull requests here, if you want to, but if possible, please use the GitLab page as this makes things far simpler for us. Also the GitHub repository might be outdated.

Recently, Microsoft announced to buy GitHub. We value Microsoft's efforts to become more involved with the Open Source world but there are just too many disadvantages GitHub has now:

* It is one, central instance
* It is owned by a company that already is even more powerful (Microsoft)
* GitHub is not Open Source itself
* To host an own instance of GitHub you have to pay
* Microsoft has some other bad habits like paying too few taxes in many countries.

By the way, Google also has many of these disadvantages and we encourage everyone to use a custom ROM like [LineageOS](https://lineageos.org/) instead of the "normal" Android.

Description
-----------

An android app that makes it possible to entirely freeze all background activities of an app.
Currently, the user has to force stop apps by hand, SuperFreeze only shows the app settings page.

Greenify is another app that can do this, but it is not Open Source.

Any contributions are welcome.

SuperFreeze is not yet another task manager promising to delete 10GB of data per month or making your device 2x as fast. This is impossible. You should freeze only
* apps that you do not trust (and do not want to run in background) and 
* apps that you use very few.

If you freeze apps that you use daily, the battery of your device will drain faster and these apps will take longer to load.

Features
--------

* Works without accessibility service as this slows down the device

Contributing to SuperFreeze
------------

If you have a problem or a question or an idea or whatever, just open an issue!

If you would like to help, have a look at the issues or think about what could be improved and open an issue for it. Please tell me what you are going to do to avoid that I also implement the same thing at the same time :-)


Copying
-------

Copyright (c) 2015 axxapy
Copyright (c) 2018 Hocceruser

SuperFreeze is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

SuperFreeze is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with SuperFreeze.  If not, see <http://www.gnu.org/licenses/>.


------------------------------------------------------------------

SuperFreeze contains files distributed under the MIT license. These are licensed both under GPLv3-or-later (see above) and MIT (see below), that is, you may choose. These files are:

```
build.gradle
src/axp/tool/apkextractor/ApkListAdapter.java
src/axp/tool/apkextractor/MainActivity.kt
src/axp/tool/apkextractor/PermissionResolver.java
res/layout/list_item.xml
res/layout/activity_main.xml
res/values/strings.xml
res/values/colors.xml
res/values/styles.xml
res/values/attrs.xml
res/values-de/strings.xml
res/xml/searchable.xml
res/menu/main.xml
AndroidManifest.xml
```

The MIT License (MIT)

Copyright (c) 2015 axxapy
Copyright (c) 2018 Hocceruser

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
