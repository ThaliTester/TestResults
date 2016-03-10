#### Test 6012434713fea37_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/Keyboard.Facilitator.LanguageModelFlusher( 1405): run()
I/Keyboard.Facilitator( 1405): flushDynamicLanguageModels()
I/ConfigService( 1691): onCreate
D/AndroidRuntime( 5280): 
D/AndroidRuntime( 5280): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5280): CheckJNI is OFF
D/AndroidRuntime( 5280): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (175 us)
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5280): Shutting down VM
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5299 uid=10565 gids={50565, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5299): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5299): Time to load native libraries: 2 ms (timestamps 9724-9726)
I/LibraryLoader( 5299): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5299): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
,I/LibraryLoader( 5299): Expected native library version number "",actual native library version number ""
,I/chromium( 5299): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5299): Initializing chromium process, singleProcess=true
,W/art     ( 5299): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5299): ApplicationContext is null in ApplicationStatus
,W/chromium( 5299): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5299): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5299): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5299): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5299): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5299): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5299): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5299): Local Branch: 
I/Adreno-EGL( 5299): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5299): Local Patches: NONE
I/Adreno-EGL( 5299): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16fa063e:true
,D/BluetoothAdapter( 5299): 446216149: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5299): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5299): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5299): CordovaWebView is running on device made by: motorola
,W/art     ( 5299): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5299): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5299): Render dirty regions requested: true
,D/Atlas   ( 5299): Validating map...
,W/chromium( 5299): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (44:243 vsyncs) (46:1153)
,I/OpenGLRenderer( 5299): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5299): Enabling debug mode 0
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1048
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +1s48ms
,I/art     (  882): Explicit concurrent mark sweep GC freed 12579(562KB) AllocSpace objects, 1(96KB) LOS objects, 33% free, 20MB/30MB, paused 1.649ms total 133.736ms
,I/Keyboard.Facilitator( 1405): onFinishInput()
,E/Adreno-ES20( 5299): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5299): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5299): Cannot call determinedVisibility() - never saw a connection for the pid: 5299
,V/AlarmManager(  882): send {34279008, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  882): send {30eaf3a1, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  882): done {34279008, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [8ms]
,V/AlarmManager(  882): done {30eaf3a1, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [14ms]
,E/Adreno-ES20( 5299): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5299): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/Finsky  ( 5117): [595] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5117): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/JsMessageQueue( 5299): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5299): JniHelper::setJavaVM(0xb7745310), pthread_self() = -1213563880
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5299): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5299):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5299):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5299):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5299):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5299): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ae68ec added. We now have 1 listener(s)
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5299): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5299): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5299): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5299): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9da6bb added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5299): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  882): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5299): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5299): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5299): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5299): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5299): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5299): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TaskPersister(  882): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/jxcore-log( 5299): Initializing JXcore engine
W/jxcore-log( 5299): JXcore engine is ready
,W/Thread-609( 5374): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10565 path="socket:[7335]" dev="sockfs" ino=7335 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-609( 5374): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10565 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-609( 5374): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10565 path="socket:[7480]" dev="sockfs" ino=7480 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-609( 5374): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10565 path="socket:[23131]" dev="sockfs" ino=23131 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5299): Starting JXcore engine
,W/jxcore-log( 5299): Platform android
W/jxcore-log( 5299): 
,W/jxcore-log( 5299): Process ARCH arm
W/jxcore-log( 5299): 
,I/SFPerfTracer(  278):      triggers: (rate: 11:314) (compose: 0:1) (post: 0:1) (render: 0:2) (16:1117 frames) (17:1214)
D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb7ce8518): 0:14)* (DimLayer (0xb7d00410): 0:6)* (StatusBar (0xb7d06800): 0:153) (NavigationBar (0xb7d5ed70): 0:35) (com.android.systemui.ImageWallpaper (0xb7da0e48): 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7da4658): 0:55)- (Starting com.test.thalitest (0xb7da2560): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7d03ea8): 17:49) 
,I/ConfigService( 1691): onDestroy
,I/jxcore-log( 5299): JXcore Cordova bridge is ready!
I/jxcore-log( 5299): 
,W/jxcore-log( 5299): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5299): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5299): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5299): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5299): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/PluginManager( 5299): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2516): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2516): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2516): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2516): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2516): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2516): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2516): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2516): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5299): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1405): onFinishInput()
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:337 vsyncs) (45:1260)
,I/SFPerfTracer(  278):      triggers: (rate: 11:314) (compose: 0:1) (post: 0:1) (render: 0:3) (16:1157 frames) (17:1262)
D/SFPerfTracer(  278):        layers: (4:10) (FocusedStackFrame (0xb7ce8518): 0:16)* (DimLayer (0xb7d00410): 0:7) (StatusBar (0xb7d06800): 0:172) (NavigationBar (0xb7d5ed70): 0:48) (com.android.systemui.ImageWallpaper (0xb7da0e48): 0:34)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb7d03ea8): 1:76)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7da7ba8): 17:28) 
,I/ActivityManager(  882): Killing 4888:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_4888/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:34000 mC
,D/TaskPersister(  882): removeObsoleteFile: deleting file=8_task.xml
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
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2516):  Nonce Reponse 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309926, SEQNUM=4363, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-22836, POWER_SUPPLY_CHARGE_COUNTER=-607, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  882): send {2ae7d1f2, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  882): done {2ae7d1f2, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [4ms]
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310650, SEQNUM=4365, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-25040, POWER_SUPPLY_CHARGE_COUNTER=-733, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  882): Nap time (uid 1000)...
I/PowerManagerService(  882): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  882): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  882): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  882): Build Date: 10/28/14 Tue
I/Adreno-EGL(  882): Local Branch: 
I/Adreno-EGL(  882): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  882): Local Patches: NONE
I/Adreno-EGL(  882): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  882): activate, handle: 1598182242, enabled: 0, index 2
D/        (  882): BstSensorExt: id=1598182242, en=0
,D/        (  882): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  882): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb7c67550
,I/DisplayManagerService(  882): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  882): Display changed displayId=0
,D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8018820
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1207859912)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1207859912) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8018820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  882): Excessive delay in setPowerMode(): 313ms
,I/PowerManagerService(  882): Sleeping (uid 1000)...
,I/WindowManager(  882): AOD feature not enabled!
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  882): startHal
,E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dc989c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb7745310, mCls = 0x17aa
I/WifiNative-HAL(  882): Could not start hal
D/WifiStateMachine(  882): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  882): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  882): setSuspendOptimizations: 4 false
E/WifiStateMachine(  882): mSuspendOptNeedsDisabled 4
,I/Keyboard.Facilitator( 1405): onFinishInput()
,I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dc989c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb7745310, mCls = 0x20166e
I/WifiNative-HAL(  882): Could not start hal
D/WifiStateMachine(  882): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  882): handleScreenStateChanged Exit: false
,D/        (  882): activate, handle: 1598182229, enabled: 0, index 0
E/        (  882): <BST> disable accel, orig state: 1
,I/        (  882): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
E/WifiStateMachine(  882): setSuspendOptimizations: 4 true
E/WifiStateMachine(  882): mSuspendOptNeedsDisabled 0
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  882): send {4670711, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  882): done {4670711, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310244, SEQNUM=4373, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-18028, POWER_SUPPLY_CHARGE_COUNTER=-828, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = ,
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
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
,E/global frequency( 2516): no tags to log
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1527): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 53524(2MB) AllocSpace objects, 32(1032KB) LOS objects, 39% free, 7MB/12MB, paused 975us total 43.234ms
,I/art     ( 2516): Explicit concurrent mark sweep GC freed 23818(1366KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 10MB/18MB, paused 937us total 56.938ms
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1527): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1527): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  882): Explicit concurrent mark sweep GC freed 14104(875KB) AllocSpace objects, 6(258KB) LOS objects, 33% free, 20MB/31MB, paused 1.461ms total 127.271ms
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 3788(159KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 842us total 31.916ms
,D/BSUtils ( 2516): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2516): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2516): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2516): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2516): BcsDSCheckin.events found events 2000
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2516): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,V/AlarmManager(  882): send {7792cf5, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {3624034d, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  882): done {3624034d, *walarm*:com.google.android.intent.action.SEND_IDLE} [3ms]
,V/AlarmManager(  882): done {7792cf5, *alarm*:android.intent.action.TIME_TICK} [40ms]
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2516): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2516): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2516): unknown error code mapping for: 0
I/global frequency( 2516): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2516): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2516):  Nonce Reponse 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=279, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311010, SEQNUM=4376, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-18529, POWER_SUPPLY_CHARGE_COUNTER=-1004, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1405): run()
I/Keyboard.Facilitator( 1405): flushDynamicLanguageModels()
,I/ConfigService( 1691): onCreate
,I/ClearcutLoggerApiImpl( 1691): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  882): send {30eaf3a1, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  882): send {2ae7d1f2, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  882): send {363a8749, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  882): done {30eaf3a1, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [10ms]
,V/AlarmManager(  882): done {2ae7d1f2, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [12ms]
V/AlarmManager(  882): done {363a8749, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [13ms]
,I/VacuumService( 1691): Vacuum at: now=1457574412414 tag=VacuumService
,I/ConfigService( 1691): onDestroy
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309973, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-1595, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  882): send {7792cf5, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): done {7792cf5, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2516):  Nonce Reponse 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/AlarmManager(  882): send {7792cf5, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {2b88a0fd, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): done {2b88a0fd, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [6ms]
,V/AlarmManager(  882): done {7792cf5, *alarm*:android.intent.action.TIME_TICK} [42ms]
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2516): Explicit concurrent mark sweep GC freed 38386(3MB) AllocSpace objects, 6(148KB) LOS objects, 39% free, 11MB/18MB, paused 1.182ms total 140.653ms
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 3750(161KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 7MB/12MB, paused 509us total 25.235ms
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2516):  Nonce Reponse 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2516): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2516): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2516): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2516): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2516): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2516): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2516): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310124, SEQNUM=4386, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-461, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  882): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/art     (  882): Explicit concurrent mark sweep GC freed 12666(666KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/31MB, paused 1.856ms total 115.850ms
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5502): 
D/AndroidRuntime( 5502): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5502): CheckJNI is OFF
D/AndroidRuntime( 5502): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10565 user=-1: uninstall pkg
I/ActivityManager(  882): Killing 5299:com.test.thalitest/u0a565 (adj 11): stop com.test.thalitest
D/WifiService(  882): Client connection lost with reason: 4
W/PackageSettings(  882): Skipping PackageSetting{f36067b com.example.hello/10564} due to missing metadata
W/ActivityManager(  882): Spurious death for ProcessRecord{236d2574 5299:com.test.thalitest/u0a565}, curProc for 5299: null
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10565 user=0: pkg removed
I/art     ( 2954): Explicit concurrent mark sweep GC freed 3677(803KB) AllocSpace objects, 16(256KB) LOS objects, 39% free, 7MB/12MB, paused 569us total 33.855ms
I/art     ( 5016): Explicit concurrent mark sweep GC freed 679(38KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 400us total 81.959ms
I/Keyboard.Facilitator( 1405): resetDictionaries() : en_US
W/GeofencerStateMachine( 1691): Ignoring removeGeofence because network location is disabled.
I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1405): run()
I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5531 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 4961): Explicit concurrent mark sweep GC freed 2006(98KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/16MB, paused 702us total 153.084ms
I/art     ( 1558): Explicit concurrent mark sweep GC freed 7340(534KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 485us total 120.511ms
I/Decoder ( 1405): createOrResetDecoder
I/art     (  882): Explicit concurrent mark sweep GC freed 6418(552KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 2.174ms total 132.204ms
I/art     (  882): WaitForGcToComplete blocked for 36.775ms for cause Explicit
I/ConfigService( 1691): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1405): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1405): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1405): run()
I/StatsUtilsManager( 1405): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1405): shouldRecordStats() = Too Soon
D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  882): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  882): removeObsoleteFile: deleting file=9_task_thumbnail.png
D/VoicemailCleanupService( 5531): Cleaning up data for package: com.test.thalitest
I/ContactLocale( 5531): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5554 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  882): Explicit concurrent mark sweep GC freed 5095(249KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 2.865ms total 194.959ms
I/Launcher( 1558): Deferring update until onResume
W/asset   ( 5554): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5554): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5554): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5554): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5576 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  882): Killing 5016:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 5502): Shutting down VM
W/ContextImpl( 5576): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_5016/cgroup.procs: No such file or directory
D/ChimeraCfgMgr( 4961): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4961): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 4961): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4961): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4961): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4961): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1691): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1691): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5600 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/LocationSettingsChecker( 4961): Removing dialog suppression flag for package com.test.thalitest
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 846us total 26.117ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 21.674ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 24.641ms
D/gH_CompatibleDatabase( 4961): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4961): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4961): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4961): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4961): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4961): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4961): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/BaseAppContext( 4961): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 4961): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4961): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
W/BaseAppContext( 4961): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 4961): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4961): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4961): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4961): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/GMPM-SVC( 4961): App measurement is starting up, version: 8489
I/GMPM-SVC( 4961): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5634 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/Icing   ( 4961): doRemovePackageData com.test.thalitest
D/ConnectivityService(  882): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
I/art     ( 1691): Explicit concurrent mark sweep GC freed 36749(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 13MB/21MB, paused 1.100ms total 85.402ms

```
