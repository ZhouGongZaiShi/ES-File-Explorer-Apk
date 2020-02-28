# ES-File-Explorer-Apk
[Normal Apk](http://www.estrongs.com/?lang=en#/) and [Amazon AppStore Apk]().

Amazon AppStore Apk contains code injected by Amazon AppStore. For example `com.amazon.android.Kiwi` and `com.amazon.android.framework.prompt.SimplePrompt`.

If you need to read amazon injected code, you can decompile two apk and compare them.

I fixed [Android app crash is crashing when clients trying to call Context.getPackageName(), throw NullPointerException](https://forums.developer.amazon.com/questions/222774/android-app-crash-is-crashing-when-clients-trying-1.html)] using reflection by reading amazon injected code.
