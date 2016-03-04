#### Test 61699762a45f11c_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/Mms/MessagesLockscreen( 5032): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
D/Mms/MessagesLockscreen( 5032): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
W/Binder  ( 2580): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2580): android.view.InflateException: Binary XML file line #11: Error inflating class com.android.keyguard.sec.SecKeyguardTextClock
W/Binder  ( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2580): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2580): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2580): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2580): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2580): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2580): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2580): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2580): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2580): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2580): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2580): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2580): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2580): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2580): 	... 16 more
W/Binder  ( 2580): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2580): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2580): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2580): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2580): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2580): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2580): 	... 19 more
--------- beginning of /dev/log/system
D/WifiDisplayAdapter( 2404): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/JavaBinder( 2580): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2580): android.view.InflateException: Binary XML file line #11: Error inflating class com.android.keyguard.sec.SecKeyguardTextClock
E/JavaBinder( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2580): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2580): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2580): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2580): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2580): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2580): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2580): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2580): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2580): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2580): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2580): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2580): 	... 16 more
E/JavaBinder( 2580): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2580): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2580): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2580): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2580): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2580): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2580): 	... 19 more
E/CscFactoryReceiver( 2754): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 2754): Media DB Scanner finished.
D/CscFactoryReceiver( 2754): start service to Set Ringtone
W/Binder  ( 2580): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2580): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2580): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2580): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2580): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2580): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2580): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2580): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2580): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2580): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2580): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2580): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2580): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2580): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2580): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2580): 	... 16 more
W/Binder  ( 2580): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2580): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2580): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2580): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2580): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2580): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2580): 	... 19 more
E/JavaBinder( 2580): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2580): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2580): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2580): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2580): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2580): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2580): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2580): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2580): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2580): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2580): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2580): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2580): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2580): 	... 16 more
E/JavaBinder( 2580): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2580): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2580): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2580): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2580): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2580): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2580): 	... 19 more
I/ActivityManager( 2404): Waited long enough for: ServiceRecord{43030340 u0 com.sec.knox.seandroid/.service.SEAndroidLauncher}
I/CastUtils( 5091): Removing provider: MediaRouter.RouteProviderInfo{ packageName=com.google.android.gms }
I/ActivityManager( 2404): Killing 4123:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
D/dalvikvm( 2404): GC_EXPLICIT freed 962K, 13% free 23950K/27528K, paused 17ms+19ms, total 246ms
D/CscFactoryReceiver( 2754): start service to Set Notification
D/CscFactoryReceiver( 2754): start service to Set Alarmtone
D/CscUpdateService( 2754): onStart
E/CscUpdateService( 2754): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2754): only ringtone update
D/CscUpdateService( 2754): onStart
E/CscUpdateService( 2754): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2754): only notification update
D/CscUpdateService( 2754): onStart
E/CscUpdateService( 2754): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2754): only alarmtone update
E/CscParser( 2754): update(): xml file exist
E/CscParser( 2754): update(): xml file exist
I/SELinux ( 5130): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5130):  
E/CscParser( 2754): update(): xml file exist
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 10% free 9508K/10480K, paused 3ms+4ms, total 39ms
I/SELinux ( 5130): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5130):  
I/SELinux ( 5130):  
I/SELinux ( 5130): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5130): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5130): >>>>> Normal User
E/dalvikvm( 5130): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
E/SELinux ( 5130): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/CSCSettings( 2754): Setting Ringtones (type) : 4
D/CscParser( 2754): AlarmTone: null
W/CSCSettings( 2754): 1. Tag_Str: null
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9508K/10480K, paused 3ms+4ms, total 35ms
W/CSCSettings( 2754): Setting Ringtones (type) : 2
D/CscParser( 2754): MessageTone: null
W/CSCSettings( 2754): 1. Tag_Str: null
W/CSCSettings( 2754): Setting Ringtones (type) : 1
D/CscParser( 2754): RingTone: null
W/CSCSettings( 2754): 1. Tag_Str: null
D/TimaKeyStoreProvider( 5130): in addTimaSignatureService
D/TimaKeyStoreProvider( 5130): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5130): Added TimaKesytore provider
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9508K/10480K, paused 3ms+5ms, total 34ms
D/dalvikvm( 5130): GC_CONCURRENT freed 3005K, 30% free 9566K/13500K, paused 3ms+2ms, total 29ms
D/dalvikvm( 5130): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/IndexBroadcastProcessorService( 5130): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 4988): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
W/ActivityThread( 4988): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/FactoryTestApp( 4988): [XMLDataStorage$parseXML] is Live Demo : false
D/FactoryTestApp( 4988): [XMLDataStorage$parseXML] modelXML=sm-g800f.dat
D/FactoryTestApp( 4988): [XMLDataStorage$parseXML] deviceXML=kminilte.dat
D/FactoryTestApp( 4988): [XMLDataStorage$parseXML] nameXML=kminiltexx.dat
I/IndexBroadcastProcessorService( 5130): lucene systemReadyToIndex
I/IndexService( 5130): lucene onCreate ...service
I/DBG_DM  ( 4066): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 20 sec
I/Mms/MmsApp( 5032):  start initViewCache mms
I/FactoryTestApp( 4988): [XMLDataStorage$parseAsset] Convert dat file: sm-g800f.dat
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5130): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5130): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
I/dalvikvm( 5130): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 5130): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
D/dalvikvm( 5130): VFY: replacing opcode 0x71 at 0x01ed
,I/IndexService( 5130): lucene beginIndexing
D/FactoryTestApp( 4988): [XMLDataStorage$parseAsset] Decode base file: factory.dat
I/IndexService( 5130): lucene onDestroy start
I/IndexService( 5130): lucene onDestroy end
I/IndexService( 5130): lucene cleanupEverything start
I/IndexService( 5130): lucene cleanupEverything end
I/IndexService( 5130): ERROR: null
I/Process ( 5130): Sending signal. PID: 5130 SIG: 9
I/ActivityManager( 2404): Process com.samsung.indexservice (pid 5130) (adj 9) has died.
D/dalvikvm( 4988): GC_CONCURRENT freed 2527K, 26% free 10019K/13500K, paused 3ms+13ms, total 31ms
D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
D/Mms/ComposeMessageFragment( 5032): fillCache, easy = false
D/checkbox( 5032): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5032): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5032): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5032): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APP
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FAILHIST_VERSION
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=MODEL_NAME
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=MODEL_NUMBER
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=CHIPSET_NAME
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=DEVICE_TYPE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=PANEL_TYPE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_ACCELEROMETER
I/ActivityManager( 2404): Waited long enough for: ServiceRecord{4345fd68 u0 com.samsung.android.sconnect/.periph.PeriphService}
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=REAR_CAMERA_TYPE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SPEAKER_COUNT
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=MIC_COUNT
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_VIBRATOR
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_LTE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_RCV
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APO
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_NVBACKUP_CMD
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_EPEN
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_SENSORHUB
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_ISP
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_SECOND_MIC_TEST
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_IRLED_FEEDBACK_IC
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HW_VER_EFS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOK_COVER
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=NEED_LPA_MODE_SET
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=MULTI_TSK_THD
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_HOVER_HIGHTLIGHT
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FACTOLOG_SYSTEM_INFO_UPDATE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_AUTO_WAKELOCK
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_AP_EX_THERM_ADC
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=CAL_AP_TEMP
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_SELFTEST_PWC_DISPLAY
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_GLOVE_MODE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FONT_SIZE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=RAM_SIZE_IF
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_FONT_SIZE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_SEMI_FUNCTION_TEST
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_TEST_UI_ORIENTATION
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_UP
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_DOWN
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_POWER
D/AndroidRuntime( 5151): 
D/AndroidRuntime( 5151): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_APP_SWITCH
D/AndroidRuntime( 5151): CheckJNI is OFF
D/AndroidRuntime( 5151): setted country_code = Poland
D/AndroidRuntime( 5151): setted countryiso_code = PL
D/AndroidRuntime( 5151): setted sales_code = PLS
D/AndroidRuntime( 5151): readGMSProperty: start
D/AndroidRuntime( 5151): readGMSProperty: already setted!!
D/AndroidRuntime( 5151): readGMSProperty: end
D/AndroidRuntime( 5151): addProductProperty: start
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_HOME
D/dalvikvm( 5151): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5151): Added shared lib libjavacore.so 0x0
D/AbsListView( 5032): Get MotionRecognitionManager
D/dalvikvm( 5151): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5151): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5151): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_BACK
D/MotionRecognitionService( 2404):  ssp status : false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_SEARCH
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_FOCUS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_CAMERA
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_F1
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_TOUCH_KEY_ODER
I/dalvikvm( 5032): Could not find method android.sec.multiwindow.MultiWindow.createInstance, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 5032): VFY: unable to resolve static method 1401: Landroid/sec/multiwindow/MultiWindow;.createInstance (Landroid/app/Activity;)Landroid/sec/multiwindow/MultiWindow;
D/dalvikvm( 5032): VFY: replacing opcode 0x71 at 0x03bb
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_TEST_VIEW_TABLE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=IS_KEY_TEST_THRESHOLD
I/dalvikvm( 5032): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 5032): VFY: unable to resolve virtual method 1402: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
D/dalvikvm( 5032): VFY: replacing opcode 0x74 at 0x0759
I/dalvikvm( 5032): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 5032): VFY: unable to resolve virtual method 1402: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
D/dalvikvm( 5032): VFY: replacing opcode 0x74 at 0x07e8
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_UP
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_DOWN
D/checkbox( 5032): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5032): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5032): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5032): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=IS_TSP_STANDARD_CHANNEL
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=IS_SENSOR_TEST_ACC_REVERSE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SUPPORT_GEOMAGNETIC_ALPS_CAL
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=GEOMAGNETIC_IC_POINT
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SENSOR_TEST_ACC_BIT
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=IS_VIBETONZ_UNSUPPORTED
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=IS_IRLED_TEST_SPLIT_COMMAND
V/WebViewChromium( 5032): Binding Chromium to the main looper Looper (main, tid 1) {4263d470}
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=AT_SPKSTEST
I/chromium( 5032): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5032): Initializing chromium process, renderers=0
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=AT_GPSSTEST
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=AT_BATTEST_RESET_WHEN_READ
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=PA0_TEMP_ADC
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=PA1_TEMP_ADC
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=NEED_ACK_FOR_CAMERA_STOP
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HALL_IC_TEST
W/chromium( 5032): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/dalvikvm( 4988): GC_CONCURRENT freed 1667K, 24% free 10388K/13500K, paused 2ms+4ms, total 39ms
E/memtrack( 5151): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5151): failed to load memtrack module: -2
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HUMITEMP_TEST
D/libEGL  ( 5032): loaded /system/lib/egl/libEGL_mali.so
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=IS_NEW_TSP_SELFTEST_SYNAPTICS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_PEEK_TO_PEEK
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_IR_CURRENT_CHANGE
D/libEGL  ( 5032): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
D/libEGL  ( 5032): loaded /system/lib/egl/libGLESv2_mali.so
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SYS_INFO_FONT_SIZE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SYS_INFO_MEMORY_SIZE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SYS_INFO_OUT_POSITION
I/Mali    ( 5032): Mali API Version : 401
I/Mali    ( 5032): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_WIDTH
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_HEIGHT
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
D/dalvikvm( 5032): GC_CONCURRENT freed 906K, 14% free 11628K/13500K, paused 4ms+2ms, total 67ms
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS
D/dalvikvm( 5151): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS_PWC
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS_PWC
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_CYPRESS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_CYPRESS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_CYPRESS
D/checkbox( 5032): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5032): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5032): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5032): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_CYPRESS
D/dalvikvm( 4670): GC_CONCURRENT freed 2287K, 24% free 10269K/13496K, paused 3ms+17ms, total 65ms
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MIN
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MAX
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MIN
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MAX
D/checkbox( 5032): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5032): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5032): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5032): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_START
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_END
D/AndroidRuntime( 5151): Calling main entry com.android.commands.am.Am
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_START
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_END
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MIN
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MAX
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MIN
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MAX
D/checkbox( 5032): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5032): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5032): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5032): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_AVG
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_AVG
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_AVG
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_MAX
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_AVG
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_MAX
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_MAX
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_AVG
D/checkbox( 5032): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5032): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5032): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5032): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_MAX
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_AVG
I/DBG_DM  ( 4066): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 21 sec
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_SAMPLE_NO
D/AndroidRuntime( 5151): Shutting down VM
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_PEAK_IR
D/dalvikvm( 5151): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 1ms+0ms, total 3ms
D/checkbox( 5032): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5032): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5032): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5032): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_IR
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_NOISE_IR
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_RED
D/checkbox( 5032): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5032): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5032): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5032): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=BOOTLOADER_VERSION
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=BATTERY_TEST_MODE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=BATTERY_VOLT_AVER
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=BATTERY_VF_OCV
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_CELCIUS
D/checkbox( 5032): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5032): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5032): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5032): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=SEC_EXT_THERMISTER_ADC
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_ADC
D/Mms/BubbleViewCache( 5032): fillCache bubble = 8
D/Mms/Synchronizer( 5032): [start]    dbSync()
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=PA1_THERMISTER_ADC
D/TP/MmsSmsProvider( 2754): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 2754): syncDBData start
V/TP/MmsSmsProvider( 2754): syncDBData sms end
V/TP/MmsSmsProvider( 2754): syncDBData mms end
V/TP/MmsSmsProvider( 2754): syncDBData end
D/Mms/Synchronizer( 5032): [end]    dbSync()
D/TP/MmsSmsProvider( 2754): match 0:Elapsed time : 1.477 ms
D/dalvikvm( 4988): GC_CONCURRENT freed 2040K, 23% free 10397K/13500K, paused 2ms+8ms, total 53ms
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_COMMAND_CMD
D/Mms/MessagingNotification( 5032): checkBadgeCount unreadCount=0 badgeCount=0
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_COMMAND_STATUS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=TSP_COMMAND_RESULT
D/TP/MmsSmsProvider( 2754): match 6:Elapsed time : 2.091 ms
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=LED_RED
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=LED_GREEN
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=LED_BLUE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=PATH_HALLIC_STATE
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=KEY_PRESSED_POWER
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=APCHIP_TEMP_ADC
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_PAM
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT_CELCIUS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=USB3_TYPE_CHECK
,D/FactoryTestApp( 4988): [XMLDataStorage$redefinitionById] id=LPA_MODE_SET
,D/FactoryTestApp( 4988): [XMLDataStorage$parseAsset] SemiFunctionMenu
,D/FactoryTestApp( 4988): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 4988): [Support$Properties.get] property=ro.factory.factory_binary
D/FactoryTestApp( 4988): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=S.LSI
,D/FactoryTestApp( 4988): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=S.LSI
,D/FactoryTestApp( 4988): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=S.LSI
I/FactoryTestApp( 4988): [ModuleCommon$ModuleCommon] Create ModuleCommon
,I/FactoryTestApp( 4988): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 4988): [ModuleCommon$getMediaScanningCount] get : 0
D/FactoryTest( 4988): User mode
,I/FactoryTestApp( 4988): [ModuleCommon$getMediaScanningCount] get : 1
W/ContextImpl( 4988): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:269 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 5178): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5178):  
,I/SELinux ( 5178): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5178):  
I/SELinux ( 5178):  
,I/SELinux ( 5178): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5178): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5178): >>>>> Normal User
,E/dalvikvm( 5178): >>>>> com.sec.android.gallery3d [ userId:0 | appId:10047 ]
,E/SELinux ( 5178): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5178): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5178): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5178): Added TimaKesytore provider
,I/Icing   ( 3261): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,D/dalvikvm( 5178): GC_CONCURRENT freed 2983K, 29% free 9589K/13500K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 5178): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/Icing   ( 3261): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,W/System.err( 5178): java.lang.NoSuchFieldException: SYSTEM_UI_FLAG_REMOVE_NAVIGATION
,W/System.err( 5178): 	at java.lang.Class.getField(Class.java:724)
,W/System.err( 5178): 	at com.sec.android.gallery3d.util.GalleryFeature.checkSystemUiVisibility(GalleryFeature.java:1588)
W/System.err( 5178): 	at com.sec.android.gallery3d.util.GalleryFeature.init(GalleryFeature.java:364)
,W/System.err( 5178): 	at com.sec.android.gallery3d.app.GalleryAppImpl.getDataManager(GalleryAppImpl.java:247)
W/System.err( 5178): 	at com.sec.android.gallery3d.provider.GalleryProvider.onCreate(GalleryProvider.java:140)
W/System.err( 5178): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
,W/System.err( 5178): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 5178): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
W/System.err( 5178): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
,W/System.err( 5178): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
W/System.err( 5178): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5178): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
,W/System.err( 5178): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5178): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 5178): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 5178): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5178): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 5178): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 5178): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 5178): 	at dalvik.system.NativeStart.main(Native Method)
W/ServiceManager( 2404): Permission failure: com.samsung.permission.SSENSOR from uid=10047 pid=5178
D/PermissionCache( 2404): checking com.samsung.permission.SSENSOR for uid=10047 => denied (332 us)
E/SensorService( 2404): Permission Denial : SEC Private Sensor 
,E/SensorService( 2404): Permission Denial : SEC Private Sensor 
,D/Spen    ( 5178): SpenSdk version level = 55
,D/Spen    ( 5178): SpenSdk jar version = 3.0.109
D/Spen    ( 5178): SpenSdk apk version = 3.0.109
,D/Spen    ( 5178): Server UPDATE Check
,W/linker  ( 5178): libSPenBase.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/SPenError( 5178): JNI_OnLoad
D/JNI_Bitmap( 5178): Init .. Done
D/SPenSpiDecoder( 5178): JNI_OnLoad .. Done
,D/SPenError( 5178): JNI_OnLoad Success
,D/PluginManager( 5178): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager( 5178): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
D/Init_SPenSdk_Jni( 5178): JNI_OnLoad
,D/Init_SPenSdk_Jni( 5178): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni( 5178): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni( 5178): JNI_OnLoad .. Done
,D/Model_ObjectImage_Jni( 5178): JNI_OnLoad .. Done
D/Model_ObjectText_Jni( 5178): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni( 5178): JNI_OnLoad .. Done
D/Model_PageDoc_Jni( 5178): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni( 5178): check build type eng[0]
D/Model_NoteDoc_Jni( 5178): JNI_OnLoad .. Done
D/Model_NoteFile_Jni( 5178): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni( 5178): JNI_OnLoad .. Done
D/Model   ( 5178): OnLoad class Done
,D/dalvikvm( 5178): No JNI_OnLoad found in /system/lib/libSPenSkia.so 0x4263e0c8, skipping init
,D/SPen_Library( 5178): Draw Engine JNI_OnLoad enter!!
,D/SPen_Library( 5178): Canvas JNI_OnLoad enter!!
,D/SPen_Library( 5178): Canvas JNI_OnLoad Success
,D/SPen_Library( 5178): TextView JNI_OnLoad enter!!
,D/SPen_Library( 5178): TextView JNI_OnLoad Success
D/SPen_Library( 5178): Text JNI_OnLoad enter!!
D/SPen_Library( 5178): Text JNI_OnLoad Success
D/SPen_Library( 5178): FontManager JNI_OnLoad enter!!
D/SPen_Library( 5178): FontManager JNI_OnLoad Success
D/SPen_Library( 5178): CapturePage JNI_OnLoad enter!!
D/SPen_Library( 5178): CapturePage JNI_OnLoad Success
,D/SPen_Library( 5178): Multi JNI_OnLoad enter!!
D/SPen_Library( 5178): Multi JNI_OnLoad Success
,D/SPen_Library( 5178): Draw Engine JNI_OnLoad Success
,D/SPen_Library( 5178): Brush JNI_OnLoad enter!!
,D/SPen_Library( 5178): Brush JNI_OnLoad Success
,D/SPen_Library( 5178): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library( 5178): ChineseBrush JNI_OnLoad Success
,D/SPen_Library( 5178): InkPen JNI_OnLoad enter!!
,D/SPen_Library( 5178): InkPen JNI_OnLoad Success
,D/SPen_Library( 5178): Marker JNI_OnLoad enter!!
,D/SPen_Library( 5178): Marker JNI_OnLoad Success
,D/SPen_Library( 5178): Pencil JNI_OnLoad enter!!
,D/SPen_Library( 5178): Pencil JNI_OnLoad Success
,D/SPen_Library( 5178): NativePen JNI_OnLoad enter!!
,D/SPen_Library( 5178): NativePen JNI_OnLoad Success
,D/SPen_Library( 5178): MagicPen JNI_OnLoad enter!!
,D/SPen_Library( 5178): MagicPen JNI_OnLoad Success
,W/linker  ( 5178): libSPenHSV.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/dalvikvm( 5178): No JNI_OnLoad found in /system/lib/libSPenHSV.so 0x4263e0c8, skipping init
,D/dalvikvm( 5178): No JNI_OnLoad found in /system/lib/libSPenVIRecognition.so 0x4263e0c8, skipping init
,D/dalvikvm( 5178): No JNI_OnLoad found in /system/lib/libSPenVITextAll.so 0x4263e0c8, skipping init
D/Spen    ( 5178): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni( 5178): SPenSdk_init2
,D/Init_SPenSdk( 5178): Init - screen_width = 720, screen_height = 1280, maxCacheSize = 5 M
D/Init_SPenSdk( 5178): Total S Pen SDK Directory Size = 0
,D/Spen    ( 5178): initialize complete
,W/GalleryUtils( 5178): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,I/PackageManager( 2404): findPreferredActivity: No PreferredActivities set
,D/NearbySource( 5178): Nearby Source Create!
,D/NearbyContext( 5178): Nearby Context Create!
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5178): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 5178): Samsung link source created
D/SLinkClient( 5178): query devices()
,I/SELinux ( 5191): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5191):  
,I/DBG_DM  ( 4066): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 22 sec
,I/SELinux ( 5191): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5191):  
I/SELinux ( 5191):  
,I/SELinux ( 5191): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5191): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5191): >>>>> Normal User
,E/dalvikvm( 5191): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
,E/SELinux ( 5191): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5191): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5191): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5191): Added TimaKesytore provider
,D/dalvikvm( 4670): GC_CONCURRENT freed 1993K, 25% free 10221K/13496K, paused 1ms+8ms, total 42ms
,D/dalvikvm( 5191): GC_CONCURRENT freed 2994K, 30% free 9572K/13496K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 5191): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SLinkClient( 5178): queryDevices : cursor.getCount() = [ 0 ]
,D/SLinkClient( 5178): onStorageUpdated(), uri = [ slink://slink ]
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5191): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/ActivityManager( 2404): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5191): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/GalleryCacheReady( 5178): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 5178): handleMeidaScanFinish()
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5178): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5178): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/ContextImpl( 5178): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache,
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30,
I/SELinux ( 5216): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5216):  
,D/ContactProvider( 5178): getAllContactInfoList Start
,D/FaceInterface( 5178): requestFaceScan() is called.
,I/FaceInterface( 5178): startFaceScan() : waiting 5 sec,
,I/SELinux ( 5216): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5216):  
I/SELinux ( 5216):  
,I/SELinux ( 5216): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ContextImpl( 4670): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1659 android.content.ContextWrapper.sendStickyBroadcast:439 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:841 <bottom of call stack> 
E/dalvikvm( 5216): >>>>> Normal User
E/dalvikvm( 5216): >>>>> com.sec.android.app.music:service [ userId:0 | appId:10152 ]
I/DBG_DM  ( 4066): [3.19.140541][Line:838][onReceive] com.sec.intent.action.SYSSCOPESTATUS
E/SELinux ( 5216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/DBG_DM  ( 4066): [3.19.140541][Line:842][onReceive] status  = 1
,I/Process ( 4670): Sending signal. PID: 4670 SIG: 9
,E/DBG_DM  ( 4066): Warning!!! [3.19.140541][Line:853][onReceive] Device is ok
,D/TimaKeyStoreProvider( 5216): in addTimaSignatureService
,I/DBG_DM  ( 4066): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.android.launcher2.Launcher
,I/ActivityManager( 2404): Process com.sec.android.app.sysscope (pid 4670) (adj 0) has died.
D/TimaKeyStoreProvider( 5216): Cannot add TimaSignature Service, License check Failed
W/LocalSuggestAlbumData( 5178): query fail: 
D/ActivityThread( 5216): Added TimaKesytore provider
,W/LocalSuggestAlbumData( 5178): query fail: 
I/ActivityManager( 2404): Killing 4136:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
,D/dalvikvm( 2724): GC_EXPLICIT freed 937K, 26% free 10063K/13488K, paused 4ms+7ms, total 51ms
,D/ContactProvider( 5178): getAllContactInfoList End
,I/syncContacts( 5178): thread: 380, sync time = 184
,D/dalvikvm( 5216): GC_CONCURRENT freed 2998K, 30% free 9573K/13500K, paused 4ms+2ms, total 25ms
,D/dalvikvm( 5216): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/com.samsung.musicplus.bitmapcache.BitmapCache( 5216): Allocated bitmap cache: 13421772
,I/SettingSearch/SearchIntentReceiver( 5015): action : android.settings.CHANGED_ICC_LOCK_ENABLE
,I/ActivityManager( 2404): Killing 4149:com.wssnps/1000 (adj 15): empty #43,
E/CscFactoryReceiver( 2754): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 2754): Media DB Scanner finished.,
D/CscFactoryReceiver( 2754): start service to Set Ringtone
D/CscFactoryReceiver( 2754): start service to Set Notification,
D/CscFactoryReceiver( 2754): start service to Set Alarmtone
D/CscUpdateService( 2754): onStart,
E/CscUpdateService( 2754): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2754): only ringtone update,
D/CscUpdateService( 2754): onStart
E/CscParser( 2754): update(): xml file exist,
E/CscUpdateService( 2754): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2754): only notification update,
E/CscParser( 2754): update(): xml file exist
,D/CscUpdateService( 2754): onStart
,E/CscUpdateService( 2754): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 2754): only alarmtone update,
E/CscParser( 2754): update(): xml file exist
,I/SELinux ( 5233): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5233):  
,W/CSCSettings( 2754): Setting Ringtones (type) : 2,
D/CscParser( 2754): MessageTone: null
,W/CSCSettings( 2754): 1. Tag_Str: null,
,W/CSCSettings( 2754): Setting Ringtones (type) : 4,
D/CscParser( 2754): AlarmTone: null
,W/CSCSettings( 2754): 1. Tag_Str: null,
,I/SELinux ( 5233): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5233):  
I/SELinux ( 5233):  
,I/SELinux ( 5233): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 5233): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/CSCSettings( 2754): Setting Ringtones (type) : 1,
E/dalvikvm( 5233): >>>>> Normal User
E/dalvikvm( 5233): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ],
D/CscParser( 2754): RingTone: null
,W/CSCSettings( 2754): 1. Tag_Str: null,
,I/DBG_DM  ( 4066): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 23 sec,
,E/SELinux ( 5233): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,I/DBG_DM  ( 4066): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected,
,E/DBG_DM  ( 4066): Warning!!! [3.19.140541][Line:224][xdmAgentTaskHandler] Network Status is not ready. DM Not Initialized,
,I/DBG_DM  ( 4066): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.android.launcher2.Launcher,
,D/TimaKeyStoreProvider( 5233): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 5233): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5233): Added TimaKesytore provider
,D/dalvikvm( 5233): GC_CONCURRENT freed 3002K, 30% free 9573K/13504K, paused 3ms+2ms, total 26ms,
,D/dalvikvm( 5233): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,D/FactoryTestApp( 4988): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED,
I/FactoryTestApp( 4988): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.,
D/FactoryTestApp( 4988): [FactoryTestBroadcastReceiver$onReceive] ACTION_MEDIA_SCANNER_FINISHED => XML data parsing was failed.,
D/FactoryTestApp( 4988): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 4988): [Support$Properties.get] property=ro.factory.factory_binary,
I/FactoryTestApp( 4988): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 4988): [ModuleCommon$getMediaScanningCount] get : 1,
D/FactoryTest( 4988): User mode
I/FactoryTestApp( 4988): [ModuleCommon$getMediaScanningCount] get : 2
,I/FactoryTestApp( 4988): [ModuleCommon$getMediaScanningCount] get : 2
,D/FactoryTestApp( 4988): [Support$Values.getBoolean] id=FACTORY_TEST_APO, value=true
D/FactoryTestApp( 4988): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/IndexBroadcastProcessorService( 5233): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
,I/FactoryTestApp( 4988): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 4988): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
I/FactoryTestApp( 4988): [FactoryTestBroadcastReceiver$USER MODE] BOOT_COMPLETE
,I/FactoryTestApp( 4988): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted] start DummyFtClient service for APO
,I/IndexBroadcastProcessorService( 5233): lucene systemReadyToIndex
W/ContextImpl( 4988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:577 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:278 
,D/FactoryTestApp( 4988): [Support$Values.getBoolean] id=SUPPORT_BOOST_MEDIASCAN, value=true
,I/FactoryTestApp( 4988): [FactoryTestBroadcastReceiver$wake lock] SUPPORT_BOOST_MEDIASCAN
I/FactoryTestApp( 4988): [ModulePower$ModulePower] Create ModulePower
,I/FactoryTestApp( 4988): [ModulePower$doMediaScanWakeLock] wake=false
,D/FactoryTest( 4988): User mode
,I/FactoryTestApp( 4988): [ModuleCommon$15 Test Ready flag] set
,I/IndexService( 5233): lucene onCreate ...service
,I/FactoryTestApp( 4988): [ModuleCommon$isFirstBoot] before : false
D/FactoryTestApp( 4988): [DummyFtClient$onCreate] Create DummyFtClient service
I/FactoryTestApp( 4988): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 4988): [DummyFtClient$onReceive] ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
D/FactoryTestApp( 4988): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 4988): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
,D/FactoryTestApp( 4988): [Support$Values.getBoolean] id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 4988): [DummyFtClient$onStartCommand] ...
D/FactoryTestApp( 4988): [DummyFtClient$sendBootCompletedAndFinish] ...
D/FactoryTestApp( 4988): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 4988): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
D/FactoryTestApp( 4988): [IPCWriterToSecPhoneService$ResponseWriter] Create IPCWriterToSecPhoneService
,I/FactoryTestApp( 4988): [IPCWriterToSecPhoneService$connectToSecPhoneService]  
W/ContextImpl( 4988): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:141 
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,D/GalleryCacheReady( 5178): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5233): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/GalleryCacheReady( 5178): handleMeidaScanFinish()
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5233): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/SELinux ( 5249): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5249):  
,D/FaceInterface( 5178): requestFaceScan() is called.,
,W/LocalSuggestAlbumData( 5178): query fail: ,
,W/LocalSuggestAlbumData( 5178): query fail: ,
,I/FaceInterface( 5178): startFaceScan() : waiting 5 sec,
,D/GalaxyFinderApplication( 3810): [Slink platform] The state of Slink geocode service is true,
D/LocationTagReadyService( 3810): SLink location service is enable. content://media/external/images/media not register,
D/GalaxyFinderApplication( 3810): [Slink platform] The state of Slink geocode service is true,
D/LocationTagReadyService( 3810): SLink location service is enable. content://media/external/video/media not register
,D/GalaxyFinderApplication( 3810): [Slink platform] The state of Slink geocode service is true,
,I/LocationTagReadyService( 3810): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3810): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3810): [Slink platform] The state of Slink geocode service is true
,I/dalvikvm( 5233): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 5233): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 5233): VFY: replacing opcode 0x71 at 0x01ed
I/SELinux ( 5249): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5249):  
I/SELinux ( 5249):  
,I/SELinux ( 5249): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/GalaxyFinderApplication( 3810): [Slink platform] The state of Slink geocode service is true
,E/SELinux ( 5249): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5249): >>>>> Normal User
,E/dalvikvm( 5249): >>>>> com.sec.phone [ userId:0 | appId:1001 ]
,E/SELinux ( 5249): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 5267): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5267):  
,D/TimaKeyStoreProvider( 5249): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5249): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5249): Added TimaKesytore provider
,I/SELinux ( 5272): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5272):  
,I/GallerySearchProvider( 5178): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5267): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5267):  
I/SELinux ( 5267):  
,I/SELinux ( 5267): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5267): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5267): >>>>> Normal User
,E/dalvikvm( 5267): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 5267): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 5272): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5272):  
I/SELinux ( 5272):  
,I/SELinux ( 5272): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5272): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5267): in addTimaSignatureService
E/dalvikvm( 5272): >>>>> Normal User
,E/dalvikvm( 5272): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,I/SELinux ( 5285): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5285):  
,E/SELinux ( 5272): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/IndexService( 5233): lucene beginIndexing
,D/TimaKeyStoreProvider( 5267): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5267): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5272): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5272): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5272): Added TimaKesytore provider
,I/SELinux ( 5285): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5285):  
I/SELinux ( 5285):  
,I/SELinux ( 5285): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5285): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5285): >>>>> Normal User
,E/dalvikvm( 5285): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5285): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/IndexService( 5233): lucene onDestroy start
I/IndexService( 5233): lucene onDestroy end
,I/IndexService( 5233): lucene cleanupEverything start
,D/TimaKeyStoreProvider( 5285): in addTimaSignatureService
,I/IndexService( 5233): ERROR: null
,E/ParserThreadsListManager( 5233): Lucene Interrupt in run
,I/IndexService( 5233): lucene cleanupEverything end
,I/Process ( 5233): Sending signal. PID: 5233 SIG: 9
,D/TimaKeyStoreProvider( 5285): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5285): Added TimaKesytore provider
,I/ActivityManager( 2404): Process com.samsung.indexservice (pid 5233) (adj 9) has died.
,D/dalvikvm( 5272): GC_CONCURRENT freed 2990K, 30% free 9579K/13496K, paused 6ms+2ms, total 43ms
,D/dalvikvm( 5272): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 5249): GC_CONCURRENT freed 2999K, 30% free 9571K/13500K, paused 6ms+2ms, total 48ms
,D/dalvikvm( 5249): WAIT_FOR_CONCURRENT_GC blocked 42ms
,I/FactoryTestApp( 4988): [IPCWriterToSecPhoneService$onServiceConnected] connected done
D/FactoryTestApp( 4988): [IPCWriterToSecPhoneService$write] Send Response Message to SecPhone
,D/FactoryTestApp( 4988): [IPCWriterToSecPhoneService$write] Response ��
,D/dalvikvm( 5285): GC_CONCURRENT freed 2999K, 30% free 9572K/13496K, paused 6ms+2ms, total 28ms
,D/dalvikvm( 5285): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 5267): GC_CONCURRENT freed 2986K, 29% free 9588K/13500K, paused 5ms+3ms, total 95ms
,D/dalvikvm( 5267): WAIT_FOR_CONCURRENT_GC blocked 76ms
,D/AT_Distributor( 1954): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/AT_Distributor( 1954): SetAtdStatus(), 1_1_0
,D/AT_Distributor( 1954): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/FactoryTestApp( 4988): [IPCWriterToSecPhoneService$handleMessage] Send BOOT COMPLETED done
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/MediaStoreImporter( 5091): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,V/KVNProvider( 5285): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5285): getFindoCursor query string : 
,V/KVNProvider( 5285): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager( 2404): Killing 4161:com.samsung.android.app.accesscontrol/u0a67 (adj 15): empty #43
,I/SELinux ( 5317): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5317):  
,I/SELinux ( 5321): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5321):  
,D/PackageManager( 2404): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 2404): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10012, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@43396c58, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/SELinux ( 5317): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5317):  
I/SELinux ( 5317):  
,I/SELinux ( 5317): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5317): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5317): >>>>> Normal User
,E/dalvikvm( 5317): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 5317): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SELinux ( 5321): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5321):  
I/SELinux ( 5321):  
,I/SELinux ( 5321): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5321): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5321): >>>>> Normal User
,E/dalvikvm( 5321): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 5321): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5317): in addTimaSignatureService
,I/InputReader( 2404): Reconfiguring input devices.  changes=0x00000010
,D/TimaKeyStoreProvider( 5317): Cannot add TimaSignature Service, License check Failed
,D/TimaKeyStoreProvider( 5321): in addTimaSignatureService
,D/ActivityThread( 5317): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5321): Cannot add TimaSignature Service, License check Failed
,D/RegisteredServicesCache( 2758): empty dynamic service
,D/ActivityThread( 5321): Added TimaKesytore provider
V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2404):   Scheme: "sms"
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{43513140 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "smsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 5317): GC_CONCURRENT freed 2998K, 30% free 9572K/13500K, paused 6ms+2ms, total 34ms,
,D/dalvikvm( 5317): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mmsto",
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 5321): GC_CONCURRENT freed 3001K, 30% free 9571K/13500K, paused 13ms+2ms, total 51ms,
,I/PowerManagerService( 2404): [PWL] Off : 5s ago
,I/PowerManagerService( 2404): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2404): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2404): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2404, ws=WorkSource{10045}) (elapsedTime=21753)
,D/dalvikvm( 5321): WAIT_FOR_CONCURRENT_GC blocked 49ms
I/PowerManagerService( 2404): [PWL]       PARTIAL_WAKE_LOCK              'StartingAlertService' (uid=10144, pid=5267, ws=null) (elapsedTime=384)
,I/ActivityManager( 2404): Killing 4177:com.samsung.android.app.airwakeupview/u0a69 (adj 15): empty #43
I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "sms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "smsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mmsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SettingSearchManagerReceiver( 2754): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,I/SettingSearchManagerReceiver( 2754): addSearchInfoDB
,I/SELinux ( 5343): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5343):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 10% free 9508K/10480K, paused 4ms+3ms, total 34ms
I/SELinux ( 5343): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5343):  
I/SELinux ( 5343):  
,I/SELinux ( 5343): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5343): >>>>> Normal User
,E/dalvikvm( 5343): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10162 ]
,E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9508K/10480K, paused 3ms+3ms, total 28ms
,D/TimaKeyStoreProvider( 5343): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5343): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5343): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9508K/10480K, paused 2ms+5ms, total 30ms
,D/dalvikvm( 5343): GC_CONCURRENT freed 2998K, 30% free 9571K/13500K, paused 5ms+3ms, total 27ms
,D/dalvikvm( 5343): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SettingSearchManagerReceiver( 2754): endInsert
,D/AssistantMenuSettingSearch( 4215): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,D/AssistantMenuSettingSearch( 4215): Make Setting DB
,I/GCoreNlp( 2736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): stay LED for fully charged
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl( 4215): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:123 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:35 
,D/dalvikvm( 2404): GC_EXPLICIT freed 2153K, 13% free 24126K/27528K, paused 7ms+20ms, total 239ms
,I/ActivityManager( 2404): Killing 4189:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty #43
,D/LocationProviderProxy( 2404): applying state to connected service
,W/ApplicationsProvider( 2957): Could not fetch usage stats
W/ApplicationsProvider( 2957): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2957): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2957): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2957): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2957): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2957): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2957): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/LocationProviderProxy( 2404): applying state to connected service
,I/ActivityManager( 2404): Killing 4203:com.sec.android.nearby.mediaserver/u0a74 (adj 15): empty #43
,I/knox    ( 4413): InnerIntentReceiver.onReceive() : com.sec.knox.seandroid.alarm.LOG_UPLOAD_ALARM_INTENT
W/ContextImpl( 4413): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.InnerIntentReceiver.onReceive:171 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 4413): KNOXAgentService. startJobThread() start
,D/knox    ( 4413): KNOXAgentService. JobThread()
D/knox    ( 4413): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4413): KNOXAgentService. startJobThread() wait
,D/knox    ( 4413): KNOXAgentService : onCreate()
,D/knox    ( 4413): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 4413): startFileChecker
,D/knox    ( 4413): KNOXAgentService : onDestroy().
,D/knox    ( 4413): ModuleBase.cancelAllAlarmManageModule()
,I/knox    ( 4413): start checking file is exist to uploading
,D/knox    ( 4413): notiShow :0 / context pref : 2
,I/knox    ( 4413): denial log zip completed
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 4707): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4707): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4707): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4707): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/comdaemonstockapp( 4707): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: widgetappstockclockDAEMON_PROCESS_START
,D/comdaemonstockapp( 4707): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,D/comdaemonstockapp( 4707): [Daemon_Stock]>>> StockclockDaemonService.java:113 [0:0] isFirstRunning , false
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4707): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4707): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4707): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4707): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4707): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 4707): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 4707): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 4707): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 4707): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 4707): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 4707): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 4707): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 4707): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 4707): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 4707): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 4707): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 4707): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/GCM     ( 2849): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/GCoreFlp( 2736): No location to return for getLastLocation()
,W/FusedLocationProvider( 2736): location=null
,E/SPPClientService( 4910): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,I/SELinux ( 5370): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5370):  
,I/ActivityManager( 2404): Killing 4228:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #43
,I/SELinux ( 5370): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5370):  
I/SELinux ( 5370):  
,I/SELinux ( 5370): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5370): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5370): >>>>> Normal User
,E/dalvikvm( 5370): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 5370): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5370): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5370): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5370): Added TimaKesytore provider
,D/dalvikvm( 5370): GC_CONCURRENT freed 2997K, 30% free 9575K/13500K, paused 3ms+1ms, total 27ms
,D/dalvikvm( 5370): WAIT_FOR_CONCURRENT_GC blocked 22ms
,E/SPPClientService( 5370): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5370): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5370): PushLog.txt file is not deleted.
D/SPPClientService( 5370): PushLog.txt file is not deleted.
,D/SPPClientService( 5370): ============PushLog. stop!
,I/SELinux ( 5387): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5387):  
,I/ActivityManager( 2404): Killing 4240:com.blurb.checkout/u0a79 (adj 15): empty #43
,I/SELinux ( 5387): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5387):  
I/SELinux ( 5387):  
,I/SELinux ( 5387): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5387): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5387): >>>>> Normal User
,E/dalvikvm( 5387): >>>>> com.sec.spp.push:RemoteNotiProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 5387): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5387): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5387): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5387): Added TimaKesytore provider
,D/dalvikvm( 5387): GC_FOR_ALLOC freed 3011K, 30% free 9557K/13496K, paused 23ms, total 23ms
,D/dalvikvm( 5387): GC_CONCURRENT freed 224K, 13% free 9563K/10964K, paused 2ms+3ms, total 22ms
,E/SPPClientService( 5387): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5387): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5387): PushLog.txt file is not deleted.
D/SPPClientService( 5387): PushLog.txt file is not deleted.
,D/SPPClientService( 5387): ============PushLog. stop!
,I/ActivityManager( 2404): Killing 4252:com.sec.knox.bridge/1000 (adj 15): empty #43
,E/MTPRx   ( 5000): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,E/MTPRx   ( 5000): check value of boot_completed is1
,E/MTPRx   ( 5000): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5000): Sd-Card path/storage/extSdCard
E/MTPRx   ( 5000): Status for mount/Unmount :removed
,E/MTPRx   ( 5000): SDcard is not available
,W/MTPRx   ( 5000): value of connected istrue
W/MTPRx   ( 5000): value of configured istrue
W/MTPRx   ( 5000): value of mtpEnabled istrue
,W/MTPRx   ( 5000): value of ptpEnabled isfalse
E/MTPRx   ( 5000): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 5000): mtpRunningStatus1
,E/MTPRx   ( 5000): MTP already launched. So return.
,D/NtpTrustedTime( 2404): forceRefresh() from cache miss
,D/NtpTrustedTime( 2404): forceRefresh Fail.
V/NetworkStats( 2404): performPollLocked(flags=0x3)
,V/NetworkStats( 2404): performPollLocked() took 25ms
D/NtpTrustedTime( 2404): forceRefresh() from cache miss
D/NtpTrustedTime( 2404): forceRefresh Fail.
,I/FactoryTestApp( 4988): [IPCWriterToSecPhoneService$disConnectSecPhoneService]  
,I/SELinux ( 5406): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5406):  
,I/SELinux ( 5406): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5406):  
I/SELinux ( 5406):  
,I/SELinux ( 5406): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5406): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5406): >>>>> Normal User
,E/dalvikvm( 5406): >>>>> com.sec.android.diagmonagent [ userId:0 | appId:1000 ]
,E/SELinux ( 5406): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5406): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5406): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5406): Added TimaKesytore provider
D/dalvikvm( 4761): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4761): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4761): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4761): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4761): VFY: unable to resolve instance field 36
,D/dalvikvm( 4761): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4761): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4761): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4761): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4761): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4761): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4761): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x43050be8
D/dalvikvm( 4761): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x43050be8
,D/dalvikvm( 4761): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x43050be8, skipping init
,D/dalvikvm( 4761): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x43050be8
,D/dalvikvm( 4761): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x43050be8
,V/JNIHelp ( 4761): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5406): GC_CONCURRENT freed 3004K, 30% free 9567K/13500K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 5406): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4761): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x43050be8
,D/dalvikvm( 4761): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x43050be8
,D/dalvikvm( 4761): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x43050be8
,D/dalvikvm( 4761): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x43050be8
,I/DBG_DIAGMONDM( 5406): [1.140541.0531][Line:472][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DIAGMONDM( 5406): [1.140541.0531][Line:48][onCreate] myUserId : 0
,I/DBG_DIAGMONDM( 5406): [1.140541.0531][Line:376][xdbDMffs_Init] 
,I/ProviderInstaller( 4761): Installed default security provider GmsCore_OpenSSL
,I/DBG_DIAGMONDM( 5406): [1.140541.0531][Line:70][onCreate] nStatus : 0
,I/DBG_DIAGMONDM( 5406): [1.140541.0531][Line:24][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 2404): Killing 4264:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
I/DBG_DM  ( 4066): [3.19.140541][Line:139][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,I/SELinux ( 5425): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5425):  
,I/SELinux ( 5425): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5425):  
I/SELinux ( 5425):  
,I/SELinux ( 5425): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5425): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5425): >>>>> Normal User
,E/dalvikvm( 5425): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 5425): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5425): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5425): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5425): Added TimaKesytore provider
,D/dalvikvm( 5425): GC_CONCURRENT freed 2985K, 29% free 9586K/13500K, paused 3ms+2ms, total 26ms,
,D/dalvikvm( 5425): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,I/FaceInterface( 5178): startFaceScan() : going on,
,D/FaceInterface( 5178): startFaceScan() is called.
,D/ContentApp( 2724): startScan() is called.,
,D/FaceValue( 2724): mSleepTime: 800,
,D/FaceValue( 2724): mMaxThreadNum: 2,
W/FaceValue( 2724): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 2724): startScan() is end.
D/ContentApp( 2724): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 2724): isNeedToRestore : start
,I/Icing.InternalIcingCorporaProvider( 5425): Updating corpora: A: com.google.android.gms, C: MAYBE
,I/SELinux ( 5440): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5440):  
,I/SELinux ( 5446): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5446):  
,D/LocationManagerService( 2404): getProviders()=[passive]
I/SELinux ( 5440): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5440):  
I/SELinux ( 5440):  
,I/SELinux ( 5440): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5440): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5440): >>>>> Normal User
,E/dalvikvm( 5440): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10073 ]
,E/SELinux ( 5440): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5440): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5440): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 5446): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5446):  
I/SELinux ( 5446):  
,I/SELinux ( 5446): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/ActivityThread( 5440): Added TimaKesytore provider
,E/SELinux ( 5446): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5446): >>>>> Normal User
,E/dalvikvm( 5446): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 5446): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5446): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5446): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5446): Added TimaKesytore provider
,D/dalvikvm( 5440): GC_CONCURRENT freed 3000K, 30% free 9579K/13504K, paused 5ms+2ms, total 36ms
,D/dalvikvm( 5440): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/FileShare-Server( 5440): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/dalvikvm( 5446): GC_CONCURRENT freed 3010K, 30% free 9566K/13504K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 5446): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/SELinux ( 5469): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5469):  
I/ActivityManager( 2404): Killing 4277:com.samsung.android.app.colorblind/1000 (adj 15): empty #43
,I/SELinux ( 5469): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5469):  
I/SELinux ( 5469):  
,I/SELinux ( 5469): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5469): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5469): >>>>> Normal User
,E/dalvikvm( 5469): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 5469): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5469): in addTimaSignatureService
I/ActivityManager( 2404): Killing 4289:com.dropbox.android/u0a95 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5469): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 5469): Added TimaKesytore provider,
,D/dalvikvm( 5469): GC_CONCURRENT freed 3006K, 30% free 9561K/13496K, paused 3ms+2ms, total 31ms,
,D/dalvikvm( 5469): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,I/SELinux ( 5484): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5484):  
I/ActivityManager( 2404): Killing 4310:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,I/SELinux ( 5484): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5484):  
I/SELinux ( 5484):  
,I/SELinux ( 5484): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5484): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5484): >>>>> Normal User
,E/dalvikvm( 5484): >>>>> com.google.android.apps.plus [ userId:0 | appId:10133 ]
,E/SELinux ( 5484): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5484): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5484): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5484): Added TimaKesytore provider
,D/FactoryTestApp( 4988): [DummyFtClient$onDestroy] Destroy DummyFtClient service
D/FactoryTestApp( 4988): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 4988): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 4988): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
D/FactoryTestApp( 4988): [DummyFtClient$onDestroy] kill process,
,I/Process ( 4988): Sending signal. PID: 4988 SIG: 9,
I/FaceInterface( 5178): startFaceScan() : going on
,D/FaceInterface( 5178): startFaceScan() is called.
,D/ContentApp( 2724): startScan() is called.
,D/ContentApp( 2724): startScan() is end.
D/ContentApp( 2724): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 2724): isNeedToRestore : start
,I/ActivityManager( 2404): Process com.sec.factory (pid 4988) (adj 0) has died.
,D/dalvikvm( 5484): GC_CONCURRENT freed 2987K, 29% free 9592K/13504K, paused 4ms+2ms, total 36ms
,D/dalvikvm( 5484): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2404): GC_EXPLICIT freed 1323K, 13% free 24026K/27528K, paused 10ms+23ms, total 285ms
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{43377560 u0 com.google.android.gms/.gcm.GcmService}
,D/BezelQuickConnect( 4488): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 4488): BezelBroadcastReceiver - packageName : com.google.android.gms,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2404): Killing 4328:com.sec.android.fwupgrade/1000 (adj 15): empty #43,
,I/iu.UploadsManager( 5484): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400,
,D/PackageBroadcastService( 3261): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 3261): Null package name or gms related package.  Ignoreing.,
,I/dalvikvm( 4926): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4926): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4926): VFY: replacing opcode 0x6e at 0x0017
,I/Icing   ( 3261): updateResources: need to parse f{com.google.android.gms}
,D/KeyguardViewMediator( 2580): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/KeyguardViewMediator( 2580): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2580): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2580): isPcwEnable = 10
D/LockPatternUtils( 2580): isPcwEnable = 10
,D/KeyguardViewMediator( 2580): doKeyguard: not showing because lockscreen is off
,I/SettingSearch/SearchIntentReceiver( 5015): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 5015): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 5015): InitTitleDBThread start --> mDoingInitTitleDB : true
,W/ContextImpl( 5091): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/SettingSearch/SearchIntentReceiver( 5015): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 5015): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/dalvikvm( 3261): GC_CONCURRENT freed 1932K, 21% free 11433K/14372K, paused 10ms+11ms, total 93ms
,W/ContextImpl( 5091): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/CacheService( 5091): onCreate
,I/iu.UploadsManager( 5484): End new media; added: 0, uploading: 0, time: 288 ms
,D/CacheService( 5091): onBind
,I/SettingSearch/SettingsSearchManager( 5015): Infomation -> numtitleinfo : 0 numSearchinfo : 319
,I/iu.Environment( 5484): update battery state; isPlugged? true*
,I/iu.Environment( 5484): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.FingerprintManager( 5484): Start processing all media
,I/iu.FingerprintManager( 5484): Start processing media store URI: content://media/external/images/media
,I/MusicLeanback( 5091): Conditions not met for autocaching.
,I/MusicLeanback( 5091): Stop autocaching.
,I/iu.FingerprintManager( 5484): Start processing media store URI: content://media/external/video/media
,D/CacheService( 5091): onDestroy
,I/iu.FingerprintManager( 5484): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5484): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 5484): Finished generating fingerprints; 0.040 seconds
,I/iu.FingerprintManager( 5484):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 340, Delta = 0
,I/SettingSearch/SettingsSearchManager( 5015):  Infomation -> getItem size : 319
,I/Icing.InternalIcingCorporaProvider( 5425): UpdateCorporaTask done [took 1719 ms] updated apps [took 1718 ms] 
,I/ActivityManager( 2404): Killing 4340:com.sec.factory.camera/1000 (adj 15): empty #43
,D/AmoledAdjustTimer( 2404): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,I/Icing   ( 3261): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,D/Icing   ( 3261): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 3261): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,I/Icing   ( 3261): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3261): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/dalvikvm( 5015): GC_EXPLICIT freed 646K, 27% free 9897K/13504K, paused 5ms+6ms, total 51ms
,D/dalvikvm( 5343): GC_EXPLICIT freed 907K, 25% free 10154K/13496K, paused 3ms+9ms, total 51ms
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{43559e60 u0 com.samsung.android.MtpApplication/.MtpService}
,I/ActivityManager( 2404): Killing 4352:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/dalvikvm( 2404): GC_EXPLICIT freed 949K, 13% free 24024K/27528K, paused 8ms+15ms, total 213ms
,D/dalvikvm( 5343): GC_EXPLICIT freed 1027K, 26% free 10016K/13496K, paused 3ms+10ms, total 47ms
,D/dalvikvm( 5015): GC_EXPLICIT freed 332K, 27% free 9928K/13504K, paused 4ms+6ms, total 44ms
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 3261): Done disabling old GoogleServicesFramework version
,I/PowerManagerService( 2404): [PWL] Off : 15s ago
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 5343): GC_EXPLICIT freed 890K, 26% free 10017K/13496K, paused 3ms+9ms, total 47ms
,D/dalvikvm( 5015): GC_EXPLICIT freed 357K, 27% free 9936K/13504K, paused 3ms+6ms, total 42ms
,V/AlarmManager( 2404): waitForAlarm result :8
,D/dalvikvm( 5343): GC_EXPLICIT freed 902K, 26% free 10026K/13496K, paused 4ms+9ms, total 46ms
,D/dalvikvm( 5015): GC_EXPLICIT freed 360K, 27% free 9940K/13504K, paused 3ms+6ms, total 41ms
,E/Watchdog( 2404): !@Sync 2
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{4329a138 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,V/AlarmManager( 2404): waitForAlarm result :8
D/NtpTrustedTime( 2404): forceRefresh() from cache miss
,D/NtpTrustedTime( 2404): forceRefresh Fail.
W/SocketClient( 1915): write error (Broken pipe)
,D/dalvikvm( 2404): GC_EXPLICIT freed 447K, 13% free 23980K/27528K, paused 8ms+16ms, total 204ms
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5343): GC_EXPLICIT freed 905K, 26% free 10025K/13496K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 5015): GC_EXPLICIT freed 360K, 27% free 9946K/13504K, paused 3ms+6ms, total 42ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 330, Delta = -10
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm( 5343): GC_EXPLICIT freed 883K, 26% free 10015K/13496K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 5015): GC_EXPLICIT freed 352K, 27% free 9952K/13504K, paused 3ms+6ms, total 41ms
,D/dalvikvm( 5343): GC_EXPLICIT freed 873K, 26% free 10020K/13496K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 5015): GC_EXPLICIT freed 349K, 27% free 9969K/13504K, paused 3ms+6ms, total 42ms
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2404): GC_EXPLICIT freed 360K, 13% free 23967K/27528K, paused 9ms+15ms, total 205ms
,D/dalvikvm( 5343): GC_EXPLICIT freed 874K, 26% free 10018K/13496K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 5015): GC_EXPLICIT freed 348K, 27% free 9979K/13504K, paused 3ms+6ms, total 42ms
,D/dalvikvm( 5343): GC_EXPLICIT freed 871K, 26% free 10016K/13496K, paused 4ms+9ms, total 46ms
,D/dalvikvm( 5015): GC_EXPLICIT freed 343K, 26% free 10000K/13504K, paused 3ms+6ms, total 42ms
,W/IcingInternalCorpora( 3261): getNumBytesRead when not calculated.
,D/dalvikvm( 5343): GC_EXPLICIT freed 871K, 26% free 10016K/13496K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 5015): GC_EXPLICIT freed 353K, 26% free 10009K/13504K, paused 3ms+6ms, total 43ms
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5343): GC_CONCURRENT freed 1470K, 23% free 10502K/13496K, paused 2ms+9ms, total 35ms
V/AlarmManager( 2404): waitForAlarm result :4
V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PowerManagerService( 2404): [PWL] Off : 30s ago
I/PowerManagerService( 2404): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2404): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2404): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2404, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=9)
,D/Finsky  ( 4926): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 4926): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4926): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4926): VFY: replacing opcode 0x62 at 0x0038
D/SSRMv2:SIOP( 2404): SIOP:: AP = 330, Delta = 0
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4926): Thread-357(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4926): Thread-357(ApacheHTTPLog):isShipBuild true
,I/System.out( 4926): Thread-357(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4926): Thread-357 calls detatch()
,E/FrameworkListener( 1915): read() failed (Connection reset by peer)
,W/Finsky  ( 4926): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/SettingSearch/SearchIntentReceiver( 5015): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 5015): LOCALE_CHANGED call search setting db finish!!
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4926): Thread-358 calls detatch()
,I/SettingSearch/SearchIntentReceiver( 5015): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 5015): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 5015): LOCALE_CHANGED call search setting db finish!!
,D/dalvikvm( 2404): GC_EXPLICIT freed 384K, 13% free 23981K/27528K, paused 11ms+16ms, total 211ms
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4926): Thread-357 calls detatch()
,W/Finsky  ( 4926): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/dalvikvm( 4926): GC_CONCURRENT freed 1756K, 20% free 10895K/13572K, paused 4ms+5ms, total 44ms
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4926): Thread-358 calls detatch()
,W/Finsky  ( 4926): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4926): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Finsky  ( 4926): [1] DailyHygiene.reschedule: Scheduling new run in 775 minutes (failures=5)
,D/WearableService( 2736): callingUid 10012, callindPid: 2736
,D/Finsky  ( 4926): [381] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 2736): client connected with version: 8296000
,D/Finsky  ( 4926): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4926): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2404): waitForAlarm result :8,
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK,
V/AlarmManager( 2404): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2404): <AppSync3 Whitelist>
,V/AlarmManager( 2404): (AppSync) ### 0 added ###,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,I/Icing   ( 3261): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music,
,I/Icing   ( 3261): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A,
,V/AlarmManager( 2404): waitForAlarm result :4,
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/dalvikvm( 4926): GC_CONCURRENT freed 1841K, 20% free 11100K/13868K, paused 5ms+4ms, total 46ms,
,D/dalvikvm( 4926): WAIT_FOR_CONCURRENT_GC blocked 19ms,
,D/Finsky  ( 4926): [370] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 4926): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,E/Watchdog( 2404): !@Sync 3,
,I/PowerManagerService( 2404): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/FactoryTest( 5000): Not factory mode,
,D/FactoryTest( 5000): Not factory mode. isFactoryMode() returend false,
D/MTPRx   ( 5000): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5000): still no open session command from host, so toast,
W/ContextImpl( 5000): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5000): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 ,
,V/ApplicationPolicy( 2404): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,D/CustomFrequencyManagerService( 2404): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,I/SurfaceFlinger( 1920): id=15 createSurf (16x16),-1 flag=20004, EimLayer,
,I/SurfaceFlinger( 1920): id=16 createSurf (16x16),-1 flag=20004, EimLayer,
W/ActivityManager( 2404): mDVFSHelper.acquire()
,D/PointerIcon( 2404): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
,D/PointerIcon( 2404): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2404): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2404): setHoveringSpenCustomIcon IconType is same.1,
,E/MTPRx   ( 5000): started activity for popup,
,I/SQLiteSecureOpenHelper( 3509): getWritableDatabase(pwd),
,I/SQLiteSecureOpenHelper( 3509): getDatabaseLocked(b,b,pwd)...,
,E/SettingsReceiverActivity( 5000): PREF_DONT_ASK_AGAIN : true,
D/PointerIcon( 2404): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2404): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2404): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2404): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2404): tr p:2772,o:f
D/StatusBarManagerService( 2404): semi p:2772,o:f
W/InputMethodManagerService( 2404): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@43509ab0 attribute=android.view.inputmethod.EditorInfo@436d4b10, token = android.os.BinderProxy@4337bcc8
,D/SettingsReceiverActivity( 5000): dev.kiessupport is : TRUE
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = -10
,D/CustomFrequencyManagerService( 2404): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2404): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2404): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService( 2404): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/SurfaceFlinger( 1920): id=16 Removed EimLayer (5/10),
I/SurfaceFlinger( 1920): id=15 Removed EimLayer (4/9)
,I/SurfaceFlinger( 1920): id=16 Removed EimLayer (-2/9)
,I/SurfaceFlinger( 1920): id=15 Removed EimLayer (-2/9),
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2404): [PWL] Off : 75s ago,
,E/Watchdog( 2404): !@Sync 4,
,V/AlarmManager( 2404): waitForAlarm result :4,
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/NtpTrustedTime( 2404): forceRefresh() from cache miss,
,D/NtpTrustedTime( 2404): forceRefresh Fail.,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2404): waitForAlarm result :8,
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2404): [PWL] Off : 105s ago,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2404): stay LED for fully charged,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2404): !@Sync 5,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2404): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2404): !@Sync 6,
,V/AlarmManager( 2404): waitForAlarm result :4,
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/NtpTrustedTime( 2404): forceRefresh() from cache miss,
,D/NtpTrustedTime( 2404): forceRefresh Fail.,
,D/dalvikvm( 2849): GC_EXPLICIT freed 1690K, 20% free 10834K/13520K, paused 8ms+8ms, total 72ms,
,I/VacuumService( 2736): Vacuum at: now=1457092598864 tag=VacuumService,
,I/PowerManagerService( 2404): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2404): waitForAlarm result :8,
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2404): !@Sync 7,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2404): stay LED for fully charged,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2404): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2404): !@Sync 8,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = -10,
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2404): stay LED for fully charged,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2404): waitForAlarm result :8,
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2404): [PWL] Off : 225s ago,
,E/Watchdog( 2404): !@Sync 9,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4,
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2404): initializing...,
I/TLC_TIMA_PKM_initialize( 2404): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2404): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2404): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2404): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2404): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2404): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2404): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2404): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2404): device_id = 0x0
,I/TZ: mc_tlc_communication( 2404): tlc_open() was called
,I/TZ: mc_tlc_communication( 2404): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2404): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2404): Opening the session,
,I/TZ: mc_tlc_communication( 2404): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2404): Trustlet response is completed,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2404): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 10,
,D/dalvikvm( 2404): GC_FOR_ALLOC freed 3245K, 16% free 24149K/28624K, paused 199ms, total 200ms,
D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = -10,
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2404): [PWL] Off : 275s ago,
,V/AlarmManager( 2404): waitForAlarm result :8,
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4,
,V/AlarmManager( 2404): waitForAlarm result :4,
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 6250): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6250):  
,I/SELinux ( 6250): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6250):  
I/SELinux ( 6250):  
,I/SELinux ( 6250): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6250): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6250): >>>>> Normal User
,E/dalvikvm( 6250): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 6250): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 6250): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6250): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6250): Added TimaKesytore provider
,D/dalvikvm( 6250): GC_CONCURRENT freed 2997K, 30% free 9571K/13496K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 6250): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2404): Killing 4393:com.samsung.helphub/1000 (adj 15): empty #43
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 11,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 12
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2404): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): stay LED for fully charged
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 13
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 14
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2404): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 15
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2404): !@Sync 16
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2404): [PWL] Off : 455s ago
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 17
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2404): !@Sync 18
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 2404): GC_FOR_ALLOC freed 2494K, 17% free 24137K/28828K, paused 179ms, total 179ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 525s ago
,E/Watchdog( 2404): !@Sync 19
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2404): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 21
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient( 1915): write error (Broken pipe)
,I/PowerManagerService( 2404): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 22
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2404): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2404): <AppSync3 Whitelist>
,V/AlarmManager( 2404): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 23
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 24
,I/PowerManagerService( 2404): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 25
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 26
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 3656): GC_CONCURRENT freed 2866K, 29% free 9731K/13532K, paused 5ms+2ms, total 53ms
,D/dalvikvm( 2404): GC_FOR_ALLOC freed 2178K, 17% free 24190K/28828K, paused 178ms, total 179ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 765s ago
,E/Watchdog( 2404): !@Sync 27
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2404): LightSensor setDelay = 200000000
,D/LightsService( 2404): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors ( 2404): LightSensor setSensorDelay = 200000000
D/Sensors ( 2404): Light sensor flush: not enabled 0
D/Sensors ( 2404): LightSensor enable = 1
D/Sensors ( 2404): LightSensor enableSensor = 1
D/SensorManager( 2404): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3261): Aggregate from 1457091454994 (log), 1457091454994 (data)
,D/Sensors ( 2404): LightSensor enable = 0
,D/Sensors ( 2404): LightSensor enableSensor = 0
,D/LightsService( 2404): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2404): unregisterListener ::   
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/Watchdog( 2404): !@Sync 28
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 29
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 855s ago
I/PowerManagerService( 2404): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2404): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2404): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2404, ws=null) (elapsedTime=3491)
,E/Watchdog( 2404): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 31
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 32
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 33
,I/PowerManagerService( 2404): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 34
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 35
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2404): GC_FOR_ALLOC freed 2447K, 17% free 24116K/28868K, paused 193ms, total 193ms
D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 36
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 37
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 38
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 39
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1155s ago
I/PowerManagerService( 2404): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2404): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2404): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2404, ws=null) (elapsedTime=3545)
,E/Watchdog( 2404): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 41
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms),D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
D/AndroidRuntime( 8449): 
D/AndroidRuntime( 8449): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8449): CheckJNI is OFF
D/AndroidRuntime( 8449): setted country_code = Poland
D/AndroidRuntime( 8449): setted countryiso_code = PL
D/AndroidRuntime( 8449): setted sales_code = PLS
D/AndroidRuntime( 8449): readGMSProperty: start
D/AndroidRuntime( 8449): readGMSProperty: already setted!!
D/AndroidRuntime( 8449): readGMSProperty: end
D/AndroidRuntime( 8449): addProductProperty: start
D/dalvikvm( 8449): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 8449): Added shared lib libjavacore.so 0x0
D/dalvikvm( 8449): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 8449): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 8449): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 8449): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 8449): failed to load memtrack module: -2
D/dalvikvm( 8449): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 8449): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2404): START PACKAGE DELETE: observer{1120150384}
D/PackageManager( 2404): pkg{<packageName>}
D/PackageManager( 2404): user{0}
D/PackageManager( 2404): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2404): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2404): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2404): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2404): [MSG] DELETE_PACKAGE_AS_USER
D/dalvikvm( 2404): GC_EXPLICIT freed 1758K, 17% free 24099K/28868K, paused 6ms+14ms, total 203ms
D/AndroidRuntime( 8449): Shutting down VM
D/PackageManager( 2404): return delete result to caller: 1120150384
D/PackageManager( 2404): returnCode: -1
D/dalvikvm( 8449): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 5ms
I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2404):   Scheme: "sms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/dalvikvm( 2404): Jit: resizing JitTable from 8192 to 16384
I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2404):   Scheme: "smsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2404):   Scheme: "mms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2404):   Scheme: "mmsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/Watchdog( 2404): !@Sync 42

```
