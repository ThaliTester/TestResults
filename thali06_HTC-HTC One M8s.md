#### Test 625481247756efd_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  969): acquireWL(1d3c9d05): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1000}
D/PMS     (  969): acquireWL(2184915a): PARTIAL_WAKE_LOCK  *backup* 0x1 969 1000 null
V/AlarmManager(  969): sending alarm PendingIntent{2f577f8b: PendingIntentRecord{19fd868 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457708927322, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{17cf2461: PendingIntentRecord{44e3b86 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180244, Int=0
W/BackupManagerService(  969): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  969): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  969): releaseWL(2184915a): PARTIAL_WAKE_LOCK  *backup* 0x1 null
V/AlarmManager(  969): sending alarm PendingIntent{2d6f0481: PendingIntentRecord{286a6926 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203397, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{1abc8967: PendingIntentRecord{ce1314 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192799, Int=0
D/PMS     (  969): acquireWL(370667bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(1d3c9d05): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  969): acquireWL(1a83f1b2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(370667bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  969): releaseWL(1a83f1b2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(e90b0ac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(e90b0ac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(1a77d175): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(1a77d175): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(3c54050a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(390b617b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(38010ff1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(3c54050a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/VacuumService( 1913): Vacuum at: now=1457708963399 tag=VacuumService
D/PMS     (  969): releaseWL(390b617b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/GoogleURLConnFactory( 1913): Using platform SSLCertificateSocketFactory
D/PMS     (  969): acquireWL(28649a57): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
W/Uploader( 1913): No account for auth token provided
E/cutils-trace( 6838): Error opening trace file: Permission denied (13)
D/PMS     (  969): releaseWL(28649a57): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(10266944): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(10266944): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, success
D/CustomizationManager( 6838): ====startRecUseTime====
D/htc.customization.log.level( 6838):  is 
W/CustomizationLogLevel( 6838): Level value is invalid, use default level 2
D/CustomizationManager( 6838):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 6838): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6838): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6838): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6838): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6838): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6838): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6838): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6838): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6838): Parsing tag category name = system
I/CustomizationCIDLoader( 6838): Parsing tag category name = application
I/CustomizationCIDLoader( 6838): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6838): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6838): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6838): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6838): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6838): add string-array item, value = 42507
I/CustomizationCIDLoader( 6838): add string-array item, value = 21902
I/CustomizationCIDLoader( 6838): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6838): add string-array item, value = 23420
I/CustomizationCIDLoader( 6838): add string-array item, value = 22299
I/CustomizationCIDLoader( 6838): add string-array item, value = 24002
I/CustomizationCIDLoader( 6838): add string-array item, value = 23210
I/CustomizationCIDLoader( 6838): add string-array item, value = 23205
I/CustomizationCIDLoader( 6838): add string-array item, value = 23806
I/CustomizationCIDLoader( 6838): add string-array item, value = 23430
I/CustomizationCIDLoader( 6838): add string-array item, value = 23408
I/CustomizationCIDLoader( 6838): add string-array item, value = 27205
I/CustomizationCIDLoader( 6838): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6838): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6838):  Read CID file spent 0.113 (s)
D/CustomizationManager( 6838):  All configurations done spent 0.113 (s)
I/ActivityManager(  969): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6838 on display 0
D/PMS     (  969): acquireHCC(26c2d5b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 969 1000 null
D/PMS     (  969): acquireHCC(1430cc29): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 969 1000 null
D/PMS     (  969): acquireWL(7b19bae): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(7b19bae): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/asset   (  969): Copying FileAsset 0x5582316600 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  969): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6861 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
I/HtcPowerSaver(  969): updateStatus (8000,98,-1,false,false,false,-1)
D/WifiController(  969): processMsg: StaEnabledState
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3331): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=98
V/ActivityManager(  969): Display changed displayId=0
D/DotMatrix( 1310): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1310): [EventService] mbHDMIConnect: false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/BatteryController( 1222): status:2 level:98 unsupport:false plugged:true
W/asset   ( 6861): Copying FileAsset 0xac4be0e0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1488): [trimMemory] 20
I/WebViewFactory( 6861): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6861): Time to load native libraries: 9 ms (timestamps 4277-4286),
I/LibraryLoader( 6861): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6861): Binding Chromium to main looper Looper (main, tid 1) {c71390}
,I/LibraryLoader( 6861): Expected native library version number "",actual native library version number ""
,I/chromium( 6861): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
I/BrowserStartupController( 6861): Initializing chromium process, singleProcess=true
W/art     ( 6861): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6861): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6861): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,W/Uploader( 1913): No account for auth token provided
,E/libEGL  ( 6861): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6861): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 6861): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6861): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6861): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6861): Local Branch: 
I/Adreno-EGL( 6861): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6861): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6861):                  d74aa161a12b9c6fc6332151
,W/System.err(  969): java.lang.Throwable: stack dump
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  969): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  969): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  969): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  969): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@356ac747:true
,D/BluetoothAdapter( 6861): 1001511100: getState(). Returning 12
,W/Uploader( 1913): No account for auth token provided
,W/art     ( 6861): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6861): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6861): CordovaWebView is running on device made by: HTC
,W/art     ( 6861): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6861): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  969): Activity pause timeout for ActivityRecord{3aa27d4f u0 com.test.thalitest/.MainActivity t12}
,W/HtcSystemUPManager(  969): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6861): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  969): setSystemUiVisibility(0xc0000600)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
D/StatusBarManagerService(  969): hiding MENU key
,D/StatusBarManagerService(  969): setSystemUiVisibility(0x8600),
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  969): hiding MENU key
,D/FindExtension( 6861): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
W/Uploader( 1913):  no longer exists, so no auth token.
,I/InputMethodManager( 6861): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1ae27731, mServedView=org.apache.cordova.engine.SystemWebView{13a3de16 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@25747397
,I/InputMethodManagerService(  969): Disable input method client, pid=1488
D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6861): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  969): Displayed com.test.thalitest/.MainActivity: +658ms (total +713ms),
,W/Uploader( 1913): No account for auth token provided
,W/BindingManager( 6861): Cannot call determinedVisibility() - never saw a connection for the pid: 6861,
,D/JsMessageQueue( 6861): Set native->JS mode to OnlineEventsBridgeMode,
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
,E/Uploader( 1913): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508),
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1913): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/jxcore_app_log( 6861): JniHelper::setJavaVM(0xab3528f8), pthread_self() = -1402498128
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6861): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6861):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6861):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6861):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6861):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6861): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29b834ab added. We now have 1 listener(s)
D/BluetoothManagerService(  969): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861): setBluetoothMacAddress: 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6861): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"},
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6861): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33c37087 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6861): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  969): New client listening to asynchronous messages
E/WifiTrafficPoller(  969): ADD_CLIENT: 8
,D/BluetoothAdapter( 6861): 1001511100: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6861): setDiscoveryMode: Discovery mode BLE is supported,
,D/BluetoothAdapter( 6861): 1001511100: getState(). Returning 12,
,I/chromium( 6861): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/Uploader( 1913): No account for auth token provided
,D/PMS     (  969): releaseWL(38010ff1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  969): acquireWL(17d6f3d4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(17d6f3d4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(ec8997d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(ec8997d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/jxcore-log( 6861): Initializing JXcore engine
,W/jxcore-log( 6861): JXcore engine is ready
,W/jxcore-log( 6861): Starting JXcore engine
,W/jxcore-log( 6861): Platform android,
W/jxcore-log( 6861): 
W/jxcore-log( 6861): Process ARCH arm
W/jxcore-log( 6861): 
,D/PMS     (  969): releaseHCC(26c2d5b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  969): releaseHCC(1430cc29): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6861): JXcore Cordova bridge is ready!,
I/jxcore-log( 6861): 
W/jxcore-log( 6861): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6861): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 6861): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6861): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6861): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,D/Process (  969): killProcessQuiet, pid=5784
I/ActivityManager(  969): Killing 5784:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  969): Recipient 5784,
,W/PluginManager( 6861): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 235ms. Plugin should use CordovaInterface.getThreadPool().,
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1580): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@37143a44,
,D/Process (  969): killProcessQuiet, pid=5712
I/ActivityManager(  969): Killing 5712:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 5712
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  969): acquireWL(1ddba072): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  969): n_update end
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PMS     (  969): releaseWL(1ddba072): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=98
D/HeadsetStateMachine( 3331): Disconnected process message: 10, size: 0
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: E msg.what=155652
D/HtcPowerSaver(  969): updateBatteryInfo
D/WifiController(  969): processMsg: DeviceActiveState
D/PMS     (  969): runPSCheck
D/WifiController(  969): processMsg: StaEnabledState,
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): >> updateStatus
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
,I/HtcPowerSaver(  969): updateStatus (8000,98,-1,false,false,false,-1),
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1222): status:2 level:98 unsupport:false plugged:true,
,D/wpa_supplicant( 1373): wlan0: BSS: Remove id 14 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 7 BSSID 00:1e:4a:8f:e3:6f SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 6 BSSID 00:1e:4a:8f:e3:6b SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 1 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 8 BSSID 00:1e:4a:8f:e3:64 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 9 BSSID 00:1e:4a:8f:e3:60 SSID '\x00' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 1373): wlan0: BSS: Remove id 10 BSSID 00:22:0d:46:1c:a0 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 3 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 11 BSSID 00:16:a6:1e:e0:a4 SSID '' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 12 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 13 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 f0:f2:6d:22:99:3e]
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1373): wlan0: BSS: Remove id 5 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age,
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 f0:f2:6d:22:99:3e
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1e:4a:8f:e3:6f]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1e:4a:8f:e3:6f
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1e:4a:8f:e3:6b]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1e:4a:8f:e3:6b
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c0]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c0,
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:e3:64]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:e3:64
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1e:4a:8f:e3:60]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:1e:4a:8f:e3:60
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:22:0d:46:1c:a0]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:22:0d:46:1c:a0,
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:16:a6:1f:06:5c]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:16:a6:1f:06:5c
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:16:a6:1e:e0:a4]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:16:a6:1e:e0:a4
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:63]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:63
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:e0:43]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:e0:43,
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e3]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e3
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:22:0d:46:1c:a3]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:22:0d:46:1c:a3
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  969): acquireWL(2b923cc3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
,V/AlarmManager(  969): sending alarm PendingIntent{17cf2461: PendingIntentRecord{44e3b86 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240244, Int=0
,V/AlarmManager(  969): sending alarm PendingIntent{24ca5079: PendingIntentRecord{53f51be com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457709101855, Int=0
,D/PMS     (  969): releaseWL(2b923cc3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1913): Explicit concurrent mark sweep GC freed 31532(1720KB) AllocSpace objects, 8(628KB) LOS objects, 47% free, 4MB/8MB, paused 1.075ms total 72.346ms,
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,W/GLSActivity( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1913): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1913): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1913): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6259): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6259): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6259): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6259): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6259): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6259): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6259): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6259): Ignoring header User-Agent because its value was null.
,D/libc    ( 6259): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6259): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6259): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6259): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6259): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6259): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604,
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 6259): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 4
,E/cutils-trace( 6926): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 6926): ====startRecUseTime====,
D/htc.customization.log.level( 6926):  is 
,W/CustomizationLogLevel( 6926): Level value is invalid, use default level 2
,D/CustomizationManager( 6926):  Read ACC file spent 0.048 (s),
,D/CIDMapFileReader( 6926): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 6926): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 6926): Parsing tag item name = HTC__Y13
,D/CIDMapFileReader( 6926): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6926): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 6926): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6926): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 6926): full path : /system/customize/CID/HTC__102.xml,
I/CustomizationCIDLoader( 6926): Parsing tag category name = system
,I/CustomizationCIDLoader( 6926): Parsing tag category name = application,
,I/CustomizationCIDLoader( 6926): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6926): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6926): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 6926): Parsing tag category name = Settings
,I/CustomizationCIDLoader( 6926): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 6926): add string-array item, value = 42507,
I/CustomizationCIDLoader( 6926): add string-array item, value = 21902
I/CustomizationCIDLoader( 6926): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6926): add string-array item, value = 23420
I/CustomizationCIDLoader( 6926): add string-array item, value = 22299
,I/CustomizationCIDLoader( 6926): add string-array item, value = 24002
I/CustomizationCIDLoader( 6926): add string-array item, value = 23210
I/CustomizationCIDLoader( 6926): add string-array item, value = 23205
I/CustomizationCIDLoader( 6926): add string-array item, value = 23806
I/CustomizationCIDLoader( 6926): add string-array item, value = 23430
,I/CustomizationCIDLoader( 6926): add string-array item, value = 23408
I/CustomizationCIDLoader( 6926): add string-array item, value = 27205
I/CustomizationCIDLoader( 6926): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6926): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6926): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6926): add string-array item, value = 23420:D:0:0
,I/CustomizationCIDLoader( 6926): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6926): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6926): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6926): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6926): add string-array item, value = 23806:D:0:0
,I/CustomizationCIDLoader( 6926): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6926): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6926): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6926):  Read CID file spent 0.102 (s)
D/CustomizationManager( 6926):  All configurations done spent 0.102 (s)
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  969): acquireWL(99db270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/UsbnetService(  969): BroadcastReceiver::onReceive+
I/BatteryService(  969): n_update end
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  969): releaseWL(99db270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=99
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/HtcPowerSaver(  969): updateBatteryInfo
D/WifiController(  969): processMsg: StaEnabledState
D/PMS     (  969): runPSCheck
D/WifiController(  969): processMsg: DefaultState
D/HtcPowerSaver(  969): Checking...
,D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3331): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  969): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1222): status:2 level:99 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  969): acquireWL(172349e9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(172349e9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/DotMatrix( 1310): [EventService] reorderNotification, total:0
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3331): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3331): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3331): Disconnected process message: 11, size: 0
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  969): updateBatteryInfo
,D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PMS     (  969): runPSCheck
D/WifiController(  969): handleMessage: E msg.what=155652
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): processMsg: DeviceActiveState
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DefaultState
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): << updateStatus
,W/ContextImpl( 6751): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 6232): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6232): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6232): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 6232): Cust_ConnectToPC   : spcsc>false
D/        ( 6232): Cust_ConnectToPC   : IPT>true
D/        ( 6232): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 6232): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 6232): Index of the first 1 = -1
,W/ContextImpl( 6232): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 ,
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
W/ContextImpl( 6232): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 6232): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 6232): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6232): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6232): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 6232): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 6232): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1433): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1433): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1433): sku_id=118
D/ContactMessageStore( 1433): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1433): start background delete task...
,D/ContactMessageStore( 1433): size: 0 , 0
,D/ContactMessageStore( 1433): Background delete complete
,D/PMS     (  969): acquireWL(233d910f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
,V/AlarmManager(  969): sending alarm PendingIntent{17cf2461: PendingIntentRecord{44e3b86 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=360244, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{403859c: PendingIntentRecord{3add9ba5 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=942337, Int=0
,I/bt-btm  ( 3331): Received oneshot timer event complete,
I/bt-btm  ( 3331): btm_ble_timeout
I/bt-btm  ( 3331): btm_gen_resolvable_private_addr,
D/PMS     (  969): acquireWL(1c65bb7a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3331 1002 null
,D/bt-btm  ( 3331): btm_ble_rand_enc_complete
I/bt-btm  ( 3331): btm_gen_resolve_paddr_low
D/bt-smp  ( 3331): smp_encrypt_data
W/bt-smp  ( 3331): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3331): Plain text(LSB ~ MSB) = 04 49 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3331): Encrypted text(LSB ~ MSB) = b0 99 df cb a9 2c 58 60 fc ff 09 4e 04 0b 1a 6b 
I/bt-btm  ( 3331): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3331): Stopping oneshot timer
D/bt-btm  ( 3331): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  969): releaseWL(233d910f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On,
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  969): releaseWL(1c65bb7a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  969): acquireWL(10cc2f2b): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{1b7e2f5f: PendingIntentRecord{29a34dac android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804496, Int=0
,V/AlarmManager(  969): sending alarm PendingIntent{17cf2461: PendingIntentRecord{44e3b86 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=960245, Int=0,
V/AlarmManager(  969): sending alarm PendingIntent{3915f88: PendingIntentRecord{3b314d21 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457709629734, Int=1800000
V/AlarmManager(  969): sending alarm PendingIntent{2041546: PendingIntentRecord{145c9307 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937180, Int=0
,I/ActivityManager(  969): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6950 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  969): sending alarm PendingIntent{1ea0ec34: PendingIntentRecord{36b49a5d com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457709501096, Int=0
,D/PMS     (  969): acquireWL(12dc3fd2): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4693 10024 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  969): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=6966 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
,V/AlarmManager(  969): sending alarm PendingIntent{11a558a3: PendingIntentRecord{157a97a0 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  969): sending alarm PendingIntent{159a871e: PendingIntentRecord{15d58cfc com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457709728202, Int=0
D/PMS     (  969): acquireWL(272adbff): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(22818dcc): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4693 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(272adbff): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(12dc3fd2): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6751): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  969): releaseWL(10cc2f2b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
D/PowerUsageList:PowerUsageHelper( 6751): MY_DEBUG = false,
,D/PowerUsageService( 6751): repeat time = 1457710628330
,I/EventLogService( 4693): Aggregate from 1457708856953 (log), 1457707829666 (data)
,D/PMS     (  969): acquireWL(18a25bf6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1913): Message class com.google.f.a.a.i
,D/PMS     (  969): releaseWL(18a25bf6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/StatusBarManagerService(  969): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
,D/StatusBarManagerService(  969): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  969): hiding MENU key
,D/FindExtension( 1488): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1488): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  969): Disable input method client, pid=6861,
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 6861): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6861): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6861): reportFullscreenMode on inactive InputConnection
,D/PMS     (  969): releaseWL(22818dcc): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6751): PowerProfile::POWER_SCREEN_FULL = 154.8,
,I/ImageRamCache( 6966): create image Cache, size: 31457280.
,I/ImageRamCache( 6966): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 6966): create image Cache, size: 31457280.
D/PowerUsageList:BatterySipperExt( 6751): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6751): gen(), null == sipper.uidObj, userId = 0
,I/FeedSettings( 6966): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 6966): GroupBudget 0.500000 0.380000
I/FeedSettings( 6966): GroupBudget 60 45 15
,D/PowerUsageList:BatterySipperExt( 6751): gen(), null == sipper.uidObj, userId = 0
,I/Prism.ExternalStringMa_( 6966): changeLocale(): en_GB,
E/cutils-trace( 6998): Error opening trace file: Permission denied (13)
I/dex2oat ( 6998): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6998): dex2oat: override thread count:4
,I/Prism.AllAppsOptionsMa_( 6966): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 6966): loadGridSize() with Alternative
,D/libc    ( 6966): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4
D/libc    ( 6966): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6966): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    ( 6966): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6966): [NET] android_getaddrinfo_proxy+
D/libc    ( 6966): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6966): [NET] android_getaddrinfo_proxy-, success
,I/dex2oat ( 6998): dex2oat took 630.338ms (threads: 4),
,I/PushClient( 6950): ApplicationMonitor {382ac045}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6950): ApplicationMonitor {382ac045}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6950): ApplicationMonitor {382ac045}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6950): ApplicationMonitor {382ac045}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6950): ApplicationMonitor {382ac045}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6950): ApplicationMonitor {382ac045}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6950): ApplicationMonitor {382ac045}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6950): ApplicationMonitor {382ac045}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6950): ApplicationMonitor {382ac045}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6950): PnsModel {3bb1d8bc}: update(): Update registration caused by: alarm,
,I/PushClient( 6950): PnsConfigModel {14e0b243}: <init>(): Use dm-client for provisioning.
,W/System.err( 6950): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6950): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6950): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6950): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  969): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7010 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7010): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7010 dbg=false s=true,
,I/DeviceManagement( 7010): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 7010): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7010): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 7010): WorkflowService: Starting workflow service
,I/DeviceManagement( 7010): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3372bcaf] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7010): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7010): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7010): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7010): SessionStateController: Checking invariants...
,D/Process (  969): killProcessQuiet, pid=6659
I/ActivityManager(  969): Killing 6659:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 7010): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/ActivityManager(  969): Recipient 6659,
,I/DeviceManagement( 7010): SessionStateController: Checking invariants...,
,I/art     (  969): Explicit concurrent mark sweep GC freed 28484(1589KB) AllocSpace objects, 9(812KB) LOS objects, 33% free, 16MB/25MB, paused 1.672ms total 159.884ms
,I/DeviceManagement( 7010): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7010): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3372bcaf]
,I/DeviceManagement( 7010): WorkflowService: Stopping workflow service,
,D/Process (  969): killProcessQuiet, pid=6616,
I/ActivityManager(  969): Killing 6616:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6616
,I/PushClient( 6950): PnsModel {3bb1d8bc}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  969): killProcessQuiet, pid=6049,
I/ActivityManager(  969): Killing 6049:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6049,
,W/SQLiteConnectionPool( 6966): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,D/PMS     (  969): acquireWL(298a6600): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1000}
D/SmartSyncUtils( 6751): isEpsOn(), nState = 0
,V/AlarmManager(  969): sending alarm PendingIntent{3f019e39: PendingIntentRecord{2afbec7e com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457709775177, Int=0
,D/PMS     (  969): releaseWL(298a6600): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  969): acquireWL(36c645df): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6751 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6751): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6751): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6751): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6751): SettingOnTime = 1457762400000, randomSettingOnTime = 1457760238000
,D/SmartSyncScreenOnOffTimeReceiver( 6751): SettingOffTime = 1457740800000, randomSettingOffTime = 1457744244000
,D/SmartSyncScreenOnOffTimeReceiver( 6751): bDayMode = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6751): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6751): bNightModeTurnOffOnce = false
,D/PMS     (  969): releaseWL(36c645df): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  969): User[0] Flushing usage stats to disk
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PMS     (  969): acquireWL(252fe22c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/UsbnetService(  969): onReceive BATTERY_CHANGED
I/BatteryService(  969): n_update end
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): releaseWL(252fe22c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/NotificationService(  969): plugged=true pluggin=true
D/WifiController(  969): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): updateBatteryInfo
D/HeadsetStateMachine( 3331): Disconnected process message: 10, size: 0
D/WifiController(  969): battery changed pluggedType: 2
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  969): runPSCheck
D/WifiController(  969): processMsg: DeviceActiveState
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): processMsg: StaEnabledState
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  969): acquireWL(654e4f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(654e4f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  969): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  969): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): runPSCheck
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  969): Checking...
D/HeadsetStateMachine( 3331): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  969): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/PowerUI ( 1222): closing low battery warning: level=100
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1400000ms)
```
