#### Test 503880191ef516a_thali02_LGE-Nexus 5 Logs

--------- beginning of main
--------- beginning of system
D/ActivityThread( 2373): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,E/ActivityThread( 2373): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@278c41e9 that was originally bound here
E/ActivityThread( 2373): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@278c41e9 that was originally bound here
E/ActivityThread( 2373): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2373): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2373): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2373): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2373): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2373): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2373): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2373): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2373): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2373): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2373): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2373): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2373): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2373): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2373): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/jxcore-log( 2486): Initializing JXcore engine
W/jxcore-log( 2486): JXcore engine is ready
W/jxcore-log( 2486): Starting JXcore engine
,W/jxcore-log( 2486): Platform android
W/jxcore-log( 2486): 
W/jxcore-log( 2486): Process ARCH arm
W/jxcore-log( 2486): 
,I/jxcore-log( 2486): JXcore Cordova bridge is ready!
I/jxcore-log( 2486): 
W/jxcore-log( 2486): JXcore engine is started
,E/jxcore-log( 2486): >> LGE-Nexus 5
E/jxcore-log( 2486): 
,I/jxcore-log( 2486): Total memory 1946181632
I/jxcore-log( 2486): 
I/jxcore-log( 2486): Free memory 389574656
I/jxcore-log( 2486): 
I/jxcore-log( 2486): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2486): 
I/jxcore-log( 2486): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2486): 
,I/jxcore-log( 2486): userPath [ 'www' ]
I/jxcore-log( 2486): 
,I/jxcore-log( 2486): Size 1080 1776
I/jxcore-log( 2486): 
,I/jxcore-log( 2486): Screen Brightness 82
I/jxcore-log( 2486): 
E/jxcore-log( 2486): Dummy Error Log.
E/jxcore-log( 2486): 
,W/ActivityThread( 2589): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 2486): getBuffer is called!!!!
I/jxcore-log( 2486): 
,I/jxcore-log( 2486): ****TEST TOOK:  5027  ms ****
I/jxcore-log( 2486): 
I/jxcore-log( 2486): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2486): 
