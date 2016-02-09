#### Test 583805004251330_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=163 Rx=213
I/HtcModeClient( 3271): handler message = 4011
E/HtcModeClient( 3271): Check connection and retry 11 times.
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-959903037] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959903036] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1363): environment dirty rate=0 [0][0][0]
--------- beginning of system
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -66 abnormalRssiCnt = 0 newLinkSpeed = 57
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-66 linkspeed=57
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.42 txretriesrate=0.00 rxrate=0.48 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -66, 3
E/cutils-trace( 6656): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6656): ====startRecUseTime====
D/htc.customization.log.level( 6656):  is 
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
W/CustomizationLogLevel( 6656): Level value is invalid, use default level 2
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  970):  packet count Tx=163 Rx=214
E/WifiTrafficPoller(  970): notifying of data activity 1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/CustomizationManager( 6656):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 6656): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6656): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6656): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6656): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6656): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6656): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6656): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6656): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6656): Parsing tag category name = system
I/CustomizationCIDLoader( 6656): Parsing tag category name = application
I/CustomizationCIDLoader( 6656): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6656): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6656): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6656): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6656): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6656): add string-array item, value = 42507
I/CustomizationCIDLoader( 6656): add string-array item, value = 21902
I/CustomizationCIDLoader( 6656): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6656): add string-array item, value = 23420
I/CustomizationCIDLoader( 6656): add string-array item, value = 22299
I/CustomizationCIDLoader( 6656): add string-array item, value = 24002
I/CustomizationCIDLoader( 6656): add string-array item, value = 23210
I/CustomizationCIDLoader( 6656): add string-array item, value = 23205
I/CustomizationCIDLoader( 6656): add string-array item, value = 23806
I/CustomizationCIDLoader( 6656): add string-array item, value = 23430
I/CustomizationCIDLoader( 6656): add string-array item, value = 23408
I/CustomizationCIDLoader( 6656): add string-array item, value = 27205
I/CustomizationCIDLoader( 6656): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6656): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6656):  Read CID file spent 0.105 (s)
D/CustomizationManager( 6656):  All configurations done spent 0.106 (s)
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6656 on display 0
D/PMS     (  970): acquireHCC(1b342ad0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
D/PMS     (  970): acquireHCC(2721cac9): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
W/asset   (  970): Copying FileAsset 0x559e0cdb30 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  970): acquireWL(26f923fc): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
I/AnimationUtil(  970): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1630): [onPause]
I/FeedProviderManager( 1630): onPause
I/FeedHostManager( 1630): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@306f875c
I/SocialFeedProvider( 1630): +onPause
I/SocialFeedProvider( 1630): -onPause
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  970): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6674 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  970): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
W/asset   ( 6674): Copying FileAsset 0xac30e120 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1630): [trimMemory] 20
I/WebViewFactory( 6674): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6674): Time to load native libraries: 10 ms (timestamps 7950-7960)
I/LibraryLoader( 6674): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6674): Binding Chromium to main looper Looper (main, tid 1) {3a929162}
I/LibraryLoader( 6674): Expected native library version number "",actual native library version number ""
I/chromium( 6674): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6674): Initializing chromium process, singleProcess=true
W/art     ( 6674): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6674): ApplicationContext is null in ApplicationStatus
D/PMS     (  970): acquireWL(22f62e83): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10072}
V/AlarmManager(  970): sending alarm PendingIntent{214fe800: PendingIntentRecord{37b5f839 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455034009857, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{1f323e7e: PendingIntentRecord{2ae32fdf com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455034011195, Int=536832000
V/AlarmManager(  970): sending alarm PendingIntent{3424f463: PendingIntentRecord{1dc46860 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455034002045, Int=20000
V/CheckinService( 4487): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
D/PMS     (  970): acquireWL(20cb842c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4487 10024 WorkSource{10024 com.google.android.gms}
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  970): handleMessage: E msg.what=131143
E/WifiStateMachine(  970): processMsg: ConnectedState
D/PMS     (  970): releaseWL(22f62e83): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  970):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):0 dur:49 rssi=-66 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=0.5 list=2412 [on:0 tx:0 rx:0 period:887] from screen [on:0 period:-959902128]
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:49 rssi=-66 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=0.5 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959902127]
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.42 rxSuccessRate=0.48 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-66
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN with age=60604 interval=60000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN try full band scan age=60604 interval=60000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1363): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1363): wpa_supplicant_scan enter
D/wpa_supplicant( 1363): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1363): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1363): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1363): WPS:  * Request Type
D/wpa_supplicant( 1363): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1363): WPS:  * UUID-E
D/wpa_supplicant( 1363): WPS:  * Primary Device Type
D/wpa_supplicant( 1363): WPS:  * RF Bands (3)
D/wpa_supplicant( 1363): WPS:  * Association State
D/wpa_supplicant( 1363): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1363): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1363): WPS:  * Manufacturer
D/wpa_supplicant( 1363): WPS:  * Model Name
D/wpa_supplicant( 1363): WPS:  * Model Number
D/wpa_supplicant( 1363): WPS:  * Device Name
D/wpa_supplicant( 1363): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1363): P2P: * P2P IE header
D/wpa_supplicant( 1363): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1363): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1363): wlan0: Add radio work 'scan'@0x5577d78860
D/wpa_supplicant( 1363): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1363): wlan0: Starting radio work 'scan'@0x5577d78860 after 0.000044 second wait
D/wpa_supplicant( 1363): wlan0: nl80211: scan request
D/wpa_supplicant( 1363): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1363): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1363): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1363): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1363): wlan0: Own scan request started a scan in 0.000122 seconds
I/wpa_supplicant( 1363): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
D/PMS     (  970): acquireWL(30afc48a): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4487 10024 WorkSource{10024 com.google.android.gms}
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  970): [1,455,034,011,220 ms] noteScanstart no scan source
E/WifiStateMachine(  970): handleMessage: X
D/PMS     (  970): releaseWL(20cb842c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4487): Checking schedule, now: 1455034011236 next: 1455034011195
I/CheckinService( 4487): active receiver: enabled
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4487, uid=10024, userID:0
I/CheckinService( 4487): Preparing to send checkin request
I/EventLogService( 4487): Accumulating logs since 1455033975320
W/chromium( 6674): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6674): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6674): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6674): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6674): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6674): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6674): Local Branch: 
I/Adreno-EGL( 6674): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6674): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6674):                  d74aa161a12b9c6fc6332151
I/CheckinRequestBuilder( 4487): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  970): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4487): Failed to find provider info for com.google.android.wearable.settings
W/System.err(  970): java.lang.Throwable: stack dump
W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@132861a9:true
D/BluetoothAdapter( 6674): 881615278: getState(). Returning 12
W/art     ( 6674): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6674): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6674): CordovaWebView is running on device made by: HTC
W/art     ( 6674): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6674): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6674): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/art     (  970): Explicit concurrent mark sweep GC freed 26516(1728KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 16MB/25MB, paused 1.873ms total 171.481ms
D/FindExtension( 6674): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/Finsky  ( 6033): [607] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6033): [1] 5.onFinished: Installation state replication succeeded.
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=163 Rx=214
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  970): notifying of data activity 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/GLSUser ( 1970): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1970): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1970): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1970): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1970): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/InputMethodManager( 6674): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1c6d263f, mServedView=org.apache.cordova.engine.SystemWebView{2fdaab0c VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1780ac55
I/InputMethodManagerService(  970): Disable input method client, pid=1630
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Enable input method client, pid=6674
I/ActivityManager(  970): Displayed com.test.thalitest/.MainActivity: +840ms
D/PMS     (  970): releaseWL(26f923fc): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/CheckinRequestBuilder( 4487): awaiting user notification for token
I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
W/ResourcesManager( 1312): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1312): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1312): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1312): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
I/ActivityManager(  970): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6727 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/XT9_C   ( 1400): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1400): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6674): Cannot call determinedVisibility() - never saw a connection for the pid: 6674
W/ResourcesManager( 6727): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6727): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6727): VM with version 2.1.0 has multidex support
I/MultiDex( 6727): install
I/MultiDex( 6727): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6727): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=144 rxSum=116} preTxRxSum={txSum=144 rxSum=116}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
W/ActivityThread( 6727): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6727): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16e09f6c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6727): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1970): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/JsMessageQueue( 6674): Set native->JS mode to OnlineEventsBridgeMode
D/AuthorizationBluetoothService( 1970): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4487): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 5186): callingUid 10024, callindPid: 5186
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4487, uid=10024, userID:0
E/MDM     ( 1782): [123] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/WVCdm   (  422): CdmEngine::OpenSession
I/WVCdm   (  422): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  422): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  422): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  422): Service_Initialize: starts!
,D/QSEECOMAPI: (  422): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  422): App is not loaded in QSEE
E/QSEECOMAPI: (  422): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  422): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  422): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  422): App is not loaded in QSEE
,D/jxcore_app_log( 6674): JniHelper::setJavaVM(0xab1b48f8), pthread_self() = -1404338824
,D/LocationInitializer( 4487): Restart initialization of location,
,D/QSEECOMAPI: (  422): Loaded image: APP id = 8
,D/DrmWidevineDash(  422): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  422): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  422): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  422): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4cae000
E/DrmWidevineDash(  422): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4cae000
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  510): got the req here! ret=0
D/DrmLibTime(  510): command id, time_cmd_id = 770
D/DrmLibTime(  510): time_getutcsec starts!
D/DrmLibTime(  510): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  510): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  510): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  510): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  510): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  510): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  510): QSEE Time Listener: Retrieved Android system time: 1455034012
D/DrmLibTime(  510): time_getutcsec returns 0, sec = 1455034012; nsec = 0
D/DrmLibTime(  510): time_getutcsec finished! 
D/DrmLibTime(  510): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  510): before calling ioctl to read the next time_cmd
E/QC-time-services(  476): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  422): hlos api version =  9
D/DrmWidevineDash(  422): tz api version =  9
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  422): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_IsKeyboxValid: ends! returns 0,
,D/WVCdm   (  422): OEMCrypto_Initialize Level 1 success. I will use level 1.,
D/DrmWidevineDash(  422): OEMCrypto_OpenSession: starts! SID=0xf4fd8928
D/DrmWidevineDash(  422): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  422): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  422): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_GetRandom: starts! randomData=0xab91c6a0, dataLength=8
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab9b8368, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  422): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  422): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  422): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  422): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  422): OEMCrypto_GetDeviceID: starts! deviceID=0xab91bf40, idLength=0xf4dd86f8
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/chromium( 6674): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4dd870e, maximum = 0xf4dd870f
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): hlos api version =  9
D/DrmWidevineDash(  422): tz api version =  9,
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  422): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4dd877c
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  422): PrepareKeyRequest: nonce=722669510
D/DrmWidevineDash(  422): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab888238
D/DrmWidevineDash(  422): message_length=1611, signature=0xab887f68, signature_length=0xf4dd86dc
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  422): CdmEngine::CloseSession
D/DrmWidevineDash(  422): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  422): L3 Terminate.
D/DrmWidevineDash(  422): OEMCrypto_Terminate: starts!,
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): Service_Uninitialize: starts!
D/QSEECOMAPI: (  422): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  422): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  422): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  422): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6761): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6761): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6761): dex2oat: override thread count:4
,I/dex2oat ( 6761): dex2oat took 60.460ms (threads: 4),
,I/Adreno-EGL( 6727): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6727): OpenGL ES Shader Compiler Version: E031.25.03.01,
I/Adreno-EGL( 6727): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6727): Local Branch: 
I/Adreno-EGL( 6727): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6727): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6727):                  d74aa161a12b9c6fc6332151
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=163 Rx=214
,I/Adreno-EGL( 6727): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6727): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6727): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6727): Local Branch: 
I/Adreno-EGL( 6727): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6727): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6727):                  d74aa161a12b9c6fc6332151
,I/WVCdm   (  422): CdmEngine::OpenSession,
I/WVCdm   (  422): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  422): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,D/DrmWidevineDash(  422): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  422): Service_Initialize: starts!
D/QSEECOMAPI: (  422): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  422): App is not loaded in QSEE
E/QSEECOMAPI: (  422): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  422): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  422): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  422): App is not loaded in QSEE
,D/QSEECOMAPI: (  422): Loaded image: APP id = 9,
D/DrmWidevineDash(  422): Service_Initialize: ends! returns 0
D/QSAPPSVER(  422): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  422): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  422): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4cae000
E/DrmWidevineDash(  422): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4cae000
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  510): got the req here! ret=0
D/DrmLibTime(  510): command id, time_cmd_id = 770
D/DrmLibTime(  510): time_getutcsec starts!
D/DrmLibTime(  510): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  510): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  510): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  510): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  510): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  510): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  510): QSEE Time Listener: Retrieved Android system time: 1455034012
D/DrmLibTime(  510): time_getutcsec returns 0, sec = 1455034012; nsec = 0
D/DrmLibTime(  510): time_getutcsec finished! 
D/DrmLibTime(  510): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  510): before calling ioctl to read the next time_cmd
E/QC-time-services(  476): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  422): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): hlos api version =  9
D/DrmWidevineDash(  422): tz api version =  9
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  422): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  422): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  422): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  422): OEMCrypto_OpenSession: starts! SID=0xf4fd8928
D/DrmWidevineDash(  422): OEMCrypto_OpenSession Session ID = 0,
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  422): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_GetRandom: starts! randomData=0xab8bd3d8, dataLength=8
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  422): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab9b8368, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  422): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  422): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  422): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  422): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  422): OEMCrypto_GetDeviceID: starts! deviceID=0xab91bf60, idLength=0xf4ed86f8
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  422): OEMCrypto_GetDeviceID: ends! returns 0
,D/PMS     (  970): releaseHCC(1b342ad0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
,D/PMS     (  970): releaseHCC(2721cac9): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  422): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4ed870e, maximum = 0xf4ed870f
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): hlos api version =  9
D/DrmWidevineDash(  422): tz api version =  9
D/DrmWidevineDash(  422): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  422): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4ed877c
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  422): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  422): PrepareKeyRequest: nonce=1972766741
D/DrmWidevineDash(  422): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab888238
D/DrmWidevineDash(  422): message_length=1646, signature=0xab8888b0, signature_length=0xf4ed86dc
D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  422): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  422): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  422): CdmEngine::CloseSession
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
,I/CheckinRequestBuilder( 4487): Classify the device as Phone.
,D/libc    ( 4487): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4487): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 4487): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4487): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4487): [NET] android_getaddrinfo_proxy+
D/libc    ( 4487): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604,
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4487): [NET] android_getaddrinfo_proxy-, success
,W/jxcore-log( 6674): Initializing JXcore engine,
W/jxcore-log( 6674): JXcore engine is ready
,W/jxcore-log( 6674): Starting JXcore engine,
,D/wpa_supplicant( 1363): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
,D/wpa_supplicant( 1363): wlan0: nl80211: New scan results available
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1363): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1363): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1363): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1363): wlan0: Scan completed in 2.072462 seconds
D/wpa_supplicant( 1363): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1363): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1363): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1363): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-55
I/wpa_supplicant( 1363): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-66
I/wpa_supplicant( 1363): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
D/wpa_supplicant( 1363): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1363): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to no match in scan
D/wpa_supplicant( 1363): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1363): wlan0: Scan-only results received
D/wpa_supplicant( 1363): wlan0: Radio work 'scan'@0x5577d78860 done in 2.073772 seconds
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1363): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  970): [1,455,034,013,296 ms] noteScanEnd no scan source
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1363): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@23cc205c sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  970): NG7005g c0:ff:d4:d3:aa:4a rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): NG700 c0:ff:d4:d3:aa:48 rssi=-66 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK nu,m: 1 rssi=-66 freq=2412
E/WifiAutoJoinController (  970): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 4 now 1455034013299
E/WifiAutoJoinController (  970): newSupplicantResults size=4 known=1 true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1363): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  970): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  970): ssid=NG700
E/WifiAutoJoinController (  970): id=0
E/WifiAutoJoinController (  970): mode=station
E/WifiAutoJoinController (  970): pairwise_cipher=CCMP
E/WifiAutoJoinController (  970): group_cipher=CCMP
E/WifiAutoJoinController (  970): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  970): wpa_state=COMPLETED
E/WifiAutoJoinController (  970): ip_address=192.168.1.130
E/WifiAutoJoinController (  970): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  970): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  970): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  970): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  970): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-66,-127) num=(1,0)
E/WifiAutoJoinController (  970): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  970): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-66 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  970): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  970): Done attemptAutoJoin status=0
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  970): handleMessage: X
D/WifiManager( 1782): getScanResults: Base Package Name=com.google.android.gms, uid=10024
D/libc    ( 4487): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4487): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:2109] from screen [on:0 period:-959900015] gl hn u24 rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959900014] gl hn u24 rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1363): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.71 txretriesrate=0.00 rxrate=1.24 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -65, 3
,W/jxcore-log( 6674): Platform android
W/jxcore-log( 6674): 
W/jxcore-log( 6674): Process ARCH arm
W/jxcore-log( 6674): 
,D/libc    ( 4487): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4487): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4487): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4487): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4487): Sending checkin request (8440 bytes),
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=178 Rx=224,
E/WifiTrafficPoller(  970): notifying of data activity 3
D/WIFI_ICON( 1222): WifiActivity: 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T],
,I/jxcore-log( 6674): JXcore Cordova bridge is ready!,
I/jxcore-log( 6674): 
W/jxcore-log( 6674): JXcore engine is started
,I/jxcore-log( 6674): Toggling radios to true,
I/jxcore-log( 6674): 
,D/BluetoothAdapter( 6674): enable(): BT is already enabled..!,
,D/WifiService(  970): New client listening to asynchronous messages,
E/WifiTrafficPoller(  970): ADD_CLIENT: 7
,D/WifiManager( 6674): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
W/Settings:Agent(  970): MONITOR_LOG
D/WifiService(  970): setWifiEnabled: true pid=6674, uid=10366
W/Settings:Agent(  970): name: wifi_on
E/WifiService(  970): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  970): value: 2
I/WifiService(  970): isSprintWifiRestricted(): false
W/Settings:Agent(  970): >> traceCallingStack()
I/WifiService(  970): isMdmWifiRestricted(): false
W/Settings:Agent(  970): Process.myPid(): 970
W/Settings:Agent(  970): Process.myTid(): 1620
W/Settings:Agent(  970): Process.myUid(): 1000
W/Settings:Agent(  970): 
W/Settings:Agent(  970): 
,W/System.err(  970): java.lang.Throwable: stack dump
,W/System.err(  970): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  970): 	,at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  970): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  970): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  970): 	,at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
,W/System.err(  970): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  970): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  970): 	,at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  970): 
W/Settings:Agent(  970): << traceCallingStack(): 23(ms)
D/WifiController(  970): handleMessage: E msg.what=155656
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
,D/WifiController(  970): handleMessage: X
D/WifiManager( 6674): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiManager( 6674): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  970): handleMessage: E msg.what=131145
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_DISCONNECT 0 0
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1363): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1363): wlan0: Cancelling scan request
D/wpa_supplicant( 1363): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
,D/wpa_supplicant( 1363): TDLS: Tear down peers
D/wpa_supplicant( 1363): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6674): Radios toggled
I/jxcore-log( 6674): 
I/jxcore-log( 6674): My device name is: HTC-HTC One M8s
I/jxcore-log( 6674): 
,I/CheckinRequestBuilder( 4487): Checkin reason type: 11 attempt count: 1,
I/ActivityManager(  970): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4487): Failed to find provider info for com.google.android.wearable.settings
,D/wpa_supplicant( 1363): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1363): wlan0: Deauthentication notification
D/wpa_supplicant( 1363): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1363): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1363): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1363): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1363): enter disconnect check
I/wpa_supplicant( 1363): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1363): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1363): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  970): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  970): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  970): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  970): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  970): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): sendTetherStateChangedBroadcast 0, 0, 0
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1363): TDLS: Remove peers on disassociation
D/PMS     (  970): acquireWL(173f9643): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/wpa_supplicant( 1363): wlan0: Disconnect event - remove keys
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/wpa_supplicant( 1363): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1363): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1363): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5577d95f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1363):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1363): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1363): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1363): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1363): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1363): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1363): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1363): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1363): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1363): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1363): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1363): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1363): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1363): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1363): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1363): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1363): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1363): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/wpa_supplicant( 1363): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1363): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  970): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: ConnectedState
E/WifiStateMachine(  970): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  970): release()
E/WifiStateMachine(  970): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  970): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  970): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  970): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  970): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  970): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1363): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1363): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1363): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1363): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1363): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1363): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1363): Power_Mode_Type mode = 0
I/wpa_supplicant( 1363): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  970): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1363): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  970): setDhcpActive: false
V/NativeCrypto( 1970): Read error: ssl=0x559deb5e90: I/O error during system call, Connection timed out
D/PMS     (  970): acquireWL(ad94c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  970): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  970): NetworkAgent != null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1363): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1363): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/PMS     (  970): releaseWL(173f9643): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1363): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1363): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
V/NativeCrypto( 1970): SSL shutdown failed: ssl=0x559deb5e90: I/O error during system call, Broken pipe
D/wpa_supplicant( 1363): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1363): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectingState
E/WifiTrafficPoller(  970):  packet count Tx=179 Rx=227
E/WifiStateMachine(  970):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  970): Start Disconnecting Watchdog 1
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131146
E/WifiStateMachine(  970): processMsg: DisconnectingState
E/WifiStateMachine(  970):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  970):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1363): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1363): wlan0: Selecting BSS from priority group 663
D/wpa_supplicant( 1363): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-55 wps
D/wpa_supplicant( 1363): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1363): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1363): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-66 wps
D/wpa_supplicant( 1363): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1363): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1363): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1363):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1363): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1363): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssi,d: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x5577d97c00  current_ssid=0x0
D/wpa_supplicant( 1363): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1363): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1363): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1363): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1363): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1363): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1363): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1363): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1363): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1363): wlan0: Add radio work 'connect'@0x5577d78860
D/wpa_supplicant( 1363): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1363): wlan0: Starting radio work 'connect'@0x5577d78860 after 0.000233 second wait
I/wpa_supplicant( 1363): check if in concurrent case
I/wpa_supplicant( 1363): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: X
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): handleMessage: E msg.what=147460
E/WifiStateMachine(  970): processMsg: DisconnectingState
D/WifiMonitor(  970): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=35 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  970):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=100859
E/WifiStateMachine(  970): processMsg: ConnectModeState
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=100860
E/WifiStateMachine(  970): ConnectModeState: Network connection lost 
D/WifiDataStallTracker(  970): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  970): stopDataStallAlarm 
E/WifiStateMachine(  970): transitionTo: destState=DisconnectedState
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectedState
,E/WifiStateMachine(  970): DisconnectedState call setCountryCode()
D/ConnectivityService(  970): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
,D/wpa_supplicant( 1363): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
,V/NetworkPolicy(  970): updateNetworkEnabledLocked()
D/wpa_supplicant( 1363): wlan0: Cancelling scan request
V/NetworkPolicy(  970): updateNotificationsLocked()
D/wpa_supplicant( 1363): wpas_start_assoc_cb, 1892
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1363): wpas_start_assoc_cb, 1895
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1363): wpas_start_assoc_cb, 1910
D/PMS     (  970): releaseWL(ad94c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1363): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1363): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1363): RSN: PMKSA cache search - network_ctx=0x5577d97c00 try_opportunistic=0
D/wpa_supplicant( 1363): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1363): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1363): wlan0: RSN: using IEEE 802.11i/D9.0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1363): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1363): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1363): wlan0: WPA: clearing AP WPA IE
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/wpa_supplicant( 1363): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Forcing reevaluation
,D/wpa_supplicant( 1363): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1363): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1363): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1363): wlan0: WPA: not using MGMT group cipher
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1363): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1363): wlan0: State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1363): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1363): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1363): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1363): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/wpa_supplicant( 1363): nl80211: Unsubscribe mgmt frames handle 0x888888ddff51f989 (mode change)
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1363): nl80211: Subscribe to mgmt frames with non-AP handle 0x5577d97100
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=0104
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=040a
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=040b
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=040c
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=040d
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=090a
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=090b
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=090c
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=090d
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=0409506f9a09
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=7f506f9a09
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=0801
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=040e
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=06
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=0a07
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=0a11
D/wpa_supplicant( 1363): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5577d97100 match=0a1a
,D/wpa_supplicant( 1363): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1363):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363):   * freq=2412
D/wpa_supplicant( 1363):   * freq_hint=2412
D/wpa_supplicant( 1363):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1363):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1363):   * WPA Versions 0x2
D/wpa_supplicant( 1363):   * pairwise=0xfac04
D/wpa_supplicant( 1363):   * group=0xfac04
D/wpa_supplicant( 1363):   * akm=0xfac02
D/wpa_supplicant( 1363):   * Auth Type 0
D/wpa_supplicant( 1363): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5577d97c3a
D/wpa_supplicant( 1363): nl80211: Connect request send successfully
D/wpa_supplicant( 1363): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1363): EAPOL: External notification - EAP success=0
E/WifiStateMachine(  970):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
D/wpa_supplicant( 1363): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1363): EAPOL: External notification - portControl=Auto
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1363): Ongoing scan action - reject new request
E/WifiStateMachine(  970): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=100874  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=100875  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
,E/WifiStateMachine(  970): processMsg: DisconnectedState
D/TetherSettings( 6377): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6377): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6377): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6377): Cust_ConnectToPC   : spcsc>false
D/        ( 6377): Cust_ConnectToPC   : IPT>true
D/        ( 6377): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  970):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
D/WifiNetworkAgent(  970): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  970): handleMessage: E msg.what=131213
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=100879
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=100880
E/WifiStateMachine(  970): processMsg: DriverStartedState
W/Settings( 6377): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  970):  DriverStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=100881
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=100881
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=100882  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
,E/WifiStateMachine(  970): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): NetworkAgent == null
E/SmartNS_Utility( 6377): hasRemovableStorageSlot: true
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/SmartNS_Utility( 6377): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6377): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=100887  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  970): handleMessage: X
,W/ContextImpl( 6377): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/SmartNS_Utility( 6377): setISNotification
,D/SmartNS_Utility( 6377): usb_cable_connect = 1
,D/SmartNS_Utility( 6377): usb_denied = 0
,I/SmartNS_PSService( 6377): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 6377): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 6377): usb_cable_connect = 1
,D/SmartNS_Utility( 6377): usb_denied = 0
,I/SmartNS_PSService( 6377): usb notificaiton:true
,I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): reapply : com.android.settings 1 36,
,I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:4,
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
,D/SmartNS_NSReceiver( 6377): Tethered state change:false isNSOpening:false,
,D/ConnectivityService(  970): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Disconnected - quitting
D/ConnectivityService(  970): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  970): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  970): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/WIFI    (  970): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  970): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524292
D/ConnectivityService(  970): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  970): Removing idletimer
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  970): enter WifiNetworkFactory startNetwork. mIPTStart:false
I/SecurityController( 1222): onLost 100
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/WISPrService( 6377): >>>>>WISPrService start isConnected = true<<<<<
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
,I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 8
,D/PMS     (  970): acquireWL(2809993e): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 970 1000 null
D/CSLegacyTypeTracker(  970): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false,
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  970): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,E/ConnectivityService(  970): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine(  970): handleMessage: E msg.what=131131
E/ConnectivityService(  970): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,E/WifiStateMachine(  970): processMsg: DisconnectedState
V/NetworkPolicy(  970): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  970):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/PMS     (  970): acquireWL(3cbb539f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/WifiStateMachine(  970):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/NetworkPolicy(  970): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
E/WifiStateMachine(  970): handleMessage: X
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
D/Tethering(  970): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkPolicy(  970): updateIfacesLocked()
D/Tethering(  970): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  970): updateNotificationsLocked()
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WISPrService( 6377): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6377): trigger connection
D/WISPrService( 6377): continue
D/wpa_supplicant( 1363): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1363): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1363): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/WISPrService( 6377): start DataConnection
D/wpa_supplicant( 1363): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1363): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1363): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6784 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/wpa_supplicant( 1363): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1363): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/libc    ( 6377): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/wpa_supplicant( 1363): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/libc    ( 6377): [NET] android_getaddrinfofornet-, err=8
D/wpa_supplicant( 1363): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1363): nl80211: Connect event
D/wpa_supplicant( 1363): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1363): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1363): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1363): wlan0: Association info event
,D/wpa_supplicant( 1363): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1363): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1363): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1363): wlan0: freq=2412 MHz
D/wpa_supplicant( 1363): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1363): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1363): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1363): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1363): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1363): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1363): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1363): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1363): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1363): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1363): TDLS: Remove peers on association
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1363): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1363): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1363): EAPOL: External notification - EAP success=0
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1363): EAPOL: External notification - portEnabled=1
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1363): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1363): EAPOL: enable timer tick
D/Tethering(  970): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1363): EAPOL: SUPP_BE entering state IDLE
,D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1363): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1363): wlan0: Cancelling scan request
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
I/wpa_supplicant( 1363): htc_wext_set_keepalive +
I/wpa_supplicant( 1363): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1363): getPrivFuncNum +	
I/wpa_supplicant( 1363): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1363): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1363): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1363): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1363): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
,D/wpa_supplicant( 1363): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1363): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1363): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1363):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1363):   key_nonce - hexdump(len=32): fd 79 24 52 73 f1 9c d8 6d 5c 05 fa b4 ae 69 37 e5 de 96 e8 d5 13 6a e2 5a f2 21 99 eb c5 1e 3a
D/wpa_supplicant( 1363):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1363):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1363):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00,
D/wpa_supplicant( 1363):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/WifiMonitor(  970): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
D/wpa_supplicant( 1363): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  970): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  970): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1363): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1363): RSN: msg 1/4 key data - hexdump(len=0):
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  970): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  970): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  970): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  970): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  970): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  970): interfaceStatusChanged wlan0, false
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/Tethering(  970): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  970): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1363): WPA: Renewed SNonce - hexdump(len=32): 6d 11 68 37 47 7f 1d ad c0 c8 59 d8 1c 0a 78 2e 2b 2a 63 1a 04 a2 1d 46 ed 71 12 11 7f 58 64 b4
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
D/wpa_supplicant( 1363): WPA: Nonce1 - hexdump(len=32): 6d 11 68 37 47 7f 1d ad c0 c8 59 d8 1c 0a 78 2e 2b 2a 63 1a 04 a2 1d 46 ed 71 12 11 7f 58 64 b4
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/wpa_supplicant( 1363): WPA: Nonce2 - hexdump(len=32): fd 79 24 52 73 f1 9c d8 6d 5c 05 fa b4 ae 69 37 e5 de 96 e8 d5 13 6a e2 5a f2 21 99 eb c5 1e 3a
D/wpa_supplicant( 1363): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1363): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1363): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1363): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1363): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1363): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1363): WPA: Derived Key MIC - hexdump(len=16): be 1d 16 bb 0b 5d 1c 66 82 be 80 dd 64 6f d4 24
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=100984  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASS,OCIATED
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info0x
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1363): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1363): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1363): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1363): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1363):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1363):   key_nonce - hexdump(len=32): fd 79 24 52 73 f1 9c d8 6d 5c 05 fa b4 ae 69 37 e5 de 96 e8 d5 13 6a e2 5a f2 21 99 eb c5 1e 3a
D/wpa_supplicant( 1363):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1363):   key_rsc - hexdump(len=8): d0 38 00 00 00 00 00 00
D/wpa_supplicant( 1363):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1363):   key_mic - hexdump(len=16): 72 b5 a4 f3 57 4b 1e 82 7f 73 a6 fa 21 0f ea f3
D/wpa_supplicant( 1363): RSN: encrypted key data - hexdump(len=56): 59 45 79 c0 54 dd 6b b7 b5 13 46 ef 8e e6 5b 1b 28 53 be cb 62 c5 e9 11 03 78 fb 38 3f 2a 41 1b ...
D/wpa_supplicant( 1363): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1363): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1363): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1363): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 40 1e ...
D/wpa_supplicant( 1363): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1363): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1363): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1363): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1363): WPA: Derived Key MIC - hexdump(len=16): 65 30 9c 54 20 36 05 88 0e f2 23 b7 70 c2 43 06
D/wpa_supplicant( 1363): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1363): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5577d98390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1363): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1363): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1363):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1363): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1363): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1363): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1363): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16),
D/wpa_supplicant( 1363): WPA: RSC - hexdump(len=6): d0 38 00 00 00 00
D/wpa_supplicant( 1363): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x555af7ce68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1363): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1363): nl80211: KEY_SEQ - hexdump(len=6): d0 38 00 00 00 00
D/wpa_supplicant( 1363):    broadcast key
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1363): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1363): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1363): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1363): wlan0: Radio work 'connect'@0x5577d78860 done in 0.136770 seconds
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
I/wpa_supplicant( 1363): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1363): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/Tethering(  970): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/libc    ( 6377): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6377): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6377): [NET] android_getaddrinfo_proxy+
E/wpa_supplicant( 1363): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1363): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1363): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/libc    ( 6377): [NET] android_getaddrinfo_proxy get netid:0
I/wpa_supplicant( 1363): set send_ind_to_ndc = 0
I/wpa_supplicant( 1363): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1363): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1363): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1363): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1363): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1363): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1363): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1363): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1363): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1363): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1363): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1363): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1363): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1363): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/Tethering(  970): interfaceStatusChanged wlan0, true
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
I/art     ( 1970): Explicit concurrent mark sweep, GC freed 7625(389KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.720ms total 50.670ms
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  970): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  970): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=42 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  970): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor(  970): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=44 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  970): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=100999  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  970): handleMessage: X
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  970): handleMessage: E msg.what=147500
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  970): Enter handleAssociatedWithEvent
D/WifiStateMachine(  970): Associated
,I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false),
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6377): [NET] android_getaddrinfo_proxy-, NODATA
D/WifiStateMachine(  970): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  970): Exit handleAssociatedWithEvent
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=101006  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/PMS     (  970): releaseWL(3cbb539f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  970): acquireWL(3f5d9216): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
,D/PMS     (  970): releaseWL(3f5d9216): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,E/WifiStateMachine(  970): NetworkAgent == null
,E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=101019  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: FOUR_WAY_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  970):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 18
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=101022  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=101023  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147459
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=101024
,E/WifiStateMachine(  970): processMsg: ConnectModeState
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
E/WifiStateMachine(  970):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=101025
V/NetworkPolicy(  970): updateNotificationsLocked()
E/WifiStateMachine(  970): Network connection established
D/WifiStateMachine(  970): fetchFrequency(), freq = 2412
,E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,E/WifiStateMachine(  970): transitionTo: destState=ObtainingIpState
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  970): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  970): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  970): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  970): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
,E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 21
D/ConnectivityService(  970): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  970): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
E/WifiStateMachine(  970): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  970): Got NetworkAgent Messenger
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  970): NetworkAgent connected
D/wpa_supplicant( 1363): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1363): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1363): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1363): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1363): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1363): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  970): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  970): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  970): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  970): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1363): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1363): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1363): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/wpa_supplicant( 1363): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1363): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
,D/wpa_supplicant( 1363): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1363): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): Start Dhcp Watchdog 2
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: ObtainingIpState
D/libc    ( 6377): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6377): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  970):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=101054  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  970):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=101055  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=101055  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  970): handleMessage: X
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ObtainingIpState
D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 6377): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
E/WifiStateMachine(  970):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:906] from screen [on:0 period:-959899103] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959899102] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SIGNAL_POLL'
D/WISPrService( 6377): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6377): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/wpa_supplicant( 1363): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=65 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=89.50 txretriesrate=0.00 rxrate=113.50 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
E/WifiStateMachine(  970): calculateWifiScore() report new score 60
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -65, 3
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  970): handleMessage: X
D/ConnectivityService(  970): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): handleMessage: E msg.what=196612
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=179,0,0
D/WifiStateMachine(  970): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  970): processMsg: L2ConnectedState
D/PMS     (  970): acquireWL(3d628925): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 970 1000 null
E/WifiStateMachine(  970):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=179,0,0
D/WifiStateMachine(  970): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  970): setDhcpActive: true
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1363): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  970): do suspend false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1363): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/wpa_supplicant( 1363): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1363): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1363): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1363): wlan0: Event DRIVER_GTK_REKEY (37) received
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1363): INFO - Deny active power mode because already has gateway
D/FlexNetS( 6597): updateSvcAllowedInSettings:false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/,WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1363): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  970): Unexpected BatchedScanResults :null
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1363): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
D/TetherSettings( 6377): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6377): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6377): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6377): Cust_ConnectToPC   : spcsc>false
D/        ( 6377): Cust_ConnectToPC   : IPT>true
D/        ( 6377): Cust_ConnectToPC   : Singel_USB>false
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f662dd3 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 6377): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiP2pService(  970): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f662dd3 target=com.android.internal.util.StateMachine$SmHandler }
E/SmartNS_Utility( 6377): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6377): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
D/SmartNS_NSReceiver( 6377): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  970): noteBatchedScanstop()
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
,W/ContextImpl( 6377): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  970): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6810 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,I/SmartNS_Utility( 6377): setISNotification
D/SmartNS_Utility( 6377): usb_cable_connect = 1
D/SmartNS_Utility( 6377): usb_denied = 0
I/SmartNS_PSService( 6377): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/SmartNS_Utility( 6377): usb_cable_connect = 1,
D/SmartNS_Utility( 6377): usb_denied = 0
I/SmartNS_PSService( 6377): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false,
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 6377): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,I/GLSUser ( 1970): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/RemoteViews( 1222): reapply : com.android.settings 2 36
I/GLSUser ( 1970): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1970): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1970): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,V/GLSActivity( 1970): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,W/CheckinRequestBuilder( 4487): awaiting user notification for token
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 1 40
D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,I/CheckinRequestBuilder( 4487): Classify the device as Phone.
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6810): [dd6.2.]  listen tmrbb8
D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,I/CheckinTask( 4487): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,I/CheckinService( 4487): Checking schedule, now: 1455034014470 next: 1455570846456
I/CheckinService( 4487): active receiver: disabled
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4487, uid=10024, userID:0
E/dhcpcd  ( 6837): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6837): version 5.5.6 starting
E/dhcpcd  ( 6837): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6837): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6837): autoip env[11]:autoip=DISABLE
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,D/PMS     (  970): releaseWL(30afc48a): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false,
,I/dhcpcd  ( 6837): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6837): wlan0: sending REQUEST (xid 0x9b9037a8), next in 0.54 seconds
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6784): remove item 101 (p2d27in234) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6810): [dd6.2.] summary 118:p2 ignore,
,D/FlexNetS( 6597): updateSvcAllowedInSettings:false
,I/ActivityManager(  970): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6848 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,I/art     (  428): Explicit concurrent mark sweep GC freed 8653(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 157us total 19.616ms,
,I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 152us total 17.193ms
,D/PhoneMonitor( 6848): Register our PhoneStateListener
,I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 150us total 16.926ms
,V/SetupWizard( 6848): Connected to Gservices successfully
,D/Process (  970): killProcessQuiet, pid=6333
I/ActivityManager(  970): Killing 6333:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 6848): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 6848): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 22 num clients 8,
,I/ActivityManager(  970): Recipient 6333
,D/ChimeraCfgMgr( 4487): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/Kids    ( 4487): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PMS     (  970): acquireWL(e0f6aa): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1970 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1970): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1970): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1970): [NET] android_getaddrinfo_proxy+
D/libc    ( 1970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1970): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  970): acquireWL(e0f6aa): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1970): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  970): releaseWL(e0f6aa): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/HtcModeClient( 3271): handler message = 4011
E/HtcModeClient( 3271): Check connection and retry 12 times.
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 22 num clients 8,
,D/wpa_supplicant( 1363): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1363): EAPOL: disable timer tick
,I/dhcpcd  ( 6837): wlan0: sending REQUEST (xid 0x9b9037a8), next in 1.77 seconds
,I/dhcpcd  ( 6837): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6837): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6837): autoip env[11]:autoip=DISABLE
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  970): handleMessage: X
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/dhcpcd  ( 6837): bind_interface: daemonise
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  970): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  970): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  970): releaseWL(3d628925): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  970): handleMessage: E msg.what=196613
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1363): Power_Mode_Type mode = 0
I/wpa_supplicant( 1363): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1363): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  970): setDhcpActive: false
E/WifiStateMachine(  970): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  970): WifiStateMachine DHCP successful
E/WifiStateMachine(  970): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  970): link address 192.168.1.130/24
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): gateway: /192.168.1.1
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1363): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1363): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131210
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1363): environment dirty rate=40 [5][2][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
,E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -64, 3
D/wpa_supplicant( 1363): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1363): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=46 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  970): NetworkAgent != null
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -64, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  970): Adding iface wlan0 to network 101
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -64, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): transitionTo: destState=ConnectedState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  970): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  970): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  970): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,E/WifiStateMachine(  970): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  970): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 22
D/HtcWifiWanDetect(  970): WAN detection
E/WifiTrafficPoller(  970):  packet count Tx=182 Rx=230
D/HtcWifiWanDetect(  970): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 2
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 23
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  970):  packet count Tx=182 Rx=230
E/WifiTrafficPoller(  970): notifying of data activity 0
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  970): ConnectedState Enter  mScreenOn=true scanperiod=20000
E/ConnectivityService(  970): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  970): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): handleMessage: X
D/ConnectivityService(  970): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/WISPrService( 6377): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  970): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=131131
E/WifiStateMachine(  970): processMsg: ConnectedState
D/ConnectivityService(  970): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
E/WifiStateMachine(  970):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/Nat464Xlat(  970): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  970): handleMessage: X
D/ConnectivityService(  970): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Connected
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): currentScore = 0, newScore = 20
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):    accepting network in place of null
D/WIFI    (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  970): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  970): sendGeneralBroadcastDelayed, restrictEnable=false
,D/Tethering(  970): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  970): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  970): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  970): ensureActiveMobilePolicyLocked()
D/PMS     (  970): acquireWL(30178638): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/ConnectivityService(  970): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/NetworkPolicy(  970): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateIfacesLocked()
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 101]
D/WISPrService( 6377): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/WIFI    (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  970): updateNotificationsLocked()
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/DATA_ICON( 1222): dataConnected: false/false
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/DATA_ICON( 1222): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,D/DATA_ICON( 1222): dataConnected: false/false
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  970): releaseWL(30178638): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  970): updateNetworkEnabledLocked()
,V/NetworkPolicy(  970): updateNotificationsLocked()
,I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  970): processMsg: DriverStartedState
,E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  970): processMsg: DefaultState
,E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  970): identical MTU - not setting
E/WifiStateMachine(  970): handleMessage: X
D/Nat464Xlat(  970): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  970): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  970): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  970): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524295
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524295
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=89.5, 0.0, 0.0  rx=113.5 bcn=0 [on:0 tx:0 rx:0 period:2087] from screen [on:0 period:-959897008] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=89.5, 0.0, 0.0  rx=113.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959897007] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): handleMessage: X
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1222): WifiActivity: 3
,E/WifiTrafficPoller(  970):  packet count Tx=184 Rx=231
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 3
,D/PMS     (  970): releaseWL(2809993e): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  970): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 3,
,D/Process (  970): killProcessQuiet, pid=6355,
I/ActivityManager(  970): Killing 6355:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6355
,D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/AlarmManager(  970): [AlarmQueuing] connectivity wifi: false
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  970): acquireWL(2c396611): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/GpsLocationProvider(  970): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  970): acquireWL(13afd376): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
D/GpsLocationProvider(  970): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  970): releaseWL(13afd376): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ConnectivityHelper( 1630): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  970): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6904 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  970): Killing 6409:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=6409
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=89.5, 0.0, 0.0  rx=113.5 bcn=0 [on:0 tx:0 rx:0 period:911] from screen [on:0 period:-959896095] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=89.5, 0.0, 0.0  rx=113.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959896094] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SIGNAL_POLL',
,I/wpa_supplicant( 1363): environment dirty rate=0 [4][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiStateMachine(  970): BroadcastRSSIForIMS, newrssi =-65 , oldRssi= -200
,I/ActivityManager(  970): Recipient 6409
,E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=47.75 txretriesrate=0.00 rxrate=59.75 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -65, 3
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/GpsLocationProvider(  970): No APN found to select.
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
E/WifiStateMachine(  970): handleMessage: X
,D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -65, 3
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  970): releaseWL(2c396611): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6810): [9d4.1.]  listen tmrbb8
,D/MdScDataSum( 6810): [9d4.1.] summary 118:p1 ignore
,I/ActivityManager(  970): Killing 6449:com.google.android.apps.plus/u0a167 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=6449
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=185 Rx=233
,I/MusicStore( 6904): Database version: 120,
,I/ActivityManager(  970): Recipient 6449,
,D/VoldConnector(  970): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6904): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  970): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6904): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  970): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6904): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6904): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6904): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6904): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6904): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6904): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@383361f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6904): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6904): GMSCore installation verified
,I/ConfigStore( 6904): Config Database version: 1,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6904, uid=10159, userID:0,
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,I/art     (  970): Explicit concurrent mark sweep GC freed 57273(2MB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 16MB/25MB, paused 1.808ms total 143.286ms
,D/MediaRouterService(  970): Client com.google.android.music (pid 6904): Registered
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,I/MediaRouter( 6904): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6904): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6904): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6904): type=WIFI subType= reason=null isConnected=true
,D/AutoSetting( 1545): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6848): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6904, uid=10159, userID:0
D/MobileConnectivityChangeReceiver( 6848): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1545): service - onCreate(),
,D/AutoSetting( 1545): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,I/GHttpClientFactory( 6904): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1545): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1545): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1545): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1545): service - handleMessage() setting current location null
,I/GoogleURLConnFactory( 6904): Using platform SSLCertificateSocketFactory,
D/LocationManagerService(  970): request 1902c74a passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  970): provider request: passive ProviderRequest[ON interval=0]
,D/ChimeraCfgMgr( 4487): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/Kids    ( 4487): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  970): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6947 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 6482): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6482): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6482): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6482): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6482): [NET] android_getaddrinfo_proxy+
D/libc    ( 6482): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 6482): [NET] android_getaddrinfo_proxy-, success
,I/Babel   ( 6482): connection state changed from UNKNOWN to CONNECTED,
,D/Process (  970): killProcessQuiet, pid=5949
I/ActivityManager(  970): Killing 5949:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5949
,D/VoldConnector(  970): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6947): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  970): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6947): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6947): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6947):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6947):   adb logcat -s GAv4
,D/VoldConnector(  970): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6947): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:101, mark:917605
E/WifiTrafficPoller(  970):  packet count Tx=190 Rx=237
D/VoldConnector(  970): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6947): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6947): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6947): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  970): [AlarmQueuing] connectivity wifi: true
,D/PMS     (  970): acquireWL(264c0bd1): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/PMS     (  970): acquireWL(2ea0e636): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
D/PMS     (  970): releaseWL(2ea0e636): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  970): [handleMessage] UPDATE_NETWORK_STATE
I/ConnectivityHelper( 1630): [onReceive] WIFI(1): CONNECTED
D/GpsLocationProvider(  970): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  970): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,W/GAv4    ( 6947): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/NetworkMonitor( 6904): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  970): No APN found to select.
,D/PMS     (  970): releaseWL(264c0bd1): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6810): [22.1.]  listen tmrbb8
,D/MdScDataSum( 6810): [22.1.] summary 118:p1 ignore,
,W/global  ( 6947): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6947): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6947): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6947): Time to load native libraries: 1 ms (timestamps 5588-5589),
I/LibraryLoader( 6947): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6947): Binding Chromium to main looper Looper (main, tid 1) {2a1c8417},
,I/LibraryLoader( 6947): Expected native library version number "",actual native library version number ""
,I/chromium( 6947): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6947): Initializing chromium process, singleProcess=true,
,W/art     ( 6947): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6947): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6947): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6947): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6947): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,I/Adreno-EGL( 6947): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6947): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6947): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6947): Local Branch: 
I/Adreno-EGL( 6947): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6947): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6947):                  d74aa161a12b9c6fc6332151
,I/NSApplication( 6947): Starting up...,
W/AudioManagerAndroid( 6947): Requires BLUETOOTH permission
,I/ActivityManager(  970): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7011 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  970): killProcessQuiet, pid=6549
I/ActivityManager(  970): Killing 6549:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131168,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): handleMessage: X
,I/ActivityManager(  970): Recipient 6549,
,I/ActivityManager(  970): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7034 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Process (  970): killProcessQuiet, pid=5855
I/ActivityManager(  970): Killing 5855:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6674): 
,I/ActivityManager(  970): Recipient 5855
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=191 Rx=238
,D/PMS     (  970): acquireWL(18050f17): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024}
,V/AlarmManager(  970): sending alarm PendingIntent{78a9f04: PendingIntentRecord{33911ced com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=106216, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{3424f463: PendingIntentRecord{1dc46860 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455034015712, Int=20000
,W/ResourcesManager( 7034): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Process (  970): killProcessQuiet, pid=5480
,I/ActivityManager(  970): Killing 5480:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  970): Recipient 5480
,V/MusicLeanback( 6904): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/MobileConnectivityChangeReceiver( 6848): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6848): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1545): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1545): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1545): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1545): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1545): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1545): service - handleMessage() setting current location null
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4487, uid=10024, userID:0,
,D/ChimeraCfgMgr( 4487): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4487): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,V/AlarmManager(  970): sending alarm PendingIntent{1a12f0fb: PendingIntentRecord{3c9f4518 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=106818, Int=0,
,D/PMS     (  970): acquireWL(8f4ca9c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  970): WiFiStateMachine SCAN ALARM
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): handleMessage: E msg.what=131143
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2076 rssi=-65 f=2412 sc=60 link=65 tx=47.8, 0.0, 0.0  rx=59.8 fiv=40000 [on:0 tx:0 rx:0 period:2596] from screen [on:0 period:-959893329]
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:2076 rssi=-65 f=2412 sc=60 link=65 tx=47.8, 0.0, 0.0  rx=59.8 fiv=40000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959893328]
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=47.75 rxSuccessRate=59.75 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-65
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN with age=8799 interval=40000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=47.75 rx=59.75
E/WifiStateMachine(  970): handleMessage: X
D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1970): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1970): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1970): [NET] android_getaddrinfo_proxy+
D/libc    ( 1970): [NET] android_getaddrinfo_proxy get netid:0
D/PMS     (  970): releaseWL(18050f17): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,I/ClockController( 1222): schedule update now=1455034020026 next=59974
I/Clock   ( 1222): updateClock:17:07 Europe/Warsaw
,I/Clock   ( 1222): updateClock:17:07 Europe/Warsaw
I/Clock   ( 1222): updateClock:17:07 Europe/Warsaw
,I/HtcModeClient( 3271): handler message = 4011
,E/HtcModeClient( 3271): Check connection and retry 12 times. Stop service and kill this process.,
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1970): [NET] android_getaddrinfo_proxy-, success
,D/HtcModeClient( 3271): Don't start project servcice
,D/HtcModeClient( 3271): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3271): connectState: CONNECTION_READY = false
D/SilentMusic( 3271): call stop
D/HtcModeClient( 3271): close connection
,W/HtcModeClient( 3271): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3271): read the terminate packet, so break
,D/Process (  970): killProcessQuiet, pid=3271
I/ActivityManager(  970): Killing 3271:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1970): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1970): [NET] android_getaddrinfofornet-, err=8
,I/ActivityManager(  970): Recipient 3271,
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6674): 
D/PMS     (  970): acquireWL(369dfca5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1970 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1970): Connected
D/PMS     (  970): releaseWL(8f4ca9c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(369dfca5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(30dd087a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1970): Message class com.google.f.a.a.p
D/PMS     (  970): releaseWL(30dd087a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6674): 
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6674): 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=47.8, 0.0, 0.0  rx=59.8 bcn=0 [on:0 tx:0 rx:0 period:399] from screen [on:0 period:-959892928] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=47.8, 0.0, 0.0  rx=59.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959892927] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1363): environment dirty rate=5 [18][1][0]
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -66 abnormalRssiCnt = 0 newLinkSpeed = 57
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-66 linkspeed=57
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -66, 3
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=32.88 txretriesrate=0.00 rxrate=37.88 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
,E/WifiStateMachine(  970): handleMessage: X
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -66, 3
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6674): 
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
I/jxcore-log( 6674): 
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 3,
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=175 rxSum=144} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  970): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=203 Rx=249
,D/AccTypeManager( 1752): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
W/SystemReader(  970): Cannot find grip_rejection_width, use default value instead,
D/PMS     (  970): acquireWL(2916be21): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6482 10112 null
,I/Prism.ItemManager( 1630): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1630): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1630): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1752): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  970): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Launcher( 1630): Deferring update until onResume
D/Launcher( 1630): waitUntilResume // bindAppsUpdated
,I/ActivityManager(  970): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7075 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/AccTypeManager( 1752): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PhoneApp( 1571): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  970): releaseWL(2916be21): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6482): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6482): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ExternalAccountType( 1752): Unsupported attribute readOnly
,W/PackageManager(  970): Unable to load service info ResolveInfo{16a0af39 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  970): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  970): 	,at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  970): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  970): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  970): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  970): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1782): DISABLE
,I/GCoreNlp( 1782): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,I/BackupManagerService(  970): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
,E/WifiTrafficPoller(  970):  packet count Tx=203 Rx=249
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  970): notifying of data activity 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  970): acquireWL(32c257ab): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(32c257ab): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(16281123): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1782 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): releaseWL(16281123): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  970): applying state to connected service
,D/LocationProviderProxy(  970): applying state to connected service
,D/PMS     (  970): acquireWL(20609c7f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(20b844c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(20609c7f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(20b844c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationManagerService(  970): getProviders()=[passive],
,I/ActivityManager(  970): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7104 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,I/[PluginManager]RegisterService( 1545): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1545): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4487): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4487): Null package name or gms related package.  Ignoreing.
,D/PMS     (  970): acquireWL(1ce8d94d): PARTIAL_WAKE_LOCK  Icing 0x1 4487 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4487): updateResources: need to parse f{com.google.android.gms},
D/PMS     (  970): acquireWL(1fe82c02): PARTIAL_WAKE_LOCK  AsyncService 0x1 7034 10167 null
,D/PMS     (  970): acquireWL(31d35750): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 7034 10167 null
,D/PMS     (  970): releaseWL(1fe82c02): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  970): releaseWL(1ce8d94d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/UpdateIcingCorporaServi( 7075): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,D/PMS     (  970): releaseWL(31d35750): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 7075): UpdateCorporaTask done [took 111 ms] updated apps [took 111 ms] 
,I/ActivityManager(  970): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=7137 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  970): acquireWL(6b1064e): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10076}
V/AlarmManager(  970): sending alarm PendingIntent{379fa36f: PendingIntentRecord{299e987c com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455034022523, Int=60000
D/PMS     (  970): releaseWL(6b1064e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=203 Rx=249
,I/art     (  970): Explicit concurrent mark sweep GC freed 27794(1495KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 1.799ms total 147.423ms,
,D/SMSBackup( 7137): SMSBackupAgentService started,
D/SMSBackup( 7137): Checking restore status
,D/SMSBackup( 7137): Restore complete
,D/SMSBackup( 7137): cancelCheckAlarm
,D/SMSBackup( 7137): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  970): killProcessQuiet, pid=6574,
I/ActivityManager(  970): Killing 6574:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6574,
,I/Prism.ItemManager( 1630): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1630): loadItems() com.htc.launcher.pageview.WidgetManager@283e03d6 +
I/Prism.WidgetManager( 1630): onLoadItems() +
,W/ResourcesManager( 1630): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/PMS     (  970): acquireWL(ad078b): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6904 10159 null,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6904, uid=10159, userID:0
,D/PMS     (  970): releaseWL(ad078b): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 6904): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6904): Stop autocaching.
,D/WearableService( 5186): callingUid 10024, callindPid: 5186
,W/ResourcesManager( 1630): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/GmsUtils( 6904): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 6904): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/asset   ( 1630): Copying FileAsset 0x559e261310 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1630): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1630): onLoadItems() -
I/Prism.ItemManager( 1630): loadItems() com.htc.launcher.pageview.WidgetManager@283e03d6 -
,D/PhoneApp( 1571): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1571): -- N1 =0,
,D/PhoneApp( 1571): -- N2 =0
,D/PhoneApp( 1571): -- N3 =0,
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=32.9, 0.0, 0.0  rx=37.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-959889915] gl hn u24 rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=32.9, 0.0, 0.0  rx=37.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959889914] gl hn u24 rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1363): environment dirty rate=0 [0][0][0],
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -66 abnormalRssiCnt = 0 newLinkSpeed = 57
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-66 linkspeed=57
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -66, 3
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=16.44 txretriesrate=0.00 rxrate=18.94 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
E/WifiStateMachine(  970): handleMessage: X
,D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -66, 3
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=203 Rx=249
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1222): WifiActivity: 2
E/WifiTrafficPoller(  970):  packet count Tx=204 Rx=249
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,E/WifiTrafficPoller(  970): notifying of data activity 2
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=175 rxSum=144} preTxRxSum={txSum=175 rxSum=144}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  970):  packet count Tx=204 Rx=249
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  970): notifying of data activity 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6674): 
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6674): 
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6674): 
,I/jxcore-log( 6674): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6674): 
,D/Process (  970): killProcessQuiet, pid=6513,
I/ActivityManager(  970): Killing 6513:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=16.4, 0.0, 0.0  rx=18.9 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-959886889] gl hn u24 rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=16.4, 0.0, 0.0  rx=18.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-959886886] gl hn u24 rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1363): environment dirty rate=0 [1][0][0]
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.72 txretriesrate=0.00 rxrate=9.97 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
,I/ActivityManager(  970): Recipient 6513,
,D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -65, 3
E/WifiStateMachine(  970): handleMessage: X
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1222): WifiActivity: 1
,E/WifiTrafficPoller(  970):  packet count Tx=204 Rx=250
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 1
,D/Process (  970): killProcessQuiet, pid=6727,
I/ActivityManager(  970): Killing 6727:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/jxcore-log( 6674): Test app app.js loaded,
I/jxcore-log( 6674): 
,I/chromium( 6674): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): 	Bluetooth MAC address: 90:E7:C4:F6:69:77, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6674): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48f77a6 added. We now have 1 listener(s)
D/BluetoothAdapter( 6674): 881615278: getState(). Returning 12
I/jxcore-log( 6674): BLE advertisement is supported
I/jxcore-log( 6674): 
,I/ActivityManager(  970): Recipient 6727
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=206 Rx=252,
D/WIFI_ICON( 1222): WifiActivity: 3
E/WifiTrafficPoller(  970): notifying of data activity 3,
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/PMS     (  970): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@215fe8aa,
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM32181 Light sensor (handle=0x00000003, connections=1)
W/PMN     (  970): goingToSleep
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
I/PMS     (  970): Sleeping (uid 1000)...
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@215fe8aa, eanble = 0, strlen(mName) = 91
D/XAN-DPS (  970): prepareColorFade 1
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  970): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3e1cbcf5
W/SensorService(  970): Listener[1] = com.htc.smartdim.sensor_eye@21962436
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1222): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  970): mWirelessDisplayManager is null
,D/PMS     (  970): acquireWL(25e4ad0a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 970 1000 null
W/PMS     (  970): mWirelessDisplayManager is still null,
W/PMN     (  970): goingToSleep done
,D/PMS     (  970): releaseWL(25e4ad0a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  970): ACTION_SCREEN_ON
I/AlarmManager(  970): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done recovering
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 24
I/AlarmManager(  970): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  970):  packet count Tx=206 Rx=252
E/WifiTrafficPoller(  970): notifying of data activity 0
,I/Adreno-EGL(  970): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  970): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  970): Build Date: 03/09/15 Mon
I/Adreno-EGL(  970): Local Branch: 
I/Adreno-EGL(  970): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  970): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  970):                  d74aa161a12b9c6fc6332151
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 3
,W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,E/WifiStateMachine(  970): handleMessage: E msg.what=131167
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
,E/WifiStateMachine(  970):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1363): SET_SCREEN_ON:On
I/wpa_supplicant( 1363): htc_wext_set_keepalive +,
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,I/wpa_supplicant( 1363): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1363): getPrivFuncNum +	
I/wpa_supplicant( 1363): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1363): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1363): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1363): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1363): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  970): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  970): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  970): handleScreenStateChanged Exit: true
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1363): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=177 rxSum=146} preTxRxSum={txSum=177 rxSum=146}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/wpa_supplicant( 1363): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -66 abnormalRssiCnt = 0 newLinkSpeed = 57
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-66 linkspeed=57
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
,E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131127
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131129
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
,E/WifiStateMachine(  970):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1363): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1363): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
,E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): handleMessage: X
,V/SRS_Proc(  422): ParamSet string: screen_state=on
,E/audio_a2dp_hw(  422): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  970): handleMessage: E msg.what=155650,
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/NetworkPolicy(  970): updateScreenOn: false
V/NetworkPolicy(  970): updateIfacesLocked()
,D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WIFI_ICON( 1222): WifiActivity: 0
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/IntentController( 1222): receive(android.intent.action.SCREEN_ON,1,false),
,I/ActivityManager(  970): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=7176 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/PMS     (  970): acquireWL(26a88fd6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(271ca257): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(26a88fd6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(271ca257): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  970): prepareColorFade done
,D/XAN-DPS (  970): setBrightness to 0
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@3e1cbcf5
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  970): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/DotMatrix( 1312): [EventService]  onDisplayChanged: 0
V/ActivityManager(  970): Display changed displayId=0
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/AlarmManager(  970): ACTION_SCREEN_OFF
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
I/AlarmManager(  970): [AlarmQueuing] screen off now: 
I/AlarmManager(  970): [AlarmQueuing] data connection: true
I/AlarmManager(  970): [AlarmQueuing] wifi connection: true
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/WifiDataStallTracker(  970): stopDataStallAlarm 
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  970): handleMessage: E msg.what=131167
E/WifiStateMachine(  970): processMsg: ConnectedState
W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@3e1cbcf5, eanble = 0, strlen(mName) = 67
E/WifiStateMachine(  970):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@21962436
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  422): ParamSet string: screen_state=off
E/audio_a2dp_hw(  422): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  970): processMsg: ConnectModeState
,E/WifiStateMachine(  970):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
W/ContextImpl( 7176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  970):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
D/WifiController(  970): handleMessage: E msg.what=155651
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiController(  970): handleMessage: X
D/wpa_supplicant( 1363): wlan0: Control interface command 'SET_SCREEN_ON 0'
,I/wpa_supplicant( 1363): SET_SCREEN_ON:Off
I/wpa_supplicant( 1363): htc_wext_set_keepalive +
I/wpa_supplicant( 1363): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1363): getPrivFuncNum +	
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
I/wpa_supplicant( 1363): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1363): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1363): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1363): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1363): htc_wext_set_keepalive - ret = 0
D/DotMatrix( 1312): [EventService] mbHDMIConnect: false, mCoverOn:false
E/WifiStateMachine(  970): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  970): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  970): handleScreenStateChanged Exit: false
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): handleMessage: X
,D/NetworkPolicy(  970): updateScreenOn: false
V/NetworkPolicy(  970): updateIfacesLocked()
,D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/SensorManager( 1222): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@234e68a2, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  970): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  970): pid=1222, uid=10041
W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@234e68a2, eanble = 1, strlen(mName) = 57
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@21962436
W/SensorService(  970): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@234e68a2
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/ContextImpl( 7176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 7176): MY_DEBUG = false
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1312): [EventService] getTotalRam: 1842 Mb,
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/IntentController( 1222): receive(android.intent.action.SCREEN_OFF,1,false)
,D/SmartSyncUtils( 7176): isEpsOn(), nState = 0
,D/ContactMessageStore( 1571): start background delete task...
D/PMS     (  970): acquireWL(22dcbdb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(22dcbdb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/ContactMessageStore( 1571): size: 0 , 0
,D/ContactMessageStore( 1571): Background delete complete
,D/PMS     (  970): acquireWL(3fe89429): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(13e1c3ae): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7176 1000 null
,D/PMS     (  970): releaseWL(3fe89429): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(13e1c3ae): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AutoSetting( 1545): service - mHandler: cancel location update
D/AutoSetting( 1545): service -           changes count: 0,
I/RemoteViews( 1222): setHTCTheme(com.htc.updater,true,33751145)
,I/RemoteViews( 1222): apply : com.htc.updater 1 8 0 36
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartDim(  970): Init customizeScreenOffDelayClass error
,W/ContextImpl( 7176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 7176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 7176): isEpsOn(), nState = 0
,D/SmartSyncUtils( 7176): isEpsOn(), nState = 0
,W/ContextImpl( 7176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@21962436
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@21962436, eanble = 0, strlen(mName) = 36
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@234e68a2
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  970): pid=970, uid=1000
E/ActivityThread(  970): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3ba0f37 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3ba0f37 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  970): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  970): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  970): 	,at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  970): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  970): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  970): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  970): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  970): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/SensorService(  970): Active sensors: size = 2
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@21962436, eanble = 0, strlen(mName) = 36
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@234e68a2
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@21962436
,D/SmartSyncUtils( 7176): getMobilePolicyEnabled, result = true,
,D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 9
,I/PowerUsageList:PowerUsageHelper( 7176): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 7176): gen(), null == sipper.uidObj, userId = 0
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl(  970): Excessive delay in setPowerMode(): 293ms
D/PMS     (  970): Setting HAL interactive mode to false
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  970): Setting HAL interactive mode to false done
D/PMS     (  970): Setting HAL auto-suspend mode to true
D/PMS     (  970): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  970): screenObserver, isScreenOn=false
I/InputMethodManager( 6674): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{2fdaab0c VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@17eeb5e7
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Disable input method client, pid=6674
I/IntentController( 1222): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputManager(  970): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
D/HABCtrl (  970): TPE algorithm. remove timeout.
D/PMS     (  970): OOBE c monitor 11
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,D/PMS     (  970): acquireWL(d4d49e5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/NfcService( 1585): ScreenObserver: OFF
D/PMS     (  970): releaseWL(d4d49e5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  970): updateBatteryInfo
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NfcService( 1585): applyRouting - 0
D/WifiController(  970): handleMessage: X
D/PMS     (  970): runPSCheck
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  970): acquireWL(28a6cba): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1585 1027 null
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NfcService( 1585): applyRouting -2
D/NfcService( 1585): applyRouting
D/NfcService( 1585): Ignore this applyRouting...
,D/PMS     (  970): releaseWL(28a6cba): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/ClockController( 1222): stop clock update:screen off
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PowerUsageList:PowerUsageHelper( 7176): MY_DEBUG = false,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 26 num clients 9,
,D/Process (  970): killProcessQuiet, pid=6784,
,I/ActivityManager(  970): Killing 6784:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 26 num clients 9,
,I/ActivityManager(  970): Recipient 6784,
,D/PMS     (  970): releaseWL(16680288): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2924] from screen [on:0 period:-959883862] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959883861] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): handleMessage: X
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 5,
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1254] from screen [on:0 period:-959882607] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  970): processMsg: L2ConnectedState,
E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959882606] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
,E/WifiStateMachine(  970): handleMessage: X,
,D/HtcUPManager( 1222): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 5,
,D/ContactMessageStore( 1571): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1571): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Process (  970): killProcessQuiet, pid=5673
I/ActivityManager(  970): Killing 5673:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5673
,E/WifiStateMachine(  970): handleMessage: E msg.what=131165,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): handleMessage: X
,D/PMS     (  970): acquireWL(13ed276b): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024},
V/AlarmManager(  970): sending alarm PendingIntent{25be92c8: PendingIntentRecord{318d9f61 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144934, Int=0,
,D/PMS     (  970): releaseWL(13ed276b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/AutoSetting( 1545): service - handleMessage() stop self
,D/AutoSetting( 1545): service - onDestroy() END,
D/AutoSetting( 1545): service - handleMessage() quit looper
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  970): acquireWL(25e29a86): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 970 1000 null
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
,D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  970): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  970): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  970): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  970):  [handleDownloadXtraData]inject done.
D/PMS     (  970): acquireWL(383dd912): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null,
D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  970): releaseWL(25e29a86): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  970): releaseWL(383dd912): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/WifiStateMachine(  970): handleMessage: E msg.what=131326,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState what:131326 2 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  970): handleMessage: X
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  970): acquireWL(6518e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
,I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(6518e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  970): battery changed pluggedType: 2
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1571): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  970): acquireWL(1b32f2e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{1a12f0fb: PendingIntentRecord{3c9f4518 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=166818, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{13f1d999: PendingIntentRecord{139c745e android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455034081586, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{23c6603f: PendingIntentRecord{1c845d0c android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=200914, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{3bfd7655: PendingIntentRecord{1fb7786a com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192196, Int=0
,D/PMS     (  970): acquireWL(33cac15b): PARTIAL_WAKE_LOCK  *backup* 0x1 970 1000 null
,W/BackupManagerService(  970): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  970): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  970): releaseWL(33cac15b): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  970): acquireWL(3ba03df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1b32f2e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data,
,D/PMS     (  970): acquireWL(1bec22d1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(3ba03df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1970): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  970): releaseWL(1bec22d1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(193e00d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(193e00d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(19d8d410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(264f5b09): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(34ddd72f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(19d8d410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(99ec5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(99ec5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1970): Vacuum at: now=1455034114363 tag=VacuumService,
,I/GoogleURLConnFactory( 1970): Using platform SSLCertificateSocketFactory
,D/PMS     (  970): releaseWL(264f5b09): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(3d6d01a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(3d6d01a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(23fab74b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(23fab74b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1970): No account for auth token provided,
,D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1970): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1970): [NET] android_getaddrinfo_proxy+
D/libc    ( 1970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  400): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1970): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1970): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1970): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1970): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1970): No account for auth token provided
,W/Uploader( 1970): No account for auth token provided,
,W/Uploader( 1970): No account for auth token provided,
,W/Uploader( 1970):  no longer exists, so no auth token.,
,W/Uploader( 1970): No account for auth token provided,
,I/GLSUser ( 1970): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1970): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1970): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1970): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1970): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1222): reapply : com.google.android.gms 4 40,
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1970): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1970): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1970): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1970): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1970): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1970): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1970): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1970): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1970): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263),
E/Uploader( 1970): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1970): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1970): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1970): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1970): No account for auth token provided,
,D/PMS     (  970): releaseWL(34ddd72f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(261373ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(261373ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(3bcc093b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3bcc093b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1545): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@e2199a5,
,D/Process (  970): killProcessQuiet, pid=6810
I/ActivityManager(  970): Killing 6810:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6810,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  970): acquireWL(3f521858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3f521858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
,D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2,
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6674): --= Surplus to requirements =--
I/jxcore-log( 6674): 
,I/jxcore-log( 6674): ****TEST TOOK:  ms ****
I/jxcore-log( 6674): 
I/jxcore-log( 6674): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6674): 
,E/cutils-trace( 7230): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 7230): ====startRecUseTime====,
D/htc.customization.log.level( 7230):  is 
W/CustomizationLogLevel( 7230): Level value is invalid, use default level 2
,D/CustomizationManager( 7230):  Read ACC file spent 0.055 (s),
,D/CIDMapFileReader( 7230): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 7230): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7230): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7230): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7230): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 7230): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7230): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 7230): full path : /system/customize/CID/HTC__102.xml,
I/CustomizationCIDLoader( 7230): Parsing tag category name = system,
I/CustomizationCIDLoader( 7230): Parsing tag category name = application
,I/CustomizationCIDLoader( 7230): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 7230): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7230): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7230): Parsing tag category name = Settings,
I/CustomizationCIDLoader( 7230): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 7230): add string-array item, value = 42507,
I/CustomizationCIDLoader( 7230): add string-array item, value = 21902
I/CustomizationCIDLoader( 7230): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7230): add string-array item, value = 23420
I/CustomizationCIDLoader( 7230): add string-array item, value = 22299
,I/CustomizationCIDLoader( 7230): add string-array item, value = 24002
,I/CustomizationCIDLoader( 7230): add string-array item, value = 23210
I/CustomizationCIDLoader( 7230): add string-array item, value = 23205
I/CustomizationCIDLoader( 7230): add string-array item, value = 23806
I/CustomizationCIDLoader( 7230): add string-array item, value = 23430
I/CustomizationCIDLoader( 7230): add string-array item, value = 23408
,I/CustomizationCIDLoader( 7230): add string-array item, value = 27205
I/CustomizationCIDLoader( 7230): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 24002:D:0:0
,I/CustomizationCIDLoader( 7230): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7230): add string-array item, value = 27205:C:1:0
,D/CustomizationManager( 7230):  Read CID file spent 0.113 (s),
D/CustomizationManager( 7230):  All configurations done spent 0.114 (s)
,D/PackageManager(  970): deletePackageAsUser: pkg=com.test.thalitest, pid=7230, uid=2000 userid=0,
,I/ActivityManager(  970): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg,
D/Process (  970): killProcessQuiet, pid=6674
I/ActivityManager(  970): Killing 6674:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  970): Skipping PackageSetting{13ca776a com.example.hello/10374} due to missing metadata,
,I/ActivityManager(  970): Recipient 6674
I/WindowState(  970): WIN DEATH: Window{3b800719 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  970): Client connection lost with reason: 4
,E/InputEventReceiver( 1400): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{18b571b7 uid 10366 pid 6674} (c)'
,I/ActivityManager(  970):   Force finishing activity ActivityRecord{15a2c5ce u0 com.test.thalitest/.MainActivity t8}
,W/ActivityManager(  970): Spurious death for ProcessRecord{256f5db1 6674:com.test.thalitest/u0a366}, curProc for 6674: null
I/ActivityManager(  970): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
,I/ActivityManager(  970):   Force finishing activity ActivityRecord{15a2c5ce u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  970): Duplicate finish request for ActivityRecord{15a2c5ce u0 com.test.thalitest/.MainActivity t8 f}
,D/DotMatrix( 1312): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/PMS     (  970): acquireWL(6dd0296): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1312): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1782): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  970): releaseWL(6dd0296): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 1752): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  970): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1752): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/VoicemailCleanupService( 1694): Cleaning up data for package: com.test.thalitest
,I/[PluginManager]RegisterService( 1545): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest,
,I/art     ( 1630): Explicit concurrent mark sweep GC freed 23618(1410KB) AllocSpace objects, 6(380KB) LOS objects, 34% free, 30MB/46MB, paused 4.008ms total 104.647ms
,D/Prism.PackageStateRece_( 1630): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1630): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1630): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/[PluginManager]RegisterService( 1545): handle notify Blinkfeed plugin client changed
,D/AccTypeManager( 1752): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1630): Deferring update until onResume
,D/Launcher( 1630): waitUntilResume // bindAppsRemoved
I/ActivityManager(  970): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7250 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/PhoneApp( 1571): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,E/ExternalAccountType( 1752): Unsupported attribute readOnly,
,I/InputMethodManagerService(  970): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/PackageManager(  970): Unable to load service info ResolveInfo{7e3f5cc com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  970): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  970): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  970): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  970): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  970): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  970): Explicit concurrent mark sweep GC freed 45647(2MB) AllocSpace objects, 7(1192KB) LOS objects, 33% free, 18MB/28MB, paused 1.773ms total 242.625ms,
,W/asset   (  970): Copying FileAsset 0x559e118a70 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.,
,D/JobSchedulerService(  970): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  970): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  970): removeObsoleteFile: deleting file=8_task_thumbnail.png
,D/StatusBarManagerService(  970): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
,D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/FindExtension( 1630): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/ContextImpl( 7250): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,I/ThreadedRenderer( 1630): Defer allocateBuffers to drawing time,
,W/ResourcesManager(  970): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  970): Got RemoteException sending setActive(false) notification to pid 6674 uid 10366
,D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,D/Process (  970): killProcessQuiet, pid=6848,
I/ActivityManager(  970): Killing 6848:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  970): Recipient 6848
,E/NetworkScheduler.SchedulerReceiver( 1970): Invalid parameter app,
E/NetworkScheduler.SchedulerReceiver( 1970): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/PMS     (  970): acquireWL(27e09966): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1970 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(27e09966): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PackageBroadcastService( 4487): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 4487): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4487): Module APK com.google.android.play.games already loaded,
D/AccountUtils( 4487): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 4487): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4487): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  970): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7288 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/LocationSettingsChecker( 4487): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteDatabase( 4487): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4487): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4487): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 4487): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4487): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4487): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 4487): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4487): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4487): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4487): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4487): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4487): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 4487): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 4487): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4487): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 4487): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 4487): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 4487): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 4487): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4487): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 4487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 4487): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4487): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 4487): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 4487): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4487): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4487): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4487): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4487): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4487): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 4487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4487): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 4487): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 4487): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 4487): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4487): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4487): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4487): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFi,le:70)
E/SQLiteOpenHelper( 4487): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4487): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 4487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 4487): Opened phenotype.db in read-only mode
,W/SQLiteOpenHelper( 4487): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 4487): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4487): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 4487): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 4487): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 4487): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4487): Process: com.google.android.gms, PID: 4487
E/AndroidRuntime( 4487): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4487): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4487): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 4487): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4487): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4487): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 4487): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4487): 	,at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4487): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4487): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 4487): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  970): App crashed! Process: com.google.android.gms
,D/Process ( 4487): killProcess, pid=4487
,D/Process ( 4487): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  970): Can't write: system_app_crash,
E/DropBoxManagerService(  970): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  970): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  970): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  970): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  970): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  970): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  970): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  970): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  970): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  970): 	... 5 more
,I/ActivityManager(  970): Recipient 4487
,D/WifiService(  970): Client connection lost with reason: 4
I/ActivityManager(  970): Process com.google.android.gms (pid 4487) has died
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
,I/GAv4    ( 7288): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 7288):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7288):   adb logcat -s GAv4
,W/GAv4    ( 7288): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7288): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,E/SharedPreferencesImpl( 7288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
,E/SharedPreferencesImpl( 7288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7288): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 7288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 7288): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,E/SQLiteDatabase( 7288): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 7288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7288): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7288): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7288): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7288): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7288): ,	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7288): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7288): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7288): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7288): Opening the database failed, dropping the table and recreating it,
E/SharedPreferencesImpl( 7288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 7288): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 7288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7288): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7288): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7288): 	at fdw.a(Unknown Source),
E/SQLiteDatabase( 7288): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7288): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7288): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7288): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7288): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7288): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 7288): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7288): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
E/SharedPreferencesImpl( 7288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7288): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 7288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7288): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
E/SQLiteDatabase( 7288): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7288): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7288): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7288): 	at aen.run(PG:536)
,I/ActivityManager(  970): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=7325 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 7325): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7325): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/VoldConnector(  970): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 7288): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache,
,W/ResourcesManager( 7288): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7288): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  970): acquireWL(3e534d69): PARTIAL_WAKE_LOCK  AsyncService 0x1 7034 10167 null
,E/SQLiteDatabase( 7288): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7288): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7288): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7288): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7288): 	at aej.c(PG:139)
E/SQLiteDatabase( 7288): 	at aej.b(PG:398)
E/SQLiteDatabase( 7288): 	at agf.f(PG:417)
E/SQLiteDatabase( 7288): 	at oe.run(PG:1112)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7288): 	,at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 7288): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 7288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7288): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7288): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7288): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7288): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7288): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7288): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 7288): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 7288): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 7288): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 7288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7288): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7288): 	at java.lang.Thread.run(Thread.java:818)
D/PMS     (  970): releaseWL(3e534d69): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  970): acquireWL(f0a008f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 7034 10167 null,
I/MultiDex( 7325): VM with version 2.1.0 has multidex support
I/MultiDex( 7325): install
I/MultiDex( 7325): VM has multidex support, MultiDex support library is disabled.
,D/PMS     (  970): releaseWL(f0a008f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 7075): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
V/JNIHelp ( 7288): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  970): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=7355 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,E/SQLiteLog( 7075): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 7075): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x559dd837c0
,W/System  ( 7288): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/art     (  428): Explicit concurrent mark sweep GC freed 8667(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 222us total 25.998ms
I/ProviderInstaller( 7288): Installed default security provider GmsCore_OpenSSL
,E/SQLiteDatabase( 7325): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 7325): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219),
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7325): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7325): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
E/SQLiteDatabase( 7325): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 7325): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 7325): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 7325): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7325): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7325): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7325): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7325): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7325): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 7325): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 7325): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7325): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7325): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7325): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7325): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 7325): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 7325): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 7325): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7325): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7325): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7325): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7325): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7325): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7288): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7288): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7288): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7288): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7288): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7288): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7288): 	at aej.c(PG:139)
E/SQLiteDatabase( 7288): 	at aej.a(PG:358)
E/SQLiteDatabase( 7288): 	at aej.a(PG:345)
E/SQLiteDatabase( 7288): 	at agf.c(PG:884)
E/SQLiteDatabase( 7288): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 7288): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7288): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7288): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7288): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 7288): Failed to query Account133 object
E/AbstractDatabaseInstance( 7288): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7288): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7288): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7288): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7288): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7288): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7288): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7288): 	,at aej.c(PG:139)
E/AbstractDatabaseInstance( 7288): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 7288): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 7288): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 7288): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 7288): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 7288): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7288): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 7288): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7288): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7288): 	at java.lang.Thread.run(Thread.java:818)
,I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 168us total 21.950ms
,I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 157us total 21.506ms
,I/ActivityManager(  970): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=7381 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,V/GLSActivity( 1970): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SharedPreferencesImpl( 7288): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak,
,I/DeviceManagement( 7355): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7355 dbg=false s=true
,I/DeviceManagement( 7355): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,E/SharedPreferencesImpl( 7075): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
I/DeviceManagement( 7355): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
E/AndroidRuntime( 7075): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 7075): Process: com.google.android.googlequicksearchbox:search, PID: 7075
E/AndroidRuntime( 7075): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7075): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 7075): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 7075): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
,E/AndroidRuntime( 7075): ,	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 7075): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 7075): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 7075): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 7075): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 7075): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 7075): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335),
E/AndroidRuntime( 7075): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 7075): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 7075): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 7075): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 7075): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 7075): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 7075): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7075): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7075): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7075): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 7355): WorkflowService: Starting workflow service,
,I/DeviceManagement( 7355): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@3042ea29] args=[Bundle[mParcelledData.dataSize=112]],
I/DeviceManagement( 7355): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 7355): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 7355): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 7355): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  970): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7406 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
,E/ActivityManager(  970): App crashed! Process: com.google.android.googlequicksearchbox:search
,D/Process ( 7075): killProcess, pid=7075
,D/Process ( 7075): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  970): Can't write: system_app_crash
E/DropBoxManagerService(  970): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  970): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  970): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  970): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  970): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  970): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  970): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  970): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  970): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  970): 	... 5 more
,V/JNIHelp ( 7325): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/DeviceManagement( 7355): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 7355): SessionStateController: Checking invariants...
,W/ActivityThread( 7325): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7325): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13843cc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7325): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  970): Recipient 7075
I/ActivityManager(  970): Process com.google.android.googlequicksearchbox:search (pid 7075) has died
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,W/NativeLibraryUtils( 7325): Failed to open lock file,
W/NativeLibraryUtils( 7325): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7325): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7325): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7325): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7325): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7325): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7325): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7325): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7325): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7325): 	... 3 more
,E/SQLiteDatabase( 7406): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.,
E/SQLiteDatabase( 7406): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7406): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7406): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7406): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7406): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 7406): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 7406): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 7406): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 7406): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 7406): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 7406): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 7406): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 7406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7406): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7406): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7406): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7406): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7406): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7406): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7406): FATAL EXCEPTION: main
E/AndroidRuntime( 7406): Process: com.android.documentsui, PID: 7406
E/AndroidRuntime( 7406): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7406): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 7406): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 7406): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 7406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/AndroidRuntime( 7406): ,	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7406): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7406): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7406): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7406): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7406): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7406): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219),
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7406): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7406): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7406): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 7406): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 7406): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 7406): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 7406): ,	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 7406): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 7406): 	... 9 more
,I/Prism.ItemManager( 1630): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1630): loadItems() com.htc.launcher.pageview.WidgetManager@283e03d6 +
I/Prism.WidgetManager( 1630): onLoadItems() +
I/ActivityManager(  970): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=7432 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=7451 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a
,E/ActivityManager(  970): App crashed! Process: com.android.documentsui
D/ErrorReport(  970): HtcErrorReportManager Begin---add error logs to dropbox
,W/System.err(  970): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system),
W/System.err(  970): ,	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  970): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  970): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  970): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
,W/System.err(  970): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  970): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  970): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  970): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  970): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/GAv4-SVC( 7325): Google Analytics 7.8.99 is starting up.
W/System.err(  970): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  970): 	at libcore.io.Posix.open(Native Method)
W/System.err(  970): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  970): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  970): 	... 12 more
,W/System.err(  970): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  970): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  970): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  970): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  970): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  970): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  970): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  970): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  970): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  970): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  970): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  970): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/ResourcesManager( 1630): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  970): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  970): 	at libcore.io.Posix.open(Native Method)
,W/System.err(  970): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  970): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  970): 	... 14 more
,W/System.err(  970): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/ResourcesManager( 7432): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/System.err(  970): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  970): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  970): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  970): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  970): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
,W/System.err(  970): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  970): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  970): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  970): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  970): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  970): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  970): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  970): 	at libcore.io.Posix.open(Native Method)
W/System.err(  970): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err(  970): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  970): 	... 14 more
E/SQLiteDatabase( 7355): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7355): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7355): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7355): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 7355): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 7355): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 7355): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 7355): 	,at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
,E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 7355): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7355): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 7355): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7355): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 7355): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 7355): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 7355): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7355): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/SQLiteDatabase( 7355): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7355): 	at java.lang.Thread.run(Thread.java:818)
I/DeviceManagement( 7355): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/ErrorReport(  970): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  970): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455034167544.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  970): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  970): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  970): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  970): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  970): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  970): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  970): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  970): 	... 4 more
D/Process ( 7406): killProcess, pid=7406
,I/DeviceManagement( 7355): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 7355): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
D/Process ( 7406): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteDatabase( 7355): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7355): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7355): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7355): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7355): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 7355): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 7355): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 7355): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 7355): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 7355): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 7355): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7355): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E,/SQLiteDatabase( 7355): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7355): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 7355): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@3042ea29]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/DeviceManagement( 7355): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
W/DeviceManagement( 7355): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/DeviceManagement( 7355): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 7355): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 7355): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 7355): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 7355): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 7355): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 7355): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 7355): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 7355): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 7355): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process (  970): killProcessQuiet, pid=6947
I/ActivityManager(  970): Killing 6947:com.google.android.apps.magazines/u0a161 (adj ,15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 

```
