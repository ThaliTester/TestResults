#### Test 6170335145aca32_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:36000 mC
D/AndroidRuntime( 5072): 
D/AndroidRuntime( 5072): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5072): CheckJNI is OFF
D/AndroidRuntime( 5072): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  878): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (242 us)
W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5072): Shutting down VM
I/ActivityManager(  878): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5091 uid=10561 gids={50561, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5091): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5091): Time to load native libraries: 2 ms (timestamps 7266-7268)
I/LibraryLoader( 5091): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5091): Binding Chromium to main looper Looper (main, tid 1) {3d42ae9d}
,I/LibraryLoader( 5091): Expected native library version number "",actual native library version number ""
I/chromium( 5091): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5091): Initializing chromium process, singleProcess=true
W/art     ( 5091): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5091): ApplicationContext is null in ApplicationStatus
,W/chromium( 5091): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5091): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5091): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5091): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5091): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5091): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5091): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5091): Local Branch: 
I/Adreno-EGL( 5091): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5091): Local Patches: NONE
I/Adreno-EGL( 5091): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  878): Message: 20
D/BluetoothManagerService(  878): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@276c1827:true
,D/BluetoothAdapter( 5091): 85504780: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5091): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5091): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5091): CordovaWebView is running on device made by: motorola
,W/art     ( 5091): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5091): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5091): Render dirty regions requested: true
,D/Atlas   ( 5091): Validating map...
,W/chromium( 5091): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:261 vsyncs) (45:1088)
,I/OpenGLRenderer( 5091): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5091): Enabling debug mode 0
,I/Keyboard.Facilitator( 1406): onFinishInput()
,I/LaunchCheckinHandler(  878): Displayed com.example.hello/.MainActivity,cp,ca,974
I/ActivityManager(  878): Displayed com.example.hello/.MainActivity: +974ms
,E/Adreno-ES20( 5091): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5091): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5091): Cannot call determinedVisibility() - never saw a connection for the pid: 5091
,I/chromium( 5091): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5091): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5091): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 5091): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5091): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5091): JniHelper::setJavaVM(0xb7ee7310), pthread_self() = -1205361392
,W/jxcore-log( 5091): Initializing JXcore engine
W/jxcore-log( 5091): JXcore engine is ready
,W/Thread-592( 5145): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10561 path="socket:[6544]" dev="sockfs" ino=6544 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-592( 5145): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10561 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-592( 5145): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10561 path="socket:[6653]" dev="sockfs" ino=6653 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-592( 5145): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10561 path="socket:[23585]" dev="sockfs" ino=23585 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5091): Starting JXcore engine
,W/jxcore-log( 5091): Platform android
W/jxcore-log( 5091): 
,W/jxcore-log( 5091): Process ARCH arm
W/jxcore-log( 5091): 
,I/jxcore-log( 5091): JXcore Cordova bridge is ready!
I/jxcore-log( 5091): 
W/jxcore-log( 5091): JXcore engine is started
,E/jxcore  ( 5091): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 5091): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/SFPerfTracer(  278):      triggers: (rate: 13:382) (compose: 0:1) (post: 0:1) (render: 0:2) (7:1063 frames) (8:1144)
D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb7c56ef0): 0:17)* (DimLayer (0xb7c0c1e0): 0:6)* (StatusBar (0xb7c11458): 0:144) (NavigationBar (0xb7bc5080): 0:21) (com.android.systemui.ImageWallpaper (0xb7bc8560): 0:9)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7c23d08): 0:52)- (Starting com.example.hello (0xb7c4f410): 0:41)- (com.example.hello/com.example.hello.MainActivity (0xb7c0efb0): 8:48) 
,D/TaskPersister(  878): removeObsoleteFile: deleting file=8_task_thumbnail.png
,V/AlarmManager(  878): send {2eb5d688, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  878): send {3ff9f821, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  878): send {3788b607, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  878): done {3788b607, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [13ms]
,V/AlarmManager(  878): done {2eb5d688, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [19ms]
,V/AlarmManager(  878): done {3ff9f821, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [24ms]
,D/Finsky  ( 4907): [575] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4907): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=329, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311322, SEQNUM=4325, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-20733, POWER_SUPPLY_CHARGE_COUNTER=-252, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:36000 mC
,I/ActivityManager(  878): Start proc com.google.android.calendar for service com.google.android.calendar/com.android.calendar.alerts.AlertService: pid=5177 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 5177): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  878): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5201 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5201): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5201): Created com.android.providers.calendar.CalendarAlarmManager@1f94fd47(com.android.providers.calendar.CalendarProvider2@385a974)
,I/AnalyticsLogBase( 5177): PlayLogger.onLoggerConnected
,I/CalendarProvider2( 5201): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5201): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  878): Killing 5015:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_5015/cgroup.procs: No such file or directory
,I/MMApiBackOffService( 2488): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2488): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 3909(164KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 707us total 30.263ms
,D/MMApiWebService( 2488): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2488):  Nonce Reponse 
I/MMApiWebService( 2488): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2488): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2488): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,W/ContextImpl( 5177): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5177): Thread[GAThread,5,main]: No campaign data found.
,I/MMApiBackOffService( 2488): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2488): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2488): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2488): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2488): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2488): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:35000 mC
,W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=319, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309912, SEQNUM=4334, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-355, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/art     (  878): Explicit concurrent mark sweep GC freed 16358(853KB) AllocSpace objects, 4(145KB) LOS objects, 33% free, 20MB/30MB, paused 1.475ms total 124.731ms
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:35000 mC
,I/ActivityManager(  878): Killing 4679:com.android.defcontainer/u0a10 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10010/pid_4679/cgroup.procs: No such file or directory
,V/AlarmManager(  878): send {7eafbe0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): done {7eafbe0, *alarm*:android.intent.action.TIME_TICK} [39ms]
,V/AlarmManager(  878): send {1c6e7164, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  878): done {1c6e7164, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [5ms]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:34000 mC
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=312, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310406, SEQNUM=4338, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-20733, POWER_SUPPLY_CHARGE_COUNTER=-452, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2488): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2488): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2488): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2488):  Nonce Reponse 
I/MMApiWebService( 2488): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2488): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2488): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2488): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2488): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2488): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2488): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2488): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2488): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:34000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:34000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1406): run()
,I/Keyboard.Facilitator( 1406): flushDynamicLanguageModels()
,I/ConfigService( 1687): onCreate
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ConfigService( 1687): onDestroy
,I/PowerManagerService(  878): Nap time (uid 1000)...
I/PowerManagerService(  878): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  878): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  878): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  878): Build Date: 10/28/14 Tue
I/Adreno-EGL(  878): Local Branch: 
I/Adreno-EGL(  878): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  878): Local Patches: NONE
I/Adreno-EGL(  878): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (8:340 vsyncs) (10:1195)
,D/        (  878): activate, handle: 1598182242, enabled: 0, index 2
D/        (  878): BstSensorExt: id=1598182242, en=0
,D/        (  878): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 225
,D/        (  878): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  878): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  878): Display changed displayId=0
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb7b12550
,D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,I/rmt_storage(  296): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb87fd820
I/rmt_storage(  296): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  296): wakelock acquired: 1, error no: 42
,I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1199581896)
,I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1199581896) wakelock released: 1, error no: 0
I/rmt_storage(  296): 
,I/rmt_storage(  296): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb87fd820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  878): Excessive delay in setPowerMode(): 344ms
,I/PowerManagerService(  878): Sleeping (uid 1000)...
,I/SFPerfTracer(  278):       trigger: frame rate (-31.874%)	(40.876 fps)	(24.464 ms) 	(4 drops)	(15 frames)
,I/WindowManager(  878): AOD feature not enabled!
,W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/SFPerfTracer(  278):      triggers: (rate: 14:391) (compose: 0:1) (post: 0:1) (render: 0:2) (15:1108 frames) (16:1202)
D/SFPerfTracer(  278):        layers: (6:11) (FocusedStackFrame (0xb7c56ef0): 0:18)* (DimLayer (0xb7c35f70): 0:14) (DimLayer (0xb7c0c1e0): 0:6)* (StatusBar (0xb7c11458): 0:150) (NavigationBar (0xb7bc5080): 0:21) (com.android.systemui.ImageWallpaper (0xb7bc8560): 0:9)* (com.example.hello/com.example.hello.MainActivity (0xb7c0efb0): 0:51) (com.example.hello/com.example.hello.MainActivity (0xb7c4f410): 0:33) (ColorFade (0xb7c23d08): 16:18) 
,D/audio_hw_primary(  308): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  308): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  308): platform_set_parameters: exit with code(0)
E/msm8974_platform(  308): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  308): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  308): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  878): startHal
,E/wifi    (  878): getStaticLongField sWifiHalHandle 0xa2ddc89c
D/wifi    (  878): halHandle = 0x0, mVM = 0xb7ee7310, mCls = 0x196e
I/WifiNative-HAL(  878): Could not start hal
,D/WifiStateMachine(  878): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  878): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  878): setSuspendOptimizations: 4 false
E/WifiStateMachine(  878): mSuspendOptNeedsDisabled 4
,D/        (  878): activate, handle: 1598182229, enabled: 0, index 0
E/        (  878): <BST> disable accel, orig state: 1
I/        (  878): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  878): startHal
E/wifi    (  878): getStaticLongField sWifiHalHandle 0xa2ddc89c
D/wifi    (  878): halHandle = 0x0, mVM = 0xb7ee7310, mCls = 0x193e
I/WifiNative-HAL(  878): Could not start hal
D/WifiStateMachine(  878): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  878): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  878): setSuspendOptimizations: 4 true
E/WifiStateMachine(  878): mSuspendOptNeedsDisabled 0
,D/audio_hw_primary(  308): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  308): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  308): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  308): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  308): adev_set_parameters: ERROR: set param called even when stream out is null
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:34000 mC
,W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  878): send {2887ddda, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  878): done {2887ddda, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:34000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=306, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311164, SEQNUM=4345, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12520, POWER_SUPPLY_CHARGE_COUNTER=-627, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  878): send {1c6e7164, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  878): send {3ff9f821, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  878): done {1c6e7164, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,V/AlarmManager(  878): done {3ff9f821, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [10ms]
,E/global frequency( 2488): no tags to log
,D/Checkin ( 2488): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2488): Explicit concurrent mark sweep GC freed 19798(1160KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 10MB/18MB, paused 1.098ms total 55.688ms
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 53363(2MB) AllocSpace objects, 32(1029KB) LOS objects, 39% free, 7MB/12MB, paused 881us total 43.122ms
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2488): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2488): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/AlarmManager(  878): send {7eafbe0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {d95fda6, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/art     (  878): Explicit concurrent mark sweep GC freed 12177(688KB) AllocSpace objects, 2(194KB) LOS objects, 33% free, 20MB/30MB, paused 1.479ms total 127.015ms
,V/AlarmManager(  878): done {d95fda6, *walarm*:com.google.android.intent.action.SEND_IDLE} [33ms]
,V/AlarmManager(  878): done {7eafbe0, *alarm*:android.intent.action.TIME_TICK} [62ms]
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 4071(170KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 649us total 36.252ms
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2488): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2488): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2488): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2488): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2488): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2488): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2488): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2488): BcsDSCheckin.events found events 2000
,D/Checkin ( 2488): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2488): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2488): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2488): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2488): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2488): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2488): unknown error code mapping for: 0
I/global frequency( 2488): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2488): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2488): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2488): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
,I/ClearcutLoggerApiImpl( 1687): disconnect managed GoogleApiClient
,I/MMApiBackOffService( 2488): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2488): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2488): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2488):  Nonce Reponse 
I/MMApiWebService( 2488): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2488): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2488): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2488): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2488): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2488): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2488): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2488): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2488): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  878): send {1c6e7164, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  878): done {1c6e7164, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,V/AlarmManager(  878): send {3002fb94, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  878): done {3002fb94, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [3ms]
,I/VacuumService( 1687): Vacuum at: now=1457427989432 tag=VacuumService
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311047, SEQNUM=4353, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13120, POWER_SUPPLY_CHARGE_COUNTER=-831, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  878): send {3ff9f821, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  878): send {7eafbe0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): done {3ff9f821, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [6ms]
,V/AlarmManager(  878): done {7eafbe0, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 5313): 
D/AndroidRuntime( 5313): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5313): CheckJNI is OFF
D/AndroidRuntime( 5313): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  878): Force stopping com.example.hello appid=10561 user=-1: uninstall pkg
I/ActivityManager(  878): Killing 5091:com.example.hello/u0a561 (adj 0): stop com.example.hello
I/WindowState(  878): WIN DEATH: Window{36755917 u0 com.example.hello/com.example.hello.MainActivity}
I/WindowState(  878): WIN DEATH: Window{2cfe8c9c u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  878): Skipping PackageSetting{33c84864 com.test.thalitest/10558} due to missing metadata
I/ActivityManager(  878):   Force finishing activity ActivityRecord{1636ec5b u0 com.example.hello/.MainActivity t9}
V/ActivityManager(  878): Display changed displayId=0
W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  878): Spurious death for ProcessRecord{2c144e32 5091:com.example.hello/u0a561}, curProc for 5091: null
W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  878): Force stopping com.example.hello appid=10561 user=0: pkg removed
D/OtaApp  ( 2488): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2488): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2488): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2488): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2488): publish the event [tag = MOT_OTA event name = LOG]
I/Keyboard.Facilitator( 1406): resetDictionaries() : en_US
W/GeofencerStateMachine( 1687): Ignoring removeGeofence because network location is disabled.
I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1555): Explicit concurrent mark sweep GC freed 7305(531KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 469us total 55.088ms
I/Keyboard.Facilitator.DecoderInitializer( 1406): run()
I/art     ( 2907): Explicit concurrent mark sweep GC freed 3236(689KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 7MB/12MB, paused 728us total 43.948ms
I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5342 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/OtaApp  ( 2488): [debug] > cancelling the previous pending intent set for download later
I/Decoder ( 1406): createOrResetDecoder
I/art     ( 1935): Explicit concurrent mark sweep GC freed 675(30KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/18MB, paused 889us total 137.461ms
I/art     (  878): Explicit concurrent mark sweep GC freed 11991(832KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.347ms total 130.545ms
I/art     (  878): WaitForGcToComplete blocked for 40.647ms for cause Explicit
I/OtaApp  ( 2488): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2488): publish the event [tag = MOT_OTA event name = LOG]
I/ConfigService( 1687): onCreate
W/InputMethodManagerService(  878): Got RemoteException sending setActive(false) notification to pid 5091 uid 10561
I/Keyboard.Facilitator( 1406): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1406): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1406): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1406): run()
I/StatsUtilsManager( 1406): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1406): shouldRecordStats() = Too Soon
D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  878): Receieved: android.intent.action.PACKAGE_REMOVED
D/VoicemailCleanupService( 5342): Cleaning up data for package: com.example.hello
I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5371 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  878): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  878): removeObsoleteFile: deleting file=8_task.xml
I/ContactLocale( 5342): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  878): Explicit concurrent mark sweep GC freed 5847(301KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.028ms total 219.563ms
I/ActivityManager(  878): Killing 4907:com.android.vending/u0a32 (adj 15): empty #7
D/AndroidRuntime( 5313): Shutting down VM
I/Launcher( 1555): Deferring update until onResume
W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_4907/cgroup.procs: No such file or directory
W/asset   ( 5371): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5371): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5371): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5371): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  878): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5396 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  878): Killing 4976:com.motorola.context/u0a8 (adj 15): empty #7
W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_4976/cgroup.procs: No such file or directory
W/ContextImpl( 5396): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1935): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1935): Clearing selected account for com.example.hello
I/LocationSettingsChecker( 1935): Removing dialog suppression flag for package com.example.hello
E/SQLiteLog( 1935): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 5396): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5396): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5396): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 5396): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5396): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5396): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 5396): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 5396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5396): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
E/SQLiteDatabase( 1935): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1935): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1935): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1935): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1935): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1935): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
E/AndroidRuntime( 5396): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5396): Process: com.android.keychain, PID: 5396
E/AndroidRuntime( 5396): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5396): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 5396): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5396): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5396): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 5396): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 5396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5396): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1935): Could not unregister android package com.example.hello
E/PhenotypeInitializer( 1935): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1935): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/PhenotypeInitializer( 1935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 1935): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 1935): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1935): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1935): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 1935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DriveAsyncService( 1935): disk I/O error (code 3850)
E/DriveAsyncService( 1935): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1935): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1935): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1935): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1935): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1935): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1935): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1935): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1935): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1935): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1935): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1935): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1935): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1935): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1935): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1935): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1935): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1687): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1687): Shutting down VM
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
E/AndroidRuntime( 1687): FATAL EXCEPTION: main
E/AndroidRuntime( 1687): Process: com.google.android.gms.persistent, PID: 1687
E/AndroidRuntime( 1687): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1687): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1687): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1687): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1687): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1687): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1687): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1687): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1687): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1687): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1687): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1687): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1687): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1687): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1687): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1687): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1687): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1687): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1687): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1687): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1687): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1687): 	... 9 more
E/GMPM-SVC( 1935): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteLog( 1935): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1935): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1935): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1935): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1935): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1935): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1935): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1935): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1935): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1935): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1935): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1935): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteOpenHelper( 1935): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1935): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1935): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1935): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1935): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1935): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1935): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1935): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1935): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1935): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1935): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 1687): Sending signal. PID: 1687 SIG: 9
W/SQLiteOpenHelper( 1935): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
E/DropBoxManagerService(  878): Can't write: system_app_crash
E/DropBoxManagerService(  878): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  878): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  878): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  878): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  878): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  878): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  878): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  878): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  878): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  878): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  878): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  878): 	... 5 more
E/DropBoxManagerService(  878): Can't write: system_app_crash
E/DropBoxManagerService(  878): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  878): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  878): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  878): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  878): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  878): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  878): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  878): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  878): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  878): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  878): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  878): 	... 5 more
D/gH_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/Process ( 5396): Sending signal. PID: 5396 SIG: 9
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
E/AndroidRuntime( 1935): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1935): Process: com.google.android.gms, PID: 1935
E/AndroidRuntime( 1935): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1935): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1935): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1935): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1935): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1935): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1935): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1935): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1935): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1935): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1935): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1935): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1935): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1935): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
I/Process ( 1935): Sending signal. PID: 1935 SIG: 9

```
