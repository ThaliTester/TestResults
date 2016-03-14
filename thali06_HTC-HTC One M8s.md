#### Test 625090943f585e4_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
,D/PMS     (  971): acquireWL(27cb826a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{123e06bf: PendingIntentRecord{2131418c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=146287, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{3b5f035b: PendingIntentRecord{2ddc57f8 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457972359533, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{2b6f34d1: PendingIntentRecord{b175b36 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202824, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{18807a37: PendingIntentRecord{117afba4 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=188727, Int=0
D/PMS     (  971): acquireWL(2ee14d0d): PARTIAL_WAKE_LOCK  *backup* 0x1 971 1000 null
D/PMS     (  971): acquireWL(75f4c2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
W/BackupManagerService(  971): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  971): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  971): releaseWL(2ee14d0d): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  971): releaseWL(27cb826a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  971): acquireWL(32d882d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(75f4c2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
V/GLSActivity( 1916): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  971): releaseWL(32d882d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(218010c5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(218010c5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(6015a1a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(6015a1a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(223794b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(1311af28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(30cafde6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(223794b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/VacuumService( 1916): Vacuum at: now=1457972396771 tag=VacuumService
I/GoogleURLConnFactory( 1916): Using platform SSLCertificateSocketFactory
D/PMS     (  971): releaseWL(1311af28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(2b6695d4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
W/Uploader( 1916): No account for auth token provided
E/cutils-trace( 6517): Error opening trace file: Permission denied (13)
D/PMS     (  971): releaseWL(2b6695d4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(37813b40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(37813b40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 1916): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1916): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1916): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1916): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1916): [NET] android_getaddrinfo_proxy+
D/libc    ( 1916): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1916): [NET] android_getaddrinfo_proxy-, success
D/CustomizationManager( 6517): ====startRecUseTime====
D/htc.customization.log.level( 6517):  is 
W/CustomizationLogLevel( 6517): Level value is invalid, use default level 2
D/CustomizationManager( 6517):  Read ACC file spent 0.045 (s)
D/CIDMapFileReader( 6517): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6517): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6517): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6517): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6517): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6517): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6517): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6517): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6517): Parsing tag category name = system
I/CustomizationCIDLoader( 6517): Parsing tag category name = application
I/CustomizationCIDLoader( 6517): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6517): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6517): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6517): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6517): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6517): add string-array item, value = 42507
I/CustomizationCIDLoader( 6517): add string-array item, value = 21902
I/CustomizationCIDLoader( 6517): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6517): add string-array item, value = 23420
I/CustomizationCIDLoader( 6517): add string-array item, value = 22299
I/CustomizationCIDLoader( 6517): add string-array item, value = 24002
I/CustomizationCIDLoader( 6517): add string-array item, value = 23210
I/CustomizationCIDLoader( 6517): add string-array item, value = 23205
I/CustomizationCIDLoader( 6517): add string-array item, value = 23806
I/CustomizationCIDLoader( 6517): add string-array item, value = 23430
I/CustomizationCIDLoader( 6517): add string-array item, value = 23408
I/CustomizationCIDLoader( 6517): add string-array item, value = 27205
I/CustomizationCIDLoader( 6517): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6517): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6517):  Read CID file spent 0.097 (s)
D/CustomizationManager( 6517):  All configurations done spent 0.097 (s)
I/ActivityManager(  971): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6517 on display 0
D/PMS     (  971): acquireHCC(1593ea79): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 971 1000 null
D/PMS     (  971): acquireHCC(1401e3be): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 971 1000 null
W/asset   (  971): Copying FileAsset 0x55a1252ad0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  971): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6540 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1305): [EventService]  onDisplayChanged: 0
V/ActivityManager(  971): Display changed displayId=0
D/DotMatrix( 1305): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6540): Copying FileAsset 0xac541608 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1493): [trimMemory] 20
D/libc    ( 1916): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1916): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1916): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1916): [NET] android_getaddrinfofornet-, err=8
I/WebViewFactory( 6540): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
W/Uploader( 1916): No account for auth token provided
,I/LibraryLoader( 6540): Time to load native libraries: 9 ms (timestamps 3645-3654),
,I/LibraryLoader( 6540): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6540): Binding Chromium to main looper Looper (main, tid 1) {2458f2a5},
I/LibraryLoader( 6540): Expected native library version number "",actual native library version number ""
I/chromium( 6540): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6540): Initializing chromium process, singleProcess=true,
W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6540): ApplicationContext is null in ApplicationStatus
,W/Uploader( 1916): No account for auth token provided,
,W/chromium( 6540): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6540): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6540): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6540): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6540): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6540): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6540): Local Branch: 
I/Adreno-EGL( 6540): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6540): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6540):                  d74aa161a12b9c6fc6332151
,W/System.err(  971): java.lang.Throwable: stack dump
W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19576017:true
,D/BluetoothAdapter( 6540): 915084321: getState(). Returning 12
,W/Uploader( 1916): No account for auth token provided,
,W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6540): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6540): CordovaWebView is running on device made by: HTC,
,W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  971): Activity pause timeout for ActivityRecord{3b260c1f u0 com.test.thalitest/.MainActivity t12}
W/Uploader( 1916):  no longer exists, so no auth token.
W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6540): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  971): setSystemUiVisibility(0xc0000600)
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
,D/StatusBarManagerService(  971): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
,D/FindExtension( 6540): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,W/Uploader( 1916): No account for auth token provided,
,I/InputMethodManager( 6540): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2d5d6c82, mServedView=org.apache.cordova.engine.SystemWebView{3662ff93 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@10b7cbd0,
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
I/InputMethodManagerService(  971): Disable input method client, pid=1493
D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6540): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  971): Displayed com.test.thalitest/.MainActivity: +683ms (total +726ms),
,W/BindingManager( 6540): Cannot call determinedVisibility() - never saw a connection for the pid: 6540,
,D/JsMessageQueue( 6540): Set native->JS mode to OnlineEventsBridgeMode,
,I/GLSUser ( 1916): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1916): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1916): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1916): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1916): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1916): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1916): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1916): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1916): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1916): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1916): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1916): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1916): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1916): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1916): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1916): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1916): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78),
E/Uploader( 1916): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/jxcore_app_log( 6540): JniHelper::setJavaVM(0xab3d58f8), pthread_self() = -1401726144
D/DotMatrix( 1305): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1305): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6540): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6540):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6540):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6540):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6540):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6540): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d81c794 added. We now have 1 listener(s)
D/BluetoothManagerService(  971): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6540): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6540): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6540): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6540): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159af383 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6540): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  971): New client listening to asynchronous messages
E/WifiTrafficPoller(  971): ADD_CLIENT: 8
,D/BluetoothAdapter( 6540): 915084321: getState(). Returning 12
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6540): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6540): setScanMode: 1 -> 2
,D/BluetoothAdapter( 6540): 915084321: getState(). Returning 12
,I/chromium( 6540): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/Uploader( 1916): No account for auth token provided
,D/PMS     (  971): releaseWL(30cafde6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): acquireWL(33e6ec64): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(33e6ec64): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): acquireWL(2eb14ecd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(2eb14ecd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/jxcore-log( 6540): Initializing JXcore engine
,W/jxcore-log( 6540): JXcore engine is ready
,W/jxcore-log( 6540): Starting JXcore engine
,D/PMS     (  971): releaseHCC(1593ea79): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  971): releaseHCC(1401e3be): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1577): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@35823306
,D/Process (  971): killProcessQuiet, pid=5401
I/ActivityManager(  971): Killing 5401:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5401
,W/jxcore-log( 6540): Platform android,
W/jxcore-log( 6540): 
W/jxcore-log( 6540): Process ARCH arm
W/jxcore-log( 6540): 
,I/jxcore-log( 6540): JXcore Cordova bridge is ready!,
I/jxcore-log( 6540): 
W/jxcore-log( 6540): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6540): execute: REQUEST_ACCESS_COARSE_LOCATION,
I/chromium( 6540): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/jxcore-log( 6540): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native,
I/jxcore-log( 6540): 
,I/io.jxcore.node.ConnectivityInfo( 6540): updateConnectivityInfo: ,
I/io.jxcore.node.ConnectivityInfo( 6540):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6540):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6540):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 6540):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 6540):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 6540):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 6540):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 6540):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 6540): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
I/jxcore-log( 6540): INFO thaliMobileNativeWrapper Method networkChanged registered to native
,I/jxcore-log( 6540): 
I/jxcore-log( 6540): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Unit Test app is loaded,
I/jxcore-log( 6540): 
I/jxcore-log( 6540): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 6540): 
,D/BluetoothAdapter( 6540): 915084321: getState(). Returning 12,
V/io.jxcore.node.JXcoreExtension( 6540): isBleMultipleAdvertisementSupported: SUPPORTED
I/chromium( 6540): [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,I/jxcore-log( 6540): INFO testUtils BLE multiple advertisement supported,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): My device name is: HTC-HTC One M8s,
I/jxcore-log( 6540): 
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  971): acquireWL(270f3382): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null,
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(270f3382): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1305): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  971): updateBatteryInfo
D/DotMatrix( 1305): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  971): plugged=true pluggin=true
D/DotMatrix( 1305): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  971): runPSCheck
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
D/HeadsetStateMachine( 3105): Disconnected process message: 10, size: 0
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
I/jxcore-log( 6540): 
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
I/jxcore-log( 6540): 
,I/jxcore-log( 6540): --= Surplus to requirements =--,
I/jxcore-log( 6540): 
I/jxcore-log( 6540): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 6540): 
,E/cutils-trace( 6606): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 6606): ====startRecUseTime====
D/htc.customization.log.level( 6606):  is 
,W/CustomizationLogLevel( 6606): Level value is invalid, use default level 2
,D/CustomizationManager( 6606):  Read ACC file spent 0.046 (s)
,D/CIDMapFileReader( 6606): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 6606): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6606): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6606): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6606): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6606): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6606): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 6606): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6606): Parsing tag category name = system
I/CustomizationCIDLoader( 6606): Parsing tag category name = application
,I/CustomizationCIDLoader( 6606): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 6606): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6606): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6606): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6606): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 6606): add string-array item, value = 42507
I/CustomizationCIDLoader( 6606): add string-array item, value = 21902
I/CustomizationCIDLoader( 6606): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6606): add string-array item, value = 23420
,I/CustomizationCIDLoader( 6606): add string-array item, value = 22299
I/CustomizationCIDLoader( 6606): add string-array item, value = 24002
I/CustomizationCIDLoader( 6606): add string-array item, value = 23210
I/CustomizationCIDLoader( 6606): add string-array item, value = 23205
I/CustomizationCIDLoader( 6606): add string-array item, value = 23806
I/CustomizationCIDLoader( 6606): add string-array item, value = 23430
I/CustomizationCIDLoader( 6606): add string-array item, value = 23408
I/CustomizationCIDLoader( 6606): add string-array item, value = 27205
I/CustomizationCIDLoader( 6606): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 23205:D:0:0
,I/CustomizationCIDLoader( 6606): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6606): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6606):  Read CID file spent 0.094 (s),
D/CustomizationManager( 6606):  All configurations done spent 0.094 (s)
,D/PackageManager(  971): deletePackageAsUser: pkg=com.test.thalitest, pid=6606, uid=2000 userid=0,
,I/ActivityManager(  971): Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
,D/Process (  971): killProcessQuiet, pid=6540
,I/ActivityManager(  971): Killing 6540:com.test.thalitest/u0a195 (adj 0): stop com.test.thalitest
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  971): Skipping PackageSetting{2ec7e7f6 com.example.hello/10374} due to missing metadata,
,I/ActivityManager(  971): Recipient 6540
,I/WindowState(  971): WIN DEATH: Window{3bdab1d2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  971): Client connection lost with reason: 4
,E/InputEventReceiver( 1377): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{350e191e uid 10195 pid 6540} (c)'
,I/ActivityManager(  971):   Force finishing activity ActivityRecord{3b260c1f u0 com.test.thalitest/.MainActivity t12},
,I/ActivityManager(  971): Force stopping com.test.thalitest appid=10195 user=0: pkg removed,
,I/ActivityManager(  971):   Force finishing activity ActivityRecord{3b260c1f u0 com.test.thalitest/.MainActivity t12 f},
W/ActivityManager(  971): Duplicate finish request for ActivityRecord{3b260c1f u0 com.test.thalitest/.MainActivity t12 f}
,W/ActivityManager(  971): Spurious death for ProcessRecord{1bb6ba93 6540:com.test.thalitest/u0a195}, curProc for 6540: null
,V/NetworkPolicy(  971): ACTION_UID_REMOVED for uid=10195,
D/DotMatrix( 1305): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/PMS     (  971): acquireWL(1a586ad0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 971 1000 null
D/DotMatrix( 1305): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1305): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1711): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  971): Cannot find grip_rejection_width, use default value instead
,D/PMS     (  971): acquireWL(a0105ce): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1815 10024 WorkSource{10024 com.google.android.gms}
,W/GeofencerStateMachine( 1815): Ignoring removeGeofence because network location is disabled.
D/PMS     (  971): releaseWL(a0105ce): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 1711): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/art     ( 5870): Explicit concurrent mark sweep GC freed 9543(577KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 383us total 80.765ms,
,I/art     ( 1493): Explicit concurrent mark sweep GC freed 3449(185KB) AllocSpace objects, 2(44KB) LOS objects, 34% free, 29MB/45MB, paused 849us total 88.724ms
,I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PhoneApp( 1434): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/Launcher( 1493): Deferring update until onResume,
D/Launcher( 1493): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1493): action: android.intent.action.PACKAGE_REMOVED
D/VoicemailCleanupService( 1671): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1711): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/[PluginManager]RegisterService( 1577): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,D/PMS     (  971): releaseWL(1a586ad0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  971): writePolicyLocked()
,I/[PluginManager]RegisterService( 1577): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  971): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6626 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,E/ExternalAccountType( 1711): Unsupported attribute readOnly
,I/InputMethodManagerService(  971): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,V/NetworkPolicy(  971): updateNetworkEnabledLocked(),
V/NetworkPolicy(  971): updateNotificationsLocked()
,W/ResourcesManager(  971): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  971): Explicit concurrent mark sweep GC freed 38020(2MB) AllocSpace objects, 8(412KB) LOS objects, 33% free, 16MB/25MB, paused 1.862ms total 233.361ms,
I/art     (  971): WaitForGcToComplete blocked for 213.703ms for cause Explicit
,D/StatusBarManagerService(  971): setSystemUiVisibility(0x8700)
,D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  971): hiding MENU key
D/StatusBarManagerService(  971): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key,
D/FindExtension( 1493): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,W/ContextImpl( 6626): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,I/ThreadedRenderer( 1493): Defer allocateBuffers to drawing time
,W/InputMethodManagerService(  971): Got RemoteException sending setActive(false) notification to pid 6540 uid 10195
D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
,E/NetworkScheduler.SchedulerReceiver( 1916): Invalid parameter app,
E/NetworkScheduler.SchedulerReceiver( 1916): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  971): acquireWL(2b328ef4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1916 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(2b328ef4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  971): killProcessQuiet, pid=5839
,I/ActivityManager(  971): Killing 5839:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
W/PackageManager(  971): Unable to load service info ResolveInfo{3e168fea com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  971): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  971): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  971): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  971): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  971): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  971): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  971): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  971): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  971): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  971): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  971): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     ( 1916): Explicit concurrent mark sweep GC freed 32565(1799KB) AllocSpace objects, 10(668KB) LOS objects, 47% free, 4MB/8MB, paused 952us total 49.465ms
,D/JobSchedulerService(  971): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  971): Explicit concurrent mark sweep GC freed 8989(504KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.579ms total 236.037ms
,I/ActivityManager(  971): Recipient 5839
,W/asset   (  971): Copying FileAsset 0x55a11260b0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false),
,D/TaskPersister(  971): removeObsoleteFile: deleting file=12_task.xml,
,D/ChimeraCfgMgr( 4416): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 4416): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 4416): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4416): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 4416): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4416): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  971): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6657 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/LocationSettingsChecker( 4416): Removing dialog suppression flag for package com.test.thalitest
,D/GOOGLEHELP_CompatibleDatabase( 4416): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 4416): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2,
,D/gH_MetricsDatabase( 4416): 0 metrics were deleted when clearing package com.test.thalitest.
,D/GOOGLEHELP_CompatibleDatabase( 4416): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4416): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 4416): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 4416): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1,
,D/GOOGLEHELP_CompatibleDatabase( 4416): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
,D/GOOGLEHELP_CompatibleDatabase( 4416): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4416): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4416): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 4416): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 4416): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/PMS     (  971): acquireWL(2f37f102): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4416 10024 null
I/ConfigService( 1916): onCreate
,I/ConfigFetchService( 4416): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,D/PMS     (  971): releaseWL(2f37f102): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,W/BaseAppContext( 4416): Using Auth Proxy for data requests.
,W/BaseAppContext( 4416): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 4416): CP2 sync disabled
,D/PMS     (  971): acquireWL(1645088b): PARTIAL_WAKE_LOCK  Icing 0x1 4416 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4416, uid=10024, userID:0
,I/Icing   ( 4416): doRemovePackageData com.test.thalitest
,D/PMS     (  971): releaseWL(1645088b): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  971): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6688 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=arm64-v8a
,W/DriveInitializer( 4416): Awaiting to be initialized,
,W/DriveInitializer( 4416): Background init thread started
,D/VoldConnector(  971): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.gms/files/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/,
W/ContextImpl( 4416): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,I/GAv4    ( 6657): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6657):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6657):   adb logcat -s GAv4
,W/DriveInitializer( 4416): Background init thread ended,
E/SQLiteLog( 4416): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4416): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55a10a8590
,E/SQLiteLog( 4416): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
E/SQLiteDBG( 4416): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55a10a8590
,E/AndroidRuntime( 4416): FATAL EXCEPTION: pool-13-thread-1
E/AndroidRuntime( 4416): Process: com.google.android.gms, PID: 4416
E/AndroidRuntime( 4416): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4416): 	,at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4416): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 4416): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4416): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4416): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 4416): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 4416): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/AndroidRuntime( 4416): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/AndroidRuntime( 4416): 	at com.google.android.gms.drive.database.f.e(SourceFile:804)
E/AndroidRuntime( 4416): 	at com.google.android.gms.drive.a.a.a.a(SourceFile:65)
E/AndroidRuntime( 4416): 	at com.google.android.gms.drive.a.a.b.run(SourceFile:97)
E/AndroidRuntime( 4416): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/AndroidRuntime( 4416): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4416): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4416): 	at java.lang.Thread.run(Thread.java:818)
E/DriveAsyncService( 4416): disk I/O error (code 3850)
E/DriveAsyncService( 4416): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4416): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4416): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4416): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4416): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4416): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4416): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/DriveAsyncService( 4416): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4416): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 4416): ,	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4416): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4416): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 4416): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4416): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4416): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 6657): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/ActivityManager(  971): App crashed! Process: com.google.android.gms
D/Process ( 4416): killProcess, pid=4416
W/GAv4    ( 6657): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 6657): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/DropBoxManagerService(  971): Can't write: system_app_crash
E/DropBoxManagerService(  971): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  971): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  971): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  971): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  971): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  971): 	... 5 more
E/SharedPreferencesImpl( 6657): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/Process ( 4416): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/GAv4    ( 6657): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 6657): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 6657): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
E/SQLiteDatabase( 6657): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6657): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6657): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6657): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6657): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6657): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6657): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6657): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6657): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6657): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 6657): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 6657): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6657): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6657): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6657): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6657): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6657): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6657): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6657): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6657): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6657): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 6657): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6657): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6657): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6657): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6657): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 6657): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6657): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6657): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6657): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6657): 	at aen.run(PG:536)
E/lowmemorykiller(  382): Error writing /proc/4416/oom_score_adj; errno=22
E/JavaBinder(  971): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  971): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,I/ActivityManager(  971): Recipient 4416,
D/WifiService(  971): Client connection lost with reason: 4
,I/ConfigService( 1916): onDestroy,
I/ActivityManager(  971): Process com.google.android.gms (pid 4416) has died
W/ActivityManager(  971): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10954ms
W/ActivityManager(  971): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10953ms
,W/ActivityManager(  971): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10953ms
,D/VoldConnector(  971): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 6657): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,E/SQLiteDatabase( 6657): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 6657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6657): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6657): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6657): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6657): 	at aej.c(PG:139)
E/SQLiteDatabase( 6657): 	at aej.b(PG:398)
E/SQLiteDatabase( 6657): 	at agf.f(PG:417)
E/SQLiteDatabase( 6657): 	at oe.run(PG:1112)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6657): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 6657): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 6657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6657): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6657): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6657): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6657): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6657): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6657): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 6657): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 6657): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 6657): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/AbstractDatabaseInstance( 6657): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6657): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6657): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6657): 	at java.lang.Thread.run(Thread.java:818),
,D/PMS     (  971): acquireWL(1df484d6): PARTIAL_WAKE_LOCK  AsyncService 0x1 6030 10167 null
W/ResourcesManager( 6657): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6657): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  971): acquireWL(307b4e44): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6030 10167 null
,D/PMS     (  971): releaseWL(1df484d6): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  971): releaseWL(307b4e44): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5870): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,I/ActivityManager(  971): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6740 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,V/JNIHelp ( 6657): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,E/SQLiteLog( 5870): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 5870): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55a0e85c40
,I/ActivityManager(  971): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=6762 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,W/System  ( 6657): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6657): Installed default security provider GmsCore_OpenSSL
,E/SharedPreferencesImpl( 5870): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
E/AndroidRuntime( 5870): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5870): Process: com.google.android.googlequicksearchbox:search, PID: 5870
E/AndroidRuntime( 5870): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5870): ,	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5870): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 5870): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5870): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5870): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 5870): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 5870): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 5870): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 5870): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 5870): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 5870): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 5870): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 5870): 	,at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 5870): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 5870): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 5870): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 5870): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5870): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5870): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 6657): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6657): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6657): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6657): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6657): 	at aej.c(PG:139)
E/SQLiteDatabase( 6657): 	at aej.a(PG:358)
E/SQLiteDatabase( 6657): 	at aej.a(PG:345)
E/SQLiteDatabase( 6657): 	at agf.c(PG:884)
E/SQLiteDatabase( 6657): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 6657): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6657): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6657): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6657): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  971): Can't write: system_app_crash
E/DropBoxManagerService(  971): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  971): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  971): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  971): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  971): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
,E/DropBoxManagerService(  971): 	... 5 more
E/ActivityManager(  971): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AbstractDatabaseInstance( 6657): Failed to query Account133 object
E/AbstractDatabaseInstance( 6657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6657): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6657): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6657): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6657): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6657): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 6657): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 6657): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 6657): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 6657): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 6657): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6657): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 6657): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6657): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6657): 	at java.lang.Thread.run(Thread.java:818)
I/DeviceManagement( 6740): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6740 dbg=false s=true
I/DeviceManagement( 6740): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
D/Process ( 5870): killProcess, pid=5870
I/DeviceManagement( 6740): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
D/Process ( 5870): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 6740): WorkflowService: Starting workflow service
I/DeviceManagement( 6740): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@246bc67a] args=[Bundle[mParcelledData.dataSize=112]]
,I/DeviceManagement( 6740): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 6740): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 6740): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 6740): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  971): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6791 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
,V/GLSActivity( 1916): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  407): Explicit concurrent mark sweep GC freed 8656(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 296us total 35.010ms,
,E/SharedPreferencesImpl( 6657): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak,
,I/DeviceManagement( 6740): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 180us total 22.406ms
I/DeviceManagement( 6740): SessionStateController: Checking invariants...,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 23.256ms,
,E/SQLiteDatabase( 6791): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.,
E/SQLiteDatabase( 6791): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
,E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6791): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 6791): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 6791): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 6791): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 6791): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 6791): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 6791): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 6791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 6791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6791): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6791): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6791): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6791): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6791): FATAL EXCEPTION: main
E/AndroidRuntime( 6791): Process: com.android.documentsui, PID: 6791
E/AndroidRuntime( 6791): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6791): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 6791): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 6791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 6791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6791): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6791): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6791): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6791): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6791): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/An,droidRuntime( 6791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6791): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 6791): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 6791): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 6791): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 6791): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 6791): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 6791): 	... 9 more
I/ActivityManager(  971): Killing 6339:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=6339
I/ActivityManager(  971): Recipient 5870
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/SQLiteDatabase( 6740): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.,
E/SQLiteDatabase( 6740): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6740): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6740): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
,E/SQLiteDatabase( 6740): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 6740): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 6740): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 6740): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
,E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147),
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 6740): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 6740): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280),
E/SQLiteDatabase( 6740): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 6740): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 6740): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 6740): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 6740): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6740): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/SQLiteDatabase( 6740): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6740): 	at java.lang.Thread.run(Thread.java:818)
,I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1493): loadItems() com.htc.launcher.pageview.WidgetManager@383e4240 +
I/Prism.WidgetManager( 1493): onLoadItems() +
,I/ActivityManager(  971): Recipient 6339,
,W/ResourcesManager( 1493): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,E/ActivityManager(  971): App crashed! Process: com.android.documentsui,
I/ActivityManager(  971): Process com.google.android.googlequicksearchbox:search (pid 5870) has died
,W/ActivityManager(  971): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10394ms,
,E/SQLiteLog( 3791): (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10195)] disk I/O error
E/SQLiteDBG( 3791): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.downloads/databases/downloads.db, handle: 0x55a0eb3f50
E/AndroidRuntime( 3791): FATAL EXCEPTION: DownloadReceiver
E/AndroidRuntime( 3791): Process: android.process.media, PID: 3791
E/AndroidRuntime( 3791): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3791): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3791): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 3791): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3791): 	,at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3791): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 3791): 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
E/AndroidRuntime( 3791): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 3791): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 3791): 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
E/AndroidRuntime( 3791): 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
E/AndroidRuntime( 3791): 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
E/AndroidRuntime( 3791): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3791): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 3791): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  971): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=6815 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a,
,I/ActivityManager(  971): Start proc com.google.android.gms for service com.google.android.gms/.feedback.FeedbackService: pid=6834 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/DeviceManagement( 6740): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/ErrorReport(  971): HtcErrorReportManager Begin---add error logs to dropbox
,E/ActivityManager(  971): App crashed! Process: android.process.media
D/ErrorReport(  971): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process (  971): killProcessQuiet, pid=6294
I/ActivityManager(  971): Killing 6294:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
I/DeviceManagement( 6740): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 6740): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,E/SQLiteDatabase( 6740): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 6740): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
,E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6740): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6740): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6740): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 6740): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 6740): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 6740): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 6740): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 6740): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 6740): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6740): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6740): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6740): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 6740): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@246bc67a]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/DeviceManagement( 6740): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
W/DeviceManagement( 6740): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/DeviceManagem,ent( 6740): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/DeviceManagement( 6740): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 6740): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 6740): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 6740): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 6740): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 6740): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 6740): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 6740): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 6740): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 6740): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  971): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,W/System.err(  971): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  971): 	,at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  971): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  971): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  971): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.Posix.open(Native Method)
W/System.err(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  971): 	... 12 more
W/System.err(  971): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  971): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  971): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  971): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  971): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.Posix.open(Native Method)
W/System.err(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  971): 	... 12 more
,W/System.err(  971): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  971): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  971): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  971): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.Posix.open(Native Method)
W/System.err(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  971): 	... 14 more
W/System.err(  971): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  971): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  971): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  971): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.Posix.open(Native Method)
W/System.err(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  971): 	... 14 more
,W/System.err(  971): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  971): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
,W/System.err(  971): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  971): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.Posix.open(Native Method)
W/System.err(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  971): 	... 14 more
W/System.err(  971): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  971): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  971): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
,W/System.err(  971): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  971): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  971): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  971): 	at libcore.io.Posix.open(Native Method)
W/System.err(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  971): 	... 14 more
,W/ResourcesManager( 1493): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Recipient 6294
,I/DeviceManagement( 6740): WorkflowService: Stopping workflow service,
,W/asset   ( 1493): Copying FileAsset 0x55a1277680 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,I/ActivityManager(  971): Killing 5711:com.google.android.talk/u0a112 (adj 15): empty #17,
,D/Process (  971): killProcessQuiet, pid=5711
,E/ErrorReport(  971): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  971): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457972446754.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  971): ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  971): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  971): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  971): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  971): 	... 4 more
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/ErrorReport(  971): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  971): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457972446759.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  971): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  971): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  971): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  971): 	... 4 more
W/ResourcesManager( 6834): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6834): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
