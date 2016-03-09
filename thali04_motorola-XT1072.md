#### Test 61703351436c7c0_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,D/CAR.SERVICE( 5104): mConnectedToCar = false, abort
--------- beginning of system
E/ActivityThread( 5104): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@219195dd that was originally bound here
E/ActivityThread( 5104): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@219195dd that was originally bound here
E/ActivityThread( 5104): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5104): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5104): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5104): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5104): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5104): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5104): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5104): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5104): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5104): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5104): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5104): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5104): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5104): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5104): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5104): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5104): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5104): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5104): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5104): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5104): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5104): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5104): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/ActivityThread( 5104): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2fdcf74c that was originally bound here
E/ActivityThread( 5104): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2fdcf74c that was originally bound here
E/ActivityThread( 5104): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5104): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5104): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5104): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5104): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5104): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5104): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5104): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5104): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5104): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5104): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5104): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5104): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5104): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5104): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5104): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5104): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5104): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5104): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5104): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5104): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5104): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ActivityManager(  884): Unbind failed: could not find connection for android.os.BinderProxy@35156ed5
D/AndroidRuntime( 5150): 
D/AndroidRuntime( 5150): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5150): CheckJNI is OFF
V/AlarmManager(  884): send {2fa346ea, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
V/AlarmManager(  884): done {2fa346ea, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [8ms]
E/SQLiteLog( 4992): (284) automatic index on view_events(_id)
D/AndroidRuntime( 5150): Calling main entry com.android.commands.am.Am
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (146 us)
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5150): Shutting down VM
I/ActivityManager(  884): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5170 uid=10564 gids={50564, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5170): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5170): Time to load native libraries: 1 ms (timestamps 3023-3024)
I/LibraryLoader( 5170): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5170): Binding Chromium to main looper Looper (main, tid 1) {16e899d5}
I/LibraryLoader( 5170): Expected native library version number "",actual native library version number ""
I/chromium( 5170): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5170): Initializing chromium process, singleProcess=true
W/art     ( 5170): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5170): ApplicationContext is null in ApplicationStatus
W/chromium( 5170): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5170): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5170): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5170): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5170): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5170): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5170): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5170): Local Branch: 
I/Adreno-EGL( 5170): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5170): Local Patches: NONE
I/Adreno-EGL( 5170): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cf55654:true
D/BluetoothAdapter( 5170): 877668022: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5170): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5170): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5170): CordovaWebView is running on device made by: motorola
W/art     ( 5170): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5170): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5170): Render dirty regions requested: true
,D/Atlas   ( 5170): Validating map...
,W/chromium( 5170): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5170): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5170): Enabling debug mode 0
,I/Keyboard.Facilitator( 1407): onFinishInput()
,I/LaunchCheckinHandler(  884): Displayed com.example.hello/.MainActivity,cp,ca,945
I/ActivityManager(  884): Displayed com.example.hello/.MainActivity: +946ms
,E/Adreno-ES20( 5170): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5170): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5170): Cannot call determinedVisibility() - never saw a connection for the pid: 5170
,I/chromium( 5170): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5170): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5170): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 5170): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5170): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5170): JniHelper::setJavaVM(0xb8a4a310), pthread_self() = -1193324872
,W/jxcore-log( 5170): Initializing JXcore engine
W/jxcore-log( 5170): JXcore engine is ready
,I/SFPerfTracer(  279):      triggers: (rate: 13:527) (compose: 0:1) (post: 0:1) (render: 0:2) (29:957 frames) (30:1041)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb8a354b0): 0:15)* (DimLayer (0xb89fd2c0): 0:6)* (StatusBar (0xb8a26358): 0:152) (NavigationBar (0xb8a27cc0): 0:26) (com.android.systemui.ImageWallpaper (0xb8a299d8): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8a5fa40): 0:55)- (Starting com.example.hello (0xb8a4c3a8): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb8a00090): 30:37) 
,W/Thread-587( 5224): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10564 path="socket:[7507]" dev="sockfs" ino=7507 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-587( 5224): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10564 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-587( 5224): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10564 path="socket:[7684]" dev="sockfs" ino=7684 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-587( 5224): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10564 path="socket:[21146]" dev="sockfs" ino=21146 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5170): Starting JXcore engine
,W/jxcore-log( 5170): Platform android
W/jxcore-log( 5170): 
,W/jxcore-log( 5170): Process ARCH arm
W/jxcore-log( 5170): 
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:301 vsyncs) (2:1043)
,I/jxcore-log( 5170): JXcore Cordova bridge is ready!
I/jxcore-log( 5170): 
,W/jxcore-log( 5170): JXcore engine is started
,E/jxcore  ( 5170): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 5170): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/ActivityManager(  884): Killing 3048:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/ActivityManager(  884): Killing 5064:com.motorola.context/u0a8 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10049/pid_3048/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10008/pid_5064/cgroup.procs: No such file or directory
,D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:36000 mC
,V/AlarmManager(  884): send {129c75a1, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  884): done {129c75a1, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [9ms]
,V/AlarmManager(  884): send {33fb53c6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  884): done {33fb53c6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=319, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311475, SEQNUM=4349, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-23437, POWER_SUPPLY_CHARGE_COUNTER=-354, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/AlarmManager(  884): send {25a28eb4, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  884): done {25a28eb4, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [19ms]
,D/Finsky  ( 4951): [560] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4951): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:35000 mC
,I/MMApiBackOffService( 2552): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2552): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 5078(221KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 885us total 29.098ms
,D/MMApiWebService( 2552): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2552):  Nonce Reponse 
I/MMApiWebService( 2552): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2552): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2552): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2552): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2552): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2552): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2552): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2552): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2552): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:34000 mC
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=309, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311303, SEQNUM=4357, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-25040, POWER_SUPPLY_CHARGE_COUNTER=-457, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=306, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311286, SEQNUM=4365, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-26742, POWER_SUPPLY_CHARGE_COUNTER=-491, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 2552): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2552): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  884): Explicit concurrent mark sweep GC freed 15685(803KB) AllocSpace objects, 4(143KB) LOS objects, 33% free, 20MB/30MB, paused 1.559ms total 114.560ms
,D/MMApiWebService( 2552): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2552):  Nonce Reponse 
I/MMApiWebService( 2552): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2552): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2552): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2552): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2552): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2552): Explicit concurrent mark sweep GC freed 19020(1202KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.094ms total 131.779ms
,D/MMApiWebService( 2552): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2552): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2552): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2552): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  884): send {2224e4a9, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): done {2224e4a9, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
,I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1695): onCreate
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  884): send {38bd37d9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  884): send {33fb53c6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  884): done {38bd37d9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [17ms]
,V/AlarmManager(  884): done {33fb53c6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [21ms]
,I/ConfigService( 1695): onDestroy
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310560, SEQNUM=4373, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-27343, POWER_SUPPLY_CHARGE_COUNTER=-763, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  884): Nap time (uid 1000)...
,I/PowerManagerService(  884): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  884): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  884): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  884): Build Date: 10/28/14 Tue
I/Adreno-EGL(  884): Local Branch: 
I/Adreno-EGL(  884): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  884): Local Patches: NONE
I/Adreno-EGL(  884): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  884): activate, handle: 1598182242, enabled: 0, index 2
D/        (  884): BstSensorExt: id=1598182242, en=0
,D/        (  884): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 225
,D/        (  884): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  884): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  884): Display changed displayId=0
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb8924550
,D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/rmt_storage(  309): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7ff6820
I/rmt_storage(  309): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  309): wakelock acquired: 1, error no: 42
,I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1207999176)
,I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1207999176) wakelock released: 1, error no: 0
I/rmt_storage(  309): 
,I/rmt_storage(  309): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7ff6820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
I/SFPerfTracer(  279):       trigger: frame rate (-33.609%)	(39.835 fps)	(25.104 ms) 	(4 drops)	(14 frames)
I/SFPerfTracer(  279):      triggers: (rate: 14:534) (compose: 0:1) (post: 0:1) (render: 0:2) (14:1008 frames) (15:1109)
D/SFPerfTracer(  279):        layers: (6:11) (FocusedStackFrame (0xb8a354b0): 0:16)* (DimLayer (0xb8a5a6c8): 0:15) (DimLayer (0xb89fd2c0): 0:6)* (StatusBar (0xb8a26358): 0:158) (NavigationBar (0xb8a27cc0): 0:26) (com.android.systemui.ImageWallpaper (0xb8a299d8): 0:8)* (com.example.hello/com.example.hello.MainActivity (0xb8a00090): 0:50) (com.example.hello/com.example.hello.MainActivity (0xb8a4c3a8): 0:34) (ColorFade (0xb8a5fa40): 15:17) 
,D/SurfaceControl(  884): Excessive delay in setPowerMode(): 329ms
,I/PowerManagerService(  884): Sleeping (uid 1000)...
,I/WindowManager(  884): AOD feature not enabled!
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  314): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  314): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  314): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  314): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  314): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  314): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2dbe89c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb8a4a310, mCls = 0x1952
I/WifiNative-HAL(  884): Could not start hal
D/WifiStateMachine(  884): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  884): setSuspendOptimizations: 4 false
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 4
,D/        (  884): activate, handle: 1598182229, enabled: 0, index 0
,E/        (  884): <BST> disable accel, orig state: 1
I/        (  884): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2dbe89c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb8a4a310, mCls = 0x20192a
I/WifiNative-HAL(  884): Could not start hal
D/WifiStateMachine(  884): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: false
D/audio_hw_primary(  314): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  314): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  314): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  314): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  314): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  884): setSuspendOptimizations: 4 true
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  884): send {2667d538, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  884): done {2667d538, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  884): send {38bd37d9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): done {38bd37d9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,E/global frequency( 2552): no tags to log
,D/Checkin ( 2552): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/AlarmManager(  884): send {35610ce4, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  884): done {35610ce4, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 52869(2MB) AllocSpace objects, 33(1041KB) LOS objects, 39% free, 7MB/12MB, paused 6.475ms total 59.390ms
,D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2552): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2552): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 4114(171KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 815us total 39.722ms
,D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2552): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2552): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2552): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2552): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2552): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2552): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2552): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/art     (  884): Explicit concurrent mark sweep GC freed 11681(651KB) AllocSpace objects, 2(192KB) LOS objects, 33% free, 20MB/30MB, paused 1.469ms total 121.779ms
,I/global frequency( 2552): BcsDSCheckin.events found events 2000
,D/Checkin ( 2552): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2552): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2552): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2552): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2552): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2552): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2552): unknown error code mapping for: 0
,I/global frequency( 2552): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2552): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/MMApiBackOffService( 2552): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2552): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2552): Explicit concurrent mark sweep GC freed 39209(3MB) AllocSpace objects, 6(148KB) LOS objects, 40% free, 11MB/18MB, paused 1.076ms total 71.112ms
,D/MMApiWebService( 2552): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2552):  Nonce Reponse 
I/MMApiWebService( 2552): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2552): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2552): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/ClearcutLoggerApiImpl( 1695): disconnect managed GoogleApiClient
,I/MMApiBackOffService( 2552): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2552): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2552): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2552): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2552): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2552): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  884): send {2898254d, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  884): send {2224e4a9, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  884): send {33fb53c6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  884): send {38bd37d9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): done {2898254d, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [7ms]
,V/AlarmManager(  884): done {33fb53c6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [26ms]
V/AlarmManager(  884): done {38bd37d9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [26ms]
,V/AlarmManager(  884): done {2224e4a9, *alarm*:android.intent.action.TIME_TICK} [54ms]
,I/VacuumService( 1695): Vacuum at: now=1457533453883 tag=VacuumService
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311573, SEQNUM=4384, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15224, POWER_SUPPLY_CHARGE_COUNTER=-1061, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  312): NetlinkHandler, power_supply subsys
I/MDMCTBK (  312): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  312): checkDefaultInst, current pid is = 312
I/MDMCTBK (  312): checkDefaultInst, pid match
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  312): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  312): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 5369): 
D/AndroidRuntime( 5369): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5369): CheckJNI is OFF
D/AndroidRuntime( 5369): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  884): Force stopping com.example.hello appid=10564 user=-1: uninstall pkg
I/ActivityManager(  884): Killing 5170:com.example.hello/u0a564 (adj 0): stop com.example.hello
I/WindowState(  884): WIN DEATH: Window{3f44fc84 u0 com.example.hello/com.example.hello.MainActivity}
I/WindowState(  884): WIN DEATH: Window{58f3c25 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  884): Skipping PackageSetting{432cb7c com.test.thalitest/10563} due to missing metadata
I/ActivityManager(  884):   Force finishing activity ActivityRecord{a90f078 u0 com.example.hello/.MainActivity t9}
V/ActivityManager(  884): Display changed displayId=0
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  884): Spurious death for ProcessRecord{c941350 5170:com.example.hello/u0a564}, curProc for 5170: null
I/ActivityManager(  884): Force stopping com.example.hello appid=10564 user=0: pkg removed
I/ActivityManager(  884):   Force finishing activity ActivityRecord{a90f078 u0 com.example.hello/.MainActivity t9 f}
W/ActivityManager(  884): Duplicate finish request for ActivityRecord{a90f078 u0 com.example.hello/.MainActivity t9 f}
I/art     ( 2981): Explicit concurrent mark sweep GC freed 2920(626KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 7MB/12MB, paused 709us total 29.412ms
I/art     ( 1557): Explicit concurrent mark sweep GC freed 7328(533KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 467us total 47.115ms
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1695): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1407): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1407): run()
I/Decoder ( 1407): createOrResetDecoder
I/art     ( 1942): Explicit concurrent mark sweep GC freed 763(34KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 1.231ms total 78.581ms
I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5394 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/OtaApp  ( 2552): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2552): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2552): [info] > Exceed max defer attempts for optional update, suppresing later btn
I/ConfigService( 1695): onCreate
D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2552): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2552): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
I/art     (  884): Explicit concurrent mark sweep GC freed 10973(768KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.428ms total 145.063ms
I/art     (  884): WaitForGcToComplete blocked for 125.095ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1407): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1407): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1407): run()
I/StatsUtilsManager( 1407): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1407): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5394): Cleaning up data for package: com.example.hello
I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5422 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5394): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  884): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task.xml
I/art     (  884): Explicit concurrent mark sweep GC freed 4536(257KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.348ms total 180.337ms
W/InputMethodManagerService(  884): Got RemoteException sending setActive(false) notification to pid 5170 uid 10564
I/Keyboard.Facilitator( 1407): onFinishInput()
I/ActivityManager(  884): Killing 5104:com.google.android.gms:car/u0a16 (adj 15): empty #7
D/AndroidRuntime( 5369): Shutting down VM
W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_5104/cgroup.procs: No such file or directory
I/Launcher( 1557): Deferring update until onResume
W/asset   ( 5422): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5422): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5422): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5422): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5443 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  884): Killing 4774:com.android.defcontainer/u0a10 (adj 15): empty #7
W/libprocessgroup(  884): failed to open /acct/uid_10010/pid_4774/cgroup.procs: No such file or directory
W/ContextImpl( 5443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1942): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1942): Clearing selected account for com.example.hello
I/LocationSettingsChecker( 1942): Removing dialog suppression flag for package com.example.hello
D/ChimeraCfgMgr( 1942): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1942): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 5443): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5443): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5443): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 5443): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5443): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5443): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 5443): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 5443): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5443): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5443): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1942): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
E/AndroidRuntime( 5443): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5443): Process: com.android.keychain, PID: 5443
E/AndroidRuntime( 5443): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5443): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 5443): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5443): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5443): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 5443): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 5443): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5443): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5443): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DriveAsyncService( 1942): disk I/O error (code 3850)
E/DriveAsyncService( 1942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1942): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1942): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1942): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1942): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1942): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1942): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1942): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1695): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1695): Shutting down VM
E/AndroidRuntime( 1695): FATAL EXCEPTION: main
E/AndroidRuntime( 1695): Process: com.google.android.gms.persistent, PID: 1695
E/AndroidRuntime( 1695): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1695): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1695): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1695): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1695): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1695): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1695): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1695): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1695): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1695): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1695): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1695): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1695): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1695): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1695): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1695): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1695): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1695): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1695): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1695): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1695): 	... 9 more
E/PhenotypeInitializer( 1942): Could not unregister android package com.example.hello
E/PhenotypeInitializer( 1942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/PhenotypeInitializer( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 1942): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 1695): Sending signal. PID: 1695 SIG: 9
I/Process ( 5443): Sending signal. PID: 5443 SIG: 9
E/DropBoxManagerService(  884): Can't write: system_app_crash
E/DropBoxManagerService(  884): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  884): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  884): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  884): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  884): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  884): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  884): 	... 5 more
E/DropBoxManagerService(  884): Can't write: system_app_crash
E/DropBoxManagerService(  884): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  884): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  884): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  884): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  884): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  884): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  884): 	... 5 more
D/ChimeraCfgMgr( 1942): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1942): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 1942): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1942): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1942): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1942): Runtime exception while performing operation
E/ClearPendingStateOp( 1942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1942): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1942): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1942): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1942): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1942): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1942): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1942): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime( 1942): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1942): Process: com.google.android.gms, PID: 1942
E/AndroidRuntime( 1942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1942): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1942): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1942): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1942): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 1942): Sending signal. PID: 1942 SIG: 9
V/BackupManagerService(  884): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  884): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
D/WifiService(  884): Client connection lost with reason: 4
D/GpsStatusListenerHelper(  884): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@1bd7632b
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
D/ConnectivityService(  884): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@192e8388)
D/ConnectivityService(  884): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  884): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  884): Process com.android.keychain (pid 5443) has died
W/ActivityManager(  884): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
W/ActivityManager(  884): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  884): Killing 1942:com.google.android.gms/u0a16 (adj 0): crash
E/DropBoxManagerService(  884): Can't write: system_app_crash
E/DropBoxManagerService(  884): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  884): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  884): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  884): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  884): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  884): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  884): 	... 5 more
W/ActivityManager(  884): Spurious death for ProcessRecord{12ef12ca 1942:com.google.android.gms/u0a16}, curProc for 1942: null
W/ActivityManager(  884): Can't find mystery application for WTF from pid=1942 uid=10016: android.os.BinderProxy@2811a121

```
