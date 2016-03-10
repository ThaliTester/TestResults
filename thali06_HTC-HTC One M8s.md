#### Test 60124347e678b8e_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
D/TelephonyReceiver( 1563): switchBindHtcMsgCursor: null
E/cutils-trace( 6528): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6528): ====startRecUseTime====
D/htc.customization.log.level( 6528):  is 
W/CustomizationLogLevel( 6528): Level value is invalid, use default level 2
D/CustomizationManager( 6528):  Read ACC file spent 0.073 (s)
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6528): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6528): Parsing tag category name = system
I/CustomizationCIDLoader( 6528): Parsing tag category name = application
I/CustomizationCIDLoader( 6528): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6528): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6528): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6528): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6528): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6528): add string-array item, value = 42507
I/CustomizationCIDLoader( 6528): add string-array item, value = 21902
I/CustomizationCIDLoader( 6528): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6528): add string-array item, value = 23420
I/CustomizationCIDLoader( 6528): add string-array item, value = 22299
I/CustomizationCIDLoader( 6528): add string-array item, value = 24002
I/CustomizationCIDLoader( 6528): add string-array item, value = 23210
I/CustomizationCIDLoader( 6528): add string-array item, value = 23205
I/CustomizationCIDLoader( 6528): add string-array item, value = 23806
I/CustomizationCIDLoader( 6528): add string-array item, value = 23430
I/CustomizationCIDLoader( 6528): add string-array item, value = 23408
I/CustomizationCIDLoader( 6528): add string-array item, value = 27205
I/CustomizationCIDLoader( 6528): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6528):  Read CID file spent 0.133 (s)
D/CustomizationManager( 6528):  All configurations done spent 0.134 (s)
--------- beginning of system
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6528 on display 0
D/PMS     (  972): acquireHCC(b0a8f67): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 972 1000 null
D/PMS     (  972): acquireHCC(3bdaa114): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 972 1000 null
I/ActivityManager(  972): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6546 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  972): Display changed displayId=0
D/DotMatrix( 1310): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1310): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1622): [trimMemory] 20
I/WebViewFactory( 6546): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6546): Time to load native libraries: 9 ms (timestamps 9223-9232),
,I/LibraryLoader( 6546): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6546): Binding Chromium to main looper Looper (main, tid 1) {22230139},
I/LibraryLoader( 6546): Expected native library version number "",actual native library version number ""
,I/chromium( 6546): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6546): Initializing chromium process, singleProcess=true,
,W/art     ( 6546): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6546): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6546): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6546): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6546): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6546): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6546): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6546): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6546): Local Branch: 
I/Adreno-EGL( 6546): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6546): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6546):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER,
W/System.err(  972): java.lang.Throwable: stack dump
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13b55998:true
,D/BluetoothAdapter( 6546): 1034516469: getState(). Returning 12
,W/art     ( 6546): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6546): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6546): CordovaWebView is running on device made by: HTC
,W/art     ( 6546): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6546): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  972): Activity pause timeout for ActivityRecord{2a2ddbd u0 com.test.thalitest/.MainActivity t12},
,W/HtcSystemUPManager(  972): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6546): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000600)
,D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key,
D/StatusBarManagerService(  972): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  972): hiding MENU key
,D/FindExtension( 6546): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6546): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4c23f06, mServedView=org.apache.cordova.engine.SystemWebView{3a8cd9c7 VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@f3d8bf4,
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/InputMethodManagerService(  972): Disable input method client, pid=1622
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6546): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  972): Displayed com.test.thalitest/.MainActivity: +657ms (total +713ms),
,W/BindingManager( 6546): Cannot call determinedVisibility() - never saw a connection for the pid: 6546
,D/JsMessageQueue( 6546): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6546): JniHelper::setJavaVM(0xaaf578f8), pthread_self() = -1406623712
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6546): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6546):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6546):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6546):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6546):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6546): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@204e4e78 added. We now have 1 listener(s)
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546): setBluetoothMacAddress: 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6546): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6546): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b55da24 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6546): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  972): New client listening to asynchronous messages
,E/WifiTrafficPoller(  972): ADD_CLIENT: 8
,D/BluetoothAdapter( 6546): 1034516469: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6546): setDiscoveryMode: Discovery mode BLE is supported,
,D/BluetoothAdapter( 6546): 1034516469: getState(). Returning 12
,I/chromium( 6546): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,W/jxcore-log( 6546): Initializing JXcore engine,
W/jxcore-log( 6546): JXcore engine is ready
,W/jxcore-log( 6546): Starting JXcore engine
,W/jxcore-log( 6546): Platform android
W/jxcore-log( 6546): ,
,W/jxcore-log( 6546): Process ARCH arm
W/jxcore-log( 6546): 
,D/PMS     (  972): releaseHCC(b0a8f67): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  972): releaseHCC(3bdaa114): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6546): JXcore Cordova bridge is ready!
I/jxcore-log( 6546): 
,W/jxcore-log( 6546): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6546): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 6546): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6546): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6546): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,I/ActivityManager(  972): Killing 5427:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=5427
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  972): Recipient 5427,
,W/PluginManager( 6546): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 241ms. Plugin should use CordovaInterface.getThreadPool().,
,D/PMS     (  972): acquireWL(2885fe9d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000},
,V/AlarmManager(  972): sending alarm PendingIntent{62bcc91: PendingIntentRecord{22077f6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=168871, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{1f0f6f12: PendingIntentRecord{2755f6e3 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=191761, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{76578e0: PendingIntentRecord{2e48e799 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189655, Int=0
,D/PMS     (  972): acquireWL(24f16a5e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(2885fe9d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On,
D/PMS     (  972): acquireWL(2be71e3f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  972): releaseWL(24f16a5e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  972): releaseWL(2be71e3f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(2c56f0d1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(2c56f0d1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  972): acquireWL(310a6736): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(310a6736): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(16a49637): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(2f62e7a4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): acquireWL(208dc0c2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): releaseWL(16a49637): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1854): Vacuum at: now=1457634623207 tag=VacuumService,
,D/PMS     (  972): releaseWL(2f62e7a4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(32b8da10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1854): Using platform SSLCertificateSocketFactory
,W/Uploader( 1854): No account for auth token provided,
,D/PMS     (  972): releaseWL(32b8da10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(2539873c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(2539873c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1854): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1854): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1854): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1854): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1854): [NET] android_getaddrinfo_proxy+
D/libc    ( 1854): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1854): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1854): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1854): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1854): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1854): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1854): No account for auth token provided,
,W/Uploader( 1854): No account for auth token provided,
,W/Uploader( 1854):  no longer exists, so no auth token.
,W/Uploader( 1854): No account for auth token provided,
,I/GLSUser ( 1854): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1854): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1854): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1854): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1854): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1854): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1854): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1854): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1854): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1854): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1854): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,W/Uploader( 1854): No account for auth token provided
,D/PMS     (  972): releaseWL(208dc0c2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(3adbde72): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(3adbde72): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  972): acquireWL(b90a2c3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(b90a2c3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1523): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3732304a
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  972): killProcessQuiet, pid=5698
I/ActivityManager(  972): Killing 5698:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5698
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  972): acquireWL(23fee740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(23fee740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  972): acquireWL(197e2679): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(197e2679): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  972): battery changed pluggedType: 2
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+,
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): << updateStatus,
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1356): wlan0: BSS: Remove id 11 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 1 BSSID 00:1f:27:54:70:c4 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c0 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 12 BSSID 00:1e:4a:8f:e3:6b SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 13 BSSID 00:1e:4a:8f:e3:6f SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 14 BSSID 00:1e:4a:8f:e3:60 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:dd:e2 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 5 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 6 BSSID 00:16:a6:1e:e0:a4 SSID '' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 15 BSSID 00:1e:4a:8f:df:db SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 16 BSSID 00:1e:4a:8f:df:df SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 17 BSSID 00:22:0d:46:1c:a2 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:70:c5 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 8 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 9 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 10 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 f0:f2:6d:22:99:3e]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 f0:f2:6d:22:99:3e
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c4]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c4
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:6b]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:6b
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:1e:4a:8f:e3:6f]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:1e:4a:8f:e3:6f
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 00:1e:4a:8f:e3:60]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 00:1e:4a:8f:e3:60
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:ef]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:ef
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e2]
,E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e2
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:16:a6:1f:06:5c]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:16:a6:1f:06:5c
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:16:a6:1e:e0:a4]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:16:a6:1e:e0:a4
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 00:1e:4a:8f:df:db]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 15 00:1e:4a:8f:df:db
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 16 00:1e:4a:8f:df:df]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 16 00:1e:4a:8f:df:df
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 17 00:22:0d:46:1c:a2]
,E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 17 00:22:0d:46:1c:a2
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:70:c5]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:70:c5
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:e3:63]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:e3:63
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:dd:e3]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:dd:e3
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:22:0d:46:1c:a3]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:22:0d:46:1c:a3
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  972): acquireWL(5056fbe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{62bcc91: PendingIntentRecord{22077f6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=228870, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{1a8b376c: PendingIntentRecord{1b1b135 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457634772583, Int=0
,D/WeatherUtility( 1221): Weather sync is On
,D/PMS     (  972): releaseWL(5056fbe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  972): acquireWL(20a4c9ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(20a4c9ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  972): Checking...
,D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  972): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1854): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1854): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1854): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1854): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 4 40
,W/GLSActivity( 1854): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1854): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1854): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1854): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1854): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1854): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1854): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5968): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5968): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5968): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5968): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5968): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5968): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5968): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5968): Ignoring header User-Agent because its value was null.
,D/libc    ( 5968): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5968): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5968): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 5968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5968): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5968): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5968): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  972): acquireWL(581539c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(581539c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
,D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  972): acquireWL(63251a5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(63251a5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): runPSCheck
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive+
,I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  972): acquireWL(2eb397a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2eb397a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1563): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1563): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1563): sku_id=118
,D/ContactMessageStore( 1563): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1563): start background delete task...
,D/ContactMessageStore( 1563): size: 0 , 0
,D/ContactMessageStore( 1563): Background delete complete
,D/PMS     (  972): acquireWL(1806d52b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(1806d52b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  972): plugged=true pluggin=true,
D/UsbnetService(  972): BroadcastReceiver::onReceive+,
D/WifiController(  972): battery changed pluggedType: 2
,D/UsbnetService(  972): onReceive BATTERY_CHANGED
,D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/HtcPowerSaver(  972): updateBatteryInfo
,D/PMS     (  972): runPSCheck
D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  972): << updateStatus
,D/PMS     (  972): acquireWL(1a1e0d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
,I/BatteryService(  972): n_update end
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): releaseWL(1a1e0d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/PowerUI ( 1221): closing low battery warning: level=100
,D/HtcPowerSaver(  972): updateBatteryInfo
D/PMS     (  972): runPSCheck
D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(61b6321): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{62bcc91: PendingIntentRecord{22077f6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=348871, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{3e637346: PendingIntentRecord{b9b9907 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941007, Int=0
I/bt-btm  ( 3106): Received oneshot timer event complete
,I/bt-btm  ( 3106): btm_ble_timeout
I/bt-btm  ( 3106): btm_gen_resolvable_private_addr
,D/PMS     (  972): acquireWL(3c4a7a34): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3106 1002 null
,D/bt-btm  ( 3106): btm_ble_rand_enc_complete,
I/bt-btm  ( 3106): btm_gen_resolve_paddr_low
D/bt-smp  ( 3106): smp_encrypt_data
W/bt-smp  ( 3106): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3106): Plain text(LSB ~ MSB) = 53 c2 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3106): Encrypted text(LSB ~ MSB) = 2f 71 98 e5 13 ef e5 8c 25 42 20 82 93 b5 82 bc 
I/bt-btm  ( 3106): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3106): Stopping oneshot timer
D/bt-btm  ( 3106): Starting oneshot timer type:103 timeout:900s
D/PMS     (  972): releaseWL(61b6321): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/art     (  972): Explicit concurrent mark sweep GC freed 36274(2010KB) AllocSpace objects, 8(804KB) LOS objects, 33% free, 16MB/24MB, paused 1.924ms total 202.236ms
,D/PMS     (  972): releaseWL(3c4a7a34): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  972): acquireWL(152a105d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(152a105d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
D/PMS     (  972): runPSCheck
D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive+
,D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState,
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(18d37dd2): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{1000}
,V/AlarmManager(  972): sending alarm PendingIntent{3e1ce384: PendingIntentRecord{3bb7476d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806106, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{62bcc91: PendingIntentRecord{22077f6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=948870, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{24cebea3: PendingIntentRecord{3f2f05a0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=934915, Int=0
,D/PMS     (  972): acquireWL(347c5559): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1854 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): releaseWL(347c5559): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  972): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6615 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  972): sending alarm PendingIntent{16c7a51e: PendingIntentRecord{1a84a1ff com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457635085433, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{3e0edbcc: PendingIntentRecord{a0c7a20 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457635397402, Int=0
,W/ContextImpl( 6441): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  972): releaseWL(18d37dd2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6441): MY_DEBUG = false,
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PowerUsageService( 6441): repeat time = 1457636297481
,D/PMS     (  972): acquireWL(38b5f1b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1854): Message class com.google.f.a.a.i
,D/PMS     (  972): releaseWL(38b5f1b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/StatusBarManagerService(  972): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
,D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
,D/FindExtension( 1622): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1622): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  972): Disable input method client, pid=6546
W/IInputConnectionWrapper( 6546): Do restartInputUnchecked, ic=null
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManager( 6546): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6546): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,I/PowerUsageList:PowerUsageHelper( 6441): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6441): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 6441): calcPower(), no data
,E/cutils-trace( 6638): Error opening trace file: Permission denied (13),
I/dex2oat ( 6638): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6638): dex2oat: override thread count:4
,I/dex2oat ( 6638): dex2oat took 736.027ms (threads: 4),
,I/PushClient( 6615): ApplicationMonitor {2032e98a}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6615): ApplicationMonitor {2032e98a}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6615): ApplicationMonitor {2032e98a}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6615): ApplicationMonitor {2032e98a}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6615): ApplicationMonitor {2032e98a}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6615): ApplicationMonitor {2032e98a}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
,I/PushClient( 6615): ApplicationMonitor {2032e98a}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6615): ApplicationMonitor {2032e98a}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6615): ApplicationMonitor {2032e98a}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6615): PnsModel {3da977f5}: update(): Update registration caused by: alarm,
,I/PushClient( 6615): PnsConfigModel {2ef21e30}: <init>(): Use dm-client for provisioning.
,W/System.err( 6615): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6615): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6615): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6615): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  972): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6645 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6645): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6645 dbg=false s=true
,I/DeviceManagement( 6645): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6645): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6645): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6645): WorkflowService: Starting workflow service
,I/DeviceManagement( 6645): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@177ee12c] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6645): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6645): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6645): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6645): SessionStateController: Checking invariants...
,I/DeviceManagement( 6645): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6645): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6645): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6645): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@177ee12c]
,I/DeviceManagement( 6645): WorkflowService: Stopping workflow service
,D/Process (  972): killProcessQuiet, pid=6244
I/ActivityManager(  972): Killing 6244:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6244
,I/PushClient( 6615): PnsModel {3da977f5}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  972): Killing 6314:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
D/Process (  972): killProcessQuiet, pid=6314
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6314
,D/PMS     (  972): acquireWL(39008ef): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{62bcc91: PendingIntentRecord{22077f6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1008870, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{3ee6cffc: PendingIntentRecord{348d8685 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457635444684, Int=0
,D/SmartSyncUtils( 6441): isEpsOn(), nState = 0
,D/PMS     (  972): acquireWL(f1cfcda): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6441 1000 null
,D/PMS     (  972): releaseWL(39008ef): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
D/SmartSyncScreenOnOffTimeReceiver( 6441): [updateNmRange] bManual = false
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6441): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6441): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6441): SettingOnTime = 1457676000000, randomSettingOnTime = 1457674649000
D/SmartSyncScreenOnOffTimeReceiver( 6441): SettingOffTime = 1457654400000, randomSettingOffTime = 1457661402000
,D/SmartSyncScreenOnOffTimeReceiver( 6441): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6441): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6441): bNightModeTurnOffOnce = false
,D/PMS     (  972): releaseWL(f1cfcda): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  972): acquireWL(2efe450b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2efe450b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
,D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(2cceefe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2cceefe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(16a50601): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(16a50601): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  972): updateBatteryInfo
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
,D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(11de0ca6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(11de0ca6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive-,
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  972): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: DeviceActiveState
D/PMS     (  972): runPSCheck
D/WifiController(  972): processMsg: StaEnabledState
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: X
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  972): User[0] Flushing usage stats to disk
,D/PMS     (  972): acquireWL(31ca26e7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(31ca26e7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  972): battery changed pluggedType: 2
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
,D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(8972294): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(8972294): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): runPSCheck
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/HeadsetStateMachine( 3106): Disconnected process message: 10, size: 0
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
