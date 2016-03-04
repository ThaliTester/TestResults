#### Test 614329799926788_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 5506): 
D/AndroidRuntime( 5506): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5506): CheckJNI is OFF
D/AndroidRuntime( 5506): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5525 uid=10545 gids={50545, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5506): Shutting down VM
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  882): Explicit concurrent mark sweep GC freed 10032(530KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.329ms total 123.455ms
,I/WebViewFactory( 5525): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5525): Time to load native libraries: 2 ms (timestamps 7624-7626)
I/LibraryLoader( 5525): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5525): Binding Chromium to main looper Looper (main, tid 1) {2d193119}
,I/LibraryLoader( 5525): Expected native library version number "",actual native library version number ""
,I/chromium( 5525): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5525): Initializing chromium process, singleProcess=true
W/art     ( 5525): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5525): ApplicationContext is null in ApplicationStatus
,W/chromium( 5525): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5525): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5525): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5525): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5525): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5525): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5525): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5525): Local Branch: 
I/Adreno-EGL( 5525): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5525): Local Patches: NONE
I/Adreno-EGL( 5525): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  882): Activity pause timeout for ActivityRecord{9fb3254 u0 com.test.thalitest/.MainActivity t6}
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8c841bb:true
,D/BluetoothAdapter( 5525): 407073656: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5525): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5525): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5525): CordovaWebView is running on device made by: motorola
,W/art     ( 5525): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5525): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5525): Render dirty regions requested: true
,D/Atlas   ( 5525): Validating map...
,W/chromium( 5525): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5525): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5525): Enabling debug mode 0
,I/Keyboard.Facilitator( 1405): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1122
,I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +1s31ms (total +1s122ms)
,W/IInputConnectionWrapper( 5525): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5525): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5525): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5525): Cannot call determinedVisibility() - never saw a connection for the pid: 5525
,D/JsMessageQueue( 5525): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5525): JniHelper::setJavaVM(0xb78f9310), pthread_self() = -1211568560
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5525): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5525):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5525):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5525):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5525):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5525): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94bd2b5 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5525): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abe0dd8 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5525): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  882): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5525): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5525): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5525): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5525): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5525): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5525): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/art     ( 5525): Suspending all threads took: 12.259ms
,W/jxcore-log( 5525): Initializing JXcore engine
W/jxcore-log( 5525): JXcore engine is ready
,I/art     ( 5525): Background sticky concurrent mark sweep GC freed 6961(624KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 13.226ms total 40.792ms
,W/Thread-604( 5575): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10545 path="socket:[8360]" dev="sockfs" ino=8360 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-604( 5575): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10545 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-604( 5575): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10545 path="socket:[7610]" dev="sockfs" ino=7610 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-604( 5575): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10545 path="socket:[23768]" dev="sockfs" ino=23768 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5525): Starting JXcore engine
,W/jxcore-log( 5525): Platform android
W/jxcore-log( 5525): 
W/jxcore-log( 5525): Process ARCH arm
W/jxcore-log( 5525): 
,I/jxcore-log( 5525): JXcore Cordova bridge is ready!
I/jxcore-log( 5525): 
W/jxcore-log( 5525): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5525): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5525): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5525): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5525): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  882): Killing 5221:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_5221/cgroup.procs: No such file or directory
,W/PluginManager( 5525): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2721): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2721): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2721): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2721): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2721): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2721): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2721): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2721): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5525): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1405): onFinishInput()
,D/TaskPersister(  882): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC

```
