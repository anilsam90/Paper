Change Log
==========

Version 2.0 *(2016-10-24)*
----------------------------

* Update internal Kryo serializer to 4.0. The data format is changed, but Paper supports backward data compatibility automatically;
* Now 58% less methods count : [4037](http://www.methodscount.com/?lib=io.paperdb%3Apaperdb%3A2.0);
* Depends on data structure you may experience faster reading but slower writing.


Version 1.5 *(2016-04-28)*
----------------------------

 * Save all the things! No more restriction to use classes only having no-arg constructor.
 * Custom serializers can be added using `Paper.addSerializer()`.
 * Kotlin is fully supported now, including saving `data class`es. Saving lambdas is not supported.


Version 1.1 *(2015-11-27)*
----------------------------

 * New ```Paper.book().getAllKeys()``` api
 * Proguard config for lib itself is included in aar.


Version 1.0 *(2015-09-15)*
----------------------------

 * New multi-book API.
 * 0.9 API is still supported and marked as deprecated.
 * Unsafe possibility to write null values is disabled.

 *NOTE:* Data storage format is unchanged. You can easily use files created within version 0.9.