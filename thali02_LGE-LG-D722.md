#### Test 503880191ef516a_thali02_LGE-LG-D722 Logs

--------- beginning of main
,--------- beginning of system
W/ActivityThread( 1874): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1874): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1874): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1874): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1874): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1874): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1874): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1874): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1874): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/jxcore-log( 3819): Initializing JXcore engine
W/jxcore-log( 3819): JXcore engine is ready
,W/jxcore-log( 3819): Starting JXcore engine
W/ActivityThread( 4008): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/jxcore-log( 3819): Platform android
W/jxcore-log( 3819): 
W/jxcore-log( 3819): Process ARCH arm
W/jxcore-log( 3819): 
,I/jxcore-log( 3819): JXcore Cordova bridge is ready!
I/jxcore-log( 3819): 
W/jxcore-log( 3819): JXcore engine is started
,E/jxcore-log( 3819): >> LGE-LG-D722
E/jxcore-log( 3819): 
,I/jxcore-log( 3819): Total memory 906309632
I/jxcore-log( 3819): 
I/jxcore-log( 3819): Free memory 28536832
I/jxcore-log( 3819): 
I/jxcore-log( 3819): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3819): 
I/jxcore-log( 3819): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3819): 
I/jxcore-log( 3819): userPath [ 'www' ]
I/jxcore-log( 3819): 
I/jxcore-log( 3819): Size 720 1196
I/jxcore-log( 3819): 
,I/jxcore-log( 3819): Screen Brightness 255
I/jxcore-log( 3819): 
E/jxcore-log( 3819): Dummy Error Log.
E/jxcore-log( 3819): 
,I/jxcore-log( 3819): getBuffer is called!!!!
I/jxcore-log( 3819): 
,E/ActivityThread( 4225): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@26cd238f that was originally bound here
E/ActivityThread( 4225): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@26cd238f that was originally bound here
E/ActivityThread( 4225): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4225): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4225): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4225): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4225): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4225): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4225): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4225): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4225): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4225): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4225): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4225): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4225): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/jxcore-log( 3819): ****TEST TOOK:  5079  ms ****
I/jxcore-log( 3819): 
I/jxcore-log( 3819): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3819): 
