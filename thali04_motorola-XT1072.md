#### Test 62548124b8ccb9f_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  881): send {74b3aae, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {3693a79f, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  881): done {3693a79f, *walarm*:com.google.android.intent.action.SEND_IDLE} [23ms]
V/AlarmManager(  881): done {74b3aae, *alarm*:android.intent.action.TIME_TICK} [45ms]
--------- beginning of main
I/PhenotypeFlagCommitter( 2027): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 2027): Using platform SSLCertificateSocketFactory
D/AndroidRuntime( 5970): 
D/AndroidRuntime( 5970): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5970): CheckJNI is OFF
D/AndroidRuntime( 5970): Calling main entry com.android.commands.am.Am
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6013 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5970): Shutting down VM
I/art     (  329): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 354us total 27.751ms
I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.271ms
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 21.431ms
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6013): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6013): Time to load native libraries: 2 ms (timestamps 5864-5866)
I/LibraryLoader( 6013): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6013): Binding Chromium to main looper Looper (main, tid 1) {33da418b}
,I/LibraryLoader( 6013): Expected native library version number "",actual native library version number ""
,I/chromium( 6013): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6013): Initializing chromium process, singleProcess=true
W/art     ( 6013): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6013): ApplicationContext is null in ApplicationStatus
,W/chromium( 6013): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6013): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6013): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6013): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6013): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6013): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6013): Local Branch: 
I/Adreno-EGL( 6013): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6013): Local Patches: NONE
I/Adreno-EGL( 6013): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
,D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33a246a1:true
,W/art     ( 6013): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6013): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6013): CordovaWebView is running on device made by: motorola
,W/art     ( 6013): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6013): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{3bc49da2 u0 com.test.thalitest/.MainActivity t9}
,D/OpenGLRenderer( 6013): Render dirty regions requested: true
,D/Atlas   ( 6013): Validating map...
,W/chromium( 6013): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6013): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6013): Enabling debug mode 0
,I/Keyboard.Facilitator( 1413): onFinishInput()
,W/IInputConnectionWrapper( 6013): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,773
,I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +658ms (total +783ms)
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:33000 mC
,E/Adreno-ES20( 6013): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6013): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6013): Cannot call determinedVisibility() - never saw a connection for the pid: 6013
,D/JsMessageQueue( 6013): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6013): JniHelper::setJavaVM(0xb7fcb310), pthread_self() = -1204413616
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a9d9c86 added. We now have 1 listener(s)
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6013): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6013): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6013): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34d43a9d added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6013): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  881): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6013): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 6013): Constructor: Bluetooth LE discovery mode is not supported
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6013): bind: Binding a new listener
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6013): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,V/io.jxcore.node.ConnectivityMonitor( 6013): updateConnectivityInfo: FORCED notification:
V/io.jxcore.node.ConnectivityMonitor( 6013):     - is Wi-Fi Direct supported: true
V/io.jxcore.node.ConnectivityMonitor( 6013):     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
V/io.jxcore.node.ConnectivityMonitor( 6013):     - is Wi-Fi enabled: true
V/io.jxcore.node.ConnectivityMonitor( 6013):     - is Bluetooth enabled: true
V/io.jxcore.node.ConnectivityMonitor( 6013):     - BSSID name: f4:f2:6d:22:99:3e
V/io.jxcore.node.ConnectivityMonitor( 6013):     - is connected/connecting to active network: true
V/io.jxcore.node.ConnectivityMonitor( 6013):     - active network type is Wi-Fi: true
D/io.jxcore.node.JXcoreExtension( 6013): notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
D/io.jxcore.node.ConnectivityMonitor( 6013): start: OK
V/io.jxcore.node.ConnectivityMonitor( 6013): updateConnectivityInfo: No relevant state changes
,V/io.jxcore.node.ConnectivityMonitor( 6013): updateConnectivityInfo: No relevant state changes
,I/chromium( 6013): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 2027): Background sticky concurrent mark sweep GC freed 110752(5MB) AllocSpace objects, 12(192KB) LOS objects, 26% free, 17MB/23MB, paused 5.853ms total 112.188ms
,E/DataBuffer( 2027): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ca9c818)
,E/DataBuffer( 2027): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@39d1b271)
,E/DataBuffer( 2027): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@370d9856)
,E/DataBuffer( 2027): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3db840d7)
,E/DataBuffer( 2027): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@287f4dc4)
,V/GLSActivity( 2027): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2027): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/global frequency( 2600): no tags to log
,D/Checkin ( 2600): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2600): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2600): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/ClearcutLoggerApiImpl( 2027): disconnect managed GoogleApiClient
,I/art     (  881): Explicit concurrent mark sweep GC freed 39042(1827KB) AllocSpace objects, 2(219KB) LOS objects, 33% free, 20MB/30MB, paused 1.524ms total 123.911ms
,I/BSUtils ( 2600): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 57566(3MB) AllocSpace objects, 35(1210KB) LOS objects, 39% free, 7MB/12MB, paused 864us total 46.245ms
,D/BSUtils ( 2600): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/jxcore-log( 6013): Initializing JXcore engine
W/jxcore-log( 6013): JXcore engine is ready
,D/BSUtils ( 2600): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2600): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2600): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/Thread-684( 6078): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[5898]" dev="sockfs" ino=5898 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-684( 6078): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-684( 6078): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9616]" dev="sockfs" ino=9616 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-684( 6078): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[27000]" dev="sockfs" ino=27000 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6013): Starting JXcore engine
,I/art     ( 2600): Explicit concurrent mark sweep GC freed 26704(1552KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/18MB, paused 1.011ms total 74.449ms
,D/BSUtils ( 2600): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2600): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2600): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2600): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2600): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2600): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2600): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2600): publish the event [tag = DEV_ATTRIBS event name = SW]
,W/jxcore-log( 6013): Platform android
W/jxcore-log( 6013): 
,W/jxcore-log( 6013): Process ARCH arm
W/jxcore-log( 6013): 
,D/Checkin ( 2600): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2600): BcsDSCheckin.events found events 33
,D/Checkin ( 2600): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2600): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2600): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 4399(184KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 623us total 29.716ms
,I/MMApiWSBase( 2600): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2600): publish the event [tag = MOT_CCE event name = LOG]
,I/jxcore-log( 6013): JXcore Cordova bridge is ready!
I/jxcore-log( 6013): 
W/jxcore-log( 6013): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6013): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 6013): [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,E/jxcore  ( 6013): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6013): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6013): [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
I/chromium( 6013): [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,I/ActivityManager(  881): Killing 5789:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_5789/cgroup.procs: No such file or directory
W/PluginManager( 6013): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 33ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,E/ActivityThread( 6013): Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@1aa6fb12 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6013): android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@1aa6fb12 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6013): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
E/ActivityThread( 6013): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
E/ActivityThread( 6013): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
E/ActivityThread( 6013): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
E/ActivityThread( 6013): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
E/ActivityThread( 6013): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
E/ActivityThread( 6013): 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
E/ActivityThread( 6013): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
E/ActivityThread( 6013): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
E/ActivityThread( 6013): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
E/ActivityThread( 6013): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
E/ActivityThread( 6013): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
E/ActivityThread( 6013): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
E/ActivityThread( 6013): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
E/ActivityThread( 6013): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
E/ActivityThread( 6013): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
E/ActivityThread( 6013): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
E/ActivityThread( 6013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6013): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityThread( 6013): Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3b8492e3 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6013): android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3b8492e3 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6013): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
E/ActivityThread( 6013): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
E/ActivityThread( 6013): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
E/ActivityThread( 6013): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
E/ActivityThread( 6013): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
E/ActivityThread( 6013): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
E/ActivityThread( 6013): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
E/ActivityThread( 6013): 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
E/ActivityThread( 6013): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
E/ActivityThread( 6013): 	at i,o.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
E/ActivityThread( 6013): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
E/ActivityThread( 6013): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
E/ActivityThread( 6013): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
E/ActivityThread( 6013): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
E/ActivityThread( 6013): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
E/ActivityThread( 6013): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
E/ActivityThread( 6013): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
E/ActivityThread( 6013): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
E/ActivityThread( 6013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6013): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/OtaApp  ( 2600): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2600): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2600): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2600): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2600): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2600): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2600): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2600): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1413): onFinishInput()
,W/IInputConnectionWrapper( 6013): showStatusIcon on inactive InputConnection
,D/AndroidRuntime( 6101): 
D/AndroidRuntime( 6101): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6101): CheckJNI is OFF
,D/AndroidRuntime( 6101): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6013:com.test.thalitest/u0a109 (adj 9): stop com.test.thalitest
,D/WifiService(  881): Client connection lost with reason: 4
,W/PackageSettings(  881): Skipping PackageSetting{3cd709d2 com.example.hello/10568} due to missing metadata
,W/ActivityManager(  881): Spurious death for ProcessRecord{7205cbd 6013:com.test.thalitest/u0a109}, curProc for 6013: null
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,I/art     ( 3029): Explicit concurrent mark sweep GC freed 9500(2MB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 7MB/12MB, paused 892us total 34.338ms
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 2027): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
,I/Decoder ( 1413): createOrResetDecoder
D/VoicemailCleanupService( 1635): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6140 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1569): Explicit concurrent mark sweep GC freed 2883(152KB) AllocSpace objects, 4(184KB) LOS objects, 25% free, 13MB/17MB, paused 497us total 100.945ms
,I/art     ( 1947): Explicit concurrent mark sweep GC freed 17678(1027KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/19MB, paused 1.033ms total 159.977ms
,W/SQLiteConnectionPool( 1947): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ConfigService( 2027): onCreate
,W/asset   ( 6140): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 6140): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6140): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6140): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Too Soon
,I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6165 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  881): removeObsoleteFile: deleting file=9_task.xml
,D/TaskPersister(  881): removeObsoleteFile: deleting file=8_task.xml
,I/Launcher( 1569): Deferring update until onResume
,I/art     (  881): Explicit concurrent mark sweep GC freed 24171(1708KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/30MB, paused 2.056ms total 250.191ms
,W/ContextImpl( 6165): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/AndroidRuntime( 6101): Shutting down VM
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6183 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6200 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5668:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_5668/cgroup.procs: No such file or directory
,I/Finsky  ( 6183): [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.open,OrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/RollingFileStream( 6183): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
,E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
,E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.open,OrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
I/Finsky  ( 6183): [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 2027): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 2027): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 2027): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 2027): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 2027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 2027): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 2027): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6183): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 6183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6183): 	at com.google.android.finsky.g.av.iterator(SourceFile:15308)
E/SQLiteDatabase( 6183): 	at com.google.android.finsky.g.w.run(SourceFile:1078)
E/SQLiteDatabase( 6183): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6183): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6183): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Settings( 6183): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6183): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 6183): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6183): 	at com.google.android.finsky.b.x.a(SourceFile:2298)
E/SQLiteDatabase( 6183): 	at com.google.android.finsky.b.z.c(SourceFile:55)
E/SQLiteDatabase( 6183): 	at com.google.android.finsky.receivers.j.doInBackground(SourceFile:3083)
E/SQLiteDatabase( 6183): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6183): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6183): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6183): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6183): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6183): 	at java.lang.Thread.run(Thread.java:818)
W/Finsky.CrashDetector( 6183): Failed to write crash file cnt=0 ts=0 cause=null.
W/Finsky.CrashDetector( 6183): java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash806214: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 6183): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/Finsky.CrashDetector( 6183): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/Finsky.CrashDetector( 6183): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/Finsky.CrashDetector( 6183): 	at com.google.android.finsky.a.a(SourceFile:179)
W/Finsky.CrashDetector( 6183): 	at com.google.android.finsky.a.uncaughtException(SourceFile:97)
W/Finsky.CrashDetector( 6183): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
W/Finsky.CrashDetector( 6183): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
W/Finsky.CrashDetector( 6183): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 6183): 	at libcore.io.Posix.open(Native Method)
W/Finsky.CrashDetector( 6183): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/Finsky.CrashDetector( 6183): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/Finsky.CrashDetector( 6183): 	... 6 more
I/Process ( 6183): Sending signal. PID: 6183 SIG: 9
,I/ActivityManager(  881): Process com.android.vending (pid 6183) has died
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
,I/ActivityManager(  881): Killing 5840:com.google.android.apps.plus/u0a90 (adj 15): empty #7

```
