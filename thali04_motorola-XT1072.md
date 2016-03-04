#### Test 617161634bd7322_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:34000 mC
D/AndroidRuntime( 5214): 
D/AndroidRuntime( 5214): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5214): CheckJNI is OFF
D/AndroidRuntime( 5214): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (161 us)
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5214): Shutting down VM
I/ActivityManager(  884): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5233 uid=10549 gids={50549, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5233): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5233): Time to load native libraries: 1 ms (timestamps 7438-7439)
I/LibraryLoader( 5233): Expected native library version number "",actual native library version number ""
,I/SFPerfTracer(  279):      triggers: (rate: 14:482) (compose: 0:1) (post: 0:1) (render: 0:2) (18:925 frames) (19:993)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb8c78798): 1:11)* (DimLayer (0xb8c1a198): 1:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8c1c588): 0:39)- (StatusBar (0xb8cbfb08): 19:163) (NavigationBar (0xb8cc0d98): 13:36) (com.android.systemui.ImageWallpaper (0xb8cc3590): 0:5)* (Starting com.motorola.ccc.ota (0xb8cad560): 0:38)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8ccc958): 18:45) (Starting com.test.thalitest (0xb8cad560): 1:4)* 
,V/WebViewChromiumFactoryProvider( 5233): Binding Chromium to main looper Looper (main, tid 1) {3f275343}
,I/LibraryLoader( 5233): Expected native library version number "",actual native library version number ""
,I/chromium( 5233): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5233): Initializing chromium process, singleProcess=true
,W/art     ( 5233): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5233): ApplicationContext is null in ApplicationStatus
,W/chromium( 5233): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5233): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5233): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5233): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5233): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5233): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5233): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5233): Local Branch: 
I/Adreno-EGL( 5233): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5233): Local Patches: NONE
I/Adreno-EGL( 5233): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@228aceec:true
,D/BluetoothAdapter( 5233): 127354348: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5233): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5233): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5233): CordovaWebView is running on device made by: motorola
,W/art     ( 5233): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5233): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5233): Render dirty regions requested: true
,D/Atlas   ( 5233): Validating map...
,W/chromium( 5233): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5233): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5233): Enabling debug mode 0
,I/LaunchCheckinHandler(  884): Displayed com.test.thalitest/.MainActivity,cp,ca,1078
I/ActivityManager(  884): Displayed com.test.thalitest/.MainActivity: +1s78ms
,I/Keyboard.Facilitator( 1407): onFinishInput()
,E/Adreno-ES20( 5233): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5233): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5233): Cannot call determinedVisibility() - never saw a connection for the pid: 5233
,E/Adreno-ES20( 5233): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5233): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (35:270 vsyncs) (37:1059)
D/JsMessageQueue( 5233): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5233): JniHelper::setJavaVM(0xb8034310), pthread_self() = -1204126672
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5233): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5233):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5233):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5233):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5233):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5233): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d442a4c added. We now have 1 listener(s)
,D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233): setBluetoothMacAddress: 08:00:00:10:DD:3C
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5233): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5233): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5233): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5233): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e61df9b added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5233): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  884): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5233): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5233): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5233): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5233): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5233): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5233): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/jxcore-log( 5233): Initializing JXcore engine
W/jxcore-log( 5233): JXcore engine is ready
,W/Thread-604( 5292): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10549 path="socket:[7355]" dev="sockfs" ino=7355 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-604( 5292): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10549 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-604( 5292): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10549 path="socket:[6897]" dev="sockfs" ino=6897 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-604( 5292): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10549 path="socket:[24674]" dev="sockfs" ino=24674 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5233): Starting JXcore engine
,W/jxcore-log( 5233): Platform android
W/jxcore-log( 5233): 
W/jxcore-log( 5233): Process ARCH arm
W/jxcore-log( 5233): 
,V/AlarmManager(  884): send {1df4a1dd, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  884): send {18687152, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  884): done {1df4a1dd, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [15ms]
V/AlarmManager(  884): done {18687152, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [15ms]
,D/Finsky  ( 5079): [591] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5079): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 5233): JXcore Cordova bridge is ready!
I/jxcore-log( 5233): 
W/jxcore-log( 5233): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5233): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5233): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5233): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5233): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5233): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2482): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2482): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2482): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2482): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2482): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2482): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2482): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2482): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5233): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1407): onFinishInput()
,I/SFPerfTracer(  279):      triggers: (rate: 14:483) (compose: 0:1) (post: 0:1) (render: 0:2) (14:1012 frames) (15:1098)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb8c78798): 0:16)* (DimLayer (0xb8c1a198): 0:6) (StatusBar (0xb8cbfb08): 15:179) (NavigationBar (0xb8cc0d98): 12:49) (com.android.systemui.ImageWallpaper (0xb8cc3590): 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8ccc958): 0:54)- (Starting com.test.thalitest (0xb8cad560): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8c1d3f0): 15:65) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8cad0d8): 0:3)* 
,I/SFPerfTracer(  279):      triggers: (rate: 14:483) (compose: 0:1) (post: 0:1) (render: 0:3) (17:1037 frames) (18:1125)
D/SFPerfTracer(  279):        layers: (4:10) (FocusedStackFrame (0xb8c78798): 0:16)* (DimLayer (0xb8c1a198): 0:6) (StatusBar (0xb8cbfb08): 0:182) (NavigationBar (0xb8cc0d98): 0:49) (com.android.systemui.ImageWallpaper (0xb8cc3590): 0:5)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb8c1d3f0): 2:76)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8cad0d8): 18:27) 
,I/ActivityManager(  884): Killing 4842:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_4842/cgroup.procs: No such file or directory
,D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:34000 mC
,I/MMApiBackOffService( 2482): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2482): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2482): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  884): Explicit concurrent mark sweep GC freed 15112(783KB) AllocSpace objects, 5(159KB) LOS objects, 33% free, 21MB/31MB, paused 1.812ms total 116.310ms
,D/MMApiWebService( 2482): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2482):  Nonce Reponse 
I/MMApiWebService( 2482): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2482): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2482): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2482): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2482): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2482): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2482): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:34000 mC
,V/AlarmManager(  884): send {2ba5fb89, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): done {2ba5fb89, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  884): send {1507d8f9, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  884): done {1507d8f9, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [4ms]
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310474, SEQNUM=4356, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-222, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  884): Nap time (uid 1000)...
I/PowerManagerService(  884): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  884): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  884): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  884): Build Date: 10/28/14 Tue
I/Adreno-EGL(  884): Local Branch: 
I/Adreno-EGL(  884): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  884): Local Patches: NONE
I/Adreno-EGL(  884): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  884): activate, handle: 1598182242, enabled: 0, index 2
D/        (  884): BstSensorExt: id=1598182242, en=0
,D/        (  884): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  884): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  884): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  884): Display changed displayId=0
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb8b91550
D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/rmt_storage(  293): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8f00820
,I/rmt_storage(  293): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  293): wakelock acquired: 1, error no: 42
I/rmt_storage(  293): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1192229576)
,I/rmt_storage(  293): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  293): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  293): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1192229576) wakelock released: 1, error no: 0
I/rmt_storage(  293): 
,I/rmt_storage(  293): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8f00820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  884): Excessive delay in setPowerMode(): 329ms
,I/WindowManager(  884): AOD feature not enabled!
I/PowerManagerService(  884): Sleeping (uid 1000)...
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  305): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  305): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  305): platform_set_parameters: exit with code(0)
E/msm8974_platform(  305): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  305): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  305): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2d1589c
,D/wifi    (  884): halHandle = 0x0, mVM = 0xb8034310, mCls = 0x197e
I/WifiNative-HAL(  884): Could not start hal
,D/WifiStateMachine(  884): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  884): setSuspendOptimizations: 4 false
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 4
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2d1589c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb8034310, mCls = 0x101956
I/WifiNative-HAL(  884): Could not start hal
D/WifiStateMachine(  884): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  884): setSuspendOptimizations: 4 true
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 0
,D/        (  884): activate, handle: 1598182229, enabled: 0, index 0
E/        (  884): <BST> disable accel, orig state: 1
I/        (  884): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  305): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  305): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  305): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  305): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  305): adev_set_parameters: ERROR: set param called even when stream out is null
,I/Keyboard.Facilitator( 1407): onFinishInput()
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  884): send {137c0777, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  884): done {137c0777, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311540, SEQNUM=4366, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13120, POWER_SUPPLY_CHARGE_COUNTER=-281, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,E/global frequency( 2482): no tags to log
,D/Checkin ( 2482): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2482): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1543): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2482): Explicit concurrent mark sweep GC freed 21095(1309KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/18MB, paused 1.444ms total 65.810ms
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 53393(2MB) AllocSpace objects, 33(1044KB) LOS objects, 39% free, 7MB/12MB, paused 786us total 45.833ms
,D/BSUtils ( 2482): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2482): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2482): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1543): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2482): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2482): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2482): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1543): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 4148(173KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 836us total 38.228ms
,D/BSUtils ( 2482): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2482): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2482): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2482): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2482): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2482): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2482): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2482): publish the event [tag = DEV_ATTRIBS event name = SW]
,V/AlarmManager(  884): send {381fa413, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  884): done {381fa413, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,I/global frequency( 2482): BcsDSCheckin.events found events 1111
,D/Checkin ( 2482): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     (  884): Explicit concurrent mark sweep GC freed 11714(672KB) AllocSpace objects, 2(192KB) LOS objects, 33% free, 20MB/31MB, paused 1.754ms total 110.991ms
,I/BSUtils ( 2482): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2482): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2482): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2482): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2482): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2482): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2482): unknown error code mapping for: 0
,I/global frequency( 2482): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 2482): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2482): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2482): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,I/MMApiBackOffService( 2482): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2482): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2482): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2482): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2482):  Nonce Reponse 
I/MMApiWebService( 2482): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2482): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2482): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2482): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2482): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2482): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2482): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1700): disconnect managed GoogleApiClient
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
,I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1700): onCreate
,V/AlarmManager(  884): send {2ba5fb89, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {1507d8f9, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  884): send {5566e6f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  884): send {18687152, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): done {1507d8f9, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [11ms]
,V/AlarmManager(  884): done {5566e6f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [31ms]
V/AlarmManager(  884): done {18687152, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [31ms]
,V/AlarmManager(  884): done {2ba5fb89, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,I/VacuumService( 1700): Vacuum at: now=1457102777031 tag=VacuumService
,I/ConfigService( 1700): onDestroy
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311102, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-520, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  884): send {2ba5fb89, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): done {2ba5fb89, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310709, SEQNUM=4374, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-723, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2482): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2482): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2482): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2482): Explicit concurrent mark sweep GC freed 27751(2MB) AllocSpace objects, 6(110KB) LOS objects, 40% free, 11MB/18MB, paused 1.090ms total 65.424ms
,D/MMApiWebService( 2482): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2482):  Nonce Reponse 
I/MMApiWebService( 2482): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2482): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2482): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2482): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2482): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2482): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2482): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311844, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  884): send {2ba5fb89, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {6add3c0, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  884): send {3c3746d6, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  884): done {6add3c0, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [24ms]
,V/AlarmManager(  884): done {2ba5fb89, *alarm*:android.intent.action.TIME_TICK} [48ms]
,V/AlarmManager(  884): done {3c3746d6, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [61ms]
,I/EventLogService( 4918): Aggregate from 1457101561104 (log), 1457101561104 (data)
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310342, SEQNUM=4382, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311217, SEQNUM=4386, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2482): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2482): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2482): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 3270(129KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.896ms total 103.161ms
,D/MMApiWebService( 2482): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2482):  Nonce Reponse 
I/MMApiWebService( 2482): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2482): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2482): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2482): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2482): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2482): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2482): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2482): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2482): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311792, SEQNUM=4387, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=8, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311208, SEQNUM=4388, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  884): User[0] Flushing usage stats to disk
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311480, SEQNUM=4389, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  884): Explicit concurrent mark sweep GC freed 13799(830KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/31MB, paused 1.766ms total 143.928ms
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5454): 
D/AndroidRuntime( 5454): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5454): CheckJNI is OFF
D/AndroidRuntime( 5454): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  884): Force stopping com.test.thalitest appid=10549 user=-1: uninstall pkg
I/ActivityManager(  884): Killing 5233:com.test.thalitest/u0a549 (adj 11): stop com.test.thalitest
D/WifiService(  884): Client connection lost with reason: 4
W/PackageSettings(  884): Skipping PackageSetting{1e4e1f5b com.example.hello/10548} due to missing metadata
W/ActivityManager(  884): Spurious death for ProcessRecord{1ee76b3f 5233:com.test.thalitest/u0a549}, curProc for 5233: null
I/ActivityManager(  884): Force stopping com.test.thalitest appid=10549 user=0: pkg removed
I/art     ( 2910): Explicit concurrent mark sweep GC freed 3832(803KB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 7MB/12MB, paused 541us total 25.960ms
I/art     ( 1561): Explicit concurrent mark sweep GC freed 7350(535KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 467us total 42.901ms
I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1700): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1407): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1407): run()
I/art     ( 4979): Explicit concurrent mark sweep GC freed 679(38KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 380us total 92.513ms
I/Decoder ( 1407): createOrResetDecoder
I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5483 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 4918): Explicit concurrent mark sweep GC freed 4044(273KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 12MB/17MB, paused 730us total 155.650ms
I/ConfigService( 1700): onCreate
I/art     (  884): Explicit concurrent mark sweep GC freed 7453(605KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 2.852ms total 141.992ms
I/art     (  884): WaitForGcToComplete blocked for 49.597ms for cause Explicit
I/CheckinRequestBuilder( 1700): Classify the device as Phone.
D/VoicemailCleanupService( 5483): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5510 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  884): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  884): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/ContactLocale( 5483): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  884): Explicit concurrent mark sweep GC freed 4015(196KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 2.033ms total 173.413ms
W/FetchTask( 1700): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/asset   ( 5510): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5510): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5510): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5510): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 1700): Classify the device as Phone.
W/FetchTask( 1700): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/CheckinRequestBuilder( 1700): Classify the device as Phone.
I/Launcher( 1561): Deferring update until onResume
I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5536 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/FetchTask( 1700): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ActivityManager(  884): Killing 4979:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
W/libprocessgroup(  884): failed to open /acct/uid_10039/pid_4979/cgroup.procs: No such file or directory
D/AndroidRuntime( 5454): Shutting down VM
I/CheckinRequestBuilder( 1700): Classify the device as Phone.
W/FetchTask( 1700): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ContextImpl( 5536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 4918): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4918): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4918): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4918): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4918): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4918): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 4918): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1700): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1700): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/CheckinRequestBuilder( 1700): Classify the device as Phone.
D/gH_CompatibleDatabase( 4918): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4918): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4918): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4918): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4918): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4918): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4918): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4918): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4918): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4918): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4918): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5561 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 4918): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4918): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/FetchTask( 1700): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/BaseAppContext( 4918): Using Auth Proxy for data requests.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): run()
W/BaseAppContext( 4918): Using Auth Proxy for data requests.
I/GMPM-SVC( 4918): App measurement is starting up, version: 8489
I/GMPM-SVC( 4918): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
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
W/Launcher( 1561): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@79745ec new=com.google.android.velvet.VelvetApplication@79745ec
I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5588 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 20.426ms
I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 19.857ms
I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.623ms
E/SQLiteDatabase( 4918): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 4918): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4918): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 4918): Opening the database failed, dropping and recreating it
W/FileUtils( 4918): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 4918): Failed to open Apps corpus file.
E/SQLiteDatabase( 4918): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 4918): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4918): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4918): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/Icing   ( 4918): Failed to open Apps corpus file.
E/GMPM-SVC( 4918): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
W/GMPM-SVC( 4918): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SharedPreferencesImpl( 4918): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
E/GMPM-SVC( 4918): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
I/Icing   ( 4918): doRemovePackageData com.test.thalitest
W/GMPM-SVC( 4918): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 4918): Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
W/GMPM-SVC( 4918): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 4918): Task exception on worker thread: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/SharedPreferencesImpl( 4918): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 4918): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 4918): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 4918): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 4918): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 4918): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 4918): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 4918): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
D/ConnectivityService(  884): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
