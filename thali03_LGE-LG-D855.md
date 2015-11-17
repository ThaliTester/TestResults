#### Test 50388019549d4ab_thali03_LGE-LG-D855 Logs

--------- beginning of system
--------- beginning of main
,D/ActivityThread( 4479): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
D/ActivityThread( 4479): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/jxcore-log( 4414): Initializing JXcore engine
W/jxcore-log( 4414): JXcore engine is ready
W/jxcore-log( 4414): Starting JXcore engine
,E/ActivityThread( 4479): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@e93e54 that was originally bound here
E/ActivityThread( 4479): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@e93e54 that was originally bound here
E/ActivityThread( 4479): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 4479): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 4479): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 4479): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 4479): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4479): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 4479): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 4479): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 4479): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 4479): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 4479): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 4479): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 4479): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4479): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4479): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4479): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/jxcore-log( 4414): Platform android
W/jxcore-log( 4414): 
W/jxcore-log( 4414): Process ARCH arm
W/jxcore-log( 4414): 
,I/jxcore-log( 4414): JXcore Cordova bridge is ready!
I/jxcore-log( 4414): 
,W/jxcore-log( 4414): JXcore engine is started
,E/jxcore-log( 4414): >> LGE-LG-D855
E/jxcore-log( 4414): 
I/jxcore-log( 4414): Total memory 2995761152
I/jxcore-log( 4414): 
I/jxcore-log( 4414): Free memory 896798720
I/jxcore-log( 4414): 
I/jxcore-log( 4414): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4414): 
I/jxcore-log( 4414): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): userPath [ 'www' ]
I/jxcore-log( 4414): 
I/jxcore-log( 4414): Size 1440 2392
I/jxcore-log( 4414): 
I/jxcore-log( 4414): Screen Brightness 50
I/jxcore-log( 4414): 
E/jxcore-log( 4414): Dummy Error Log.
E/jxcore-log( 4414): 
,I/jxcore-log( 4414): getBuffer is called!!!!
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): ****TEST TOOK:  5029  ms ****
I/jxcore-log( 4414): 
I/jxcore-log( 4414): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4414): 
,W/ActivityThread( 5057): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
