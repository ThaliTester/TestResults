#### Test 62754403b276699_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  988): acquireWL(3fae3d6b): PARTIAL_WAKE_LOCK  *alarm* 0x1 988 1000 WorkSource{1000}
V/AlarmManager(  988): sending alarm PendingIntent{36fba561: PendingIntentRecord{1f8f2886 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457975926319, Int=0
D/PMS     (  988): acquireWL(1fa8f0c8): PARTIAL_WAKE_LOCK  *backup* 0x1 988 1000 null
V/AlarmManager(  988): sending alarm PendingIntent{95b92bf: PendingIntentRecord{216ddd8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180975, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{2bf14547: PendingIntentRecord{14c05174 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203692, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{226c369d: PendingIntentRecord{3b254712 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189490, Int=0
D/PMS     (  988): acquireWL(1472eee3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
W/BackupManagerService(  988): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  988): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  988): releaseWL(1fa8f0c8): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  988): releaseWL(3fae3d6b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1237): Weather sync is On
D/PMS     (  988): acquireWL(204b10e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
W/WeatherTimeKeeper( 1237): [refreshWeatherData] no weather data
D/PMS     (  988): releaseWL(1472eee3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
V/GLSActivity( 1862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  988): releaseWL(204b10e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(e5ea66a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(e5ea66a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(14fd575b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(bde1bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(31b8bf36): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
E/cutils-trace( 6558): Error opening trace file: Permission denied (13)
I/art     ( 1862): Explicit concurrent mark sweep GC freed 16896(944KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 1.417ms total 95.971ms
D/PMS     (  988): releaseWL(14fd575b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(7d4ffa4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(7d4ffa4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/VacuumService( 1862): Vacuum at: now=1457975963087 tag=VacuumService
I/GoogleURLConnFactory( 1862): Using platform SSLCertificateSocketFactory
D/PMS     (  988): releaseWL(bde1bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(186d010d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/CustomizationManager( 6558): ====startRecUseTime====
D/htc.customization.log.level( 6558):  is 
W/CustomizationLogLevel( 6558): Level value is invalid, use default level 2
W/Uploader( 1862): No account for auth token provided
D/PMS     (  988): releaseWL(186d010d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(2575a109): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(2575a109): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 1862): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1862): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1862): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1862): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1862): [NET] android_getaddrinfo_proxy+
D/libc    ( 1862): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/CustomizationManager( 6558):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 6558): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6558): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6558): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6558): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6558): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6558): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6558): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6558): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6558): Parsing tag category name = system
I/CustomizationCIDLoader( 6558): Parsing tag category name = application
I/CustomizationCIDLoader( 6558): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6558): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6558): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6558): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6558): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6558): add string-array item, value = 42507
I/CustomizationCIDLoader( 6558): add string-array item, value = 21902
I/CustomizationCIDLoader( 6558): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6558): add string-array item, value = 23420
I/CustomizationCIDLoader( 6558): add string-array item, value = 22299
I/CustomizationCIDLoader( 6558): add string-array item, value = 24002
I/CustomizationCIDLoader( 6558): add string-array item, value = 23210
I/CustomizationCIDLoader( 6558): add string-array item, value = 23205
I/CustomizationCIDLoader( 6558): add string-array item, value = 23806
I/CustomizationCIDLoader( 6558): add string-array item, value = 23430
I/CustomizationCIDLoader( 6558): add string-array item, value = 23408
I/CustomizationCIDLoader( 6558): add string-array item, value = 27205
I/CustomizationCIDLoader( 6558): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6558): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6558):  Read CID file spent 0.098 (s)
D/CustomizationManager( 6558):  All configurations done spent 0.099 (s)
I/ActivityManager(  988): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6558 on display 0
D/PMS     (  988): acquireHCC(201c7f0e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 988 1000 null
D/PMS     (  988): acquireHCC(2dac8d2f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 988 1000 null
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1862): [NET] android_getaddrinfo_proxy-, success
W/asset   (  988): Copying FileAsset 0x559fbbd010 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  988): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6581 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1356): [EventService]  onDisplayChanged: 0
V/ActivityManager(  988): Display changed displayId=0
D/DotMatrix( 1356): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6581): Copying FileAsset 0xac556b20 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1604): [trimMemory] 20
I/WebViewFactory( 6581): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6581): Time to load native libraries: 9 ms (timestamps 4507-4516),
,I/LibraryLoader( 6581): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6581): Binding Chromium to main looper Looper (main, tid 1) {16428821},
I/LibraryLoader( 6581): Expected native library version number "",actual native library version number ""
,I/chromium( 6581): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6581): Initializing chromium process, singleProcess=true,
,W/art     ( 6581): Attempt to remove local handle scope entry from IRT, ignoring
D/libc    ( 1862): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1862): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1862): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1862): [NET] android_getaddrinfofornet-, err=8
,E/SysUtils( 6581): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6581): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6581): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6581): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6581): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6581): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6581): Build Date: 03/09/15 Mon,
I/Adreno-EGL( 6581): Local Branch: 
I/Adreno-EGL( 6581): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6581): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6581):                  d74aa161a12b9c6fc6332151
,W/System.err(  988): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  988): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  988): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  988): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  988): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  988): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothManagerService(  988): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e4999d4:true
,D/BluetoothAdapter( 6581): 941859636: getState(). Returning 12,
,W/Uploader( 1862): No account for auth token provided
,W/art     ( 6581): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6581): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6581): CordovaWebView is running on device made by: HTC
,W/art     ( 6581): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6581): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  988): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/ActivityManager(  988): Activity pause timeout for ActivityRecord{26d69f3c u0 com.test.thalitest/.MainActivity t12}
,W/chromium( 6581): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/Uploader( 1862): No account for auth token provided
,D/StatusBarManagerService(  988): setSystemUiVisibility(0xc0000600)
,D/StatusBarManagerService(  988): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  988): hiding MENU key
D/StatusBarManagerService(  988): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  988): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  988): hiding MENU key
,D/FindExtension( 6581): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,W/Uploader( 1862): No account for auth token provided
,I/InputMethodManager( 6581): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@97b2ce, mServedView=org.apache.cordova.engine.SystemWebView{126615ef VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@160058fc
,I/InputMethodManagerService(  988): Disable input method client, pid=1604
D/StatusBarManagerService(  988): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1237): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6581): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  988): Displayed com.test.thalitest/.MainActivity: +661ms (total +704ms)
,W/BindingManager( 6581): Cannot call determinedVisibility() - never saw a connection for the pid: 6581
,W/Uploader( 1862):  no longer exists, so no auth token.,
,D/JsMessageQueue( 6581): Set native->JS mode to OnlineEventsBridgeMode,
,W/Uploader( 1862): No account for auth token provided
,D/jxcore_app_log( 6581): JniHelper::setJavaVM(0xab3eb8f8), pthread_self() = -1401860216
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6581): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6581):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6581):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6581):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6581):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6581): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa10d00 added. We now have 1 listener(s)
D/BluetoothManagerService(  988): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6581): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6581): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6581): setHandshakeRequired: true -> false,
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6581): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96e58df added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6581): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  988): New client listening to asynchronous messages
E/WifiTrafficPoller(  988): ADD_CLIENT: 8
,D/BluetoothAdapter( 6581): 941859636: getState(). Returning 12
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6581): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6581): setScanMode: 1 -> 2
,D/BluetoothAdapter( 6581): 941859636: getState(). Returning 12
,I/chromium( 6581): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GLSUser ( 1862): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1862): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1862): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1862): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1862): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1862): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1862): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1862): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1862): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1862): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1862): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1862): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1862): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1862): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1862): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125),
E/Uploader( 1862): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1862): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1237): reapply : com.google.android.gms 1 40
,D/DotMatrix( 1356): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1356): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  988): releaseWL(31b8bf36): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  988): acquireWL(3c08485d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  988): releaseWL(3c08485d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): acquireWL(2a8155d2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(2a8155d2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/jxcore-log( 6581): Initializing JXcore engine
W/jxcore-log( 6581): JXcore engine is ready
,W/jxcore-log( 6581): Starting JXcore engine,
,W/jxcore-log( 6581): Platform android,
W/jxcore-log( 6581): 
W/jxcore-log( 6581): Process ARCH arm
W/jxcore-log( 6581): 
,D/PMS     (  988): releaseHCC(201c7f0e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  988): releaseHCC(2dac8d2f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6581): JXcore Cordova bridge is ready!,
I/jxcore-log( 6581): 
W/jxcore-log( 6581): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6581): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 6581): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6581): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}],
,I/chromium( 6581): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,D/Process (  988): killProcessQuiet, pid=5726
I/ActivityManager(  988): Killing 5726:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  988): Recipient 5726
,W/PluginManager( 6581): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 128ms. Plugin should use CordovaInterface.getThreadPool().
,D/HtcUPManager( 1237): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1237): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1675): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@26191d92
,D/Process (  988): killProcessQuiet, pid=5401
I/ActivityManager(  988): Killing 5401:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  988): Recipient 5401
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  988): acquireWL(33a3b6a3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null,
I/BatteryService(  988): n_update end
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  988): updateBatteryInfo
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1237): closing low battery warning: level=100
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/PMS     (  988): runPSCheck
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  988): Checking...
D/UsbnetService(  988): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): handleMessage: E msg.what=155652
,D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: DeviceActiveState
D/PMS     (  988): releaseWL(33a3b6a3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WifiController(  988): processMsg: StaEnabledState
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  988): processMsg: DefaultState
I/HtcPowerSaver(  988): << updateStatus
D/WifiController(  988): handleMessage: X
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1350): wlan0: BSS: Remove id 6 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 1 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush_by_age
,D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 f0:f2:6d:22:99:3e]
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 8 BSSID 00:1f:27:54:dd:eb SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 10 BSSID 00:1f:27:54:dd:e0 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 9 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 f0:f2:6d:22:99:3e
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 11 BSSID 00:1f:27:54:dd:e4 SSID '\x00' due to wpa_bss_flush_by_age
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0]
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:e0:44 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 13 BSSID 00:1f:27:54:e0:40 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 14 BSSID 24:a4:3c:de:78:94 SSID 'skup' due to wpa_bss_flush_by_age
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:dd:ef]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:dd:ef
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:1f:27:54:dd:eb]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:1f:27:54:dd:eb
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:dd:e0]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:dd:e0
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:16:a6:1f:06:5c]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:16:a6:1f:06:5c
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:1f:27:54:dd:e4]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:1f:27:54:dd:e4
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:e0:44]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:e0:44
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:e0:40]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:e0:40
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 12 BSSID 62:45:b0:73:93:45 SSID '' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 5 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 24:a4:3c:de:78:94]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 24:a4:3c:de:78:94
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 62:45:b0:73:93:45]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 62:45:b0:73:93:45
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:e3]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:e3
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:e0:43]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:e0:43
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  988): acquireWL(36c9da0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
V/AlarmManager(  988): sending alarm PendingIntent{95b92bf: PendingIntentRecord{216ddd8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240975, Int=0
,V/AlarmManager(  988): sending alarm PendingIntent{117afd1e: PendingIntentRecord{db119ff com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457976100541, Int=0
,D/PMS     (  988): releaseWL(36c9da0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1237): Weather sync is On
,W/WeatherTimeKeeper( 1237): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1862): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1862): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1862): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1862): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1862): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1356): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1356): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1237): reapply : com.google.android.gms 3 40
W/GLSActivity( 1862): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1862): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1862): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1862): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1862): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1862): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1862): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5951): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5951): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5951): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5951): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5951): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5951): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5951): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5951): Ignoring header User-Agent because its value was null.
,D/libc    ( 5951): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5951): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5951): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5951): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5951): [NET] android_getaddrinfo_proxy+
D/libc    ( 5951): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5951): [NET] android_getaddrinfo_proxy-, success,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  988): acquireWL(23b7fec9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(23b7fec9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1237): closing low battery warning: level=100
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): processMsg: DeviceActiveState
,D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  988): acquireWL(1d6ee9ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null,
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(1d6ee9ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/WifiController(  988): battery changed pluggedType: 2
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/PMS     (  988): runPSCheck
D/WifiController(  988): handleMessage: E msg.what=155652
D/HtcPowerSaver(  988): Checking...
D/WifiController(  988): processMsg: DeviceActiveState
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): processMsg: StaEnabledState
D/PowerUI ( 1237): closing low battery warning: level=100
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  988): acquireWL(36ca80ef): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null,
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(36ca80ef): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PowerUI ( 1237): closing low battery warning: level=100
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/WifiController(  988): battery changed pluggedType: 2
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): Checking...
D/WifiController(  988): handleMessage: E msg.what=155652
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): handleMessage: X
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1560): MSG_CHECK_DELETION >>,
,D/ContactMessageStore( 1560): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1560): sku_id=118
D/ContactMessageStore( 1560): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1560): start background delete task...
,D/ContactMessageStore( 1560): size: 0 , 0,
D/ContactMessageStore( 1560): Background delete complete
,D/PMS     (  988): acquireWL(2f5be7fc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(2f5be7fc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PowerUI ( 1237): closing low battery warning: level=100
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  988): updateBatteryInfo
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  988): plugged=true pluggin=true
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  988): Checking...
D/UsbnetService(  988): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  988): >> updateStatus
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  988): battery changed pluggedType: 2
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PMS     (  988): acquireWL(13b8be85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
D/UsbnetService(  988): BroadcastReceiver::onReceive+
I/BatteryService(  988): n_update end
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/PMS     (  988): releaseWL(13b8be85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/NotificationService(  988): plugged=true pluggin=true
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1237): closing low battery warning: level=100
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  988): runPSCheck
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  988): Checking...
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: DeviceActiveState
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  988): acquireWL(f93d4da): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(f93d4da): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): Checking...
D/WifiController(  988): handleMessage: E msg.what=155652
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
D/PowerUI ( 1237): closing low battery warning: level=100
D/WifiController(  988): processMsg: DefaultState
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): handleMessage: X
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  988): << updateStatus
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  988): acquireWL(27683d0b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(27683d0b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive-,
D/HtcPowerSaver(  988): Checking...
D/WifiController(  988): handleMessage: E msg.what=155652
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): processMsg: DeviceActiveState
D/PowerUI ( 1237): closing low battery warning: level=100
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: DefaultState
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): handleMessage: X
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  988): << updateStatus
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  988): acquireWL(b7d87e8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
,V/AlarmManager(  988): sending alarm PendingIntent{95b92bf: PendingIntentRecord{216ddd8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=360976, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{294bbe01: PendingIntentRecord{1eea64a6 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941014, Int=0
,I/bt-btm  ( 3116): Received oneshot timer event complete
I/bt-btm  ( 3116): btm_ble_timeout
,I/bt-btm  ( 3116): btm_gen_resolvable_private_addr
,D/PMS     (  988): acquireWL(12db9ee7): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3116 1002 null
,D/bt-btm  ( 3116): btm_ble_rand_enc_complete,
I/bt-btm  ( 3116): btm_gen_resolve_paddr_low
D/bt-smp  ( 3116): smp_encrypt_data
W/bt-smp  ( 3116): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3116): Plain text(LSB ~ MSB) = e5 4f 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3116): Encrypted text(LSB ~ MSB) = 0e e0 8e 68 b8 6a 29 57 a8 12 c3 0e c2 0e 8c 3b 
I/bt-btm  ( 3116): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3116): Stopping oneshot timer
D/bt-btm  ( 3116): Starting oneshot timer type:103 timeout:900s,
,D/PMS     (  988): releaseWL(b7d87e8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1237): Weather sync is On
W/WeatherTimeKeeper( 1237): [refreshWeatherData] no weather data
,D/PMS     (  988): releaseWL(12db9ee7): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  988): acquireWL(3f973a94): PARTIAL_WAKE_LOCK  *alarm* 0x1 988 1000 WorkSource{1000}
V/AlarmManager(  988): sending alarm PendingIntent{326f91d1: PendingIntentRecord{1094f436 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806047, Int=0
,V/AlarmManager(  988): sending alarm PendingIntent{95b92bf: PendingIntentRecord{216ddd8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=960975, Int=0,
V/AlarmManager(  988): sending alarm PendingIntent{9b5393d: PendingIntentRecord{1bc82532 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=938520, Int=0,
,D/PMS     (  988): acquireWL(6394283): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(6394283): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  988): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6648 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  988): sending alarm PendingIntent{cf76c00: PendingIntentRecord{30412c39 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457976501689, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{144f627e: PendingIntentRecord{1d025a66 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457976725778, Int=0
,D/PMS     (  988): acquireWL(14383df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6472): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/WeatherUtility( 1237): Weather sync is On,
W/WeatherTimeKeeper( 1237): [refreshWeatherData] no weather data
D/PMS     (  988): releaseWL(3f973a94): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6472): MY_DEBUG = false,
,D/PowerUsageService( 6472): repeat time = 1457977625867,
,D/PMS     (  988): acquireWL(47b288a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  988): releaseWL(14383df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/StatusBarManagerService(  988): setSystemUiVisibility(0x8700),
D/StatusBarManagerService(  988): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  988): hiding MENU key
,D/StatusBarManagerService(  988): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  988): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  988): hiding MENU key
,D/FindExtension( 1604): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1604): Defer allocateBuffers to drawing time
,D/PMS     (  988): acquireWL(3c16bb18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1862): Message class com.google.f.a.a.i
,I/PowerUsageList:PowerUsageHelper( 6472): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/InputMethodManagerService(  988): Disable input method client, pid=6581
D/StatusBarManagerService(  988): swetImeWindowStatus vis=0 backDisposition=0
D/PMS     (  988): releaseWL(3c16bb18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PhoneStatusBar( 1237): setImeWindowStatus(false,false),
W/IInputConnectionWrapper( 6581): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6581): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6581): reportFullscreenMode on inactive InputConnection
,D/PowerUsageList:BatterySipperExt( 6472): gen(), null == sipper.uidObj, userId = 0,
D/PowerUsageList:BatterySipperExt( 6472): gen(), null == sipper.uidObj, userId = 0
D/PowerUsageList:BatterySipperExt( 6472): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 6673): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6673): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6673): dex2oat: override thread count:4
,D/PMS     (  988): releaseWL(47b288a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  988): acquireWL(f3f2971): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(f3f2971): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): acquireWL(3aeb4356): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(3aeb4356): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/dex2oat ( 6673): dex2oat took 797.825ms (threads: 4),
,I/PushClient( 6648): ApplicationMonitor {311e855d}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6648): ApplicationMonitor {311e855d}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6648): ApplicationMonitor {311e855d}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6648): ApplicationMonitor {311e855d}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6648): ApplicationMonitor {311e855d}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6648): ApplicationMonitor {311e855d}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6648): ApplicationMonitor {311e855d}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6648): ApplicationMonitor {311e855d}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6648): ApplicationMonitor {311e855d}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6648): PnsModel {3823a334}: update(): Update registration caused by: alarm,
,I/PushClient( 6648): PnsConfigModel {853fc1b}: <init>(): Use dm-client for provisioning.
,W/System.err( 6648): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6648): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6648): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6648): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  988): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6681 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6681): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6681 dbg=false s=true,
,I/DeviceManagement( 6681): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6681): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6681): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6681): WorkflowService: Starting workflow service
,I/DeviceManagement( 6681): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3823a334] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6681): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6681): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6681): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6681): SessionStateController: Checking invariants...
,I/art     (  988): Explicit concurrent mark sweep GC freed 34561(1911KB) AllocSpace objects, 12(1260KB) LOS objects, 33% free, 16MB/24MB, paused 1.741ms total 137.832ms,
,I/DeviceManagement( 6681): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 6681): SessionStateController: Checking invariants...
,I/DeviceManagement( 6681): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6681): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3823a334]
,I/DeviceManagement( 6681): WorkflowService: Stopping workflow service
,D/Process (  988): killProcessQuiet, pid=6378
,I/ActivityManager(  988): Killing 6378:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  988): Recipient 6378,
,I/PushClient( 6648): PnsModel {3823a334}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  988): killProcessQuiet, pid=6332
I/ActivityManager(  988): Killing 6332:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  988): Recipient 6332
,D/PMS     (  988): acquireWL(2776c83a): PARTIAL_WAKE_LOCK  *alarm* 0x1 988 1000 WorkSource{1000},
V/AlarmManager(  988): sending alarm PendingIntent{15711ceb: PendingIntentRecord{20bb1a48 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457976772356, Int=0,
D/SmartSyncUtils( 6472): isEpsOn(), nState = 0
,D/PMS     (  988): releaseWL(2776c83a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  988): acquireWL(d5c50e1): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6472 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6472): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6472): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6472): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6472): SettingOnTime = 1458021600000, randomSettingOnTime = 1458019803000
D/SmartSyncScreenOnOffTimeReceiver( 6472): SettingOffTime = 1458000000000, randomSettingOffTime = 1458004429000
D/SmartSyncScreenOnOffTimeReceiver( 6472): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6472): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6472): bNightModeTurnOffOnce = false
,D/PMS     (  988): releaseWL(d5c50e1): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  988): acquireWL(3ff92e06): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
,D/PMS     (  988): releaseWL(3ff92e06): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  988): updateBatteryInfo
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PowerUI ( 1237): closing low battery warning: level=100
,D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/PMS     (  988): runPSCheck
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  988): Checking...
D/UsbnetService(  988): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): handleMessage: E msg.what=155652
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  988): acquireWL(7c29cc7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(7c29cc7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  988): updateBatteryInfo
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1237): closing low battery warning: level=100
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1),
D/UsbnetService(  988): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  988): << updateStatus
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  988): battery changed pluggedType: 2
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  988): acquireWL(228b92f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(228b92f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1237): closing low battery warning: level=100
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  988): updateBatteryInfo
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  988): Checking...
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  988): >> updateStatus
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): handleMessage: E msg.what=155652
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  988): processMsg: DeviceActiveState
I/HtcPowerSaver(  988): << updateStatus
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/WifiController(  988): handleMessage: X
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  988): acquireWL(18ec1a1d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(18ec1a1d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  988): updateBatteryInfo
,D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  988): plugged=true pluggin=true
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1237): closing low battery warning: level=100
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/UsbnetService(  988): onReceive BATTERY_CHANGED
,D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  988): BroadcastReceiver::onReceive-
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
,I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  988): User[0] Flushing usage stats to disk,
,D/PMS     (  988): acquireWL(1bea2492): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(1bea2492): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): Checking...
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): handleMessage: E msg.what=155652
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  988): processMsg: DeviceActiveState
I/HtcPowerSaver(  988): << updateStatus
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: DefaultState
D/PowerUI ( 1237): closing low battery warning: level=100
D/WifiController(  988): handleMessage: X
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  988): acquireWL(14c23e63): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
,V/AlarmManager(  988): sending alarm PendingIntent{95b92bf: PendingIntentRecord{216ddd8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1020976, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{2948ea60: PendingIntentRecord{31b53b19 android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1208807, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{3081f7de: PendingIntentRecord{14905dbf com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457977028602, Int=1800000
,D/HtcSystemUPManager(  988): UPAlarmListener onAlarmArrival
V/AlarmManager(  988): sending alarm PendingIntent{3ec24c8c: PendingIntentRecord{2c556fd5 com.htc.task broadcastIntent}}, i=com.htc.task.statistics, t=1, cnt=1, w=1457976967943, Int=0
D/HtcSystemUPManager(  988): UPAlarmListener [SYSTEM_UP_UPLOAD] cur = 1457977028609, last = 1457890567832, freq = 86400000
D/HtcSystemUPManager(  988): AlarmScheduler_INEXACT [onReceive] end
D/HtcSystemUPManager(  988): com.htc.upm.AlarmScheduler$SchedulerBase$1@6a0cc0f
,D/PMS     (  988): acquireWL(3c31b3ea): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4436 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1237): Weather sync is On
W/WeatherTimeKeeper( 1237): [refreshWeatherData] no weather data
,D/PMS     (  988): acquireWL(188da578): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4436 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  988): releaseWL(3c31b3ea): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,W/HtcSystemUPManager(  988): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability,
I/ActivityManager(  988): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=6710 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,W/HtcSystemUPManager(  988): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability,
,I/EventLogService( 4436): Aggregate from 1457975856021 (log), 1457975228567 (data)
,W/HtcSystemUPManager(  988): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,W/HtcSystemUPManager(  988): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,W/ResourcesManager( 6710): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/HtcSystemUPManager(  988): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
D/HtcSystemUPManager(  988): HtcSystemUPHandler sendService() has been called
,D/HtcSystemUPManager(  988): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
,I/HtcSystemUPManager(  988): HtcSystemUPDataStore Send UPLOAD message to UP service 
,D/HtcAppUPService( 1675): HtcUPDataProvider bulkInsert() has been called.,
,D/PMS     (  988): releaseWL(14c23e63): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10069},
D/PMS     (  988): releaseWL(188da578): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcAppUPService( 1675): HtcUPServiceStore Store Version: 1 Data version: 1 File total length: 9 bytes.  Data length: 0bytes,
I/HtcAppUPService( 1675): HtcUPServiceStore Uploading is triggered by System...
,D/HtcSystemUPManager(  988): HtcSystemUPHandler send to UPService takes: 38 ms
D/HtcAppUPService( 1675): HtcUPService onCreate()
,D/HtcAppUPService( 1675): PolicyStore [Init] Get cached policy bundle
D/HtcAppUPService( 1675): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.SYSTEM_UP_NOTIFY cmp=com.htc.sense.hsp/.upservice.HtcUPService (has extras) }, this = com.htc.sense.hsp.upservice.HtcUPService@36f2b1ec
,D/HtcAppUPService( 1675): appid: tellhtc_client, category: usage_report, key: enable, value: 1, due date: -1, current time: 1457977028752, default value: null
,D/HtcAppUPService( 1675): HtcUPServicePreference Upload schedule enable? false
D/HtcAppUPService( 1675): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.SYSTEM_UP_NOTIFY
,D/HtcAppUPService( 1675): ReportUploader User Profiling function had been closed by user,
I/HtcAppUPService( 1675): HtcUPServiceStore Clear data store!
,D/HtcAppUPService( 1675): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,D/HtcAppUPService( 1675): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
,D/HtcAppUPService( 1675): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@36f2b1ec
,D/Process (  988): killProcessQuiet, pid=5746
I/ActivityManager(  988): Killing 5746:com.google.android.talk/u0a112 (adj 15): empty #17
,D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  988): Recipient 5746
,D/PMS     (  988): acquireWL(2240d642): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(2240d642): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): Checking...
,I/HtcPowerSaver(  988): >> updateStatus
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PowerUI ( 1237): closing low battery warning: level=100
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): processMsg: DeviceActiveState
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  988): processMsg: StaEnabledState
,D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): handleMessage: X
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  988): acquireWL(fef8653): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  988): n_update end
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  988): releaseWL(fef8653): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  988): updateBatteryInfo
I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1237): closing low battery warning: level=100
D/UsbnetService(  988): BroadcastReceiver::onReceive+
,D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): Checking...
D/WifiController(  988): handleMessage: E msg.what=155652
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  988): processMsg: DefaultState
I/HtcPowerSaver(  988): << updateStatus
D/WifiController(  988): handleMessage: X
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  988): acquireWL(3b1bab90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(3b1bab90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1237): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  988): updateBatteryInfo
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PowerUI ( 1237): closing low battery warning: level=100
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1237): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1356): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  988): plugged=true pluggin=true
D/DotMatrix( 1356): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  988): Checking...
D/UsbnetService(  988): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  988): >> updateStatus
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  988): battery changed pluggedType: 2
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1237): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1400000ms)
```
