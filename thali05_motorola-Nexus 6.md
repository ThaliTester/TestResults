#### Test 50388019aa1a16d_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  821): Killing 2977:com.google.android.gm/u0a78 (adj 15): empty #17
I/ActivityManager(  821): Start proc 3327:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
--------- beginning of main
I/art     ( 1506): Explicit concurrent mark sweep GC freed 12841(708KB) AllocSpace objects, 8(693KB) LOS objects, 37% free, 26MB/42MB, paused 1.701ms total 49.232ms
I/ActivityManager(  821): Start proc 3350:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
I/ActivityManager(  821): Killing 3012:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
D/TimeService( 3350): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448020214383
D/        ( 3350): TimeServiceNative: User Time to be set is 1448020214383
D/QC-time-services( 3350): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3350): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3350): Lib:time_genoff_operation: pargs->ts_val = 1448020214383
D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448020214383
D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1448020214383, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/7/70 8:3:18
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 8323398000
D/QC-time-services(  374): Daemon:new time 1448020214383 
D/QC-time-services(  374): Daemon: delta 1439696816383 genoff 1439696816383 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696816383 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 3350): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  374): Updating the TOD offset
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696816383 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  374): Daemon:Update to modem bit set
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1132055414383
E/QC-time-services( 3350): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  821): Killing 2874:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
I/art     (  821): Explicit concurrent mark sweep GC freed 20908(1107KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 2.425ms total 88.784ms
,I/ActivityManager(  821): Start proc 3372:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
I/GAv4    ( 3372): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3372):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3372):   adb logcat -s GAv4
W/GAv4    ( 3372): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3372): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3372): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  821): Waited long enough for: ServiceRecord{1053e211 u0 org.simalliance.openmobileapi.service/.SmartcardService}
I/ActivityManager(  821): Killing 3080:com.android.settings/1000 (adj 15): empty #17
D/AndroidRuntime( 3370): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3370): CheckJNI is OFF
D/AndroidRuntime( 3370): Calling main entry com.android.commands.am.Am
V/Herrevad( 1822): NQAS connected
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{b3facf2 token=Token{173b07fd ActivityRecord{12ec0c54 u0 com.example.hello/.MainActivity t22}}} to stack=1 task=22 at 0
D/AndroidRuntime( 3370): Shutting down VM
V/WindowManager(  821): Adding window Window{eacdc9f u0 Starting com.example.hello} at 3 of 8 (after Window{312493f9 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1534): Closing mic
I/MicrophoneInputStream( 1534): mic_close com.google.android.apps.gsa.speech.audio.u@36461d09
I/ActivityManager(  821): Start proc 3407:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1534): Stopping hotword detection.
I/HotwordRecognitionRnr( 1534): Hotword detection finished
I/ActivityManager(  821): Start proc 3424:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
I/WebViewFactory( 3407): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3407): Time to load native libraries: 1 ms (timestamps 9372-9373)
I/LibraryLoader( 3407): Expected native library version number "",actual native library version number ""
I/ActivityManager(  821): Killing 2574:com.google.android.apps.maps/u0a65 (adj 15): empty #17
W/ContextImpl( 3424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
V/WebViewChromiumFactoryProvider( 3407): Binding Chromium to main looper Looper (main, tid 1) {32a3348}
I/LibraryLoader( 3407): Expected native library version number "",actual native library version number ""
I/chromium( 3407): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3407): Initializing chromium process, singleProcess=true
,W/art     ( 3407): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3407): ApplicationContext is null in ApplicationStatus
,W/chromium( 3407): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659524371
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/libEGL  ( 3407): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3407): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3407): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bd7c097:true
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29bd95d9:true
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 2177): getBluetoothService() called with no BluetoothManagerCallback
,W/art     ( 3407): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3407): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager(  821): Start proc 3472:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 2177): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2177): Accept thread started.
D/SystemWebViewEngine( 3407): CordovaWebView is running on device made by: motorola
D/LocalBluetoothProfileManager( 3424): Adding local A2DP profile
D/BluetoothManagerService(  821): Message: 30
W/art     ( 3407): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3407): Attempt to remove local handle scope entry from IRT, ignoring
D/LocalBluetoothProfileManager( 3424): Adding local HEADSET profile
D/BluetoothManagerService(  821): Message: 30
D/BluetoothManagerService(  821): Message: 30
D/BluetoothManagerService(  821): Message: 30
D/LocalBluetoothProfileManager( 3424): Adding local MAP profile
D/BluetoothMap( 3424): Create BluetoothMap proxy object
D/BluetoothManagerService(  821): Message: 30
D/BluetoothManagerService(  821): Message: 30
D/LocalBluetoothProfileManager( 3424): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3424): finishStartingService: stopping service
D/BluetoothA2dp( 3424): Proxy object connected
D/A2dpProfile( 3424): Bluetooth service connected
,D/BluetoothInputDevice( 3424): Proxy object connected
,D/HidProfile( 3424): Bluetooth service connected
,D/BluetoothPan( 3424): BluetoothPAN Proxy object connected
D/PanProfile( 3424): Bluetooth service connected
D/BluetoothMap( 3424): Proxy object connected
D/MapProfile( 3424): Bluetooth service connected
D/BluetoothMap( 3424): getConnectedDevices()
,D/BluetoothPbap( 3424): Proxy object connected
D/PbapServerProfile( 3424): Bluetooth service connected
,I/ActivityManager(  821): Killing 3045:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 3424): Proxy object connected
D/HeadsetProfile( 3424): Bluetooth service connected
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{274287d1 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,D/OpenGLRenderer( 3407): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3407): Validating map...
,V/WindowManager(  821): Adding window Window{26f92375 u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{eacdc9f u0 Starting com.example.hello})
,W/chromium( 3407): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3407): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3407): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.example.hello/.MainActivity: +624ms (total +25s454ms)
,I/Keyboard.Facilitator( 1217): onFinishInput()
,W/BindingManager( 3407): Cannot call determinedVisibility() - never saw a connection for the pid: 3407
,I/chromium( 3407): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/StrictMode( 3472): StrictMode policy violation; ~duration=229 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3472): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3472): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3472): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3472): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3472): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3472): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3472): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3472): StrictMode policy violation; ~duration=229 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3472): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3472): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3472): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3472): StrictMode policy violation; ~duration=227 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3472): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3472): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3472): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3472): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3472): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3472): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3472): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3472): StrictMode policy violation; ~duration=224 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3472): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3472): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3472): StrictMode policy violation; ~duration=220 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3472): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3472): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3472): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3472): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3472): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3472): StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3472): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3472): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3472): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3472): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3472): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3472): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3472): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3472): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3472): # via Binder call with stack:
D/StrictMode( 3472): android.os.StrictMode$LogStackTrace
D/StrictMode( 3472): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3472): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3472): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3472): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3472): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3472): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3472): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3472): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3472): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3472): StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3472): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3472): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3472): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3472): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3472): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3472): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3472): StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3472): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3472): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3472): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3472): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication,.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3472): StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3472): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3472): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3472): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3472): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3472): StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3472): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3472): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3472): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3472): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3472): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3472): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3472): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3472): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3472): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3472): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3472): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3472): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3472): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3472): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3472): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3472): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3472): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3472): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3472): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/ActivityThread( 3472): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/com.google.a.a.a.b.a( 3472): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e575562:true
I/ActivityManager(  821): Killing 3164:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,D/JsMessageQueue( 3407): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3407): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/AuthorizationBluetoothService( 1506): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/jxcore_app_log( 3407): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576524032
D/JX-Cordova( 3407): jxcore cordova android initializing
,I/Atfwd_Daemon(  376): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  376): ATFWD --> QMI Port : rmnet_usb0
,D/GCM     ( 1506): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/jxcore-log( 3407): Initializing JXcore engine
W/jxcore-log( 3407): JXcore engine is ready
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/jxcore-log( 3407): Starting JXcore engine
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Atfwd_Daemon(  376): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  376): Trying to register 8 commands:
I/Atfwd_Daemon(  376): cmd0: +CKPD
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd1: +CTSA
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd2: +CFUN
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd3: +CMAR
W/m.example.hello( 3407): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12921]" dev="sockfs" ino=12921 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3407): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3407): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13011]" dev="sockfs" ino=13011 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3407): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20218]" dev="sockfs" ino=20218 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  376): cmd4: +CDIS
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd5: +CRSL
,I/ActivityManager(  821): Start proc 3527:com.motorola.android.buacontactadapter/u0a88 for broadcast com.motorola.android.buacontactadapter/.BuaReceiver
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd6: +CSS
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  376): cmd7: $QCPWRDN
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): Registered AT Commands event handler
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  821): Explicit concurrent mark sweep GC freed 14526(703KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 2.156ms total 86.013ms
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1822): [AccountUtils] Account not ready
W/Kids    ( 1822): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1822): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1822): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1822): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1822): 	at java.lang.Thread.run(Thread.java:818)
,I/art     ( 1822): Explicit concurrent mark sweep GC freed 22062(1338KB) AllocSpace objects, 15(240KB) LOS objects, 36% free, 27MB/43MB, paused 1.538ms total 38.660ms
W/jxcore-log( 3407): Platform android
W/jxcore-log( 3407): 
W/jxcore-log( 3407): Process ARCH arm
W/jxcore-log( 3407): 
,D/BuaReceiver( 3527): ====== got intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/jxcore-log( 3407): JXcore Cordova bridge is ready!
I/jxcore-log( 3407): 
W/jxcore-log( 3407): JXcore engine is started
,I/ActivityManager(  821): Start proc 3546:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
I/ActivityManager(  821): Waited long enough for: ServiceRecord{654147a u0 com.qualcomm.atfwd/.AtFwdService}
,E/jxcore-log( 3407): >> motorola-Nexus 6
E/jxcore-log( 3407): 
,I/jxcore-log( 3407): Total memory 3113791488
I/jxcore-log( 3407): 
,I/jxcore-log( 3407): Free memory 982745088
I/jxcore-log( 3407): 
,I/jxcore-log( 3407): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3407): 
I/jxcore-log( 3407): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3407): 
,I/jxcore-log( 3407): userPath [ 'www' ]
I/jxcore-log( 3407): 
,I/jxcore-log( 3407): Size 1440 2392
I/jxcore-log( 3407): 
,I/jxcore-log( 3407): Screen Brightness 82
I/jxcore-log( 3407): 
E/jxcore-log( 3407): Dummy Error Log.
E/jxcore-log( 3407): 
,I/MediaStoreImporter( 3100): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  821): Start proc 3566:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  821): Killing 2842:com.google.android.talk/u0a61 (adj 15): empty #17
,D/PackageBroadcastService( 1822): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1822): Loading module APK com.google.android.play.games
,I/ActivityManager(  821): Start proc 3587:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
,I/ActivityManager(  821): Killing 2957:com.google.android.gms:car/u0a11 (adj 15): empty #17
,W/ResourcesManager( 3587): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3587): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3587): VM with version 2.1.0 has multidex support
I/MultiDex( 3587): install
I/MultiDex( 3587): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3587): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3587): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  821): Killing 3192:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/jxcore-log( 3407): getBuffer is called!!!!
I/jxcore-log( 3407): 
,I/ConfigFetchService( 1822): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1822): launchTask
,V/ConfigFetchTask( 1822): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1X1B543koap9TCuPFk4VqlcibI2Sxko9tImVz9DSz8gnyJINdkyjJxSyrx4loDAFFX-NoRgQpIPdUt9Y3cY8S5SZ55OIu0scNhxyluIfCt4pm4vLAH3_6xTwnjRZnFIc9N-38AaBRYH8JJSANKCUlVdLc_I8ni5ULBdc7QVLcHctRghyU-fqyKfWgFCNV5JoyCmf7JM
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1822): Module APK com.google.android.play.games already loaded
,I/PeopleContactsSync( 1822): CP2 sync disabled
D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1822): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1822): Failed to find package metadata for com.example.hello
D/Vision  ( 1822): No vision deps
I/GoogleURLConnFactory( 1822): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  821): Start proc 3616:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 192us total 9.172ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 214us total 9.070ms
,I/UpdateIcingCorporaServi( 1534): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 217us total 13.186ms
,I/UpdateIcingCorporaServi( 1534): UpdateCorporaTask done [took 87 ms] updated apps [took 87 ms] 
,W/BaseAppContext( 1822): Using Auth Proxy for data requests.
W/BaseAppContext( 1822): Using Auth Proxy for data requests.
,W/BaseAppContext( 1822): Using Auth Proxy for data requests.
,W/BaseAppContext( 1822): Using Auth Proxy for data requests.
,W/BaseAppContext( 1822): Using Auth Proxy for data requests.
,W/BaseAppContext( 1822): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1822): fetch service done; releasing wakelock
,I/ConfigFetchService( 1822): stopping self
,D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1822): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 3616): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3616):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3616):   adb logcat -s GAv4
,W/GAv4    ( 3616): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3616): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3616): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3616): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/ResourcesManager( 3616): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3616): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3616): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3616): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  821): Start proc 3658:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3658): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  821): Killing 2605:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/CalendarProvider2( 3658): Created com.android.providers.calendar.CalendarAlarmManager@3838f9eb(com.android.providers.calendar.CalendarProvider2@32a3348)
,D/GCM     ( 1506): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1506): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,E/SQLiteLog( 3658): (284) automatic index on view_events(_id),
,V/GmsCoreStatsServiceLauncher( 1822): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,D/WearableService( 3587): callingUid 10011, callindPid: 3587
,D/LocationInitializer( 1822): Restart initialization of location
,I/ActivityManager(  821): Start proc 3680:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
,E/MDM     ( 1848): [167] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ActivityThread( 3680): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/Gmail   ( 3680): getAccountsCursor
,I/ActivityManager(  821): Start proc 3703:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 17092(833KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 26MB/42MB, paused 745us total 36.365ms
,W/ActivityManager(  821): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 3680): Observing account changes for notifications
,I/Exchange( 3703): EasService.onCreate
,I/Exchange( 3703): RestartPingTask
,I/Exchange( 3703): RestartPingsTask did not start any pings.
,I/Exchange( 3703): PSS stopIfIdle
I/Exchange( 3703): PSS has no active accounts; stopping service.
,W/GAV2    ( 3680): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 3680): getAccountsCursor
,I/Exchange( 3703): onDestroy
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  821): Start proc 3737:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,E/SQLiteLog( 3680): (283) recovered 14 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 3680): notifyAccountChanged
,I/Gmail   ( 3680): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3680): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     (  821): Explicit concurrent mark sweep GC freed 12162(617KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.568ms total 47.183ms
,W/ResourcesManager( 3737): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Gmail   ( 3680): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3680): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3680): getAccountsCursor
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3680): getAccountsCursor
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotifUtils( 3680): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/NotifUtils( 3680): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,I/ActivityManager(  821): Killing 3299:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=14.12 rxSuccessRate=14.83 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2462,5220
,I/Babel_SMS( 3737): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3737): MmsConfig.loadMmsSettings
,I/Babel_SMS( 3737): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 3737): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3737): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3737): MmsConfig.loadFromResources
,E/Babel_SMS( 3737): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 3737): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 3737): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3737): startup - clean
,I/Babel   ( 3737): deleted: false for 0
,I/Babel_telephony( 3737): TeleModule.launchCompleted
,W/Telecom (  821): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 3737): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3737): BAM#gBA: invalid account id: -1
W/Babel   ( 3737): BAM#gBA: invalid account id: -1
,I/Babel_telephony( 3737): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  821): TelecomServiceImpl: null is not visible for the calling user
,W/VideoCapabilities( 3737): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3737): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 3737): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3737): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3737): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3737): Unrecognized profile 2130706433 for video/avc
,I/CalendarProvider2( 3658): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3658): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/vclib   ( 3737): onServiceConnected
,W/Babel   ( 3737): Attempted to change video mute state without an active call.
,I/ActivityManager(  821): Killing 3327:com.google.android.keep/u0a79 (adj 15): empty #17
,W/ResourcesManager( 3737): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3737): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3737): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3737): Installed default security provider GmsCore_OpenSSL
,D/PackageBroadcastService( 1822): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1822): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 1534): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1313): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3308bb63 new=com.google.android.velvet.VelvetApplication@3308bb63
,I/Icing   ( 1822): updateResources: need to parse f{com.google.android.gms}
,I/Babel_telephony( 3737): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,W/VideoCapabilities( 3737): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3737): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3737): Unrecognized profile 2130706433 for video/avc
,I/UpdateIcingCorporaServi( 1534): UpdateCorporaTask done [took 32 ms] updated apps [took 32 ms] 
,I/ActivityManager(  821): Start proc 3790:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.InternalReceiver
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 3737): UserRecoverableAuthException.
,E/Babel   ( 3737): eei: BadAuthentication
E/Babel   ( 3737): 	at eeg.a(Unknown Source)
E/Babel   ( 3737): 	at eeg.a(Unknown Source)
E/Babel   ( 3737): 	at eeg.a(Unknown Source)
E/Babel   ( 3737): 	at g.a(Unknown Source)
E/Babel   ( 3737): 	at cae.a(SourceFile:3089)
E/Babel   ( 3737): 	at cae.a(SourceFile:1131)
E/Babel   ( 3737): 	at cws.a(SourceFile:4333)
E/Babel   ( 3737): 	at cws.a(SourceFile:1419)
E/Babel   ( 3737): 	at crl.a(SourceFile:492)
E/Babel   ( 3737): 	at crl.a(SourceFile:1468)
E/Babel   ( 3737): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3737): 	at cas.b(SourceFile:106)
E/Babel   ( 3737): 	at cap.d(SourceFile:335)
E/Babel   ( 3737): 	at caq.run(SourceFile:81)
E/Babel   ( 3737): Error getting auth token
E/Babel   ( 3737): dvm
E/Babel   ( 3737): 	at g.a(Unknown Source)
E/Babel   ( 3737): 	at cae.a(SourceFile:3089)
E/Babel   ( 3737): 	at cae.a(SourceFile:1131)
E/Babel   ( 3737): 	at cws.a(SourceFile:4333)
E/Babel   ( 3737): 	at cws.a(SourceFile:1419)
E/Babel   ( 3737): 	at crl.a(SourceFile:492)
E/Babel   ( 3737): 	at crl.a(SourceFile:1468)
E/Babel   ( 3737): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3737): 	at cas.b(SourceFile:106)
E/Babel   ( 3737): 	at cap.d(SourceFile:335)
E/Babel   ( 3737): 	at caq.run(SourceFile:81)
,E/Babel   ( 3737): Account registration failed 1-Redacted-21
E/Babel   ( 3737): cyp: null -- null
E/Babel   ( 3737): 	at cae.a(SourceFile:3121)
E/Babel   ( 3737): 	at cae.a(SourceFile:1131)
E/Babel   ( 3737): 	at cws.a(SourceFile:4333)
E/Babel   ( 3737): 	at cws.a(SourceFile:1419)
E/Babel   ( 3737): 	at crl.a(SourceFile:492)
E/Babel   ( 3737): 	at crl.a(SourceFile:1468)
E/Babel   ( 3737): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3737): 	at cas.b(SourceFile:106)
E/Babel   ( 3737): 	at cap.d(SourceFile:335)
E/Babel   ( 3737): 	at caq.run(SourceFile:81)
,I/art     ( 3737): Note: end time exceeds epoch: 
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1506): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 3737): Unexpected exception while authenticating.
,E/Babel   ( 3737): eej: User intervention required. Notification has been pushed.
E/Babel   ( 3737): 	at eeg.b(Unknown Source)
E/Babel   ( 3737): 	at eeg.b(Unknown Source)
E/Babel   ( 3737): 	at g.a(Unknown Source)
E/Babel   ( 3737): 	at cae.b(SourceFile:1146)
E/Babel   ( 3737): 	at dcg.run(SourceFile:5617)
E/Babel   ( 3737): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 3737): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 3737): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 3737): connection state changed from UNKNOWN to CONNECTED
,I/MusicLeanback( 3100): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3100): Stop autocaching.
,D/GCM     ( 1506): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1506): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1822): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1848): [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3100): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 1822): Restart initialization of location
,E/GmsUtils( 3100): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  821): Killing 3350:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3732f4ec mBinding = false
,D/BluetoothManagerService(  821): Message: 2
,D/BluetoothManagerService(  821): Sending off request.
,D/BluetoothAdapterState( 2177): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2177): Setting state to 13
I/BluetoothAdapterState( 2177): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 2177): onBluetoothDisable()
,I/BluetoothAdapterState( 2177): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2177): Scan Mode:20,
,D/BluetoothAdapterState( 2177): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true,
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
W/bt-btif ( 2177): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 12 -> 13,
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration,
D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
E/BtOppRfcommListener( 2177): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothMapMasInstance( 2177): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2177): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2177): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/BluetoothMapService( 2177): onReceive
,D/BluetoothMapService( 2177): STATE_TURNING_OFF
,D/BluetoothMapService( 2177): MAP Service closeService in
D/BluetoothMapMasInstance( 2177): MAP Service shutdown
,I/BtOppRfcommListener( 2177): stopping Accept Thread
I/BtOppRfcommListener( 2177): BluetoothSocket listen thread finished
D/WifiService(  821): New client listening to asynchronous messages
D/WifiService(  821): setWifiEnabled: false pid=3407, uid=10272
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 3424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3424): finishStartingService: stopping service
,D/BluetoothPbap( 3424): Proxy object disconnected
,D/PbapServerProfile( 3424): Bluetooth service disconnected
,D/AuthorizationBluetoothService( 1506): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,I/jxcore-log( 3407): ****TEST TOOK:  5144  ms ****
I/jxcore-log( 3407): 
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 3407): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3407): 
,D/CommandListener(  355): Clearing all IP addresses on wlan0
V/NativeCrypto( 1506): Read error: ssl=0xaecde200: I/O error during system call, Connection timed out
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 1506): SSL shutdown failed: ssl=0xaecde200: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011,
E/WifiStateMachine(  821): scanCount==0 - aborting
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/WifiScanningService(  821): SCAN_AVAILABLE : 1
D/RttService(  821): SCAN_AVAILABLE : 1,
D/WifiScanningService(  821): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState
D/RttService(  821): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
,D/CommandListener(  355): Clearing all IP addresses on wlan0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,E/WifiStateMachine(  821): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 1068): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/wpa_supplicant( 1200): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  821): Start proc 3856:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/wpa_supplicant( 1200): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  821): MasterInitialState.processMessage what=3
,E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/NetworkMonitor( 3100): type=WIFI subType= reason=null isConnected=false
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,W/bt-btif ( 2177): ag scb idx 1 not allocated
E/bt-btif ( 2177): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2177): RX termination
W/bt_userial( 2177): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2177): Leaving userial_read_thread()
D/bt_userial( 2177): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2177): hw_epilog_process
I/bt_userial_vendor( 2177): device fd = 53 close
,D/AndroidRuntime( 3854): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3854): CheckJNI is OFF
,I/GKI_LINUX( 2177): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2177): GKI_exit_task 0 done
I/GKI_LINUX( 2177): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2177): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 2177): Received stop request...Stopping profile...
,D/BluetoothHeadset(  821): Proxy object disconnected
,D/HeadsetStateMachine( 2177): Exit Disconnected: -1
D/BluetoothHeadset( 1068): Proxy object disconnected
D/A2dpService( 2177): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2177): Exit Disconnected: -1
,D/BluetoothHeadset( 3424): Proxy object disconnected
D/HeadsetProfile( 3424): Bluetooth service disconnected
,D/BluetoothA2dp( 1068): Proxy object disconnected
,D/BluetoothHeadset( 1280): Proxy object disconnected
,D/BluetoothA2dp( 3424): Proxy object disconnected
D/HeadsetStateMachine( 2177): Unbinding service...
D/A2dpProfile( 3424): Bluetooth service disconnected
I/wpa_supplicant( 1200): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  821): InitialState.processMessage what=4,
D/BluetoothHeadset(  821): Proxy object disconnected
D/BluetoothHeadset(  821): Proxy object disconnected
E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/BluetoothAdapterState( 2177): Stopping profile services that were post enabled
,D/BluetoothA2dp(  821): Proxy object disconnected
,D/Tethering(  821): sendTetherStateChangedBroadcast 0, 0, 0
W/BluetoothHeadsetServiceJni( 2177): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2177): Cleaning up Bluetooth Handsfree callback object
D/HidService( 2177): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 1068): Proxy object disconnected
D/HealthService( 2177): Received stop request...Stopping profile...
W/Settings( 1848): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GKI_LINUX( 2177): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2177): GKI_exit_task 2 done
I/GKI_LINUX( 2177): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/PanService( 2177): Received stop request...Stopping profile...
D/BluetoothPan( 1068): BluetoothPAN Proxy object disconnected
D/BtGatt.DebugUtils( 2177): handleDebugAction() action=null
D/BluetoothInputDevice( 3424): Proxy object disconnected
D/HidProfile( 3424): Bluetooth service disconnected
,D/BluetoothPan( 3424): BluetoothPAN Proxy object disconnected
D/PanProfile( 3424): Bluetooth service disconnected
D/BtGatt.GattService( 2177): Received stop request...Stopping profile...
D/BtGatt.GattService( 2177): stop()
D/BtGatt.AdvertiseManager( 2177): advertise clients cleared
W/Settings( 3737): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothMapService( 2177): Received stop request...Stopping profile...
,D/BluetoothMapService( 2177): stop()
,D/BluetoothMapEmailAppObserver( 2177): deinitObservers()
D/BluetoothMapEmailAppObserver( 2177): removeReceiver()
,D/BluetoothMap( 1068): Proxy object disconnected
D/BluetoothMap( 3424): Proxy object disconnected
,D/MapProfile( 3424): Bluetooth service disconnected
W/BluetoothHidServiceJni( 2177): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2177): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2177): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2177): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2177): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2177): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2177): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2177): MAP Service closeService in
D/BluetoothAdapterState( 2177): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 2177): cleanup()
D/BluetoothAdapterProperties( 2177): Setting state to 10
D/BluetoothMapService( 2177): MAP Service closeService in
I/BluetoothAdapterState( 2177): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(false) to 19 receivers.
I/BluetoothAdapterState( 2177): Entering OffState
,D/BluetoothMap( 3424): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1068): onBluetoothStateChange: up=false
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false,
,D/BluetoothAvrcpController( 1068): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1068): 
E/BluetoothAvrcpController( 1068): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@2bb8dcf5
E/BluetoothAvrcpController( 1068): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1068): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1068): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551),
E/BluetoothAvrcpController( 1068): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1068): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1068): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset( 1068): onBluetoothStateChange: up=false,
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3424): onBluetoothStateChange: up=false
D/BluetoothPbap( 3424): onBluetoothStateChange: up=false
D/BluetoothMap( 1068): onBluetoothStateChange: up=false,
D/BluetoothHeadset( 1280): onBluetoothStateChange: up=false
D/BluetoothHeadset( 3424): onBluetoothStateChange: up=false
D/BluetoothA2dp(  821): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3424): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
D/BluetoothA2dpSink( 1068): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1068): 
E/BluetoothA2dpSink( 1068): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@b86ea8a
E/BluetoothA2dpSink( 1068): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1068): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1068): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1068): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1068): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1068): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothInputDevice( 1068): onBluetoothStateChange: up=false
D/BluetoothHeadsetClient( 1068): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1068): 
E/BluetoothHeadsetClient( 1068): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@34a418fb
E/BluetoothHeadsetClient( 1068): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1068): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1068): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1068): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1068): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1068): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothManagerService(  821): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  821): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3732f4ec mBinding = false
,D/BluetoothManagerService(  821): Sending unbind request.
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1068): 117910321: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1068): 117910321: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1068): 117910321: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 17606(936KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 952us total 23.612ms
,D/AndroidRuntime( 3854): Calling main entry com.android.commands.pm.Pm
,I/art     (  821): Explicit concurrent mark sweep GC freed 26419(1352KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.255ms total 69.094ms
,I/GKI_LINUX( 2177): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2177): GKI_exit_task 1 done
I/GKI_LINUX( 2177): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2177): cleanupNative: return from cleanup
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3407:com.example.hello/u0a272 (adj 0): stop com.example.hello
,I/art     ( 2177): System.exit called, status: 0
I/AndroidRuntime( 2177): VM exiting with result code 0, cleanup skipped.
,W/PackageSettings(  821): Skipping PackageSetting{34142857 com.test.thalitest/10265} due to missing metadata
,I/WindowState(  821): WIN DEATH: Window{26f92375 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  821): Client connection lost with reason: 4
,W/ActivityManager(  821): Force removing ActivityRecord{12ec0c54 u0 com.example.hello/.MainActivity t22}: app died, no saved state
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=0: pkg removed
,I/ActivityManager(  821): Process com.android.bluetooth (pid 2177) has died
,W/ActivityManager(  821): Spurious death for ProcessRecord{3bc2f16d 3407:com.example.hello/u0a272}, curProc for 3407: null
,I/Keyboard.Facilitator( 1217): resetDictionaries() : en_US
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1217): run()
,D/TaskPersister(  821): removeObsoleteFile: deleting file=22_task.xml
,I/Decoder ( 1217): createOrResetDecoder
V/MusicLeanback( 3100): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/art     ( 1068): Explicit concurrent mark sweep GC freed 46298(1959KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 3.040ms total 63.076ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1217): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1217): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/ActivityManager(  821): Start proc 3900:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1217): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1217): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1217): run()
I/StatsUtilsManager( 1217): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1217): shouldRecordStats() = Too Soon
,D/SprintDMReceiver( 3900): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3407 uid 10272
I/Keyboard.Facilitator( 1217): onFinishInput()
,D/SprintDMHelper( 3900): simOperator:  IMSI: null
,D/SprintDMReceiver( 3900): Not Sprint UICC, don't do anything.
I/ActivityManager(  821): Killing 3372:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/art     (  821): Explicit concurrent mark sweep GC freed 12666(949KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.837ms total 143.862ms
,I/art     ( 3854): System.exit called, status: 0
,I/AndroidRuntime( 3854): VM exiting with result code 0.
,I/SystemUpdateService( 1822): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,W/LocationOracleImpl( 1534): Best location was null
,D/Launcher.Workspace( 1313): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1313): 11683562 - stripEmptyScreens()
,D/SystemUpdateService( 1822): onCreate
,D/SystemUpdateService( 1822): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/HotwordRecognitionRnr( 1534): Starting hotword detection.
,I/MicrophoneInputStream( 1534): mic_starting com.google.android.apps.gsa.speech.audio.u@61c8216
,E/ClearcutLoggerIntentService( 1506): could not write to store: java.io.IOException: Could not end transaction after writing to SQLite
,E/SQLiteLog( 1506): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ClearcutLoggerIntentService( 1506): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1506): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1506): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1506): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1506): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1506): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ClearcutLoggerIntentService( 1506): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1506): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1506): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1506): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1506): 	at java.lang.Thread.run(Thread.java:818)
,I/iu.Environment( 1822): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
E/SQLiteLog( 1506): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
E/ClearcutLoggerIntentService( 1506): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1506): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1506): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1506): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1506): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1506): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1506): 	at java.lang.Thread.run(Thread.java:818)
I/iu.UploadsManager( 1822): num queued entries: 0
E/SQLiteLog( 1822): (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
I/AudioFlinger(  359): AudioFlinger's thread 0xb4063000 ready to run
I/MicrophoneInputStream( 1534): mic_started com.google.android.apps.gsa.speech.audio.u@61c8216
I/SystemUpdateService( 1822): active receiver: enabled
D/ChimeraCfgMgr( 1822): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
--------- beginning of crash
E/AndroidRuntime( 1822): FATAL EXCEPTION: iu-sync-manager
E/AndroidRuntime( 1822): Process: com.google.android.gms, PID: 1822
E/AndroidRuntime( 1822): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1822): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1822): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1822): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1822): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1822): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/AndroidRuntime( 1822): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/AndroidRuntime( 1822): 	at com.google.android.libraries.social.autobackup.ad.a(SourceFile:403)
E/AndroidRuntime( 1822): 	at com.google.android.libraries.social.autobackup.i.a(SourceFile:307)
E/AndroidRuntime( 1822): 	at com.google.android.libraries.social.autobackup.i.b(SourceFile:43)
E/AndroidRuntime( 1822): 	at com.google.android.libraries.social.autobackup.k.handleMessage(SourceFile:218)
E/AndroidRuntime( 1822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1822): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SystemUpdateService( 1822): showing system update notification
D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
I/Babel   ( 3737): connection state changed from CONNECTED to DISCONNECTED
,E/Search.SharedPreferencesProto( 1534): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  821): Start proc 3933:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
W/ResourcesManager(  821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
,D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,I/CheckinService( 1822): Done disabling old GoogleServicesFramework version
,D/Atlas   (  821): Validating map...
,I/ValidateNoPeople(  821): skipping global notification
,I/HotwordWorker( 1534): onReady
V/SystemUpdateService( 1822): retry (wakeup: false) in 3599917 ms
,D/SystemUpdateService( 1822): onDestroy
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  821): Initialized EGL, version 1.4
,D/OpenGLRenderer(  821): Enabling debug mode 0
,I/GAv4    ( 3933): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3933):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3933):   adb logcat -s GAv4
,W/GAv4    ( 3933): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3933): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3933): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3933): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3933): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 3933): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3933): Failed to open database '/data/data/com.google.android.apps.magazines/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3933): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3933): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3933): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj.zzb(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj.zzie(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj.isEmpty(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzl.zzis(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzl$3.run(Unknown Source)
E/SQLiteDatabase( 3933): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3933): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3933): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3933): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3933): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
E/GAv4    ( 3933): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 3933): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3933): Failed to open database '/data/data/com.google.android.apps.magazines/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3933): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3933): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3933): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3933): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj.zzb(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj.zzie(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzj.isEmpty(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzl.zzis(Unknown Source)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.analytics.internal.zzl$3.run(Unknown Source)
E/SQLiteDatabase( 3933): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3933): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3933): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3933): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3933): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3933): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
E/GAv4    ( 3933): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 3933): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/QMI_FW  (  821): xport_send: Sendto failed for port 3840
E/LocSvc_api_v02(  821): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659524371
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/GAv4    ( 3933): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3933): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 3933): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 3933): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3933): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3933): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 3933): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3933): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/HotwordDetector( 1534): Closing mic
I/MicrophoneInputStream( 1534): mic_close com.google.android.apps.gsa.speech.audio.u@61c8216
,E/Search.SharedPreferencesProto( 1534): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  821): Killing 3546:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,W/OpenGLRenderer( 1313): Incorrectly called buildLayer on View: ew, destroying layer...
,D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1534): Hotword detection finished
I/HotwordRecognitionRnr( 1534): Stopping hotword detection.
,E/qdoverlay(  260): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  260): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  260): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  260): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  260): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  260): MdpCtrl close error in unset
,E/NSDepend( 3933): Could not load library: pdflib.dex.jar
E/NSDepend( 3933): java.io.FileNotFoundException: /data/data/com.google.android.apps.magazines/app_dex/pdflib.dex.jar: open failed: EROFS (Read-only file system)
E/NSDepend( 3933): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/NSDepend( 3933): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/NSDepend( 3933): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:202)
E/NSDepend( 3933): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:190)
E/NSDepend( 3933): 	at com.google.common.io.ByteSink.writeFrom(ByteSink.java:138)
E/NSDepend( 3933): 	at com.google.apps.dots.android.newsstand.NSDepend.dynamicallyLoadLibrary(NSDepend.java:1368)
E/NSDepend( 3933): 	at com.google.apps.dots.android.newsstand.NSDepend.getClassLoaderForJar(NSDepend.java:1315)
E/NSDepend( 3933): 	at com.google.apps.dots.android.newsstand.NSDepend$3.doInBackground(NSDepend.java:1348)
E/NSDepend( 3933): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:56)
E/NSDepend( 3933): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:52)
E/NSDepend( 3933): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/NSDepend( 3933): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/NSDepend( 3933): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/NSDepend( 3933): 	at com.google.android.libraries.bind.async.Queue$3$1.run(Queue.java:103)
E/NSDepend( 3933): 	at java.lang.Thread.run(Thread.java:818)
E/NSDepend( 3933): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/NSDepend( 3933): 	at libcore.io.Posix.open(Native Method)
E/NSDepend( 3933): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/NSDepend( 3933): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/NSDepend( 3933): 	... 14 more
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
E/qdoverlay(  260): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  260): MdpCtrl close error in unset

```
