#### Test 581356550b07fff_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7
--------- beginning of system
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  984):  packet count Tx=130 Rx=210
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  984): notifying of data activity 1
E/WifiStateMachine(  984): handleMessage: E msg.what=131155
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1043524399] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1043524397] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984):  get link layer stats 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1323): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  984): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  984): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.44 txretriesrate=0.00 rxrate=1.39 userTriggerdPenalty0
E/WifiStateMachine(  984):  good link -> stuck count =0
E/WifiStateMachine(  984):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  984):  isHighRSSI       ---> score=61
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  984): handleMessage: X
D/WifiWatchdogStateMachine(  984): RSSI current: 3 new: -63, 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  984):  packet count Tx=130 Rx=210
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  984): notifying of data activity 0
,E/WifiDataStallTracker(  984): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  984): updateDataStallInfo: mDataStallTxRxSum={txSum=113 rxSum=103} preTxRxSum={txSum=113 rxSum=103}
D/WifiDataStallTracker(  984): updateDataStallInfo: NONE
D/WifiDataStallTracker(  984): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/cutils-trace( 6425): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6425): ====startRecUseTime====
D/htc.customization.log.level( 6425):  is 
W/CustomizationLogLevel( 6425): Level value is invalid, use default level 2
D/CustomizationManager( 6425):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6425): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6425): Parsing tag category name = system
I/CustomizationCIDLoader( 6425): Parsing tag category name = application
I/CustomizationCIDLoader( 6425): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6425): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6425): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6425): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6425): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6425): add string-array item, value = 42507
I/CustomizationCIDLoader( 6425): add string-array item, value = 21902
I/CustomizationCIDLoader( 6425): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6425): add string-array item, value = 23420
I/CustomizationCIDLoader( 6425): add string-array item, value = 22299
I/CustomizationCIDLoader( 6425): add string-array item, value = 24002
I/CustomizationCIDLoader( 6425): add string-array item, value = 23210
I/CustomizationCIDLoader( 6425): add string-array item, value = 23205
I/CustomizationCIDLoader( 6425): add string-array item, value = 23806
I/CustomizationCIDLoader( 6425): add string-array item, value = 23430
I/CustomizationCIDLoader( 6425): add string-array item, value = 23408
I/CustomizationCIDLoader( 6425): add string-array item, value = 27205
I/CustomizationCIDLoader( 6425): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6425):  Read CID file spent 0.095 (s)
D/CustomizationManager( 6425):  All configurations done spent 0.095 (s)
I/ActivityManager(  984): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6425 on display 0
D/PMS     (  984): acquireHCC(1bcb064d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 984 1000 null
D/PMS     (  984): acquireHCC(1deb5502): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 984 1000 null
W/asset   (  984): Copying FileAsset 0x55684927c0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  984): acquireWL(22ceba49): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 984 1000 null
I/FeedHostManager( 1615): [onPause]
I/FeedProviderManager( 1615): onPause
I/FeedHostManager( 1615): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2a585bf6
I/SocialFeedProvider( 1615): +onPause
I/SocialFeedProvider( 1615): -onPause
I/AnimationUtil(  984): isHTCRecent(ThaliTest/Recent screens.)/7
W/HtcSystemUPManager(  984): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  984): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6444 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/asset   ( 6444): Copying FileAsset 0xac15dab8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/StatusBarManagerService(  984): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  984): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  984): hiding MENU key
I/TrimMemoryManager( 1615): [trimMemory] 20
,I/WebViewFactory( 6444): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6444): Time to load native libraries: 10 ms (timestamps 4901-4911)
,I/LibraryLoader( 6444): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6444): Binding Chromium to main looper Looper (main, tid 1) {3f70a213}
,I/LibraryLoader( 6444): Expected native library version number "",actual native library version number ""
,I/chromium( 6444): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6444): Initializing chromium process, singleProcess=true,
,W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6444): ApplicationContext is null in ApplicationStatus,
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  984):  packet count Tx=130 Rx=210
,W/chromium( 6444): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6444): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6444): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6444): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6444): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6444): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6444): Local Branch: 
I/Adreno-EGL( 6444): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6444): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6444):                  d74aa161a12b9c6fc6332151
,W/System.err(  984): java.lang.Throwable: stack dump
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  984): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d3e97fe:true
,W/System.err(  984): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  984): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  984): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  984): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6444): 940150140: getState(). Returning 12
,W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6444): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6444): CordovaWebView is running on device made by: HTC,
W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  984): Explicit concurrent mark sweep GC freed 23390(1217KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 2.606ms total 171.361ms
,W/chromium( 6444): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FindExtension( 6444): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
I/HtcModeClient( 3201): handler message = 4011
E/HtcModeClient( 3201): Check connection and retry 11 times.
,I/InputMethodManager( 6444): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@19894dac, mServedView=org.apache.cordova.engine.SystemWebView{3428aa75 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@24be6a0a
,I/InputMethodManagerService(  984): Disable input method client, pid=1615
,D/StatusBarManagerService(  984): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  984): Enable input method client, pid=6444
,I/ActivityManager(  984): Displayed com.test.thalitest/.MainActivity: +793ms
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false),
,D/PMS     (  984): releaseWL(22ceba49): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,W/BindingManager( 6444): Cannot call determinedVisibility() - never saw a connection for the pid: 6444
,W/XT9_C   ( 1404): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
I/XT9_C   ( 1404): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1404): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1404): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/JsMessageQueue( 6444): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6444): JniHelper::setJavaVM(0xaaff28f8), pthread_self() = -1405906120
,I/chromium( 6444): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  984):  packet count Tx=130 Rx=211
E/WifiTrafficPoller(  984): notifying of data activity 1,
,D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  984): acquireWL(2347b447): PARTIAL_WAKE_LOCK  *alarm* 0x1 984 1000 WorkSource{10072}
,V/AlarmManager(  984): sending alarm PendingIntent{145f9474: PendingIntentRecord{11a5bd9d com.android.vending startService}}, i=null, t=0, cnt=1, w=1454950388240, Int=0
V/AlarmManager(  984): sending alarm PendingIntent{7c5c212: PendingIntentRecord{3c414de3 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454950391425, Int=536832000
,V/AlarmManager(  984): sending alarm PendingIntent{107277e5: PendingIntentRecord{16302ba android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454950384536, Int=20000
,V/CheckinService( 4417): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,D/PMS     (  984): acquireWL(2e1b83e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4417 10024 WorkSource{10024 com.google.android.gms}
,D/WifiDisplayAdapter(  984): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  984):     Client/Owner: Client
D/WifiDisplayAdapter(  984):     GroupId: 
D/WifiDisplayAdapter(  984):     Passphrase: 
D/WifiDisplayAdapter(  984):     SessionId: 0
D/WifiDisplayAdapter(  984):     IP Address: }
,E/WifiStateMachine(  984): WiFiStateMachine SCAN ALARM
D/PMS     (  984): releaseWL(2347b447): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  984): handleMessage: E msg.what=131143
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:93 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 list=2412 [on:0 tx:0 rx:0 period:2483] from screen [on:0 period:-1043521893]
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:93 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1043521892]
E/WifiStateMachine(  984): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.44 rxSuccessRate=1.39 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-63
E/WifiStateMachine(  984): WifiStateMachine CMD_START_SCAN with age=23141 interval=60000 maxinterval=300000
E/WifiStateMachine(  984): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  984): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  984): has c0:ff:d4:d3:aa:48 freq=2412 age=2488 ?=true
E/WifiStateMachine(  984): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1323): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1323): wpa_supplicant_scan enter
D/wpa_supplicant( 1323): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1323): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1323): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1323): WPS:  * Request Type
D/wpa_supplicant( 1323): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1323): WPS:  * UUID-E
D/wpa_supplicant( 1323): WPS:  * Primary Device Type
D/wpa_supplicant( 1323): WPS:  * RF Bands (3)
D/wpa_supplicant( 1323): WPS:  * Association State
D/wpa_supplicant( 1323): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1323): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1323): WPS:  * Manufacturer
D/wpa_supplicant( 1323): WPS:  * Model Name
D/wpa_supplicant( 1323): WPS:  * Model Number
,D/wpa_supplicant( 1323): WPS:  * Device Name
D/wpa_supplicant( 1323): WPS:  * Version2 (0x20)
D/PMS     (  984): acquireWL(3e39ed5e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4417 10024 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1323): P2P: * P2P IE header
D/wpa_supplicant( 1323): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1323): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1323): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1323): wlan0: Add radio work 'scan'@0x5594bc7680
D/wpa_supplicant( 1323): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1323): wlan0: Starting radio work 'scan'@0x5594bc7680 after 0.000059 second wait
D/wpa_supplicant( 1323): wlan0: nl80211: scan request
D/wpa_supplicant( 1323): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1323): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1323): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1323): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1323): wlan0: Own scan request started a scan in 0.000159 seconds
I/wpa_supplicant( 1323): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  984): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  984): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  984): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  984): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  984): [1,454,950,391,457 ms] noteScanstart no scan source
E/WifiStateMachine(  984): handleMessage: X
,D/PMS     (  984): releaseWL(2e1b83e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4417): Checking schedule, now: 1454950391486 next: 1454950391425
I/CheckinService( 4417): active receiver: enabled
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4417, uid=10024, userID:0
,I/CheckinService( 4417): Preparing to send checkin request
,I/EventLogService( 4417): Accumulating logs since 1454950356769
,I/CheckinRequestBuilder( 4417): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  984): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4417): Failed to find provider info for com.google.android.wearable.settings
,D/wpa_supplicant( 1323): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,D/wpa_supplicant( 1323): wlan0: nl80211: New scan results available
,D/wpa_supplicant( 1323): nl80211: Scan included frequencies: 2412
W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1323): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1323): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1323): wlan0: Scan completed in 0.080372 seconds
,D/wpa_supplicant( 1323): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1323): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1323): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1323): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-53
I/wpa_supplicant( 1323): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1323): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1323): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
D/wpa_supplicant( 1323): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1323): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1323): wlan0: Scan-only results received
D/wpa_supplicant( 1323): wlan0: Radio work 'scan'@0x5594bc7680 done in 0.081532 seconds
E/WifiMonitor(  984): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  984): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  984): handleMessage: E msg.what=147461
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  984): processMsg: ConnectModeState
E/WifiStateMachine(  984):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  984): processMsg: DriverStartedState
E/WifiStateMachine(  984):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  984): processMsg: SupplicantStartedState
E/WifiStateMachine(  984):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1323): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  984): [1,454,950,391,539 ms] noteScanEnd no scan source
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1323): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  984): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@198c7585 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  984): NG7005g c0:ff:d4:d3:aa:4a rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  984): NG700 c0:ff:d4:d3:aa:48 rssi=-63 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  984): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  984): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  984):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-63 freq=2412
E/WifiAutoJoinController (  984): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  984): Gonzos 38:f8:89:11:e9:11 rssi=-75 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  984): ageScanResultsOut delay 40000 size 4 now 1454950391542
E/WifiAutoJoinController (  984): newSupplicantResults size=4 known=1 true
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1323): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  984): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  984): ssid=NG700
E/WifiAutoJoinController (  984): id=0
E/WifiAutoJoinController (  984): mode=station
E/WifiAutoJoinController (  984): pairwise_cipher=CCMP
E/WifiAutoJoinController (  984): group_cipher=CCMP,
E/WifiAutoJoinController (  984): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  984): wpa_state=COMPLETED
E/WifiAutoJoinController (  984): ip_address=192.168.1.130
E/WifiAutoJoinController (  984): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  984): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  984): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  984): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  984): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-63,-127) num=(1,0)
E/WifiAutoJoinController (  984): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  984): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-63 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  984): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  984): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  984): Done attemptAutoJoin status=0
E/WifiConfigStore(  984):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  984): handleMessage: X
,I/GLSUser ( 1859): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1859): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1859): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1859): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1859): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
,W/CheckinRequestBuilder( 4417): awaiting user notification for token
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,D/PMS     (  984): releaseHCC(1bcb064d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  984): releaseHCC(1deb5502): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/ActivityManager(  984): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6501 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 6501): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6501): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/jxcore-log( 6444): Initializing JXcore engine
,W/jxcore-log( 6444): JXcore engine is ready
,I/MultiDex( 6501): VM with version 2.1.0 has multidex support,
I/MultiDex( 6501): install
I/MultiDex( 6501): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6501): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/jxcore-log( 6444): Starting JXcore engine
,W/System  ( 6501): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2008755: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
,W/ActivityThread( 6501): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 6501): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1859): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Finsky  ( 5962): [597] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/AuthorizationBluetoothService( 1859): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4417): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,D/Finsky  ( 5962): [1] 5.onFinished: Installation state replication succeeded.,
E/WifiStateMachine(  984): handleMessage: E msg.what=131155
E/WifiStateMachine(  984): processMsg: ConnectedState
,E/WifiStateMachine(  984):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:511] from screen [on:0 period:-1043521374] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  984): processMsg: L2ConnectedState
,E/WifiStateMachine(  984):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1043521372] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  984):  get link layer stats 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1323): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  984): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
,E/WifiStateMachine(  984): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.22 txretriesrate=0.00 rxrate=1.19 userTriggerdPenalty0
E/WifiStateMachine(  984):  good link -> stuck count =0
E/WifiStateMachine(  984):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  984):  isHighRSSI       ---> score=61
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  984): RSSI current: 3 new: -62, 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  984): handleMessage: X
D/WearableService( 5676): callingUid 10024, callindPid: 5676
,E/MDM     ( 1834): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/jxcore-log( 6444): Platform android
W/jxcore-log( 6444): 
W/jxcore-log( 6444): Process ARCH arm
W/jxcore-log( 6444): 
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4417, uid=10024, userID:0,
,I/WVCdm   (  435): CdmEngine::OpenSession
I/WVCdm   (  435): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  435): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/LocationInitializer( 4417): Restart initialization of location
E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  984):  packet count Tx=130 Rx=211
E/WifiTrafficPoller(  984): notifying of data activity 0
D/WIFI_ICON( 1221): WifiActivity: 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/DrmWidevineDash(  435): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  435): Service_Initialize: starts!
D/QSEECOMAPI: (  435): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  435): App is not loaded in QSEE,
,E/QSEECOMAPI: (  435): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  435): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  435): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  435): App is not loaded in QSEE
,D/QSEECOMAPI: (  435): Loaded image: APP id = 8
,D/DrmWidevineDash(  435): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  435): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  435): qsapps_get_capabilities: returns 0
,D/DrmWidevineDash(  435): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf469e000
E/DrmWidevineDash(  435): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf469e000
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  548): got the req here! ret=0
D/DrmLibTime(  548): command id, time_cmd_id = 770
,D/DrmLibTime(  548): time_getutcsec starts!
D/DrmLibTime(  548): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  548): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  548): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  548): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  548): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  548): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  548): QSEE Time Listener: Retrieved Android system time: 1454950392
D/DrmLibTime(  548): time_getutcsec returns 0, sec = 1454950392; nsec = 0
D/DrmLibTime(  548): time_getutcsec finished! 
D/DrmLibTime(  548): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  548): before calling ioctl to read the next time_cmd
E/QC-time-services(  472): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  435): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): hlos api version =  9
D/DrmWidevineDash(  435): tz api version =  9
D/DrmWidevineDash(  435): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  435): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  435): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  435): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  435): OEMCrypto_OpenSession: starts! SID=0xff999da8
D/DrmWidevineDash(  435): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  435): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  435): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_GetRandom: starts! randomData=0xab260710, dataLength=8
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab1b77d8, wrapped_rsa_key_length=1280
,D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  435): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  435): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  435): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  435): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  435): OEMCrypto_GetDeviceID: starts! deviceID=0xab1b6610, idLength=0xf4b0f6f8
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  435): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
,D/DrmWidevineDash(  435): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  435): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  435): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b0f70e, maximum = 0xf4b0f70f
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  435): hlos api version =  9
D/DrmWidevineDash(  435): tz api version =  9
D/DrmWidevineDash(  435): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  435): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b0f77c
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  435): PrepareKeyRequest: nonce=851997722
D/DrmWidevineDash(  435): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab301b00
D/DrmWidevineDash(  435): message_length=1611, signature=0xab302150, signature_length=0xf4b0f6dc
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  435): CdmEngine::CloseSession
D/DrmWidevineDash(  435): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  435): L3 Terminate.
D/DrmWidevineDash(  435): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): Service_Uninitialize: starts!
D/QSEECOMAPI: (  435): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  435): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  435): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  435): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  435): CdmEngine::OpenSession
,I/WVCdm   (  435): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  435): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  435): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  435): Service_Initialize: starts!
D/QSEECOMAPI: (  435): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  435): App is not loaded in QSEE
E/QSEECOMAPI: (  435): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  435): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  435): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  435): App is not loaded in QSEE
,D/QSEECOMAPI: (  435): Loaded image: APP id = 9
,D/DrmWidevineDash(  435): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  435): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  435): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  435): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf469e000
E/DrmWidevineDash(  435): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf469e000
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  548): got the req here! ret=0,
D/DrmLibTime(  548): command id, time_cmd_id = 770
D/DrmLibTime(  548): time_getutcsec starts!
D/DrmLibTime(  548): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  548): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  548): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  548): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  548): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
,D/DrmLibTime(  548): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,D/DrmLibTime(  548): QSEE Time Listener: Retrieved Android system time: 1454950392
D/DrmLibTime(  548): time_getutcsec returns 0, sec = 1454950392; nsec = 0
,D/DrmLibTime(  548): time_getutcsec finished! 
D/DrmLibTime(  548): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  548): before calling ioctl to read the next time_cmd
,E/QC-time-services(  472): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): hlos api version =  9
D/DrmWidevineDash(  435): tz api version =  9
D/DrmWidevineDash(  435): OEMCrypto_APIVersion: ends! returns version 9,
D/DrmWidevineDash(  435): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/jxcore-log( 6444): JXcore Cordova bridge is ready!
I/jxcore-log( 6444): 
W/jxcore-log( 6444): JXcore engine is started
,E/jxcore  ( 6444): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6444): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  435): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  435): OEMCrypto_OpenSession: starts! SID=0xff999da8
D/DrmWidevineDash(  435): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  435): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  435): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_GetRandom: starts! randomData=0xab2fed00, dataLength=8
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab1b77d8, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  435): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  435): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  435): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  435): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  435): OEMCrypto_GetDeviceID: starts! deviceID=0xab1b6630, idLength=0xf49136f8
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/chromium( 6444): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  435): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  435): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_GetHDCPCapability: starts!, current = 0xf491370e, maximum = 0xf491370f
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  435): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): hlos api version =  9
D/DrmWidevineDash(  435): tz api version =  9
D/DrmWidevineDash(  435): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  435): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf491377c
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  435): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  435): PrepareKeyRequest: nonce=2170092338
D/DrmWidevineDash(  435): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab1c6910
D/DrmWidevineDash(  435): message_length=1646, signature=0xab1c6f88, signature_length=0xf49136dc
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/PMS     (  984): acquireWL(2e89ff41): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 984 1000 null
W/PluginManager( 6444): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 41ms. Plugin should use CordovaInterface.getThreadPool().
W/HtcSystemUPManager(  984): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1615): [onResume]
,I/FeedProviderManager( 1615): onResume
I/SocialFeedProvider( 1615): +onResume
I/SocialFeedProvider( 1615): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1615): -onResume
,D/StatusBarManagerService(  984): setSystemUiVisibility(0x700),
D/FindExtension( 1615): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,D/StatusBarManagerService(  984): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/ThreadedRenderer( 1615): Defer allocateBuffers to drawing time
D/StatusBarManagerService(  984): hiding MENU key
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false),
I/InputMethodManagerService(  984): Disable input method client, pid=6444
D/StatusBarManagerService(  984): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  984): Enable input method client, pid=1615
W/IInputConnectionWrapper( 6444): reportFullscreenMode on inactive InputConnection
,D/PMS     (  984): releaseWL(2e89ff41): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  435): CdmEngine::CloseSession,
D/DrmWidevineDash(  435): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  435): L3 Terminate.
D/DrmWidevineDash(  435): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  435): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  435): Service_Uninitialize: starts!
D/QSEECOMAPI: (  435): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  435): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  435): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  435): OEMCrypto_Terminate: ends! returns 0
,D/StatusBarManagerService(  984): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  984): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  984): hiding MENU key
,E/cutils-trace( 6535): Error opening trace file: Permission denied (13)
I/dex2oat ( 6535): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6535): dex2oat: override thread count:4
,I/dex2oat ( 6535): dex2oat took 74.305ms (threads: 4)
,I/Adreno-EGL( 6501): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6501): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6501): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6501): Local Branch: 
I/Adreno-EGL( 6501): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6501): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6501):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6501): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6501): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6501): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6501): Local Branch: 
I/Adreno-EGL( 6501): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6501): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6501):                  d74aa161a12b9c6fc6332151
,I/CheckinRequestBuilder( 4417): Classify the device as Phone.
,D/libc    ( 4417): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4417): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4417): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4417): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4417): [NET] android_getaddrinfo_proxy+
D/libc    ( 4417): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4417): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4417): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4417): [NET] android_getaddrinfofornet-, err=8
,W/OpenGLRenderer( 1615): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  984):  packet count Tx=137 Rx=216
D/WIFI_ICON( 1221): WifiActivity: 3
E/WifiTrafficPoller(  984): notifying of data activity 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    ( 4417): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
,D/libc    ( 4417): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4417): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4417): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4417): Sending checkin request (8435 bytes),
,I/CheckinRequestBuilder( 4417): Checkin reason type: 11 attempt count: 1,
,I/ActivityManager(  984): Cannot resolve ContentProvider=com.google.android.wearable.settings,
E/ActivityThread( 4417): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1859): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1859): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1859): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1859): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1859): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,W/CheckinRequestBuilder( 4417): awaiting user notification for token
,I/CheckinRequestBuilder( 4417): Classify the device as Phone.
,I/CheckinTask( 4417): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4417): Checking schedule, now: 1454950393929 next: 1455487225923
I/CheckinService( 4417): active receiver: disabled
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4417, uid=10024, userID:0
,D/PMS     (  984): releaseWL(3e39ed5e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  984): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6546 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/PhoneMonitor( 6546): Register our PhoneStateListener,
,V/SetupWizard( 6546): Connected to Gservices successfully,
,D/PhoneMonitor( 6546): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/ChimeraCfgMgr( 4417): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 4417): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PhoneMonitor( 6546): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,D/GCM     ( 1859): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=225
,E/WifiDataStallTracker(  984): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  984): updateDataStallInfo: mDataStallTxRxSum={txSum=130 rxSum=116} preTxRxSum={txSum=113 rxSum=103}
D/WifiDataStallTracker(  984): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  984): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,E/WifiStateMachine(  984): handleMessage: E msg.what=131155,
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1043518352] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1043518351] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984):  get link layer stats 0
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1323): environment dirty rate=5 [17][1][0],
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  984): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
,E/WifiStateMachine(  984): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.61 txretriesrate=0.00 rxrate=7.60 userTriggerdPenalty0
E/WifiStateMachine(  984):  good link -> stuck count =0
E/WifiStateMachine(  984):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  984):  isHighRSSI       ---> score=65
E/WifiStateMachine(  984): handleMessage: X
D/WifiWatchdogStateMachine(  984): RSSI current: 3 new: -62, 3
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1221): WifiActivity: 0
,E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=225
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  984): notifying of data activity 0
,I/HtcModeClient( 3201): handler message = 4011,
E/HtcModeClient( 3201): Check connection and retry 12 times.
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=225
,D/Process (  984): killProcessQuiet, pid=6178
I/ActivityManager(  984): Killing 6178:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  984): Recipient 6178,
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=226
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  984): notifying of data activity 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Process (  984): killProcessQuiet, pid=6254,
I/ActivityManager(  984): Killing 6254:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  984): Recipient 6254
D/WifiService(  984): Client connection lost with reason: 4
,D/Process (  984): killProcessQuiet, pid=6211
I/ActivityManager(  984): Killing 6211:com.google.android.apps.docs/u0a101 (adj 15): empty #18
,D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  984): Recipient 6211
,E/WifiStateMachine(  984): handleMessage: E msg.what=131155
E/WifiStateMachine(  984): processMsg: ConnectedState
,E/WifiStateMachine(  984):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1043515329] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1043515328] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  984):  get link layer stats 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1323): environment dirty rate=0 [0][0][0]
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3,
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  984): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  984): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.31 txretriesrate=0.00 rxrate=4.30 userTriggerdPenalty0
E/WifiStateMachine(  984):  good link -> stuck count =0
E/WifiStateMachine(  984):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  984):  isHighRSSI       ---> score=61
E/WifiStateMachine(  984): handleMessage: X
,D/WifiWatchdogStateMachine(  984): RSSI current: 3 new: -63, 3
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=226
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  984): notifying of data activity 0
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=226
,E/WifiDataStallTracker(  984): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  984): updateDataStallInfo: mDataStallTxRxSum={txSum=130 rxSum=116} preTxRxSum={txSum=130 rxSum=116},
D/WifiDataStallTracker(  984): updateDataStallInfo: NONE
D/WifiDataStallTracker(  984): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=227
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  984): notifying of data activity 1
,I/HtcModeClient( 3201): handler message = 4011,
,E/HtcModeClient( 3201): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3201): Don't start project servcice
,D/HtcModeClient( 3201): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3201): connectState: CONNECTION_READY = false
,D/SilentMusic( 3201): call stop
D/HtcModeClient( 3201): close connection,
W/HtcModeClient( 3201): leaveProjectMode: It does not enter ProjectMode,
,W/CANMesgAgentLocalSocket( 3201): read the terminate packet, so break
,D/Process (  984): killProcessQuiet, pid=3201
,I/ActivityManager(  984): Killing 3201:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  984): Recipient 3201
,E/WifiStateMachine(  984): handleMessage: E msg.what=131155,
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1043512307] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1043512306] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984):  get link layer stats 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL',
,I/wpa_supplicant( 1323): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  984): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  984): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.15 txretriesrate=0.00 rxrate=2.65 userTriggerdPenalty0
E/WifiStateMachine(  984):  good link -> stuck count =0
E/WifiStateMachine(  984):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  984):  isHighRSSI       ---> score=61
E/WifiStateMachine(  984): handleMessage: X
D/WifiWatchdogStateMachine(  984): RSSI current: 3 new: -63, 3
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=227
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  984): notifying of data activity 0
,I/Prism.ItemManager( 1615): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1615): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1615): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
D/AccTypeManager( 1766): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  984): Cannot find grip_rejection_width, use default value instead
D/PMS     (  984): acquireWL(1f18076e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6298 10112 null
,D/AccTypeManager( 1766): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,W/ResourcesManager(  984): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1766): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/[PluginManager]RegisterService( 1472): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1472): handle notify Blinkfeed plugin client changed
D/PhoneApp( 1557): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  984): releaseWL(1f18076e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6298): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6298): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ExternalAccountType( 1766): Unsupported attribute readOnly,
,D/PackageBroadcastService( 4417): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4417): Null package name or gms related package.  Ignoreing.,
,D/PMS     (  984): acquireWL(18ca4afc): PARTIAL_WAKE_LOCK  Icing 0x1 4417 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(1b686fda): PARTIAL_WAKE_LOCK  AsyncService 0x1 6034 10167 null
,D/PMS     (  984): releaseWL(1b686fda): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  984): acquireWL(20ef1ae8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6034 10167 null
,I/Icing   ( 4417): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 5871): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,D/PMS     (  984): releaseWL(20ef1ae8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/PMS     (  984): releaseWL(18ca4afc): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/UpdateIcingCorporaServi( 5871): UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] 
,W/PackageManager(  984): Unable to load service info ResolveInfo{28b46b2c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  984): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  984): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  984): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  984): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  984): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  984): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  984): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  984): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  984): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
V/GmsNetworkLocationProvi( 1834): DISABLE
I/GCoreNlp( 1834): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,I/BackupManagerService(  984): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LocationProviderProxy(  984): applying state to connected service
,D/PMS     (  984): acquireWL(31796b4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  984): releaseWL(31796b4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  984): applying state to connected service
,D/PMS     (  984): acquireWL(42e32dd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(f192e52): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): releaseWL(42e32dd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  984): Explicit concurrent mark sweep GC freed 30054(1640KB) AllocSpace objects, 6(248KB) LOS objects, 33% free, 19MB/28MB, paused 1.720ms total 149.381ms,
D/PMS     (  984): releaseWL(f192e52): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(3129e095): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  984): releaseWL(3129e095): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=227
,I/ActivityManager(  984): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6585 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  984): acquireWL(398035aa): PARTIAL_WAKE_LOCK  *alarm* 0x1 984 1000 WorkSource{10076}
V/AlarmManager(  984): sending alarm PendingIntent{376cd59b: PendingIntentRecord{134e5d38 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454950402199, Int=60000
D/PMS     (  984): releaseWL(398035aa): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6585): SMSBackupAgentService started,
D/SMSBackup( 6585): Checking restore status,
,D/SMSBackup( 6585): Restore complete
,D/SMSBackup( 6585): cancelCheckAlarm
,D/SMSBackup( 6585): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/PMS     (  984): acquireWL(2f25d002): PARTIAL_WAKE_LOCK  Icing 0x1 4417 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  984): releaseWL(2f25d002): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(ec39b50): PARTIAL_WAKE_LOCK  Icing 0x1 4417 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): releaseWL(ec39b50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/Prism.ItemManager( 1615): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1615): loadItems() com.htc.launcher.pageview.WidgetManager@3522823 +
I/Prism.WidgetManager( 1615): onLoadItems() +
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=227
,E/Prism.WidgetManager( 1615): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1615): onLoadItems() -
I/Prism.ItemManager( 1615): loadItems() com.htc.launcher.pageview.WidgetManager@3522823 -
,D/PhoneApp( 1557): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1557): -- N1 =0
,D/PhoneApp( 1557): -- N2 =0
,D/PhoneApp( 1557): -- N3 =0
,E/WifiStateMachine(  984): handleMessage: E msg.what=131155,
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1043509286] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
,E/WifiStateMachine(  984):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1043509285] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984):  get link layer stats 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1323): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  984): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  984): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.08 txretriesrate=0.00 rxrate=2.32 userTriggerdPenalty0
E/WifiStateMachine(  984):  good link -> stuck count =0
E/WifiStateMachine(  984):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  984):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  984): RSSI current: 3 new: -63, 3
E/WifiStateMachine(  984): handleMessage: X
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=229
E/WifiTrafficPoller(  984): notifying of data activity 1,
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiDataStallTracker(  984): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  984): updateDataStallInfo: mDataStallTxRxSum={txSum=130 rxSum=116} preTxRxSum={txSum=130 rxSum=116}
D/WifiDataStallTracker(  984): updateDataStallInfo: NONE
D/WifiDataStallTracker(  984): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,E/WifiStateMachine(  984): WiFiStateMachine SCAN ALARM,
D/PMS     (  984): acquireWL(33451905): PARTIAL_WAKE_LOCK  *alarm* 0x1 984 1000 WorkSource{1000}
D/WifiDisplayAdapter(  984): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
,D/WifiDisplayAdapter(  984):     Client/Owner: Client
D/WifiDisplayAdapter(  984):     GroupId: 
D/WifiDisplayAdapter(  984):     Passphrase: 
D/WifiDisplayAdapter(  984):     SessionId: 0
D/WifiDisplayAdapter(  984):     IP Address: }
E/WifiStateMachine(  984): handleMessage: E msg.what=131143
E/WifiStateMachine(  984): processMsg: ConnectedState
V/AlarmManager(  984): sending alarm PendingIntent{107277e5: PendingIntentRecord{16302ba android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454950404536, Int=20000
,E/WifiStateMachine(  984):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:82 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=2.3 list=2412 [on:0 tx:0 rx:0 period:464] from screen [on:0 period:-1043508804]
D/PMS     (  984): releaseWL(33451905): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:82 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=2.3 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1043508803]
,E/WifiStateMachine(  984): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.08 rxSuccessRate=2.32 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-63
E/WifiStateMachine(  984): WifiStateMachine CMD_START_SCAN with age=36230 interval=60000 maxinterval=300000
E/WifiStateMachine(  984): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  984): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  984): has c0:ff:d4:d3:aa:48 freq=2412 age=469 ?=true
E/WifiStateMachine(  984): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1323): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1323): wpa_supplicant_scan enter
,D/wpa_supplicant( 1323): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1323): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1323): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1323): WPS:  * Request Type
D/wpa_supplicant( 1323): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1323): WPS:  * UUID-E
D/wpa_supplicant( 1323): WPS:  * Primary Device Type
D/wpa_supplicant( 1323): WPS:  * RF Bands (3)
D/wpa_supplicant( 1323): WPS:  * Association State
D/wpa_supplicant( 1323): WPS:  * Configuration Error (0)
,D/wpa_supplicant( 1323): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1323): WPS:  * Manufacturer
D/wpa_supplicant( 1323): WPS:  * Model Name
D/wpa_supplicant( 1323): WPS:  * Model Number
D/wpa_supplicant( 1323): WPS:  * Device Name
D/wpa_supplicant( 1323): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1323): P2P: * P2P IE header
D/wpa_supplicant( 1323): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1323): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1323): wlan0: Limit manual scan to specified channels
,D/wpa_supplicant( 1323): wlan0: Add radio work 'scan'@0x5594bc7680
D/wpa_supplicant( 1323): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1323): wlan0: Starting radio work 'scan'@0x5594bc7680 after 0.000041 second wait
D/wpa_supplicant( 1323): wlan0: nl80211: scan request
D/wpa_supplicant( 1323): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1323): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1323): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1323): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1323): wlan0: Own scan request started a scan in 0.000086 seconds
I/wpa_supplicant( 1323): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor(  984): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  984): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  984): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  984): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  984): [1,454,950,404,544 ms] noteScanstart no scan source
E/WifiStateMachine(  984): handleMessage: X
,D/wpa_supplicant( 1323): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1323): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1323): nl80211: Scan included frequencies: 2412,
D/wpa_supplicant( 1323): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1323): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1323): wlan0: Scan completed in 0.081826 seconds,
D/wpa_supplicant( 1323): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1323): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1323): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
,I/wpa_supplicant( 1323): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-53
I/wpa_supplicant( 1323): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
,W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/wpa_supplicant( 1323): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1323): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
D/wpa_supplicant( 1323): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1323): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1323): wlan0: Scan-only results received
D/wpa_supplicant( 1323): wlan0: Radio work 'scan'@0x5594bc7680 done in 0.082728 seconds
,E/WifiMonitor(  984): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  984): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  984): handleMessage: E msg.what=147461
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
,E/WifiStateMachine(  984): processMsg: ConnectModeState
,E/WifiStateMachine(  984):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  984): processMsg: DriverStartedState
E/WifiStateMachine(  984):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  984): processMsg: SupplicantStartedState
E/WifiStateMachine(  984):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1323): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  984): [1,454,950,404,632 ms] noteScanEnd no scan source
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1323): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  984): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@198c7585 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  984): NG7005g c0:ff:d4:d3:aa:4a rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  984): NG700 c0:ff:d4:d3:aa:48 rssi=-63 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  984): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  984): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  984):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-63 freq=2412
E/WifiAutoJoinController (  984): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  984): Gonzos 38:f8:89:11:e9:11 rssi=-75 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  984): ageScanResultsOut delay 40000 size 4 now 1454950404636
E/WifiAutoJoinController (  984): newSupplicantResults size=4 known=1 true
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
,D/wpa_supplicant( 1323): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  984): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  984): ssid=NG700
E/WifiAutoJoinController (  984): id=0
E/WifiAutoJoinController (  984): mode=station
E/WifiAutoJoinController (  984): pairwise_cipher=CCMP
E/WifiAutoJoinController (  984): group_cipher=CCMP
E/WifiAutoJoinController (  984): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  984): wpa_state=COMPLETED
E/WifiAutoJoinController (  984): ip_address=192.168.1.130
E/WifiAutoJoinController (  984): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  984): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  984): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  984): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  984): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-63,-127) num=(1,0)
E/WifiAutoJoinController (  984): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  984): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-63 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  984): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  984): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  984): Done attemptAutoJoin status=0
E/WifiConfigStore(  984):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  984): handleMessage: X
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=230
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=232
,D/Process (  984): killProcessQuiet, pid=5491
I/ActivityManager(  984): Killing 5491:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiStateMachine(  984): handleMessage: E msg.what=131155,
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:2534] from screen [on:0 period:-1043506266] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
,E/WifiStateMachine(  984):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1043506265] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984):  get link layer stats 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1323): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  984): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
,E/WifiStateMachine(  984): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.54 txretriesrate=0.00 rxrate=2.66 userTriggerdPenalty0
E/WifiStateMachine(  984):  good link -> stuck count =0
E/WifiStateMachine(  984):  badRSSI count0 lowRSSI count0 --> score 56
,E/WifiStateMachine(  984):  isHighRSSI       ---> score=61
,I/ActivityManager(  984): Recipient 5491
D/MediaRouterService(  984): Client com.google.android.music (pid 5491): Died!
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=232
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  984): notifying of data activity 0
,E/WifiStateMachine(  984): handleMessage: X
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiWatchdogStateMachine(  984): RSSI current: 3 new: -63, 3
,I/PMS     (  984): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  984): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2459553a,
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  984): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  984): pid=984, uid=1000
D/ActivityManager(  984): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{e95d5a #7 A=.Prism U=0 sz=1}
W/SensorService(  984): Active sensors: size = 4
W/PMS     (  984): mWirelessDisplayManager is null
W/SensorService(  984): Accelerometer Sensor (handle=0x00000000, connections=1)
W/PMN     (  984): goingToSleep
W/SensorService(  984): CM32181 Light sensor (handle=0x00000003, connections=1)
W/PMS     (  984): mWirelessDisplayManager is still null
,W/SensorService(  984): CM36686 Proximity sensor (handle=0x00000004, connections=1)
I/PMS     (  984): Sleeping (uid 1000)...
W/SensorService(  984): Significant Motion (handle=0x0000000d, connections=1)
D/XAN-DPS (  984): prepareColorFade 1
W/SensorService(  984): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2459553a, eanble = 0, strlen(mName) = 91
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  984): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@9582e2a
W/SensorService(  984): Listener[1] = com.htc.smartdim.sensor_eye@30634076
W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  984): acquireWL(b6a5b8b): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 984 1000 null
,W/PMN     (  984): goingToSleep done
,I/FeedHostManager( 1615): [onPause]
I/FeedProviderManager( 1615): onPause
I/FeedHostManager( 1615): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2a585bf6
,I/SocialFeedProvider( 1615): +onPause
,I/SocialFeedProvider( 1615): -onPause
W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/Adreno-EGL(  984): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  984): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  984): Build Date: 03/09/15 Mon
I/Adreno-EGL(  984): Local Branch: 
I/Adreno-EGL(  984): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  984): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  984):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  984): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6609 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/AlarmManager(  984): ACTION_SCREEN_ON,
,I/AlarmManager(  984): [AlarmQueuing] recover blocked alarms
,I/AlarmManager(  984): [AlarmQueuing] done recovering
,I/AlarmManager(  984): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  984): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  984): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  984):  packet count Tx=147 Rx=232
,W/HtcSystemUPManager(  984): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,E/WifiDataStallTracker(  984): ENABLE_DATA_MONITOR_POLL true Token 1
D/PMS     (  984): releaseWL(b6a5b8b): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiStateMachine(  984): handleMessage: E msg.what=131167
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  984): processMsg: ConnectModeState
E/WifiStateMachine(  984):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  984): processMsg: DriverStartedState
E/WifiStateMachine(  984):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  984): processMsg: SupplicantStartedState
E/WifiStateMachine(  984):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  984): processMsg: DefaultState
E/WifiStateMachine(  984):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  984):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1323): SET_SCREEN_ON:On
I/wpa_supplicant( 1323): htc_wext_set_keepalive +
I/wpa_supplicant( 1323): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1323): getPrivFuncNum +	
I/wpa_supplicant( 1323): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1323): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1323): htc_wext_set_keepalive - ret = 0
,I/wpa_supplicant( 1323): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1323): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  984): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  984): backgroundScan enabled=false startBackgroundScanIfNeeded:false,
D/WifiDisplayAdapter(  984): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  984):     Client/Owner: Client
D/WifiDisplayAdapter(  984):     GroupId: 
D/WifiDisplayAdapter(  984):     Passphrase: 
D/WifiDisplayAdapter(  984):     SessionId: 0
D/WifiDisplayAdapter(  984):     IP Address: }
E/WifiStateMachine(  984): handleScreenStateChanged Exit: true
E/WifiStateMachine(  984): handleMessage: X
E/WifiStateMachine(  984): handleMessage: E msg.what=131154
,E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiDataStallTracker(  984): updateDataStallInfo: mDataStallTxRxSum={txSum=130 rxSum=116} preTxRxSum={txSum=130 rxSum=116}
D/WifiDataStallTracker(  984): updateDataStallInfo: NONE
D/WifiDataStallTracker(  984): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,V/SRS_Proc(  435): ParamSet string: screen_state=on
E/audio_a2dp_hw(  435): adev_set_parameters: ERROR: set param called even when stream out is null
I/wpa_supplicant( 1323): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  984): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  984): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  984): handleMessage: X
E/WifiStateMachine(  984): handleMessage: E msg.what=131127
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
,E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  984): processMsg: ConnectModeState
D/WifiController(  984): handleMessage: E msg.what=155650
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
E/WifiStateMachine(  984):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  984): handleMessage: X
E/WifiStateMachine(  984): handleMessage: E msg.what=131129
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  984): processMsg: ConnectModeState
E/WifiStateMachine(  984):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1323): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1323): wlan0: BLACKLIST CLEAR 
E/WifiStateMachine(  984): handleMessage: X
D/WifiMonitor(  984): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  984): WifiMonitor:wlan0 cnt=34 dispatchEvent: BLACKLIST CLEAR 
,D/NetworkPolicy(  984): updateScreenOn: false
,V/NetworkPolicy(  984): updateIfacesLocked()
D/NetworkManagementService(  984): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
D/GpsLocationProvider(  984): receive broadcast intent, action: android.intent.action.SCREEN_ON
,W/ResourcesManager( 6609): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false),
,D/PMS     (  984): acquireWL(10363db2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms},
,I/CalendarProvider2( 6609): Created com.android.providers.calendar.CalendarAlarmManager@3f70a213(com.htc.providers.calendar.HtcCalendarProvider@208fc50)
D/PMS     (  984): acquireWL(1790b103): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  984): prepareColorFade done
,D/XAN-DPS (  984): setBrightness to 0
,D/PMS     (  984): releaseWL(1790b103): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  984): releaseWL(10363db2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/CalendarProvider2( 6609): wait start:true
,I/SensorManager(  984): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@9582e2a
I/DisplayManagerService(  984): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  984): disable: get sensor name = CM32181 Light sensor
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  984): pid=984, uid=1000
W/SensorService(  984): Active sensors: size = 3
,D/AlarmManager(  984): ACTION_SCREEN_OFF
W/SensorService(  984): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  984): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  984): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  984): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@9582e2a, eanble = 0, strlen(mName) = 66
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  984): Listener[0] = com.htc.smartdim.sensor_eye@30634076
W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1312): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1312): [EventService] mbHDMIConnect: false, mCoverOn:false
I/AlarmManager(  984): [AlarmQueuing] screen off now: 
I/AlarmManager(  984): [AlarmQueuing] data connection: true
I/AlarmManager(  984): [AlarmQueuing] wifi connection: true
V/ActivityManager(  984): Display changed displayId=0
,E/WifiTrafficPoller(  984): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  984): stopDataStallAlarm 
,E/WifiDataStallTracker(  984): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  984): handleMessage: E msg.what=131167
E/WifiStateMachine(  984): processMsg: ConnectedState
,E/WifiStateMachine(  984):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
D/WifiDisplayAdapter(  984): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  984):     Client/Owner: Client
D/WifiDisplayAdapter(  984):     GroupId: 
D/WifiDisplayAdapter(  984):     Passphrase: 
D/WifiDisplayAdapter(  984):     SessionId: 0
D/WifiDisplayAdapter(  984):     IP Address: }
E/WifiStateMachine(  984):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  984): processMsg: ConnectModeState
E/WifiStateMachine(  984):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  984): processMsg: DriverStartedState
E/WifiStateMachine(  984):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine(  984): processMsg: SupplicantStartedState
E/WifiStateMachine(  984):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  984): processMsg: DefaultState
E/WifiStateMachine(  984):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  984):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1323): SET_SCREEN_ON:Off
I/wpa_supplicant( 1323): htc_wext_set_keepalive +
I/wpa_supplicant( 1323): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1323): getPrivFuncNum +	
I/wpa_supplicant( 1323): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1323): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1323): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1323): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1323): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  984): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
V/SRS_Proc(  435): ParamSet string: screen_state=off
E/audio_a2dp_hw(  435): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  984): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  984): handleScreenStateChanged Exit: false
E/WifiStateMachine(  984): handleMessage: X
E/WifiStateMachine(  984): handleMessage: E msg.what=131154
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  984): handleMessage: X
,D/NetworkPolicy(  984): updateScreenOn: false
D/WifiController(  984): handleMessage: E msg.what=155651
V/NetworkPolicy(  984): updateIfacesLocked()
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
D/NetworkManagementService(  984): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/CalendarProvider2( 6609): wait end:false
,I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@dba4042, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  984): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  984): pid=1221, uid=10041
W/SensorService(  984): Active sensors: size = 4
W/SensorService(  984): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  984): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  984): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  984): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  984): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@dba4042, eanble = 1, strlen(mName) = 56
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  984): Listener[0] = com.htc.smartdim.sensor_eye@30634076
W/SensorService(  984): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@dba4042
W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  984): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6640 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3,
,D/DotMatrix( 1312): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  984): receive broadcast intent, action: android.intent.action.SCREEN_OFF,
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false),
D/ContactMessageStore( 1557): start background delete task...
D/PMS     (  984): acquireWL(79c4bf1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/ContactMessageStore( 1557): size: 0 , 0
D/ContactMessageStore( 1557): Background delete complete
,D/PMS     (  984): releaseWL(79c4bf1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  984): acquireWL(a15f3d6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): releaseWL(a15f3d6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6640): MY_DEBUG = false,
,D/PMS     (  984): acquireWL(3718b62d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6640 1000 null,
,D/SmartSyncUtils( 6640): isEpsOn(), nState = 0,
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  984): Setting HAL interactive mode to false
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  984): Setting HAL interactive mode to false done
D/SurfaceControl(  984): Excessive delay in setPowerMode(): 282ms
D/PMS     (  984): Setting HAL auto-suspend mode to true
W/HtcSystemUPManager(  984): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  984): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  984): screenObserver, isScreenOn=false
,D/HABCtrl (  984): TPE algorithm. remove timeout.
D/PMS     (  984): OOBE c monitor 11
D/StatusBarManagerService(  984): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  984): Disable input method client, pid=1615
I/InputManager(  984): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  984): acquireWL(10d57762): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(10d57762): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NfcService( 1579): applyRouting - 0
D/HtcPowerSaver(  984): updateBatteryInfo
I/RemoteViews( 1221): apply : com.htc.updater 1 11 0 36
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PMS     (  984): acquireWL(2d0fe0f3): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1579 1027 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/NotificationService(  984): plugged=true pluggin=true
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  984): runPSCheck
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  984): Checking...
D/UsbnetService(  984): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  984): >> updateStatus
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/WifiController(  984): battery changed pluggedType: 2
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  984): releaseWL(2d0fe0f3): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/UsbnetService(  984): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  984): updateStatus (8000,97,-1,false,false,false,-1)
D/WifiController(  984): handleMessage: E msg.what=155652
I/HtcPowerSaver(  984): << updateStatus
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
D/NfcService( 1579): applyRouting -2
D/NfcService( 1579): applyRouting
D/NfcService( 1579): Ignore this applyRouting...
D/NfcService( 1579): ScreenObserver: OFF
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,D/PowerUI ( 1221): closing low battery warning: level=97
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  984): Init customizeScreenOffDelayClass error
,D/PMS     (  984): releaseWL(3718b62d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6640): isEpsOn(), nState = 0
I/ClockController( 1221): stop clock update:screen off
I/BatteryController( 1221): status:2 level:97 unsupport:false plugged:true
D/SmartSyncUtils( 6640): isEpsOn(), nState = 0
W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  984): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@30634076,
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  984): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  984): pid=984, uid=1000,
W/SensorService(  984): Active sensors: size = 3
W/SensorService(  984): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  984): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  984): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  984): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@30634076, eanble = 0, strlen(mName) = 36
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  984): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@dba4042
W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  984): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  984): pid=984, uid=1000
,W/SensorService(  984): Active sensors: size = 2
W/SensorService(  984): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  984): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  984): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@30634076, eanble = 0, strlen(mName) = 36
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  984): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@dba4042
,W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  984): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@30634076
,E/ActivityThread(  984): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@292a9677 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  984): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@292a9677 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  984): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  984): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  984): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  984): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  984): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  984): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  984): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  984): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  984): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  984): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  984): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  984): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  984): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  984): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  984): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  984): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  984): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  984): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6673 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/PowerUsageList:PowerUsageHelper( 6640): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6640): gen(), null == sipper.uidObj, userId = 0,
,I/ActivityManager(  984): Killing 6005:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  984): killProcessQuiet, pid=6005
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6640): getMobilePolicyEnabled, result = true,
,D/WifiService(  984): New client listening to asynchronous messages
E/WifiTrafficPoller(  984): ADD_CLIENT: 7
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL false Token 13 num clients 7
,I/ActivityManager(  984): Recipient 6005,
,D/PowerUsageList:PowerUsageHelper( 6640): MY_DEBUG = false,
,D/Process (  984): killProcessQuiet, pid=5791
I/ActivityManager(  984): Killing 5791:com.google.android.gm/u0a106 (adj 15): empty #17
,D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  984): Recipient 5791
,E/WifiTrafficPoller(  984): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,I/CalendarProvider2( 6609): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6609): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 6362): ---------------------------------------------------,
D/ProviderChangeReceiver( 6362): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  984): killProcessQuiet, pid=6327,
I/ActivityManager(  984): Killing 6327:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6362): start to updateAlertNotification!
,I/ActivityManager(  984): Recipient 6327
,D/HtcAlertService( 6362): No fired or scheduled alerts
,D/HtcAlertUtils( 6362): -- cancelReminderNotification --
,D/HtcAlertUtils( 6362): broadcastExistReminder!
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  984): releaseWL(51564c8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,E/WifiDataStallTracker(  984): DATA_MONITOR_POLL false Token 3
,E/WifiStateMachine(  984): handleMessage: E msg.what=131155
E/WifiStateMachine(  984): processMsg: ConnectedState
E/WifiStateMachine(  984):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2876] from screen [on:0 period:-1043503247] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1043503244] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984): handleMessage: X
,E/WifiStateMachine(  984): handleMessage: E msg.what=131155
E/WifiStateMachine(  984): processMsg: ConnectedState
,E/WifiStateMachine(  984):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:388] from screen [on:0 period:-1043502855] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  984): processMsg: L2ConnectedState
E/WifiStateMachine(  984):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1043502852] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  984): handleMessage: X
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  984): DATA_MONITOR_POLL false Token 3,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/ContactMessageStore( 1557): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1557): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  984): Killing 5590:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
D/Process (  984): killProcessQuiet, pid=5590
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  984): Recipient 5590,
,D/PMS     (  984): acquireWL(317a7ae): PARTIAL_WAKE_LOCK  *alarm* 0x1 984 1000 WorkSource{10024},
V/AlarmManager(  984): sending alarm PendingIntent{24bd994f: PendingIntentRecord{b8a88dc com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142735, Int=0
,D/PMS     (  984): releaseWL(317a7ae): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  984): acquireWL(15d77de5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  984): n_update end
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  984): releaseWL(15d77de5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/NotificationService(  984): plugged=true pluggin=true
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  984): battery changed pluggedType: 2
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=97
D/WifiController(  984): handleMessage: E msg.what=155652
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
,D/HtcPowerSaver(  984): updateBatteryInfo
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1221): status:2 level:97 unsupport:false plugged:true,
,D/GpsLocationProvider(  984): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  984): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  984): acquireWL(393a90ba): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 984 1000 null
,D/libc    (  984): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  984): [NET] android_getaddrinfofornet-, err=8
D/libc    (  984): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  984): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    (  984): [NET] android_getaddrinfo_proxy+
D/libc    (  984): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  984): [NET] android_getaddrinfo_proxy-, success
D/libc    (  984): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  984): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  984): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  984): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  984): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  984):  [handleDownloadXtraData]inject done.
D/PMS     (  984): acquireWL(170fe86): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 984 1000 null
D/PMS     (  984): releaseWL(393a90ba): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/GpsLocationProvider(  984): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  984): releaseWL(170fe86): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1557): switchBindHtcMsgCursor: null
,D/PMS     (  984): acquireWL(2c4d6347): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 984 1000 WorkSource{1000}
V/AlarmManager(  984): sending alarm PendingIntent{ec5a391: PendingIntentRecord{152302f6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=144861, Int=0
V/AlarmManager(  984): sending alarm PendingIntent{11d1774: PendingIntentRecord{2e40849d android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454950461985, Int=0
V/AlarmManager(  984): sending alarm PendingIntent{84e7d12: PendingIntentRecord{172ece3 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=197761, Int=0
V/AlarmManager(  984): sending alarm PendingIntent{3cae36e0: PendingIntentRecord{3c25cd99 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191746, Int=0
D/PMS     (  984): acquireWL(3e13585e): PARTIAL_WAKE_LOCK  *backup* 0x1 984 1000 null
,D/PMS     (  984): acquireWL(9dd743f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  984): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  984): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  984): releaseWL(3e13585e): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  984): releaseWL(2c4d6347): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  984): acquireWL(146fe10c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  984): releaseWL(9dd743f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1859): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1859): Explicit concurrent mark sweep GC freed 13597(740KB) AllocSpace objects, 5(420KB) LOS objects, 48% free, 4MB/8MB, paused 1.017ms total 69.246ms,
,D/PMS     (  984): releaseWL(146fe10c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(32bc1536): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  984): releaseWL(32bc1536): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(64fac37): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  984): releaseWL(64fac37): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(1fef45a4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(f0cf0d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  984): acquireWL(3368d4d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  984): releaseWL(1fef45a4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1859): Vacuum at: now=1454950493242 tag=VacuumService,
,I/GoogleURLConnFactory( 1859): Using platform SSLCertificateSocketFactory,
,D/PMS     (  984): releaseWL(f0cf0d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(d684f09): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1859): No account for auth token provided,
,D/PMS     (  984): releaseWL(d684f09): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(2774950e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): releaseWL(2774950e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1859): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1859): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1859): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1859): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1859): [NET] android_getaddrinfo_proxy+
D/libc    ( 1859): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1859): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1859): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1859): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1859): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1859): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1859): No account for auth token provided,
,W/Uploader( 1859): No account for auth token provided,
,W/Uploader( 1859):  no longer exists, so no auth token.
,W/Uploader( 1859): No account for auth token provided,
,I/GLSUser ( 1859): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1859): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1859): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1859): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1859): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,E/Uploader( 1859): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1859): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1859): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1859): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1859): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1859): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1859): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1859): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1859): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1859): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1859): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1859): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
,E/Uploader( 1859): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  984): releaseWL(3368d4d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  984): acquireWL(2b6098c3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): releaseWL(2b6098c3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(107ea540): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1859 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  984): releaseWL(107ea540): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  984): acquireWL(2bc60c79): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null,
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(2bc60c79): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo
D/NotificationService(  984): plugged=true pluggin=true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=98
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  984): updateStatus (8000,98,-1,false,false,false,-1)
,D/UsbnetService(  984): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  984): << updateStatus
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  984): battery changed pluggedType: 2
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/WifiController(  984): handleMessage: E msg.what=155652
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState,
D/WifiController(  984): handleMessage: X
,I/BatteryController( 1221): status:2 level:98 unsupport:false plugged:true,
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1472): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@25c4d1a,
I/ActivityManager(  984): Killing 5435:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  984): killProcessQuiet, pid=5435
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  984): Recipient 5435
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1323): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/WifiMonitor(  984): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  984): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1323): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  984): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  984): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,D/wpa_supplicant( 1323): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  984): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  984): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  984): acquireWL(19b65dbe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(19b65dbe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  984): plugged=true pluggin=true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=98
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  984): updateBatteryInfo
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/PMS     (  984): runPSCheck
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  984): Checking...
D/UsbnetService(  984): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  984): >> updateStatus
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  984): battery changed pluggedType: 2
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  984): handleMessage: E msg.what=155652
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
,I/HtcPowerSaver(  984): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1221): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  984): acquireWL(229fe1f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 984 1000 WorkSource{1000}
V/AlarmManager(  984): sending alarm PendingIntent{ec5a391: PendingIntentRecord{152302f6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=204862, Int=0
,V/AlarmManager(  984): sending alarm PendingIntent{791f735: PendingIntentRecord{1a7697ca com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454950636276, Int=0
,I/ActivityManager(  984): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6709 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  984): sending alarm PendingIntent{16fa5d3b: PendingIntentRecord{27a3dc58 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454950644359, Int=0,
,D/PMS     (  984): releaseWL(229fe1f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data,
,E/cutils-trace( 6730): Error opening trace file: Permission denied (13),
I/dex2oat ( 6730): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,I/dex2oat ( 6730): dex2oat: override thread count:4,
,I/dex2oat ( 6730): dex2oat took 677.757ms (threads: 4)
,I/PushClient( 6709): ApplicationMonitor {2f153605}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6709): ApplicationMonitor {2f153605}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6709): ApplicationMonitor {2f153605}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6709): ApplicationMonitor {2f153605}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6709): ApplicationMonitor {2f153605}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6709): ApplicationMonitor {2f153605}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6709): ApplicationMonitor {2f153605}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6709): ApplicationMonitor {2f153605}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6709): ApplicationMonitor {2f153605}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6709): PnsModel {38098d7c}: update(): Update registration caused by: alarm
,I/PushClient( 6709): PnsConfigModel {30963603}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6709): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6709): SLF4J: Defaulting to no-operation (NOP) logger implementation,
W/System.err( 6709): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6709): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  984): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6738 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6738): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6738 dbg=false s=true
,I/DeviceManagement( 6738): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6738): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6738): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6738): WorkflowService: Starting workflow service
,I/DeviceManagement( 6738): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@38098d7c] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6738): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6738): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6738): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6738): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6738): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6738): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6738): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6738): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@38098d7c],
,I/DeviceManagement( 6738): WorkflowService: Stopping workflow service,
,I/ActivityManager(  984): Killing 6444:com.test.thalitest/u0a366 (adj 15): empty #17,
D/Process (  984): killProcessQuiet, pid=6444
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6709): PnsModel {38098d7c}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  984): Recipient 6444
,E/InputEventReceiver( 1404): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{3462ca4f uid 10366 pid 6444} (c)'
,D/Process (  984): killProcessQuiet, pid=6546,
I/ActivityManager(  984): Killing 6546:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  984): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  984): Recipient 6546,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1859): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1859): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1859): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1859): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1859): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1859): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1859): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1859): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1859): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1859): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1859): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1859): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1859): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5962): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5962): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5962): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5962): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5962): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5962): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5962): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5962): Ignoring header User-Agent because its value was null.
,D/libc    ( 5962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5962): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5962): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5962): [NET] android_getaddrinfo_proxy+
D/libc    ( 5962): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5962): [NET] android_getaddrinfo_proxy-, success
,I/art     (  984): Explicit concurrent mark sweep GC freed 40001(2MB) AllocSpace objects, 6(1208KB) LOS objects, 33% free, 18MB/28MB, paused 2.738ms total 232.530ms,
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,D/PMS     (  984): acquireWL(1a87931e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null,
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(1a87931e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/NotificationService(  984): plugged=true pluggin=true
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/WifiController(  984): battery changed pluggedType: 2
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/WifiController(  984): handleMessage: E msg.what=155652
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=99
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  984): updateBatteryInfo
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
D/PMS     (  984): acquireWL(1c0f7ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null
D/HeadsetPhoneState( 3098): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/BatteryService(  984): n_update end
D/HeadsetStateMachine( 3098): Disconnected process message: 11, size: 0
D/PMS     (  984): releaseWL(1c0f7ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/NotificationService(  984): plugged=true pluggin=true
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/WifiController(  984): battery changed pluggedType: 2
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  984): updateBatteryInfo
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderNotification, total:0
D/PMS     (  984): runPSCheck
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  984): Checking...
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  984): >> updateStatus
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WifiController(  984): handleMessage: E msg.what=155652
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,D/TetherSettings( 5938): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5938): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5938): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5938): Cust_ConnectToPC   : spcsc>false
D/        ( 5938): Cust_ConnectToPC   : IPT>true
D/        ( 5938): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 5938): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5938): Index of the first 1 = -1
W/ContextImpl( 5938): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5938): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 ,
,W/Settings( 5938): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SmartNS_Utility( 5938): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5938): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5938): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/SmartNS_Utility( 5938): [ACC]android_networking:tethering_guard_support=false
W/SystemReader( 5938): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  984): acquireWL(e8f3415): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(e8f3415): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  984): updateBatteryInfo
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  984): plugged=true pluggin=true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  984): runPSCheck
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  984): Checking...
D/UsbnetService(  984): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  984): >> updateStatus
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/WifiController(  984): battery changed pluggedType: 2
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  984): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  984): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  984): processMsg: DeviceActiveState
I/HtcPowerSaver(  984): << updateStatus
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
,D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/ContactMessageStore( 1557): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1557): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1557): sku_id=118,
D/ContactMessageStore( 1557): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1557): start background delete task...
,D/ContactMessageStore( 1557): size: 0 , 0
,D/ContactMessageStore( 1557): Background delete complete
,D/PMS     (  984): acquireWL(3215c32a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(3215c32a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo
,D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  984): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  984): << updateStatus
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/NotificationService(  984): plugged=true pluggin=true
D/WifiController(  984): handleMessage: E msg.what=155652
,D/WifiController(  984): battery changed pluggedType: 2
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  984): acquireWL(1137151b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 984 1000 WorkSource{1000}
I/bt-btm  ( 3098): Received oneshot timer event complete
,V/AlarmManager(  984): sending alarm PendingIntent{ec5a391: PendingIntentRecord{152302f6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=384862, Int=0
I/bt-btm  ( 3098): btm_ble_timeout
I/bt-btm  ( 3098): btm_gen_resolvable_private_addr
D/PMS     (  984): acquireWL(ac466b8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3098 1002 null
V/AlarmManager(  984): sending alarm PendingIntent{173bfc91: PendingIntentRecord{14a4e7f6 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940812, Int=0
,D/bt-btm  ( 3098): btm_ble_rand_enc_complete
I/bt-btm  ( 3098): btm_gen_resolve_paddr_low
D/bt-smp  ( 3098): smp_encrypt_data
,W/bt-smp  ( 3098): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3098): Plain text(LSB ~ MSB) = 71 5d 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3098): Encrypted text(LSB ~ MSB) = 83 ea 29 3e 34 4b 2b 5a 66 eb 27 4f 97 fb a0 fa 
I/bt-btm  ( 3098): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3098): Stopping oneshot timer
D/bt-btm  ( 3098): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  984): releaseWL(1137151b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  984): releaseWL(ac466b8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  984): acquireWL(2727e7f7): PARTIAL_WAKE_LOCK  *alarm* 0x1 984 1000 WorkSource{10024}
V/AlarmManager(  984): sending alarm PendingIntent{34b53664: PendingIntentRecord{1d12d0cd com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=934452, Int=0
D/PMS     (  984): acquireWL(282f8d82): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1859 10024 WorkSource{10024 com.google.android.gms}
,V/AlarmManager(  984): sending alarm PendingIntent{1d8b3776: PendingIntentRecord{1a70c177 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805521, Int=0
,D/PMS     (  984): releaseWL(282f8d82): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  984): sending alarm PendingIntent{de90c93: PendingIntentRecord{256c5aca com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454951263645, Int=0,
,W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  984): releaseWL(2727e7f7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6640): MY_DEBUG = false,
,D/PowerUsageService( 6640): repeat time = 1454952163691,
,I/PowerUsageList:PowerUsageHelper( 6640): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6640): gen(), null == sipper.uidObj, userId = 0,
,D/GCM     ( 1859): Message class com.google.f.a.a.i
D/PMS     (  984): acquireWL(1508acc9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1859 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): releaseWL(1508acc9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  984): acquireWL(5ccffce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(5ccffce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  984): updateBatteryInfo
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/NotificationService(  984): plugged=true pluggin=true
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  984): runPSCheck
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): Checking...
D/WifiController(  984): handleMessage: E msg.what=155652
I/HtcPowerSaver(  984): >> updateStatus
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): battery changed pluggedType: 2
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  984): acquireWL(158ddeef): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 984 1000 WorkSource{1000}
V/AlarmManager(  984): sending alarm PendingIntent{ec5a391: PendingIntentRecord{152302f6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=984861, Int=0
V/AlarmManager(  984): sending alarm PendingIntent{32eedfc: PendingIntentRecord{34664c85 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454951307991, Int=0
,D/SmartSyncUtils( 6640): isEpsOn(), nState = 0
,D/PMS     (  984): acquireWL(2ebd4ada): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6640 1000 null
,D/PMS     (  984): releaseWL(158ddeef): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6640): [updateNmRange] bManual = false
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6640): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6640): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6640): SettingOnTime = 1454997600000, randomSettingOnTime = 1454996952000
D/SmartSyncScreenOnOffTimeReceiver( 6640): SettingOffTime = 1454976000000, randomSettingOffTime = 1454980742000
,D/SmartSyncScreenOnOffTimeReceiver( 6640): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6640): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6640): bNightModeTurnOffOnce = false
,D/PMS     (  984): releaseWL(2ebd4ada): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  984): acquireWL(12037b0b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 984 1000 null
,I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(12037b0b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo,
D/NotificationService(  984): plugged=true pluggin=true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  984): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  984): << updateStatus
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  984): battery changed pluggedType: 2
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/WifiController(  984): handleMessage: E msg.what=155652
D/WifiController(  984): processMsg: DeviceActiveState
D/WifiController(  984): processMsg: StaEnabledState
D/WifiController(  984): processMsg: DefaultState
D/WifiController(  984): handleMessage: X
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  984): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
