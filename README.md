# Oraunverulegur
##### Voice recording demo.

Make sure that following permissions are placed in the manifest file.
```
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.RECORD_AUDIO" />
```
And then go to Settings->Apps->{Your recording app} and make sure that these permissions are indeed granted.
It may happen so that they are disableed by default and you will get RunTimeException on MediaRecorder#setAudioSource(...) call.

Check yo' self.
