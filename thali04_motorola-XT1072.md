#### Test 6012434797f7ca7_thali04_motorola-XT1072 Logs


```
--------- beginning of main,
I/ThermalEngine(  305): Sensor:xo_therm_pu2:34000 mC
D/AndroidRuntime( 5152): 
D/AndroidRuntime( 5152): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5152): CheckJNI is OFF
D/AndroidRuntime( 5152): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  281): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (165 us)
W/ContextImpl( 1454): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/SFPerfTracer(  281):      triggers: (rate: 14:408) (compose: 0:1) (post: 0:1) (render: 0:2) (0:966 frames) (1:1031)
D/SFPerfTracer(  281):        layers: (3:11) (FocusedStackFrame (0xb7ee6d68): 0:10)* (DimLayer (0xb7ed1a70): 0:3)* (StatusBar (0xb7eefae8): 0:156) (NavigationBar (0xb7ef2ed0): 0:37) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7f07e50): 0:44)- (com.android.systemui.ImageWallpaper (0xb7f0a648): 0:8)* (Starting com.motorola.ccc.ota (0xb7f0d838): 0:29)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7f139d0): 0:25) 
D/AndroidRuntime( 5152): Shutting down VM
I/SFPerfTracer(  281):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:200 vsyncs) (1:1032)
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5171 uid=10557 gids={50557, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1454): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5171): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5171): Time to load native libraries: 1 ms (timestamps 7292-7293)
,I/LibraryLoader( 5171): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5171): Binding Chromium to main looper Looper (main, tid 1) {38b199e4}
,I/LibraryLoader( 5171): Expected native library version number "",actual native library version number ""
,I/chromium( 5171): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5171): Initializing chromium process, singleProcess=true
,W/art     ( 5171): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5171): ApplicationContext is null in ApplicationStatus
,W/chromium( 5171): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5171): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5171): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5171): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5171): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5171): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5171): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5171): Local Branch: 
I/Adreno-EGL( 5171): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5171): Local Patches: NONE
I/Adreno-EGL( 5171): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
,D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8418c54:true
,D/BluetoothAdapter( 5171): 389959791: getState() :  mService = null. Returning STATE_OFF
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
,I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1693): onCreate
,W/art     ( 5171): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5171): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5171): CordovaWebView is running on device made by: motorola
,W/art     ( 5171): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5171): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5171): Render dirty regions requested: true
,D/Atlas   ( 5171): Validating map...
,W/chromium( 5171): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5171): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5171): Enabling debug mode 0
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1061
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +1s61ms
,I/art     (  883): Explicit concurrent mark sweep GC freed 12823(597KB) AllocSpace objects, 1(94KB) LOS objects, 33% free, 20MB/30MB, paused 1.877ms total 125.788ms
,I/Keyboard.Facilitator( 1407): onFinishInput()
,E/Adreno-ES20( 5171): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5171): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5171): Cannot call determinedVisibility() - never saw a connection for the pid: 5171
,D/JsMessageQueue( 5171): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 5171): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5171): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5171): JniHelper::setJavaVM(0xb82a8310), pthread_self() = -1201604064
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5171): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5171):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5171):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5171):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5171):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5171): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0b929 added. We now have 1 listener(s)
D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5171): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5171): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5171): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5171): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a962ddc added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5171): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  883): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5171): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5171): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5171): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5171): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5171): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5171): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/AlarmManager(  883): send {167db008, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  883): send {d5693a1, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  883): done {167db008, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [11ms]
V/AlarmManager(  883): done {d5693a1, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [11ms]
,D/Finsky  ( 5003): [580] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5003): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/jxcore-log( 5171): Initializing JXcore engine
W/jxcore-log( 5171): JXcore engine is ready
,D/TaskPersister(  883): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/Thread-595( 5247): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10557 path="socket:[5586]" dev="sockfs" ino=5586 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-595( 5247): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10557 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-595( 5247): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10557 path="socket:[9564]" dev="sockfs" ino=9564 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-595( 5247): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10557 path="socket:[24092]" dev="sockfs" ino=24092 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5171): Starting JXcore engine
,W/jxcore-log( 5171): Platform android
W/jxcore-log( 5171): 
,W/jxcore-log( 5171): Process ARCH arm
W/jxcore-log( 5171): 
,I/jxcore-log( 5171): JXcore Cordova bridge is ready!
I/jxcore-log( 5171): 
,W/jxcore-log( 5171): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5171): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5171): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5171): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5171): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1454): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5171): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1454): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/SFPerfTracer(  281):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (16:299 vsyncs) (18:1147)
,I/SFPerfTracer(  281):      triggers: (rate: 14:410) (compose: 0:1) (post: 0:1) (render: 0:2) (18:1064 frames) (19:1147)
D/SFPerfTracer(  281):        layers: (3:11) (FocusedStackFrame (0xb7ee6d68): 0:15)* (DimLayer (0xb7ed1a70): 0:6)* (StatusBar (0xb7eefae8): 0:175) (NavigationBar (0xb7ef2ed0): 0:50) (com.android.systemui.ImageWallpaper (0xb7f0a648): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7f139d0): 0:52)- (Starting com.test.thalitest (0xb7f0d838): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7f08830): 19:56) 
,I/art     ( 2499): Explicit concurrent mark sweep GC freed 19419(1166KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 10MB/18MB, paused 926us total 80.829ms
,D/OtaApp  ( 2499): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2499): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2499): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2499): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2499): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2499): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2499): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2499): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1407): onFinishInput()
,W/IInputConnectionWrapper( 5171): showStatusIcon on inactive InputConnection
,I/ActivityManager(  883): Killing 4770:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_4770/cgroup.procs: No such file or directory
,I/ConfigService( 1693): onDestroy
,D/TaskPersister(  883): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:34000 mC
,I/MMApiBackOffService( 2499): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2499): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2499): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1454): Explicit concurrent mark sweep GC freed 21014(1163KB) AllocSpace objects, 17(471KB) LOS objects, 39% free, 7MB/12MB, paused 923us total 41.581ms
,D/MMApiWebService( 2499): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2499):  Nonce Reponse 
I/MMApiWebService( 2499): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2499): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2499): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2499): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2499): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2499): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2499): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  883): send {29d0aa51, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): done {29d0aa51, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  883): send {af8e45, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  883): done {af8e45, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=301, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312272, SEQNUM=4351, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-544, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  883): Nap time (uid 1000)...
I/PowerManagerService(  883): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  883): Build Date: 10/28/14 Tue
I/Adreno-EGL(  883): Local Branch: 
I/Adreno-EGL(  883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  883): Local Patches: NONE
I/Adreno-EGL(  883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  883): activate, handle: 1598182242, enabled: 0, index 2
D/        (  883): BstSensorExt: id=1598182242, en=0
D/        (  883): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 224
,D/        (  883): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  281): Set power mode=0, type=0 flinger=0xb7dd8550
,D/qdhwcomposer(  281): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  883): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  883): Display changed displayId=0
,I/rmt_storage(  292): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb79e4820
I/rmt_storage(  292): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  292): wakelock acquired: 1, error no: 42
I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1214363512)
,I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1214363512) wakelock released: 1, error no: 0
I/rmt_storage(  292): 
,I/rmt_storage(  292): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb79e4820
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  281): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  281): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  883): Excessive delay in setPowerMode(): 327ms
,I/PowerManagerService(  883): Sleeping (uid 1000)...
,I/WindowManager(  883): AOD feature not enabled!
,W/ContextImpl( 1454): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  297): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  297): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  297): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  297): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  297): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  297): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2da689c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb82a8310, mCls = 0x20188e
I/WifiNative-HAL(  883): Could not start hal
,D/WifiStateMachine(  883): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  883): setSuspendOptimizations: 4 false
,E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 4
,I/Keyboard.Facilitator( 1407): onFinishInput()
,I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2da689c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb82a8310, mCls = 0x1856
I/WifiNative-HAL(  883): Could not start hal
,D/WifiStateMachine(  883): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: false
,D/        (  883): activate, handle: 1598182229, enabled: 0, index 0
E/        (  883): <BST> disable accel, orig state: 1
I/        (  883): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  297): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  297): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  297): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  297): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  297): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  883): setSuspendOptimizations: 4 true
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  883): send {30f6d3aa, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  883): done {30f6d3aa, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311870, SEQNUM=4359, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-630, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,E/global frequency( 2499): no tags to log
,D/Checkin ( 2499): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2499): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2499): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2499): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2499): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1454): Explicit concurrent mark sweep GC freed 37585(2015KB) AllocSpace objects, 17(583KB) LOS objects, 39% free, 7MB/12MB, paused 508us total 32.645ms
,D/BSUtils ( 2499): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2499): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2499): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  883): Explicit concurrent mark sweep GC freed 13837(846KB) AllocSpace objects, 6(255KB) LOS objects, 33% free, 20MB/31MB, paused 1.438ms total 120.838ms
,D/BSUtils ( 2499): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2499): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2499): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2499): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2499): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2499): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2499): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2499): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2499): BcsDSCheckin.events found events 1946
,D/Checkin ( 2499): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2499): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     ( 2499): Explicit concurrent mark sweep GC freed 27049(1916KB) AllocSpace objects, 7(162KB) LOS objects, 39% free, 12MB/20MB, paused 906us total 60.763ms
,D/MMApiWebService( 2499): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2499): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2499): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2499): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2499): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2499): unknown error code mapping for: 0
,I/global frequency( 2499): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 2499): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2499): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
D/Checkin ( 2499): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  883): send {bc68076, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  883): done {bc68076, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/MMApiBackOffService( 2499): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2499): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2499): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1454): Explicit concurrent mark sweep GC freed 3220(128KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 759us total 32.339ms
,D/MMApiWebService( 2499): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2499):  Nonce Reponse 
I/MMApiWebService( 2499): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2499): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2499): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2499): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2499): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2499): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2499): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1693): disconnect managed GoogleApiClient
,V/AlarmManager(  883): send {29d0aa51, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {af8e45, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  883): send {fecd677, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  883): send {d5693a1, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  883): done {af8e45, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [12ms]
,V/AlarmManager(  883): done {fecd677, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [30ms]
V/AlarmManager(  883): done {d5693a1, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [30ms]
,V/AlarmManager(  883): done {29d0aa51, *alarm*:android.intent.action.TIME_TICK} [56ms]
,I/VacuumService( 1693): Vacuum at: now=1457379075772 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1693): onCreate
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1693): onDestroy
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312324, SEQNUM=4365, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-830, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311940, SEQNUM=4371, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-1124, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {29d0aa51, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): done {29d0aa51, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2499): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2499): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2499): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2499): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2499):  Nonce Reponse 
I/MMApiWebService( 2499): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2499): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2499): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2499): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2499): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2499): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2499): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311577, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-1449, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312152, SEQNUM=4373, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-1450, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312148, SEQNUM=4374, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-1452, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311841, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-8, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2499): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2499): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2499): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2499): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2499):  Nonce Reponse 
I/MMApiWebService( 2499): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2499): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2499): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2499): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2499): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2499): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2499): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2499): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2499): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  883): send {29d0aa51, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {1f311ebc, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/Finsky  ( 5003): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  883): send {1a6fd3f1, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  883): send {201c8fb0, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  883): done {1a6fd3f1, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [22ms]
,V/AlarmManager(  883): done {1f311ebc, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [36ms]
,V/AlarmManager(  883): done {29d0aa51, *alarm*:android.intent.action.TIME_TICK} [110ms]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  883): Explicit concurrent mark sweep GC freed 13533(699KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.523ms total 154.991ms
,V/AlarmManager(  883): done {201c8fb0, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [214ms]
,W/Finsky  ( 5003): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 4847): Aggregate from 1457378156090 (log), 1457378156090 (data)
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5003): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5003): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5003): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  883): send {309ba8c5, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5003): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/WearableService( 1693): callingUid 10016, callindPid: 1693
,V/AlarmManager(  883): done {309ba8c5, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [15ms]
,D/DeviceConnectionService( 1693): client connected with version: 8296000
,D/Finsky  ( 5003): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 5003): [596] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5003): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5003): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {29d0aa51, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {47ab340, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  883): done {47ab340, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [12ms]
,V/AlarmManager(  883): done {29d0aa51, *alarm*:android.intent.action.TIME_TICK} [46ms]
,D/Finsky  ( 5003): [580] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5003): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5405): 
D/AndroidRuntime( 5405): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5405): CheckJNI is OFF
D/AndroidRuntime( 5405): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10557 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 5171:com.test.thalitest/u0a557 (adj 11): stop com.test.thalitest
D/WifiService(  883): Client connection lost with reason: 4
W/PackageSettings(  883): Skipping PackageSetting{249b169c com.example.hello/10555} due to missing metadata
W/ActivityManager(  883): Spurious death for ProcessRecord{353c3817 5171:com.test.thalitest/u0a557}, curProc for 5171: null
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10557 user=0: pkg removed
I/art     ( 2922): Explicit concurrent mark sweep GC freed 3798(806KB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 7MB/12MB, paused 780us total 33.885ms
W/GeofencerStateMachine( 1693): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1407): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1407): run()
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4901): Explicit concurrent mark sweep GC freed 686(38KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 385us total 57.775ms
I/Decoder ( 1407): createOrResetDecoder
I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5429 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1558): Explicit concurrent mark sweep GC freed 7288(530KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 487us total 142.147ms
I/ConfigService( 1693): onCreate
I/art     ( 4847): Explicit concurrent mark sweep GC freed 3590(255KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 12MB/17MB, paused 766us total 191.764ms
I/art     (  883): Explicit concurrent mark sweep GC freed 13782(936KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 21MB/31MB, paused 2.039ms total 168.940ms
I/art     (  883): WaitForGcToComplete blocked for 70.274ms for cause Explicit
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
D/VoicemailCleanupService( 5429): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
I/ContactLocale( 5429): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5457 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  883): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  883): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/art     (  883): Explicit concurrent mark sweep GC freed 5316(281KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.793ms total 168.772ms
I/Launcher( 1558): Deferring update until onResume
W/asset   ( 5457): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5457): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5457): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5457): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5479 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  883): Killing 4901:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_4901/cgroup.procs: No such file or directory
D/AndroidRuntime( 5405): Shutting down VM
W/ContextImpl( 5479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 4847): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4847): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4847): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4847): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4847): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4847): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1693): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1693): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5500 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/LocationSettingsChecker( 4847): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 4847): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4847): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4847): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4847): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4847): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4847): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4847): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4847): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4847): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4847): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4847): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4847): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4847): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 4847): Using Auth Proxy for data requests.
I/GMPM-SVC( 4847): App measurement is starting up, version: 8489
I/GMPM-SVC( 4847): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 4847): Using Auth Proxy for data requests.
W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@17a86249 new=com.google.android.velvet.VelvetApplication@17a86249
I/Icing   ( 4847): doRemovePackageData com.test.thalitest
I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5535 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/ConnectivityService(  883): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/art     ( 1693): Explicit concurrent mark sweep GC freed 38262(2MB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 13MB/21MB, paused 1.045ms total 91.884ms
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c4c6d35)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1ced5ca)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e70c33b)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c214a58)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@36e3a7b1)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1fec8496)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@68cb404)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27da0ded)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a645422)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a65eb3)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3230c70)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@12569be9)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3197906e)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e9e330f)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19847f9c)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@af40da5)
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5566 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a

```
