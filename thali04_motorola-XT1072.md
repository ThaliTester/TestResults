#### Test 61362366345141a_thali04_motorola-XT1072 Logs


```
--------- beginning of system
D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=314, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311957, SEQNUM=4365, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-152, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,--------- beginning of main
D/AndroidRuntime( 5249): 
D/AndroidRuntime( 5249): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5249): CheckJNI is OFF
D/AndroidRuntime( 5249): Calling main entry com.android.commands.am.Am
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (141 us)
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5249): Shutting down VM
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5268 uid=10556 gids={50556, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5268): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5268): Time to load native libraries: 3 ms (timestamps 3256-3259)
I/LibraryLoader( 5268): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5268): Binding Chromium to main looper Looper (main, tid 1) {1cd4c716}
I/LibraryLoader( 5268): Expected native library version number "",actual native library version number ""
I/chromium( 5268): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5268): Initializing chromium process, singleProcess=true
W/art     ( 5268): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5268): ApplicationContext is null in ApplicationStatus
W/chromium( 5268): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5268): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5268): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5268): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5268): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5268): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5268): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5268): Local Branch: 
I/Adreno-EGL( 5268): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5268): Local Patches: NONE
I/Adreno-EGL( 5268): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a2dd287:true
D/BluetoothAdapter( 5268): 351234153: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5268): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5268): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5268): CordovaWebView is running on device made by: motorola
I/SFPerfTracer(  278):      triggers: (rate: 15:268) (compose: 0:1) (post: 0:1) (render: 0:3) (5:1145 frames) (6:1219)
D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb774d140): 0:12)* (DimLayer (0xb77e4aa0): 0:4)* (StatusBar (0xb77a2138): 0:165) (NavigationBar (0xb77a3e50): 0:32) (com.android.systemui.ImageWallpaper (0xb77aa708): 0:33)* (Starting com.motorola.ccc.ota (0xb7803dc8): 0:38)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb78061b8): 0:54)* (Starting com.test.thalitest (0xb77e8c98): 6:29) 
W/art     ( 5268): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5268): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5268): Render dirty regions requested: true
,D/Atlas   ( 5268): Validating map...
,W/chromium( 5268): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5268): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5268): Enabling debug mode 0
,I/Keyboard.Facilitator( 1402): onFinishInput()
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,1060
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +1s61ms
,E/Adreno-ES20( 5268): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5268): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5268): Cannot call determinedVisibility() - never saw a connection for the pid: 5268
,D/JsMessageQueue( 5268): Set native->JS mode to OnlineEventsBridgeMode
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (21:289 vsyncs) (23:1246)
,E/Adreno-ES20( 5268): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5268): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5268): JniHelper::setJavaVM(0xb82c2310), pthread_self() = -1201230304
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5268): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5268):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5268):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5268):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5268):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5268): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f34b13 added. We now have 1 listener(s)
,D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5268): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5268): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5268): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5268): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1671304e added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5268): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5268): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
D/WifiService(  879): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5268): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5268): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5268): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5268): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5268): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5268): Initializing JXcore engine
W/jxcore-log( 5268): JXcore engine is ready
,W/Thread-605( 5339): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10556 path="socket:[5810]" dev="sockfs" ino=5810 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-605( 5339): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10556 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-605( 5339): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10556 path="socket:[7452]" dev="sockfs" ino=7452 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-605( 5339): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10556 path="socket:[22165]" dev="sockfs" ino=22165 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5268): Starting JXcore engine
,D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:35000 mC
,W/jxcore-log( 5268): Platform android
W/jxcore-log( 5268): 
W/jxcore-log( 5268): Process ARCH arm
W/jxcore-log( 5268): 
,I/jxcore-log( 5268): JXcore Cordova bridge is ready!
I/jxcore-log( 5268): 
,W/jxcore-log( 5268): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5268): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5268): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5268): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5268): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5268): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2580): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2580): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2580): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2580): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2580): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2580): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2580): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2580): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  879): send {2a241b7c, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  879): done {2a241b7c, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [3ms]
,W/IInputConnectionWrapper( 5268): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1402): onFinishInput()
,D/Finsky  ( 5118): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5118): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SFPerfTracer(  278):      triggers: (rate: 15:269) (compose: 0:1) (post: 0:1) (render: 0:3) (17:1241 frames) (18:1333)
D/SFPerfTracer(  278):        layers: (4:12) (FocusedStackFrame (0xb774d140): 0:17)* (DimLayer (0xb77e4aa0): 0:7) (StatusBar (0xb77a2138): 0:184) (NavigationBar (0xb77a3e50): 0:45) (com.android.systemui.ImageWallpaper (0xb77aa708): 0:33)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb78061b8): 0:55)- (Starting com.test.thalitest (0xb77e8c98): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7804c30): 1:81)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb77c53e0): 18:29) 
,I/ActivityManager(  879): Killing 4930:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_4930/cgroup.procs: No such file or directory
,V/AlarmManager(  879): send {af72067, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  879): done {af72067, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:34000 mC
,I/MMApiBackOffService( 2580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2580): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 21233(1182KB) AllocSpace objects, 16(459KB) LOS objects, 39% free, 7MB/12MB, paused 929us total 39.850ms
,D/MMApiWebService( 2580): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2580):  Nonce Reponse 
I/MMApiWebService( 2580): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2580): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2580): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2580): Explicit concurrent mark sweep GC freed 20767(1289KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.574ms total 66.899ms
,D/MMApiWebService( 2580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2580): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:34000 mC
,V/AlarmManager(  879): send {2f0394a2, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {2f0394a2, *alarm*:android.intent.action.TIME_TICK} [36ms]
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=306, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310974, SEQNUM=4384, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15825, POWER_SUPPLY_CHARGE_COUNTER=-201, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  879): send {1a0e644c, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  879): done {1a0e644c, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
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
D/        (  879): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 222
,D/        (  879): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  879): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  879): Display changed displayId=0
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb76ca550
,D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,I/rmt_storage(  296): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8013820
I/rmt_storage(  296): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  296): wakelock acquired: 1, error no: 42
I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1207879544)
,I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1207879544) wakelock released: 1, error no: 0
I/rmt_storage(  296): 
,I/rmt_storage(  296): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8013820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
D/SurfaceControl(  879): Excessive delay in setPowerMode(): 329ms
,I/WindowManager(  879): AOD feature not enabled!
I/PowerManagerService(  879): Sleeping (uid 1000)...
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  302): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  302): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  302): platform_set_parameters: exit with code(0)
E/msm8974_platform(  302): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  302): audio_extn_set_anc_parameters: anc_enabled:0
I/WifiNative-HAL(  879): startHal
E/audio_a2dp_hw(  302): adev_set_parameters: ERROR: set param called even when stream out is null
E/wifi    (  879): getStaticLongField sWifiHalHandle 0xa2e8489c
D/wifi    (  879): halHandle = 0x0, mVM = 0xb82c2310, mCls = 0x13a6
I/WifiNative-HAL(  879): Could not start hal
D/WifiStateMachine(  879): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  879): setSuspendOptimizations: 4 false
E/WifiStateMachine(  879): mSuspendOptNeedsDisabled 4
,D/        (  879): activate, handle: 1598182229, enabled: 0, index 0
E/        (  879): <BST> disable accel, orig state: 1
I/        (  879): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  302): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  302): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  302): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  302): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  302): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  879): startHal
E/wifi    (  879): getStaticLongField sWifiHalHandle 0xa2e8489c
D/wifi    (  879): halHandle = 0x0, mVM = 0xb82c2310, mCls = 0x201352
I/WifiNative-HAL(  879): Could not start hal
D/WifiStateMachine(  879): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: false
,I/Keyboard.Facilitator( 1402): onFinishInput()
,E/WifiStateMachine(  879): setSuspendOptimizations: 4 true
E/WifiStateMachine(  879): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  879): send {275569fe, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  879): done {275569fe, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:33000 mC
,E/global frequency( 2580): no tags to log
,D/Checkin ( 2580): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2580): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  879): Explicit concurrent mark sweep GC freed 17275(962KB) AllocSpace objects, 7(350KB) LOS objects, 33% free, 21MB/31MB, paused 1.679ms total 120.574ms
,D/BSUtils ( 2580): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2580): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 36953(1979KB) AllocSpace objects, 16(566KB) LOS objects, 39% free, 7MB/12MB, paused 526us total 35.468ms
,D/BSUtils ( 2580): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2580): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2580): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2580): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2580): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2580): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2580): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2580): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2580): BcsDSCheckin.events found events 1875
D/Checkin ( 2580): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2580): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2580): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2580): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2580): unknown error code mapping for: 0
,I/global frequency( 2580): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2580): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2580): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2580): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  879): send {329a280a, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  879): done {329a280a, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311083, SEQNUM=4394, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-346, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2580): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2580): Explicit concurrent mark sweep GC freed 37850(2MB) AllocSpace objects, 5(127KB) LOS objects, 40% free, 11MB/18MB, paused 1.369ms total 72.721ms
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 3625(142KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 703us total 26.933ms
,D/MMApiWebService( 2580): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2580):  Nonce Reponse 
I/MMApiWebService( 2580): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2580): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2580): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     (  879): Explicit concurrent mark sweep GC freed 7413(389KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.648ms total 110.468ms
,D/MMApiWebService( 2580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2580): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1680): disconnect managed GoogleApiClient
,V/AlarmManager(  879): send {2f0394a2, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {1a0e644c, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  879): send {592487b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  879): send {af72067, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  879): done {1a0e644c, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [6ms]
,V/AlarmManager(  879): done {592487b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [26ms]
V/AlarmManager(  879): done {af72067, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [26ms]
,V/AlarmManager(  879): done {2f0394a2, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/VacuumService( 1680): Vacuum at: now=1457361613503 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1402): run()
,I/Keyboard.Facilitator( 1402): flushDynamicLanguageModels()
,I/ConfigService( 1680): onCreate
,I/CheckinRequestBuilder( 1680): Classify the device as Phone.
,W/FetchTask( 1680): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1680): Classify the device as Phone.
,W/FetchTask( 1680): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1680): Classify the device as Phone.
,W/FetchTask( 1680): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1680): Classify the device as Phone.
,W/FetchTask( 1680): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1680): Classify the device as Phone.
,W/FetchTask( 1680): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1680): onDestroy
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311275, SEQNUM=4404, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-576, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  879): send {2f0394a2, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {2f0394a2, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2580): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2580): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2580):  Nonce Reponse 
I/MMApiWebService( 2580): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2580): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2580): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2580): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311747, SEQNUM=4406, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-968, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311150, SEQNUM=4407, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-1014, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {2f0394a2, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {bef0620, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  879): send {1c4e200c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,D/Finsky  ( 5118): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  879): send {296a7cb9, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  879): done {296a7cb9, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [22ms]
,V/AlarmManager(  879): done {bef0620, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [33ms]
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  879): done {2f0394a2, *alarm*:android.intent.action.TIME_TICK} [77ms]
,V/AlarmManager(  879): done {1c4e200c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [84ms]
,W/Finsky  ( 5118): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1935): Aggregate from 1457360179347 (log), 1457360179347 (data)
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5118): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5118): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5118): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  879): send {3c922d96, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5118): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/WearableService( 1680): callingUid 10016, callindPid: 1680
V/AlarmManager(  879): done {3c922d96, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [17ms]
,D/DeviceConnectionService( 1680): client connected with version: 8296000
,D/Finsky  ( 5118): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
D/Finsky  ( 5118): [604] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5118): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5118): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {1aa32aa5, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  879): done {1aa32aa5, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [10ms]
,D/Finsky  ( 5118): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5118): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311708, SEQNUM=4416, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310812, SEQNUM=4419, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-53, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2580): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2580): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2580):  Nonce Reponse 
I/MMApiWebService( 2580): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2580): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2580): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     (  879): Explicit concurrent mark sweep GC freed 15245(759KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.717ms total 113.636ms
,D/MMApiWebService( 2580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2580): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2580): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311673, SEQNUM=4424, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-135, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5538): 
D/AndroidRuntime( 5538): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5538): CheckJNI is OFF
D/AndroidRuntime( 5538): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10556 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 5268:com.test.thalitest/u0a556 (adj 11): stop com.test.thalitest
D/WifiService(  879): Client connection lost with reason: 4
W/ActivityManager(  879): Spurious death for ProcessRecord{38582ef6 5268:com.test.thalitest/u0a556}, curProc for 5268: null
W/PackageSettings(  879): Skipping PackageSetting{1076db0e com.example.hello/10555} due to missing metadata
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10556 user=0: pkg removed
I/art     ( 3018): Explicit concurrent mark sweep GC freed 4219(903KB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 7MB/12MB, paused 556us total 29.829ms
I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1680): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1402): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1402): run()
I/Decoder ( 1402): createOrResetDecoder
I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5566 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1555): Explicit concurrent mark sweep GC freed 7372(536KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 510us total 147.452ms
I/ConfigService( 1680): onCreate
I/art     (  879): Explicit concurrent mark sweep GC freed 8485(733KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 20MB/31MB, paused 2.463ms total 139.440ms
I/art     (  879): WaitForGcToComplete blocked for 36.108ms for cause Explicit
I/art     ( 1935): Explicit concurrent mark sweep GC freed 3962(229KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 14.306ms total 178.523ms
I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (23:391 vsyncs) (25:1368)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1402): run()
D/VoicemailCleanupService( 5566): Cleaning up data for package: com.test.thalitest
I/art     ( 1680): Explicit concurrent mark sweep GC freed 39265(2MB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 13MB/22MB, paused 992us total 74.539ms
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8c0d0f8)
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1194b9d1)
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1596fc36)
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@39e60737)
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8ae04a4)
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@325a220d)
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@9cea5c2)
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1989dfd3)
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1218c710)
E/DataBuffer( 1680): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@793d209)
I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5588 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/Keyboard.Facilitator.MainLanguageModelLoader( 1402): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Loading LM = contacts
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1402): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1402): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1402): run()
I/StatsUtilsManager( 1402): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1402): shouldRecordStats() = Too Soon
I/ContactLocale( 5566): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Launcher( 1555): Deferring update until onResume
W/asset   ( 5588): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5588): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5588): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5588): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  879): Explicit concurrent mark sweep GC freed 5197(259KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 1.638ms total 226.946ms
I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5611 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  879): Killing 5085:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/AndroidRuntime( 5538): Shutting down VM
W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_5085/cgroup.procs: No such file or directory
W/ContextImpl( 5611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1935): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1935): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1935): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1680): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1680): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1935): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1935): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1935): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1935): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1935): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1935): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1935): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5642 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1935): doRemovePackageData com.test.thalitest
W/Launcher( 1555): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b323733 new=com.google.android.velvet.VelvetApplication@2b323733
E/SQLiteLog( 1555): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5668 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.177ms
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 19.434ms

```
