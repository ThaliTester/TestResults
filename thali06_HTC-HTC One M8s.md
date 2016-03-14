#### Test 6262501074dad8f_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  988): acquireWL(3a1c5539): PARTIAL_WAKE_LOCK  *alarm* 0x1 988 1000 WorkSource{1000}
V/AlarmManager(  988): sending alarm PendingIntent{31dd77e: PendingIntentRecord{14d154df android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457995225361, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{2877452c: PendingIntentRecord{3de40bf5 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192033, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{a3bed8a: PendingIntentRecord{20a05ffb android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202312, Int=0
D/PMS     (  988): acquireWL(38a98818): PARTIAL_WAKE_LOCK  *backup* 0x1 988 1000 null
W/BackupManagerService(  988): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  988): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  988): releaseWL(38a98818): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  988): acquireWL(22367271): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(3a1c5539): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/PMS     (  988): acquireWL(1c735856): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(22367271): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
--------- beginning of main
V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  988): releaseWL(1c735856): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(2d3d4230): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(2d3d4230): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(e5ffea9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(e5ffea9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(3e2d1c2e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(315f33cf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(10dc65): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(3e2d1c2e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/VacuumService( 1892): Vacuum at: now=1457995258428 tag=VacuumService
D/PMS     (  988): releaseWL(315f33cf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/GoogleURLConnFactory( 1892): Using platform SSLCertificateSocketFactory
E/cutils-trace( 6580): Error opening trace file: Permission denied (13)
D/PMS     (  988): acquireWL(2d77331d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(2d77331d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(12c1c992): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(12c1c992): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/CustomizationManager( 6580): ====startRecUseTime====
D/htc.customization.log.level( 6580):  is 
W/CustomizationLogLevel( 6580): Level value is invalid, use default level 2
D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1892): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1892): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1892): [NET] android_getaddrinfo_proxy+
D/libc    ( 1892): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1892): [NET] android_getaddrinfo_proxy-, success
D/CustomizationManager( 6580):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 6580): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6580): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6580): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6580): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6580): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6580): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6580): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6580): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6580): Parsing tag category name = system
I/CustomizationCIDLoader( 6580): Parsing tag category name = application
I/CustomizationCIDLoader( 6580): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6580): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6580): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6580): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6580): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6580): add string-array item, value = 42507
I/CustomizationCIDLoader( 6580): add string-array item, value = 21902
I/CustomizationCIDLoader( 6580): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6580): add string-array item, value = 23420
I/CustomizationCIDLoader( 6580): add string-array item, value = 22299
I/CustomizationCIDLoader( 6580): add string-array item, value = 24002
I/CustomizationCIDLoader( 6580): add string-array item, value = 23210
I/CustomizationCIDLoader( 6580): add string-array item, value = 23205
I/CustomizationCIDLoader( 6580): add string-array item, value = 23806
I/CustomizationCIDLoader( 6580): add string-array item, value = 23430
I/CustomizationCIDLoader( 6580): add string-array item, value = 23408
I/CustomizationCIDLoader( 6580): add string-array item, value = 27205
I/CustomizationCIDLoader( 6580): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6580): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6580):  Read CID file spent 0.101 (s)
D/CustomizationManager( 6580):  All configurations done spent 0.101 (s)
I/ActivityManager(  988): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6580 on display 0
D/PMS     (  988): acquireHCC(2b94c98c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 988 1000 null
D/PMS     (  988): acquireHCC(120aa8d5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 988 1000 null
D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1892): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1892): [NET] android_getaddrinfofornet-, err=8
W/asset   (  988): Copying FileAsset 0x5576ecf790 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  988): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6607 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  450): Explicit concurrent mark sweep GC freed 8672(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 233us total 18.572ms
V/ActivityManager(  988): Display changed displayId=0
D/DotMatrix( 1329): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1329): [EventService] mbHDMIConnect: false, mCoverOn:false
I/art     (  450): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 221us total 14.289ms
I/art     (  450): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 216us total 14.135ms
W/asset   ( 6607): Copying FileAsset 0xabfa3830 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1510): [trimMemory] 20
I/WebViewFactory( 6607): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6607): Time to load native libraries: 10 ms (timestamps 3174-3184),
,I/LibraryLoader( 6607): Expected native library version number "",actual native library version number "",
,D/PMS     (  988): acquireWL(dd9fd51): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
V/WebViewChromiumFactoryProvider( 6607): Binding Chromium to main looper Looper (main, tid 1) {3ef83378}
I/LibraryLoader( 6607): Expected native library version number "",actual native library version number ""
,I/chromium( 6607): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6607): Initializing chromium process, singleProcess=true,
,W/art     ( 6607): Attempt to remove local handle scope entry from IRT, ignoring
D/PMS     (  988): acquireWL(13e9b6b7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,E/SysUtils( 6607): ApplicationContext is null in ApplicationStatus
,D/PMS     (  988): releaseWL(dd9fd51): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1892): Using platform SSLCertificateSocketFactory
,W/Uploader( 1892): No account for auth token provided
,D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1892): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1892): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1892): [NET] android_getaddrinfo_proxy+
D/libc    ( 1892): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/chromium( 6607): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6607): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6607): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6607): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6607): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6607): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6607): Local Branch: 
I/Adreno-EGL( 6607): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6607): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6607):                  d74aa161a12b9c6fc6332151
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1892): [NET] android_getaddrinfo_proxy-, success
,I/PhenotypeFlagCommitter( 1892): Experiment Configs successfully retrieved for com.google.android.gms.phenotype,
,W/System.err(  988): java.lang.Throwable: stack dump
D/BluetoothManagerService(  988): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  988): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba3adbc:true
W/System.err(  988): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  988): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  988): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  988): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6607): 599825037: getState(). Returning 12
,D/PMS     (  988): releaseWL(10dc65): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): acquireWL(2f087145): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,W/art     ( 6607): Attempt to remove local handle scope entry from IRT, ignoring
,D/PMS     (  988): releaseWL(2f087145): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): acquireWL(34826b43): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(34826b43): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
W/AwContents( 6607): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6607): CordovaWebView is running on device made by: HTC,
,W/art     ( 6607): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6607): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  988): Activity pause timeout for ActivityRecord{17b8f8ea u0 com.test.thalitest/.MainActivity t12},
W/HtcSystemUPManager(  988): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6607): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1892): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1892): [NET] android_getaddrinfofornet-, err=8
D/StatusBarManagerService(  988): setSystemUiVisibility(0xc0000600)
D/StatusBarManagerService(  988): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  988): hiding MENU key
D/StatusBarManagerService(  988): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  988): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  988): hiding MENU key
,D/FindExtension( 6607): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,W/Uploader( 1892): No account for auth token provided
,I/InputMethodManager( 6607): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@208eeff9, mServedView=org.apache.cordova.engine.SystemWebView{3d903b3e VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@386a4d9f
,I/PhoneStatusBar( 1242): setImeWindowStatus(false,false)
I/InputMethodManagerService(  988): Disable input method client, pid=1510
D/StatusBarManagerService(  988): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6607): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  988): Displayed com.test.thalitest/.MainActivity: +681ms (total +726ms)
,W/BindingManager( 6607): Cannot call determinedVisibility() - never saw a connection for the pid: 6607,
,W/Uploader( 1892): No account for auth token provided,
,D/JsMessageQueue( 6607): Set native->JS mode to OnlineEventsBridgeMode
,W/Uploader( 1892):  no longer exists, so no auth token.
,D/jxcore_app_log( 6607): JniHelper::setJavaVM(0xaae378f8), pthread_self() = -1407843216
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6607): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13407033 added. We now have 1 listener(s)
D/BluetoothManagerService(  988): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6607): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6607): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
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
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1edfefee added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6607): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  988): New client listening to asynchronous messages,
E/WifiTrafficPoller(  988): ADD_CLIENT: 8
,D/BluetoothAdapter( 6607): 599825037: getState(). Returning 12
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6607): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6607): setScanMode: 1 -> 2
,D/BluetoothAdapter( 6607): 599825037: getState(). Returning 12
,W/Uploader( 1892): No account for auth token provided,
,I/chromium( 6607): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  988): releaseWL(13e9b6b7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): acquireWL(2118dc97): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(2118dc97): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): acquireWL(1e961e84): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(1e961e84): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/jxcore-log( 6607): Initializing JXcore engine
,W/jxcore-log( 6607): JXcore engine is ready
,W/jxcore-log( 6607): Starting JXcore engine,
,W/jxcore-log( 6607): Platform android,
W/jxcore-log( 6607): 
W/jxcore-log( 6607): Process ARCH arm
W/jxcore-log( 6607): 
,D/PMS     (  988): releaseHCC(2b94c98c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  988): releaseHCC(120aa8d5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6607): JXcore Cordova bridge is ready!,
I/jxcore-log( 6607): 
W/jxcore-log( 6607): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6607): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 6607): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6607): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6607): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,W/PluginManager( 6607): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 24ms. Plugin should use CordovaInterface.getThreadPool().,
,D/Process (  988): killProcessQuiet, pid=5641,
,I/ActivityManager(  988): Killing 5641:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  988): Recipient 5641
,D/HtcUPManager( 1242): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1242): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1591): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3a47fe4
I/ActivityManager(  988): Killing 5484:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  988): killProcessQuiet, pid=5484
,D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  988): Recipient 5484,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  988): acquireWL(214f666d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null,
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(214f666d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1242): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  988): plugged=true pluggin=true
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  988): BroadcastReceiver::onReceive-
,D/WifiController(  988): handleMessage: E msg.what=155652
,D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: DeviceActiveState
D/HtcPowerSaver(  988): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  988): runPSCheck
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X,
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  988): acquireWL(55202a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null,
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(55202a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  988): updateBatteryInfo
,D/NotificationService(  988): plugged=true pluggin=true
,D/UsbnetService(  988): BroadcastReceiver::onReceive+,
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  988): Checking...
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/HtcPowerSaver(  988): >> updateStatus
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/WifiController(  988): battery changed pluggedType: 2,
D/WifiController(  988): handleMessage: E msg.what=155652
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  988): processMsg: DeviceActiveState
I/HtcPowerSaver(  988): << updateStatus
D/WifiController(  988): processMsg: StaEnabledState
D/PowerUI ( 1242): closing low battery warning: level=100
D/WifiController(  988): processMsg: DefaultState
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): handleMessage: X
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1357): wlan0: BSS: Remove id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 5 BSSID 00:1f:27:54:dd:eb SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 6 BSSID 00:1f:27:54:dd:e0 SSID '\x00' due to wpa_bss_flush_by_age
,D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e]
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:dd:e4 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 14 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 15 BSSID 00:1f:27:54:e0:44 SSID '\x00' due to wpa_bss_flush_by_age
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 12 BSSID 00:22:0d:46:1c:a4 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 8 BSSID 62:45:b0:73:93:45 SSID '' due to wpa_bss_flush_by_age
,D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 9 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:ef]
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 10 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:ef
D/wpa_supplicant( 1357): wlan0: BSS: Remove id 11 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:eb]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:eb,
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e0]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e0
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:dd:e4]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:dd:e4
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 00:16:a6:1f:06:5c]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 00:16:a6:1f:06:5c
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 00:1f:27:54:e0:44]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 15 00:1f:27:54:e0:44
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:22:0d:46:1c:a4]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:22:0d:46:1c:a4
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 62:45:b0:73:93:45]
,E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 62:45:b0:73:93:45
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:dd:e3]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:dd:e3
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:22:0d:46:1c:a3]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:22:0d:46:1c:a3
D/WifiMonitor(  988): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:1f:27:54:e0:43]
E/WifiMonitor(  988): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:1f:27:54:e0:43
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  988): acquireWL(2c04ab33): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000},
V/AlarmManager(  988): sending alarm PendingIntent{28faef6d: PendingIntentRecord{31957a2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=204128, Int=0
,V/AlarmManager(  988): sending alarm PendingIntent{2d08fc69: PendingIntentRecord{bf1a6ee com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457995398310, Int=0
D/PMS     (  988): releaseWL(2c04ab33): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1242): Weather sync is On
W/WeatherTimeKeeper( 1242): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1892): Explicit concurrent mark sweep GC freed 34400(1890KB) AllocSpace objects, 9(520KB) LOS objects, 46% free, 4MB/8MB, paused 1.329ms total 85.115ms
,I/GLSUser ( 1892): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1892): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1892): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1892): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1242): reapply : com.google.android.gms 2 40,
,W/GLSActivity( 1892): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1892): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1892): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1892): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1892): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1892): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1892): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6002): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6002): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6002): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6002): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6002): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6002): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6002): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6002): Ignoring header User-Agent because its value was null.
,D/libc    ( 6002): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6002): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6002): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6002): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6002): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6002): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6002): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  988): acquireWL(263cb27f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(263cb27f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/WifiController(  988): battery changed pluggedType: 2
,D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
,D/HtcPowerSaver(  988): updateBatteryInfo
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  988): << updateStatus
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
D/PowerUI ( 1242): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  988): acquireWL(1374e24c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
,D/PMS     (  988): releaseWL(1374e24c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/WifiController(  988): battery changed pluggedType: 2
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/PowerUI ( 1242): closing low battery warning: level=100
D/WifiController(  988): handleMessage: E msg.what=155652
D/PMS     (  988): runPSCheck
D/WifiController(  988): processMsg: DeviceActiveState
D/HtcPowerSaver(  988): Checking...
D/WifiController(  988): processMsg: StaEnabledState
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): processMsg: DefaultState
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): handleMessage: X
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/PMS     (  988): acquireWL(387fb295): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
D/UsbnetService(  988): onReceive BATTERY_CHANGED
I/BatteryService(  988): n_update end
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  988): releaseWL(387fb295): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/NotificationService(  988): plugged=true pluggin=true
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: DeviceActiveState
D/HtcPowerSaver(  988): updateBatteryInfo
D/WifiController(  988): processMsg: StaEnabledState
D/PMS     (  988): runPSCheck
D/WifiController(  988): processMsg: DefaultState
D/HtcPowerSaver(  988): Checking...
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): handleMessage: X
D/PowerUI ( 1242): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1455): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1455): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1455): sku_id=118
D/ContactMessageStore( 1455): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1455): start background delete task...
,D/ContactMessageStore( 1455): size: 0 , 0
,D/ContactMessageStore( 1455): Background delete complete
,D/PMS     (  988): acquireWL(2b069faa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
D/UsbnetService(  988): BroadcastReceiver::onReceive+
I/BatteryService(  988): n_update end
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/PMS     (  988): releaseWL(2b069faa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  988): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  988): runPSCheck
D/WifiController(  988): handleMessage: E msg.what=155652
D/HtcPowerSaver(  988): Checking...
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
D/PowerUI ( 1242): closing low battery warning: level=100
D/WifiController(  988): processMsg: DefaultState
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): handleMessage: X
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  988): acquireWL(3df3f79b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000},
V/AlarmManager(  988): sending alarm PendingIntent{28faef6d: PendingIntentRecord{31957a2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=384128, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{1333d738: PendingIntentRecord{25f5e311 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=942200, Int=0
,I/bt-btm  ( 3163): Received oneshot timer event complete
I/bt-btm  ( 3163): btm_ble_timeout
I/bt-btm  ( 3163): btm_gen_resolvable_private_addr
,D/PMS     (  988): acquireWL(5070c76): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3163 1002 null
,D/bt-btm  ( 3163): btm_ble_rand_enc_complete,
D/PMS     (  988): releaseWL(3df3f79b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
I/bt-btm  ( 3163): btm_gen_resolve_paddr_low
D/bt-smp  ( 3163): smp_encrypt_data
W/bt-smp  ( 3163): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3163): Plain text(LSB ~ MSB) = d7 e3 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3163): Encrypted text(LSB ~ MSB) = 55 63 a2 3a 3f eb 4a e7 01 00 d2 3f af 2e 4e 3b 
I/bt-btm  ( 3163): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3163): Stopping oneshot timer,
D/bt-btm  ( 3163): Starting oneshot timer type:103 timeout:900s
D/WeatherUtility( 1242): Weather sync is On
W/WeatherTimeKeeper( 1242): [refreshWeatherData] no weather data
,D/PMS     (  988): releaseWL(5070c76): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  988): acquireWL(23107277): PARTIAL_WAKE_LOCK  *alarm* 0x1 988 1000 WorkSource{10024}
V/AlarmManager(  988): sending alarm PendingIntent{2feb2ee4: PendingIntentRecord{37c49f4d com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457995507821, Int=1800000
,V/AlarmManager(  988): sending alarm PendingIntent{29cf7a02: PendingIntentRecord{240fbf13 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=938653, Int=0
,D/PMS     (  988): acquireWL(29e5550): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4486 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  988): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6676 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  988): sending alarm PendingIntent{2748e349: PendingIntentRecord{2bf344e com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457995718267, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{388a64cf: PendingIntentRecord{4be2e5c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805880, Int=0
,V/AlarmManager(  988): sending alarm PendingIntent{2f1b767c: PendingIntentRecord{245fdba com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457996024043, Int=0
,D/PMS     (  988): acquireWL(cb36b05): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(cb36b05): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(1dde475a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4486 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(29e5550): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6493): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  988): releaseWL(23107277): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6493): MY_DEBUG = false
,D/PowerUsageService( 6493): repeat time = 1457996924125
,I/EventLogService( 4486): Aggregate from 1457995155019 (log), 1457993707777 (data)
,D/PMS     (  988): acquireWL(18ea1914): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1892): Message class com.google.f.a.a.i
,D/PMS     (  988): releaseWL(18ea1914): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  988): releaseWL(1dde475a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,D/StatusBarManagerService(  988): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  988): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  988): hiding MENU key
,D/StatusBarManagerService(  988): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  988): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  988): hiding MENU key
,D/FindExtension( 1510): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1510): Defer allocateBuffers to drawing time,
I/InputMethodManagerService(  988): Disable input method client, pid=6607
,D/StatusBarManagerService(  988): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6607): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6607): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6607): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1242): setImeWindowStatus(false,false)
,I/PowerUsageList:PowerUsageHelper( 6493): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6493): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6493): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 6493): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 6700): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6700): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6700): dex2oat: override thread count:4
,I/dex2oat ( 6700): dex2oat took 798.765ms (threads: 4),
,I/PushClient( 6676): ApplicationMonitor {2b390f24}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
I/PushClient( 6676): ApplicationMonitor {2b390f24}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6676): ApplicationMonitor {2b390f24}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6676): ApplicationMonitor {2b390f24}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6676): ApplicationMonitor {2b390f24}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6676): ApplicationMonitor {2b390f24}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6676): ApplicationMonitor {2b390f24}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6676): ApplicationMonitor {2b390f24}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6676): ApplicationMonitor {2b390f24}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/PushClient( 6676): PnsModel {13e4abb7}: update(): Update registration caused by: alarm
,I/PushClient( 6676): PnsConfigModel {39e2c99a}: <init>(): Use dm-client for provisioning.
,W/System.err( 6676): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 6676): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6676): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6676): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  988): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6707 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6707): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6707 dbg=false s=true,
,I/DeviceManagement( 6707): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6707): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
I/DeviceManagement( 6707): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6707): WorkflowService: Starting workflow service
,I/DeviceManagement( 6707): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@362caa51] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6707): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6707): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6707): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6707): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6707): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6707): SessionStateController: Checking invariants...
,I/DeviceManagement( 6707): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6707): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@362caa51],
,I/DeviceManagement( 6707): WorkflowService: Stopping workflow service,
,I/ActivityManager(  988): Killing 6401:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  988): killProcessQuiet, pid=6401
,D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  988): Recipient 6401
,I/PushClient( 6676): PnsModel {13e4abb7}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  988): killProcessQuiet, pid=6356
,I/ActivityManager(  988): Killing 6356:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  988): Recipient 6356,
,D/PMS     (  988): acquireWL(322b5198): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
,V/AlarmManager(  988): sending alarm PendingIntent{28faef6d: PendingIntentRecord{31957a2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=984127, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{2de3df1: PendingIntentRecord{8e5fdd6 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457996070515, Int=0
,D/SmartSyncUtils( 6493): isEpsOn(), nState = 0
,D/WeatherUtility( 1242): Weather sync is On
,W/WeatherTimeKeeper( 1242): [refreshWeatherData] no weather data
,I/art     (  988): Explicit concurrent mark sweep GC freed 33736(1891KB) AllocSpace objects, 9(784KB) LOS objects, 33% free, 16MB/24MB, paused 1.756ms total 193.633ms,
D/PMS     (  988): acquireWL(6c87857): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6493 1000 null
D/PMS     (  988): releaseWL(322b5198): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6493): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6493): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6493): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6493): SettingOnTime = 1458021600000, randomSettingOnTime = 1458020874000
,D/SmartSyncScreenOnOffTimeReceiver( 6493): SettingOffTime = 1458000000000, randomSettingOffTime = 1458000594000
,D/SmartSyncScreenOnOffTimeReceiver( 6493): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6493): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6493): bNightModeTurnOffOnce = false
,D/PMS     (  988): releaseWL(6c87857): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  988): acquireWL(224fef44): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
,I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(224fef44): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): Checking...
D/WifiController(  988): handleMessage: E msg.what=155652
I/HtcPowerSaver(  988): >> updateStatus
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1242): closing low battery warning: level=100
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  988): acquireWL(987c82d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
I/BatteryService(  988): n_update end
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  988): releaseWL(987c82d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1242): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/PMS     (  988): runPSCheck
D/WifiController(  988): handleMessage: E msg.what=155652
D/HtcPowerSaver(  988): Checking...
D/WifiController(  988): processMsg: DeviceActiveState
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  988): acquireWL(2d9c2162): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
D/UsbnetService(  988): BroadcastReceiver::onReceive+
I/BatteryService(  988): n_update end
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/PMS     (  988): releaseWL(2d9c2162): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/NotificationService(  988): plugged=true pluggin=true
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: DeviceActiveState
D/HtcPowerSaver(  988): updateBatteryInfo
D/WifiController(  988): processMsg: StaEnabledState
D/PMS     (  988): runPSCheck
D/WifiController(  988): processMsg: DefaultState
D/HtcPowerSaver(  988): Checking...
,D/WifiController(  988): handleMessage: X
I/HtcPowerSaver(  988): >> updateStatus
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1242): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  988): << updateStatus
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  988): acquireWL(317242f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
D/UsbnetService(  988): BroadcastReceiver::onReceive+
I/BatteryService(  988): n_update end
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/PMS     (  988): releaseWL(317242f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/NotificationService(  988): plugged=true pluggin=true
D/WifiController(  988): handleMessage: E msg.what=155652
D/HtcPowerSaver(  988): updateBatteryInfo
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
D/PowerUI ( 1242): closing low battery warning: level=100
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
,D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  988): runPSCheck
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  988): User[0] Flushing usage stats to disk
,D/PMS     (  988): acquireWL(18febbb0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000},
V/AlarmManager(  988): sending alarm PendingIntent{28faef6d: PendingIntentRecord{31957a2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1044128, Int=0
V/AlarmManager(  988): sending alarm PendingIntent{1bc5ba29: PendingIntentRecord{369ef1ae com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_UPDATE_GOLDEN_TABLE, t=0, cnt=1, w=1457996400000, Int=0
,V/AlarmManager(  988): sending alarm PendingIntent{9e41b4f: PendingIntentRecord{248be2dc com.google.android.gms broadcastIntent}}, i=com.google.android.gms.reminders.REFRESH_NOTIFICATION, t=0, cnt=1, w=1457996400000, Int=0
,V/AlarmManager(  988): sending alarm PendingIntent{d6cfe5: PendingIntentRecord{3eec7aba com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1457996400000, Int=0
,D/PMS     (  988): acquireWL(3df11d6b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6493 1000 null
D/WeatherUtility( 1242): Weather sync is On
,W/WeatherTimeKeeper( 1242): [refreshWeatherData] no weather data
,D/PMS     (  988): acquireWL(3b298561): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4486 10024 null
,I/FeedHostManager( 1510): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
,D/PMS     (  988): acquireWL(21578886): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4486 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): acquireWL(3b822547): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1510 10074 null
D/PMS     (  988): releaseWL(3b822547): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/PMS     (  988): releaseWL(3b298561): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  988): releaseWL(18febbb0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10074}
,D/PMS     (  988): releaseWL(21578886): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,D/ContactMessageStore( 1455): notify MmsSms
D/AccFlag ( 1455): sense_version=6.0
D/AccFlag ( 1455): sku_id=118
D/TelephUtils( 1455): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1455): sku_id=118
,D/TelephUtils( 1455): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1455): sku_id=118
,D/TelephUtils( 1455): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 95,
D/AccFlag ( 1455): sku_id=118
,D/TelephUtils( 1455): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65,
D/AccFlag ( 1455): sku_id=118
,D/PMS     (  988): acquireWL(34d070e0): PARTIAL_WAKE_LOCK  Icing 0x1 4486 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  988): releaseWL(34d070e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  988): acquireWL(f01225e): PARTIAL_WAKE_LOCK  Icing 0x1 4486 10024 WorkSource{10024 com.google.android.gms},
,D/TelephUtils( 1455): QUERY for  <hidden uri>  [ com.android.phone ] tid: 56
,I/ActivityManager(  988): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=6740 uid=10035 gids={50035, 9997} abi=arm64-v8a
,D/SMSBackup( 6429): Got a database change event,
,I/Icing   ( 4486): Indexing 45DF604A3178D15E8C0610E8DC9A22B2315E4983 from com.google.android.gms
,I/Icing   ( 4486): Indexing done 45DF604A3178D15E8C0610E8DC9A22B2315E4983
,D/PMS     (  988): releaseWL(f01225e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  988): Killing 4583:com.google.android.talk/u0a112 (adj 15): empty #17
,D/Process (  988): killProcessQuiet, pid=4583
D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  988): Recipient 4583
,D/PMS     (  988): releaseWL(3df11d6b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  988): acquireWL(19b8375b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  988): n_update end
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  988): releaseWL(19b8375b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
D/PowerUI ( 1242): closing low battery warning: level=100
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
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
D/WifiController(  988): handleMessage: X
,D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  988): acquireWL(3faf7bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
I/BatteryService(  988): n_update end
D/PMS     (  988): releaseWL(3faf7bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  988): runPSCheck,
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
,D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  988): << updateStatus
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1242): closing low battery warning: level=100
D/WifiController(  988): handleMessage: E msg.what=155652
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
D/WifiController(  988): processMsg: DefaultState
D/WifiController(  988): handleMessage: X
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  988): acquireWL(2f4d88d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  988): n_update end
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  988): releaseWL(2f4d88d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1242): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1242): closing low battery warning: level=100
D/HeadsetStateMachine( 3163): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  988): updateBatteryInfo
D/UsbnetService(  988): BroadcastReceiver::onReceive+
D/PowerUI ( 1242): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  988): onReceive BATTERY_CHANGED
D/NotificationService(  988): plugged=true pluggin=true
D/UsbnetService(  988):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  988): runPSCheck
D/UsbnetService(  988): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  988): Checking...
I/HtcPowerSaver(  988): >> updateStatus
D/WifiController(  988): handleMessage: E msg.what=155652
D/WifiController(  988): processMsg: DeviceActiveState
D/WifiController(  988): battery changed pluggedType: 2
D/WifiController(  988): processMsg: StaEnabledState
,I/HtcPowerSaver(  988): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  988): processMsg: DefaultState
I/HtcPowerSaver(  988): << updateStatus
D/WifiController(  988): handleMessage: X
,I/BatteryController( 1242): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1400000ms),E/cutils-trace( 6764): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6764): ====startRecUseTime====
D/htc.customization.log.level( 6764):  is 
W/CustomizationLogLevel( 6764): Level value is invalid, use default level 2
D/CustomizationManager( 6764):  Read ACC file spent 0.045 (s)
D/CIDMapFileReader( 6764): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6764): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6764): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6764): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6764): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6764): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6764): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6764): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6764): Parsing tag category name = system
I/CustomizationCIDLoader( 6764): Parsing tag category name = application
I/CustomizationCIDLoader( 6764): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6764): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6764): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6764): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6764): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6764): add string-array item, value = 42507
I/CustomizationCIDLoader( 6764): add string-array item, value = 21902
I/CustomizationCIDLoader( 6764): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6764): add string-array item, value = 23420
I/CustomizationCIDLoader( 6764): add string-array item, value = 22299
I/CustomizationCIDLoader( 6764): add string-array item, value = 24002
I/CustomizationCIDLoader( 6764): add string-array item, value = 23210
I/CustomizationCIDLoader( 6764): add string-array item, value = 23205
I/CustomizationCIDLoader( 6764): add string-array item, value = 23806
I/CustomizationCIDLoader( 6764): add string-array item, value = 23430
I/CustomizationCIDLoader( 6764): add string-array item, value = 23408
I/CustomizationCIDLoader( 6764): add string-array item, value = 27205
I/CustomizationCIDLoader( 6764): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6764): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6764):  Read CID file spent 0.091 (s)
D/CustomizationManager( 6764):  All configurations done spent 0.091 (s)
D/PackageManager(  988): deletePackageAsUser: pkg=com.test.thalitest, pid=6764, uid=2000 userid=0
D/Process (  988): killProcessQuiet, pid=6607
I/ActivityManager(  988): Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
I/ActivityManager(  988): Killing 6607:com.test.thalitest/u0a195 (adj 11): stop com.test.thalitest
W/PackageSettings(  988): Skipping PackageSetting{29226da7 com.example.hello/10374} due to missing metadata
I/ActivityManager(  988): Recipient 6607
D/WifiService(  988): Client connection lost with reason: 4
E/InputEventReceiver( 1397): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{28e44b16 uid 10195 pid 6607} (c)'
I/ActivityManager(  988): Force stopping com.test.thalitest appid=10195 user=0: pkg removed
W/ActivityManager(  988): Spurious death for ProcessRecord{26591f36 6607:com.test.thalitest/u0a195}, curProc for 6607: null
D/PMS     (  988): acquireWL(1538ee37): PARTIAL_WAKE_LOCK  NetworkStats 0x1 988 1000 null
V/NetworkPolicy(  988): ACTION_UID_REMOVED for uid=10195
W/GeofencerStateMachine( 1829): Ignoring removeGeofence because network location is disabled.
D/PMS     (  988): acquireWL(175c5fa4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1329): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/PMS     (  988): releaseWL(175c5fa4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1329): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/SystemReader(  988): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1756): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/AccTypeManager( 1756): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/art     ( 5928): Explicit concurrent mark sweep GC freed 9581(578KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 302us total 111.015ms
D/PhoneApp( 1455): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1591): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/PMS     (  988): releaseWL(1538ee37): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  988): writePolicyLocked()
D/VoicemailCleanupService( 1721): Cleaning up data for package: com.test.thalitest
V/NetworkPolicy(  988): updateNetworkEnabledLocked()
V/NetworkPolicy(  988): updateNotificationsLocked()
D/AccTypeManager( 1756): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1591): handle notify Blinkfeed plugin client changed
I/art     ( 1510): Explicit concurrent mark sweep GC freed 17515(1201KB) AllocSpace objects, 17(820KB) LOS objects, 34% free, 30MB/46MB, paused 1.342ms total 139.505ms
E/ExternalAccountType( 1756): Unsupported attribute readOnly
D/Prism.PackageStateRece_( 1510): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1510): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1510): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1510): Deferring update until onResume
D/Launcher( 1510): waitUntilResume // bindAppsRemoved
I/ActivityManager(  988): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6784 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/art     (  445): Explicit concurrent mark sweep GC freed 8654(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 166us total 21.345ms
I/InputMethodManagerService(  988): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/art     (  445): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 133us total 17.452ms
W/ResourcesManager(  988): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     (  445): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 144us total 17.582ms
I/art     (  988): Explicit concurrent mark sweep GC freed 43467(2MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 16MB/24MB, paused 2.760ms total 246.940ms
I/art     (  988): WaitForGcToComplete blocked for 241.687ms for cause Explicit
W/ContextImpl( 6784): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
W/PackageManager(  988): Unable to load service info ResolveInfo{35cfb5d2 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  988): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  988): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  988): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  988): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  988): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  988): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  988): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  988): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  988): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  988): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/NetworkScheduler.SchedulerReceiver( 1892): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1892): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  988): acquireWL(beb3530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  988): releaseWL(beb3530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/JobSchedulerService(  988): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  988): removeObsoleteFile: deleting file=12_task.xml
D/ChimeraCfgMgr( 4486): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4486): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 4486): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4486): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4486): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4486): Module APK com.google.android.play.games already loaded
I/art     (  988): Explicit concurrent mark sweep GC freed 7232(386KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.444ms total 250.305ms
I/ActivityManager(  988): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6816 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
I/LocationSettingsChecker( 4486): Removing dialog suppression flag for package com.test.thalitest
W/asset   (  988): Copying FileAsset 0x5576fc6e30 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/GOOGLEHELP_CompatibleDatabase( 4486): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4486): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4486): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4486): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4486): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4486): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4486): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4486): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4486): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4486): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4486): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4486): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4486): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/PMS     (  988): acquireWL(1cb01451): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4486 10024 null
I/ActivityManager(  988): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6842 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=arm64-v8a
I/ConfigFetchService( 4486): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigService( 1892): onCreate
D/PMS     (  988): releaseWL(1cb01451): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
W/BaseAppContext( 4486): Using Auth Proxy for data requests.
I/PeopleContactsSync( 4486): CP2 sync disabled
D/PMS     (  988): acquireWL(b96748e): PARTIAL_WAKE_LOCK  Icing 0x1 4486 10024 WorkSource{10024 com.google.android.gms}
I/PackageManager(  988):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4486, uid=10024, userID:0
I/Icing   ( 4486): doRemovePackageData com.test.thalitest
D/PMS     (  988): releaseWL(b96748e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
W/BaseAppContext( 4486): Using Auth Proxy for data requests.
W/DriveInitializer( 4486): Awaiting to be initialized
W/DriveInitializer( 4486): Background init thread started
D/VoldConnector(  988): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.gms/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
W/ContextImpl( 4486): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
I/GAv4    ( 6816): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6816):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6816):   adb logcat -s GAv4
W/GAv4    ( 6816): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/DriveInitializer( 4486): Background init thread ended
W/art     ( 4486): Suspending all threads took: 15.524ms
W/GAv4    ( 6816): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6816): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 6816): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
E/SQLiteLog( 1892): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1892): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/phenotype.db, handle: 0x5576d4d220
E/ClearcutLoggerIntentService( 1892): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1892): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1892): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1892): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1892): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1892): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1892): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1892): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1892): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1892): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1892): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1892): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1892): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1892): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1892): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 6816): (2570) os_unix.c:30196: (30) unlink(/data/data/com.google.android.apps.docs/databases/DocList.db-journal) - 
D/VoldConnector(  988): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 6816): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
E/SQLiteLog( 6816): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/PMS     (  988): acquireWL(261bcf4a): PARTIAL_WAKE_LOCK  AsyncService 0x1 6071 10167 null
E/AbstractDatabaseInstance( 6816): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 6816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteConnectionPool.tryAcquireNonPrimaryConnectionLocked(SQLiteConnectionPool.java:899)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:609)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:752)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1754)
E/AbstractDatabaseInstance( 6816): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1683)
E/AbstractDatabaseInstance( 6816): 	at ael.a(PG:1522)
E/AbstractDatabaseInstance( 6816): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6816): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6816): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 6816): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 6816): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 6816): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 6816): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6816): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDBG( 6816): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0x5576bd7220
D/PMS     (  988): acquireWL(30ca9fd8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6071 10167 null
E/GAv4    ( 6816): Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 6816): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6816): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/PMS     (  988): releaseWL(261bcf4a): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/SQLiteLog( 6816): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 6816): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0x5576bd7220
E/GAv4    ( 6816): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 6816): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 6816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteConnectionPool.tryAcquireNonPrimaryConnectionLocked(SQLiteConnectionPool.java:899)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:609)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:752)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1754)
E/CAKEMIX_CRASHED( 6816): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1683)
E/CAKEMIX_CRASHED( 6816): 	at ael.a(PG:1522)
E/CAKEMIX_CRASHED( 6816): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 6816): 	at aen.run(PG:536)
W/ResourcesManager( 6816): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6816): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  988): releaseWL(30ca9fd8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
I/UpdateIcingCorporaServi( 5928): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DeviceManagement( 6707): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 6707): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 6707): WorkflowService: Starting workflow service
I/DeviceManagement( 6707): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@2175d3e3] args=[Bundle[mParcelledData.dataSize=112]]
I/DeviceManagement( 6707): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 6707): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 6707): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 6707): BackgroundController: *** Processing package remove for appID=com.test.thalitest
E/SQLiteLog( 5928): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 5928): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x5576bcb930
I/ActivityManager(  988): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6900 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  988): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 6816 on display 0
I/DeviceManagement( 6707): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 6707): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 6707): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0x5576bd0d90
V/JNIHelp ( 6816): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Process ( 6816): killProcess, pid=6816
D/Process ( 6816): vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
W/DeviceManagement( 6707): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@2175d3e3]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 6707): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 6707): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 6707): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 6707): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 6707): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 6707): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 6707): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 6707): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 6707): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 6707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 6707): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 6707): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/OpenGLRenderer( 1510): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
I/ActivityManager(  988): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=6922 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
I/DeviceManagement( 6707): WorkflowService: Stopping workflow service
E/SharedPreferencesImpl( 5928): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 5928): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5928): Process: com.google.android.googlequicksearchbox:search, PID: 5928
E/AndroidRuntime( 5928): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5928): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5928): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 5928): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5928): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5928): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 5928): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 5928): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 5928): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 5928): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 5928): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 5928): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 5928): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 5928): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 5928): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 5928): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 5928): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 5928): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5928): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5928): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  988): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 5928): killProcess, pid=5928
D/Process ( 5928): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  988): Can't write: system_app_crash
E/DropBoxManagerService(  988): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  988): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  988): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  988): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  988): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  988): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  988): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  988): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  988): 	... 5 more
I/ActivityManager(  988): Recipient 6816
I/ActivityManager(  988): Process com.google.android.apps.docs (pid 6816) has died
W/HtcSystemUPManager(  988): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  988): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=6945 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
E/SQLiteDatabase( 6900): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 6900): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6900): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6900): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6900): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6900): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 6900): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 6900): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 6900): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 6900): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 6900): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 6900): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 6900): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 6900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6900): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6900): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6900): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6900): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6900): FATAL EXCEPTION: main
E/AndroidRuntime( 6900): Process: com.android.documentsui, PID: 6900
E/AndroidRuntime( 6900): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6900): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 6900): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 6900): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 6900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6900): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6900): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6900): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6900): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6900): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6900): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6900): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6900): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6900): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 6900): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 6900): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 6900): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 6900): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 6900): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 6900): 	... 9 more
D/ErrorReport(  988): HtcErrorReportManager Begin---add error logs to dropbox
E/ActivityManager(  988): App crashed! Process: com.android.documentsui
E/SQLiteLog( 3882): (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10195)] disk I/O error
E/SQLiteDBG( 3882): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.downloads/databases/downloads.db, handle: 0x5576c3a160
W/System.err(  988): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
E/AndroidRuntime( 3882): FATAL EXCEPTION: DownloadReceiver
E/AndroidRuntime( 3882): Process: android.process.media, PID: 3882
E/AndroidRuntime( 3882): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3882): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3882): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 3882): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3882): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3882): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 3882): 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
E/AndroidRuntime( 3882): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 3882): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 3882): 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
E/AndroidRuntime( 3882): 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
E/AndroidRuntime( 3882): 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
E/AndroidRuntime( 3882): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 3882): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3882): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 3882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  988): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  988): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.Posix.open(Native Method)
W/System.err(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  988): 	... 12 more
W/System.err(  988): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  988): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  988): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  988): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  988): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  988): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.Posix.open(Native Method)
W/System.err(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  988): 	... 14 more
W/System.err(  988): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  988): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  988): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  988): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  988): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  988): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.Posix.open(Native Method)
W/System.err(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  988): 	... 14 more
E/ActivityManager(  988): App crashed! Process: android.process.media
D/ErrorReport(  988): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  988): Recipient 5928
W/System.err(  988): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:456)
I/ActivityManager(  988): Process com.google.android.googlequicksearchbox:search (pid 5928) has died
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  988): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  988): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  988): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ActivityManager(  988): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
W/System.err(  988): 	at libcore.io.Posix.open(Native Method)
W/System.err(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  988): 	... 12 more
E/ErrorReport(  988): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  988): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457996673060.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  988): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  988): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  988): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  988): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  988): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  988): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  988): 	... 4 more
W/System.err(  988): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
D/Process ( 6900): killProcess, pid=6900
D/Process ( 6900): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  988): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  988): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  988): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  988): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  988): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.Posix.open(Native Method)
W/System.err(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  988): 	... 14 more
W/System.err(  988): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  988): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  988): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  988): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  988): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  988): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  988): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  988): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  988): 	at libcore.io.Posix.open(Native Method)
W/System.err(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  988): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  988): 	... 14 more
D/Process ( 3882): killProcess, pid=3882
D/Process ( 3882): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  988): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  988): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457996673071.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  988): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  988): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  988): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  988): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  988): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  988): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  988): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  988): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  988): 	... 4 more
E/lowmemorykiller(  383): Error writing /proc/3882/oom_score_adj; errno=22
I/ActivityManager(  988): Killing 6463:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  988): killProcessQuiet, pid=6463
D/Process (  988): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  988): Recipient 6900
I/ActivityManager(  988): Recipient 3882
I/Prism.ItemManager( 1510): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1510): loadItems() com.htc.launcher.pageview.WidgetManager@3ddae6cf +
I/Prism.WidgetManager( 1510): onLoadItems() +

```
