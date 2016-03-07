#### Test 61362366a48397d_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:34000 mC
D/AndroidRuntime( 5254): 
D/AndroidRuntime( 5254): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5254): CheckJNI is OFF
D/AndroidRuntime( 5254): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (188 us)
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5254): Shutting down VM
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5273 uid=10554 gids={50554, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5273): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5273): Time to load native libraries: 2 ms (timestamps 7413-7415)
,I/LibraryLoader( 5273): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5273): Binding Chromium to main looper Looper (main, tid 1) {24966874}
,I/SFPerfTracer(  279):      triggers: (rate: 14:562) (compose: 0:1) (post: 0:1) (render: 0:2) (18:839 frames) (19:918)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb8550248): 1:11)* (DimLayer (0xb8603d20): 1:6) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8569780): 0:46)- (StatusBar (0xb856d868): 19:166) (NavigationBar (0xb8608e08): 13:35) (com.android.systemui.ImageWallpaper (0xb860dd10): 0:5)* (Starting com.motorola.ccc.ota (0xb85dc2f0): 0:24)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb85de008): 18:50) (Starting com.test.thalitest (0xb8569780): 1:3)* 
,I/LibraryLoader( 5273): Expected native library version number "",actual native library version number ""
I/chromium( 5273): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5273): Initializing chromium process, singleProcess=true
,W/art     ( 5273): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5273): ApplicationContext is null in ApplicationStatus
,W/chromium( 5273): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5273): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5273): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5273): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5273): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5273): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5273): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5273): Local Branch: 
I/Adreno-EGL( 5273): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5273): Local Patches: NONE
I/Adreno-EGL( 5273): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0f0e37:true
,D/BluetoothAdapter( 5273): 753637344: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5273): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5273): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5273): CordovaWebView is running on device made by: motorola
,W/art     ( 5273): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5273): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5273): Render dirty regions requested: true
,D/Atlas   ( 5273): Validating map...
,W/chromium( 5273): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (44:228 vsyncs) (46:946)
,I/OpenGLRenderer( 5273): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5273): Enabling debug mode 0
,I/Keyboard.Facilitator( 1403): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1083
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +1s84ms
,E/Adreno-ES20( 5273): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5273): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5273): Cannot call determinedVisibility() - never saw a connection for the pid: 5273
,D/JsMessageQueue( 5273): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 5273): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5273): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5273): JniHelper::setJavaVM(0xb8dd8310), pthread_self() = -1189877272,
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5273): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5273):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5273):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5273):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5273):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5273): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23a0d979 added. We now have 1 listener(s)
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5273): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5273): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5273): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5273): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2787c66c added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5273): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  880): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5273): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5273): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5273): setScanMode: 1 -> 2
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5273): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5273): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5273): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5273): Initializing JXcore engine
W/jxcore-log( 5273): JXcore engine is ready
,W/Thread-604( 5344): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10554 path="socket:[7323]" dev="sockfs" ino=7323 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-604( 5344): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10554 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-604( 5344): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10554 path="socket:[9652]" dev="sockfs" ino=9652 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-604( 5344): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10554 path="socket:[24778]" dev="sockfs" ino=24778 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,D/TaskPersister(  880): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/jxcore-log( 5273): Starting JXcore engine
,W/jxcore-log( 5273): Platform android
W/jxcore-log( 5273): 
W/jxcore-log( 5273): Process ARCH arm
W/jxcore-log( 5273): 
,I/jxcore-log( 5273): JXcore Cordova bridge is ready!
I/jxcore-log( 5273): 
,W/jxcore-log( 5273): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5273): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5273): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5273): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5273): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5273): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2525): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2525): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2525): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2525): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2525): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2525): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2525): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2525): publish the event [tag = MOT_OTA event name = LOG]
,I/art     (  880): Explicit concurrent mark sweep GC freed 13126(640KB) AllocSpace objects, 2(110KB) LOS objects, 33% free, 21MB/31MB, paused 1.554ms total 118.733ms
,V/AlarmManager(  880): send {26314f6c, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
V/AlarmManager(  880): done {26314f6c, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [128ms]
,W/IInputConnectionWrapper( 5273): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1403): onFinishInput()
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/Finsky  ( 5108): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5108): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager(  880): send {fbff417, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  880): done {fbff417, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [3ms]
,I/SFPerfTracer(  279):      triggers: (rate: 14:564) (compose: 0:1) (post: 0:1) (render: 0:2) (14:932 frames) (15:1030)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb8550248): 0:16)* (DimLayer (0xb8603d20): 1:9) (StatusBar (0xb856d868): 15:182) (NavigationBar (0xb8608e08): 12:48) (com.android.systemui.ImageWallpaper (0xb860dd10): 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb85de008): 0:60)- (Starting com.test.thalitest (0xb8569780): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb85db910): 15:72) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb85dd628): 1:4)* 
,W/ProcessCpuTracker(  880): Skipping unknown process pid 5356
,W/ProcessCpuTracker(  880): Skipping unknown process pid 5359
,W/ProcessCpuTracker(  880): Skipping unknown process pid 5362
W/ProcessCpuTracker(  880): Skipping unknown process pid 5363
,I/SFPerfTracer(  279):      triggers: (rate: 14:564) (compose: 0:1) (post: 0:1) (render: 0:4) (17:956 frames) (18:1056)
D/SFPerfTracer(  279):        layers: (4:10) (FocusedStackFrame (0xb8550248): 0:16)* (DimLayer (0xb8603d20): 0:9) (StatusBar (0xb856d868): 0:185) (NavigationBar (0xb8608e08): 0:48) (com.android.systemui.ImageWallpaper (0xb860dd10): 0:5)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb85db910): 1:81)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb85dd628): 18:27) 
,I/ActivityManager(  880): Killing 5083:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_5083/cgroup.procs: No such file or directory
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (19:327 vsyncs) (21:1060)
,D/TaskPersister(  880): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:34000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 2525): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2525): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,I/art     ( 2525): Explicit concurrent mark sweep GC freed 20614(1219KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 10MB/18MB, paused 1.113ms total 72.413ms
,D/MMApiWebService( 2525): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 20969(1173KB) AllocSpace objects, 16(461KB) LOS objects, 39% free, 7MB/12MB, paused 959us total 39.183ms
,D/MMApiWebService( 2525): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2525):  Nonce Reponse 
I/MMApiWebService( 2525): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2525): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2525): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2525): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2525): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2525): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2525): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:34000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  880): send {273c8b6a, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  880): done {273c8b6a, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311058, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-18529, POWER_SUPPLY_CHARGE_COUNTER=-534, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  880): Nap time (uid 1000)...
I/PowerManagerService(  880): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  880): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  880): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  880): Build Date: 10/28/14 Tue
I/Adreno-EGL(  880): Local Branch: 
I/Adreno-EGL(  880): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  880): Local Patches: NONE
I/Adreno-EGL(  880): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  880): activate, handle: 1598182242, enabled: 0, index 2
D/        (  880): BstSensorExt: id=1598182242, en=0
D/        (  880): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  880): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb84cf550
D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  880): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  880): Display changed displayId=0
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8537820
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1202490056)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1202490056) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8537820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
D/SurfaceControl(  880): Excessive delay in setPowerMode(): 328ms
,I/PowerManagerService(  880): Sleeping (uid 1000)...
,I/WindowManager(  880): AOD feature not enabled!
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2e3f89c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb8dd8310, mCls = 0x1976
I/WifiNative-HAL(  880): Could not start hal
,D/WifiStateMachine(  880): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  880): setSuspendOptimizations: 4 false
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 4
,D/        (  880): activate, handle: 1598182229, enabled: 0, index 0
E/        (  880): <BST> disable accel, orig state: 1
I/        (  880): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2e3f89c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb8dd8310, mCls = 0x1936
I/WifiNative-HAL(  880): Could not start hal
D/WifiStateMachine(  880): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: false
E/WifiStateMachine(  880): setSuspendOptimizations: 4 true
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 0
,I/Keyboard.Facilitator( 1403): onFinishInput()
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  880): send {3f539c6e, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  880): done {3f539c6e, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311244, SEQNUM=4382, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13120, POWER_SUPPLY_CHARGE_COUNTER=-602, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  880): send {23b04069, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {1b574f0f, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {1b574f0f, *walarm*:com.google.android.intent.action.SEND_IDLE} [11ms]
,V/AlarmManager(  880): done {23b04069, *alarm*:android.intent.action.TIME_TICK} [43ms]
,E/global frequency( 2525): no tags to log
,D/Checkin ( 2525): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2525): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2525): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2525): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2525): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 37689(2019KB) AllocSpace objects, 17(582KB) LOS objects, 39% free, 7MB/12MB, paused 705us total 33.062ms
,D/BSUtils ( 2525): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2525): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2525): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  880): Explicit concurrent mark sweep GC freed 13841(823KB) AllocSpace objects, 5(239KB) LOS objects, 33% free, 20MB/31MB, paused 1.404ms total 123.922ms
,D/BSUtils ( 2525): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2525): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2525): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2525): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2525): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2525): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2525): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2525): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/global frequency( 2525): BcsDSCheckin.events found events 1784
,D/Checkin ( 2525): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2525): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2525): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 2525): Explicit concurrent mark sweep GC freed 23780(1718KB) AllocSpace objects, 6(140KB) LOS objects, 40% free, 12MB/20MB, paused 861us total 59.026ms
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 3195(127KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 515us total 26.033ms
,D/MMApiWebService( 2525): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2525): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2525): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2525): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2525): unknown error code mapping for: 0
,I/global frequency( 2525): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2525): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2525): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2525): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2525): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2525): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2525): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2525): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2525):  Nonce Reponse 
I/MMApiWebService( 2525): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2525): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2525): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2525): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2525): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2525): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2525): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1690): disconnect managed GoogleApiClient
,I/Keyboard.Facilitator.LanguageModelFlusher( 1403): run()
,I/Keyboard.Facilitator( 1403): flushDynamicLanguageModels()
,I/ConfigService( 1690): onCreate
,V/AlarmManager(  880): send {fbff417, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  880): send {273c8b6a, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  880): send {91ecb46, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): done {fbff417, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,V/AlarmManager(  880): done {273c8b6a, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [11ms]
V/AlarmManager(  880): done {91ecb46, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [12ms]
,I/VacuumService( 1690): Vacuum at: now=1457354325191 tag=VacuumService
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1690): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311380, SEQNUM=4388, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11418, POWER_SUPPLY_CHARGE_COUNTER=-828, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {23b04069, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {23b04069, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310994, SEQNUM=4390, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-1126, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2525): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2525): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2525): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2525): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2525):  Nonce Reponse 
I/MMApiWebService( 2525): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2525): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2525): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2525): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2525): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2525): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2525): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {23b04069, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {16eef555, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {16eef555, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [8ms]
,V/AlarmManager(  880): done {23b04069, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2525): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2525): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2525): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2525): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2525):  Nonce Reponse 
I/MMApiWebService( 2525): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2525): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2525): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2525): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2525): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2525): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2525): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2525): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2525): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311208, SEQNUM=4393, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311792, SEQNUM=4394, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  880): Explicit concurrent mark sweep GC freed 12525(671KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/31MB, paused 1.481ms total 132.496ms
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311558, SEQNUM=4400, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-20, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311199, SEQNUM=4402, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-42, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5501): 
D/AndroidRuntime( 5501): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5501): CheckJNI is OFF
D/AndroidRuntime( 5501): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10554 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 5273:com.test.thalitest/u0a554 (adj 11): stop com.test.thalitest
D/WifiService(  880): Client connection lost with reason: 4
W/PackageSettings(  880): Skipping PackageSetting{391fbf2c com.example.hello/10548} due to missing metadata
W/ActivityManager(  880): Spurious death for ProcessRecord{2a9652f5 5273:com.test.thalitest/u0a554}, curProc for 5273: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10554 user=0: pkg removed
I/art     ( 2920): Explicit concurrent mark sweep GC freed 3797(823KB) AllocSpace objects, 16(256KB) LOS objects, 39% free, 7MB/12MB, paused 551us total 33.810ms
W/GeofencerStateMachine( 1690): Ignoring removeGeofence because network location is disabled.
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1403): resetDictionaries() : en_US
I/art     ( 1555): Explicit concurrent mark sweep GC freed 7350(534KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 589us total 76.305ms
I/Keyboard.Facilitator.DecoderInitializer( 1403): run()
I/Decoder ( 1403): createOrResetDecoder
I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5531 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 5006): Explicit concurrent mark sweep GC freed 679(38KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 389us total 130.450ms
I/art     ( 4952): Explicit concurrent mark sweep GC freed 2004(95KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/16MB, paused 763us total 153.418ms
I/art     (  880): Explicit concurrent mark sweep GC freed 7444(640KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 1.609ms total 123.156ms
I/art     (  880): WaitForGcToComplete blocked for 43.064ms for cause Explicit
I/ConfigService( 1690): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1403): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1403): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1403): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1403): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1403): run()
I/StatsUtilsManager( 1403): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1403): shouldRecordStats() = Too Soon
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
D/VoicemailCleanupService( 5531): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5553 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  880): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  880): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/Launcher( 1555): Deferring update until onResume
I/ContactLocale( 5531): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  880): Explicit concurrent mark sweep GC freed 4790(235KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 3.208ms total 199.489ms
W/asset   ( 5553): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5553): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5553): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5553): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5574 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/AndroidRuntime( 5501): Shutting down VM
I/ActivityManager(  880): Killing 5006:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_5006/cgroup.procs: No such file or directory
W/ContextImpl( 5574): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 4952): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4952): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4952): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4952): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4952): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4952): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 4952): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1690): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1690): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 4952): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4952): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4952): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4952): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4952): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4952): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4952): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4952): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4952): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4952): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4952): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4952): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4952): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5597 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  880): send {23b04069, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {16eef555, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  880): done {23b04069, *alarm*:android.intent.action.TIME_TICK} [38ms]
W/BaseAppContext( 4952): Using Auth Proxy for data requests.
I/GMPM-SVC( 4952): App measurement is starting up, version: 8489
I/GMPM-SVC( 4952): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 4952): Using Auth Proxy for data requests.
W/FileUtils( 4952): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 4952): Failed to open Apps corpus file.
E/SQLiteDatabase( 4952): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 4952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4952): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/SQLiteDatabase( 4952): 	at com.google.android.gms.drive.database.m.b(SourceFile:601)
E/SQLiteDatabase( 4952): 	at com.google.android.gms.drive.database.m.a(SourceFile:595)
E/SQLiteDatabase( 4952): 	at com.google.android.gms.drive.database.o.run(SourceFile:616)
--------- beginning of crash
E/AndroidRuntime( 4952): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4952): Process: com.google.android.gms, PID: 4952
E/AndroidRuntime( 4952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 4952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4952): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/AndroidRuntime( 4952): 	at com.google.android.gms.drive.database.m.b(SourceFile:601)
E/AndroidRuntime( 4952): 	at com.google.android.gms.drive.database.m.a(SourceFile:595)
E/AndroidRuntime( 4952): 	at com.google.android.gms.drive.database.o.run(SourceFile:616)
E/Icing   ( 4952): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 4952): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
I/Icing   ( 4952): doRemovePackageData com.test.thalitest
E/DropBoxManagerService(  880): Can't write: system_app_crash
E/DropBoxManagerService(  880): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  880): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  880): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  880): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  880): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  880): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  880): 	... 5 more
I/Process ( 4952): Sending signal. PID: 4952 SIG: 9
W/Launcher( 1555): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3fd61a99 new=com.google.android.velvet.VelvetApplication@3fd61a99
E/SQLiteLog( 1555): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5627 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.409ms
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
