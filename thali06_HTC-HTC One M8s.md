#### Test 613623667b1a8f4_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
D/TelephonyReceiver( 1536): switchBindHtcMsgCursor: null
E/cutils-trace( 6611): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6611): ====startRecUseTime====
D/htc.customization.log.level( 6611):  is 
W/CustomizationLogLevel( 6611): Level value is invalid, use default level 2
D/CustomizationManager( 6611):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 6611): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6611): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6611): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6611): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6611): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6611): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6611): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6611): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6611): Parsing tag category name = system
I/CustomizationCIDLoader( 6611): Parsing tag category name = application
I/CustomizationCIDLoader( 6611): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6611): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6611): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6611): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6611): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6611): add string-array item, value = 42507
I/CustomizationCIDLoader( 6611): add string-array item, value = 21902
I/CustomizationCIDLoader( 6611): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6611): add string-array item, value = 23420
I/CustomizationCIDLoader( 6611): add string-array item, value = 22299
I/CustomizationCIDLoader( 6611): add string-array item, value = 24002
I/CustomizationCIDLoader( 6611): add string-array item, value = 23210
I/CustomizationCIDLoader( 6611): add string-array item, value = 23205
I/CustomizationCIDLoader( 6611): add string-array item, value = 23806
I/CustomizationCIDLoader( 6611): add string-array item, value = 23430
I/CustomizationCIDLoader( 6611): add string-array item, value = 23408
I/CustomizationCIDLoader( 6611): add string-array item, value = 27205
I/CustomizationCIDLoader( 6611): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6611): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6611):  Read CID file spent 0.108 (s)
D/CustomizationManager( 6611):  All configurations done spent 0.109 (s)
--------- beginning of system
I/ActivityManager(  945): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6611 on display 0
D/PMS     (  945): acquireHCC(35e18f7e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 945 1000 null
D/PMS     (  945): acquireHCC(2436acdf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 945 1000 null
I/ActivityManager(  945): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6629 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1332): [EventService]  onDisplayChanged: 0
V/ActivityManager(  945): Display changed displayId=0
D/DotMatrix( 1332): [EventService] mbHDMIConnect: false, mCoverOn:false
W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
I/TrimMemoryManager( 1587): [trimMemory] 20
I/WebViewFactory( 6629): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6629): Time to load native libraries: 9 ms (timestamps 9088-9097),
,I/LibraryLoader( 6629): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6629): Binding Chromium to main looper Looper (main, tid 1) {20beb217},
I/LibraryLoader( 6629): Expected native library version number "",actual native library version number ""
,I/chromium( 6629): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6629): Initializing chromium process, singleProcess=true,
,W/art     ( 6629): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6629): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6629): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6629): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6629): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6629): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6629): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6629): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6629): Local Branch: 
I/Adreno-EGL( 6629): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6629): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6629):                  d74aa161a12b9c6fc6332151
,W/System.err(  945): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  945): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  945): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  945): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  945): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  945): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  945): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d0885c4:true
,D/BluetoothAdapter( 6629): 232519202: getState(). Returning 12
,W/art     ( 6629): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6629): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6629): CordovaWebView is running on device made by: HTC
,W/art     ( 6629): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6629): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  945): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6629): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  945): setSystemUiVisibility(0xc0000600)
,D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  945): hiding MENU key
,D/StatusBarManagerService(  945): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  945): hiding MENU key
,D/FindExtension( 6629): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6629): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2f6819cc, mServedView=org.apache.cordova.engine.SystemWebView{26f75415 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@102b632a
,I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
I/InputMethodManagerService(  945): Disable input method client, pid=1587
,D/StatusBarManagerService(  945): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6629): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  945): Displayed com.test.thalitest/.MainActivity: +632ms (total +678ms)
,W/BindingManager( 6629): Cannot call determinedVisibility() - never saw a connection for the pid: 6629
,D/JsMessageQueue( 6629): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6629): JniHelper::setJavaVM(0xab24a8f8), pthread_self() = -1403483992
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6629): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6629):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6629):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6629):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6629):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6629): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f09fce added. We now have 1 listener(s)
,D/BluetoothManagerService(  945): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629): setBluetoothMacAddress: 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6629): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6629): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7aeada added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6629): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  945): New client listening to asynchronous messages
E/WifiTrafficPoller(  945): ADD_CLIENT: 8
,D/BluetoothAdapter( 6629): 232519202: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6629): setDiscoveryMode: Discovery mode BLE is supported,
,D/BluetoothAdapter( 6629): 232519202: getState(). Returning 12
,I/chromium( 6629): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6629): Initializing JXcore engine,
W/jxcore-log( 6629): JXcore engine is ready
,W/jxcore-log( 6629): Starting JXcore engine
,W/jxcore-log( 6629): Platform android
W/jxcore-log( 6629): 
,W/jxcore-log( 6629): Process ARCH arm
W/jxcore-log( 6629): 
,D/PMS     (  945): releaseHCC(35e18f7e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  945): releaseHCC(2436acdf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6629): JXcore Cordova bridge is ready!,
I/jxcore-log( 6629): 
W/jxcore-log( 6629): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6629): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 6629): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6629): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6629): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,D/Process (  945): killProcessQuiet, pid=6310
I/ActivityManager(  945): Killing 6310:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  945): Recipient 6310
,W/PluginManager( 6629): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 230ms. Plugin should use CordovaInterface.getThreadPool().
,D/PMS     (  945): acquireWL(3727418c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000},
V/AlarmManager(  945): sending alarm PendingIntent{2b7c3b7b: PendingIntentRecord{1a26fd98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=188259, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{2ff7c0d5: PendingIntentRecord{22fc30ea android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=193712, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{3b444fdb: PendingIntentRecord{2accea78 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189414, Int=0
,D/PMS     (  945): acquireWL(39809551): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(3727418c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/PMS     (  945): acquireWL(36e471b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  945): releaseWL(39809551): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  945): releaseWL(36e471b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(35e9090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(35e9090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  945): Explicit concurrent mark sweep GC freed 39881(2MB) AllocSpace objects, 6(624KB) LOS objects, 33% free, 16MB/25MB, paused 2.319ms total 245.224ms
D/PMS     (  945): acquireWL(1eaf9d89): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(1eaf9d89): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): acquireWL(33bc018e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(115a1daf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(e6b8945): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(33bc018e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1954): Vacuum at: now=1457623565992 tag=VacuumService
,D/PMS     (  945): releaseWL(115a1daf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  945): acquireWL(1634e5cb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1954): Using platform SSLCertificateSocketFactory
,W/Uploader( 1954): No account for auth token provided
,D/PMS     (  945): releaseWL(1634e5cb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(2aaa13a7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(2aaa13a7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1954): [NET] android_getaddrinfo_proxy+
D/libc    ( 1954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1954): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1954): No account for auth token provided
,W/Uploader( 1954): No account for auth token provided
,W/Uploader( 1954): No account for auth token provided,
,W/Uploader( 1954):  no longer exists, so no auth token.,
,W/Uploader( 1954): No account for auth token provided
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1217): reapply : com.google.android.gms 3 40
E/Uploader( 1954): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1954): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1954): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1954): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1954): No account for auth token provided
,D/PMS     (  945): releaseWL(e6b8945): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(385a4db5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(385a4db5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(111e6c4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(111e6c4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1643): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2fec1d2e,
I/ActivityManager(  945): Killing 5389:com.htc.mediamanager/u0a28 (adj 15): empty #17
,D/Process (  945): killProcessQuiet, pid=5389
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 5389,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  945): acquireWL(1a2ed7bb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(1a2ed7bb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): closing low battery warning: level=100
,D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  945): plugged=true pluggin=true
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/WifiController(  945): handleMessage: E msg.what=155652
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  945): updateBatteryInfo
D/PMS     (  945): runPSCheck
D/HtcPowerSaver(  945): Checking...
I/HtcPowerSaver(  945): >> updateStatus
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1338): wlan0: BSS: Remove id 11 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 f0:f2:6d:22:99:3e]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 f0:f2:6d:22:99:3e
,D/PMS     (  945): acquireWL(14f04d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null,
I/BatteryService(  945): n_update end
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PMS     (  945): releaseWL(14f04d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/NotificationService(  945): plugged=true pluggin=true
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
D/PMS     (  945): runPSCheck
D/WifiController(  945): handleMessage: E msg.what=155652
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): processMsg: DeviceActiveState
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: DefaultState
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  945): handleMessage: X
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  945): << updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1338): wlan0: BSS: Remove id 13 BSSID 00:1e:4a:8f:e3:6f SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 12 BSSID 00:1e:4a:8f:e3:6b SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 14 BSSID 00:1e:4a:8f:e3:60 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 15 BSSID 00:1e:4a:8f:e3:64 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 16 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 1 BSSID 00:1f:27:54:70:c4 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c6 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:dd:e0 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 5 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 4 BSSID 00:22:0d:46:1c:a4 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 6 BSSID 00:1f:27:54:70:c2 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 7 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 8 BSSID 00:1f:27:54:70:c5 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:1e:4a:8f:e3:6f]
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 9 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:1e:4a:8f:e3:6f
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:6b]
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 10 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:6b
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 00:1e:4a:8f:e3:60]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 00:1e:4a:8f:e3:60
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 00:1e:4a:8f:e3:64]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 15 00:1e:4a:8f:e3:64
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 16 00:1f:27:54:dd:ef]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 16 00:1f:27:54:dd:ef
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c4]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c4
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c6]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c6
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:e0]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:e0
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:16:a6:1f:06:5c]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:16:a6:1f:06:5c
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:22:0d:46:1c:a4]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:22:0d:46:1c:a4
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:70:c2]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:70:c2
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1e:4a:8f:e3:63]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1e:4a:8f:e3:63
D/WifiMonitor(  945): Event [IFNAME=wlan0 ,CTRL-EVENT-BSS-REMOVED 8 00:1f:27:54:70:c5]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:1f:27:54:70:c5
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:dd:e3]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:dd:e3
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:22:0d:46:1c:a3]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:22:0d:46:1c:a3
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1217): reapply : com.google.android.gms 2 40
,W/GLSActivity( 1954): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1954): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1954): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1954): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1954): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1954): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1954): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5935): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5935): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5935): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5935): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5935): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5935): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5935): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5935): Ignoring header User-Agent because its value was null.,
D/libc    ( 5935): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5935): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5935): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 5935): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5935): [NET] android_getaddrinfo_proxy+
D/libc    ( 5935): [NET] android_getaddrinfo_proxy get netid:0,
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5935): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  945): acquireWL(38527bfa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000},
V/AlarmManager(  945): sending alarm PendingIntent{2b7c3b7b: PendingIntentRecord{1a26fd98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=248260, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{34795408: PendingIntentRecord{157367a1 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457623728664, Int=0
,I/ActivityManager(  945): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6695 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  945): sending alarm PendingIntent{133c5dc6: PendingIntentRecord{226a7187 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457623754095, Int=0
,D/PMS     (  945): releaseWL(38527bfa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1217): Weather sync is On
,W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/StatusBarManagerService(  945): setSystemUiVisibility(0x8700)
,D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  945): hiding MENU key
D/StatusBarManagerService(  945): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  945): hiding MENU key
,D/FindExtension( 1587): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1587): Defer allocateBuffers to drawing time,
,I/InputMethodManagerService(  945): Disable input method client, pid=6629
W/IInputConnectionWrapper( 6629): Do restartInputUnchecked, ic=null
,D/StatusBarManagerService(  945): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManager( 6629): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213),
W/IInputConnectionWrapper( 6629): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
,E/cutils-trace( 6717): Error opening trace file: Permission denied (13),
I/dex2oat ( 6717): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6717): dex2oat: override thread count:4
,I/dex2oat ( 6717): dex2oat took 719.319ms (threads: 4)
,I/PushClient( 6695): ApplicationMonitor {1aa87e70}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6695): ApplicationMonitor {1aa87e70}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6695): ApplicationMonitor {1aa87e70}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6695): ApplicationMonitor {1aa87e70}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6695): ApplicationMonitor {1aa87e70}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6695): ApplicationMonitor {1aa87e70}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6695): ApplicationMonitor {1aa87e70}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6695): ApplicationMonitor {1aa87e70}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6695): ApplicationMonitor {1aa87e70}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6695): PnsModel {2bf258b3}: update(): Update registration caused by: alarm
,I/PushClient( 6695): PnsConfigModel {27b34146}: <init>(): Use dm-client for provisioning.
,W/System.err( 6695): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6695): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6695): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6695): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  945): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6724 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6724): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6724 dbg=false s=true,
,I/DeviceManagement( 6724): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6724): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6724): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
I/DeviceManagement( 6724): WorkflowService: Starting workflow service
,I/DeviceManagement( 6724): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1aa87e70] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6724): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6724): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6724): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6724): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6724): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6724): SessionStateController: Checking invariants...
,I/DeviceManagement( 6724): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6724): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1aa87e70],
,I/DeviceManagement( 6724): WorkflowService: Stopping workflow service,
,D/Process (  945): killProcessQuiet, pid=6430,
I/ActivityManager(  945): Killing 6430:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6695): PnsModel {2bf258b3}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  945): Recipient 6430
,D/Process (  945): killProcessQuiet, pid=6385,
I/ActivityManager(  945): Killing 6385:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6385
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  945): acquireWL(202dcf38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(202dcf38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  945): updateBatteryInfo,
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/PMS     (  945): runPSCheck
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): handleMessage: E msg.what=155652
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: DeviceActiveState
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  945): acquireWL(25f47b11): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(25f47b11): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  945): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  945): plugged=true pluggin=true
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  945): runPSCheck
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  945): >> updateStatus
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  945): battery changed pluggedType: 2
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): handleMessage: E msg.what=155652
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  945): processMsg: DeviceActiveState
I/HtcPowerSaver(  945): << updateStatus
,D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1536): MSG_CHECK_DELETION >>,
D/ContactMessageStore( 1536): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1536): sku_id=118
D/ContactMessageStore( 1536): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1536): start background delete task...
,D/ContactMessageStore( 1536): size: 0 , 0
,D/ContactMessageStore( 1536): Background delete complete
,D/PMS     (  945): acquireWL(26bdc476): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/BatteryService(  945): n_update end
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  945): releaseWL(26bdc476): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): handleMessage: E msg.what=155652
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/HtcPowerSaver(  945): updateBatteryInfo
D/PMS     (  945): runPSCheck
D/HtcPowerSaver(  945): Checking...
I/HtcPowerSaver(  945): >> updateStatus
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,D/PMS     (  945): acquireWL(39ecca77): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
D/UsbnetService(  945): BroadcastReceiver::onReceive+
I/BatteryService(  945): n_update end
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/PMS     (  945): releaseWL(39ecca77): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  945): BroadcastReceiver::onReceive-
,D/NotificationService(  945): plugged=true pluggin=true
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  945): battery changed pluggedType: 2
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  945): updateBatteryInfo
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  945): runPSCheck
D/WifiController(  945): handleMessage: E msg.what=155652
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): processMsg: DeviceActiveState
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: StaEnabledState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  945): acquireWL(1e8ca6e4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(1e8ca6e4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  945): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  945): >> updateStatus
,D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  945): handleMessage: E msg.what=155652
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: DeviceActiveState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  945): handleMessage: X
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  945): acquireWL(1514b74d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PMS     (  945): releaseWL(1514b74d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/WifiController(  945): battery changed pluggedType: 2
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  945): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  945): runPSCheck
D/WifiController(  945): handleMessage: E msg.what=155652
D/HtcPowerSaver(  945): Checking...
,D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): closing low battery warning: level=100
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  945): acquireWL(1c39b202): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
I/bt-btm  ( 3074): Received oneshot timer event complete
V/AlarmManager(  945): sending alarm PendingIntent{2b7c3b7b: PendingIntentRecord{1a26fd98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=428259, Int=0
I/bt-btm  ( 3074): btm_ble_timeout
V/AlarmManager(  945): sending alarm PendingIntent{8599713: PendingIntentRecord{5df4d50 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=939916, Int=0
I/bt-btm  ( 3074): btm_gen_resolvable_private_addr
D/PMS     (  945): acquireWL(25827b49): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3074 1002 null
,D/bt-btm  ( 3074): btm_ble_rand_enc_complete,
I/bt-btm  ( 3074): btm_gen_resolve_paddr_low
D/bt-smp  ( 3074): smp_encrypt_data,
W/bt-smp  ( 3074): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3074): Plain text(LSB ~ MSB) = 55 ab 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3074): Encrypted text(LSB ~ MSB) = 83 86 1c e0 41 55 1b 98 1b 9d 00 0b b9 bf e2 2d 
I/bt-btm  ( 3074): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3074): Stopping oneshot timer
D/bt-btm  ( 3074): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  945): releaseWL(1c39b202): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1217): Weather sync is On,
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/PMS     (  945): releaseWL(25827b49): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  945): acquireWL(1d94ec4e): PARTIAL_WAKE_LOCK  *alarm* 0x1 945 1000 WorkSource{10024}
V/AlarmManager(  945): sending alarm PendingIntent{abc916f: PendingIntentRecord{3173ee7c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936286, Int=0
,D/PMS     (  945): acquireWL(10ee8305): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  945): sending alarm PendingIntent{3cdfcf5: PendingIntentRecord{3c458a8a android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804212, Int=0
D/PMS     (  945): releaseWL(10ee8305): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  945): sending alarm PendingIntent{3c577f5a: PendingIntentRecord{2593aa60 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457624337794, Int=0
,W/ContextImpl( 6524): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  945): releaseWL(1d94ec4e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
D/PowerUsageList:PowerUsageHelper( 6524): MY_DEBUG = false
,D/PowerUsageService( 6524): repeat time = 1457625237832,
,D/PMS     (  945): acquireWL(14f7668): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1954): Message class com.google.f.a.a.i
,D/PMS     (  945): releaseWL(14f7668): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6524): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6524): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 6524): calcPower(), no data
,D/PMS     (  945): acquireWL(1594a81): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{2b7c3b7b: PendingIntentRecord{1a26fd98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=968259, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{287e3726: PendingIntentRecord{3fef3f67 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457624383734, Int=0
,D/SmartSyncUtils( 6524): isEpsOn(), nState = 0,
,D/PMS     (  945): releaseWL(1594a81): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On,
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
D/PMS     (  945): acquireWL(ed99114): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6524 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6524): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6524): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6524): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6524): SettingOnTime = 1457676000000, randomSettingOnTime = 1457674642000
D/SmartSyncScreenOnOffTimeReceiver( 6524): SettingOffTime = 1457654400000, randomSettingOffTime = 1457654756000
,D/SmartSyncScreenOnOffTimeReceiver( 6524): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6524): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6524): bNightModeTurnOffOnce = false
,D/PMS     (  945): releaseWL(ed99114): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  945): acquireWL(264f0dbd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null,
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(264f0dbd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  945): BroadcastReceiver::onReceive+,
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/WifiController(  945): battery changed pluggedType: 2
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  945): updateBatteryInfo
D/WifiController(  945): handleMessage: E msg.what=155652
,D/PMS     (  945): runPSCheck
D/WifiController(  945): processMsg: DeviceActiveState
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): processMsg: StaEnabledState
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0,
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  945): acquireWL(3069fb2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(3069fb2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  945): updateBatteryInfo
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/PMS     (  945): runPSCheck
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): handleMessage: E msg.what=155652
D/PowerUI ( 1217): closing low battery warning: level=100
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
D/WifiController(  945): battery changed pluggedType: 2
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  945): << updateStatus
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  945): acquireWL(4266b03): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(4266b03): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  945): updateBatteryInfo
D/HeadsetPhoneState( 3074): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/NotificationService(  945): plugged=true pluggin=true
D/HeadsetStateMachine( 3074): Disconnected process message: 11, size: 0
D/PowerUI ( 1217): closing low battery warning: level=98
D/DotMatrix( 1332): [EventService] reorderNotification, total:1
D/PMS     (  945): runPSCheck
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  945): Checking...
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  945): >> updateStatus
,D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/WifiController(  945): battery changed pluggedType: 2
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  945): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  945): updateStatus (8000,98,-1,false,false,false,-1)
D/WifiController(  945): handleMessage: E msg.what=155652
I/HtcPowerSaver(  945): << updateStatus
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
,W/ContextImpl( 6524): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5911): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5911): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5911): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5911): Cust_ConnectToPC   : spcsc>false
D/        ( 5911): Cust_ConnectToPC   : IPT>true
D/        ( 5911): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 5911): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5911): Index of the first 1 = -1
,W/ContextImpl( 5911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 ,
,W/Settings( 5911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/BatteryController( 1217): status:2 level:98 unsupport:false plugged:true
,E/SmartNS_Utility( 5911): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 5911): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5911): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5911): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5911): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/PMS     (  945): acquireWL(21e3c8b9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null,
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(21e3c8b9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  945): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): closing low battery warning: level=98
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): handleMessage: E msg.what=155652
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: StaEnabledState
I/HtcPowerSaver(  945): updateStatus (8000,98,-1,false,false,false,-1)
D/WifiController(  945): processMsg: DefaultState
I/HtcPowerSaver(  945): << updateStatus
D/WifiController(  945): handleMessage: X
,I/BatteryController( 1217): status:2 level:98 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  945): User[0] Flushing usage stats to disk
,D/PMS     (  945): acquireWL(d3b04fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/BatteryService(  945): n_update end
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  945): releaseWL(d3b04fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PowerUI ( 1217): closing low battery warning: level=99
D/UsbnetService(  945): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/PMS     (  945): runPSCheck
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): handleMessage: E msg.what=155652
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: StaEnabledState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
I/HtcPowerSaver(  945): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1217): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  945): acquireWL(381ab45f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(381ab45f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  945): updateBatteryInfo
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): handleMessage: E msg.what=155652
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: DeviceActiveState
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: DefaultState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): handleMessage: X
D/HeadsetStateMachine( 3074): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3074): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3074): Disconnected process message: 11, size: 0
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  945): << updateStatus
D/DotMatrix( 1332): [EventService] reorderNotification, total:0
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
W/ContextImpl( 6524): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/TetherSettings( 5911): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5911): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5911): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5911): Cust_ConnectToPC   : spcsc>false
D/        ( 5911): Cust_ConnectToPC   : IPT>true
D/        ( 5911): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5911): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5911): Index of the first 1 = -1
W/ContextImpl( 5911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
W/ContextImpl( 5911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
W/Settings( 5911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5911): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5911): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5911): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1400000ms)
```
