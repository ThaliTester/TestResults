#### Test 62885377aa56850_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/Uploader( 1896): No account for auth token provided
W/Uploader( 1896): No account for auth token provided
W/Uploader( 1896): No account for auth token provided
W/Uploader( 1896):  no longer exists, so no auth token.
W/Uploader( 1896): No account for auth token provided
,I/art     ( 1896): Explicit concurrent mark sweep GC freed 28234(1522KB) AllocSpace objects, 6(460KB) LOS objects, 47% free, 4MB/8MB, paused 2.389ms total 59.839ms
I/GLSUser ( 1896): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1896): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1896): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1896): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1896): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Uploader( 1896): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1896): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1896): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1896): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1896): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1896): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1896): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1896): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1896): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1896): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1896): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1896): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1896): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1242): reapply : com.google.android.gms 3 40
W/Uploader( 1896): No account for auth token provided
E/cutils-trace( 6683): Error opening trace file: Permission denied (13)
--------- beginning of system
D/PMS     (  928): releaseWL(14936730): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  928): acquireWL(aa6fc60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1896 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  928): releaseWL(aa6fc60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  928): acquireWL(3c3ee519): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1896 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  928): releaseWL(3c3ee519): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/CustomizationManager( 6683): ====startRecUseTime====
D/htc.customization.log.level( 6683):  is 
W/CustomizationLogLevel( 6683): Level value is invalid, use default level 2
D/CustomizationManager( 6683):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 6683): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6683): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6683): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6683): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6683): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6683): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6683): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6683): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6683): Parsing tag category name = system
I/CustomizationCIDLoader( 6683): Parsing tag category name = application
I/CustomizationCIDLoader( 6683): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6683): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6683): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6683): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6683): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6683): add string-array item, value = 42507
I/CustomizationCIDLoader( 6683): add string-array item, value = 21902
I/CustomizationCIDLoader( 6683): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6683): add string-array item, value = 23420
I/CustomizationCIDLoader( 6683): add string-array item, value = 22299
I/CustomizationCIDLoader( 6683): add string-array item, value = 24002
I/CustomizationCIDLoader( 6683): add string-array item, value = 23210
I/CustomizationCIDLoader( 6683): add string-array item, value = 23205
I/CustomizationCIDLoader( 6683): add string-array item, value = 23806
I/CustomizationCIDLoader( 6683): add string-array item, value = 23430
I/CustomizationCIDLoader( 6683): add string-array item, value = 23408
I/CustomizationCIDLoader( 6683): add string-array item, value = 27205
I/CustomizationCIDLoader( 6683): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6683): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6683):  Read CID file spent 0.106 (s)
D/CustomizationManager( 6683):  All configurations done spent 0.107 (s)
I/ActivityManager(  928): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6683 on display 0
D/PMS     (  928): acquireHCC(1aeb59de): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 928 1000 null
D/PMS     (  928): acquireHCC(b4b17bf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 928 1000 null
W/asset   (  928): Copying FileAsset 0x556416e8b0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  928): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6701 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  928): Display changed displayId=0
D/DotMatrix( 1330): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1330): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6701): Copying FileAsset 0xabf8e938 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1646): [trimMemory] 20
I/WebViewFactory( 6701): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6701): Time to load native libraries: 10 ms (timestamps 4361-4371)
,I/LibraryLoader( 6701): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6701): Binding Chromium to main looper Looper (main, tid 1) {2499b9e2}
,I/LibraryLoader( 6701): Expected native library version number "",actual native library version number ""
,I/chromium( 6701): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6701): Initializing chromium process, singleProcess=true
,W/art     ( 6701): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6701): ApplicationContext is null in ApplicationStatus
,W/chromium( 6701): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6701): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6701): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6701): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6701): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6701): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6701): Local Branch: 
I/Adreno-EGL( 6701): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6701): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6701):                  d74aa161a12b9c6fc6332151
,W/System.err(  928): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  928): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  928): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  928): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  928): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  928): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  928): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a151324:true
D/BluetoothAdapter( 6701): 1058902574: getState(). Returning 12,
,W/art     ( 6701): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6701): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6701): CordovaWebView is running on device made by: HTC
,W/art     ( 6701): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6701): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  928): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6701): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/StatusBarManagerService(  928): setSystemUiVisibility(0xc0000600)
D/StatusBarManagerService(  928): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  928): hiding MENU key
D/StatusBarManagerService(  928): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  928): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  928): hiding MENU key
,D/FindExtension( 6701): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6701): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@335515db, mServedView=org.apache.cordova.engine.SystemWebView{a453878 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1b7dcb51
I/InputMethodManagerService(  928): Disable input method client, pid=1646
I/PhoneStatusBar( 1242): setImeWindowStatus(false,false)
D/StatusBarManagerService(  928): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6701): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  928): Displayed com.test.thalitest/.MainActivity: +683ms (total +728ms)
,W/BindingManager( 6701): Cannot call determinedVisibility() - never saw a connection for the pid: 6701
,D/JsMessageQueue( 6701): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6701): JniHelper::setJavaVM(0xaae238f8), pthread_self() = -1407649520
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6701): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6701):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6701):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6701):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6701):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6701): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c02df45 added. We now have 1 listener(s)
,D/BluetoothManagerService(  928): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6701): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6701): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6701): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6701): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701):     - Discovery mode: BLE,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b3afa8 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6701): addListener: New listener added - the number of listeners is now 1
D/WifiService(  928): New client listening to asynchronous messages
E/WifiTrafficPoller(  928): ADD_CLIENT: 8
,D/BluetoothAdapter( 6701): 1058902574: getState(). Returning 12
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6701): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6701): setScanMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6701): bind: Binding a new listener
,D/BluetoothManagerService(  928): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6701): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothAdapter( 6701): 1058902574: getState(). Returning 12
,V/io.jxcore.node.ConnectivityMonitor( 6701): updateConnectivityInfo: FORCED notification:
V/io.jxcore.node.ConnectivityMonitor( 6701):     - is Wi-Fi Direct supported: true
V/io.jxcore.node.ConnectivityMonitor( 6701):     - is Bluetooth LE multiple advertisement supported: SUPPORTED
V/io.jxcore.node.ConnectivityMonitor( 6701):     - is Wi-Fi enabled: true
V/io.jxcore.node.ConnectivityMonitor( 6701):     - is Bluetooth enabled: true
V/io.jxcore.node.ConnectivityMonitor( 6701):     - BSSID name: f4:f2:6d:22:99:3e
V/io.jxcore.node.ConnectivityMonitor( 6701):     - is connected/connecting to active network: true
V/io.jxcore.node.ConnectivityMonitor( 6701):     - active network type is Wi-Fi: true
D/io.jxcore.node.JXcoreExtension( 6701): notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
D/io.jxcore.node.ConnectivityMonitor( 6701): start: OK
V/io.jxcore.node.ConnectivityMonitor( 6701): updateConnectivityInfo: No relevant state changes
,V/io.jxcore.node.ConnectivityMonitor( 6701): updateConnectivityInfo: No relevant state changes
,I/chromium( 6701): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6701): Initializing JXcore engine,
W/jxcore-log( 6701): JXcore engine is ready
,W/jxcore-log( 6701): Starting JXcore engine
,W/jxcore-log( 6701): Platform android,
W/jxcore-log( 6701): 
W/jxcore-log( 6701): Process ARCH arm
W/jxcore-log( 6701): 
,D/PMS     (  928): releaseHCC(1aeb59de): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  928): releaseHCC(b4b17bf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null,
,I/jxcore-log( 6701): JXcore Cordova bridge is ready!
I/jxcore-log( 6701): 
W/jxcore-log( 6701): JXcore engine is started
I/org.thaliproject.p2p.ThaliPermissions( 6701): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 6701): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6701): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6701): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/Process (  928): killProcessQuiet, pid=5893,
I/ActivityManager(  928): Killing 5893:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  928): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  928): Recipient 5893
,W/PluginManager( 6701): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 240ms. Plugin should use CordovaInterface.getThreadPool().
,E/ActivityThread( 6701): Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@30f72ac1 that was originally registered here. Are you missing a call to unregisterReceiver()?,
E/ActivityThread( 6701): android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@30f72ac1 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6701): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 6701): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 6701): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread( 6701): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread( 6701): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1749)
E/ActivityThread( 6701): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
E/ActivityThread( 6701): 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
E/ActivityThread( 6701): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
E/ActivityThread( 6701): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
E/ActivityThread( 6701): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
E/ActivityThread( 6701): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
E/ActivityThread( 6701): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
E/ActivityThread( 6701): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
E/ActivityThread( 6701): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
E/ActivityThread( 6701): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
E/ActivityThrea,d( 6701): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
E/ActivityThread( 6701): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
E/ActivityThread( 6701): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6701): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 6701): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityThread( 6701): Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3a8a3266 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6701): android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3a8a3266 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6701): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 6701): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 6701): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread( 6701): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread( 6701): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1749)
E/ActivityThread( 6701): 	,at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
E/ActivityThread( 6701): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
E/ActivityThread( 6701): 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
E/ActivityThread( 6701): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
E/ActivityThread( 6701): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
E/ActivityThread( 6701): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
E/ActivityThread( 6701): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
E/ActivityThread( 6701): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
E/ActivityThread( 6701): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
E/ActivityThread( 6701): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
E/ActivityThread( 6701): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
E/ActivityThread( 6701): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
E/ActivityThread( 6701): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
E/ActivityThread( 6701): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6701): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 6701): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/HtcUPManager( 1242): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1242): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1553): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@e99058f
,D/Process (  928): killProcessQuiet, pid=5536,
,I/ActivityManager(  928): Killing 5536:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  928): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  928): Recipient 5536
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 1
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  928): acquireWL(332bd816): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  928): n_update end
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  928): releaseWL(332bd816): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1242): closing low battery warning: level=100
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  928): updateBatteryInfo
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/PMS     (  928): runPSCheck
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  928): Checking...
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  928): >> updateStatus
,D/WifiController(  928): handleMessage: E msg.what=155652
D/WifiController(  928): battery changed pluggedType: 2
D/WifiController(  928): processMsg: DeviceActiveState
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  928): processMsg: StaEnabledState
I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  928): processMsg: DefaultState
I/HtcPowerSaver(  928): << updateStatus
D/WifiController(  928): handleMessage: X
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 4
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  928): acquireWL(1c85e597): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  928): n_update end
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  928): releaseWL(1c85e597): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  928): updateBatteryInfo
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/PowerUI ( 1242): closing low battery warning: level=100
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/PMS     (  928): runPSCheck
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  928): Checking...
D/UsbnetService(  928): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  928): >> updateStatus
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  928): handleMessage: E msg.what=155652
D/WifiController(  928): processMsg: DeviceActiveState
D/WifiController(  928): battery changed pluggedType: 2
D/WifiController(  928): processMsg: StaEnabledState
D/WifiController(  928): processMsg: DefaultState
D/WifiController(  928): handleMessage: X
,I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  928): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1370): wlan0: BSS: Remove id 1 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1370): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1370): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1370): wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:dd:e2 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1370): wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  928): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 f0:f2:6d:22:99:3e]
D/wpa_supplicant( 1370): wlan0: BSS: Remove id 5 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
E/WifiMonitor(  928): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 f0:f2:6d:22:99:3e
D/wpa_supplicant( 1370): wlan0: BSS: Remove id 6 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  928): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1]
E/WifiMonitor(  928): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1
D/WifiMonitor(  928): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0]
E/WifiMonitor(  928): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0
D/WifiMonitor(  928): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:dd:e2]
E/WifiMonitor(  928): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:dd:e2
D/WifiMonitor(  928): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e3]
E/WifiMonitor(  928): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e3
D/WifiMonitor(  928): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:e0:43]
E/WifiMonitor(  928): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:e0:43
D/WifiMonitor(  928): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:22:0d:46:1c:a3]
E/WifiMonitor(  928): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:22:0d:46:1c:a3
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  928): acquireWL(1ac0f384): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null,
I/BatteryService(  928): n_update end
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/PMS     (  928): releaseWL(1ac0f384): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  928): plugged=true pluggin=true
,D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  928): updateBatteryInfo
D/WifiController(  928): handleMessage: E msg.what=155652
D/PMS     (  928): runPSCheck
D/WifiController(  928): processMsg: DeviceActiveState
D/HtcPowerSaver(  928): Checking...
D/WifiController(  928): processMsg: StaEnabledState
I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): processMsg: DefaultState
D/WifiController(  928): battery changed pluggedType: 2
,D/WifiController(  928): handleMessage: X
D/PowerUI ( 1242): closing low battery warning: level=100
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  928): << updateStatus
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1896): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1896): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1896): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1896): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1896): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1896): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1896): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1896): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1896): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1896): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1896): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1896): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1896): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1242): reapply : com.google.android.gms 2 40
,E/PlayEventLogger( 6086): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6086): ,	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6086): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6086): Ignoring header User-Agent because its value was null.,
,D/libc    ( 6086): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6086): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 6086): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6086): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6086): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6086): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6086): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  928): acquireWL(3ae872c6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
I/BatteryService(  928): n_update end
D/PMS     (  928): releaseWL(3ae872c6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  928): BroadcastReceiver::onReceive+,
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/WifiController(  928): battery changed pluggedType: 2
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/WifiController(  928): handleMessage: E msg.what=155652
,D/WifiController(  928): processMsg: DeviceActiveState
D/WifiController(  928): processMsg: StaEnabledState
D/WifiController(  928): processMsg: DefaultState
D/WifiController(  928): handleMessage: X
D/HtcPowerSaver(  928): updateBatteryInfo
,D/PMS     (  928): runPSCheck
D/HtcPowerSaver(  928): Checking...
I/HtcPowerSaver(  928): >> updateStatus
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1242): closing low battery warning: level=100
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  928): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  928): acquireWL(33156287): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 928 1000 WorkSource{1000},
V/AlarmManager(  928): sending alarm PendingIntent{e90f348: PendingIntentRecord{f87b5e1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=250387, Int=0
,V/AlarmManager(  928): sending alarm PendingIntent{c54b5dd: PendingIntentRecord{1568f552 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1458040649884, Int=0,
,I/ActivityManager(  928): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6765 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  928): sending alarm PendingIntent{27dba023: PendingIntentRecord{21600920 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1458040739009, Int=0,
,D/PMS     (  928): releaseWL(33156287): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1242): Weather sync is On
W/WeatherTimeKeeper( 1242): [refreshWeatherData] no weather data
,D/StatusBarManagerService(  928): setSystemUiVisibility(0x8700),
D/StatusBarManagerService(  928): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  928): hiding MENU key
,D/StatusBarManagerService(  928): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  928): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  928): hiding MENU key
,D/FindExtension( 1646): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
I/ThreadedRenderer( 1646): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  928): Disable input method client, pid=6701,
D/StatusBarManagerService(  928): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6701): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6701): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6701): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1242): setImeWindowStatus(false,false)
,E/cutils-trace( 6789): Error opening trace file: Permission denied (13),
I/dex2oat ( 6789): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6789): dex2oat: override thread count:4,
,I/dex2oat ( 6789): dex2oat took 957.087ms (threads: 4)
,I/PushClient( 6765): ApplicationMonitor {3f1d922e}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6765): ApplicationMonitor {3f1d922e}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6765): ApplicationMonitor {3f1d922e}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6765): ApplicationMonitor {3f1d922e}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6765): ApplicationMonitor {3f1d922e}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk,
,I/PushClient( 6765): ApplicationMonitor {3f1d922e}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6765): ApplicationMonitor {3f1d922e}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6765): ApplicationMonitor {3f1d922e}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6765): ApplicationMonitor {3f1d922e}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6765): PnsModel {2f908ca9}: update(): Update registration caused by: alarm
,I/PushClient( 6765): PnsConfigModel {326295f4}: <init>(): Use dm-client for provisioning.
,W/System.err( 6765): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6765): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6765): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6765): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  928): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6796 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6796): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6796 dbg=false s=true
,I/DeviceManagement( 6796): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6796): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6796): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6796): WorkflowService: Starting workflow service
,I/DeviceManagement( 6796): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2f908ca9] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6796): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6796): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6796): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6796): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6796): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6796): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6796): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6796): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2f908ca9]
,I/DeviceManagement( 6796): WorkflowService: Stopping workflow service
,D/Process (  928): killProcessQuiet, pid=6500,
I/ActivityManager(  928): Killing 6500:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  928): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  928): Recipient 6500
,I/PushClient( 6765): PnsModel {2f908ca9}: update(): The registration record has not expired yet. No need to update.
,I/ActivityManager(  928): Killing 6455:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  928): killProcessQuiet, pid=6455
D/Process (  928): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  928): Recipient 6455,
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1587): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1587): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1587): sku_id=118
D/ContactMessageStore( 1587): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1587): start background delete task...
,D/ContactMessageStore( 1587): size: 0 , 0
,D/ContactMessageStore( 1587): Background delete complete
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  928): acquireWL(3613d04d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null,
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  928): n_update end
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  928): releaseWL(3613d04d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/NotificationService(  928): plugged=true pluggin=true
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1242): closing low battery warning: level=100
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  928): updateBatteryInfo
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/PMS     (  928): runPSCheck
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  928): Checking...
D/UsbnetService(  928): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): handleMessage: E msg.what=155652
D/WifiController(  928): battery changed pluggedType: 2
D/WifiController(  928): processMsg: DeviceActiveState
,D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  928): processMsg: StaEnabledState
D/WifiController(  928): processMsg: DefaultState
D/WifiController(  928): handleMessage: X
I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  928): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  928): acquireWL(38755702): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
I/BatteryService(  928): n_update end
D/PMS     (  928): releaseWL(38755702): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  928): updateBatteryInfo
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  928): runPSCheck
D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  928): Checking...,
D/WifiController(  928): handleMessage: E msg.what=155652
I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): processMsg: DeviceActiveState
D/WifiController(  928): battery changed pluggedType: 2
D/WifiController(  928): processMsg: StaEnabledState
D/PowerUI ( 1242): closing low battery warning: level=100
D/WifiController(  928): processMsg: DefaultState
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  928): handleMessage: X
I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  928): << updateStatus
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  928): acquireWL(1804d813): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  928): n_update end
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  928): releaseWL(1804d813): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/WifiController(  928): battery changed pluggedType: 2
,D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1242): closing low battery warning: level=100
D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  928): updateBatteryInfo
D/WifiController(  928): handleMessage: E msg.what=155652
D/PMS     (  928): runPSCheck
D/WifiController(  928): processMsg: DeviceActiveState
D/HtcPowerSaver(  928): Checking...
D/WifiController(  928): processMsg: StaEnabledState
I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): processMsg: DefaultState
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  928): handleMessage: X
I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0,
I/HtcPowerSaver(  928): << updateStatus
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  928): acquireWL(2597fa50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  928): n_update end
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  928): releaseWL(2597fa50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  928): updateBatteryInfo
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/PowerUI ( 1242): closing low battery warning: level=100
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/NotificationService(  928): plugged=true pluggin=true
,D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  928): runPSCheck
D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  928): Checking...
D/WifiController(  928): handleMessage: E msg.what=155652
I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): processMsg: DeviceActiveState
D/WifiController(  928): battery changed pluggedType: 2
D/WifiController(  928): processMsg: StaEnabledState
,I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  928): processMsg: DefaultState
I/HtcPowerSaver(  928): << updateStatus
D/WifiController(  928): handleMessage: X
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  928): acquireWL(39da2449): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 928 1000 WorkSource{1000},
,I/bt-btm  ( 3229): Received oneshot timer event complete
V/AlarmManager(  928): sending alarm PendingIntent{e90f348: PendingIntentRecord{f87b5e1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=430387, Int=0
V/AlarmManager(  928): sending alarm PendingIntent{3265e14e: PendingIntentRecord{105ae26f com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940113, Int=0
I/bt-btm  ( 3229): btm_ble_timeout
I/bt-btm  ( 3229): btm_gen_resolvable_private_addr,
D/PMS     (  928): acquireWL(388a6b7c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3229 1002 null
,D/bt-btm  ( 3229): btm_ble_rand_enc_complete,
I/bt-btm  ( 3229): btm_gen_resolve_paddr_low
D/bt-smp  ( 3229): smp_encrypt_data
W/bt-smp  ( 3229): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3229): Plain text(LSB ~ MSB) = f2 41 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3229): Encrypted text(LSB ~ MSB) = 7b 0c f6 d5 3e 5b f0 54 6e 6b 60 35 70 c1 43 ed 
I/bt-btm  ( 3229): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3229): Stopping oneshot timer
D/bt-btm  ( 3229): Starting oneshot timer type:103 timeout:900s,
,D/WeatherUtility( 1242): Weather sync is On
D/PMS     (  928): releaseWL(39da2449): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1242): [refreshWeatherData] no weather data
,D/PMS     (  928): releaseWL(388a6b7c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  928): acquireWL(1d97bc05): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
I/BatteryService(  928): n_update end
D/PMS     (  928): releaseWL(1d97bc05): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/PowerUI ( 1242): closing low battery warning: level=100
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  928): updateBatteryInfo
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/PMS     (  928): runPSCheck
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  928): Checking...
D/UsbnetService(  928): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): handleMessage: E msg.what=155652
D/WifiController(  928): battery changed pluggedType: 2
D/WifiController(  928): processMsg: DeviceActiveState
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  928): processMsg: StaEnabledState
I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  928): processMsg: DefaultState
I/HtcPowerSaver(  928): << updateStatus
D/WifiController(  928): handleMessage: X
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  928): acquireWL(5c2c45a): PARTIAL_WAKE_LOCK  *alarm* 0x1 928 1000 WorkSource{10024}
V/AlarmManager(  928): sending alarm PendingIntent{35d368b: PendingIntentRecord{fd0c368 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=933942, Int=0
D/PMS     (  928): acquireWL(21dd1381): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1896 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  928): sending alarm PendingIntent{1b7f6ead: PendingIntentRecord{fc905e2 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804409, Int=0
V/AlarmManager(  928): sending alarm PendingIntent{1dd8cc26: PendingIntentRecord{1a169b4f com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1458041275953, Int=0
,D/PMS     (  928): releaseWL(21dd1381): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6591): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  928): releaseWL(5c2c45a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 6591): MY_DEBUG = false
,D/PowerUsageService( 6591): repeat time = 1458042175989
,D/PMS     (  928): acquireWL(38a2ae14): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1896 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1896): Message class com.google.f.a.a.i,
,D/PMS     (  928): releaseWL(38a2ae14): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 6591): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6591): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6591): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6591): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 6591): calcPower(), no data
,D/PMS     (  928): acquireWL(25c666bd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 928 1000 WorkSource{1000},
V/AlarmManager(  928): sending alarm PendingIntent{e90f348: PendingIntentRecord{f87b5e1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=970387, Int=0
V/AlarmManager(  928): sending alarm PendingIntent{3bf584b2: PendingIntentRecord{29a3ec03 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1458041322129, Int=0
,D/SmartSyncUtils( 6591): isEpsOn(), nState = 0,
D/PMS     (  928): acquireWL(3a069780): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6591 1000 null
D/PMS     (  928): releaseWL(25c666bd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6591): [updateNmRange] bManual = false,
,D/WeatherUtility( 1242): Weather sync is On
W/WeatherTimeKeeper( 1242): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6591): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6591): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6591): SettingOnTime = 1458108000000, randomSettingOnTime = 1458105087000,
D/SmartSyncScreenOnOffTimeReceiver( 6591): SettingOffTime = 1458086400000, randomSettingOffTime = 1458091832000
,D/SmartSyncScreenOnOffTimeReceiver( 6591): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6591): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6591): bNightModeTurnOffOnce = false
,D/PMS     (  928): releaseWL(3a069780): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  928): acquireWL(23f7b1b9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null,
I/BatteryService(  928): n_update end
D/PMS     (  928): releaseWL(23f7b1b9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  928): BroadcastReceiver::onReceive+,
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/WifiController(  928): battery changed pluggedType: 2
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  928): updateBatteryInfo
D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/PMS     (  928): runPSCheck
,D/WifiController(  928): handleMessage: E msg.what=155652
D/HtcPowerSaver(  928): Checking...
D/WifiController(  928): processMsg: DeviceActiveState
I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): processMsg: StaEnabledState
D/PowerUI ( 1242): closing low battery warning: level=100
D/WifiController(  928): processMsg: DefaultState
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  928): handleMessage: X
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  928): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  928): User[0] Flushing usage stats to disk
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  928): acquireWL(36b339fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  928): n_update end
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  928): releaseWL(36b339fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  928): updateBatteryInfo
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/PowerUI ( 1242): closing low battery warning: level=100
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  928): runPSCheck
D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  928): Checking...
I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): handleMessage: E msg.what=155652
D/WifiController(  928): processMsg: DeviceActiveState
D/WifiController(  928): battery changed pluggedType: 2
D/WifiController(  928): processMsg: StaEnabledState
D/WifiController(  928): processMsg: DefaultState
D/WifiController(  928): handleMessage: X
,I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  928): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,E/cutils-trace( 6833): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 6833): ====startRecUseTime====,
D/htc.customization.log.level( 6833):  is 
W/CustomizationLogLevel( 6833): Level value is invalid, use default level 2
,D/CustomizationManager( 6833):  Read ACC file spent 0.064 (s),
,D/CIDMapFileReader( 6833): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 6833): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 6833): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6833): Parsing tag item name = HTC__032,
D/CIDMapFileReader( 6833): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6833): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 6833): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 6833): full path : /system/customize/CID/HTC__102.xml,
I/CustomizationCIDLoader( 6833): Parsing tag category name = system
,I/CustomizationCIDLoader( 6833): Parsing tag category name = application
,I/CustomizationCIDLoader( 6833): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 6833): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6833): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6833): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6833): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 6833): add string-array item, value = 42507,
I/CustomizationCIDLoader( 6833): add string-array item, value = 21902
I/CustomizationCIDLoader( 6833): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6833): add string-array item, value = 23420
I/CustomizationCIDLoader( 6833): add string-array item, value = 22299
I/CustomizationCIDLoader( 6833): add string-array item, value = 24002,
I/CustomizationCIDLoader( 6833): add string-array item, value = 23210
I/CustomizationCIDLoader( 6833): add string-array item, value = 23205
I/CustomizationCIDLoader( 6833): add string-array item, value = 23806
I/CustomizationCIDLoader( 6833): add string-array item, value = 23430
I/CustomizationCIDLoader( 6833): add string-array item, value = 23408,
I/CustomizationCIDLoader( 6833): add string-array item, value = 27205
I/CustomizationCIDLoader( 6833): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6833): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6833): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6833): add string-array item, value = 23420:D:0:0
,I/CustomizationCIDLoader( 6833): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6833): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6833): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6833): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6833): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6833): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6833): add string-array item, value = 23408:C:1:0
,I/CustomizationCIDLoader( 6833): add string-array item, value = 27205:C:1:0
,D/CustomizationManager( 6833):  Read CID file spent 0.126 (s)
D/CustomizationManager( 6833):  All configurations done spent 0.126 (s)
,D/PMS     (  928): acquireWL(3e6f455f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
I/BatteryService(  928): n_update end
,D/PMS     (  928): releaseWL(3e6f455f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  928): updateBatteryInfo
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/PowerUI ( 1242): closing low battery warning: level=100
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  928): runPSCheck
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  928): Checking...
D/UsbnetService(  928): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): handleMessage: E msg.what=155652
D/WifiController(  928): battery changed pluggedType: 2
D/WifiController(  928): processMsg: DeviceActiveState
D/WifiController(  928): processMsg: StaEnabledState
D/WifiController(  928): processMsg: DefaultState
D/WifiController(  928): handleMessage: X
,D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  928): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,E/cutils-trace( 6857): Error opening trace file: Permission denied (13),
,D/CustomizationManager( 6857): ====startRecUseTime====,
,D/htc.customization.log.level( 6857):  is 
W/CustomizationLogLevel( 6857): Level value is invalid, use default level 2
,D/CustomizationManager( 6857):  Read ACC file spent 0.037 (s)
,D/CIDMapFileReader( 6857): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6857): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6857): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6857): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6857): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6857): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6857): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 6857): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 6857): Parsing tag category name = system
,I/CustomizationCIDLoader( 6857): Parsing tag category name = application
I/CustomizationCIDLoader( 6857): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 6857): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6857): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6857): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6857): Parsing tag category name = ACC,
I/CustomizationCIDLoader( 6857): add string-array item, value = 42507
I/CustomizationCIDLoader( 6857): add string-array item, value = 21902
I/CustomizationCIDLoader( 6857): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6857): add string-array item, value = 23420
I/CustomizationCIDLoader( 6857): add string-array item, value = 22299
I/CustomizationCIDLoader( 6857): add string-array item, value = 24002
I/CustomizationCIDLoader( 6857): add string-array item, value = 23210
I/CustomizationCIDLoader( 6857): add string-array item, value = 23205
I/CustomizationCIDLoader( 6857): add string-array item, value = 23806
I/CustomizationCIDLoader( 6857): add string-array item, value = 23430
I/CustomizationCIDLoader( 6857): add string-array item, value = 23408
I/CustomizationCIDLoader( 6857): add string-array item, value = 27205
I/CustomizationCIDLoader( 6857): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6857): add string-array item, value = 21902:C:1:0,
I/CustomizationCIDLoader( 6857): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6857): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6857): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6857): add string-array item, value = 24002:D:0:0,
I/CustomizationCIDLoader( 6857): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6857): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6857): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6857): add string-array item, value = 23430:C:1:0
,I/CustomizationCIDLoader( 6857): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6857): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6857):  Read CID file spent 0.074 (s)
D/CustomizationManager( 6857):  All configurations done spent 0.074 (s)
,D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/PMS     (  928): acquireWL(2fdabac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
D/UsbnetService(  928): onReceive BATTERY_CHANGED
I/BatteryService(  928): n_update end
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  928): releaseWL(2fdabac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/NotificationService(  928): plugged=true pluggin=true
D/WifiController(  928): handleMessage: E msg.what=155652
D/WifiController(  928): battery changed pluggedType: 2
D/WifiController(  928): processMsg: DeviceActiveState
D/PowerUI ( 1242): closing low battery warning: level=100
D/WifiController(  928): processMsg: StaEnabledState
D/HtcPowerSaver(  928): updateBatteryInfo
D/WifiController(  928): processMsg: DefaultState
D/PMS     (  928): runPSCheck
D/WifiController(  928): handleMessage: X
D/HtcPowerSaver(  928): Checking...
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  928): >> updateStatus
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  928): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  928): acquireWL(358b075): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
I/BatteryService(  928): n_update end
D/PMS     (  928): releaseWL(358b075): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  928): updateBatteryInfo
D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/WifiController(  928): battery changed pluggedType: 2
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  928): runPSCheck
D/UsbnetService(  928): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  928): Checking...
D/WifiController(  928): handleMessage: E msg.what=155652,
I/HtcPowerSaver(  928): >> updateStatus
D/WifiController(  928): processMsg: DeviceActiveState
D/WifiController(  928): processMsg: StaEnabledState
D/WifiController(  928): processMsg: DefaultState
D/WifiController(  928): handleMessage: X
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  928): << updateStatus
,D/PowerUI ( 1242): closing low battery warning: level=100
,D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  928): acquireWL(2204f80a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 928 1000 null
I/BatteryService(  928): n_update end
D/PMS     (  928): releaseWL(2204f80a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  928): updateBatteryInfo
,D/UsbnetService(  928): BroadcastReceiver::onReceive+
D/NotificationService(  928): plugged=true pluggin=true
D/UsbnetService(  928): onReceive BATTERY_CHANGED
D/PMS     (  928): runPSCheck
D/UsbnetService(  928):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  928): Checking...
D/UsbnetService(  928): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  928): >> updateStatus
D/PowerUI ( 1242): closing low battery warning: level=100
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  928): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  928): << updateStatus
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  928): handleMessage: E msg.what=155652
D/WifiController(  928): processMsg: DeviceActiveState
D/WifiController(  928): processMsg: StaEnabledState
D/WifiController(  928): processMsg: DefaultState
,D/WifiController(  928): handleMessage: X
D/WifiController(  928): battery changed pluggedType: 2
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1400000ms)
```
