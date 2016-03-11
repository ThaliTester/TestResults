#### Test 62509094ffd3875_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/TelephonyReceiver( 1443): switchBindHtcMsgCursor: null
,E/cutils-trace( 6381): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6381): ====startRecUseTime====
D/htc.customization.log.level( 6381):  is 
W/CustomizationLogLevel( 6381): Level value is invalid, use default level 2
D/CustomizationManager( 6381):  Read ACC file spent 0.045 (s)
D/CIDMapFileReader( 6381): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6381): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6381): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6381): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6381): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6381): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6381): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6381): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6381): Parsing tag category name = system
I/CustomizationCIDLoader( 6381): Parsing tag category name = application
I/CustomizationCIDLoader( 6381): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6381): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6381): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6381): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6381): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6381): add string-array item, value = 42507
I/CustomizationCIDLoader( 6381): add string-array item, value = 21902
I/CustomizationCIDLoader( 6381): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6381): add string-array item, value = 23420
I/CustomizationCIDLoader( 6381): add string-array item, value = 22299
I/CustomizationCIDLoader( 6381): add string-array item, value = 24002
I/CustomizationCIDLoader( 6381): add string-array item, value = 23210
I/CustomizationCIDLoader( 6381): add string-array item, value = 23205
I/CustomizationCIDLoader( 6381): add string-array item, value = 23806
I/CustomizationCIDLoader( 6381): add string-array item, value = 23430
I/CustomizationCIDLoader( 6381): add string-array item, value = 23408
I/CustomizationCIDLoader( 6381): add string-array item, value = 27205
I/CustomizationCIDLoader( 6381): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6381): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6381):  Read CID file spent 0.094 (s)
D/CustomizationManager( 6381):  All configurations done spent 0.094 (s)
--------- beginning of system
I/ActivityManager(  948): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6381 on display 0
D/PMS     (  948): acquireHCC(f3078ec): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 948 1000 null
D/PMS     (  948): acquireHCC(2f0394b5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 948 1000 null
W/asset   (  948): Copying FileAsset 0x55ab37e530 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
I/ActivityManager(  948): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6399 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  948): Display changed displayId=0
D/DotMatrix( 1308): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1308): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6399): Copying FileAsset 0xac59e780 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1493): [trimMemory] 20
I/WebViewFactory( 6399): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6399): Time to load native libraries: 9 ms (timestamps 9232-9241),
,I/LibraryLoader( 6399): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6399): Binding Chromium to main looper Looper (main, tid 1) {26528cec},
I/LibraryLoader( 6399): Expected native library version number "",actual native library version number ""
,I/chromium( 6399): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6399): Initializing chromium process, singleProcess=true,
,W/art     ( 6399): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6399): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6399): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6399): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6399): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6399): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6399): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6399): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6399): Local Branch: 
I/Adreno-EGL( 6399): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6399): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
,I/Adreno-EGL( 6399):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  948): java.lang.Throwable: stack dump
W/System.err(  948): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  948): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  948): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  948): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  948): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c01d5a2:true
,D/BluetoothAdapter( 6399): 773528251: getState(). Returning 12
,W/art     ( 6399): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6399): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6399): CordovaWebView is running on device made by: HTC
,W/art     ( 6399): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6399): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6399): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/HtcSystemUPManager(  948): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  948): setSystemUiVisibility(0xc0000600)
D/StatusBarManagerService(  948): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  948): hiding MENU key
,D/StatusBarManagerService(  948): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  948): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  948): hiding MENU key
,D/FindExtension( 6399): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6399): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3930c7dd, mServedView=org.apache.cordova.engine.SystemWebView{28989f52 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@14f30223
,I/InputMethodManagerService(  948): Disable input method client, pid=1493
D/StatusBarManagerService(  948): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6399): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  948): Displayed com.test.thalitest/.MainActivity: +624ms (total +669ms)
,W/BindingManager( 6399): Cannot call determinedVisibility() - never saw a connection for the pid: 6399
,D/JsMessageQueue( 6399): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6399): JniHelper::setJavaVM(0xab4328f8), pthread_self() = -1401405568
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6399): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6399):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6399):     - Insecure RFCOMM socket port number: -1,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6399):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6399):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6399): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18fbd77 added. We now have 1 listener(s)
D/BluetoothManagerService(  948): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6399): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6399): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b8ba13 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6399): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  948): New client listening to asynchronous messages
,E/WifiTrafficPoller(  948): ADD_CLIENT: 9
,D/BluetoothAdapter( 6399): 773528251: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6399): setDiscoveryMode: Discovery mode BLE is supported
,D/BluetoothAdapter( 6399): 773528251: getState(). Returning 12
,I/chromium( 6399): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6399): Initializing JXcore engine
,W/jxcore-log( 6399): JXcore engine is ready
,W/jxcore-log( 6399): Starting JXcore engine
,W/jxcore-log( 6399): Platform android
W/jxcore-log( 6399): 
W/jxcore-log( 6399): Process ARCH arm
W/jxcore-log( 6399): 
,D/PMS     (  948): releaseHCC(f3078ec): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  948): releaseHCC(2f0394b5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6399): JXcore Cordova bridge is ready!
I/jxcore-log( 6399): 
W/jxcore-log( 6399): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6399): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 6399): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6399): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6399): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/Process (  948): killProcessQuiet, pid=6154
I/ActivityManager(  948): Killing 6154:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  948): Recipient 6154
,W/PluginManager( 6399): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 126ms. Plugin should use CordovaInterface.getThreadPool().,
,D/PMS     (  948): acquireWL(293092aa): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{10024}
V/AlarmManager(  948): sending alarm PendingIntent{2fda6e9b: PendingIntentRecord{14968238 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189580, Int=0
,V/AlarmManager(  948): sending alarm PendingIntent{f12b211: PendingIntentRecord{275d2f76 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=200748, Int=0
D/PMS     (  948): acquireWL(12675977): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(293092aa): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  948): acquireWL(3c4d89e4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  948): releaseWL(12675977): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  948): releaseWL(3c4d89e4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  948): acquireWL(2f56b74e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  948): releaseWL(2f56b74e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  948): acquireWL(281a006f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(281a006f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  948): acquireWL(40e317c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): acquireWL(f070a05): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  948): acquireWL(1af0348b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  948): releaseWL(40e317c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1864): Vacuum at: now=1457690876672 tag=VacuumService,
,I/GoogleURLConnFactory( 1864): Using platform SSLCertificateSocketFactory,
,D/PMS     (  948): releaseWL(f070a05): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  948): acquireWL(35f34181): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1864): No account for auth token provided
,D/PMS     (  948): releaseWL(35f34181): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): acquireWL(14e6226): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(14e6226): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1864): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1864): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1864): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1864): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1864): [NET] android_getaddrinfo_proxy+
D/libc    ( 1864): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  408): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  408): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  408): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  408): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1864): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1864): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1864): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1864): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1864): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1864): No account for auth token provided
,W/Uploader( 1864): No account for auth token provided
,W/Uploader( 1864): No account for auth token provided,
,W/Uploader( 1864): No account for auth token provided,
,W/Uploader( 1864):  no longer exists, so no auth token.
,W/Uploader( 1864): No account for auth token provided
,I/GLSUser ( 1864): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1864): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1864): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1864): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1864): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1864): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1864): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1864): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1864): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1864): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1864): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1864): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1864): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1864): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1864): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1864): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1864): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
,D/PMS     (  948): releaseWL(1af0348b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  948): acquireWL(1abb567b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(1abb567b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): acquireWL(143f7c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(143f7c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1586): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@24805e44
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
I/ActivityManager(  948): Killing 6178:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,D/Process (  948): killProcessQuiet, pid=6178
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 6178,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  948): acquireWL(2c8e8cf1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(2c8e8cf1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/NotificationService(  948): plugged=true pluggin=true,
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): processMsg: DeviceActiveState
,D/WifiController(  948): processMsg: StaEnabledState
D/HtcPowerSaver(  948): updateBatteryInfo
,D/WifiController(  948): processMsg: DefaultState,
,D/PMS     (  948): runPSCheck
D/WifiController(  948): handleMessage: X
D/HtcPowerSaver(  948): Checking...
,D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  948): >> updateStatus
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  948): battery changed pluggedType: 2
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1336): wlan0: BSS: Remove id 7 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 6 BSSID 00:1e:4a:8f:e3:6f SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 5 BSSID 00:1e:4a:8f:e3:6b SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 1 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 13 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 14 BSSID 00:1f:27:54:dd:e2 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 9 BSSID 00:22:0d:46:1c:a4 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 8 BSSID 00:22:0d:46:1c:a0 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 10 BSSID 00:16:a6:1e:e0:a4 SSID '' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 11 BSSID 00:1e:4a:8f:df:d2 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 3 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 12 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1336): wlan0: BSS: Remove id 15 BSSID 00:12:0e:f8:c9:a1 SSID 'DELL S320wi INTERACTIVE' due to wpa_bss_flush_by_age
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 f0:f2:6d:22:99:3e]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 f0:f2:6d:22:99:3e
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1e:4a:8f:e3:6f]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1e:4a:8f:e3:6f
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1e:4a:8f:e3:6b]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1e:4a:8f:e3:6b
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0,
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:dd:ef]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:dd:ef
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 00:1f:27:54:dd:e2]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 00:1f:27:54:dd:e2
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:22:0d:46:1c:a4]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:22:0d:46:1c:a4
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:22:0d:46:1c:a0]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:22:0d:46:1c:a0
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:16:a6:1e:e0:a4]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:16:a6:1e:e0:a4
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:1e:4a:8f:df:d2]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:1e:4a:8f:df:d2
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1e:4a:8f:e3:63]
,E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1e:4a:8f:e3:63
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e3]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e3
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:22:0d:46:1c:a3]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:22:0d:46:1c:a3
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 00:12:0e:f8:c9:a1]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 15 00:12:0e:f8:c9:a1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PMS     (  948): acquireWL(1b09a0d6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/BatteryService(  948): n_update end
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  948): releaseWL(1b09a0d6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1215): closing low battery warning: level=100
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/PMS     (  948): runPSCheck
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  948): Checking...
D/UsbnetService(  948): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  948): handleMessage: X
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1864): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1864): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1864): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1864): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1864): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/GLSActivity( 1864): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1864): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1864): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1864): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1864): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1864): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1864): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1215): reapply : com.google.android.gms 4 40
,E/PlayEventLogger( 5514): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5514): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5514): Ignoring header User-Agent because its value was null.
,D/libc    ( 5514): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5514): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5514): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5514): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5514): [NET] android_getaddrinfo_proxy+
D/libc    ( 5514): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  408): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  408): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  408): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  408): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5514): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/PMS     (  948): acquireWL(23573bc8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000},
V/AlarmManager(  948): sending alarm PendingIntent{3be4c6ed: PendingIntentRecord{3d531922 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=204348, Int=0
,V/AlarmManager(  948): sending alarm PendingIntent{3129eb86: PendingIntentRecord{24404c47 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457691019482, Int=0
,V/AlarmManager(  948): sending alarm PendingIntent{c884c74: PendingIntentRecord{330c159d com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457691053128, Int=1800000
,D/PMS     (  948): acquireWL(3f293a12): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2195 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
D/PMS     (  948): releaseWL(23573bc8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,D/PMS     (  948): acquireWL(2c17bbe0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2195 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(3f293a12): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 2195): Aggregate from 1457690715300 (log), 1457689253069 (data),
,D/PMS     (  948): releaseWL(2c17bbe0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  948): acquireWL(316cb60c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(316cb60c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  948): updateBatteryInfo
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  948): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  948): runPSCheck
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  948): Checking...
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  948): >> updateStatus
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/WifiController(  948): battery changed pluggedType: 2
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  948): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  948): handleMessage: E msg.what=155652
I/HtcPowerSaver(  948): << updateStatus
D/WifiController(  948): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  948): acquireWL(4095b55): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(4095b55): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  948): battery changed pluggedType: 2
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  948): updateBatteryInfo
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  948): runPSCheck
D/WifiController(  948): handleMessage: E msg.what=155652
D/HtcPowerSaver(  948): Checking...
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  948): >> updateStatus
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
,I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  948): acquireWL(a8df96a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000}
,V/AlarmManager(  948): sending alarm PendingIntent{3be4c6ed: PendingIntentRecord{3d531922 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=384348, Int=0
,I/ActivityManager(  948): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6468 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  948): sending alarm PendingIntent{126dae5b: PendingIntentRecord{393526f8 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457691160966, Int=0
,D/PMS     (  948): releaseWL(a8df96a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On,
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/StatusBarManagerService(  948): setSystemUiVisibility(0x8700)
,D/StatusBarManagerService(  948): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  948): hiding MENU key
,D/StatusBarManagerService(  948): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  948): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  948): hiding MENU key
,D/FindExtension( 1493): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1493): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  948): Disable input method client, pid=6399,
D/StatusBarManagerService(  948): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
W/IInputConnectionWrapper( 6399): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6399): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6399): reportFullscreenMode on inactive InputConnection
,E/cutils-trace( 6490): Error opening trace file: Permission denied (13),
I/dex2oat ( 6490): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6490): dex2oat: override thread count:4
,I/dex2oat ( 6490): dex2oat took 717.272ms (threads: 4),
,I/PushClient( 6468): ApplicationMonitor {2b648b31}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6468): ApplicationMonitor {2b648b31}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6468): ApplicationMonitor {2b648b31}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6468): ApplicationMonitor {2b648b31}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6468): ApplicationMonitor {2b648b31}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk,
,I/PushClient( 6468): ApplicationMonitor {2b648b31}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6468): ApplicationMonitor {2b648b31}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6468): ApplicationMonitor {2b648b31}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6468): ApplicationMonitor {2b648b31}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/PushClient( 6468): PnsModel {b518bd8}: update(): Update registration caused by: alarm,
,I/PushClient( 6468): PnsConfigModel {3d20f28f}: <init>(): Use dm-client for provisioning.
,W/System.err( 6468): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6468): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6468): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6468): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  948): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6497 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6497): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6497 dbg=false s=true
,I/DeviceManagement( 6497): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6497): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6497): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6497): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6497): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@b518bd8] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6497): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6497): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6497): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6497): SessionStateController: Checking invariants...
,I/DeviceManagement( 6497): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 6497): SessionStateController: Checking invariants...
,I/DeviceManagement( 6497): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6497): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@b518bd8]
,I/DeviceManagement( 6497): WorkflowService: Stopping workflow service
,I/ActivityManager(  948): Killing 4596:com.android.settings/1000 (adj 15): empty #17,
,D/Process (  948): killProcessQuiet, pid=4596
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 4596,
,I/PushClient( 6468): PnsModel {b518bd8}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  948): killProcessQuiet, pid=5140
,I/ActivityManager(  948): Killing 5140:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5140
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  948): acquireWL(1958c3c5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(1958c3c5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1215): closing low battery warning: level=100
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/PMS     (  948): runPSCheck
D/WifiController(  948): handleMessage: E msg.what=155652
D/HtcPowerSaver(  948): Checking...,
D/WifiController(  948): processMsg: DeviceActiveState
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: DefaultState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): handleMessage: X
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  948): << updateStatus
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1443): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1443): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1443): sku_id=118
D/ContactMessageStore( 1443): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1443): start background delete task...
,D/ContactMessageStore( 1443): size: 0 , 0
,D/ContactMessageStore( 1443): Background delete complete
,D/PMS     (  948): acquireWL(5cf911a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
,I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(5cf911a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/PMS     (  948): runPSCheck,
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  948): Checking...
D/UsbnetService(  948): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): handleMessage: E msg.what=155652
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: StaEnabledState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): processMsg: DefaultState
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  948): handleMessage: X
,I/HtcPowerSaver(  948): << updateStatus
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  948): acquireWL(bb2e44b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000}
V/AlarmManager(  948): sending alarm PendingIntent{3be4c6ed: PendingIntentRecord{3d531922 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=504349, Int=0
,V/AlarmManager(  948): sending alarm PendingIntent{19bc3e28: PendingIntentRecord{b06d741 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=943988, Int=0,
I/bt-btm  ( 3382): Received oneshot timer event complete
I/bt-btm  ( 3382): btm_ble_timeout
I/bt-btm  ( 3382): btm_gen_resolvable_private_addr
,D/PMS     (  948): acquireWL(4c5a4e6): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3382 1002 null
D/PMS     (  948): releaseWL(bb2e44b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/bt-btm  ( 3382): btm_ble_rand_enc_complete,
I/bt-btm  ( 3382): btm_gen_resolve_paddr_low
D/bt-smp  ( 3382): smp_encrypt_data
W/bt-smp  ( 3382): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3382): Plain text(LSB ~ MSB) = 7b 2b 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3382): Encrypted text(LSB ~ MSB) = 16 c1 fd 2c b1 20 17 0c 5b 1d 17 1b aa 06 87 ff 
I/bt-btm  ( 3382): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3382): Stopping oneshot timer
D/bt-btm  ( 3382): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  948): releaseWL(4c5a4e6): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  948): acquireWL(30497a27): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(30497a27): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  948): updateBatteryInfo
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  948): runPSCheck
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  948): Checking...
I/HtcPowerSaver(  948): >> updateStatus
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
,D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  948): onReceive BATTERY_CHANGED
,I/HtcPowerSaver(  948): << updateStatus
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  948): handleMessage: E msg.what=155652
,D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: DeviceActiveState
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  948): acquireWL(13ab14d4): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{10024}
V/AlarmManager(  948): sending alarm PendingIntent{3028a67d: PendingIntentRecord{25b72972 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936058, Int=0
D/PMS     (  948): acquireWL(1dc991c3): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1864 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  948): sending alarm PendingIntent{545cd30: PendingIntentRecord{265d2da9 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804742, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{190eaa40: PendingIntentRecord{2d290d45 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457691641676, Int=0
D/PMS     (  948): releaseWL(1dc991c3): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  948): releaseWL(13ab14d4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6317): MY_DEBUG = false,
,D/PowerUsageService( 6317): repeat time = 1457692541709,
,D/PMS     (  948): acquireWL(29ca6abe): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1864 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1864): Message class com.google.f.a.a.i,
I/PowerUsageList:PowerUsageHelper( 6317): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PMS     (  948): releaseWL(29ca6abe): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PowerUsageList:BatterySipperExt( 6317): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 6317): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 6317): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  948): acquireWL(4a9871f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000},
D/SmartSyncUtils( 6317): isEpsOn(), nState = 0
V/AlarmManager(  948): sending alarm PendingIntent{3be4c6ed: PendingIntentRecord{3d531922 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=984349, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{4542a6c: PendingIntentRecord{384b2835 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457691693262, Int=0
,D/PMS     (  948): acquireWL(2c3e74ca): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6317 1000 null
,D/PMS     (  948): releaseWL(4a9871f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6317): [updateNmRange] bManual = false
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6317): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6317): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6317): SettingOnTime = 1457762400000, randomSettingOnTime = 1457760310000
,D/SmartSyncScreenOnOffTimeReceiver( 6317): SettingOffTime = 1457740800000, randomSettingOffTime = 1457740816000
,D/SmartSyncScreenOnOffTimeReceiver( 6317): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6317): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6317): bNightModeTurnOffOnce = false
,D/PMS     (  948): releaseWL(2c3e74ca): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  948): acquireWL(3c69763b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  948): n_update end
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/PMS     (  948): releaseWL(3c69763b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/WifiController(  948): battery changed pluggedType: 2
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  948): updateBatteryInfo
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  948): runPSCheck
D/WifiController(  948): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  948): Checking...
D/WifiController(  948): processMsg: DeviceActiveState
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): processMsg: StaEnabledState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): processMsg: DefaultState
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  948): handleMessage: X
I/HtcPowerSaver(  948): << updateStatus
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  948): acquireWL(78f8158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(78f8158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  948): updateBatteryInfo
,D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
,D/PowerUI ( 1215): closing low battery warning: level=100
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  948): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  948): runPSCheck
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  948): Checking...
D/UsbnetService(  948): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  948): >> updateStatus
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/WifiController(  948): battery changed pluggedType: 2
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  948): acquireWL(139312b1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(139312b1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  948): updateBatteryInfo
,D/UsbnetService(  948): onReceive BATTERY_CHANGED
,D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  948): runPSCheck
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  948): Checking...
D/WifiController(  948): handleMessage: E msg.what=155652
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: StaEnabledState
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  948): processMsg: DefaultState
I/HtcPowerSaver(  948): << updateStatus
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): handleMessage: X
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  948): acquireWL(b371396): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(b371396): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  948): updateBatteryInfo
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  948): plugged=true pluggin=true
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
D/PMS     (  948): runPSCheck
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  948): Checking...
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  948): >> updateStatus
D/UsbnetService(  948): onReceive BATTERY_CHANGED
,D/WifiController(  948): battery changed pluggedType: 2
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  948): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  948): << updateStatus
D/WifiController(  948): handleMessage: E msg.what=155652
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  948): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  948): User[0] Flushing usage stats to disk,
,D/PMS     (  948): acquireWL(a6f3b17): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(a6f3b17): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  948): updateBatteryInfo
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  948): plugged=true pluggin=true
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
D/PMS     (  948): runPSCheck
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  948): Checking...
D/UsbnetService(  948): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  948): >> updateStatus
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  948): battery changed pluggedType: 2
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
,I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  948): acquireWL(20275b04): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(20275b04): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  948): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/NotificationService(  948): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/PMS     (  948): runPSCheck
D/HtcPowerSaver(  948): Checking...
I/HtcPowerSaver(  948): >> updateStatus
,D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  948): acquireWL(179528ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(179528ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/WifiController(  948): battery changed pluggedType: 2
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  948): runPSCheck
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  948): Checking...
D/WifiController(  948): handleMessage: E msg.what=155652
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3382): Disconnected process message: 10, size: 0
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1215): closing low battery warning: level=100
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1400000ms)
```
