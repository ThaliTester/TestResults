#### Test 625090944a5472b_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  959): acquireWL(14fc7980): PARTIAL_WAKE_LOCK  *alarm* 0x1 959 1000 WorkSource{1000}
V/AlarmManager(  959): sending alarm PendingIntent{1584ebb9: PendingIntentRecord{3380ebfe android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457941954388, Int=0
V/AlarmManager(  959): sending alarm PendingIntent{882005e: PendingIntentRecord{222afc3f android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=192054, Int=0
V/AlarmManager(  959): sending alarm PendingIntent{3a400f5f: PendingIntentRecord{146fadac android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=201927, Int=0
V/AlarmManager(  959): sending alarm PendingIntent{397f8a75: PendingIntentRecord{22fbca0a com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190984, Int=0
D/PMS     (  959): acquireWL(2a80427b): PARTIAL_WAKE_LOCK  *backup* 0x1 959 1000 null
D/PMS     (  959): acquireWL(12fff898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
W/BackupManagerService(  959): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  959): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  959): releaseWL(2a80427b): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  959): releaseWL(14fc7980): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1212): Weather sync is On
W/WeatherTimeKeeper( 1212): [refreshWeatherData] no weather data
D/PMS     (  959): acquireWL(324b58f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): releaseWL(12fff898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  959): releaseWL(324b58f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): acquireWL(1abe85f3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): releaseWL(1abe85f3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): acquireWL(3ce142b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): releaseWL(3ce142b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): acquireWL(125b3529): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): acquireWL(21be50ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): acquireWL(118fd9dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): releaseWL(125b3529): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/VacuumService( 1869): Vacuum at: now=1457941990094 tag=VacuumService
I/GoogleURLConnFactory( 1869): Using platform SSLCertificateSocketFactory
D/PMS     (  959): releaseWL(21be50ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): acquireWL(2622c9ba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): releaseWL(2622c9ba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): acquireWL(1622c06b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
W/Uploader( 1869): No account for auth token provided
D/PMS     (  959): releaseWL(1622c06b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 1869): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1869): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1869): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1869): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1869): [NET] android_getaddrinfo_proxy+
D/libc    ( 1869): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1869): [NET] android_getaddrinfo_proxy-, success
E/cutils-trace( 6585): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6585): ====startRecUseTime====
D/htc.customization.log.level( 6585):  is 
W/CustomizationLogLevel( 6585): Level value is invalid, use default level 2
D/libc    ( 1869): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1869): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1869): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1869): [NET] android_getaddrinfofornet-, err=8
D/CustomizationManager( 6585):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6585): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6585): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6585): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6585): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6585): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6585): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6585): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6585): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6585): Parsing tag category name = system
I/CustomizationCIDLoader( 6585): Parsing tag category name = application
I/CustomizationCIDLoader( 6585): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6585): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6585): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6585): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6585): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6585): add string-array item, value = 42507
I/CustomizationCIDLoader( 6585): add string-array item, value = 21902
I/CustomizationCIDLoader( 6585): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6585): add string-array item, value = 23420
I/CustomizationCIDLoader( 6585): add string-array item, value = 22299
I/CustomizationCIDLoader( 6585): add string-array item, value = 24002
I/CustomizationCIDLoader( 6585): add string-array item, value = 23210
I/CustomizationCIDLoader( 6585): add string-array item, value = 23205
I/CustomizationCIDLoader( 6585): add string-array item, value = 23806
I/CustomizationCIDLoader( 6585): add string-array item, value = 23430
I/CustomizationCIDLoader( 6585): add string-array item, value = 23408
I/CustomizationCIDLoader( 6585): add string-array item, value = 27205
I/CustomizationCIDLoader( 6585): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6585): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6585):  Read CID file spent 0.096 (s)
D/CustomizationManager( 6585):  All configurations done spent 0.096 (s)
I/ActivityManager(  959): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6585 on display 0
D/PMS     (  959): acquireHCC(8aaf847): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 959 1000 null
D/PMS     (  959): acquireHCC(165b8874): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 959 1000 null
I/ActivityManager(  959): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6607 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1328): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1328): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  959): Display changed displayId=0
W/Uploader( 1869): No account for auth token provided
I/TrimMemoryManager( 1616): [trimMemory] 20
W/Uploader( 1869): No account for auth token provided
I/WebViewFactory( 6607): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
W/Uploader( 1869): No account for auth token provided
,I/LibraryLoader( 6607): Time to load native libraries: 14 ms (timestamps 2839-2853),
,I/LibraryLoader( 6607): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6607): Binding Chromium to main looper Looper (main, tid 1) {25ceef7d}
,I/LibraryLoader( 6607): Expected native library version number "",actual native library version number ""
,I/chromium( 6607): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6607): Initializing chromium process, singleProcess=true
,W/art     ( 6607): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6607): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6607): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6607): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6607): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 6607): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6607): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6607): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6607): Local Branch: 
I/Adreno-EGL( 6607): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6607): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6607):                  d74aa161a12b9c6fc6332151
,W/Uploader( 1869):  no longer exists, so no auth token.
,W/System.err(  959): java.lang.Throwable: stack dump
W/System.err(  959): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  959): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  959): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  959): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  959): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c476755:true
,D/BluetoothAdapter( 6607): 350226041: getState(). Returning 12
,W/art     ( 6607): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6607): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6607): CordovaWebView is running on device made by: HTC
,W/Uploader( 1869): No account for auth token provided
,W/art     ( 6607): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6607): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  959): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/ActivityManager(  959): Activity pause timeout for ActivityRecord{2644a19d u0 com.test.thalitest/.MainActivity t12}
,W/chromium( 6607): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  959): setSystemUiVisibility(0xc0000600)
D/StatusBarManagerService(  959): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  959): hiding MENU key
D/StatusBarManagerService(  959): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  959): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  959): hiding MENU key
,D/FindExtension( 6607): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/art     ( 1869): Explicit concurrent mark sweep GC freed 22530(1265KB) AllocSpace objects, 6(440KB) LOS objects, 48% free, 4MB/8MB, paused 793us total 45.155ms
,I/GLSUser ( 1869): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1869): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1869): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1869): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1328): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1328): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1869): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1869): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1869): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1869): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1869): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1869): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1869): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1869): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1869): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1869): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1869): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1869): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1869): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/RemoteViews( 1212): reapply : com.google.android.gms 2 40
,I/InputMethodManager( 6607): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3995997a, mServedView=org.apache.cordova.engine.SystemWebView{7d1b52b VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3bf6d88
,I/InputMethodManagerService(  959): Disable input method client, pid=1616
D/StatusBarManagerService(  959): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6607): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1212): setImeWindowStatus(false,false)
,I/ActivityManager(  959): Displayed com.test.thalitest/.MainActivity: +675ms (total +724ms)
,W/BindingManager( 6607): Cannot call determinedVisibility() - never saw a connection for the pid: 6607,
,D/PMS     (  959): releaseWL(118fd9dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  959): acquireWL(8fbdeb1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(8fbdeb1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  959): acquireWL(3efdef96): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(3efdef96): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/JsMessageQueue( 6607): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6607): JniHelper::setJavaVM(0xaaf528f8), pthread_self() = -1406533816
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17f23bcc added. We now have 1 listener(s)
D/BluetoothManagerService(  959): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setBluetoothMacAddress: 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6607): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6607): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"},
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6607): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bce3f1b added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6607): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  959): New client listening to asynchronous messages
,E/WifiTrafficPoller(  959): ADD_CLIENT: 8
,D/BluetoothAdapter( 6607): 350226041: getState(). Returning 12
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6607): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setScanMode: 1 -> 2
D/BluetoothAdapter( 6607): 350226041: getState(). Returning 12
,I/chromium( 6607): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6607): Initializing JXcore engine
,W/jxcore-log( 6607): JXcore engine is ready
,W/jxcore-log( 6607): Starting JXcore engine,
,W/jxcore-log( 6607): Platform android
W/jxcore-log( 6607): 
,W/jxcore-log( 6607): Process ARCH arm
W/jxcore-log( 6607): 
,D/PMS     (  959): releaseHCC(8aaf847): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  959): releaseHCC(165b8874): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6607): JXcore Cordova bridge is ready!
I/jxcore-log( 6607): 
W/jxcore-log( 6607): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6607): execute: REQUEST_ACCESS_COARSE_LOCATION,
I/chromium( 6607): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 6607): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6607): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6607): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
I/chromium( 6607): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,D/Process (  959): killProcessQuiet, pid=5722
I/ActivityManager(  959): Killing 5722:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  959): Recipient 5722,
,W/PluginManager( 6607): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 231ms. Plugin should use CordovaInterface.getThreadPool().,
,E/cutils-trace( 6666): Error opening trace file: Permission denied (13),
,D/CustomizationManager( 6666): ====startRecUseTime====,
D/htc.customization.log.level( 6666):  is 
W/CustomizationLogLevel( 6666): Level value is invalid, use default level 2
,D/CustomizationManager( 6666):  Read ACC file spent 0.031 (s),
,D/CIDMapFileReader( 6666): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 6666): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6666): Parsing tag item name = HTC__Y13,
D/CIDMapFileReader( 6666): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6666): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6666): Parsing tag item name = HTC__002,
D/CIDMapFileReader( 6666): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6666): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6666): Parsing tag category name = system
,I/CustomizationCIDLoader( 6666): Parsing tag category name = application
I/CustomizationCIDLoader( 6666): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6666): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6666): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6666): Parsing tag category name = Settings
,I/CustomizationCIDLoader( 6666): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6666): add string-array item, value = 42507
I/CustomizationCIDLoader( 6666): add string-array item, value = 21902
I/CustomizationCIDLoader( 6666): add string-array item, value = 26006:26001.26002.26003
,I/CustomizationCIDLoader( 6666): add string-array item, value = 23420
I/CustomizationCIDLoader( 6666): add string-array item, value = 22299
I/CustomizationCIDLoader( 6666): add string-array item, value = 24002
I/CustomizationCIDLoader( 6666): add string-array item, value = 23210,
I/CustomizationCIDLoader( 6666): add string-array item, value = 23205
I/CustomizationCIDLoader( 6666): add string-array item, value = 23806
I/CustomizationCIDLoader( 6666): add string-array item, value = 23430
I/CustomizationCIDLoader( 6666): add string-array item, value = 23408,
I/CustomizationCIDLoader( 6666): add string-array item, value = 27205
I/CustomizationCIDLoader( 6666): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6666): add string-array item, value = 21902:C:1:0,
I/CustomizationCIDLoader( 6666): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6666): add string-array item, value = 23420:D:0:0
,I/CustomizationCIDLoader( 6666): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6666): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6666): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6666): add string-array item, value = 23205:D:0:0,
I/CustomizationCIDLoader( 6666): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6666): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6666): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6666): add string-array item, value = 27205:C:1:0
,D/CustomizationManager( 6666):  Read CID file spent 0.066 (s)
D/CustomizationManager( 6666):  All configurations done spent 0.066 (s)
,D/PackageManager(  959): deletePackageAsUser: pkg=com.test.thalitest, pid=6666, uid=2000 userid=0
,I/ActivityManager(  959): Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
,D/Process (  959): killProcessQuiet, pid=6607,
I/ActivityManager(  959): Killing 6607:com.test.thalitest/u0a195 (adj 9): stop com.test.thalitest
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  959): Skipping PackageSetting{399454e9 com.example.hello/10374} due to missing metadata
,I/ActivityManager(  959): Recipient 6607
,D/WifiService(  959): Client connection lost with reason: 4
,E/InputEventReceiver( 1386): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{392bfd58 uid 10195 pid 6607} (c)'
,W/ActivityManager(  959): Spurious death for ProcessRecord{1522e717 6607:com.test.thalitest/u0a195}, curProc for 6607: null,
I/ActivityManager(  959): Force stopping com.test.thalitest appid=10195 user=0: pkg removed
,V/NetworkPolicy(  959): ACTION_UID_REMOVED for uid=10195,
D/DotMatrix( 1328): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1328): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
V/NetworkPolicy(  959): writePolicyLocked()
D/DotMatrix( 1328): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1767): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/PMS     (  959): acquireWL(28beb4ed): PARTIAL_WAKE_LOCK  NetworkStats 0x1 959 1000 null
,W/SystemReader(  959): Cannot find grip_rejection_width, use default value instead
,D/PMS     (  959): acquireWL(1ae4ddb3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1816 10024 WorkSource{10024 com.google.android.gms}
,W/GeofencerStateMachine( 1816): Ignoring removeGeofence because network location is disabled.,
D/PMS     (  959): releaseWL(1ae4ddb3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/InputMethodManagerService(  959): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
V/NetworkPolicy(  959): updateNetworkEnabledLocked()
,V/NetworkPolicy(  959): updateNotificationsLocked()
,D/AccTypeManager( 1767): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/art     ( 5938): Explicit concurrent mark sweep GC freed 9541(577KB) AllocSpace objects, 0(0B) LOS objects, 43% free, 2MB/4MB, paused 332us total 88.568ms
,D/PMS     (  959): releaseWL(28beb4ed): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/[PluginManager]RegisterService( 1517): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,D/VoicemailCleanupService( 1711): Cleaning up data for package: com.test.thalitest
,D/AccTypeManager( 1767): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PhoneApp( 1560): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1517): handle notify Blinkfeed plugin client changed
,W/ResourcesManager(  959): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,E/ExternalAccountType( 1767): Unsupported attribute readOnly,
I/art     ( 1616): Explicit concurrent mark sweep GC freed 92454(5MB) AllocSpace objects, 41(3MB) LOS objects, 34% free, 30MB/46MB, paused 1.477ms total 127.932ms
D/Prism.PackageStateRece_( 1616): action: android.intent.action.PACKAGE_REMOVED,
I/Prism.ItemManager( 1616): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1616): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1616): Deferring update until onResume,
D/Launcher( 1616): waitUntilResume // bindAppsRemoved
,I/ActivityManager(  959): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6686 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/art     (  959): Explicit concurrent mark sweep GC freed 40080(2MB) AllocSpace objects, 9(760KB) LOS objects, 33% free, 16MB/25MB, paused 1.711ms total 204.410ms
,I/art     (  959): WaitForGcToComplete blocked for 184.636ms for cause Explicit
,W/PackageManager(  959): Unable to load service info ResolveInfo{2ba23432 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  959): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  959): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  959): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  959): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  959): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  959): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  959): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  959): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  959): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/JobSchedulerService(  959): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  959): Explicit concurrent mark sweep GC freed 6216(340KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.625ms total 212.901ms
,D/TaskPersister(  959): removeObsoleteFile: deleting file=12_task.xml
,D/StatusBarManagerService(  959): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  959): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  959): hiding MENU key
,D/StatusBarManagerService(  959): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  959): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  959): hiding MENU key
,W/ContextImpl( 6686): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,D/FindExtension( 1616): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1616): Defer allocateBuffers to drawing time
,W/InputMethodManagerService(  959): Got RemoteException sending setActive(false) notification to pid 6607 uid 10195,
D/StatusBarManagerService(  959): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1212): setImeWindowStatus(false,false)
,I/ActivityManager(  959): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6714 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=arm64-v8a
,E/NetworkScheduler.SchedulerReceiver( 1869): Invalid parameter app,
,E/NetworkScheduler.SchedulerReceiver( 1869): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/PMS     (  959): acquireWL(2594d5fd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(2594d5fd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4492): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4492): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 4492): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4492): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 4492): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4492): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  959): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6742 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
I/LocationSettingsChecker( 4492): Removing dialog suppression flag for package com.test.thalitest
I/art     (  444): Explicit concurrent mark sweep GC freed 8667(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 176us total 27.822ms
,D/GOOGLEHELP_CompatibleDatabase( 4492): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4492): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 4492): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4492): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/art     (  444): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 247us total 25.688ms
,D/GOOGLEHELP_CompatibleDatabase( 4492): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4492): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4492): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4492): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 4492): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 4492): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4492): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 4492): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 4492): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/PMS     (  959): acquireWL(1e2c386d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4492 10024 null
I/art     (  444): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 176us total 21.903ms
,I/ConfigService( 1869): onCreate
W/BaseAppContext( 4492): Using Auth Proxy for data requests.
I/ConfigFetchService( 4492): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  959): releaseWL(1e2c386d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,W/BaseAppContext( 4492): Using Auth Proxy for data requests.
,D/PMS     (  959): acquireWL(1966d41c): PARTIAL_WAKE_LOCK  Icing 0x1 4492 10024 WorkSource{10024 com.google.android.gms},
,I/Icing   ( 4492): doRemovePackageData com.test.thalitest,
I/PeopleContactsSync( 4492): CP2 sync disabled
,I/PackageManager(  959):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4492, uid=10024, userID:0
,D/PMS     (  959): releaseWL(1966d41c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/DriveInitializer( 4492): Awaiting to be initialized
,W/DriveInitializer( 4492): Background init thread started
,D/VoldConnector(  959): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.gms/files/},
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
W/ContextImpl( 4492): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,E/SQLiteLog( 4492): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4492): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x556763ee70
,W/DriveInitializer( 4492): Background init thread ended
,E/SQLiteLog( 4492): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4492): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x556763ee70
,E/AndroidRuntime( 4492): FATAL EXCEPTION: Background initialization thread,
E/AndroidRuntime( 4492): Process: com.google.android.gms, PID: 4492
E/AndroidRuntime( 4492): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850),
,E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 4492): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/AndroidRuntime( 4492): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/AndroidRuntime( 4492): 	at com.google.android.gms.drive.database.f.e(SourceFile:804)
E/AndroidRuntime( 4492): 	at com.google.android.gms.drive.events.ao.a(SourceFile:135)
E/AndroidRuntime( 4492): 	at com.google.android.gms.drive.r.run(SourceFile:72)
,E/DriveAsyncService( 4492): disk I/O error (code 3850)
E/DriveAsyncService( 4492): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4492): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4492): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4492): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4492): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4492): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4492): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/DriveAsyncService( 4492): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4492): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 4492): 	,at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4492): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4492): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 4492): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4492): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4492): 	at java.lang.Thread.run(Thread.java:818)
E/ActivityManager(  959): App crashed! Process: com.google.android.gms
D/Process ( 4492): killProcess, pid=4492
,D/Process ( 4492): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  959): Can't write: system_app_crash
E/DropBoxManagerService(  959): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  959): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  959): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  959): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  959): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  959): 	... 5 more
,I/GAv4    ( 6742): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6742):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6742):   adb logcat -s GAv4
,W/GAv4    ( 6742): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6742): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 6742): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 6742): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6742): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,E/SQLiteDatabase( 6742): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6742): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6742): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6742): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6742): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6742): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/SQLiteDatabase( 6742): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6742): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6742): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 6742): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,E/SQLiteDatabase( 6742): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6742): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6742): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6742): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6742): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6742): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6742): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6742): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6742): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6742): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6742): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  959): Recipient 4492
D/WifiService(  959): Client connection lost with reason: 4
I/ActivityManager(  959): Process com.google.android.gms (pid 4492) has died
W/ActivityManager(  959): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
I/ConfigService( 1869): onDestroy
W/ActivityManager(  959): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  959): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
,E/SQLiteDatabase( 6742): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
,E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6742): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6742): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6742): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6742): 	at aen.run(PG:536)
,I/ActivityManager(  959): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=6785 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 6785): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6785): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6785): VM with version 2.1.0 has multidex support
,I/MultiDex( 6785): install
I/MultiDex( 6785): VM has multidex support, MultiDex support library is disabled.
,D/VoldConnector(  959): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 6742): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,D/PMS     (  959): acquireWL(2fb49e20): PARTIAL_WAKE_LOCK  AsyncService 0x1 6092 10167 null
,D/PMS     (  959): releaseWL(2fb49e20): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  959): acquireWL(1c50319e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6092 10167 null
E/SQLiteDatabase( 6742): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6742): 	at aev.getWritableDatabase(PG:238)
,E/SQLiteDatabase( 6742): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6742): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6742): 	at aej.c(PG:139)
E/SQLiteDatabase( 6742): 	at aej.b(PG:398)
E/SQLiteDatabase( 6742): 	at agf.f(PG:417)
E/SQLiteDatabase( 6742): 	at oe.run(PG:1112)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6742): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 6742): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6742): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6742): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6742): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6742): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6742): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6742): 	,at aej.b(PG:398)
E/AbstractDatabaseInstance( 6742): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 6742): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 6742): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 6742): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6742): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 6742): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6742): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  959): releaseWL(1c50319e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5938): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,V/JNIHelp ( 6742): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  959): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6816 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,E/SQLiteLog( 5938): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 5938): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55674cbad0
,E/SQLiteDatabase( 6785): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 6785): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 6785): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6785): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6785): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 6785): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 6785): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 6785): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6785): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6785): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  959): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=6838 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
W/System  ( 6742): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6742): Installed default security provider GmsCore_OpenSSL
E/SharedPreferencesImpl( 5938): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,E/AndroidRuntime( 5938): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5938): Process: com.google.android.googlequicksearchbox:search, PID: 5938
E/AndroidRuntime( 5938): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5938): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5938): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 5938): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5938): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5938): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 5938): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 5938): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 5938): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 5938): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 5938): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 5938): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 5938): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 5938): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 5938): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 5938): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 5938): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 5938): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5938): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5938): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  959): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 5938): killProcess, pid=5938
E/DropBoxManagerService(  959): Can't write: system_app_crash
E/DropBoxManagerService(  959): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  959): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  959): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  959): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  959): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  959): 	... 5 more
D/Process ( 5938): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
E/SQLiteDatabase( 6742): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6742): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6742): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6742): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6742): 	at aej.c(PG:139)
E/SQLiteDatabase( 6742): 	at aej.a(PG:358)
E/SQLiteDatabase( 6742): 	at aej.a(PG:345)
E/SQLiteDatabase( 6742): 	at agf.c(PG:884)
E/SQLiteDatabase( 6742): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 6742): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6742): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6742): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 6742): Failed to query Account133 object
E/AbstractDatabaseInstance( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6742): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6742): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6742): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6742): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6742): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 6742): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 6742): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 6742): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 6742): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 6742): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6742): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6742): 	at java.lang.Thread.run(Thread.java:818)
V/GLSActivity( 1869): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DeviceManagement( 6816): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6816 dbg=false s=true
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
I/DeviceManagement( 6816): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 6816): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
V/JNIHelp ( 6785): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/DeviceManagement( 6816): WorkflowService: Starting workflow service
I/DeviceManagement( 6816): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@25ceef7d] args=[Bundle[mParcelledData.dataSize=112]]
I/DeviceManagement( 6816): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 6816): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 6816): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 6816): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  959): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6868 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
,W/ActivityThread( 6785): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6785): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cf39d30: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6785): Installed default security provider GmsCore_OpenSSL
,I/DeviceManagement( 6816): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 6816): SessionStateController: Checking invariants...
,I/ActivityManager(  959): Recipient 5938,
I/ActivityManager(  959): Process com.google.android.googlequicksearchbox:search (pid 5938) has died
W/ActivityManager(  959): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,W/NativeLibraryUtils( 6785): Failed to open lock file
W/NativeLibraryUtils( 6785): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6785): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 6785): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 6785): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 6785): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6785): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,W/NativeLibraryUtils( 6785): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 6785): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 6785): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 6785): 	... 3 more
,I/GAv4-SVC( 6785): Google Analytics 7.8.99 is starting up.,
,W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6742): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed,
W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 6742): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6742): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6742): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
,E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
,E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 6742): 	at aev.getWritableDatabase(PG:238)
,E/CAKEMIX_CRASHED( 6742): ,	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 6742): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 6742): 	at aen.run(PG:536)
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  959): Killing 5454:com.htc.mediamanager/u0a28 (adj 15): empty #17
,W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 6742): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6742): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6742): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 6742): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 6742): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 6742): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 6742): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 6868): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 6868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6868): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 6868): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 6868): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 6868): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 6868): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 6868): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 6868): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 6868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 6868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6868): 	,at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6868): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6868): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6868): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/CAKEMIX_CRASHED( 6742): java.lang.RuntimeException: An error occured while executing doInBackground()
E/CAKEMIX_CRASHED( 6742): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/CAKEMIX_CRASHED( 6742): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/CAKEMIX_CRASHED( 6742): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/CAKEMIX_CRASHED( 6742): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/CAKEMIX_CRASHED( 6742): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/CAKEMIX_CRASHED( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/CAKEMIX_CRASHED( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/CAKEMIX_CRASHED( 6742): 	at java.lang.Thread.run(Thread.java:818)
E/CAKEMIX_CRASHED( 6742): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 6742): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 6742): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 6742): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 6742): 	at aej.c(PG:139)
E/CAKEMIX_CRASHED( 6742): 	at aej.a(PG:358)
E/CAKEMIX_CRASHED( 6742): 	at aej.a(PG:345)
E/CAKEMIX_CRASHED( 6742): 	at agf.c(PG:884)
,E/CAKEMIX_CRASHED( 6742): 	at aii.doInBackground(PG:1063)
E/CAKEMIX_CRASHED( 6742): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/CAKEMIX_CRASHED( 6742): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/CAKEMIX_CRASHED( 6742): 	... 4 more
,E/SQLiteDatabase( 6785): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6785): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:884)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6785): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.e.k.run(SourceFile:388)
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 6785): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 6785): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 6785): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 6785): 	,at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 6785): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 6785): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 6785): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6785): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6785): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 6785): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 6785): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 6785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 6785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6785): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 6785): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 6785): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 6785): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 6785): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 6785): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 6785): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 6785): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 6785): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 6785): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 6785): 	at java.lang.Thread.run(Thread.java:818)
,E/AndroidRuntime( 6868): FATAL EXCEPTION: main
E/AndroidRuntime( 6868): Process: com.android.documentsui, PID: 6868
E/AndroidRuntime( 6868): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6868): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 6868): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 6868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 6868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6868): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6868): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6868): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6868): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6868): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6868): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 6868): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 6868): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 6868): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 6868): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 6868): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 6868): 	... 9 more
,E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/Process (  959): killProcessQuiet, pid=5454
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/SQLiteOpenHelper( 6785): Opened reminders.db in read-only mode
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 6785): Opening the database failed, dropping the table and recreating it
E/SQLiteDatabase( 6785): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6785): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.jav,a:1280)
E/SQLiteDatabase( 6785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:897)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6785): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.e.k.run(SourceFile:388)
E/GAv4-SVC( 6785): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4-SVC( 6785): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6785): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6785): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 6785): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6785): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6785): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 6785): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 6785): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6785): 	at android.database,.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 6785): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 6785): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6785): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6785): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 6785): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 6785): Process: com.google.android.gms, PID: 6785
E/AndroidRuntime( 6785): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 6785): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 6785): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 6785): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 6785): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 6785): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 6785): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 6785): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6785): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 6785): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 6785): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 6785): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 6785): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 6785): 	... 4 more
E/SQLiteDatabase( 6816): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 6816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 6816): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 6816): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 6816): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 6816): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 6816): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 6816): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 6816): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 6816): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 6816): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 6816): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 6816): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6816): 	at java.lang.Thread.run(Thread.java:818)
,I/Prism.ItemManager( 1616): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1616): loadItems() com.htc.launcher.pageview.WidgetManager@708fed1 +
I/Prism.WidgetManager( 1616): onLoadItems() +
,W/ResourcesManager( 1616): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  959): Recipient 5454,
,E/ActivityManager(  959): App crashed! Process: com.android.documentsui,
E/ActivityManager(  959): App crashed! Process: com.google.android.gms
D/ErrorReport(  959): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  959): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 6742 on display 0,
,I/DeviceManagement( 6816): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(  959): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
,W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,I/DeviceManagement( 6816): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 6816): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 3872): (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10195)] disk I/O error
E/SQLiteDBG( 3872): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.downloads/databases/downloads.db, handle: 0x5567491380
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  959): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  959): 	at libcore.io.Posix.open(Native Method)
W/System.err(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  959): 	... 12 more
,E/SQLiteDatabase( 6816): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 6816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 6816): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 6816): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 6816): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 6816): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 6816): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 6816): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6816): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6816): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 3872): FATAL EXCEPTION: DownloadReceiver
E/AndroidRuntime( 3872): Process: android.process.media, PID: 3872
E/AndroidRuntime( 3872): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 3872): 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
E/AndroidRuntime( 3872): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 3872): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 3872): 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
E/AndroidRuntime( 3872): 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
E/AndroidRuntime( 3872): 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
E/AndroidRuntime( 3872): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 3872): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3872): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 3872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 6816): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@25ceef7d]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/DeviceManagement( 6816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
W/DeviceManagement( 6816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/DeviceManagement( 6816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 6816): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 6816): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO,.java:289)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 6816): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 6816): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 6816): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 6816): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 6816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 6816): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 6816): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  959): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  959): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  959): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
,W/System.err(  959): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  959): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  959): 	at libcore.io.Posix.open(Native Method)
W/System.err(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  959): 	... 14 more
,W/System.err(  959): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  959): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  959): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
,W/System.err(  959): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  959): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  959): 	at libcore.io.Posix.open(Native Method)
W/System.err(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  959): 	... 14 more
,D/Process ( 6742): killProcess, pid=6742
E/DropBoxManagerService(  959): Can't write: system_app_crash
E/DropBoxManagerService(  959): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  959): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  959): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  959): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  959): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  959): 	... 5 more
D/Process ( 6742): vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 6816): WorkflowService: Stopping workflow service
I/ActivityManager(  959): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 6742 on display 0
E/ActivityManager(  959): App crashed! Process: android.process.media
W/OpenGLRenderer( 1616): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,E/JavaBinder(  959): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  959): Exception thrown sending new intent to ActivityRecord{26fa3868 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t13}
W/ActivityManager(  959): android.os.TransactionTooLargeException
W/ActivityManager(  959): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  959): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  959): 	at android.app.ApplicationThreadProxy.scheduleNewIntent(ApplicationThreadNative.java:890)
W/ActivityManager(  959): 	at com.android.server.am.ActivityRecord.deliverNewIntentLocked(ActivityRecord.java:660)
W/ActivityManager(  959): 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLockedImpl(ActivityStackSupervisor.java:2027)
W/ActivityManager(  959): 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLocked(ActivityStackSupervisor.java:1648)
W/ActivityManager(  959): 	at com.android.server.am.ActivityStackSupervisor.startActivityLocked(ActivityStackSupervisor.java:1557)
W/ActivityManager(  959): 	at com.android.server.am.ActivityStackSupervisor.startActivityMayWait(ActivityStackSupervisor.java:972)
W/ActivityManager(  959): 	at com.android.server.am.ActivityManagerService.startActivityAsUser(ActivityManagerService.java:3757)
W/ActivityManager(  959): 	at com.android.server.am.ActivityManagerService.startActivity(ActivityManagerService.java:3744)
W/ActivityManager(  959): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:145)
W/ActivityManager(  959): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/ActivityManager(  959): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  959): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
E/ErrorReport(  959): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  959): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457941995402.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  959): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  959): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  959): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  959): 	... 4 more
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
D/ErrorReport(  959): HtcErrorReportManager Begin---add error logs to dropbox
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,W/System.err(  959): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  959): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  959): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  959): 	at libcore.io.Posix.open(Native Method)
W/System.err(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  959): 	... 12 more
W/System.err(  959): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  959): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  959): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  959): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  959): 	at libcore.io.Posix.open(Native Method)
W/System.err(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  959): 	... 14 more
W/System.err(  959): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  959): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  959): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  959): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  959): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  959): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  959): 	at libcore.io.Posix.open(Native Method)
W/System.err(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  959): 	... 14 more
,I/ActivityManager(  959): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=6904 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a
,D/Process ( 6785): killProcess, pid=6785
,D/Process ( 6785): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
D/Process ( 6868): killProcess, pid=6868
D/Process ( 3872): killProcess, pid=3872
D/Process ( 3872): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/Process ( 6868): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 ,
E/ErrorReport(  959): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  959): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457941995441.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  959): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  959): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  959): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  959): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  959): 	... 4 more
E/lowmemorykiller(  383): Error writing /proc/3872/oom_score_adj; errno=22
I/ActivityManager(  959): Killing 6401:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  959): killProcessQuiet, pid=6401
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 1616): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  959): Recipient 6742
,I/ActivityManager(  959): Recipient 6868,
,I/ActivityManager(  959): Recipient 3872
,I/ActivityManager(  959): Recipient 6785
,I/ActivityManager(  959): Recipient 6401
,W/asset   ( 1616): Copying FileAsset 0x5567a1dae0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,

```
