#### Test 60124347d4f5b03_thali04_motorola-XT1072 Logs


```
--------- beginning of main,
I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
D/AndroidRuntime( 5227): 
D/AndroidRuntime( 5227): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5227): CheckJNI is OFF
D/AndroidRuntime( 5227): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (169 us)
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5227): Shutting down VM
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5246 uid=10558 gids={50558, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5246): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5246): Time to load native libraries: 6 ms (timestamps 7425-7431)
I/LibraryLoader( 5246): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5246): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
I/LibraryLoader( 5246): Expected native library version number "",actual native library version number ""
I/chromium( 5246): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/SFPerfTracer(  279):      triggers: (rate: 12:331) (compose: 0:1) (post: 0:1) (render: 0:2) (18:1025 frames) (19:1104)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb7c05308): 1:12)* (DimLayer (0xb7b5bab8): 1:6) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7b5d7d0): 0:47)- (StatusBar (0xb7b61610): 19:171) (NavigationBar (0xb7be1dc8): 13:39) (com.android.systemui.ImageWallpaper (0xb7be50f8): 0:8)* (Starting com.motorola.ccc.ota (0xb7bcd388): 0:24)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7c0f640): 18:48) (Starting com.test.thalitest (0xb7bcd388): 1:4)* 
,I/BrowserStartupController( 5246): Initializing chromium process, singleProcess=true
,W/art     ( 5246): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5246): ApplicationContext is null in ApplicationStatus
,W/chromium( 5246): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5246): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5246): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5246): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5246): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5246): Local Branch: 
I/Adreno-EGL( 5246): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5246): Local Patches: NONE
I/Adreno-EGL( 5246): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f6d8cd5:true
,D/BluetoothAdapter( 5246): 446216149: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5246): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5246): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5246): CordovaWebView is running on device made by: motorola
,W/art     ( 5246): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5246): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5246): Render dirty regions requested: true
,D/Atlas   ( 5246): Validating map...
,W/chromium( 5246): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5246): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5246): Enabling debug mode 0
,I/Keyboard.Facilitator( 1403): onFinishInput()
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:239 vsyncs) (1:1132)
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1032
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +1s32ms
,E/Adreno-ES20( 5246): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5246): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5246): Cannot call determinedVisibility() - never saw a connection for the pid: 5246
,D/JsMessageQueue( 5246): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 5246): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5246): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/PluginManager( 5246): THREAD WARNING: exec() call to CoreAndroid.show blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,D/jxcore_app_log( 5246): JniHelper::setJavaVM(0xb8194310), pthread_self() = -1202748792
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5246): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5246):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5246):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5246):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5246):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5246): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ae68ec added. We now have 1 listener(s)
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5246): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5246): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5246): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5246): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9da6bb added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5246): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  881): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5246): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5246): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5246): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5246): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5246): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5246): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5246): Initializing JXcore engine
W/jxcore-log( 5246): JXcore engine is ready
,W/Thread-605( 5312): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10558 path="socket:[6363]" dev="sockfs" ino=6363 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-605( 5312): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10558 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-605( 5312): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10558 path="socket:[6567]" dev="sockfs" ino=6567 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-605( 5312): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10558 path="socket:[21504]" dev="sockfs" ino=21504 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5246): Starting JXcore engine
,W/jxcore-log( 5246): Platform android
W/jxcore-log( 5246): 
W/jxcore-log( 5246): Process ARCH arm
W/jxcore-log( 5246): 
,D/TaskPersister(  881): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/jxcore-log( 5246): JXcore Cordova bridge is ready!
I/jxcore-log( 5246): 
W/jxcore-log( 5246): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5246): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5246): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5246): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5246): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5246): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2545): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2545): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2545): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2545): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2545): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2545): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2545): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2545): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  881): send {20bc0cf2, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  881): done {20bc0cf2, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [7ms]
,I/Keyboard.Facilitator( 1403): onFinishInput()
,W/IInputConnectionWrapper( 5246): showStatusIcon on inactive InputConnection
,D/Finsky  ( 5098): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5098): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SFPerfTracer(  279):      triggers: (rate: 12:333) (compose: 0:1) (post: 0:1) (render: 0:2) (13:1117 frames) (14:1215)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb7c05308): 0:17)* (DimLayer (0xb7b5bab8): 0:9) (StatusBar (0xb7b61610): 14:187) (NavigationBar (0xb7be1dc8): 11:52) (com.android.systemui.ImageWallpaper (0xb7be50f8): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7c0f640): 0:57)- (Starting com.test.thalitest (0xb7bcd388): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7b5d7d0): 14:70) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7bcd388): 0:6)* 
,I/SFPerfTracer(  279):      triggers: (rate: 12:333) (compose: 0:1) (post: 0:1) (render: 0:3) (18:1142 frames) (19:1242)
D/SFPerfTracer(  279):        layers: (4:10) (FocusedStackFrame (0xb7c05308): 0:17)* (DimLayer (0xb7b5bab8): 0:9) (StatusBar (0xb7b61610): 0:190) (NavigationBar (0xb7be1dc8): 0:52) (com.android.systemui.ImageWallpaper (0xb7be50f8): 0:8)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb7b5d7d0): 2:80)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7bcd388): 19:30) 
,I/ActivityManager(  881): Killing 5066:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_5066/cgroup.procs: No such file or directory
,V/AlarmManager(  881): send {ea619b5, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  881): done {ea619b5, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [8ms]
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (24:339 vsyncs) (26:1245)
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
,D/TaskPersister(  881): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/MMApiBackOffService( 2545): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2545): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2545): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1460): Explicit concurrent mark sweep GC freed 20481(1144KB) AllocSpace objects, 16(462KB) LOS objects, 40% free, 7MB/12MB, paused 1.044ms total 43.657ms
,D/MMApiWebService( 2545): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2545):  Nonce Reponse 
I/MMApiWebService( 2545): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2545): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
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
,I/MMApiBackOffService( 2545): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2545): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2545): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2545): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2545): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2545): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  881): send {2e6842b6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  881): done {2e6842b6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [4ms]
,V/AlarmManager(  881): send {368b441, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): done {368b441, *alarm*:android.intent.action.TIME_TICK} [40ms]
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310448, SEQNUM=4362, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-317, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  881): Nap time (uid 1000)...
I/PowerManagerService(  881): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  881): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  881): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  881): Build Date: 10/28/14 Tue
I/Adreno-EGL(  881): Local Branch: 
I/Adreno-EGL(  881): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  881): Local Patches: NONE
I/Adreno-EGL(  881): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  881): activate, handle: 1598182242, enabled: 0, index 2
D/        (  881): BstSensorExt: id=1598182242, en=0
,D/        (  881): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  881): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  881): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb7ad3550
D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,V/ActivityManager(  881): Display changed displayId=0
,I/rmt_storage(  289): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8a12820
,I/rmt_storage(  289): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  289): wakelock acquired: 1, error no: 42
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1197397880)
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1197397880) wakelock released: 1, error no: 0
I/rmt_storage(  289): 
,I/rmt_storage(  289): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8a12820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
D/SurfaceControl(  881): Excessive delay in setPowerMode(): 328ms
,I/PowerManagerService(  881): Sleeping (uid 1000)...
,I/WindowManager(  881): AOD feature not enabled!
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2def89c
D/wifi    (  881): halHandle = 0x0, mVM = 0xb8194310, mCls = 0x20165e
I/WifiNative-HAL(  881): Could not start hal
,D/WifiStateMachine(  881): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  881): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  881): setSuspendOptimizations: 4 false
E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 4
,D/        (  881): activate, handle: 1598182229, enabled: 0, index 0
E/        (  881): <BST> disable accel, orig state: 1
I/        (  881): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/Keyboard.Facilitator( 1403): onFinishInput()
,I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2def89c
D/wifi    (  881): halHandle = 0x0, mVM = 0xb8194310, mCls = 0x101632
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
I/WifiNative-HAL(  881): Could not start hal
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
D/WifiStateMachine(  881): backgroundScan enabled=true startBackgroundScanIfNeeded:false
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
E/WifiStateMachine(  881): handleScreenStateChanged Exit: false
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  881): setSuspendOptimizations: 4 true
E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
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
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  881): send {bba9284, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  881): done {bba9284, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  881): send {2d2cca6d, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  881): done {2d2cca6d, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,E/global frequency( 2545): no tags to log
,D/Checkin ( 2545): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2545): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1531): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  881): Explicit concurrent mark sweep GC freed 17042(956KB) AllocSpace objects, 7(355KB) LOS objects, 33% free, 21MB/31MB, paused 1.448ms total 121.850ms
,I/art     ( 2545): Explicit concurrent mark sweep GC freed 23755(1378KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 10MB/18MB, paused 1.061ms total 64.512ms
,D/BSUtils ( 2545): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2545): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2545): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1531): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1460): Explicit concurrent mark sweep GC freed 37373(2010KB) AllocSpace objects, 17(586KB) LOS objects, 39% free, 7MB/12MB, paused 713us total 33.754ms
,D/BSUtils ( 2545): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2545): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2545): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1531): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2545): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2545): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2545): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2545): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2545): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2545): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2545): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2545): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2545): BcsDSCheckin.events found events 2000
,D/Checkin ( 2545): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2545): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2545): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1460): Explicit concurrent mark sweep GC freed 3576(141KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 705us total 25.940ms
,D/MMApiWebService( 2545): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2545): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2545): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2545): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2545): unknown error code mapping for: 0
I/global frequency( 2545): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2545): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2545): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2545): publish the event [tag = MOT_CHECKIN event name = LOG]
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
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310881, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-20733, POWER_SUPPLY_CHARGE_COUNTER=-478, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2545): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2545): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2545): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2545): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2545):  Nonce Reponse 
I/MMApiWebService( 2545): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2545): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2545): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2545): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2545): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2545): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2545): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1694): disconnect managed GoogleApiClient
,I/Keyboard.Facilitator.LanguageModelFlusher( 1403): run()
,I/Keyboard.Facilitator( 1403): flushDynamicLanguageModels()
,I/ConfigService( 1694): onCreate
,V/AlarmManager(  881): send {2e6842b6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  881): send {368b441, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {dbfae1c, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  881): send {ea619b5, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  881): done {2e6842b6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [6ms]
,V/AlarmManager(  881): done {dbfae1c, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [24ms]
V/AlarmManager(  881): done {ea619b5, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [24ms]
,V/AlarmManager(  881): done {368b441, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/VacuumService( 1694): Vacuum at: now=1457399704630 tag=VacuumService
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1694): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
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
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310769, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12520, POWER_SUPPLY_CHARGE_COUNTER=-724, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/art     (  881): Explicit concurrent mark sweep GC freed 10917(577KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.376ms total 187.387ms
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  881): send {368b441, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): done {368b441, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2545): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2545): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2545): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2545): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2545):  Nonce Reponse 
I/MMApiWebService( 2545): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2545): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2545): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2545): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2545): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2545): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2545): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310354, SEQNUM=4382, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-1075, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310337, SEQNUM=4383, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {368b441, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {2a5d0a51, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  881): send {37203677, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  881): done {2a5d0a51, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [18ms]
,V/AlarmManager(  881): done {368b441, *alarm*:android.intent.action.TIME_TICK} [44ms]
,V/AlarmManager(  881): done {37203677, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [45ms]
,I/EventLogService( 1939): Aggregate from 1457398234284 (log), 1457398234284 (data)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2545): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2545): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2545): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2545): Explicit concurrent mark sweep GC freed 38401(3MB) AllocSpace objects, 6(148KB) LOS objects, 40% free, 11MB/18MB, paused 1.196ms total 141.860ms
,D/MMApiWebService( 2545): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2545):  Nonce Reponse 
I/MMApiWebService( 2545): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2545): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2545): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2545): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1460): Explicit concurrent mark sweep GC freed 3198(127KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 783us total 29.318ms
,D/MMApiWebService( 2545): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2545): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2545): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2545): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2545): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310892, SEQNUM=4391, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-22, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310302, SEQNUM=4394, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5454): 
D/AndroidRuntime( 5454): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5454): CheckJNI is OFF
D/AndroidRuntime( 5454): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10558 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 5246:com.test.thalitest/u0a558 (adj 11): stop com.test.thalitest
D/WifiService(  881): Client connection lost with reason: 4
W/PackageSettings(  881): Skipping PackageSetting{f36067b com.example.hello/10555} due to missing metadata
W/ActivityManager(  881): Spurious death for ProcessRecord{8d56aac 5246:com.test.thalitest/u0a558}, curProc for 5246: null
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10558 user=0: pkg removed
I/art     ( 2951): Explicit concurrent mark sweep GC freed 4126(890KB) AllocSpace objects, 18(288KB) LOS objects, 39% free, 7MB/12MB, paused 534us total 28.772ms
I/Keyboard.Facilitator( 1403): resetDictionaries() : en_US
W/GeofencerStateMachine( 1694): Ignoring removeGeofence because network location is disabled.
I/art     ( 5004): Explicit concurrent mark sweep GC freed 688(39KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 387us total 43.117ms
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5478 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1403): run()
I/Decoder ( 1403): createOrResetDecoder
I/art     ( 1556): Explicit concurrent mark sweep GC freed 7356(535KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 480us total 118.735ms
I/ConfigService( 1694): onCreate
I/art     ( 1939): Explicit concurrent mark sweep GC freed 3773(220KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 1.048ms total 197.295ms
I/art     (  881): Explicit concurrent mark sweep GC freed 14989(1081KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 20MB/31MB, paused 1.750ms total 150.639ms
I/art     (  881): WaitForGcToComplete blocked for 91.948ms for cause Explicit
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
D/VoicemailCleanupService( 5478): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5506 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5478): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  881): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  881): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/Launcher( 1556): Deferring update until onResume
W/asset   ( 5506): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5506): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5506): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5506): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  881): Explicit concurrent mark sweep GC freed 4848(234KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.908ms total 193.778ms
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5525 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  881): Killing 5004:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 5454): Shutting down VM
W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_5004/cgroup.procs: No such file or directory
W/ContextImpl( 5525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1939): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1939): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1694): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1694): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1939): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5552 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1939): doRemovePackageData com.test.thalitest
W/Launcher( 1556): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5576 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.293ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 19.731ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 20.125ms
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
