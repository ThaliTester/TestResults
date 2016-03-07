#### Test 613623665d5a4d6_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,I/SFPerfTracer(  279):      triggers: (rate: 13:526) (compose: 0:1) (post: 0:1) (render: 0:2) (0:883 frames) (1:954)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb8044758): 0:12)* (DimLayer (0xb80c9a38): 0:3)* (StatusBar (0xb80ccce0): 1:159) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb80a91e8): 0:48)- (NavigationBar (0xb80ab5d8): 0:23) (com.android.systemui.ImageWallpaper (0xb80af3e8): 0:8)* (Starting com.motorola.ccc.ota (0xb80e1000): 0:31)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb80df798): 0:28) 
--------- beginning of main
D/AndroidRuntime( 5135): 
D/AndroidRuntime( 5135): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5135): CheckJNI is OFF
D/AndroidRuntime( 5135): Calling main entry com.android.commands.am.Am
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (160 us)
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5135): Shutting down VM
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5154 uid=10553 gids={50553, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5154): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5154): Time to load native libraries: 3 ms (timestamps 5205-5208)
,I/LibraryLoader( 5154): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5154): Binding Chromium to main looper Looper (main, tid 1) {7a243fe}
,I/LibraryLoader( 5154): Expected native library version number "",actual native library version number ""
,I/chromium( 5154): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5154): Initializing chromium process, singleProcess=true
W/art     ( 5154): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5154): ApplicationContext is null in ApplicationStatus
W/chromium( 5154): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5154): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5154): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5154): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5154): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5154): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5154): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5154): Local Branch: 
I/Adreno-EGL( 5154): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5154): Local Patches: NONE
I/Adreno-EGL( 5154): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
,D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25eeea7f:true
,D/BluetoothAdapter( 5154): 511316209: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5154): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5154): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5154): CordovaWebView is running on device made by: motorola
,W/art     ( 5154): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5154): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5154): Render dirty regions requested: true
,D/Atlas   ( 5154): Validating map...
,W/chromium( 5154): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5154): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5154): Enabling debug mode 0
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1031
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +1s31ms
,I/Keyboard.Facilitator( 1409): onFinishInput()
,E/Adreno-ES20( 5154): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5154): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5154): Cannot call determinedVisibility() - never saw a connection for the pid: 5154
,E/Adreno-ES20( 5154): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5154): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:34000 mC
,D/JsMessageQueue( 5154): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5154): JniHelper::setJavaVM(0xb8743310), pthread_self() = -1196765184
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5154): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5154):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5154):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5154):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5154):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5154): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2426925b added. We now have 1 listener(s)
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5154): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5154): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5154): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5154): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@337636 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5154): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  880): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5154): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5154): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5154): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5154): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5154): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5154): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5154): Initializing JXcore engine
W/jxcore-log( 5154): JXcore engine is ready
,D/TaskPersister(  880): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/Thread-585( 5222): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10553 path="socket:[9312]" dev="sockfs" ino=9312 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-585( 5222): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10553 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-585( 5222): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10553 path="socket:[6745]" dev="sockfs" ino=6745 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-585( 5222): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10553 path="socket:[21468]" dev="sockfs" ino=21468 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5154): Starting JXcore engine
,W/jxcore-log( 5154): Platform android
W/jxcore-log( 5154): 
W/jxcore-log( 5154): Process ARCH arm
W/jxcore-log( 5154): 
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (15:298 vsyncs) (17:1061)
,I/SFPerfTracer(  279):      triggers: (rate: 13:527) (compose: 0:1) (post: 0:1) (render: 0:2) (16:972 frames) (17:1061)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb8044758): 0:17)* (DimLayer (0xb80c9a38): 0:6)* (StatusBar (0xb80ccce0): 0:178) (NavigationBar (0xb80ab5d8): 0:36) (com.android.systemui.ImageWallpaper (0xb80af3e8): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb80df798): 0:56)- (Starting com.test.thalitest (0xb80e1000): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb80a9bc8): 17:46) 
,I/jxcore-log( 5154): JXcore Cordova bridge is ready!
I/jxcore-log( 5154): 
,W/jxcore-log( 5154): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5154): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5154): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5154): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5154): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2523): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2523): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2523): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2523): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2523): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2523): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2523): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2523): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  880): send {124f114, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  880): done {124f114, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [6ms]
,W/IInputConnectionWrapper( 5154): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1409): onFinishInput()
,D/Finsky  ( 4948): [570] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4948): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  880): Killing 4923:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/SFPerfTracer(  279):      triggers: (rate: 13:527) (compose: 0:1) (post: 0:1) (render: 0:3) (17:1012 frames) (18:1109)
D/SFPerfTracer(  279):        layers: (4:10) (FocusedStackFrame (0xb8044758): 0:19)* (DimLayer (0xb80c9a38): 0:7) (StatusBar (0xb80ccce0): 0:197) (NavigationBar (0xb80ab5d8): 0:49) (com.android.systemui.ImageWallpaper (0xb80af3e8): 0:8)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb80a9bc8): 2:73)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb80e1000): 18:28) 
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_4923/cgroup.procs: No such file or directory
,W/BindingManager( 5154): Cannot call determinedVisibility() - never saw a connection for the pid: 5154
,V/AlarmManager(  880): send {3b3945f, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  880): done {3b3945f, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [8ms]
,D/TaskPersister(  880): removeObsoleteFile: deleting file=8_task.xml
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,D/CdsService( 2523): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2523): [i] > Retry handler returned true; Retry web request after backoff time: 30000
,D/Checkin ( 2523): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  880): send {2c9e0443, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {2c9e0443, *alarm*:android.intent.action.TIME_TICK} [53ms]
,I/MMApiBackOffService( 2523): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2523): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2523): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2523): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2523):  Nonce Reponse 
I/MMApiWebService( 2523): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2523): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2523): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2523): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 20706(1151KB) AllocSpace objects, 17(477KB) LOS objects, 40% free, 7MB/12MB, paused 901us total 43.663ms
,D/MMApiWebService( 2523): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2523): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2523): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  880): send {34e95976, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  880): done {34e95976, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310669, SEQNUM=4352, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-16927, POWER_SUPPLY_CHARGE_COUNTER=-328, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb7fc2550
D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  880): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  880): Display changed displayId=0
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb80c9820
,I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
,I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1207134920)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1207134920) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb80c9820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
D/SurfaceControl(  880): Excessive delay in setPowerMode(): 328ms
,I/PowerManagerService(  880): Sleeping (uid 1000)...
,I/WindowManager(  880): AOD feature not enabled!
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  298): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  298): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  298): platform_set_parameters: exit with code(0)
E/msm8974_platform(  298): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  298): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  298): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2d9c89c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb8743310, mCls = 0x1014ea
I/WifiNative-HAL(  880): Could not start hal
D/WifiStateMachine(  880): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: true
E/WifiStateMachine(  880): setSuspendOptimizations: 4 false
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 4
,D/        (  880): activate, handle: 1598182229, enabled: 0, index 0
E/        (  880): <BST> disable accel, orig state: 1
I/        (  880): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/Keyboard.Facilitator( 1409): onFinishInput()
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2d9c89c
,D/audio_hw_primary(  298): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  298): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  298): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  298): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  298): adev_set_parameters: ERROR: set param called even when stream out is null
,D/wifi    (  880): halHandle = 0x0, mVM = 0xb8743310, mCls = 0x10149e
I/WifiNative-HAL(  880): Could not start hal
D/WifiStateMachine(  880): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  880): setSuspendOptimizations: 4 true
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,D/CdsService( 2523): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2523): [i] > Retry handler returned true; Retry web request after backoff time: 60000
,D/Checkin ( 2523): publish the event [tag = MOT_OTA event name = LOG]
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  880): send {6f515d6, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  880): done {6f515d6, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,E/global frequency( 2523): no tags to log
,D/Checkin ( 2523): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2523): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2523): Explicit concurrent mark sweep GC freed 33219(1875KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.972ms total 86.299ms
,I/art     (  880): Explicit concurrent mark sweep GC freed 17618(968KB) AllocSpace objects, 7(352KB) LOS objects, 33% free, 21MB/31MB, paused 1.370ms total 123.580ms
,D/BSUtils ( 2523): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2523): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2523): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 37514(2007KB) AllocSpace objects, 16(574KB) LOS objects, 39% free, 7MB/12MB, paused 688us total 41.637ms
,D/BSUtils ( 2523): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2523): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2523): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2523): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2523): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2523): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2523): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2523): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2523): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2523): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2523): publish the event [tag = DEV_ATTRIBS event name = SW]
,V/AlarmManager(  880): send {1984b962, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  880): done {1984b962, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,I/global frequency( 2523): BcsDSCheckin.events found events 1702
,D/Checkin ( 2523): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2523): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2523): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2523): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2523): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2523): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2523): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 2523): unknown error code mapping for: 0
I/global frequency( 2523): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2523): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310216, SEQNUM=4364, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-440, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2523): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2523): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2523): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2523): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2523):  Nonce Reponse 
I/MMApiWebService( 2523): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2523): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2523): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2523): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 3586(141KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 813us total 35.570ms
,D/MMApiWebService( 2523): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2523): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2523): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1689): disconnect managed GoogleApiClient
,V/AlarmManager(  880): send {2c9e0443, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {34e95976, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  880): send {11cafaf3, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  880): send {3b3945f, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  880): done {34e95976, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [9ms]
,V/AlarmManager(  880): done {11cafaf3, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [25ms]
V/AlarmManager(  880): done {3b3945f, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [25ms]
,V/AlarmManager(  880): done {2c9e0443, *alarm*:android.intent.action.TIME_TICK} [54ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1409): run()
,I/Keyboard.Facilitator( 1409): flushDynamicLanguageModels()
,I/art     (  880): Explicit concurrent mark sweep GC freed 9733(502KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.406ms total 109.739ms
,I/ConfigService( 1689): onCreate
,I/VacuumService( 1689): Vacuum at: now=1457344407005 tag=VacuumService
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,D/CdsService( 2523): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2523): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2523): publish the event [tag = MOT_OTA event name = LOG]
,I/ConfigService( 1689): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310095, SEQNUM=4368, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-613, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {2c9e0443, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {2c9e0443, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2523): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2523): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2523): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2523): Explicit concurrent mark sweep GC freed 36115(2MB) AllocSpace objects, 6(135KB) LOS objects, 39% free, 11MB/18MB, paused 1.686ms total 138.601ms
,D/MMApiWebService( 2523): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2523):  Nonce Reponse 
I/MMApiWebService( 2523): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2523): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2523): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2523): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2523): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2523): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2523): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2523): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2523): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2523): publish the event [tag = MOT_OTA event name = LOG]
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
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/AlarmManager(  880): send {2c9e0443, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {2bed4411, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {2bed4411, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [8ms]
,V/AlarmManager(  880): done {2c9e0443, *alarm*:android.intent.action.TIME_TICK} [52ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309979, SEQNUM=4376, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-1689, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2523): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2523): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2523): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2523): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2523):  Nonce Reponse 
I/MMApiWebService( 2523): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2523): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2523): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2523): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2523): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2523): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2523): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2523): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2523): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2523): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2523): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2523): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5390): 
D/AndroidRuntime( 5390): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5390): CheckJNI is OFF
D/AndroidRuntime( 5390): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10553 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 5154:com.test.thalitest/u0a553 (adj 11): stop com.test.thalitest
D/WifiService(  880): Client connection lost with reason: 4
W/PackageSettings(  880): Skipping PackageSetting{18e548f6 com.example.hello/10548} due to missing metadata
W/ActivityManager(  880): Spurious death for ProcessRecord{365f1f7d 5154:com.test.thalitest/u0a553}, curProc for 5154: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10553 user=0: pkg removed
I/art     ( 2955): Explicit concurrent mark sweep GC freed 4133(954KB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 7MB/12MB, paused 647us total 35.060ms
I/art     ( 4863): Explicit concurrent mark sweep GC freed 688(39KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 358us total 45.400ms
W/GeofencerStateMachine( 1689): Ignoring removeGeofence because network location is disabled.
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1409): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1409): run()
I/Decoder ( 1409): createOrResetDecoder
I/art     ( 1559): Explicit concurrent mark sweep GC freed 7289(529KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 490us total 79.443ms
I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5420 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1939): Explicit concurrent mark sweep GC freed 2187(88KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 913us total 145.129ms
I/art     (  880): Explicit concurrent mark sweep GC freed 13581(959KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 20MB/31MB, paused 2.048ms total 134.636ms
I/art     (  880): WaitForGcToComplete blocked for 48.913ms for cause Explicit
I/ConfigService( 1689): onCreate
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
D/VoicemailCleanupService( 5420): Cleaning up data for package: com.test.thalitest
I/ContactLocale( 5420): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5442 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  880): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  880): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/Launcher( 1559): Deferring update until onResume
I/art     (  880): Explicit concurrent mark sweep GC freed 5304(259KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 2.948ms total 204.449ms
W/asset   ( 5442): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5442): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5442): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5442): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5464 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  880): Killing 4863:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 5390): Shutting down VM
W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_4863/cgroup.procs: No such file or directory
W/ContextImpl( 5464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1939): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1939): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1939): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/NetworkScheduler.SchedulerReceiver( 1689): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1689): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5490 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1939): doRemovePackageData com.test.thalitest
W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2f323a7b new=com.google.android.velvet.VelvetApplication@2f323a7b
I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5514 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
