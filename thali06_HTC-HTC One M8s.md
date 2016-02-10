#### Test 58380500a584679_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  960):  packet count Tx=164 Rx=231
,E/WifiStateMachine(  960): handleMessage: E msg.what=131155
E/WifiStateMachine(  960): processMsg: ConnectedState
E/WifiStateMachine(  960):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926372376] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926372375] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960):  get link layer stats 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
--------- beginning of system
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  960): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  960): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.28 txretriesrate=0.00 rxrate=0.85 userTriggerdPenalty0
E/WifiStateMachine(  960):  good link -> stuck count =0
E/WifiStateMachine(  960):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  960):  isHighRSSI       ---> score=61
E/WifiStateMachine(  960): handleMessage: X
D/WifiWatchdogStateMachine(  960): RSSI current: 3 new: -60, 3
E/cutils-trace( 6365): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6365): ====startRecUseTime====
D/htc.customization.log.level( 6365):  is 
W/CustomizationLogLevel( 6365): Level value is invalid, use default level 2
D/CustomizationManager( 6365):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 6365): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6365): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6365): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6365): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6365): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6365): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6365): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6365): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6365): Parsing tag category name = system
I/CustomizationCIDLoader( 6365): Parsing tag category name = application
I/CustomizationCIDLoader( 6365): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6365): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6365): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6365): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6365): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6365): add string-array item, value = 42507
I/CustomizationCIDLoader( 6365): add string-array item, value = 21902
I/CustomizationCIDLoader( 6365): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6365): add string-array item, value = 23420
I/CustomizationCIDLoader( 6365): add string-array item, value = 22299
I/CustomizationCIDLoader( 6365): add string-array item, value = 24002
I/CustomizationCIDLoader( 6365): add string-array item, value = 23210
I/CustomizationCIDLoader( 6365): add string-array item, value = 23205
I/CustomizationCIDLoader( 6365): add string-array item, value = 23806
I/CustomizationCIDLoader( 6365): add string-array item, value = 23430
I/CustomizationCIDLoader( 6365): add string-array item, value = 23408
I/CustomizationCIDLoader( 6365): add string-array item, value = 27205
I/CustomizationCIDLoader( 6365): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6365): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6365):  Read CID file spent 0.098 (s)
D/CustomizationManager( 6365):  All configurations done spent 0.098 (s)
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6365 on display 0
D/PMS     (  960): acquireHCC(31f5dc89): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 960 1000 null
D/PMS     (  960): acquireHCC(9d6d48e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 960 1000 null
W/asset   (  960): Copying FileAsset 0x55b9c92580 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  960): acquireWL(2956b845): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 960 1000 null
I/AnimationUtil(  960): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1628): [onPause]
I/FeedProviderManager( 1628): onPause
I/SocialFeedProvider( 1628): +onPause
I/SocialFeedProvider( 1628): -onPause
I/FeedHostManager( 1628): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@17d3fa04
W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6383 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  960): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  960): hiding MENU key
W/asset   ( 6383): Copying FileAsset 0xac521568 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1628): [trimMemory] 20
,I/WebViewFactory( 6383): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  960):  packet count Tx=164 Rx=231
I/LibraryLoader( 6383): Time to load native libraries: 9 ms (timestamps 7076-7085)
I/LibraryLoader( 6383): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6383): Binding Chromium to main looper Looper (main, tid 1) {1758c5f0}
I/LibraryLoader( 6383): Expected native library version number "",actual native library version number ""
I/chromium( 6383): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/PMS     (  960): acquireWL(3877d8c0): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{10072}
V/AlarmManager(  960): sending alarm PendingIntent{3391f9f9: PendingIntentRecord{3ee77d3e com.android.vending startService}}, i=null, t=0, cnt=1, w=1455067538738, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{2cad679f: PendingIntentRecord{1f61c0ec com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455067541944, Int=536832000
V/AlarmManager(  960): sending alarm PendingIntent{2d3c1305: PendingIntentRecord{b3dcf5a android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455067533697, Int=20000
V/CheckinService( 4443): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
D/PMS     (  960): acquireWL(7ef3cb5): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4443 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  960): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
E/WifiStateMachine(  960): handleMessage: E msg.what=131143
D/PMS     (  960): releaseWL(3877d8c0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  960): processMsg: ConnectedState
D/PMS     (  960): acquireWL(140adebb): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4443 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  960):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):0 dur:142 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.8 list=2412 [on:0 tx:0 rx:0 period:981] from screen [on:0 period:-926371376]
D/PMS     (  960): releaseWL(7ef3cb5): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:142 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.8 list=2412 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-926371376]
E/WifiStateMachine(  960): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.28 rxSuccessRate=0.85 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  960): WifiStateMachine CMD_START_SCAN with age=60323 interval=60000 maxinterval=300000
E/WifiStateMachine(  960): WifiStateMachine CMD_START_SCAN try full band scan age=60323 interval=60000 maxinterval=300000
E/WifiStateMachine(  960): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  960): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1330): WPS:  * UUID-E
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1330): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1330): WPS:  * Manufacturer
D/wpa_supplicant( 1330): WPS:  * Model Name
D/wpa_supplicant( 1330): WPS:  * Model Number
D/wpa_supplicant( 1330): WPS:  * Device Name
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1330): P2P: * P2P IE header
D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x55a615d680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x55a615d680 after 0.000026 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000063 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  960): [1,455,067,541,970 ms] noteScanstart no scan source
I/BrowserStartupController( 6383): Initializing chromium process, singleProcess=true
E/WifiStateMachine(  960): handleMessage: X
W/art     ( 6383): Attempt to remove local handle scope entry from IRT, ignoring
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  960): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  960): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/SysUtils( 6383): ApplicationContext is null in ApplicationStatus
I/CheckinService( 4443): Checking schedule, now: 1455067541996 next: 1455067541944
I/CheckinService( 4443): active receiver: enabled
I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4443, uid=10024, userID:0
I/CheckinService( 4443): Preparing to send checkin request
I/EventLogService( 4443): Accumulating logs since 1455067507037
W/chromium( 6383): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6383): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6383): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6383): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6383): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6383): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6383): Local Branch: 
I/Adreno-EGL( 6383): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6383): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6383):                  d74aa161a12b9c6fc6332151
I/CheckinRequestBuilder( 4443): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  960): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4443): Failed to find provider info for com.google.android.wearable.settings
W/System.err(  960): java.lang.Throwable: stack dump
W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  960): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d8bb1ee:true
D/BluetoothAdapter( 6383): 823939356: getState(). Returning 12
I/art     (  960): Explicit concurrent mark sweep GC freed 39915(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/25MB, paused 1.515ms total 167.794ms
D/Finsky  ( 6030): [612] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6030): [1] 5.onFinished: Installation state replication succeeded.
W/art     ( 6383): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6383): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6383): CordovaWebView is running on device made by: HTC
W/art     ( 6383): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6383): Attempt to remove local handle scope entry from IRT, ignoring
I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/CheckinRequestBuilder( 4443): awaiting user notification for token
D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
I/ActivityManager(  960): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6432 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/chromium( 6383): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6383): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/ResourcesManager( 6432): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6432): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6432): VM with version 2.1.0 has multidex support
I/MultiDex( 6432): install
I/MultiDex( 6432): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6432): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/InputMethodManager( 6383): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1ca9bd95, mServedView=org.apache.cordova.engine.SystemWebView{22474eaa VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@13d07a9b
I/InputMethodManagerService(  960): Disable input method client, pid=1628
D/StatusBarManagerService(  960): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  960): Enable input method client, pid=6383
D/PMS     (  960): releaseWL(2956b845): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/ActivityThread( 6432): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6432): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1aa7627b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6432): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +978ms
D/GCM     ( 1884): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1884): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4443): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/WearableService( 4945): callingUid 10024, callindPid: 4945
I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4443, uid=10024, userID:0
W/XT9_C   ( 1398): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1398): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1398): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1398): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
E/MDM     ( 1825): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/BindingManager( 6383): Cannot call determinedVisibility() - never saw a connection for the pid: 6383
D/JsMessageQueue( 6383): Set native->JS mode to OnlineEventsBridgeMode
I/WVCdm   (  422): CdmEngine::OpenSession
I/WVCdm   (  422): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  422): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/LocationInitializer( 4443): Restart initialization of location
D/DrmWidevineDash(  422): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  422): Service_Initialize: starts!
D/QSEECOMAPI: (  422): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  422): App is not loaded in QSEE
E/QSEECOMAPI: (  422): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  422): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  422): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  422): App is not loaded in QSEE
D/QSEECOMAPI: (  422): Loaded image: APP id = 8
D/DrmWidevineDash(  422): Service_Initialize: ends! returns 0
D/QSAPPSVER(  422): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  422): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  422): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b44000
E/DrmWidevineDash(  422): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b44000
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  541): got the req here! ret=0
D/DrmLibTime(  541): command id, time_cmd_id = 770
D/DrmLibTime(  541): time_getutcsec starts!
D/DrmLibTime(  541): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  541): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  541): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  541): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  541): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  541): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  541): QSEE Time Listener: Retrieved Android system time: 1455067542
D/DrmLibTime(  541): time_getutcsec returns 0, sec = 1455067542; nsec = 0
D/DrmLibTime(  541): time_getutcsec finished! 
D/DrmLibTime(  541): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  541): before calling ioctl to read the next time_cmd
E/QC-time-services(  476): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): hlos api version =  9
D/DrmWidevineDash(  422): tz api version =  9
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  422): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  960):  packet count Tx=164 Rx=231
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  422): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  422): OEMCrypto_OpenSession: starts! SID=0xffc2e738
D/DrmWidevineDash(  422): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  422): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_GetRandom: starts! randomData=0xaadcdab8, dataLength=8
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaade64f0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  422): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  422): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  422): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  422): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  422): OEMCrypto_GetDeviceID: starts! deviceID=0xaadbb628, idLength=0xf4e6e6f8
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4e6e70e, maximum = 0xf4e6e70f
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): hlos api version =  9
D/DrmWidevineDash(  422): tz api version =  9
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  422): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4e6e77c
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  422): PrepareKeyRequest: nonce=619873024
D/DrmWidevineDash(  422): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaadf6440
D/DrmWidevineDash(  422): message_length=1611, signature=0xaae3f6e0, signature_length=0xf4e6e6dc
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/jxcore_app_log( 6383): JniHelper::setJavaVM(0xab3b58f8), pthread_self() = -1402157880
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  422): CdmEngine::CloseSession
D/DrmWidevineDash(  422): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  422): L3 Terminate.
D/DrmWidevineDash(  422): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): Service_Uninitialize: starts!
D/QSEECOMAPI: (  422): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  422): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  422): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  422): OEMCrypto_Terminate: ends! returns 0
I/chromium( 6383): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/WVCdm   (  422): CdmEngine::OpenSession
I/WVCdm   (  422): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  422): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  422): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  422): Service_Initialize: starts!
D/QSEECOMAPI: (  422): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  422): App is not loaded in QSEE
E/QSEECOMAPI: (  422): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  422): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  422): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  422): App is not loaded in QSEE
D/QSEECOMAPI: (  422): Loaded image: APP id = 9
D/DrmWidevineDash(  422): Service_Initialize: ends! returns 0
D/QSAPPSVER(  422): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  422): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  422): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b44000
E/DrmWidevineDash(  422): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b44000
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  541): got the req here! ret=0
D/DrmLibTime(  541): command id, time_cmd_id = 770
D/DrmLibTime(  541): time_getutcsec starts!
D/DrmLibTime(  541): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  541): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  541): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  541): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  541): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  541): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  541): QSEE Time Listener: Retrieved Android system time: 1455067543
D/DrmLibTime(  541): time_getutcsec returns 0, sec = 1455067543; nsec = 0
D/DrmLibTime(  541): time_getutcsec finished! 
D/DrmLibTime(  541): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  541): before calling ioctl to read the next time_cmd
E/QC-time-services(  476): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): hlos api version =  9
D/DrmWidevineDash(  422): tz api version =  9
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  422): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  422): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  422): OEMCrypto_OpenSession: starts! SID=0xffc2e738
D/DrmWidevineDash(  422): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  422): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_GetRandom: starts! randomData=0xaae3f8e0, dataLength=8
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaade64f0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  422): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  422): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  422): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  422): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  422): OEMCrypto_GetDeviceID: starts! deviceID=0xaadbb648, idLength=0xf4c6e6f8
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4c6e70e, maximum = 0xf4c6e70f
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): hlos api version =  9
D/DrmWidevineDash(  422): tz api version =  9
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  422): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4c6e77c
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  422): PrepareKeyRequest: nonce=4168869055
D/DrmWidevineDash(  422): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaadcb8a0
D/DrmWidevineDash(  422): message_length=1646, signature=0xaae3ebf8, signature_length=0xf4c6e6dc
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  422): CdmEngine::CloseSession
D/DrmWidevineDash(  422): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  422): L3 Terminate.
D/DrmWidevineDash(  422): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): Service_Uninitialize: starts!
D/QSEECOMAPI: (  422): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  422): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  422): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  422): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6471): Error opening trace file: Permission denied (13)
I/dex2oat ( 6471): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6471): dex2oat: override thread count:4
,I/dex2oat ( 6471): dex2oat took 42.467ms (threads: 4)
,I/Adreno-EGL( 6432): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6432): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6432): Build Date: 03/09/15 Mon,
I/Adreno-EGL( 6432): Local Branch: 
I/Adreno-EGL( 6432): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6432): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6432):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6432): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6432): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6432): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6432): Local Branch: 
I/Adreno-EGL( 6432): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6432): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6432):                  d74aa161a12b9c6fc6332151
D/PMS     (  960): releaseHCC(31f5dc89): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  960): releaseHCC(9d6d48e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/CheckinRequestBuilder( 4443): Classify the device as Phone.
,D/libc    ( 4443): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4443): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4443): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4443): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4443): [NET] android_getaddrinfo_proxy+
D/libc    ( 4443): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4443): [NET] android_getaddrinfo_proxy-, success
,E/WifiDataStallTracker(  960): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  960): updateDataStallInfo: mDataStallTxRxSum={txSum=147 rxSum=118} preTxRxSum={txSum=146 rxSum=118}
D/WifiDataStallTracker(  960): updateDataStallInfo: OUT sent=1 mSentSinceLastRecv=1
D/WifiDataStallTracker(  960): onDataStallAlarm: Sent 1 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  960):  packet count Tx=165 Rx=231
D/WIFI_ICON( 1221): WifiActivity: 2
E/WifiTrafficPoller(  960): notifying of data activity 2
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,E/WifiStateMachine(  960): handleMessage: E msg.what=131155,
E/WifiStateMachine(  960): processMsg: ConnectedState
,E/WifiStateMachine(  960):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:2021] from screen [on:0 period:-926369353] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
,E/WifiStateMachine(  960):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-926369351] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  960):  get link layer stats 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0],
D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
,I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 2.040532 seconds
D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1330): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1330): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
I/wpa_supplicant( 1330): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 5
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/wpa_supplicant( 1330): BSS: last_scan_res_used=5/32
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55a615d680 done in 2.041440 seconds
E/WifiConfigStore(  960): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  960): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  960): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.64 txretriesrate=0.00 rxrate=0.42 userTriggerdPenalty0
E/WifiStateMachine(  960):  good link -> stuck count =0
E/WifiStateMachine(  960):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  960):  isHighRSSI       ---> score=61
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=147461
E/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiWatchdogStateMachine(  960): RSSI current: 3 new: -60, 3
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  960):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
D/WifiStateMachine(  960): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  960): [1,455,067,544,024 ms] noteScanEnd no scan source
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  960): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2f565c2b sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  960): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  960): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,E/WifiConfigStore(  960): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  960): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  960):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  960): Gonzos 38:f8:89:11:e9:11 rssi=-80 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  960): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  960): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  960): ageScanResultsOut delay 40000 size 5 now 1455067544027
E/WifiAutoJoinController (  960): newSupplicantResults size=5 known=1 true
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  960): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  960): ssid=NG700
E/WifiAutoJoinController (  960): id=0
E/WifiAutoJoinController (  960): mode=station
E/WifiAutoJoinController (  960): pairwise_cipher=CCMP
E/WifiAutoJoinController (  960): group_cipher=CCMP
E/WifiAutoJoinController (  960): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  960): wpa_state=COMPLETED
E/WifiAutoJoinController (  960): ip_address=192.168.1.130
E/WifiAutoJoinController (  960): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  960): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  960): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  960): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  960): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  960): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  960): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  960): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  960): Done attemptAutoJoin status=0
E/WifiConfigStore(  960):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  960): handleMessage: X
D/WifiManager( 1825): getScanResults: Base Package Name=com.google.android.gms, uid=10024
D/libc    ( 4443): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4443): [NET] android_getaddrinfofornet-, err=8
,W/jxcore-log( 6383): Initializing JXcore engine,
,W/jxcore-log( 6383): JXcore engine is ready
,W/jxcore-log( 6383): Starting JXcore engine
,W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/jxcore-log( 6383): Platform android
W/jxcore-log( 6383): 
,W/jxcore-log( 6383): Process ARCH arm
W/jxcore-log( 6383): ,
,D/libc    ( 4443): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4443): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4443): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4443): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4443): Sending checkin request (8414 bytes),
,I/jxcore-log( 6383): JXcore Cordova bridge is ready!,
I/jxcore-log( 6383): 
W/jxcore-log( 6383): JXcore engine is started
,E/jxcore  ( 6383): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6383): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6383): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/PMS     (  960): acquireWL(9439203): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 960 1000 null,
W/PluginManager( 6383): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 47ms. Plugin should use CordovaInterface.getThreadPool().
W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1628): [onResume]
I/FeedProviderManager( 1628): onResume
I/SocialFeedProvider( 1628): +onResume
I/SocialFeedProvider( 1628): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1628): -onResume
,D/StatusBarManagerService(  960): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  960): hiding MENU key
,D/FindExtension( 1628): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1628): Defer allocateBuffers to drawing time
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/InputMethodManagerService(  960): Disable input method client, pid=6383
D/StatusBarManagerService(  960): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  960): Enable input method client, pid=1628
,W/IInputConnectionWrapper( 6383): reportFullscreenMode on inactive InputConnection
,D/PMS     (  960): releaseWL(9439203): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  960):  packet count Tx=182 Rx=243
E/WifiTrafficPoller(  960): notifying of data activity 3
,D/WIFI_ICON( 1221): WifiActivity: 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/StatusBarManagerService(  960): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  960): hiding MENU key
,I/CheckinRequestBuilder( 4443): Checkin reason type: 11 attempt count: 1
,I/ActivityManager(  960): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4443): Failed to find provider info for com.google.android.wearable.settings,
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4443): awaiting user notification for token
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/CheckinRequestBuilder( 4443): Classify the device as Phone.
,I/HtcModeClient( 3250): handler message = 4011
,E/HtcModeClient( 3250): Check connection and retry 12 times.
,I/CheckinTask( 4443): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4443): Checking schedule, now: 1455067545295 next: 1455604377290,
I/CheckinService( 4443): active receiver: disabled
I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4443, uid=10024, userID:0
,D/PMS     (  960): releaseWL(140adebb): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6485 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/PhoneMonitor( 6485): Register our PhoneStateListener,
W/OpenGLRenderer( 1628): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,V/SetupWizard( 6485): Connected to Gservices successfully
,D/ChimeraCfgMgr( 4443): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 4443): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PhoneMonitor( 6485): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/GCM     ( 1884): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,D/PhoneMonitor( 6485): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  960):  packet count Tx=184 Rx=246
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 0
,E/WifiTrafficPoller(  960):  packet count Tx=184 Rx=246
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  960): notifying of data activity 0
,E/WifiStateMachine(  960): handleMessage: E msg.what=131155,
E/WifiStateMachine(  960): processMsg: ConnectedState,
E/WifiStateMachine(  960):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926366326] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState,
E/WifiStateMachine(  960):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926366325] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960):  get link layer stats 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=15 [20][3][0],
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
E/WifiConfigStore(  960): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  960): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=9.82 txretriesrate=0.00 rxrate=7.71 userTriggerdPenalty0
E/WifiStateMachine(  960):  good link -> stuck count =0
E/WifiStateMachine(  960):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  960):  isHighRSSI       ---> score=65,
D/WifiWatchdogStateMachine(  960): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  960): handleMessage: X
,I/ActivityManager(  960): Killing 5544:com.google.android.music:main/u0a159 (adj 15): empty #17
,D/Process (  960): killProcessQuiet, pid=5544
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 5544
D/MediaRouterService(  960): Client com.google.android.music (pid 5544): Died!
,D/Process (  960): killProcessQuiet, pid=5829
I/ActivityManager(  960): Killing 5829:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  960):  packet count Tx=184 Rx=246
,I/ActivityManager(  960): Recipient 5829
,D/Process (  960): killProcessQuiet, pid=5860
I/ActivityManager(  960): Killing 5860:com.google.android.gm/u0a106 (adj 15): empty #18
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 5860
,E/WifiDataStallTracker(  960): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  960): updateDataStallInfo: mDataStallTxRxSum={txSum=168 rxSum=133} preTxRxSum={txSum=147 rxSum=118}
,D/WifiDataStallTracker(  960): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  960): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 3
E/WifiTrafficPoller(  960):  packet count Tx=186 Rx=248
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  960): notifying of data activity 3
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  960):  packet count Tx=186 Rx=248
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
E/WifiTrafficPoller(  960): notifying of data activity 0
,E/WifiStateMachine(  960): handleMessage: E msg.what=131155
E/WifiStateMachine(  960): processMsg: ConnectedState
E/WifiStateMachine(  960):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926363305] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
,E/WifiStateMachine(  960):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926363304] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  960):  get link layer stats 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [3][0][0]
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  960): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  960): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.91 txretriesrate=0.00 rxrate=4.86 userTriggerdPenalty0
,E/WifiStateMachine(  960):  good link -> stuck count =0
E/WifiStateMachine(  960):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  960):  isHighRSSI       ---> score=65
E/WifiStateMachine(  960): handleMessage: X
D/WifiWatchdogStateMachine(  960): RSSI current: 3 new: -60, 3,
,I/HtcModeClient( 3250): handler message = 4011,
,E/HtcModeClient( 3250): Check connection and retry 12 times. Stop service and kill this process.,
D/HtcModeClient( 3250): Don't start project servcice
,D/HtcModeClient( 3250): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3250): connectState: CONNECTION_READY = false
D/SilentMusic( 3250): call stop
,D/HtcModeClient( 3250): close connection
W/HtcModeClient( 3250): leaveProjectMode: It does not enter ProjectMode,
W/CANMesgAgentLocalSocket( 3250): read the terminate packet, so break
,D/Process (  960): killProcessQuiet, pid=3250
,I/ActivityManager(  960): Killing 3250:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 3250,
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  960):  packet count Tx=186 Rx=248
,I/ActivityManager(  960): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6510 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  960): acquireWL(187396e5): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{10076}
V/AlarmManager(  960): sending alarm PendingIntent{3b4f35ba: PendingIntentRecord{2af4bc6b com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455067551818, Int=60000
D/PMS     (  960): releaseWL(187396e5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076},
,D/SMSBackup( 6510): SMSBackupAgentService started,
D/SMSBackup( 6510): Checking restore status
D/SMSBackup( 6510): Restore complete
D/SMSBackup( 6510): cancelCheckAlarm
D/SMSBackup( 6510): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  960): killProcessQuiet, pid=5982
I/ActivityManager(  960): Killing 5982:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  960):  packet count Tx=186 Rx=249
E/WifiTrafficPoller(  960): notifying of data activity 1
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  960): Recipient 5982
,D/AccTypeManager( 1766): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  960): Cannot find grip_rejection_width, use default value instead
I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1628): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,D/AccTypeManager( 1766): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6532 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ResourcesManager(  960): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1766): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PhoneApp( 1564): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/art     (  456): Explicit concurrent mark sweep GC freed 8687(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 491us total 33.167ms
,E/ExternalAccountType( 1766): Unsupported attribute readOnly,
I/art     (  456): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 564us total 24.622ms
,W/ResourcesManager( 6532): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  456): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 270us total 19.251ms,
,W/PackageManager(  960): Unable to load service info ResolveInfo{222b5cd4 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  960): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  960): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  960): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  960): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  960): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  960): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  960): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  960): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  960): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  960): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  960): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1825): DISABLE,
I/GCoreNlp( 1825): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  960): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LocationProviderProxy(  960): applying state to connected service
,D/PMS     (  960): acquireWL(1683f75c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(1683f75c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  960): applying state to connected service
,D/PMS     (  960): acquireWL(21072d48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(21072d48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  960): acquireWL(d8a67e1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  960): releaseWL(d8a67e1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): acquireWL(1ea45d60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  960): releaseWL(1ea45d60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel_SMS( 6532): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6532): MmsConfig.loadMmsSettings
,I/ActivityManager(  960): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6562 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6532, uid=10112, userID:0
,W/Settings( 6532): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/HtcWrapAdjustableCursorFactory( 6562): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,I/Babel_Crash( 6532): startup - clean
,D/MessageFrequencyProvider( 6562): onCreate
,I/Babel   ( 6532): deleted: false for 0
,I/art     (  960): Explicit concurrent mark sweep GC freed 30951(1762KB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 19MB/28MB, paused 1.330ms total 136.822ms
,D/MmsCustomizationProvider( 6562): query uri: content://htc-mms-customization/mms-ua/ua_string,
V/GetPrviateResource( 6562): GetPrviateResource
,V/GetPrviateResource( 6562): GetPrviateResource
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6532, uid=10112, userID:0
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6532, uid=10112, userID:0
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6532, uid=10112, userID:0
I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6532, uid=10112, userID:0
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6532, uid=10112, userID:0
,D/MessageCustFlag( 6562): sense_version=6.0
,D/MmsCustomizationProvider( 6562): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/BTAccessoryUtil( 6562): createReceiver
,D/BTAccessoryUtil( 6562): registerReceiver return intent = null,
I/Babel_SMS( 6532): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
D/PMS     (  960): acquireWL(18091142): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6532 10112 null
I/Babel_SMS( 6532): MmsConfig.loadFromDatabase
D/MessageCustFlag( 6562): sku_id=118
,D/HtcBuildUtils( 6562): getRATByHtcTelephonyCapability:1
,W/SystemReader( 6562): Cannot find qct_8960_interface, use default value instead
,E/Babel_SMS( 6532): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6532): MmsConfig.loadFromResources
E/Babel_SMS( 6532): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6532): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/VideoCapabilities( 6532): Unrecognized profile 2130706433 for video/avc,
,I/[PluginManager]RegisterService( 1531): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1531): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4443): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4443): Null package name or gms related package.  Ignoreing.
,D/PMS     (  960): acquireWL(301d1f45): PARTIAL_WAKE_LOCK  Icing 0x1 4443 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  960): acquireWL(104b869a): PARTIAL_WAKE_LOCK  AsyncService 0x1 6107 10167 null
,D/PMS     (  960): releaseWL(104b869a): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  960): acquireWL(1342efa8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6107 10167 null
,I/Icing   ( 4443): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  960): releaseWL(1342efa8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5950): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,W/VideoCapabilities( 6532): Unsupported mime video/x-ms-wmv
,D/PMS     (  960): releaseWL(301d1f45): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/Utils   ( 6532): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 6532): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6532): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6532): Unsupported mime audio/qcelp
W/VideoCapabilities( 6532): Unsupported mime video/x-ms-wmv
,I/UpdateIcingCorporaServi( 5950): UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] 
,I/VideoCapabilities( 6532): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6532): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6532): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6532): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6532): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6532): onServiceConnected
,W/Babel   ( 6532): Attempted to change video mute state without an active call.
,D/PMS     (  960): releaseWL(18091142): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6532): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6532): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6532): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6532): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6532): Installed default security provider GmsCore_OpenSSL
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  960):  packet count Tx=186 Rx=249
E/WifiTrafficPoller(  960): notifying of data activity 0
D/WIFI_ICON( 1221): WifiActivity: 0
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  960): handleMessage: E msg.what=131155
E/WifiStateMachine(  960): processMsg: ConnectedState
,E/WifiStateMachine(  960):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.9, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-926360283] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.9, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926360282] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  960):  get link layer stats 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  960): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  960): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.95 txretriesrate=0.00 rxrate=2.93 userTriggerdPenalty0
E/WifiStateMachine(  960):  good link -> stuck count =0
,E/WifiStateMachine(  960):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  960):  isHighRSSI       ---> score=61
E/WifiStateMachine(  960): handleMessage: X
D/WifiWatchdogStateMachine(  960): RSSI current: 3 new: -60, 3
,I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1628): loadItems() com.htc.launcher.pageview.WidgetManager@25ea4c43 +
I/Prism.WidgetManager( 1628): onLoadItems() +
,E/WifiStateMachine(  960): WiFiStateMachine SCAN ALARM,
D/PMS     (  960): acquireWL(37dbb0f9): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{1000}
E/WifiStateMachine(  960): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
E/WifiStateMachine(  960): processMsg: ConnectedState
V/AlarmManager(  960): sending alarm PendingIntent{2d3c1305: PendingIntentRecord{b3dcf5a android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455067553697, Int=20000
E/WifiStateMachine(  960):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2054 rssi=-60 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.9 fiv=90000 [on:0 tx:0 rx:0 period:625] from screen [on:0 period:-926359643]
D/PMS     (  960): releaseWL(37dbb0f9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:2054 rssi=-60 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.9 fiv=90000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-926359641]
E/WifiStateMachine(  960): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.95 rxSuccessRate=2.93 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  960): WifiStateMachine CMD_START_SCAN with age=11735 interval=90000 maxinterval=300000
E/WifiStateMachine(  960): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  960): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  960): has c0:ff:d4:d3:aa:48 freq=2412 age=631 ?=true
,E/WifiStateMachine(  960): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1330): WPS:  * UUID-E
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1330): WPS:  * Device Password ID (0),
D/wpa_supplicant( 1330): WPS:  * Manufacturer
D/wpa_supplicant( 1330): WPS:  * Model Name
D/wpa_supplicant( 1330): WPS:  * Model Number
D/wpa_supplicant( 1330): WPS:  * Device Name
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1330): P2P: * P2P IE header
D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1330): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x55a615d680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x55a615d680 after 0.000049 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000099 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  960): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  960): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  960): [1,455,067,553,709 ms] noteScanstart no scan source
E/WifiStateMachine(  960): handleMessage: X
,E/WifiDataStallTracker(  960): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  960): updateDataStallInfo: mDataStallTxRxSum={txSum=168 rxSum=133} preTxRxSum={txSum=168 rxSum=133}
D/WifiDataStallTracker(  960): updateDataStallInfo: NONE
D/WifiDataStallTracker(  960): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
,D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 0.081113 seconds
D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1330): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1330): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
I/wpa_supplicant( 1330): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 6
,D/wpa_supplicant( 1330): BSS: last_scan_res_used=5/32
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55a615d680 done in 0.082219 seconds
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  960): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  960): handleMessage: E msg.what=147461
E/WifiStateMachine(  960): processMsg: ConnectedState
,E/WifiStateMachine(  960):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
D/WifiStateMachine(  960): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  960): [1,455,067,553,792 ms] noteScanEnd no scan source
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  960): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2f565c2b sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  960): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  960): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  960): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  960): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  960):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  960): Gonzos 38:f8:89:11:e9:11 rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  960): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  960): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  960): ageScanResultsOut delay 40000 size 5 now 1455067553795
E/WifiAutoJoinController (  960): newSupplicantResults size=5 known=1 true
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  960): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  960): ssid=NG700
E/WifiAutoJoinController (  960): id=0
E/WifiAutoJoinController (  960): mode=station
E/WifiAutoJoinController (  960): pairwise_cipher=CCMP
E/WifiAutoJoinController (  960): group_cipher=CCMP
E/WifiAutoJoinController (  960): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  960): wpa_state=COMPLETED
E/WifiAutoJoinController (  960): ip_address=192.168.1.130
E/WifiAutoJoinController (  960): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  960): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  960): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  960): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  960): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  960): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  960): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  960): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  960): Done attemptAutoJoin status=0
E/WifiConfigStore(  960):  writeKnownNetworkHistory() num networks:1 n,eedWrite=false
E/WifiStateMachine(  960): handleMessage: X
,W/ResourcesManager( 1628): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  960):  packet count Tx=186 Rx=249
,W/asset   ( 1628): Copying FileAsset 0x55b9f5b010 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1628): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1628): onLoadItems() -
I/Prism.ItemManager( 1628): loadItems() com.htc.launcher.pageview.WidgetManager@25ea4c43 -
,D/PhoneApp( 1564): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1564): -- N1 =0
D/PhoneApp( 1564): -- N2 =0
D/PhoneApp( 1564): -- N3 =0
,D/Messaging( 6562): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6562): networkCode: 
,D/MessageCustFlag( 6562): sku_id=118
,D/MmsConfig( 6562): SIE smsPri: null,
D/MmsConfig( 6562): networkCode: 
,D/MmsConfig( 6562): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 6562): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 6562): ,
D/MmsAsyncWorkHandler( 6562): HM tk = 20001
D/ReportIndicatorCache( 6562): MSG_QUERY_REPORTS >>
D/SettingsManager( 6562): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@4bb9769
,D/Messaging( 6562): mNeedToUpdateDate2 start
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/AccFlag ( 1564): sku_id=118
,D/MmsAsyncWorkHandler( 6562): ,
D/MmsAsyncWorkHandler( 6562): HM tk = 20002
D/DraftCache( 6562): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6562): [DraftCache/1] refresh
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/MmsSmsV2Provider( 1564):  slotId = -1000,
D/MmsSmsV2Provider( 1564): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 6562): networkCode: 
,I/Messaging( 6562): mccmnc> ,
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 100
D/MmsSmsV2Provider( 1564):  slotId = -1000
D/MmsSmsV2Provider( 1564): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 6562): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 84,
,D/AccFlag ( 1564): sku_id=118
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
,D/MmsSmsV2Provider( 1564):  slotId = -1000
D/MmsSmsV2Provider( 1564): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6562): mNeedToUpdateDate2: false
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 84,
D/AccFlag ( 1564): sku_id=118
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
,D/MmsSmsV2Provider( 1564):  slotId = -1000
D/MmsSmsV2Provider( 1564): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 6562): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/DraftCache( 6562): [DraftCache/156] rebuildCache,
,D/PhoneStorageUtil( 6562): HtcWrapEnvironment.getSupportedStorages() >1,
D/PhoneStorageUtil( 6562): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6562): createReceiver
D/MessageCustFlag( 6562): sense_version=6.0
,D/Jerry   ( 6562): start to preload cursor >>>>>>>
,D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 84,
D/Jerry   ( 1564): URI_DRAFT
D/TelephUtils( 1564): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
V/MmsProvider( 1564): Update uri=content://mms, match=0
V/MmsProvider( 1564): selection=st=129 AND m_type!=134
,D/DraftCache( 6562): hasDraft() = false mNeedNotifyChange = true
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 100
D/MmsSmsV2Provider( 1564):  slotId = -1000
D/Messaging( 6562): Reset downloading state: 0
D/DraftCache( 6562): [DraftCache/156] rebuildCache time: 5
,V/MmsSystemEventReceiver( 6562): TransactionService is going to be woken up.,
,V/TransactionService( 6562): 1-Creating TransactionService,
,D/Messaging( 6562): ViewCache CreatePreload,
D/Messaging( 6562): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 6562): _has_set_default_values_2=true,
,V/TransactionService( 6562): onStartCommand: 1
D/MmsSystemEventReceiver( 6562): unRegisterForConnectionStateChanges
V/TransactionService( 6562): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 6562): Loading previous transactions.
,D/MsgPreferenceUtils( 6562): def_index: 0
,D/MsgPreferenceUtils( 6562): globalIndex = 1,
D/TelephUtils( 1564): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/AccFlag ( 1564): device_type: 1
,D/MsgPreferenceUtils( 6562): phone state: true,
D/MsgPreferenceUtils( 6562): sd state: false
D/MsgPreferenceUtils( 6562): vIndex = 0
D/TransactionService( 6562): Force clearing mTransactionList
,D/TransactionService( 6562): Force set service start id to 1
V/TransactionService( 6562): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6562): unRegisterForConnectionStateChanges
D/TransactionService( 6562): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 6562): Destroying TransactionService
,V/TransactionService( 6562): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  960):  packet count Tx=186 Rx=249
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  960):  packet count Tx=186 Rx=249
,E/WifiStateMachine(  960): handleMessage: E msg.what=131155,
E/WifiStateMachine(  960): processMsg: ConnectedState
E/WifiStateMachine(  960):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:2369] from screen [on:0 period:-926357265] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926357264] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960):  get link layer stats 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiConfigStore(  960): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  960): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.48 txretriesrate=0.00 rxrate=1.46 userTriggerdPenalty0
E/WifiStateMachine(  960):  good link -> stuck count =0
E/WifiStateMachine(  960):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  960):  isHighRSSI       ---> score=61
,E/WifiStateMachine(  960): handleMessage: X
D/WifiWatchdogStateMachine(  960): RSSI current: 3 new: -60, 3
,D/ActivityManager(  960): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{af32dd #7 A=.Prism U=0 sz=1}
W/PMS     (  960): mWirelessDisplayManager is null
W/PMS     (  960): mWirelessDisplayManager is still null
,I/SensorManager(  960): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1e170e6d
I/PMS     (  960): Going to sleep due to screen timeout (uid 1000)...
W/SensorService(  960): Following SensorService logs are not warning, just make sure they are printed
I/PMS     (  960): Sleeping (uid 1000)...
W/SensorService(  960): disable: get sensor name = Accelerometer Sensor
D/XAN-DPS (  960): prepareColorFade 1
,W/SensorService(  960): pid=960, uid=1000
W/PMN     (  960): goingToSleep
W/SensorService(  960): Active sensors: size = 4
D/PMS     (  960): acquireWL(20062e52): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 960 1000 null
W/SensorService(  960): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  960): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  960): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  960): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  960): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1e170e6d, eanble = 0, strlen(mName) = 91
W/SensorService(  960): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  960): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@fa73f58
W/SensorService(  960): Listener[1] = com.htc.smartdim.sensor_eye@2ad493aa
W/SensorService(  960): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/Adreno-EGL(  960): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  960): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  960): Build Date: 03/09/15 Mon
I/Adreno-EGL(  960): Local Branch: 
I/Adreno-EGL(  960): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  960): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  960):                  d74aa161a12b9c6fc6332151
W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMN     (  960): goingToSleep done
I/FeedHostManager( 1628): [onPause]
I/FeedProviderManager( 1628): onPause
,I/FeedHostManager( 1628): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@17d3fa04
I/SocialFeedProvider( 1628): +onPause
I/SocialFeedProvider( 1628): -onPause
D/AlarmManager(  960): ACTION_SCREEN_ON
,I/AlarmManager(  960): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  960): [AlarmQueuing] done recovering
I/AlarmManager(  960): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  960): [AlarmQueuing] done EPS screen off alarm recovering
,I/ActivityManager(  960): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6628 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,D/PMS     (  960): releaseWL(20062e52): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null,
E/WifiTrafficPoller(  960): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  960):  packet count Tx=186 Rx=249
,E/WifiDataStallTracker(  960): ENABLE_DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  960): updateDataStallInfo: mDataStallTxRxSum={txSum=168 rxSum=133} preTxRxSum={txSum=168 rxSum=133}
D/WifiDataStallTracker(  960): updateDataStallInfo: NONE
D/WifiDataStallTracker(  960): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,E/WifiStateMachine(  960): handleMessage: E msg.what=131167
E/WifiStateMachine(  960): processMsg: ConnectedState
E/WifiStateMachine(  960):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
V/SRS_Proc(  422): ParamSet string: screen_state=on
E/audio_a2dp_hw(  422): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
,E/WifiStateMachine(  960):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: E msg.what=155650
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
E/WifiStateMachine(  960):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  960):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1330): SET_SCREEN_ON:On
I/wpa_supplicant( 1330): htc_wext_set_keepalive +
I/wpa_supplicant( 1330): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1330): getPrivFuncNum +	
I/wpa_supplicant( 1330): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1330): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1330): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  960): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
D/WifiStateMachine(  960): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/NetworkPolicy(  960): updateScreenOn: false
E/WifiStateMachine(  960): handleScreenStateChanged Exit: true
V/NetworkPolicy(  960): updateIfacesLocked()
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131154
E/WifiStateMachine(  960): processMsg: ConnectedState
E/WifiStateMachine(  960):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,D/NetworkManagementService(  960): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  960): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  960): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131127
,E/WifiStateMachine(  960): processMsg: ConnectedState
E/WifiStateMachine(  960):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
,E/WifiStateMachine(  960):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131129
E/WifiStateMachine(  960): processMsg: ConnectedState
E/WifiStateMachine(  960):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1330): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  960): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
,E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=35 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  960): handleMessage: X
,D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/ResourcesManager( 6628): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/GpsLocationProvider(  960): receive broadcast intent, action: android.intent.action.SCREEN_ON,
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false)
,D/XAN-DPS (  960): prepareColorFade done
,D/XAN-DPS (  960): setBrightness to 0
,I/SensorManager(  960): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@fa73f58
W/SensorService(  960): Following SensorService logs are not warning, just make sure they are printed
I/DisplayManagerService(  960): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  960): disable: get sensor name = CM32181 Light sensor
V/ActivityManager(  960): Display changed displayId=0
D/DotMatrix( 1332): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1332): [EventService] mbHDMIConnect: false, mCoverOn:false
,W/SensorService(  960): pid=960, uid=1000
W/SensorService(  960): Active sensors: size = 3
W/SensorService(  960): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  960): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  960): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  960): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@fa73f58, eanble = 0, strlen(mName) = 66
W/SensorService(  960): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  960): Listener[0] = com.htc.smartdim.sensor_eye@2ad493aa
W/SensorService(  960): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL true Token 12 num clients 6
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,D/PMS     (  960): acquireWL(19b4dd9e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): acquireWL(13bcb07f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms},
,I/CalendarProvider2( 6628): Created com.android.providers.calendar.CalendarAlarmManager@4bb9769(com.htc.providers.calendar.HtcCalendarProvider@3037a5ee),
D/PMS     (  960): releaseWL(19b4dd9e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(13bcb07f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 6628): wait start:true
,D/AlarmManager(  960): ACTION_SCREEN_OFF
,I/AlarmManager(  960): [AlarmQueuing] screen off now: 
I/AlarmManager(  960): [AlarmQueuing] data connection: true
I/AlarmManager(  960): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  960): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  960): stopDataStallAlarm 
E/WifiDataStallTracker(  960): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  960): handleMessage: E msg.what=131167
E/WifiStateMachine(  960): processMsg: ConnectedState
E/WifiStateMachine(  960):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine(  960): processMsg: ConnectModeState,
D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
V/SRS_Proc(  422): ParamSet string: screen_state=off
,D/NetworkPolicy(  960): updateScreenOn: false
I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@219a8e2, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
V/NetworkPolicy(  960): updateIfacesLocked()
E/audio_a2dp_hw(  422): adev_set_parameters: ERROR: set param called even when stream out is null
D/NetworkManagementService(  960): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  960):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
E/WifiStateMachine(  960):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  960):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1330): SET_SCREEN_ON:Off
I/wpa_supplicant( 1330): htc_wext_set_keepalive +
I/wpa_supplicant( 1330): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1330): getPrivFuncNum +	
I/wpa_supplicant( 1330): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1330): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1330): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1330): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  960): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  960): backgroundScan enabled=true startBackgroundScanIfNeeded:false
W/SensorService(  960): Following SensorService logs are not warning, just make sure they are printed
E/WifiStateMachine(  960): handleScreenStateChanged Exit: false
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131154
E/WifiStateMachine(  960): processMsg: ConnectedState
E/WifiStateMachine(  960):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiController(  960): handleMessage: E msg.what=155651
E/WifiStateMachine(  960):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  960): handleMessage: X
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
,D/WifiController(  960): handleMessage: X
W/SensorService(  960): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  960): pid=1221, uid=10041
,W/SensorService(  960): Active sensors: size = 4
W/SensorService(  960): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  960): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  960): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  960): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  960): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@219a8e2, eanble = 1, strlen(mName) = 56
W/SensorService(  960): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  960): Listener[0] = com.htc.smartdim.sensor_eye@2ad493aa
W/SensorService(  960): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@219a8e2
W/SensorService(  960): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1332): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  960): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/CalendarProvider2( 6628): wait end:false
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false)
D/ContactMessageStore( 1564): start background delete task...
,D/PMS     (  960): acquireWL(9389b50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  960): releaseWL(9389b50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): acquireWL(1c4cb149): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1564): size: 0 , 0
,D/ContactMessageStore( 1564): Background delete complete
,D/PMS     (  960): releaseWL(1c4cb149): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  960): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6659 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145)
,I/RemoteViews( 1221): apply : com.htc.updater 0 14 1 36
,W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  960): Setting HAL interactive mode to false
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  960): Excessive delay in setPowerMode(): 297ms
D/PowerUsageList:PowerUsageHelper( 6659): MY_DEBUG = false
,D/PMS     (  960): Setting HAL interactive mode to false done
D/PMS     (  960): Setting HAL auto-suspend mode to true
D/PMS     (  960): Setting HAL auto-suspend mode done
W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/InputMethodManagerService(  960): screenObserver, isScreenOn=false
D/StatusBarManagerService(  960): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  960): Disable input method client, pid=1628
,D/PMS     (  960): acquireWL(c141c7c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
D/HABCtrl (  960): TPE algorithm. remove timeout.
D/PMS     (  960): OOBE c monitor 11
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(c141c7c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/InputManager(  960): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false),
D/UsbnetService(  960): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  960): updateBatteryInfo
,D/UsbnetService(  960): onReceive BATTERY_CHANGED
,D/NotificationService(  960): plugged=true pluggin=true,
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  960): runPSCheck
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  960): >> updateStatus
,D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState,
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
,D/SmartSyncUtils( 6659): isEpsOn(), nState = 0
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): << updateStatus
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
D/NfcService( 1579): ScreenObserver: OFF
D/NfcService( 1579): applyRouting - 0
,D/PMS     (  960): acquireWL(9261905): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1579 1027 null
,D/NfcService( 1579): applyRouting -2
D/NfcService( 1579): applyRouting
D/NfcService( 1579): Ignore this applyRouting...
,D/PMS     (  960): releaseWL(9261905): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PMS     (  960): acquireWL(1fb65d5a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6659 1000 null,
,W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  960): Init customizeScreenOffDelayClass error
,D/PMS     (  960): releaseWL(1fb65d5a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,I/ClockController( 1221): stop clock update:screen off,
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6659): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6659): isEpsOn(), nState = 0,
,W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  960): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2ad493aa
W/SensorService(  960): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  960): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  960): pid=960, uid=1000
E/ActivityThread(  960): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@20fcdb9b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  960): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@20fcdb9b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  960): 	,at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  960): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  960): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  960): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  960): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  960): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  960): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  960): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  960): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  960): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  960): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  960): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  960): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  960): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  960): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  960): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  960): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  960): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/SensorService(  960): Active sensors: size = 3
W/SensorService(  960): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  960): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  960): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  960): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2ad493aa, eanble = 0, strlen(mName) = 36
W/SensorService(  960): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  960): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@219a8e2
W/SensorService(  960): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  960): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  960): disable: get sensor name = CM36686 Proximity sensor
W/SensorService(  960): pid=960, uid=1000
W/SensorService(  960): Active sensors: size = 2
W/SensorService(  960): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  960): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  960): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2ad493aa, eanble = 0, strlen(mName) = 36
W/SensorService(  960): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  960): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@219a8e2
W/SensorService(  960): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  960): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2ad493aa
,I/ActivityManager(  960): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6690 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  960): Killing 6254:com.htc.cs.dm/u0a99 (adj 15): empty #17,
D/Process (  960): killProcessQuiet, pid=6254
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6254
,I/PowerUsageList:PowerUsageHelper( 6659): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/SmartSyncUtils( 6659): getMobilePolicyEnabled, result = true
D/Process (  960): killProcessQuiet, pid=6277
I/ActivityManager(  960): Killing 6277:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 ,
,E/WifiTrafficPoller(  960): ADD_CLIENT: 7,
D/WifiService(  960): New client listening to asynchronous messages
,D/PowerUsageList:BatterySipperExt( 6659): gen(), null == sipper.uidObj, userId = 0,
,E/WifiTrafficPoller(  960): TRAFFIC_STATS_POLL false Token 13 num clients 7
,I/ActivityManager(  960): Recipient 6277,
,D/PowerUsageList:PowerUsageHelper( 6659): MY_DEBUG = false
,D/Process (  960): killProcessQuiet, pid=6071,
I/ActivityManager(  960): Killing 6071:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/CalendarProvider2( 6628): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6628): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  960): Recipient 6071,
,I/ActivityManager(  960): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6715 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
D/Process (  960): killProcessQuiet, pid=6308
I/ActivityManager(  960): Killing 6308:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6308
,D/PMS     (  960): releaseWL(c91be29): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/Process (  960): killProcessQuiet, pid=5620
,I/ActivityManager(  960): Killing 5620:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 6715): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  960): Recipient 5620
,D/CalendarApplication( 6715): onCreate
,D/ProviderChangeReceiver( 6715): ---------------------------------------------------
,D/ProviderChangeReceiver( 6715): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/ActivityManager(  960): Killing 5484:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=5484
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6715): start to updateAlertNotification!
,I/ActivityManager(  960): Recipient 5484
,E/WifiDataStallTracker(  960): DATA_MONITOR_POLL false Token 3
,D/HtcAlertService( 6715): No fired or scheduled alerts
,D/HtcAlertUtils( 6715): -- cancelReminderNotification --
,D/HtcAlertUtils( 6715): broadcastExistReminder!
,D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  960): handleMessage: E msg.what=131155
,E/WifiStateMachine(  960): processMsg: ConnectedState
,E/WifiStateMachine(  960):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-926354243] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926354242] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960): handleMessage: X
,E/WifiStateMachine(  960): handleMessage: E msg.what=131155
E/WifiStateMachine(  960): processMsg: ConnectedState
,E/WifiStateMachine(  960):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:707] from screen [on:0 period:-926353534] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-926353532] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  960): handleMessage: X
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  960): DATA_MONITOR_POLL false Token 3
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/ActivityManager(  960): Killing 5678:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=5678
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 5678
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ContactMessageStore( 1564): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1564): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  960): acquireWL(14744081): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000},
V/AlarmManager(  960): sending alarm PendingIntent{91fd293: PendingIntentRecord{567a2d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=115160, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{5ecf526: PendingIntentRecord{39fa2567 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142178, Int=0
,D/PMS     (  960): releaseWL(14744081): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  960): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  960): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
D/PMS     (  960): acquireWL(3b917f14): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 960 1000 null,
,D/libc    (  960): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  960): [NET] android_getaddrinfofornet-, err=8
D/libc    (  960): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  960): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  960): [NET] android_getaddrinfo_proxy+
,D/libc    (  960): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  960): [NET] android_getaddrinfo_proxy-, success
D/libc    (  960): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  960): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  960): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  960): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  960): acquireWL(b917880): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 960 1000 null
D/GpsLocationProvider(  960): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  960): releaseWL(3b917f14): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  960):  [handleDownloadXtraData]inject done.
,D/PMS     (  960): releaseWL(b917880): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  960): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  960): acquireWL(32a77eb9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/BatteryService(  960): n_update end
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/PMS     (  960): releaseWL(32a77eb9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): runPSCheck
D/WifiController(  960): handleMessage: E msg.what=155652
D/HtcPowerSaver(  960): Checking...
D/WifiController(  960): processMsg: DeviceActiveState
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
,D/WifiController(  960): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  960): battery changed pluggedType: 2
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  960): << updateStatus
D/WifiController(  960): handleMessage: X
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1564): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  960): acquireWL(160382fe): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{3fdc5a5f: PendingIntentRecord{18d59cac android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455067612368, Int=0
D/PMS     (  960): acquireWL(1b84d75): PARTIAL_WAKE_LOCK  *backup* 0x1 960 1000 null
V/AlarmManager(  960): sending alarm PendingIntent{91fd293: PendingIntentRecord{567a2d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=175160, Int=0
,V/AlarmManager(  960): sending alarm PendingIntent{90d10a: PendingIntentRecord{15163d7b android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=201185, Int=0,
V/AlarmManager(  960): sending alarm PendingIntent{955d798: PendingIntentRecord{38cd4bf1 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190374, Int=0
,W/BackupManagerService(  960): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  960): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  960): releaseWL(1b84d75): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  960): acquireWL(29f2f3d6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(160382fe): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  960): acquireWL(10413657): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  960): releaseWL(29f2f3d6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  960): releaseWL(10413657): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  960): acquireWL(22c88829): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(22c88829): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  960): acquireWL(2194a7ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(2194a7ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): acquireWL(35f6994f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): acquireWL(3ecf88dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  960): acquireWL(28790ba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(35f6994f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
I/VacuumService( 1884): Vacuum at: now=1455067646287 tag=VacuumService
,D/PMS     (  960): releaseWL(3ecf88dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  960): acquireWL(343a56c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
I/GoogleURLConnFactory( 1884): Using platform SSLCertificateSocketFactory
,W/Uploader( 1884): No account for auth token provided
,D/PMS     (  960): releaseWL(343a56c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  960): acquireWL(29f81361): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(29f81361): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1884): No account for auth token provided,
,W/Uploader( 1884): No account for auth token provided,
,W/Uploader( 1884):  no longer exists, so no auth token.,
,W/Uploader( 1884): No account for auth token provided,
,I/art     ( 1884): Explicit concurrent mark sweep GC freed 21713(1203KB) AllocSpace objects, 5(420KB) LOS objects, 48% free, 4MB/8MB, paused 1.112ms total 91.988ms,
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/Uploader( 1884): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,E/Uploader( 1884): ,	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1884): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1884): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1884): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1884): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1884): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1884): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1884): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1884): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1884): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,D/PMS     (  960): releaseWL(28790ba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  960): acquireWL(3b459c6a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(3b459c6a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  960): acquireWL(1648155b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(1648155b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1531): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@28ff57c8
D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/Process (  960): killProcessQuiet, pid=6383
I/ActivityManager(  960): Killing 6383:com.test.thalitest/u0a366 (adj 15): empty #17
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6383
E/InputEventReceiver( 1398): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{25cefe13 uid 10366 pid 6383} (c)'
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  960): acquireWL(129501f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(129501f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): onReceive BATTERY_CHANGED
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): BroadcastReceiver::onReceive-
,D/PMS     (  960): runPSCheck
D/WifiController(  960): handleMessage: E msg.what=155652
D/HtcPowerSaver(  960): Checking...
D/WifiController(  960): processMsg: DeviceActiveState
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  960): acquireWL(ddb96d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(ddb96d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): runPSCheck
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  960): >> updateStatus
D/PowerUI ( 1221): closing low battery warning: level=100
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): << updateStatus
D/UsbnetService(  960): onReceive BATTERY_CHANGED
,D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1330): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
,D/wpa_supplicant( 1330): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  960): acquireWL(5191536): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(5191536): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  960): updateBatteryInfo
,D/PMS     (  960): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): >> updateStatus
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  960): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  960): << updateStatus
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  960): Explicit concurrent mark sweep GC freed 39351(2MB) AllocSpace objects, 5(1160KB) LOS objects, 33% free, 18MB/28MB, paused 1.490ms total 162.185ms,
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): ,	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): ,	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 6030): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6030): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6030): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6030): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6030): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6030): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6030): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,W/System  ( 6030): Ignoring header User-Agent because its value was null.
,D/libc    ( 6030): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6030): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6030): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6030): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6030): [NET] android_getaddrinfo_proxy+
D/libc    ( 6030): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6030): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 4
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): acquireWL(3448d928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  960): n_update end
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  960): releaseWL(3448d928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): onReceive BATTERY_CHANGED
,D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  960): Checking...
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  960): acquireWL(121ed641): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000},
V/AlarmManager(  960): sending alarm PendingIntent{91fd293: PendingIntentRecord{567a2d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=235160, Int=0
,V/AlarmManager(  960): sending alarm PendingIntent{26871127: PendingIntentRecord{39e65fd4 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1455067785839, Int=0,
,V/AlarmManager(  960): sending alarm PendingIntent{a41957d: PendingIntentRecord{3526ec72 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455067865340, Int=1800000,
,D/PMS     (  960): acquireWL(fc998c3): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4443 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): acquireWL(4d70c79): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4443 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  960): releaseWL(121ed641): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  960): releaseWL(fc998c3): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/EventLogService( 4443): Aggregate from 1455067542066 (log), 1455066065298 (data),
,D/PMS     (  960): releaseWL(4d70c79): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 1
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  960): acquireWL(20b2f735): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  960): n_update end
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): releaseWL(20b2f735): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/PMS     (  960): runPSCheck
D/WifiController(  960): handleMessage: E msg.what=155652
D/HtcPowerSaver(  960): Checking...
D/WifiController(  960): processMsg: DeviceActiveState
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PMS     (  960): acquireWL(1b8397ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/BatteryService(  960): n_update end
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/PMS     (  960): releaseWL(1b8397ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  960): handleMessage: E msg.what=155652
D/NotificationService(  960): plugged=true pluggin=true
D/WifiController(  960): processMsg: DeviceActiveState
,D/PMS     (  960): runPSCheck,
D/WifiController(  960): processMsg: StaEnabledState
D/HtcPowerSaver(  960): Checking...
,D/WifiController(  960): processMsg: DefaultState
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): handleMessage: X
D/WifiController(  960): battery changed pluggedType: 2
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  960): << updateStatus
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  960): acquireWL(3f835d3b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(3f835d3b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/PMS     (  960): runPSCheck
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): >> updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  960): << updateStatus
,D/PowerUI ( 1221): closing low battery warning: level=100
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1564): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1564): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1564): sku_id=118
D/ContactMessageStore( 1564): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1564): start background delete task...
,D/ContactMessageStore( 1564): size: 0 , 0
,D/ContactMessageStore( 1564): Background delete complete
,D/PMS     (  960): acquireWL(27f8dc58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/PMS     (  960): releaseWL(27f8dc58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  960): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  960): updateBatteryInfo
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: StaEnabledState
D/PMS     (  960): runPSCheck
D/WifiController(  960): processMsg: DefaultState
D/HtcPowerSaver(  960): Checking...
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): >> updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(1c28d1b1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(1c28d1b1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  960): plugged=true pluggin=true,
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  960): runPSCheck
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  960): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  960): handleMessage: E msg.what=155652
I/HtcPowerSaver(  960): << updateStatus
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  960): acquireWL(d2b6696): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(d2b6696): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  960): updateBatteryInfo
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): battery changed pluggedType: 2
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): >> updateStatus
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  960): handleMessage: E msg.what=155652
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  960): acquireWL(2c09217): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(2c09217): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  960): updateBatteryInfo
D/PMS     (  960): runPSCheck
D/HtcPowerSaver(  960): Checking...
I/HtcPowerSaver(  960): >> updateStatus
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): << updateStatus
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  960): acquireWL(2d4b6604): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(2d4b6604): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  960): updateBatteryInfo
D/PMS     (  960): runPSCheck
D/HtcPowerSaver(  960): Checking...
I/HtcPowerSaver(  960): >> updateStatus
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(2d47d7ed): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{91fd293: PendingIntentRecord{567a2d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=475160, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{4c14653: PendingIntentRecord{20ea6b90 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804908, Int=0
,V/AlarmManager(  960): sending alarm PendingIntent{19af5622: PendingIntentRecord{1c3238b3 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936432, Int=0
,I/ActivityManager(  960): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6753 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  960): sending alarm PendingIntent{1c1ade70: PendingIntentRecord{21d705e9 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1455068163888, Int=0
,D/PMS     (  960): acquireWL(2790b26e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(2790b26e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
D/PMS     (  960): releaseWL(2d47d7ed): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/GCM     ( 1884): Message class com.google.f.a.a.i
D/PMS     (  960): acquireWL(1f27719c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(1f27719c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,E/cutils-trace( 6775): Error opening trace file: Permission denied (13),
I/dex2oat ( 6775): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6775): dex2oat: override thread count:4,
,I/dex2oat ( 6775): dex2oat took 673.006ms (threads: 4),
,I/PushClient( 6753): ApplicationMonitor {cfc32fa}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6753): ApplicationMonitor {cfc32fa}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6753): ApplicationMonitor {cfc32fa}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6753): ApplicationMonitor {cfc32fa}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6753): ApplicationMonitor {cfc32fa}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6753): ApplicationMonitor {cfc32fa}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6753): ApplicationMonitor {cfc32fa}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false,
I/PushClient( 6753): ApplicationMonitor {cfc32fa}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6753): ApplicationMonitor {cfc32fa}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6753): PnsModel {216d4125}: update(): Update registration caused by: alarm,
,I/PushClient( 6753): PnsConfigModel {27e18b20}: <init>(): Use dm-client for provisioning.
,W/System.err( 6753): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6753): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6753): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6753): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  960): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6782 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6782): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6782 dbg=false s=true
,I/DeviceManagement( 6782): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6782): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6782): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6782): WorkflowService: Starting workflow service
,I/DeviceManagement( 6782): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@cfc32fa] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6782): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6782): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6782): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6782): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6782): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6782): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6782): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6782): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@cfc32fa],
,I/DeviceManagement( 6782): WorkflowService: Stopping workflow service
,I/ActivityManager(  960): Killing 6485:com.google.android.setupwizard/u0a77 (adj 15): empty #17,
D/Process (  960): killProcessQuiet, pid=6485
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6485,
,I/PushClient( 6753): PnsModel {216d4125}: update(): The registration record has not expired yet. No need to update.
,I/ActivityManager(  960): Killing 6432:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=6432,
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6432
,I/bt-btm  ( 3100): Received oneshot timer event complete
D/PMS     (  960): acquireWL(79ac3a0): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{1002}
I/bt-btm  ( 3100): btm_ble_timeout
V/AlarmManager(  960): sending alarm PendingIntent{12403b59: PendingIntentRecord{1744931e com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940312, Int=0
I/bt-btm  ( 3100): btm_gen_resolvable_private_addr
,D/PMS     (  960): releaseWL(79ac3a0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1002}
,D/PMS     (  960): acquireWL(3439f7ff): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3100 1002 null,
,D/bt-btm  ( 3100): btm_ble_rand_enc_complete,
I/bt-btm  ( 3100): btm_gen_resolve_paddr_low
D/bt-smp  ( 3100): smp_encrypt_data,
W/bt-smp  ( 3100): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3100): Plain text(LSB ~ MSB) = 32 72 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3100): Encrypted text(LSB ~ MSB) = 6e 19 80 26 08 73 8d 63 7f ee 5c b3 ab e8 f9 71 
I/bt-btm  ( 3100): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3100): Stopping oneshot timer
D/bt-btm  ( 3100): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  960): releaseWL(3439f7ff): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): acquireWL(347879cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/PMS     (  960): releaseWL(347879cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/NotificationService(  960): plugged=true pluggin=true
,D/WifiController(  960): handleMessage: E msg.what=155652
D/PMS     (  960): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  960): Checking...
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  960): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): battery changed pluggedType: 2
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  960): handleMessage: X
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  960): acquireWL(c303415): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{91fd293: PendingIntentRecord{567a2d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=955161, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{3da2c32a: PendingIntentRecord{12f64040 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455068411893, Int=0
,W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  960): releaseWL(c303415): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,D/PowerUsageList:PowerUsageHelper( 6659): MY_DEBUG = false
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PowerUsageService( 6659): repeat time = 1455069311942,
,I/PowerUsageList:PowerUsageHelper( 6659): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6659): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  960): acquireWL(199966b8): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{1000},
V/AlarmManager(  960): sending alarm PendingIntent{decfc91: PendingIntentRecord{c01e7f6 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455068457302, Int=0
D/SmartSyncUtils( 6659): isEpsOn(), nState = 0,
,D/PMS     (  960): releaseWL(199966b8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  960): acquireWL(fc0e7f7): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6659 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6659): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6659): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6659): AlarmOnTime = -1,
,D/SmartSyncScreenOnOffTimeReceiver( 6659): SettingOnTime = 1455084000000, randomSettingOnTime = 1455083581000
D/SmartSyncScreenOnOffTimeReceiver( 6659): SettingOffTime = 1455148800000, randomSettingOffTime = 1455153320000
,D/SmartSyncScreenOnOffTimeReceiver( 6659): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6659): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6659): bNightModeTurnOffOnce = false
,D/PMS     (  960): acquireWL(1bda3664): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{dd3d0cd: PendingIntentRecord{385c8d82 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1455068457338, Int=0
D/PMS     (  960): releaseWL(fc0e7f7): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncDataLinkTurnOffService( 6659): SMARTSYNC_TURN_OFF_NETWORK, current time = 1455068457350, randomOffTime = 1455153320000, newRandomOffTime = 1455153320000
,D/SmartSyncDataLinkTurnOffService( 6659): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 1455083581000, randomMobileOnTime = 1455083581000
,D/PMS     (  960): releaseWL(1bda3664): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/SmartSyncUtils( 6659): getMobilePolicyEnabled, result = true,
D/SmartSyncDataLinkTurnOffService( 6659): turnOffMobile bPolicyEnabled = true
,D/SmartSyncUtils( 6659): isWifiHotSpotEnabled = false,
D/SmartSyncDataLinkTurnOffService( 6659): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  960): getProviders()=[gps, network],
D/LocationManagerService(  960): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  960): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1],
D/SmartSyncDataLinkTurnOffService( 6659): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6659): isCharging status = 5,
,D/SmartSyncDataLinkTurnOffService( 6659): turnOffWifi ui setting = true
,D/SmartSyncUtils( 6659): isWifiHotSpotEnabled = false,
I/ActivityManager(  960): Cannot resolve ContentProvider=com.htc.vowifi
,D/SmartSyncUtils( 6659): state = 0
E/ActivityThread( 6659): Failed to find provider info for com.htc.vowifi
,D/SmartSyncDataLinkTurnOffService( 6659): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 6659): turnOffWifi bWifiConnected = true
,D/PMS     (  960): acquireWL(2f3654d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(2f3654d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/PMS     (  960): runPSCheck
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  960): acquireWL(10d9acc9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{91fd293: PendingIntentRecord{567a2d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1015160, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{2bc9ffce: PendingIntentRecord{1846deef com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1455068637403, Int=0
W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  960): releaseWL(10d9acc9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/SmartSyncDataLinkTurnOffService( 6659): turnOffWifi ui setting = true,
D/SmartSyncUtils( 6659): isWifiHotSpotEnabled = false
I/ActivityManager(  960): Cannot resolve ContentProvider=com.htc.vowifi
D/SmartSyncUtils( 6659): state = 0
E/ActivityThread( 6659): Failed to find provider info for com.htc.vowifi,
D/SmartSyncDataLinkTurnOffService( 6659): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 6659): turnOffWifi bWifiConnected = true,
D/LocationManagerService(  960): getProviders()=[gps, network]
,D/LocationManagerService(  960): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  960): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1],
D/SmartSyncDataLinkTurnOffService( 6659): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6659): isCharging status = 5
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  960): User[0] Flushing usage stats to disk
,D/PMS     (  960): acquireWL(1c474c85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
,I/BatteryService(  960): n_update end,
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): releaseWL(1c474c85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
,D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  960): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/PMS     (  960): runPSCheck
,D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: DeviceActiveState
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  960): processMsg: StaEnabledState
I/HtcPowerSaver(  960): << updateStatus
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
D/HeadsetStateMachine( 3100): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
