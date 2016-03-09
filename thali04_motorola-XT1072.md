#### Test 6012434764ab483_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
D/AndroidRuntime( 5438): 
D/AndroidRuntime( 5438): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5438): CheckJNI is OFF
D/AndroidRuntime( 5438): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (180 us)
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5438): Shutting down VM
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5457 uid=10562 gids={50562, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5457): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5457): Time to load native libraries: 4 ms (timestamps 7638-7642)
I/LibraryLoader( 5457): Expected native library version number "",actual native library version number ""
,I/SFPerfTracer(  278):      triggers: (rate: 12:394) (compose: 0:1) (post: 0:1) (render: 0:2) (18:980 frames) (19:1056)
D/SFPerfTracer(  278):        layers: (4:12) (FocusedStackFrame (0xb8b94e30): 1:12)* (DimLayer (0xb8af6db8): 1:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8afa208): 0:41)- (StatusBar (0xb8b80f80): 18:162) (NavigationBar (0xb8b84d38): 12:33) (com.android.systemui.ImageWallpaper (0xb8b87230): 0:7)* (Starting com.motorola.ccc.ota (0xb8b2ba98): 0:36)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8baa758): 18:38) (Starting com.test.thalitest (0xb8b2ba98): 1:3)* 
,V/WebViewChromiumFactoryProvider( 5457): Binding Chromium to main looper Looper (main, tid 1) {23110ccd}
,I/LibraryLoader( 5457): Expected native library version number "",actual native library version number ""
,I/chromium( 5457): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5457): Initializing chromium process, singleProcess=true
,W/art     ( 5457): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5457): ApplicationContext is null in ApplicationStatus
,W/chromium( 5457): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5457): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5457): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5457): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5457): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5457): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5457): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5457): Local Branch: 
I/Adreno-EGL( 5457): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5457): Local Patches: NONE
I/Adreno-EGL( 5457): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  879): Message: 20
,D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@318aa903:true
,D/BluetoothAdapter( 5457): 983177724: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5457): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5457): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5457): CordovaWebView is running on device made by: motorola
,W/art     ( 5457): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5457): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  879): Explicit concurrent mark sweep GC freed 12553(678KB) AllocSpace objects, 1(97KB) LOS objects, 33% free, 20MB/31MB, paused 1.656ms total 117.362ms
,D/OpenGLRenderer( 5457): Render dirty regions requested: true
,D/Atlas   ( 5457): Validating map...
,W/chromium( 5457): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5457): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5457): Enabling debug mode 0
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,1163
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +1s164ms
,I/Keyboard.Facilitator( 1409): onFinishInput()
,E/Adreno-ES20( 5457): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5457): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5457): Cannot call determinedVisibility() - never saw a connection for the pid: 5457
,E/Adreno-ES20( 5457): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5457): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/JsMessageQueue( 5457): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5457): JniHelper::setJavaVM(0xb7412310), pthread_self() = -1216665136
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5457): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5457):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5457):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5457):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5457):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5457): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@802c92e added. We now have 1 listener(s)
,D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5457): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5457): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5457): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5457): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18302d65 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5457): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  879): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5457): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5457): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5457): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5457): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5457): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5457): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/jxcore-log( 5457): Initializing JXcore engine
W/jxcore-log( 5457): JXcore engine is ready
,W/Thread-619( 5516): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10562 path="socket:[5876]" dev="sockfs" ino=5876 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-619( 5516): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10562 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-619( 5516): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10562 path="socket:[7555]" dev="sockfs" ino=7555 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-619( 5516): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10562 path="socket:[24802]" dev="sockfs" ino=24802 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5457): Starting JXcore engine
,W/jxcore-log( 5457): Platform android
W/jxcore-log( 5457): 
,W/jxcore-log( 5457): Process ARCH arm
W/jxcore-log( 5457): 
,I/jxcore-log( 5457): JXcore Cordova bridge is ready!
I/jxcore-log( 5457): 
W/jxcore-log( 5457): JXcore engine is started
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (15:289 vsyncs) (17:1138)
,I/org.thaliproject.p2p.ThaliPermissions( 5457): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5457): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5457): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5457): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2572): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2572): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2572): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2572): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2572): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  879): send {2674eec8, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
V/AlarmManager(  879): done {2674eec8, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [5ms]
,W/IInputConnectionWrapper( 5457): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1409): onFinishInput()
,D/Finsky  ( 5141): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5141): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SFPerfTracer(  278):      triggers: (rate: 12:394) (compose: 0:1) (post: 0:1) (render: 0:2) (14:1064 frames) (15:1160)
D/SFPerfTracer(  278):        layers: (4:12) (FocusedStackFrame (0xb8b94e30): 0:17)* (DimLayer (0xb8af6db8): 0:7) (StatusBar (0xb8b80f80): 15:179) (NavigationBar (0xb8b84d38): 12:46) (com.android.systemui.ImageWallpaper (0xb8b87230): 0:7)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8baa758): 0:48)- (Starting com.test.thalitest (0xb8b2ba98): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8afa208): 15:67) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8b2ba98): 0:5)* 
,I/SFPerfTracer(  278):      triggers: (rate: 12:394) (compose: 0:1) (post: 0:1) (render: 0:3) (17:1089 frames) (18:1187)
,D/SFPerfTracer(  278):        layers: (4:10) (FocusedStackFrame (0xb8b94e30): 0:17)* (DimLayer (0xb8af6db8): 0:7) (StatusBar (0xb8b80f80): 0:182) (NavigationBar (0xb8b84d38): 0:46) (com.android.systemui.ImageWallpaper (0xb8b87230): 0:7)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb8afa208): 1:77)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8b2ba98): 18:29) 
,I/ActivityManager(  879): Killing 5307:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_5307/cgroup.procs: No such file or directory
,V/AlarmManager(  879): send {2fc8e4e3, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  879): send {38d8cee0, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  879): done {2fc8e4e3, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [21ms]
,V/AlarmManager(  879): done {38d8cee0, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [25ms]
,I/EventLogService( 4971): Aggregate from 1457485705177 (log), 1457485705177 (data)
,D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
,D/CdsService( 2572): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2572): [i] > Retry handler returned true; Retry web request after backoff time: 30000
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,I/MMApiBackOffService( 2572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2572): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2572):  Nonce Reponse 
I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2572): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2572): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2572): Explicit concurrent mark sweep GC freed 30565(1754KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/18MB, paused 1.500ms total 84.279ms
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2572): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  879): send {174ea439, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {174ea439, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  879): send {ff9bbdf, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  879): done {ff9bbdf, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=290, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311107, SEQNUM=4358, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-544, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  879): Nap time (uid 1000)...
I/PowerManagerService(  879): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  879): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  879): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  879): Build Date: 10/28/14 Tue
I/Adreno-EGL(  879): Local Branch: 
I/Adreno-EGL(  879): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  879): Local Patches: NONE
I/Adreno-EGL(  879): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  879): activate, handle: 1598182242, enabled: 0, index 2
D/        (  879): BstSensorExt: id=1598182242, en=0
D/        (  879): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  879): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb8a6b550
D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
I/DisplayManagerService(  879): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  879): Display changed displayId=0
,I/rmt_storage(  292): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7240820
I/rmt_storage(  292): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  292): wakelock acquired: 1, error no: 42
I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1222376136)
,I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1222376136) wakelock released: 1, error no: 0
I/rmt_storage(  292): 
,I/rmt_storage(  292): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7240820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
D/SurfaceControl(  879): Excessive delay in setPowerMode(): 323ms
,I/PowerManagerService(  879): Sleeping (uid 1000)...
,I/WindowManager(  879): AOD feature not enabled!
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  300): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  300): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  300): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  300): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  300): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  300): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  879): startHal
E/wifi    (  879): getStaticLongField sWifiHalHandle 0xa2e4589c
D/wifi    (  879): halHandle = 0x0, mVM = 0xb7412310, mCls = 0x20136e
I/WifiNative-HAL(  879): Could not start hal
D/WifiStateMachine(  879): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  879): setSuspendOptimizations: 4 false
E/WifiStateMachine(  879): mSuspendOptNeedsDisabled 4
,D/        (  879): activate, handle: 1598182229, enabled: 0, index 0
E/        (  879): <BST> disable accel, orig state: 1
I/        (  879): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  879): startHal
E/wifi    (  879): getStaticLongField sWifiHalHandle 0xa2e4589c
D/wifi    (  879): halHandle = 0x0, mVM = 0xb7412310, mCls = 0x20133e
I/WifiNative-HAL(  879): Could not start hal
D/WifiStateMachine(  879): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: false
,D/audio_hw_primary(  300): adev_set_parameters: enter: screen_state=off
I/Keyboard.Facilitator( 1409): onFinishInput()
,V/msm8974_platform(  300): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  300): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  300): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  300): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  879): setSuspendOptimizations: 4 true
E/WifiStateMachine(  879): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/CdsService( 2572): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2572): [i] > Retry handler returned true; Retry web request after backoff time: 60000
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  879): send {2b442437, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  879): done {2b442437, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311302, SEQNUM=4365, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15224, POWER_SUPPLY_CHARGE_COUNTER=-623, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  879): send {28965da4, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  879): done {28965da4, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,E/global frequency( 2572): no tags to log
,D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 54609(3MB) AllocSpace objects, 35(1153KB) LOS objects, 39% free, 7MB/12MB, paused 751us total 42.832ms
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     (  879): Explicit concurrent mark sweep GC freed 16162(1117KB) AllocSpace objects, 6(260KB) LOS objects, 33% free, 21MB/31MB, paused 1.450ms total 124.705ms
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2572): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2572): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2572): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/global frequency( 2572): BcsDSCheckin.events found events 2000
,D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 4117(172KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 545us total 26.751ms
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2572): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2572): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2572): unknown error code mapping for: 0
I/global frequency( 2572): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2572): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2572): Explicit concurrent mark sweep GC freed 39344(3MB) AllocSpace objects, 6(148KB) LOS objects, 39% free, 11MB/18MB, paused 1.534ms total 72.601ms
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2572):  Nonce Reponse 
I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2572): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2572): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2572): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1716): disconnect managed GoogleApiClient
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311485, SEQNUM=4369, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-754, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  879): send {174ea439, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {ff9bbdf, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  879): send {aadb010, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  879): send {38d8cee0, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  879): done {ff9bbdf, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [9ms]
,V/AlarmManager(  879): done {aadb010, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [27ms]
V/AlarmManager(  879): done {38d8cee0, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [27ms]
,V/AlarmManager(  879): done {174ea439, *alarm*:android.intent.action.TIME_TICK} [54ms]
,I/VacuumService( 1716): Vacuum at: now=1457487609530 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1409): run()
,I/Keyboard.Facilitator( 1409): flushDynamicLanguageModels()
,I/ConfigService( 1716): onCreate
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,D/CdsService( 2572): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2572): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,I/ConfigService( 1716): onDestroy
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {174ea439, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {174ea439, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309897, SEQNUM=4374, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1224, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2572): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2572):  Nonce Reponse 
I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2572): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2572): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2572): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2572): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2572): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {174ea439, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {1f9b7a7e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  879): done {1f9b7a7e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [5ms]
,V/AlarmManager(  879): done {174ea439, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310434, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-24, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1716): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b7ddd8f)
,E/DataBuffer( 1716): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29b3181c)
,E/DataBuffer( 1716): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1441fc25)
,E/DataBuffer( 1716): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2489d1fa)
,E/DataBuffer( 1716): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e04c3ab)
,I/art     ( 1716): Explicit concurrent mark sweep GC freed 36520(2MB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 13MB/21MB, paused 982us total 163.043ms
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2572): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,I/art     (  879): Explicit concurrent mark sweep GC freed 12409(615KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.859ms total 119.275ms
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2572):  Nonce Reponse 
I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2572): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2572): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 3436(136KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 777us total 29.835ms
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2572): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2572): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2572): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2572): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5681): 
D/AndroidRuntime( 5681): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5681): CheckJNI is OFF
D/AndroidRuntime( 5681): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10562 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 5457:com.test.thalitest/u0a562 (adj 11): stop com.test.thalitest
D/WifiService(  879): Client connection lost with reason: 4
W/PackageSettings(  879): Skipping PackageSetting{2044725 com.example.hello/10561} due to missing metadata
W/ActivityManager(  879): Spurious death for ProcessRecord{3fb63d2 5457:com.test.thalitest/u0a562}, curProc for 5457: null
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10562 user=0: pkg removed
I/art     ( 2958): Explicit concurrent mark sweep GC freed 3471(740KB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 7MB/12MB, paused 572us total 28.021ms
I/art     ( 4971): Explicit concurrent mark sweep GC freed 4938(319KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 12MB/17MB, paused 691us total 66.558ms
I/Keyboard.Facilitator( 1409): resetDictionaries() : en_US
W/GeofencerStateMachine( 1716): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5708 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1409): run()
I/art     ( 5017): Explicit concurrent mark sweep GC freed 747(42KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 542us total 107.412ms
I/art     ( 1557): Explicit concurrent mark sweep GC freed 7312(531KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 529us total 97.247ms
I/Decoder ( 1409): createOrResetDecoder
I/art     (  879): Explicit concurrent mark sweep GC freed 10370(799KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 20MB/31MB, paused 3.464ms total 138.520ms
I/art     (  879): WaitForGcToComplete blocked for 79.166ms for cause Explicit
I/ConfigService( 1716): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1409): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1409): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1409): run()
I/StatsUtilsManager( 1409): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1409): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5708): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5731 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/ContactLocale( 5708): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  317): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 20.687ms
I/Launcher( 1557): Deferring update until onResume
I/art     (  317): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.926ms
W/asset   ( 5731): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5731): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5731): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5731): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  879): Explicit concurrent mark sweep GC freed 4956(235KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.879ms total 208.942ms
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 20.580ms
I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5755 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  879): Killing 5017:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 5681): Shutting down VM
W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_5017/cgroup.procs: No such file or directory
W/ContextImpl( 5755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 4971): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4971): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4971): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4971): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4971): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4971): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 4971): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1716): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1716): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 4971): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4971): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4971): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4971): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5779 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 4971): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4971): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4971): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4971): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4971): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4971): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4971): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4971): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4971): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 4971): Using Auth Proxy for data requests.
W/BaseAppContext( 4971): Using Auth Proxy for data requests.
I/GMPM-SVC( 4971): App measurement is starting up, version: 8489
I/GMPM-SVC( 4971): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/Launcher( 1557): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@30414bce new=com.google.android.velvet.VelvetApplication@30414bce
I/Icing   ( 4971): doRemovePackageData com.test.thalitest
I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5807 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/ConnectivityService(  879): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/DriveInitializer( 4971): Awaiting to be initialized
W/DriveInitializer( 4971): Background init thread started
E/SQLiteLog( 4971): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 4971): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 4971): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4971): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4971): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 4971): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4971): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4971): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 4971): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 4971): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 4971): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 4971): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer( 4971): Background init thread ended
E/DriveAsyncService( 4971): disk I/O error (code 3850)
E/DriveAsyncService( 4971): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4971): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4971): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 4971): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4971): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4971): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 4971): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 4971): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4971): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4971): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4971): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4971): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4971): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4971): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 4971): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4971): Process: com.google.android.gms, PID: 4971
E/AndroidRuntime( 4971): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4971): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4971): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 4971): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 4971): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/DropBoxManagerService(  879): Can't write: system_app_crash
E/DropBoxManagerService(  879): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  879): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  879): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  879): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  879): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  879): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  879): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  879): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  879): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  879): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  879): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  879): 	... 5 more
I/Process ( 4971): Sending signal. PID: 4971 SIG: 9
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
D/ConnectivityService(  879): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2f9a62ab)
D/ConnectivityService(  879): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  879): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
