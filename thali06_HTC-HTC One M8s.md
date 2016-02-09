#### Test 58380500306a2c5_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  946): handleMessage: E msg.what=131155
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-935694681] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-935694680] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1322): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.26 txretriesrate=0.00 rxrate=0.86 userTriggerdPenalty0
E/WifiStateMachine(  946):  good link -> stuck count =0
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  946):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  946): handleMessage: X
--------- beginning of system
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/cutils-trace( 6416): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6416): ====startRecUseTime====
D/htc.customization.log.level( 6416):  is 
W/CustomizationLogLevel( 6416): Level value is invalid, use default level 2
D/CustomizationManager( 6416):  Read ACC file spent 0.045 (s)
D/CIDMapFileReader( 6416): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6416): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6416): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6416): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6416): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6416): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6416): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6416): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6416): Parsing tag category name = system
I/CustomizationCIDLoader( 6416): Parsing tag category name = application
I/CustomizationCIDLoader( 6416): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6416): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6416): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6416): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6416): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6416): add string-array item, value = 42507
I/CustomizationCIDLoader( 6416): add string-array item, value = 21902
I/CustomizationCIDLoader( 6416): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6416): add string-array item, value = 23420
I/CustomizationCIDLoader( 6416): add string-array item, value = 22299
I/CustomizationCIDLoader( 6416): add string-array item, value = 24002
I/CustomizationCIDLoader( 6416): add string-array item, value = 23210
I/CustomizationCIDLoader( 6416): add string-array item, value = 23205
I/CustomizationCIDLoader( 6416): add string-array item, value = 23806
I/CustomizationCIDLoader( 6416): add string-array item, value = 23430
I/CustomizationCIDLoader( 6416): add string-array item, value = 23408
I/CustomizationCIDLoader( 6416): add string-array item, value = 27205
I/CustomizationCIDLoader( 6416): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6416): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6416):  Read CID file spent 0.095 (s)
D/CustomizationManager( 6416):  All configurations done spent 0.095 (s)
D/PMS     (  946): acquireHCC(20751c11): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 946 1000 null
I/ActivityManager(  946): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6416 on display 0
D/PMS     (  946): acquireHCC(6905176): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 946 1000 null
D/PMS     (  946): acquireWL(d7e684d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 946 1000 null
I/FeedHostManager( 1627): [onPause]
I/FeedProviderManager( 1627): onPause
I/FeedHostManager( 1627): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2d57f1bf
I/AnimationUtil(  946): isHTCRecent(ThaliTest/Recent screens.)/6
I/SocialFeedProvider( 1627): +onPause
I/SocialFeedProvider( 1627): -onPause
W/HtcSystemUPManager(  946): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  946): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6434 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/WifiDataStallTracker(  946): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  946): updateDataStallInfo: mDataStallTxRxSum={txSum=112 rxSum=100} preTxRxSum={txSum=112 rxSum=100}
D/WifiDataStallTracker(  946): updateDataStallInfo: NONE
D/WifiDataStallTracker(  946): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/TrimMemoryManager( 1627): [trimMemory] 20
D/StatusBarManagerService(  946): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  946): hiding MENU key
E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  946):  packet count Tx=129 Rx=219
,I/WebViewFactory( 6434): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6434): Time to load native libraries: 9 ms (timestamps 4861-4870)
I/LibraryLoader( 6434): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6434): Binding Chromium to main looper Looper (main, tid 1) {6554261}
I/LibraryLoader( 6434): Expected native library version number "",actual native library version number ""
I/chromium( 6434): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6434): Initializing chromium process, singleProcess=true
W/art     ( 6434): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6434): ApplicationContext is null in ApplicationStatus
W/chromium( 6434): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6434): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6434): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6434): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6434): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6434): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6434): Local Branch: 
I/Adreno-EGL( 6434): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6434): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6434):                  d74aa161a12b9c6fc6332151
W/System.err(  946): java.lang.Throwable: stack dump
D/BluetoothManagerService(  946): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  946): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc63cb2:true
W/System.err(  946): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  946): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  946): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  946): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6434): 172139421: getState(). Returning 12
W/art     ( 6434): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6434): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6434): CordovaWebView is running on device made by: HTC
W/art     ( 6434): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6434): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6434): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6434): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6434): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@13841c2, mServedView=org.apache.cordova.engine.SystemWebView{7094bd3 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@c41c310
I/InputMethodManagerService(  946): Disable input method client, pid=1627
D/StatusBarManagerService(  946): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  946): Enable input method client, pid=6434
I/ActivityManager(  946): Displayed com.test.thalitest/.MainActivity: +814ms
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/PMS     (  946): releaseWL(d7e684d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/XT9_C   ( 1399): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1399): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1399): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1399): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6434): Cannot call determinedVisibility() - never saw a connection for the pid: 6434
I/HtcModeClient( 3229): handler message = 4011
E/HtcModeClient( 3229): Check connection and retry 11 times.
,D/JsMessageQueue( 6434): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6434): JniHelper::setJavaVM(0xab3538f8), pthread_self() = -1402567640
E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  946):  packet count Tx=129 Rx=220
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  946): notifying of data activity 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/chromium( 6434): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  946): releaseHCC(20751c11): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  946): releaseHCC(6905176): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6434): Initializing JXcore engine
W/jxcore-log( 6434): JXcore engine is ready
,W/jxcore-log( 6434): Starting JXcore engine
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  946):  packet count Tx=129 Rx=220
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  946): notifying of data activity 0
,W/jxcore-log( 6434): Platform android,
W/jxcore-log( 6434): 
W/jxcore-log( 6434): Process ARCH arm
W/jxcore-log( 6434): 
,D/PMS     (  946): acquireWL(10c82e6b): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{10072}
,V/AlarmManager(  946): sending alarm PendingIntent{35228dc8: PendingIntentRecord{17997e61 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455058216433, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{30e28d86: PendingIntentRecord{13394647 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455058221533, Int=536832000
V/CheckinService( 4451): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
V/AlarmManager(  946): sending alarm PendingIntent{14dfabce: PendingIntentRecord{38e91aef android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455058214449, Int=20000
,D/PMS     (  946): acquireWL(4b6be74): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4451 10024 WorkSource{10024 com.google.android.gms},
E/WifiStateMachine(  946): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
,E/WifiStateMachine(  946): handleMessage: E msg.what=131143
D/PMS     (  946): releaseWL(10c82e6b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:222 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 list=2412 [on:0 tx:0 rx:0 period:2871] from screen [on:0 period:-935691791]
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:222 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-935691790]
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.26 rxSuccessRate=0.86 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN with age=59049 interval=60000 maxinterval=300000
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  946): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  946): has c0:ff:d4:d3:aa:48 freq=2412 age=2876 ?=true
E/WifiStateMachine(  946): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
,D/wpa_supplicant( 1322): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1322): wpa_supplicant_scan enter
D/wpa_supplicant( 1322): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1322): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1322): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1322): WPS:  * Request Type
D/wpa_supplicant( 1322): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1322): WPS:  * UUID-E
D/wpa_supplicant( 1322): WPS:  * Primary Device Type
D/wpa_supplicant( 1322): WPS:  * RF Bands (3)
D/wpa_supplicant( 1322): WPS:  * Association State
D/wpa_supplicant( 1322): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1322): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1322): WPS:  * Manufacturer
D/wpa_supplicant( 1322): WPS:  * Model Name
D/wpa_supplicant( 1322): WPS:  * Model Number
D/wpa_supplicant( 1322): WPS:  * Device Name
D/wpa_supplicant( 1322): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1322): P2P: * P2P IE header
D/wpa_supplicant( 1322): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1322): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1322): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1322): wlan0: Add radio work 'scan'@0x55b0f12aa0
D/wpa_supplicant( 1322): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1322): wlan0: Starting radio work 'scan'@0x55b0f12aa0 after 0.000055 second wait
D/wpa_supplicant( 1322): wlan0: nl80211: scan request
D/wpa_supplicant( 1322): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1322): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1322): wlan0: Event SCAN_STARTED (49) received
,D/wpa_supplicant( 1322): wlan0: Own scan request started a scan in 0.000094 seconds
I/wpa_supplicant( 1322): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  946): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  946): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  946): [1,455,058,221,556 ms] noteScanstart no scan source
E/WifiStateMachine(  946): handleMessage: X
,D/PMS     (  946): acquireWL(1ec9fc12): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4451 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(4b6be74): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4451): Checking schedule, now: 1455058221591 next: 1455058221533
,I/CheckinService( 4451): active receiver: enabled
I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4451, uid=10024, userID:0
,I/CheckinService( 4451): Preparing to send checkin request
,I/EventLogService( 4451): Accumulating logs since 1455058186278
,I/CheckinRequestBuilder( 4451): Checkin reason type: 11 attempt count: 1
,I/ActivityManager(  946): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4451): Failed to find provider info for com.google.android.wearable.settings
D/wpa_supplicant( 1322): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1322): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1322): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1322): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1322): wlan0: Scan completed in 0.076944 seconds
D/wpa_supplicant( 1322): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1322): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1322): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1322): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1322): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1322): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-85
I/wpa_supplicant( 1322): [NULL] 34:36:3b:bd:89:28 freq=2462 level=-89
D/wpa_supplicant( 1322): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1322): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to no match in scan
D/wpa_supplicant( 1322): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1322): wlan0: Scan-only results received
D/wpa_supplicant( 1322): wlan0: Radio work 'scan'@0x55b0f12aa0 done in 0.077825 seconds
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  946): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  946): handleMessage: E msg.what=147461
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
D/WifiStateMachine(  946): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1322): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  946): [1,455,058,221,639 ms] noteScanEnd no scan source
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1322): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  946): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2bfd2992 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  946): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  946): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  946): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  946): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  946):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  946): UPC503894600 a0:c5:62:7a:49:97 rssi=-85 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  946): andilabs 34:36:3b:bd:89:28 rssi=-89 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  946): ageScanResultsOut delay 40000 size 5 now 1455058221641
E/WifiAutoJoinController (  946): newSupplicantResults size=5 known=1 true
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1322): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  946): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  946): ssid=NG700
E/WifiAutoJoinController (  946): id=0
E/WifiAutoJoinController (  946): mode=station
E/WifiAutoJoinController (  946): pairwise_cipher=CCMP
E/WifiAutoJoinController (  946): group_cipher=CCMP
E/WifiAutoJoinController (  946): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  946): wpa_state=COMPLETED
E/WifiAutoJoinController (  946): ip_address=192.168.1.130
E/WifiAutoJoinController (  946): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  946): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  946): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  946): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  946): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  946): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  946): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  946): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  946): Done attemptAutoJoin status=0
E/WifiConfigStore(  946):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  946): handleMessage: X
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:124] from screen [on:0 period:-935691663] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
,E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-935691662] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL',
,I/wpa_supplicant( 1322): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.13 txretriesrate=0.00 rxrate=0.93 userTriggerdPenalty0
E/WifiStateMachine(  946):  good link -> stuck count =0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  946):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  946): handleMessage: X
,I/GLSUser ( 1855): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1855): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1855): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1855): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6434): JXcore Cordova bridge is ready!,
I/jxcore-log( 6434): 
W/jxcore-log( 6434): JXcore engine is started
,D/Finsky  ( 5922): [592] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5922): [1] 5.onFinished: Installation state replication succeeded.
,I/art     (  946): Explicit concurrent mark sweep GC freed 26513(1358KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 1.539ms total 155.809ms,
,W/CheckinRequestBuilder( 4451): awaiting user notification for token,
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 2 40,
,I/ActivityManager(  946): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6489 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 6489): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6489): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,I/MultiDex( 6489): VM with version 2.1.0 has multidex support,
I/MultiDex( 6489): install
I/MultiDex( 6489): VM has multidex support, MultiDex support library is disabled.
,I/jxcore-log( 6434): Toggling radios to true,
I/jxcore-log( 6434): 
,D/BluetoothAdapter( 6434): enable(): BT is already enabled..!,
,D/WifiManager( 6434): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366,
D/WifiService(  946): New client listening to asynchronous messages
E/WifiTrafficPoller(  946): ADD_CLIENT: 7
D/WifiService(  946): setWifiEnabled: true pid=6434, uid=10366
W/Settings:Agent(  946): MONITOR_LOG
E/WifiService(  946): Invoking mWifiStateMachine.setWifiEnabled,
W/Settings:Agent(  946): name: wifi_on
I/WifiService(  946): isSprintWifiRestricted(): false
W/Settings:Agent(  946): value: 2
I/WifiService(  946): isMdmWifiRestricted(): false
W/Settings:Agent(  946): >> traceCallingStack(),
W/Settings:Agent(  946): Process.myPid(): 946
W/Settings:Agent(  946): Process.myTid(): 973
W/Settings:Agent(  946): Process.myUid(): 1000
W/Settings:Agent(  946): 
W/Settings:Agent(  946): ,
W/System.err(  946): java.lang.Throwable: stack dump
,V/JNIHelp ( 6489): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System.err(  946): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  946): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  946): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  946): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  946): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  946): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  946): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  946): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  946): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  946): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
,W/System.err(  946): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  946): 
W/Settings:Agent(  946): << traceCallingStack(): 16(ms)
D/WifiController(  946): handleMessage: E msg.what=155656
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiManager( 6434): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131145
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
,E/WifiStateMachine(  946):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1322): wlan0: Cancelling scan request
D/wpa_supplicant( 1322): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/WifiManager( 6434): reconnect: Base Package Name=com.test.thalitest, uid=10366
D/wpa_supplicant( 1322): TDLS: Tear down peers
D/wpa_supplicant( 1322): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 6434): Radios toggled
I/jxcore-log( 6434): 
,I/jxcore-log( 6434): My device name is: HTC-HTC One M8s
I/jxcore-log( 6434): 
,W/ActivityThread( 6489): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6489): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d83c922: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6489): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1855): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/wpa_supplicant( 1322): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1322): wlan0: Deauthentication notification
D/wpa_supplicant( 1322): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1322): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1322): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1322): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1322): enter disconnect check
,I/wpa_supplicant( 1322): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412],
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,E/WifiMonitor(  946): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  946): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  946): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1322): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1322): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  946): interfaceLinkStateChanged wlan0, false
D/UsbDeviceManager(  946): [USBNET] bCheckSuppFunc: cdc_network
D/AuthorizationBluetoothService( 1855): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/PMS     (  946): acquireWL(2e858dc2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 946 1000 null
D/Tethering(  946): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  946): interfaceLinkStateChanged wlan0, false
D/Tethering(  946): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/Tethering(  946): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  946): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  946): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1322): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1322): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1322): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1322): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1322): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55b0f2ff88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1322):    addr=c0:ff:d4:d3:aa:48
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
D/wpa_supplicant( 1322): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1322): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1322): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  946): sendTetherStateChangedBroadcast 0, 0, 0
D/wpa_supplicant( 1322): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1322): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1322): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1322): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1322): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1322): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1322): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1322): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1322): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1322): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1322): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1322): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1322): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1322): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1322): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1322): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1322): nl80211: Ignore disconnect event triggered during reassociation
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/UsbnetService(  946): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  946): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  946): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  946): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  946): handleMessage: new destination call exit/enter
E/WifiStateMachine(  946): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  946): invokeExitMethods: ConnectedState
E/WifiStateMachine(  946): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  946): release()
E/WifiStateMachine(  946): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  946): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  946): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  946): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  946): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  946): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  946): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1322): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1322): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1322): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  946): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1322): Power_Mode_Type mode = 0
I/wpa_supplicant( 1322): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  946): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  946): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1322): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  946): setDhcpActive: false
V/GmsCoreStatsServiceLauncher( 4451): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/NativeCrypto( 1855): Read error: ssl=0x55aaf93940: I/O error during system call, Connection timed out
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  946): acquireWL(261aa7d3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  946): releaseWL(2e858dc2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  946): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
V/NetworkPolicy(  946): updateNetworkEnabledLocked()
E/WifiStateMachine(  946): setDetailed state send new extra info<unknown ssid>
V/NetworkPolicy(  946): updateNotificationsLocked()
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  946): NetworkAgent != null
D/ConnectivityService(  946): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL true Token 11
V/NativeCrypto( 1855): SSL shutdown failed: ssl=0x55aaf93940: I/O error during system call, Broken pipe
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
V/NetworkPolicy(  946): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  946): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  946): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  946): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/ConnectivityService(  946): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1322): wlan0: Control interface command 'SAVE_CONFIG'
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1322): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1322): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1322): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  946): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  946): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  946): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  946):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  946): Start Disconnecting Watchdog 1
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131146
E/WifiStateMachine(  946): processMsg: DisconnectingState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1322): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1322): wlan0: Selecting BSS from priority group 670
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): Forcing reevaluation
D/wpa_supplicant( 1322): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-52 wps
D/wpa_supplicant( 1322): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1322): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1322): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-60 wps
D/wpa_supplicant( 1322): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x43,1
D/wpa_supplicant( 1322): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1322): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1322):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1322): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1322): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x55b0f31c00  current_ssid=0x0
D/wpa_supplicant( 1322): wlan0: Request association with c0:ff:d4:d3:aa:48
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): Validated
D/wpa_supplicant( 1322): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1322): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1322): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1322): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1322): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1322): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1322): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1322): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
D/wpa_supplicant( 1322): TDLS: TDLS is allowed in the target BSS
D/PMS     (  946): releaseWL(261aa7d3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1322): wlan0: Add radio work 'connect'@0x55b0f12aa0
D/wpa_supplicant( 1322): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1322): wlan0: Starting radio work 'connect'@0x55b0f12aa0 after 0.000161 second wait
I/wpa_supplicant( 1322): check if in concurrent case
I/wpa_supplicant( 1322): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  946): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=35 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=147460
E/WifiStateMachine(  946): processMsg: DisconnectingState
D/wpa_supplicant( 1322): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1322): wlan0: Cancelling scan request
D/wpa_supplicant( 1322): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1322): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1322): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1322): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1322): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1322): RSN: PMKSA cache search - network_ctx=0x55b0f31c00 try_opportunistic=0
D/wpa_supplicant( 1322): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322): RSN: No PMKSA cache entry found
E/WifiStateMachine(  946):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=97422
D/wpa_supplicant( 1322): wlan0: RSN: using IEEE 802.11i/D9.0
E/WifiStateMachine(  946): processMsg: ConnectModeState
D/wpa_supplicant( 1322): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1322): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1322): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1322): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1322): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1322): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1322): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1322): wlan0: WPA: not using MGMT group cipher
E/WifiTrafficPoller(  946):  packet count Tx=129 Rx=220
D/wpa_supplicant( 1322): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1322): wlan0: State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1322): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1322): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1322): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1322): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  946):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=97422
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1322): nl80211: Unsubscribe mgmt frames handle 0x888888dd387b9989 (mode change)
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  946): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  946): ConnectModeState: Network connection lost 
E/WifiStateMachine(  946): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  946): handleMessage: new destination call exit/enter
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1322): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b0f31100
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=0104
E/WifiStateMachine(  946): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  946): invokeExitMethods: DisconnectingState
D/WifiMonitor(  946): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
E/WifiStateMachine(  946): moveTempStackToStateStack: i=0,j=4
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=040a
E/WifiStateMachine(  946): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  946): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  946): DisconnectedState call setCountryCode()
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=040b
E/WifiStateMachine(  946):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=040c
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=040d
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=090a
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=090b
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=090c
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=090d
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=0409506f9a09
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=7f506f9a09
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=0801
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=040e
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=06
,D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=0a07
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=0a11
D/wpa_supplicant( 1322): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f31100 match=0a1a
D/wpa_supplicant( 1322): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1322):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322):   * freq=2412
D/wpa_supplicant( 1322):   * freq_hint=2412
D/wpa_supplicant( 1322):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1322):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1322):   * WPA Versions 0x2
D/wpa_supplicant( 1322):   * pairwise=0xfac04
D/wpa_supplicant( 1322):   * group=0xfac04
D/wpa_supplicant( 1322):   * akm=0xfac02
D/wpa_supplicant( 1322):   * Auth Type 0
D/wpa_supplicant( 1322): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55b0f31c3a
D/wpa_supplicant( 1322): nl80211: Connect request send successfully
D/wpa_supplicant( 1322): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1322): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1322): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1322): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1322): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1322): Ongoing scan action - reject new request
E/WifiStateMachine(  946): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131101
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
E/WifiStateMachine(  946):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  946): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  946): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=147462
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=97429  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  946): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  946): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=97430  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131212
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  946): processMsg: DriverStartedState
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  946):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
E/WifiStateMachine(  946):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  946): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  946): handleMessage: X
D/WifiNetworkAgent(  946): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  946): handleMessage: E msg.what=131212
E/WifiStateMachine(  946): processMsg: DisconnectedState
D/WifiDataStallTracker(  946): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  946): stopDataStallAlarm 
D/WifiService(  946): New client listening to asynchronous messages
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  946): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiStateMachine(  946):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
E/WifiStateMachine(  946):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WISPrService( 5898): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  946): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  946): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131212
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
E/WifiStateMachine(  946):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  946): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131213
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=97440
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=97441
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=97441
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=97442
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=147462
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=97442  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  946): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  946): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  946): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  946): NetworkAgent == null
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=97451  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  946): handleMessage: X
E/WifiTrafficPoller(  946): ADD_CLIENT: 8
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  946): handleMessage: E msg.what=131131
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  946): processMsg: ConnectModeState
I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:3
E/WifiStateMachine(  946):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  946): handleMessage: X
W/WISPrService( 5898): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5898): trigger connection
D/WISPrService( 5898): continue
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524292
D/ConnectivityService(  946): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): Disconnected - quitting
D/ConnectivityService(  946): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1223): onLost 100
D/Nat464Xlat(  946): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/WIFI    (  946): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  946): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  946):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  946): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  946): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/NetworkManagementService(  946): Removing idletimer
D/usbnet  (  946): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  946):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  946): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiStateMachine(  946): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5898): start DataConnection
D/libc    ( 5898): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5898): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:21
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
,D/libc    ( 5898): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5898): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5898): [NET] android_getaddrinfo_proxy+
D/libc    ( 5898): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/PMS     (  946): acquireWL(1745da09): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 946 1000 null
D/libc    ( 5898): [NET] android_getaddrinfo_proxy-, NODATA
D/CSLegacyTypeTracker(  946): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  946): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
I/ActivityManager(  946): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6523 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/ConnectivityService(  946): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  946): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  946): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/ConnectivityService(  946): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  946): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  946): ensureActiveMobilePolicyLocked()
D/wpa_supplicant( 1322): Wireless event: cmd=0x8c02 len=271
D/PMS     (  946): acquireWL(1d22c40e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 946 1000 null
I/wpa_supplicant( 1322): WEXT: Custom wireless event: 'BEACONIEs='
D/PMS     (  946): releaseWL(1d22c40e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1322): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1322): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1322): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1322): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/Tethering(  946): interfaceLinkStateChanged wlan0, false
D/Tethering(  946): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1322): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1322): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1322): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1322): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1322): nl80211: Connect event
D/wpa_supplicant( 1322): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1322): nl80211: Associated with c0:ff:d4:d3:aa:48
D/Tethering(  946): interfaceLinkStateChanged wlan0, false
D/Tethering(  946): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1322): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1322): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1322): wlan0: Association info event
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1322): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1322): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 1322): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1322): wlan0: freq=2412 MHz
D/wpa_supplicant( 1322): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1322): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1322): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1322): nl80211: Set wlan0 operstate 0->0 (DORMANT)
,D/wpa_supplicant( 1322): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1322): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1322): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1322): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1322): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1322): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1322): TDLS: Remove peers on association
D/wpa_supplicant( 1322): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1322): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1322): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1322): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1322): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1322): EAPOL: enable timer tick
D/wpa_supplicant( 1322): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1322): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1322): wlan0: Cancelling scan request
I/wpa_supplicant( 1322): htc_wext_set_keepalive +
I/wpa_supplicant( 1322): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/wpa_supplicant( 1322): getPrivFuncNum +	
I/wpa_supplicant( 1322): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1322): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1322): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1322): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1322): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/Tethering(  946): interfaceLinkStateChanged wlan0, false
D/NetworkPolicy(  946): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/wpa_supplicant( 1322): wlan0:   EAPOL-Key type=2
V/NetworkPolicy(  946): updateNetworkEnabledLocked()
D/Tethering(  946): interfaceStatusChanged wlan0, false
V/NetworkPolicy(  946): updateIfacesLocked()
D/wpa_supplicant( 1322): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1322): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1322):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1322):   key_nonce - hexdump(len=32): c0 a6 73 17 ef 0a 9c 21 fd 67 f9 dc 26 b3 ca 8c 42 43 86 d2 3c 5b 9a 77 01 0d 80 bd 56 ad 8f e5
D/wpa_supplicant( 1322):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
V/NetworkPolicy(  946): updateNotificationsLocked()
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1322):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1322):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1322):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1322): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/NetworkManagementService(  946): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/wpa_supplicant( 1322): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1322): RSN: msg 1/4 key data - hexdump(len=0):
D/Tethering(  946): interfaceLinkStateChanged wlan0, true
D/Tethering(  946): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1322): WPA: Renewed SNonce - hexdump(len=32): e3 cf ff 58 ef a3 50 8b ca 93 aa 64 4b 4b 0b 55 ec c7 96 8f fb 78 5d 3f e9 a6 a7 c7 46 3d e7 2f
D/wpa_supplicant( 1322): WPA: Nonce1 - hexdump(len=32): e3 cf ff 58 ef a3 50 8b ca 93 aa 64 4b 4b 0b 55, ec c7 96 8f fb 78 5d 3f e9 a6 a7 c7 46 3d e7 2f
D/wpa_supplicant( 1322): WPA: Nonce2 - hexdump(len=32): c0 a6 73 17 ef 0a 9c 21 fd 67 f9 dc 26 b3 ca 8c 42 43 86 d2 3c 5b 9a 77 01 0d 80 bd 56 ad 8f e5
D/DATA_ICON( 1223): dataConnected: false/false
D/wpa_supplicant( 1322): WPA: PMK - hexdump(len=32): [REMOVED]
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1322): WPA: PTK - hexdump(len=48): [REMOVED]
V/Tethering(  946): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1322): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1322): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1322): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1322): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1322): WPA: Derived Key MIC - hexdump(len=16): 94 8c 7a 43 c7 58 a8 4f 1d f9 a1 9e e6 d0 9d 84
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  946): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  946): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  946): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  946): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  946): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  946): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  946): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  946): handleMessage: E msg.what=147462
D/HTCRequest(  946): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  946): processMsg: DisconnectedState
D/HTCRequest(  946): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  946): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1322): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1322): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1322): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/UsbDeviceManager(  946): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1322): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1322):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/wpa_supplicant( 1322):   key_nonce - hexdump(len=32): c0 a6 73 17 ef 0a 9c 21 fd 67 f9 dc 26 b3 ca 8c 42 43 86 d2 3c 5b 9a 77 01 0d 80 bd 56 ad 8f e5
E/WifiStateMachine(  946):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=97539  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/wpa_supplicant( 1322):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1322):   key_rsc - hexdump(len=8): aa 84 00 00 00 00 00 00
D/wpa_supplicant( 1322):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
E/WifiStateMachine(  946): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/wpa_supplicant( 1322):   key_mic - hexdump(len=16): 6f d9 e7 21 95 a8 19 ad d1 09 ea b0 6d a2 c2 a5
E/WifiStateMac,hine(  946): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  946): setDetailed state send new extra info0x
D/wpa_supplicant( 1322): RSN: encrypted key data - hexdump(len=56): c4 b4 e7 dc 63 42 59 dc 9b c6 ed 5c 7c 4b 52 51 55 60 85 6a 86 66 ca e7 b7 ec 79 b5 dd c4 a8 58 ...
D/wpa_supplicant( 1322): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1322): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1322): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1322): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 40 1e ...
D/WifiMonitor(  946): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1322): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1322): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/WifiMonitor(  946): handleAssociatedWithEvent. bLFR =false
D/wpa_supplicant( 1322): wlan0: WPA: Sending EAPOL-Key 4/4
D/WifiMonitor(  946): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1322): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1322): WPA: Derived Key MIC - hexdump(len=16): 9a ef 17 7e 8b 99 90 0b 8a 54 d2 24 6a 08 56 e1
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1322): wlan0: WPA: Installing PTK to the driver
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  946): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/wpa_supplicant( 1322): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55b0f32390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1322): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/PMS     (  946): acquireWL(26d1c141): PARTIAL_WAKE_LOCK  NetworkStats 0x1 946 1000 null
D/wpa_supplicant( 1322): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
V/NetworkPolicy(  946): updateNetworkEnabledLocked()
D/wpa_supplicant( 1322):    addr=c0:ff:d4:d3:aa:48
V/NetworkPolicy(  946): updateNotificationsLocked()
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiMonitor(  946): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1322): EAPOL: External notification - portValid=1
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1322): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1322): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/wpa_supplicant( 1322): WPA: Group Key - hexdump(len=16): [REMOVED]
V/NetworkPolicy(  946): updateNetworkEnabledLocked()
D/wpa_supplicant( 1322): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/PMS     (  946): releaseWL(26d1c141): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1322): WPA: RSC - hexdump(len=6): aa 84 00 00 00 00
V/NetworkPolicy(  946): updateNotificationsLocked()
D/wpa_supplicant( 1322): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5590583e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1322): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1322): nl80211: KEY_SEQ - hexdump(len=6): aa 84 00 00 00 00
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1322):    broadcast key
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 1322): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
D/wpa_supplicant( 1322): wlan0: Cancelling authentication timeout
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/wpa_supplicant( 1322): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/wpa_supplicant( 1322): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1322): wlan0: Radio work 'connect'@0x55b0f12aa0 done in 0.123138 seconds
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/ConnectivityService(  946): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/wpa_supplicant( 1322): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/ConnectivityService(  946): Got NetworkAgent Messenger
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/ConnectivityService(  946): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/HTCRequest(  946): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/ConnectivityService(  946): NetworkAgent connected
I/wpa_supplicant( 1322): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/WifiMonitor(  946): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1322): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1322): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1322): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 1322): set send_ind_to_ndc = 0
I/wpa_supplicant( 1322): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1322): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1322): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1322): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1322): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1322): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1322): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1322): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1322): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1322): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1322): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1322): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1322): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/Tethering(  946): interfaceLinkStateChanged wlan0, true
D/Tethering(  946): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  946): processMsg: ConnectModeState
D/WifiMonitor(  946): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  946): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  946): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=42 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  946): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor(  946): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=44 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  946): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  946): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  946):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=97546  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/UsbnetService(  946): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  946): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=147500
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  946): Enter handleAssociatedWithEvent
D/WifiStateMachine(  946): Associated
D/WifiStateMachine(  946): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  946): Exit handleAssociatedWithEvent
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=147462
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=97554  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  946): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  946): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  946): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/libc    ( 5898): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5898): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  946): NetworkAgent == null
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=97565  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 18
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=147462
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=97567  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WISPrService( 5898): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine(  946): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
E/WifiStateMachine(  946): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=97568  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=147459
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=97569
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  946): processMsg: ConnectModeState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=97570
E/WifiStateMachine(  946): Network connection established
D/WifiStateMachine(  946): fetchFrequency(), freq = 2412
E/WifiStateMachine(  946): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  946): NetworkAgent == null
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946): transitionTo: destState=ObtainingIpState
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 20
E/WifiStateMachine(  946): handleMessage: new destination call exit/enter
E/WifiStateMachine(  946): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  946): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  946): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  946): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  946): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  946): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  946): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  946): NetworkAgent == null
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 21
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  946): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  946): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  946): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1322): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1322): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1322): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  946): invokeEnterMethods: ObtainingIpState
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  946): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  946): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  946): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  946): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1322): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1322): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1322): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/WISPrService( 5898): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  946): Start Dhcp Watchdog 2
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131101
E/WifiStateMachine(  946): processMsg: ObtainingIpState
E/WifiStateMachine(  946):  ObtainingIpState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
D/WISPrService( 5898): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  946):  L2ConnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  946):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  946): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  946): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=147462
E/WifiStateMachine(  946): processMsg: ObtainingIpState
E/WifiStateMachine(  946):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=97606  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=97606  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=97607  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131155
E/WifiStateMachine(  946): processMsg: ObtainingIpState
E/WifiStateMachine(  946):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:636] from screen [on:0 period:-935691014] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:3
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-935691012] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1322): environment dirty rate=33 [3][1][0]
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=65.00 txretriesrate=0.00 rxrate=110.00 userTriggerdPenalty0
E/WifiStateMachine(  946):  good link -> stuck count =0
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  946):  isHighRSSI       ---> score=65
E/WifiStateMachine(  946): calculateWifiScore() report new score 60
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
I/ActivityManager(  946): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6547 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=196612
E/WifiStateMachine(  946): processMsg: ObtainingIpState
D/ConnectivityService(  946): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  946):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=130,0,0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=130,0,0
D/WifiStateMachine(  946): handlePreDhcpSetup Held wake lock during DHCP
D/WifiDataStallTracker(  946): setDhcpActive: true
D/PMS     (  946): acquireWL(3401f235): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 946 1000 null
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiStateMachine(  946): handlePreDhcpSetup mBluetoothConnectionActive: false
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1322): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -60, 3
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  946): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  946): do suspend false
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1322): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER POWERMODE 1'
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
I/wpa_supplicant( 1322): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1322): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1322): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1322): wlan0: Event DRIVER_GTK_REKEY (37) received
D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1322): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  946): Unexpected BatchedScanResults :null
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1322): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  946): noteBatchedScanstop()
E/WifiStateMachine(  946): handleMessage: X
D/WifiP2pService(  946): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f95086e target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  946): handleMessage: E msg.what=131212
D/WifiP2pService(  946): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f95086e target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  946): processMsg: ObtainingIpState
E/WifiStateMachine(  946):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
E/WifiStateMachine(  946):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  946): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  946): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  946): handleMessage: X
D/WearableService( 4805): callingUid 10024, callindPid: 4805
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4451, uid=10024, userID:0
,D/QSEECOMAPI: (  401): Loaded image: APP id = 8
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,E/MDM     ( 1827): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46c0000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46c0000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  533): got the req here! ret=0
D/DrmLibTime(  533): command id, time_cmd_id = 770
D/DrmLibTime(  533): time_getutcsec starts!
D/DrmLibTime(  533): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  533): QSEE Time Listener: get_utc_seconds
,D/DrmLibTime(  533): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  533): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  533): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  533): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  533): QSEE Time Listener: Retrieved Android system time: 1455058222
D/DrmLibTime(  533): time_getutcsec returns 0, sec = 1455058222; nsec = 0
D/DrmLibTime(  533): time_getutcsec finished! 
D/DrmLibTime(  533): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  533): before calling ioctl to read the next time_cmd
E/QC-time-services(  458): Daemon: Time-services: Waiting to acceptconnection
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/LocationInitializer( 4451): Restart initialization of location
,D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/TetherSettings( 5898): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5898): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5898): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5898): Cust_ConnectToPC   : spcsc>false
D/        ( 5898): Cust_ConnectToPC   : IPT>true
D/        ( 5898): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5898): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 5898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xfff583b8
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/SmartNS_Utility( 5898): hasRemovableStorageSlot: true
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab866640, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/SmartNS_Utility( 5898): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5898): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab8ae470, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab875128, idLength=0xf4b316f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/SmartNS_Utility( 5898): setISNotification
E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL false Token 22 num clients 8
D/SmartNS_Utility( 5898): usb_cable_connect = 1
D/SmartNS_Utility( 5898): usb_denied = 0
I/SmartNS_PSService( 5898): usb notificaiton:true
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 5898): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 5898): usb_cable_connect = 1
D/SmartNS_Utility( 5898): usb_denied = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/SmartNS_PSService( 5898): usb notificaiton:true
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b3170e, maximum = 0xf4b3170f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b3177c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=2822412895
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab998818
D/DrmWidevineDash(  401): message_length=1611, signature=0xab998e68, signature_length=0xf4b316dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1223): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 5898): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1223): reapply : com.android.settings 1 36
,I/ActivityManager(  946): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6577 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,D/MdScPhnSt( 6547): [3dc.2.]  listen tmrbb8,
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
E/dhcpcd  ( 6598): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6598): version 5.5.6 starting
,I/WVCdm   (  401): CdmEngine::CloseSession,
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/dhcpcd  ( 6598): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6598): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6598): autoip env[11]:autoip=DISABLE
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
,D/MdProvGlob( 6523): remove item 101 (p2d27in267) for 15:android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 6577): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/MdScDataSum( 6547): [3dc.2.] summary 118:p2 ignore
,I/dhcpcd  ( 6598): wlan0: rebinding lease of 192.168.1.130
,I/dhcpcd  ( 6598): wlan0: sending REQUEST (xid 0xee7aae85), next in 1.42 seconds
,I/CalendarProvider2( 6577): Created com.android.providers.calendar.CalendarAlarmManager@2622e1c8(com.htc.providers.calendar.HtcCalendarProvider@6554261),
,D/CalendarProvider2( 6577): wait start:true
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 6577): wait end:false
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  401): App is not loaded in QSEE
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/QSEECOMAPI: (  401): Loaded image: APP id = 9
,D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
,D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
,D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46c0000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46c0000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  533): got the req here! ret=0
D/DrmLibTime(  533): command id, time_cmd_id = 770
D/DrmLibTime(  533): time_getutcsec starts!
D/DrmLibTime(  533): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  533): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  533): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  533): QSEE Time Listener: Checking if ATS_MODEM is set or not.
D/FlexNetS( 6577): updateSvcAllowedInSettings:false
E/QC-time-services(  533): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  533): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  533): QSEE Time Listener: Retrieved Android system time: 1455058222
D/DrmLibTime(  533): time_getutcsec returns 0, sec = 1455058222; nsec = 0
D/DrmLibTime(  533): time_getutcsec finished! 
D/DrmLibTime(  533): iotcl_continue_command finished! and return 0 
,D/DrmLibTime(  533): before calling ioctl to read the next time_cmd
E/QC-time-services(  458): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9,
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/FlexNetS( 6577): updateSvcAllowedInSettings:false
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf4935928
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab866828, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab8ae470, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab875148, idLength=0xf4b316f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b3170e, maximum = 0xf4b3170f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9,
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b3177c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=2565865980
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab998948
D/DrmWidevineDash(  401): message_length=1646, signature=0xab9951e0, signature_length=0xf4b316dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
,D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6619): Error opening trace file: Permission denied (13),
I/dex2oat ( 6619): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6619): dex2oat: override thread count:4
,I/dex2oat ( 6619): dex2oat took 65.934ms (threads: 4),
,I/Adreno-EGL( 6489): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6489): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6489): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6489): Local Branch: 
I/Adreno-EGL( 6489): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6489): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6489):                  d74aa161a12b9c6fc6332151
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL false Token 22 num clients 8,
,I/Adreno-EGL( 6489): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6489): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6489): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6489): Local Branch: 
I/Adreno-EGL( 6489): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6489): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6489):                  d74aa161a12b9c6fc6332151
,D/wpa_supplicant( 1322): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1322): EAPOL: disable timer tick
,I/CheckinRequestBuilder( 4451): Classify the device as Phone.,
,D/libc    ( 4451): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4451): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4451): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4451): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4451): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4451): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4451): [NET] android_getaddrinfo_proxy-, NODATA
E/CheckinTask( 4451): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinService( 4451): Checking schedule, now: 1455058223323 next: 1455058233318,
I/CheckinService( 4451): active receiver: disabled
I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4451, uid=10024, userID:0
,D/PMS     (  946): releaseWL(1ec9fc12): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  946): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6628 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/PhoneMonitor( 6628): Register our PhoneStateListener
,D/Process (  946): killProcessQuiet, pid=5806
I/ActivityManager(  946): Killing 5806:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 6628): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6628): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  946): Recipient 5806
,D/GCM     ( 1855): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 4451): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/Kids    ( 4451): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/CalendarProvider2( 6577): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6577): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  946): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6652 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
D/Process (  946): killProcessQuiet, pid=5871
I/ActivityManager(  946): Killing 5871:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 5871
,I/dhcpcd  ( 6598): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,W/ResourcesManager( 6652): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/CalendarApplication( 6652): onCreate
D/ProviderChangeReceiver( 6652): ---------------------------------------------------
D/ProviderChangeReceiver( 6652): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  946): killProcessQuiet, pid=6156,
I/ActivityManager(  946): Killing 6156:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 6652): start to updateAlertNotification!
,I/dhcpcd  ( 6598): wlan0: leased 192.168.1.130 for 86400 seconds
I/dhcpcd  ( 6598): autoip env[11]:autoip=DISABLE
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  946): handleMessage: E msg.what=131212
E/WifiStateMachine(  946): processMsg: ObtainingIpState
E/WifiStateMachine(  946):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
,E/WifiStateMachine(  946):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  946): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  946): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  946): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  946): handleMessage: X
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  946): handleMessage: E msg.what=131212
E/WifiStateMachine(  946): processMsg: ObtainingIpState
,E/WifiStateMachine(  946):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  946): processMsg: L2ConnectedState
,E/WifiStateMachine(  946):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  946): processMsg: ConnectModeState
,E/WifiStateMachine(  946):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  946): processMsg: DefaultState
E/WifiStateMachine(  946):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  946): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  946): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  946): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  946): handleMessage: X
,I/ActivityManager(  946): Recipient 6156
,I/dhcpcd  ( 6598): bind_interface: daemonise
,D/HtcAlertService( 6652): No fired or scheduled alerts
,D/HtcAlertUtils( 6652): -- cancelReminderNotification --
,D/HtcAlertUtils( 6652): broadcastExistReminder!
,D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/WifiP2pService(  946): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  946): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  946): releaseWL(3401f235): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  946): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  946): handleMessage: E msg.what=196613
E/WifiStateMachine(  946): processMsg: ObtainingIpState
E/WifiStateMachine(  946):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  946): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1322): Power_Mode_Type mode = 0
I/wpa_supplicant( 1322): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1322): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  946): setDhcpActive: false
E/WifiStateMachine(  946): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  946): WifiStateMachine DHCP successful
E/WifiStateMachine(  946): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  946): link address 192.168.1.130/24
E/WifiStateMachine(  946): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  946): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  946): gateway: /192.168.1.1
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1322): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  946): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131210
E/WifiStateMachine(  946): processMsg: ObtainingIpState
E/WifiStateMachine(  946):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
,E/WifiStateMachine(  946):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1322): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1322): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1322): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  946): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -58, 3
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=46 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  946): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  946): NetworkAgent != null
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  946): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
V/NetworkPolicy(  946): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  946): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL true Token 22
D/HtcWifiWanDetect(  946): WAN detection
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/HtcWifiWanDetect(  946): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  946):  packet count Tx=132 Rx=222
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  946): notifying of data activity 3
E/WifiDataStallTracker(  946): ENABLE_DATA_MONITOR_POLL true Token 2
,D/ConnectivityService(  946): Adding iface wlan0 to network 101
,D/WifiDataStallTracker(  946): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  946): updateDataStallInfo: NONE
D/WifiDataStallTracker(  946): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  946): transitionTo: destState=ConnectedState
E/WifiStateMachine(  946): handleMessage: new destination call exit/enter
E/WifiStateMachine(  946): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  946): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  946): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  946): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  946): invokeEnterMethods: ConnectedState
V/NetworkPolicy(  946): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL true Token 23
E/WifiTrafficPoller(  946):  packet count Tx=132 Rx=222
E/WifiTrafficPoller(  946): notifying of data activity 0
E/WifiStateMachine(  946): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  946): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WIFI_ICON( 1223): WifiActivity: 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1223): WifiActivity: 0
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5898): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  946): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine(  946): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
E/WifiStateMachine(  946): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/ConnectivityService(  946): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  946): handleMessage: X
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  946): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  946): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  946): handleMessage: E msg.what=131131
E/WifiStateMachine(  946): processMsg: ConnectedState
D/ConnectivityService(  946): Setting Dns servers for network 101 to [/192.168.1.1]
E/WifiStateMachine(  946):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  946): processMsg: L2ConnectedState
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  946):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  946): processMsg: ConnectModeState
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  946):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  946): handleMessage: X
,D/Nat464Xlat(  946): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  946): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): Connected
D/ConnectivityService(  946): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  946): rematching NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): Validated
D/ConnectivityService(  946):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  946): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  946):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  946):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  946):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  946): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  946): currentScore = 0, newScore = 20
D/ConnectivityService(  946):    accepting network in place of null
D/ConnectivityService(  946): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/CSLegacyTypeTracker(  946): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  946): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  946): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  946): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  946): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WIFI    (  946): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  946): ensureActiveMobilePolicyLocked()
D/WIFI    (  946):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  946): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  946): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/WISPrService( 5898): >>>>>WISPrService start isConnected = true<<<<<
D/Tethering(  946): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  946): acquireWL(c98af15): PARTIAL_WAKE_LOCK  NetworkStats 0x1 946 1000 null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  946): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/Tethering(  946): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): Validated
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkPolicy(  946): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . R,eturn.
V/NetworkPolicy(  946): updateNetworkEnabledLocked()
V/NetworkPolicy(  946): updateIfacesLocked()
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/ConnectivityService(  946): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  946): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  946): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  946):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  946):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  946): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  946): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  946): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  946): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  946):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  946): updateNotificationsLocked()
D/WIFI    (  946): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  946): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  946): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  946): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  946): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/usbnet  (  946):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/usbnet  (  946): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/SecurityController( 1223): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
I/SecurityController( 1223): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  946): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/ConnectivityService(  946): Validated NetworkAgentInfo [WIFI () - 101]
D/DATA_ICON( 1223): dataConnected: false/false
D/ConnectivityService(  946): rematching NetworkAgentInfo [WIFI () - 101]
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  946):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  946):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  946): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  946): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  946): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PMS     (  946): acquireWL(2199222a): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4451 10024 WorkSource{10024 com.google.android.gms}
D/DATA_ICON( 1223): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/PMS     (  946): releaseWL(c98af15): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1223): dataConnected: false/false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/NetworkPolicy(  946): updateNetworkEnabledLocked()
I/SecurityController( 1223): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,V/NetworkPolicy(  946): updateNotificationsLocked()
,D/PMS     (  946): acquireWL(2ccc5db8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4451 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): releaseWL(2199222a): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/CheckinService( 4451): Checking schedule, now: 1455058224268 next: 1455058221533
,I/CheckinService( 4451): active receiver: enabled
I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4451, uid=10024, userID:0
,I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/CheckinService( 4451): Preparing to send checkin request,
I/EventLogService( 4451): Accumulating logs since 1455058221616
,I/CheckinRequestBuilder( 4451): Checkin reason type: 8 attempt count: 1,
,I/ActivityManager(  946): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4451): Failed to find provider info for com.google.android.wearable.settings
,E/WifiDataStallTracker(  946): DATA_MONITOR_POLL true Token 3,
,I/GLSUser ( 1855): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1855): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1855): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1855): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4451): awaiting user notification for token,
,W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1223): reapply : com.google.android.gms 2 40,
,I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  401): Service_Initialize: starts!,
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
,D/QSEECOMAPI: (  401): Loaded image: APP id = 10,
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46c0000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46c0000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  533): got the req here! ret=0,
D/DrmLibTime(  533): command id, time_cmd_id = 770
D/DrmLibTime(  533): time_getutcsec starts!
D/DrmLibTime(  533): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  533): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  533): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  533): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  533): Receive Passed == base = 13, unit = 1, operation = 2, result = 0,
D/DrmLibTime(  533): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  533): QSEE Time Listener: Retrieved Android system time: 1455058224
D/DrmLibTime(  533): time_getutcsec returns 0, sec = 1455058224; nsec = 0
D/DrmLibTime(  533): time_getutcsec finished! 
D/DrmLibTime(  533): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  533): before calling ioctl to read the next time_cmd
E/QC-time-services(  458): Daemon: Time-services: Waiting to acceptconnection
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xfff583b8
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab994d80, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab952100, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab875108, idLength=0xf4b316f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b3170e, maximum = 0xf4b3170f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b3177c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=742858789
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab998818
D/DrmWidevineDash(  401): message_length=1611, signature=0xab998e68, signature_length=0xf4b316dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
,D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 10
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=65.0, 0.0, 0.0  rx=110.0 bcn=0 [on:0 tx:0 rx:0 period:2334] from screen [on:0 period:-935688647] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
,E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=65.0, 0.0, 0.0  rx=110.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-935688646] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946): handleMessage: X
,I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
,E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
,D/QSEECOMAPI: (  401): Loaded image: APP id = 11,
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46c0000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46c0000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  533): got the req here! ret=0,
D/DrmLibTime(  533): command id, time_cmd_id = 770
D/DrmLibTime(  533): time_getutcsec starts!
D/DrmLibTime(  533): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  533): QSEE Time Listener: get_utc_seconds
,D/DrmLibTime(  533): QSEE Time Listener: time_get_modem_time,
D/DrmLibTime(  533): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  533): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  533): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  533): QSEE Time Listener: Retrieved Android system time: 1455058224
D/DrmLibTime(  533): time_getutcsec returns 0, sec = 1455058224; nsec = 0
D/DrmLibTime(  533): time_getutcsec finished! 
,D/DrmLibTime(  533): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  533): before calling ioctl to read the next time_cmd
E/QC-time-services(  458): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9,
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf4935928,
,D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab994f70, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab952100, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab875148, idLength=0xf4b316f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b3170e, maximum = 0xf4b3170f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b3177c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=2725294359
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab998818
D/DrmWidevineDash(  401): message_length=1646, signature=0xab998e90, signature_length=0xf4b316dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 11
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 6489): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6489): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6489): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6489): Local Branch: 
I/Adreno-EGL( 6489): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6489): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6489):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6489): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6489): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6489): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6489): Local Branch: 
I/Adreno-EGL( 6489): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6489): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6489):                  d74aa161a12b9c6fc6332151
,I/CheckinRequestBuilder( 4451): Classify the device as Phone.,
,D/libc    ( 4451): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4451): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4451): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4451): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4451): [NET] android_getaddrinfo_proxy+
D/libc    ( 4451): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 4451): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4451): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4451): [NET] android_getaddrinfofornet-, err=8
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8,
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  946):  packet count Tx=139 Rx=228
D/WIFI_ICON( 1223): WifiActivity: 3
,E/WifiTrafficPoller(  946): notifying of data activity 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/HtcModeClient( 3229): handler message = 4011,
E/HtcModeClient( 3229): Check connection and retry 12 times.
,D/libc    ( 4451): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4451): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4451): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4451): [NET] android_getaddrinfofornet-, err=8
D/ConnectivityService(  946): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  946): releaseWL(1745da09): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  946): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
I/AlarmManager(  946): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  946): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  946): acquireWL(3025df93): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 946 1000 null
D/PMS     (  946): acquireWL(8f12bd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 946 1000 null
D/PMS     (  946): releaseWL(8f12bd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  946): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  946): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  946): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, err=8
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  946): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  946): [NET] android_getaddrinfo_proxy+
D/libc    (  946): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/CheckinTask( 4451): Sending checkin request (8446 bytes)
,I/ConnectivityHelper( 1627): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  946): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6714 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  946): No APN found to select.
,D/MdScPhnSt( 6547): [aca.1.]  listen tmrbb8,
D/PMS     (  946): releaseWL(3025df93): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScDataSum( 6547): [aca.1.] summary 118:p1 ignore,
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=65.0, 0.0, 0.0  rx=110.0 bcn=0 [on:0 tx:0 rx:0 period:643] from screen [on:0 period:-935688002] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=65.0, 0.0, 0.0  rx=110.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-935688001] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
,W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1322): environment dirty rate=18 [16][3][0]
,E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiStateMachine(  946): BroadcastRSSIForIMS, newrssi =-60 , oldRssi= -200
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=42.00 txretriesrate=0.00 rxrate=60.50 userTriggerdPenalty0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  946):  good link -> stuck count =0
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  946):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  946): handleMessage: X
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/MusicStore( 6714): Database version: 120
,D/VoldConnector(  946): SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6714): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  946): SND -> {29 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6714): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  946): SND -> {30 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6714): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 4451): Checkin reason type: 8 attempt count: 1,
,I/ActivityManager(  946): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4451): Failed to find provider info for com.google.android.wearable.settings,
,W/ResourcesManager( 6714): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6714): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6714): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6714): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6714): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@223648fc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6714): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6714): GMSCore installation verified
,I/ConfigStore( 6714): Config Database version: 1,
,I/art     (  946): Explicit concurrent mark sweep GC freed 53684(2MB) AllocSpace objects, 6(248KB) LOS objects, 33% free, 16MB/25MB, paused 1.448ms total 150.893ms
,I/art     ( 1855): Explicit concurrent mark sweep GC freed 9854(523KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 700us total 36.783ms
I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6714, uid=10159, userID:0
,D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
,D/WifiDisplayAdapter(  946):     IP Address: }
,D/MediaRouterService(  946): Client com.google.android.music (pid 6714): Registered
,D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
,I/MediaRouter( 6714): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6714): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6714): type=WIFI subType= reason=null isConnected=true
,I/GLSUser ( 1855): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1855): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1855): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1855): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4451): awaiting user notification for token,
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 1 40
,I/NetworkMonitor( 6714): type=WIFI subType= reason=null isConnected=true
,I/CheckinRequestBuilder( 4451): Classify the device as Phone.
,I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6714, uid=10159, userID:0
,D/AutoSetting( 1541): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6628): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6628): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1541): service - onCreate()
,D/PMS     (  946): acquireWL(3523598c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4451 10024 WorkSource{10024 com.google.android.gms}
,D/AutoSetting( 1541): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/LocationManagerService(  946): request 1ca99ef3 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  946): provider request: passive ProviderRequest[ON interval=0]
D/PMS     (  946): releaseWL(3523598c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/AutoSetting( 1541): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1541): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1541): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1541): service - handleMessage() setting current location null
,I/GHttpClientFactory( 6714): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/CheckinTask( 4451): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/GoogleURLConnFactory( 6714): Using platform SSLCertificateSocketFactory
,I/CheckinService( 4451): Checking schedule, now: 1455058226089 next: 1455595058082
I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4451, uid=10024, userID:0
I/CheckinService( 4451): active receiver: disabled
,I/CheckinService( 4451): Checking schedule, now: 1455058226120 next: 1455595058082
I/CheckinService( 4451): active receiver: disabled
I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4451, uid=10024, userID:0
,D/PMS     (  946): releaseWL(2ccc5db8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4451): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4451): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
I/ActivityManager(  946): Killing 6178:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  946): killProcessQuiet, pid=6178
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  946):  packet count Tx=150 Rx=236
,I/ActivityManager(  946): Recipient 6178,
,I/ActivityManager(  946): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6761 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6306): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 6306): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6306): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6306): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6306): [NET] android_getaddrinfo_proxy+
D/libc    ( 6306): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6306): [NET] android_getaddrinfo_proxy-, success
,I/Babel   ( 6306): connection state changed from UNKNOWN to CONNECTED,
,D/VoldConnector(  946): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6761): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6761): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6761):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6761):   adb logcat -s GAv4
D/VoldConnector(  946): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6761): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  946): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6761): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  946): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6761): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6761): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6761): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6761): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6761): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6761): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6761): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6761): Time to load native libraries: 11 ms (timestamps 2041-2052),
,I/LibraryLoader( 6761): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6761): Binding Chromium to main looper Looper (main, tid 1) {368056a5},
I/LibraryLoader( 6761): Expected native library version number "",actual native library version number ""
,I/chromium( 6761): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6761): Initializing chromium process, singleProcess=true
,W/art     ( 6761): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6761): ApplicationContext is null in ApplicationStatus
,W/chromium( 6761): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6761): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6761): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6761): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6761): OpenGL ES Shader Compiler Version: E031.25.03.01,
I/Adreno-EGL( 6761): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6761): Local Branch: 
I/Adreno-EGL( 6761): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6761): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6761):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6761): Requires BLUETOOTH permission,
,I/NSApplication( 6761): Starting up...
,I/ActivityManager(  946): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6821 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  946): killProcessQuiet, pid=5963
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  946): Killing 5963:com.google.android.gms:car/u0a24 (adj 15): empty #17
,I/ActivityManager(  946): Recipient 5963
,E/WifiStateMachine(  946): handleMessage: E msg.what=131168
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  946): processMsg: DefaultState
,E/WifiStateMachine(  946):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  946): handleMessage: X
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  946): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  946): [NET] android_getaddrinfo_proxy+
D/libc    (  946): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  946):  packet count Tx=156 Rx=240
,D/ConnectivityService(  946): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  946): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  946): acquireWL(10a34c69): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 946 1000 null
I/AlarmManager(  946): [AlarmQueuing] connectivity wifi: true
I/ConnectivityHelper( 1627): [onReceive] WIFI(1): CONNECTED
I/NetworkMonitor( 6714): type=WIFI subType= reason=null isConnected=true
,D/PMS     (  946): acquireWL(1905b6ee): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 946 1000 null
D/htcCheckinService(  946): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/GpsLocationProvider(  946): [handleMessage] UPDATE_NETWORK_STATE,
D/PMS     (  946): releaseWL(1905b6ee): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  946): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,E/GpsLocationProvider(  946): No APN found to select.
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  946): [NET] android_getaddrinfo_proxy-, success
D/HtcWifiWanDetect(  946): Find DNS Address www.htc.com/23.59.123.86
D/PMS     (  946): releaseWL(10a34c69): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6547): [688.1.]  listen tmrbb8
,D/MdScDataSum( 6547): [688.1.] summary 118:p1 ignore
,D/Process (  946): killProcessQuiet, pid=6210
I/ActivityManager(  946): Killing 6210:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,I/ActivityManager(  946): Recipient 6210,
,I/ActivityManager(  946): Killing 6283:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
D/Process (  946): killProcessQuiet, pid=6283
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6283,
,D/Process (  946): killProcessQuiet, pid=5340
I/ActivityManager(  946): Killing 5340:com.android.defcontainer/u0a15 (adj 15): empty #18
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 5340
,D/Process (  946): killProcessQuiet, pid=6341
I/ActivityManager(  946): Killing 6341:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6341,
,D/PMS     (  946): acquireWL(1ea9b5c6): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{10024}
,V/AlarmManager(  946): sending alarm PendingIntent{20c8e987: PendingIntentRecord{121cc0b4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=102766, Int=0,
V/AlarmManager(  946): sending alarm PendingIntent{14dfabce: PendingIntentRecord{38e91aef android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455058224430, Int=20000
,V/SetupWizard( 6628): Connected to Gservices successfully
,D/ChimeraCfgMgr( 4451): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/Kids    ( 4451): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,V/MusicLeanback( 6714): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PMS     (  946): acquireWL(382d14dd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1855): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    ( 1855): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1855): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1855): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1855): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1855): [NET] android_getaddrinfo_proxy+
D/libc    ( 1855): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/AutoSetting( 1541): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/MobileConnectivityChangeReceiver( 6628): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6628): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1541): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1541): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1541): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1541): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1541): service - handleMessage() setting current location null
,I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4451, uid=10024, userID:0,
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6434): 
,D/ChimeraCfgMgr( 4451): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/Kids    ( 4451): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1855): [NET] android_getaddrinfo_proxy-, success
,E/WifiStateMachine(  946): WiFiStateMachine SCAN ALARM,
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
E/WifiStateMachine(  946): handleMessage: E msg.what=131143
D/PMS     (  946): releaseWL(1ea9b5c6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:83 rssi=-60 f=2412 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=60.5 list=2412 [on:0 tx:0 rx:0 period:2675] from screen [on:0 period:-935685320]
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:83 rssi=-60 f=2412 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=60.5 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-935685319]
,E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=42.00 rxSuccessRate=60.50 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN with age=65519 interval=40000 maxinterval=300000
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN try full band scan age=65519 interval=40000 maxinterval=300000
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=42.00 rx=60.50
E/WifiStateMachine(  946): handleMessage: X
,D/libc    ( 1855): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1855): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1855): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1855): [NET] android_getaddrinfofornet-, err=8
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  946):  packet count Tx=167 Rx=249
,D/GCM     ( 1855): Connected
D/PMS     (  946): acquireWL(21eb21d9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): releaseWL(382d14dd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(21eb21d9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(1c43b79e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1855): Message class com.google.f.a.a.p
,D/PMS     (  946): releaseWL(1c43b79e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=60.5 bcn=0 [on:0 tx:0 rx:0 period:324] from screen [on:0 period:-935684994] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=60.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-935684993] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1322): environment dirty rate=9 [22][2][0]
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -59, 3
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=31.00 txretriesrate=0.00 rxrate=40.25 userTriggerdPenalty0
E/WifiStateMachine(  946):  good link -> stuck count =0
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  946):  isHighRSSI       ---> score=65
E/WifiStateMachine(  946): handleMessage: X
,D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -59, 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6434): 
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6434): 
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6434): 
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 6434): 
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
I/jxcore-log( 6434): 
,E/WifiDataStallTracker(  946): DATA_MONITOR_POLL true Token 3,
,D/WifiDataStallTracker(  946): updateDataStallInfo: mDataStallTxRxSum={txSum=142 rxSum=124} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  946): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  946): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  946):  packet count Tx=169 Rx=252
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  946):  packet count Tx=169 Rx=252
E/WifiTrafficPoller(  946): notifying of data activity 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 3229): handler message = 4011
,E/HtcModeClient( 3229): Check connection and retry 12 times. Stop service and kill this process.,
D/HtcModeClient( 3229): Don't start project servcice
,D/HtcModeClient( 3229): setEject: MEDIA_EJECT_STATE = true,
D/HtcModeClient( 3229): connectState: CONNECTION_READY = false
D/SilentMusic( 3229): call stop
D/HtcModeClient( 3229): close connection
W/HtcModeClient( 3229): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3229): read the terminate packet, so break
D/libc    (  393): [NET]Querying server xid =425 (# 1) address = 192.168.1.1 (try=1,nscount=1,v_circuit=0)
,D/libc    (  393): before statp->options=0x800002C3)
,D/Process (  946): killProcessQuiet, pid=3229,
I/ActivityManager(  946): Killing 3229:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    (  393): after statp->options=0x800002C1),
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    (  946): [NET] android_getaddrinfo_proxy-, success
,D/AlarmManager(  946): Ignore time set to 1455058230667 in setTime(); too close to current time 1455058230362,
,I/ActivityManager(  946): Recipient 3229,
,D/PMS     (  946): acquireWL(1613724c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6714 10159 null,
,I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6714, uid=10159, userID:0
,I/MusicLeanback( 6714): Conditions not met for autocaching. okToAttempt=false
D/PMS     (  946): releaseWL(1613724c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6714): Stop autocaching.
,D/WearableService( 4805): callingUid 10024, callindPid: 4805
,E/GmsUtils( 6714): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6714): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1223): WifiActivity: 3,
E/WifiTrafficPoller(  946):  packet count Tx=171 Rx=254
E/WifiTrafficPoller(  946): notifying of data activity 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=31.0, 0.0, 0.0  rx=40.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-935681983] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=31.0, 0.0, 0.0  rx=40.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-935681981] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1322): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
,E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -60, 3,
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=16.50 txretriesrate=0.00 rxrate=21.62 userTriggerdPenalty0,
E/WifiStateMachine(  946):  good link -> stuck count =0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 60,
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  946):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  946): handleMessage: X
,D/AccTypeManager( 1766): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,W/SystemReader(  946): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1766): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  946): acquireWL(2d6dcd8b): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6306 10112 null
,I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
,W/Prism.AllAppsManager( 1627): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1627): Deferring update until onResume
,D/Launcher( 1627): waitUntilResume // bindAppsUpdated
,W/ResourcesManager(  946): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1766): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  946): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6875 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,D/PhoneApp( 1565): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,E/ExternalAccountType( 1766): Unsupported attribute readOnly,
,D/PMS     (  946): releaseWL(2d6dcd8b): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/PackageManager(  946): Unable to load service info ResolveInfo{2a7ab712 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  946): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  946): 	,at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  946): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  946): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  946): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  946): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  946): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  946): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  946): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  946): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  946): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  946): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1827): DISABLE,
,I/GCoreNlp( 1827): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  946): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,D/LocationProviderProxy(  946): applying state to connected service
,D/PMS     (  946): acquireWL(1ed344da): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1827 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): releaseWL(1ed344da): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(1742693d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1827 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(1742693d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/LocationManagerService(  946): getProviders()=[passive]
,I/ActivityManager(  946): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6904 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/art     (  440): Explicit concurrent mark sweep GC freed 8641(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 179us total 20.470ms,
I/art     (  946): Explicit concurrent mark sweep GC freed 30220(1610KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/25MB, paused 2.100ms total 158.495ms
D/LocationProviderProxy(  946): applying state to connected service
I/art     (  440): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 154us total 18.438ms
,D/PMS     (  946): acquireWL(130282f5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1827 10024 WorkSource{10024 com.google.android.gms}
,I/[PluginManager]RegisterService( 1541): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1541): handle notify Blinkfeed plugin client changed
D/PMS     (  946): acquireWL(1a76988a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1827 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): releaseWL(130282f5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(1a76988a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PackageBroadcastService( 4451): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/art     (  440): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 237us total 31.015ms
D/PMS     (  946): acquireWL(d2db356): PARTIAL_WAKE_LOCK  AsyncService 0x1 6251 10167 null
I/PackageBroadcastService( 4451): Null package name or gms related package.  Ignoreing.
,D/PMS     (  946): releaseWL(d2db356): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  946): acquireWL(19051bad): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6251 10167 null
D/PMS     (  946): acquireWL(a69aee2): PARTIAL_WAKE_LOCK  Icing 0x1 4451 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(19051bad): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/Icing   ( 4451): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 6875): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  946): releaseWL(a69aee2): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8,
D/WIFI_ICON( 1223): WifiActivity: 2
E/WifiTrafficPoller(  946):  packet count Tx=172 Rx=254
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
E/WifiTrafficPoller(  946): notifying of data activity 2
,I/UpdateIcingCorporaServi( 6875): UpdateCorporaTask done [took 132 ms] updated apps [took 132 ms] ,
,I/ActivityManager(  946): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6936 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  946): acquireWL(1b6cc530): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{10076}
V/AlarmManager(  946): sending alarm PendingIntent{484c5a9: PendingIntentRecord{2a77d72e com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455058232819, Int=60000
D/PMS     (  946): releaseWL(1b6cc530): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6936): SMSBackupAgentService started
,D/SMSBackup( 6936): Checking restore status
,D/SMSBackup( 6936): Restore complete
,D/SMSBackup( 6936): cancelCheckAlarm
,D/SMSBackup( 6936): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  946): killProcessQuiet, pid=5463
,I/ActivityManager(  946): Killing 5463:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 5463
,I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1627): loadItems() com.htc.launcher.pageview.WidgetManager@d5e12b0 +
I/Prism.WidgetManager( 1627): onLoadItems() +,
,W/ResourcesManager( 1627): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8
E/WifiTrafficPoller(  946):  packet count Tx=172 Rx=254
E/WifiTrafficPoller(  946): notifying of data activity 0
D/WIFI_ICON( 1223): WifiActivity: 0
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/ResourcesManager( 1627): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/asset   ( 1627): Copying FileAsset 0x55ab4effb0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1627): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1627): onLoadItems() -
I/Prism.ItemManager( 1627): loadItems() com.htc.launcher.pageview.WidgetManager@d5e12b0 -
,D/PhoneApp( 1565): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1565): -- N1 =0
,D/PhoneApp( 1565): -- N2 =0
,D/PhoneApp( 1565): -- N3 =0,
,E/WifiDataStallTracker(  946): DATA_MONITOR_POLL true Token 3,
,D/WifiDataStallTracker(  946): updateDataStallInfo: mDataStallTxRxSum={txSum=142 rxSum=124} preTxRxSum={txSum=142 rxSum=124},
D/WifiDataStallTracker(  946): updateDataStallInfo: NONE
D/WifiDataStallTracker(  946): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  946):  packet count Tx=172 Rx=254
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=16.5, 0.0, 0.0  rx=21.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-935678960] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=16.5, 0.0, 0.0  rx=21.6 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-935678958] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1322): environment dirty rate=100 [1][1][0],
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.75 txretriesrate=0.00 rxrate=10.81 userTriggerdPenalty0,
E/WifiStateMachine(  946):  good link -> stuck count =0
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  946):  isHighRSSI       ---> score=65
E/WifiStateMachine(  946): handleMessage: X
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -59, 3
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 6434): 
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
I/jxcore-log( 6434): 
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 6434): 
,I/jxcore-log( 6434): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6434): 
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  946):  packet count Tx=172 Rx=255
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  946): notifying of data activity 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 6434): Test app app.js loaded,
I/jxcore-log( 6434): 
,I/chromium( 6434): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): ,	,Bluetooth MAC address: 90:E7:C4:F6:69:77, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): ,	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6434): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ca71ef5 added. We now have 1 listener(s)
,D/BluetoothAdapter( 6434): 172139421: getState(). Returning 12
I/jxcore-log( 6434): BLE advertisement is supported
I/jxcore-log( 6434): 
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1223): WifiActivity: 3
E/WifiTrafficPoller(  946):  packet count Tx=173 Rx=256
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiTrafficPoller(  946): notifying of data activity 3
,D/Process (  946): killProcessQuiet, pid=6652,
I/ActivityManager(  946): Killing 6652:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6652
,D/Process (  946): killProcessQuiet, pid=6523
I/ActivityManager(  946): Killing 6523:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  946): Recipient 6523
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 24 num clients 8
E/WifiTrafficPoller(  946):  packet count Tx=174 Rx=257
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.8, 0.0, 0.0  rx=10.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-935675939] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
,E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.8, 0.0, 0.0  rx=10.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-935675938] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1322): environment dirty rate=0 [2][0][0]
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.38 txretriesrate=0.00 rxrate=6.91 userTriggerdPenalty0
,E/WifiStateMachine(  946):  good link -> stuck count =0
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  946):  isHighRSSI       ---> score=65
E/WifiStateMachine(  946): handleMessage: X
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -59, 3
,I/PMS     (  946): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  946): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2bd0b505
,W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  946): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  946): pid=946, uid=1000
W/PMN     (  946): goingToSleep
W/SensorService(  946): Active sensors: size = 4
W/SensorService(  946): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  946): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  946): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2bd0b505, eanble = 0, strlen(mName) = 91
W/SensorService(  946): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  946): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@f17f9e2
W/SensorService(  946): Listener[1] = com.htc.smartdim.sensor_eye@31d75da4
W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1223): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  946): mWirelessDisplayManager is null
W/PMS     (  946): mWirelessDisplayManager is still null
,D/PMS     (  946): acquireWL(1d91045c): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 946 1000 null
W/PMN     (  946): goingToSleep done
,I/PMS     (  946): Sleeping (uid 1000)...
,D/XAN-DPS (  946): prepareColorFade 1
D/PMS     (  946): releaseWL(1d91045c): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/HtcSystemUPManager(  946): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/AlarmManager(  946): ACTION_SCREEN_ON
,E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL true Token 24
,I/AlarmManager(  946): [AlarmQueuing] recover blocked alarms
E/WifiTrafficPoller(  946):  packet count Tx=174 Rx=258
I/AlarmManager(  946): [AlarmQueuing] done recovering
E/WifiTrafficPoller(  946): notifying of data activity 1
I/AlarmManager(  946): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  946): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiDataStallTracker(  946): ENABLE_DATA_MONITOR_POLL true Token 3
D/WIFI_ICON( 1223): WifiActivity: 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  946): updateDataStallInfo: mDataStallTxRxSum={txSum=144 rxSum=126} preTxRxSum={txSum=144 rxSum=126}
D/WifiDataStallTracker(  946): updateDataStallInfo: NONE
D/WifiDataStallTracker(  946): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  946): handleMessage: E msg.what=131167
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  946): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  946): Build Date: 03/09/15 Mon
I/Adreno-EGL(  946): Local Branch: 
I/Adreno-EGL(  946): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  946): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  946):                  d74aa161a12b9c6fc6332151
,E/WifiStateMachine(  946):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: DefaultState
,E/WifiStateMachine(  946):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  946):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
,W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
,D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1322): SET_SCREEN_ON:On
I/wpa_supplicant( 1322): htc_wext_set_keepalive +
I/wpa_supplicant( 1322): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1322): getPrivFuncNum +	
I/wpa_supplicant( 1322): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1322): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1322): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1322): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1322): htc_wext_set_TX_TRACKING - ret = 0
,E/WifiStateMachine(  946): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  946): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  946): handleScreenStateChanged Exit: true
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131154
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
V/SRS_Proc(  401): ParamSet string: screen_state=on
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  946): handleMessage: E msg.what=155650
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,D/NetworkPolicy(  946): updateScreenOn: false
V/NetworkPolicy(  946): updateIfacesLocked()
,D/NetworkManagementService(  946): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/GpsLocationProvider(  946): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/wpa_supplicant( 1322): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131127
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
,E/WifiStateMachine(  946): processMsg: ConnectModeState,
,E/WifiStateMachine(  946):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131129
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
,E/WifiStateMachine(  946):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1322): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1322): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  946): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  946): handleMessage: X
,I/ActivityManager(  946): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6964 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
I/IntentController( 1223): receive(android.intent.action.SCREEN_ON,1,false)
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 25 num clients 8
,D/XAN-DPS (  946): prepareColorFade done,
D/XAN-DPS (  946): setBrightness to 0
W/ContextImpl( 6964): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  946): acquireWL(31f84cc7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1827 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(170782f4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1827 10024 WorkSource{10024 com.google.android.gms}
,I/SensorManager(  946): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@f17f9e2
I/DisplayManagerService(  946): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed
V/ActivityManager(  946): Display changed displayId=0
W/SensorService(  946): disable: get sensor name = CM32181 Light sensor
,D/DotMatrix( 1333): [EventService]  onDisplayChanged: 0
W/SensorService(  946): pid=946, uid=1000
W/SensorService(  946): Active sensors: size = 3
W/SensorService(  946): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  946): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@f17f9e2, eanble = 0, strlen(mName) = 66
W/SensorService(  946): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  946): Listener[0] = com.htc.smartdim.sensor_eye@31d75da4
W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/ContextImpl( 6964): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
,D/DotMatrix( 1333): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/PMS     (  946): releaseWL(170782f4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(31f84cc7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 6964): MY_DEBUG = false
,D/SmartSyncUtils( 6964): isEpsOn(), nState = 0
,D/PMS     (  946): acquireWL(111f9492): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6964 1000 null
,D/PMS     (  946): releaseWL(111f9492): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/AlarmManager(  946): ACTION_SCREEN_OFF
,I/AlarmManager(  946): [AlarmQueuing] screen off now: 
I/AlarmManager(  946): [AlarmQueuing] data connection: true
,I/AlarmManager(  946): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 25
,D/WifiDataStallTracker(  946): stopDataStallAlarm 
E/WifiDataStallTracker(  946): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  946): handleMessage: E msg.what=131167
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
,D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
E/WifiStateMachine(  946):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1322): SET_SCREEN_ON:Off
,I/wpa_supplicant( 1322): htc_wext_set_keepalive +
I/wpa_supplicant( 1322): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1322): getPrivFuncNum +	
I/wpa_supplicant( 1322): getPrivFuncNum -, cmd = 0x8bf6
D/NetworkPolicy(  946): updateScreenOn: false
I/wpa_supplicant( 1322): htc_wext_set_keepalive fnum = 0x8bf6
V/NetworkPolicy(  946): updateIfacesLocked()
I/wpa_supplicant( 1322): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1322): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1322): htc_wext_set_keepalive - ret = 0
V/SRS_Proc(  401): ParamSet string: screen_state=off
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  946): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  946): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  946): handleScreenStateChanged Exit: false
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131154
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  946): handleMessage: X
D/WifiController(  946): handleMessage: E msg.what=155651
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/NetworkManagementService(  946): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiController(  946): handleMessage: X
,I/SensorManager( 1223): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@30d83aa1, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  946): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  946): pid=1223, uid=10041,
W/SensorService(  946): Active sensors: size = 4
W/SensorService(  946): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  946): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@30d83aa1, eanble = 1, strlen(mName) = 57
W/SensorService(  946): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  946): Listener[0] = com.htc.smartdim.sensor_eye@31d75da4
W/SensorService(  946): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@30d83aa1
W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1333): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  946): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/ContactMessageStore( 1565): start background delete task...
I/IntentController( 1223): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1565): size: 0 , 0
D/ContactMessageStore( 1565): Background delete complete
,W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  946): Init customizeScreenOffDelayClass error
D/PMS     (  946): acquireWL(24a2ee63): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1827 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): releaseWL(24a2ee63): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(193da60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1827 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(193da60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6964): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6964): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6964): isEpsOn(), nState = 0
D/SmartSyncUtils( 6964): isEpsOn(), nState = 0
,W/ContextImpl( 6964): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,I/RemoteViews( 1223): setHTCTheme(com.htc.updater,true,33751145),
W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
D/AutoSetting( 1541): service - mHandler: cancel location update
D/AutoSetting( 1541): service -           changes count: 0
I/SensorManager(  946): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@31d75da4
W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  946): disable: get sensor name = Accelerometer Sensor
W/SensorService(  946): pid=946, uid=1000
W/SensorService(  946): Active sensors: size = 3
W/SensorService(  946): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@31d75da4, eanble = 0, strlen(mName) = 36
,W/SensorService(  946): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  946): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@30d83aa1
W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  946): disable: get sensor name = CM36686 Proximity sensor
I/RemoteViews( 1223): apply : com.htc.updater 0 11 0 36
W/SensorService(  946): pid=946, uid=1000
W/SensorService(  946): Active sensors: size = 2
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@31d75da4, eanble = 0, strlen(mName) = 36
W/SensorService(  946): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  946): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@30d83aa1
W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  946): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@31d75da4
,E/ActivityThread(  946): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@2813070d that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  946): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@2813070d that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  946): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  946): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  946): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  946): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  946): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  946): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  946): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  946): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  946): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  946): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  946): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  946): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  946): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  946): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  946): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  946): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  946): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  946): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  946): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6998 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/PowerUsageList:PowerUsageHelper( 6964): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6964): gen(), null == sipper.uidObj, userId = 0
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  946): Setting HAL interactive mode to false
D/SurfaceControl(  946): Excessive delay in setPowerMode(): 294ms
D/PMS     (  946): Setting HAL interactive mode to false done
W/HtcSystemUPManager(  946): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  946): Setting HAL auto-suspend mode to true
D/PMS     (  946): Setting HAL auto-suspend mode done
I/InputMethodManagerService(  946): screenObserver, isScreenOn=false
D/StatusBarManagerService(  946): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  946): Disable input method client, pid=6434
,I/InputMethodManager( 6434): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{7094bd3 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2515048a
D/HABCtrl (  946): TPE algorithm. remove timeout.
D/PMS     (  946): OOBE c monitor 11
,I/InputManager(  946): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
I/IntentController( 1223): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/PMS     (  946): acquireWL(39cc0dbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(39cc0dbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  946): updateBatteryInfo
D/PowerUI ( 1223): closing low battery warning: level=97
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PMS     (  946): runPSCheck
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): handleMessage: E msg.what=155652
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  946): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,D/NfcService( 1582): ScreenObserver: OFF
,D/NfcService( 1582): applyRouting - 0
,D/PMS     (  946): acquireWL(28cc3c8c): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1582 1027 null
,D/NfcService( 1582): applyRouting -2
D/NfcService( 1582): applyRouting
D/NfcService( 1582): Ignore this applyRouting...
,D/PMS     (  946): releaseWL(28cc3c8c): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/Process (  946): killProcessQuiet, pid=6547
I/ActivityManager(  946): Killing 6547:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6964): getMobilePolicyEnabled, result = true
,D/WifiService(  946): New client listening to asynchronous messages
,E/WifiTrafficPoller(  946): ADD_CLIENT: 9
,I/ClockController( 1223): stop clock update:screen off
,I/BatteryController( 1223): status:2 level:97 unsupport:false plugged:true
,I/ActivityManager(  946): Recipient 6547
,D/PowerUsageList:PowerUsageHelper( 6964): MY_DEBUG = false
,I/ActivityManager(  946): Killing 6628:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  946): killProcessQuiet, pid=6628
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6628
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL false Token 26 num clients 9
,E/WifiDataStallTracker(  946): DATA_MONITOR_POLL false Token 5
,D/PMS     (  946): releaseWL(22f5032b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-935672917] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-935672916] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946): handleMessage: X
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:623] from screen [on:0 period:-935672292] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-935672290] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946): handleMessage: X
,D/HtcUPManager( 1223): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  946): DATA_MONITOR_POLL false Token 5
,D/ContactMessageStore( 1565): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1565): MSG_NOTIFY_CS_TO_SYNC <<,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  946): Killing 5541:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  946): killProcessQuiet, pid=5541
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 5541
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 2
,E/WifiStateMachine(  946): handleMessage: E msg.what=131165,
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  946): processMsg: DefaultState
,E/WifiStateMachine(  946):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  946): handleMessage: X
,D/PMS     (  946): acquireWL(39b09fd5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000},
V/AlarmManager(  946): sending alarm PendingIntent{3df93fc7: PendingIntentRecord{2f78f9f4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=135284, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{14a523ea: PendingIntentRecord{c3dc6db com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143738, Int=0
,D/PMS     (  946): releaseWL(39b09fd5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/AutoSetting( 1541): service - handleMessage() stop self,
D/AutoSetting( 1541): service - onDestroy() END,
D/AutoSetting( 1541): service - handleMessage() quit looper,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  946): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  946): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  946): acquireWL(31469578): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 946 1000 null
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  946): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  946): [NET] android_getaddrinfo_proxy+
D/libc    (  946): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  946): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  946): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  946): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  946): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  946):  [handleDownloadXtraData]inject done.
,D/PMS     (  946): acquireWL(310b9124): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 946 1000 null,
D/GpsLocationProvider(  946): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  946): releaseWL(31469578): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/PMS     (  946): releaseWL(310b9124): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/WifiStateMachine(  946): handleMessage: E msg.what=131326
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState what:131326 2 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  946): handleMessage: X
,W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  946): acquireWL(dfdf48d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(dfdf48d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  946): updateBatteryInfo
,D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/NotificationService(  946): plugged=true pluggin=true,
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/PMS     (  946): runPSCheck
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DeviceActiveState
I/HtcPowerSaver(  946): updateStatus (8000,97,-1,false,false,false,-1)
D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): << updateStatus
D/WifiController(  946): processMsg: DefaultState
D/PowerUI ( 1223): closing low battery warning: level=97
D/WifiController(  946): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:2 level:97 unsupport:false plugged:true,
,D/TelephonyReceiver( 1565): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  946): acquireWL(7b24642): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{1000},
,V/AlarmManager(  946): sending alarm PendingIntent{315c3653: PendingIntentRecord{34029b90 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455058292049, Int=0
D/PMS     (  946): acquireWL(11e24c89): PARTIAL_WAKE_LOCK  *backup* 0x1 946 1000 null
V/AlarmManager(  946): sending alarm PendingIntent{3df93fc7: PendingIntentRecord{2f78f9f4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=195284, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{ba2848e: PendingIntentRecord{c69e4af android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=199035, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{1b1de0bc: PendingIntentRecord{339a2845 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189875, Int=0
,D/PMS     (  946): acquireWL(1b465b9a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
W/BackupManagerService(  946): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  946): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  946): releaseWL(11e24c89): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  946): releaseWL(7b24642): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  946): acquireWL(3ffa1ccb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(1b465b9a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  946): releaseWL(3ffa1ccb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): acquireWL(ba21afd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(ba21afd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(34ecc3f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(2baf5a43): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): acquireWL(1f7a69f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): releaseWL(34ecc3f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(2263579f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(2263579f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1855): Vacuum at: now=1455058324099 tag=VacuumService
,D/PMS     (  946): releaseWL(2baf5a43): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): acquireWL(cf8f0ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms},
I/GoogleURLConnFactory( 1855): Using platform SSLCertificateSocketFactory
,W/Uploader( 1855): No account for auth token provided,
,D/PMS     (  946): releaseWL(cf8f0ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(21eeacb5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(21eeacb5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1855): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1855): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1855): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1855): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1855): [NET] android_getaddrinfo_proxy+
D/libc    ( 1855): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1855): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1855): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1855): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 1855): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1855): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1855): No account for auth token provided,
,W/Uploader( 1855): No account for auth token provided,
,W/Uploader( 1855):  no longer exists, so no auth token.,
,W/Uploader( 1855): No account for auth token provided
,I/GLSUser ( 1855): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1855): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1855): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1855): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40,
,E/Uploader( 1855): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1855): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1855): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1855): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1855): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1855): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1855): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1855): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1855): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1855): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1855): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1855): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1855): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1855): No account for auth token provided,
,D/PMS     (  946): releaseWL(1f7a69f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): acquireWL(38ccc369): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(38ccc369): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  946): acquireWL(1eef61ee): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(1eef61ee): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1541): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@30656ba3
D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  946): Killing 6489:com.google.android.gms.unstable/u0a24 (adj 15): empty #17,
D/Process (  946): killProcessQuiet, pid=6489
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6489
,D/PMS     (  946): acquireWL(7d7668f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(7d7668f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  946): updateBatteryInfo
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=98
,D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/PMS     (  946): runPSCheck
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,I/HtcPowerSaver(  946): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus,
,I/BatteryController( 1223): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6434): --= Surplus to requirements =--
I/jxcore-log( 6434): 
,I/jxcore-log( 6434): ****TEST TOOK:  ms ****
I/jxcore-log( 6434): 
I/jxcore-log( 6434): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6434): 
,E/cutils-trace( 7038): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 7038): ====startRecUseTime====,
D/htc.customization.log.level( 7038):  is 
W/CustomizationLogLevel( 7038): Level value is invalid, use default level 2
,D/CustomizationManager( 7038):  Read ACC file spent 0.048 (s),
,D/CIDMapFileReader( 7038): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7038): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7038): Parsing tag item name = HTC__Y13
,D/CIDMapFileReader( 7038): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7038): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7038): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7038): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 7038): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 7038): Parsing tag category name = system
,I/CustomizationCIDLoader( 7038): Parsing tag category name = application
I/CustomizationCIDLoader( 7038): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7038): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7038): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7038): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7038): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 7038): add string-array item, value = 42507
,I/CustomizationCIDLoader( 7038): add string-array item, value = 21902
I/CustomizationCIDLoader( 7038): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7038): add string-array item, value = 23420
I/CustomizationCIDLoader( 7038): add string-array item, value = 22299
I/CustomizationCIDLoader( 7038): add string-array item, value = 24002
I/CustomizationCIDLoader( 7038): add string-array item, value = 23210
I/CustomizationCIDLoader( 7038): add string-array item, value = 23205
I/CustomizationCIDLoader( 7038): add string-array item, value = 23806
I/CustomizationCIDLoader( 7038): add string-array item, value = 23430
I/CustomizationCIDLoader( 7038): add string-array item, value = 23408
I/CustomizationCIDLoader( 7038): add string-array item, value = 27205
I/CustomizationCIDLoader( 7038): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 24002:D:0:0,
I/CustomizationCIDLoader( 7038): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7038): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7038):  Read CID file spent 0.096 (s)
D/CustomizationManager( 7038):  All configurations done spent 0.096 (s)
,D/PackageManager(  946): deletePackageAsUser: pkg=com.test.thalitest, pid=7038, uid=2000 userid=0,
,I/ActivityManager(  946): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  946): Killing 6434:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
,D/Process (  946): killProcessQuiet, pid=6434
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  946): Skipping PackageSetting{2d154c10 com.example.hello/10374} due to missing metadata,
,E/libprocessgroup(  946): failed to kill 1 processes for processgroup 6434
,I/WindowState(  946): WIN DEATH: Window{1ce33662 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  946): Client connection lost with reason: 4
I/ActivityManager(  946):   Force finishing activity ActivityRecord{3b88d377 u0 com.test.thalitest/.MainActivity t8}
E/InputEventReceiver( 1399): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{391c33f3 uid 10366 pid 6434} (c)'
,I/ActivityManager(  946): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
,D/DotMatrix( 1333): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
D/DotMatrix( 1333): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/PMS     (  946): acquireWL(23652d25): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1827 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/PMS     (  946): releaseWL(23652d25): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/SystemReader(  946): Cannot find grip_rejection_width, use default value instead
W/GeofencerStateMachine( 1827): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1766): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1766): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PhoneApp( 1565): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
,D/AccTypeManager( 1766): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/VoicemailCleanupService( 1723): Cleaning up data for package: com.test.thalitest
I/[PluginManager]RegisterService( 1541): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/art     ( 1627): Explicit concurrent mark sweep GC freed 23139(1384KB) AllocSpace objects, 6(468KB) LOS objects, 34% free, 29MB/45MB, paused 1.012ms total 117.655ms
,D/Prism.PackageStateRece_( 1627): action: android.intent.action.PACKAGE_REMOVED
,I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,E/ExternalAccountType( 1766): Unsupported attribute readOnly
,I/ActivityManager(  946): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7058 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
I/Launcher( 1627): Deferring update until onResume
D/Launcher( 1627): waitUntilResume // bindAppsRemoved
,I/[PluginManager]RegisterService( 1541): handle notify Blinkfeed plugin client changed
,I/InputMethodManagerService(  946): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/ResourcesManager(  946): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/art     (  946): Explicit concurrent mark sweep GC freed 45049(2MB) AllocSpace objects, 7(1200KB) LOS objects, 33% free, 19MB/28MB, paused 12.053ms total 249.620ms
,I/art     (  946): WaitForGcToComplete blocked for 218.186ms for cause Explicit
,W/ContextImpl( 7058): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 ,
,D/StatusBarManagerService(  946): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,D/StatusBarManagerService(  946): hiding MENU key
,D/StatusBarManagerService(  946): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  946): hiding MENU key
,D/FindExtension( 1627): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1627): Defer allocateBuffers to drawing time,
,W/InputMethodManagerService(  946): Got RemoteException sending setActive(false) notification to pid 6434 uid 10366
,D/StatusBarManagerService(  946): swetImeWindowStatus vis=0 backDisposition=0
,E/NetworkScheduler.SchedulerReceiver( 1855): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1855): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?,
,D/PMS     (  946): acquireWL(12ea8203): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1855 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): releaseWL(12ea8203): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/PackageManager(  946): Unable to load service info ResolveInfo{216b24f1 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  946): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  946): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  946): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  946): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  946): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  946): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  946): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  946): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  946): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  946): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  946): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  946): Killing 6761:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  946): killProcessQuiet, pid=6761
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/JobSchedulerService(  946): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  946): Explicit concurrent mark sweep GC freed 9055(518KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 18MB/28MB, paused 2.504ms total 251.399ms
,I/ActivityManager(  946): Recipient 6761
,D/TaskPersister(  946): removeObsoleteFile: deleting file=8_task.xml,
D/TaskPersister(  946): removeObsoleteFile: deleting file=8_task_thumbnail.png
,D/PackageBroadcastService( 4451): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 4451): Clearing selected account for com.test.thalitest,
,D/ChimeraCfgMgr( 4451): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4451): Module APK com.google.android.play.games already loaded
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
,D/ChimeraCfgMgr( 4451): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4451): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  946): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7093 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/LocationSettingsChecker( 4451): Removing dialog suppression flag for package com.test.thalitest
,D/GOOGLEHELP_CompatibleDatabase( 4451): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1,
D/GOOGLEHELP_CompatibleDatabase( 4451): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4451): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4451): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4451): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4451): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 4451): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4451): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 4451): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 4451): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/PMS     (  946): acquireWL(c337e9c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4451 10024 null
D/GOOGLEHELP_CompatibleDatabase( 4451): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,I/ConfigFetchService( 4451): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
D/GOOGLEHELP_CompatibleDatabase( 4451): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4451): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ConfigService( 1855): onCreate,
,D/PMS     (  946): releaseWL(c337e9c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,W/BaseAppContext( 4451): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 4451): CP2 sync disabled
,D/PMS     (  946): acquireWL(24c4646): PARTIAL_WAKE_LOCK  Icing 0x1 4451 10024 WorkSource{10024 com.google.android.gms}
I/Icing   ( 4451): doRemovePackageData com.test.thalitest
,D/PMS     (  946): releaseWL(24c4646): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/BaseAppContext( 4451): Using Auth Proxy for data requests.
I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4451, uid=10024, userID:0
,W/DriveInitializer( 4451): Awaiting to be initialized
,W/DriveInitializer( 4451): Background init thread started,
,E/SQLiteDBG( 4451): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55ab0ba6b0,
,E/DocListDatabase( 4451): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 4451): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/DocListDatabase( 4451): ,	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4451): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/DocListDatabase( 4451): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4451): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4451): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/DocListDatabase( 4451): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 4451): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 4451): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 4451): Background init thread ended
E/AndroidRuntime( 4451): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4451): Process: com.google.android.gms, PID: 4451
E/AndroidRuntime( 4451): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 4451): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4451): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 4451): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4451): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4451): ,	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 4451): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 4451): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 4451): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,E/SQLiteLog( 4451): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4451): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55ab0ba6b0
E/ActivityManager(  946): App crashed! Process: com.google.android.gms
E/DriveAsyncService( 4451): disk I/O error (code 3850)
E/DriveAsyncService( 4451): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4451): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4451): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4451): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4451): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4451): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4451): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/DriveAsyncService( 4451): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4451): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
,E/DriveAsyncService( 4451): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4451): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4451): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 4451): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4451): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4451): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 4451): killProcess, pid=4451
,D/Process ( 4451): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  946): Can't write: system_app_crash,
E/DropBoxManagerService(  946): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  946): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72),
E/DropBoxManagerService(  946): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  946): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  946): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  946): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  946): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  946): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  946): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  946): 	... 5 more
,I/GAv4    ( 7093): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7093):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7093):   adb logcat -s GAv4
,W/GAv4    ( 7093): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7093): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/ActivityManager(  946): Recipient 4451
D/WifiService(  946): Client connection lost with reason: 4
,I/ConfigService( 1855): onDestroy,
I/ActivityManager(  946): Process com.google.android.gms (pid 4451) has died
W/ActivityManager(  946): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  946): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms,
W/ActivityManager(  946): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,W/GAv4    ( 7093): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 7093): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,E/SQLiteDatabase( 7093): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7093): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7093): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7093): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7093): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7093): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7093): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7093): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7093): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7093): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7093): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7093): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 7093): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7093): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7093): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834),
,E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7093): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7093): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7093): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7093): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7093): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7093): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7093): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7093): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/SQLiteDatabase( 7093): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7093): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7093): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7093): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7093): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7093): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7093): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7093): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7093): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7093): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7093): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7093): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7093): 	at aen.run(PG:536)
,I/ActivityManager(  946): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=7135 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 7135): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7135): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/VoldConnector(  946): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 7093): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache,
,E/SQLiteDatabase( 7093): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7093): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7093): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7093): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7093): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7093): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7093): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7093): 	at aej.c(PG:139)
E/SQLiteDatabase( 7093): 	at aej.b(PG:398),
E/SQLiteDatabase( 7093): 	at agf.f(PG:417)
E/SQLiteDatabase( 7093): 	at oe.run(PG:1112)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/SQLiteDatabase( 7093): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7093): 	at java.lang.Thread.run(Thread.java:818)
I/MultiDex( 7135): VM with version 2.1.0 has multidex support
I/MultiDex( 7135): install
I/MultiDex( 7135): VM has multidex support, MultiDex support library is disabled.
D/PMS     (  946): acquireWL(1765582a): PARTIAL_WAKE_LOCK  AsyncService 0x1 6251 10167 null
,E/AbstractDatabaseInstance( 7093): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 7093): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7093): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7093): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7093): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7093): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7093): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7093): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7093): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 7093): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 7093): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 7093): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 7093): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7093): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7093): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7093): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 7093): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7093): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  946): releaseWL(1765582a): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  946): acquireWL(20a83b8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6251 10167 null
,D/PMS     (  946): releaseWL(20a83b8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 6875): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,V/JNIHelp ( 7093): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/Prism.ItemManager( 1627): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1627): loadItems() com.htc.launcher.pageview.WidgetManager@d5e12b0 +
I/Prism.WidgetManager( 1627): onLoadItems() +
I/ActivityManager(  946): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=7166 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,E/SQLiteDatabase( 7135): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.,
E/SQLiteDatabase( 7135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7135): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 7135): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 7135): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 7135): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7135): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7135): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231),
E/SQLiteDatabase( 7135): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7135): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7135): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7135): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 7135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7135): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 7135): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 7135): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 7135): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7135): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7135): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7135): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7135): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7135): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 1627): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,E/SQLiteLog( 6875): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 6875): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55aae838e0
,W/System  ( 7093): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7093): Installed default security provider GmsCore_OpenSSL
,E/SQLiteDatabase( 7093): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7093): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7093): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7093): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7093): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7093): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7093): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7093): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7093): 	at aej.c(PG:139)
E/SQLiteDatabase( 7093): 	at aej.a(PG:358)
E/SQLiteDatabase( 7093): 	at aej.a(PG:345)
E/SQLiteDatabase( 7093): 	at agf.c(PG:884)
E/SQLiteDatabase( 7093): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 7093): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7093): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7093): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7093): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 7093): Failed to query Account133 object
E/AbstractDatabaseInstance( 7093): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7093): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7093): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7093): 	at ,aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7093): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7093): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7093): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7093): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 7093): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 7093): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 7093): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 7093): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 7093): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7093): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 7093): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7093): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7093): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  946): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=7192 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,V/GLSActivity( 1855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DeviceManagement( 7166): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7166 dbg=false s=true
,E/SharedPreferencesImpl( 6875): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
I/DeviceManagement( 7166): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,E/AndroidRuntime( 6875): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6875): Process: com.google.android.googlequicksearchbox:search, PID: 6875
E/AndroidRuntime( 6875): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6875): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6875): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 6875): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6875): ,	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298),
E/AndroidRuntime( 6875): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 6875): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 6875): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 6875): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 6875): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 6875): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 6875): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 6875): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 6875): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 6875): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 6875): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 6875): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
,E/AndroidRuntime( 6875): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6875): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6875): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6875): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 7166): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
E/DropBoxManagerService(  946): Can't write: system_app_crash
E/DropBoxManagerService(  946): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  946): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  946): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  946): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  946): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  946): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  946): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  946): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  946): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  946): 	... 5 more
E/ActivityManager(  946): App crashed! Process: com.google.android.googlequicksearchbox:search
,I/DeviceManagement( 7166): WorkflowService: Starting workflow service
,V/JNIHelp ( 7135): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/DeviceManagement( 7166): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@3a24aa47] args=[Bundle[mParcelledData.dataSize=112]]
I/DeviceManagement( 7166): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 7166): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 7166): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 7166): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  946): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7218 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
,D/Process ( 6875): killProcess, pid=6875
D/Process ( 6875): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
,W/ActivityThread( 7135): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/DeviceManagement( 7166): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,W/System  ( 7135): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19668082: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7135): Installed default security provider GmsCore_OpenSSL
,I/DeviceManagement( 7166): SessionStateController: Checking invariants...,
,W/NativeLibraryUtils( 7135): Failed to open lock file
W/NativeLibraryUtils( 7135): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7135): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7135): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7135): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7135): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7135): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7135): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7135): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7135): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7135): 	... 3 more
,I/GAv4-SVC( 7135): Google Analytics 7.8.99 is starting up.,
,I/ActivityManager(  946): Recipient 6875
,I/ActivityManager(  946): Process com.google.android.googlequicksearchbox:search (pid 6875) has died
,W/ActivityManager(  946): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,E/SQLiteDatabase( 7218): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.,
E/SQLiteDatabase( 7218): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7218): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7218): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
E/SQLiteDatabase( 7218): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7218): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 7218): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 7218): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 7218): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 7218): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 7218): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 7218): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 7218): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 7218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7218): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7218): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7218): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7218): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7218): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7218): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7218): FATAL EXCEPTION: main
E/AndroidRuntime( 7218): Process: com.android.documentsui, PID: 7218
E/AndroidRuntime( 7218): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7218): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 7218): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 7218): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 7218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7218): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7218): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7218): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7218): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7218): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7218): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7218): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7218): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7218): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRunti,me( 7218): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7218): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7218): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 7218): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 7218): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 7218): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 7218): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 7218): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 7218): 	... 9 more
,I/art     ( 1855): Explicit concurrent mark sweep GC freed 24214(1379KB) AllocSpace objects, 9(500KB) LOS objects, 48% free, 4MB/8MB, paused 893us total 43.752ms
,I/ActivityManager(  946): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=7246 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,E/ActivityManager(  946): App crashed! Process: com.android.documentsui
,D/ErrorReport(  946): HtcErrorReportManager Begin---add error logs to dropbox
,W/System.err(  946): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
,W/System.err(  946): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ResourcesManager( 1627): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/System.err(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  946): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  946): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  946): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  946): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  946): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  946): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  946): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  946): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  946): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  946): 	at libcore.io.Posix.open(Native Method)
W/System.err(  946): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  946): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  946): 	... 12 more
W/System.err(  946): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  946): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  946): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  946): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  946): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  946): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  946): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  946): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  946): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  946): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  946): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  946): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  946): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  946): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  946): 	at libcore.io.Posix.open(Native Method)
W/System.err(  946): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  946): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  946): 	... 14 more
,E/SQLiteDatabase( 7166): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7166): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7166): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7166): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 7166): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 7166): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 7166): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 7166): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7166): ,	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 7166): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7166): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 7166): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7166): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 7166): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 7166): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 7166): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7166): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7166): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7166): 	at java.lang.Thread.run(Thread.java:818)
I/DeviceManagement( 7166): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(  946): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  946): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  946): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  946): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  946): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  946): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  946): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  946): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  946): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  946): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  946): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  946): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  946): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System.err(  946): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  946): 	at libcore.io.Posix.open(Native Method)
W/System.err(  946): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  946): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  946): 	... 14 more
I/DeviceManagement( 7166): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 7166): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,E/SQLiteDatabase( 7166): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7166): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185),
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7166): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7166): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7166): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 7166): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 7166): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 7166): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 7166): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
,E/SQLiteDatabase( 7166): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 7166): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7166): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7166): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7166): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 7166): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@3a24aa47]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/DeviceManagement( 7166): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
W/DeviceManagement( 7166): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/DeviceManagement( 7166): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 7166): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 7166): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283),
W/DeviceManagement( 7166): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 7166): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 7166): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 7166): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 7166): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 7166): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 7166): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 7166): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  946): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=7269 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a
,I/DeviceManagement( 7166): WorkflowService: Stopping workflow service
,W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7093): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,I/ActivityManager(  946): Killing 6821:com.android.chrome/u0a96 (adj 15): empty #17
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/ErrorReport(  946): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  946): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455058398609.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  946): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  946): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  946): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  946): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  946): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  946): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  946): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  946): 	... 4 more
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/Process (  946): killProcessQuiet, pid=6821
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  440): Explicit concurrent mark sweep GC freed 8660(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 185us total 24.789ms
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7093): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 7093): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 7246): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/GAv4    ( 7093): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 7093): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 7093): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 7093): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 7093): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 7093): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7093): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7093): 	at aen.run(PG:536)
E/GAv4    ( 7093): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7093): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7093): Job execution failed: android.database.sqlite.SQLiteExcepti,on: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7093): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7093): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7093): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7093): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 7093): java.lang.RuntimeException: An error occured while executing doInBackground()
E/CAKEMIX_CRASHED( 7093): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/CAKEMIX_CRASHED( 7093): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/CAKEMIX_CRASHED( 7093): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/CAKEMIX_CRASHED( 7093): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/CAKEMIX_CRASHED( 7093): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/CAKEMIX_CRASHED( 7093): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/CAKEMIX_CRASHED( 7093): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/CAKEMIX_CRASHED( 7093): 	at java.lang.Thread.run(Thread.java:818)
E/CAKEMIX_CRASHED,( 7093): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 7093): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 7093): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 7093): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 7093): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 7093): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7093): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7093): 	at aej.c(PG:139)
E/CAKEMIX_CRASHED( 7093): 	at aej.a(PG:358)
E/CAKEMIX_CRASHED( 7093): 	at aej.a(PG:345)
E/CAKEMIX_CRASHED( 7093): 	at agf.c(PG:884)
E/CAKEMIX_CRASHED( 7093): 	at aii.doInBackground(PG:1063)
E/CAKEMIX_CRASHED( 7093): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/CAKEMIX_CRASHED( 7093): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/CAKEMIX_CRASHED( 7093): 	... 4 more
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7093): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/art     (  440): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 155us total 23.021ms
I/art     (  440): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 170us total 17.827ms
,W/asset   ( 1627): Copying FileAsset 0x55ab311070 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,D/PhoneApp( 1565): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1565): -- N1 =0
D/PhoneApp( 1565): -- N2 =0
D/PhoneApp( 1565): -- N3 =0
,I/ActivityManager(  946): Recipient 6821
,I/ActivityManager(  946): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 7093 on display 0,
,E/SQLiteDatabase( 7135): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 7135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7135): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7135): 	,at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7135): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 7135): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 7135): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 7135): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 7135): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 7135): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 7135): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 7135): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7135): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7135): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7135): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7135): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7135): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 7135): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 7135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 7135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 7135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7135): 	,at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7135): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 7135): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 7135): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 7135): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 7135): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 7135): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 7135): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 7135): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 7135): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7135): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 7135): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7135): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7135): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 7135): Opened reminders.db in read-only mode
,D/DotMatrix( 1333): [EventService]  onDisplayChanged: 0
,D/DotMatrix( 1333): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  946): Display changed displayId=0
,E/Prism.WidgetManager( 1627): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1627): onLoadItems() -
I/Prism.ItemManager( 1627): loadItems() com.htc.launcher.pageview.WidgetManager@d5e12b0 -
,E/SQLiteLog( 1627): (3850) statement aborts at 16: [DELETE FROM externalapp WHERE package_name='com.test.thalitest'] disk I/O error,
E/SQLiteDBG( 1627): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/externalapp.db, handle: 0x55aae60bc0
,W/System.err( 1627): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,D/Process ( 7093): killProcess, pid=7093
```
