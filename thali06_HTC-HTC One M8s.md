#### Test 57659382b63fd0b_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  931): handleMessage: E msg.what=131326
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !what:131326 1 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !what:131326 1 0
E/WifiStateMachine(  931): handleMessage: X
E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6
--------- beginning of system
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=339
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  931): notifying of data activity 0
I/HtcModeClient( 3152): handler message = 4011
E/HtcModeClient( 3152): Check connection and retry 12 times.
E/WifiStateMachine(  931): handleMessage: E msg.what=131155
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1911279029] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1911279028] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931):  get link layer stats 0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1369): environment dirty rate=0 [0][0][0]
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  931): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  931): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.21 txretriesrate=0.00 rxrate=1.21 userTriggerdPenalty0
E/WifiStateMachine(  931):  good link -> stuck count =0
E/WifiStateMachine(  931):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  931):  isHighRSSI       ---> score=61
E/WifiStateMachine(  931): handleMessage: X
D/WifiWatchdogStateMachine(  931): RSSI current: 3 new: -60, 3
,E/cutils-trace( 6299): Error opening trace file: Permission denied (13)
E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=339
D/CustomizationManager( 6299): ====startRecUseTime====
D/htc.customization.log.level( 6299):  is 
W/CustomizationLogLevel( 6299): Level value is invalid, use default level 2
D/CustomizationManager( 6299):  Read ACC file spent 0.044 (s)
D/CIDMapFileReader( 6299): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6299): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6299): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6299): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6299): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6299): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6299): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6299): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6299): Parsing tag category name = system
I/CustomizationCIDLoader( 6299): Parsing tag category name = application
I/CustomizationCIDLoader( 6299): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6299): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6299): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6299): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6299): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6299): add string-array item, value = 42507
I/CustomizationCIDLoader( 6299): add string-array item, value = 21902
I/CustomizationCIDLoader( 6299): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6299): add string-array item, value = 23420
I/CustomizationCIDLoader( 6299): add string-array item, value = 22299
I/CustomizationCIDLoader( 6299): add string-array item, value = 24002
I/CustomizationCIDLoader( 6299): add string-array item, value = 23210
I/CustomizationCIDLoader( 6299): add string-array item, value = 23205
I/CustomizationCIDLoader( 6299): add string-array item, value = 23806
I/CustomizationCIDLoader( 6299): add string-array item, value = 23430
I/CustomizationCIDLoader( 6299): add string-array item, value = 23408
I/CustomizationCIDLoader( 6299): add string-array item, value = 27205
I/CustomizationCIDLoader( 6299): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6299): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6299):  Read CID file spent 0.090 (s)
D/CustomizationManager( 6299):  All configurations done spent 0.090 (s)
I/ActivityManager(  931): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6299 on display 0
D/PMS     (  931): acquireHCC(cd206ca): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 931 1000 null
D/PMS     (  931): acquireHCC(3dbaa03b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 931 1000 null
W/asset   (  931): Copying FileAsset 0x556a82c740 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  931): acquireWL(1671c596): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 931 1000 null
I/FeedHostManager( 1489): [onPause]
I/AnimationUtil(  931): isHTCRecent(ThaliTest/Recent screens.)/7
I/FeedProviderManager( 1489): onPause
I/FeedHostManager( 1489): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@1fdb2a23
I/SocialFeedProvider( 1489): +onPause
I/SocialFeedProvider( 1489): -onPause
W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  931): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6317 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  931): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  931): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  931): hiding MENU key
W/asset   ( 6317): Copying FileAsset 0xac2a78e8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1489): [trimMemory] 20
I/WebViewFactory( 6317): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6317): Time to load native libraries: 9 ms (timestamps 1212-1221)
I/LibraryLoader( 6317): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6317): Binding Chromium to main looper Looper (main, tid 1) {19a7bba3}
I/LibraryLoader( 6317): Expected native library version number "",actual native library version number ""
I/chromium( 6317): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6317): Initializing chromium process, singleProcess=true
W/art     ( 6317): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6317): ApplicationContext is null in ApplicationStatus
W/chromium( 6317): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6317): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6317): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6317): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6317): Local Branch: 
I/Adreno-EGL( 6317): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6317): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6317):                  d74aa161a12b9c6fc6332151
W/System.err(  931): java.lang.Throwable: stack dump
W/System.err(  931): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  931): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  931): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  931): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  931): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  931): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bff6207:true
D/BluetoothAdapter( 6317): 812674815: getState(). Returning 12
W/art     ( 6317): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6317): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6317): CordovaWebView is running on device made by: HTC
W/art     ( 6317): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6317): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  931): Explicit concurrent mark sweep GC freed 40072(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.690ms total 163.631ms
E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=339
W/chromium( 6317): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6317): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
E/WifiDataStallTracker(  931): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  931): updateDataStallInfo: mDataStallTxRxSum={txSum=236 rxSum=239} preTxRxSum={txSum=236 rxSum=239}
D/WifiDataStallTracker(  931): updateDataStallInfo: NONE
D/WifiDataStallTracker(  931): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/InputMethodManager( 6317): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2885db85, mServedView=org.apache.cordova.engine.SystemWebView{17bf2dda VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2cfb220b
I/InputMethodManagerService(  931): Disable input method client, pid=1489
D/StatusBarManagerService(  931): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  931): Enable input method client, pid=6317
W/BindingManager( 6317): Cannot call determinedVisibility() - never saw a connection for the pid: 6317
I/ActivityManager(  931): Displayed com.test.thalitest/.MainActivity: +912ms
D/PMS     (  931): releaseWL(1671c596): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
W/XT9_C   ( 1378): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1378): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1378): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1378): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/JsMessageQueue( 6317): Set native->JS mode to OnlineEventsBridgeMode
D/PMS     (  931): acquireWL(2c9007c9): PARTIAL_WAKE_LOCK  *alarm* 0x1 931 1000 WorkSource{10072}
V/AlarmManager(  931): sending alarm PendingIntent{2a28bece: PendingIntentRecord{3ed031ef com.android.vending startService}}, i=null, t=0, cnt=1, w=1454082629819, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{3ee935b4: PendingIntentRecord{14e0e5dd android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454082636053, Int=20000
E/WifiStateMachine(  931): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  931): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  931):     Client/Owner: Client
D/WifiDisplayAdapter(  931):     GroupId: 
D/WifiDisplayAdapter(  931):     Passphrase: 
D/WifiDisplayAdapter(  931):     SessionId: 0
D/WifiDisplayAdapter(  931):     IP Address: }
E/WifiStateMachine(  931): handleMessage: E msg.what=131143
D/PMS     (  931): releaseWL(2c9007c9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):0 dur:2092 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.2 fiv=60000 [on:0 tx:0 rx:0 period:1728] from screen [on:0 period:-1911277284]
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:2092 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.2 fiv=60000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1911277283]
E/WifiStateMachine(  931): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.21 rxSuccessRate=1.21 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  931): WifiStateMachine CMD_START_SCAN with age=16191 interval=60000 maxinterval=300000
E/WifiStateMachine(  931): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  931): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  931): has c0:ff:d4:d3:aa:48 freq=2412 age=1733 ?=true
E/WifiStateMachine(  931): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1369): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1369): wpa_supplicant_scan enter
D/wpa_supplicant( 1369): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1369): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1369): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1369): WPS:  * Request Type
D/wpa_supplicant( 1369): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1369): WPS:  * UUID-E
D/wpa_supplicant( 1369): WPS:  * Primary Device Type
D/wpa_supplicant( 1369): WPS:  * RF Bands (3)
D/wpa_supplicant( 1369): WPS:  * Association State
D/wpa_supplicant( 1369): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1369): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1369): WPS:  * Manufacturer
D/wpa_supplicant( 1369): WPS:  * Model Name
D/wpa_supplicant( 1369): WPS:  * Model Number
D/wpa_supplicant( 1369): WPS:  * Device Name
D/wpa_supplicant( 1369): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1369): P2P: * P2P IE header
D/wpa_supplicant( 1369): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1369): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1369): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1369): wlan0: Add radio work 'scan'@0x5594507680
D/wpa_supplicant( 1369): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1369): wlan0: Starting radio work 'scan'@0x5594507680 after 0.000059 second wait
D/wpa_supplicant( 1369): wlan0: nl80211: scan request
D/wpa_supplicant( 1369): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1369): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1369): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1369): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1369): wlan0: Own scan request started a scan in 0.000103 seconds
I/wpa_supplicant( 1369): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  931): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  931): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  931): [1,454,082,636,065 ms] noteScanstart no scan source
E/WifiStateMachine(  931): handleMessage: X
,D/wpa_supplicant( 1369): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1369): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1369): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1369): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1369): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1369): wlan0: Scan completed in 0.071635 seconds
D/wpa_supplicant( 1369): nl80211: Associated on 2412 MHz
,D/wpa_supplicant( 1369): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1369): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1369): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1369): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-56
I/wpa_supplicant( 1369): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1369): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-82
I/wpa_supplicant( 1369): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1369): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1369): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1369): wlan0: Scan-only results received
D/wpa_supplicant( 1369): wlan0: Radio work 'scan'@0x5594507680 done in 0.072450 seconds
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  931): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  931): handleMessage: E msg.what=147461
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  931): processMsg: ConnectModeState
,E/WifiStateMachine(  931):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  931): processMsg: DriverStartedState
E/WifiStateMachine(  931):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
,E/WifiStateMachine(  931):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
D/WifiStateMachine(  931): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1369): wlan0: Control interface command 'LIST_DONGLES'
,W/ContextImpl(  931): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  931): [1,454,082,636,140 ms] noteScanEnd no scan source
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1369): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  931): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@6f86295 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  931): NG7005g c0:ff:d4:d3:aa:4a rssi=-56 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  931): Gonzos 38:f8:89:11:e9:11 rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
,E/WifiAutoJoinController (  931): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  931): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  931): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  931): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  931):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  931): UPC503894600 a0:c5:62:7a:49:97 rssi=-82 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  931): ageScanResultsOut delay 40000 size 5 now 1454082636144
E/WifiAutoJoinController (  931): newSupplicantResults size=5 known=1 true
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
,D/wpa_supplicant( 1369): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  931): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  931): ssid=NG700
E/WifiAutoJoinController (  931): id=0
E/WifiAutoJoinController (  931): mode=station
E/WifiAutoJoinController (  931): pairwise_cipher=CCMP
E/WifiAutoJoinController (  931): group_cipher=CCMP
E/WifiAutoJoinController (  931): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  931): wpa_state=COMPLETED
E/WifiAutoJoinController (  931): ip_address=192.168.1.130
E/WifiAutoJoinController (  931): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  931): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  931): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  931): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
,E/WifiAutoJoinController (  931): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  931): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  931): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  931): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  931): Done attemptAutoJoin status=0
E/WifiConfigStore(  931):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  931): handleMessage: X
,D/jxcore_app_log( 6317): JniHelper::setJavaVM(0xab13b8f8), pthread_self() = -1404185032
,I/chromium( 6317): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Finsky  ( 5945): [587] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5945): [1] 5.onFinished: Installation state replication succeeded.
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=339
,D/PMS     (  931): releaseHCC(cd206ca): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  931): releaseHCC(3dbaa03b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6317): Initializing JXcore engine
W/jxcore-log( 6317): JXcore engine is ready
,W/jxcore-log( 6317): Starting JXcore engine
,W/jxcore-log( 6317): Platform android,
W/jxcore-log( 6317): 
W/jxcore-log( 6317): Process ARCH arm
W/jxcore-log( 6317): 
,E/WifiStateMachine(  931): handleMessage: E msg.what=131155,
,E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:1269] from screen [on:0 period:-1911276010] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1911276009] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931):  get link layer stats 0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1369): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
,E/WifiConfigStore(  931): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  931): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.10 txretriesrate=0.00 rxrate=0.60 userTriggerdPenalty0
E/WifiStateMachine(  931):  good link -> stuck count =0
E/WifiStateMachine(  931):  badRSSI count0 lowRSSI count0 --> score 56
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
,E/WifiStateMachine(  931):  isHighRSSI       ---> score=61
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiWatchdogStateMachine(  931): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  931): handleMessage: X
,I/jxcore-log( 6317): JXcore Cordova bridge is ready!
I/jxcore-log( 6317): 
,W/jxcore-log( 6317): JXcore engine is started
,E/jxcore  ( 6317): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6317): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6317): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/PMS     (  931): acquireWL(2897fe0b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 931 1000 null
W/PluginManager( 6317): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 46ms. Plugin should use CordovaInterface.getThreadPool().
,W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1489): [onResume]
I/FeedProviderManager( 1489): onResume
D/StatusBarManagerService(  931): setSystemUiVisibility(0x700)
I/SocialFeedProvider( 1489): +onResume
D/StatusBarManagerService(  931): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SocialFeedProvider( 1489): updateAccounts - Accounts is no change
D/StatusBarManagerService(  931): hiding MENU key
I/SocialFeedProvider( 1489): -onResume
,D/FindExtension( 1489): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1489): Defer allocateBuffers to drawing time
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6
I/InputMethodManagerService(  931): Disable input method client, pid=6317
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=340
D/StatusBarManagerService(  931): swetImeWindowStatus vis=0 backDisposition=0
E/WifiTrafficPoller(  931): notifying of data activity 1
I/InputMethodManagerService(  931): Enable input method client, pid=1489
D/WIFI_ICON( 1222): WifiActivity: 1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/IInputConnectionWrapper( 6317): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false),
,D/PMS     (  931): releaseWL(2897fe0b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  931): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  931): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  931): hiding MENU key
,D/Process (  931): killProcessQuiet, pid=5740
I/ActivityManager(  931): Killing 5740:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  931): Recipient 5740
,W/OpenGLRenderer( 1489): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=340,
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  931): notifying of data activity 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 3152): handler message = 4011,
,E/HtcModeClient( 3152): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3152): Don't start project servcice,
,D/HtcModeClient( 3152): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3152): connectState: CONNECTION_READY = false
,D/SilentMusic( 3152): call stop
D/HtcModeClient( 3152): close connection,
W/HtcModeClient( 3152): leaveProjectMode: It does not enter ProjectMode,
,W/CANMesgAgentLocalSocket( 3152): read the terminate packet, so break
,D/Process (  931): killProcessQuiet, pid=3152
I/ActivityManager(  931): Killing 3152:com.htc.autobot/u0a47 (adj 15): empty #17,
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  931): Recipient 3152
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=340
,E/WifiStateMachine(  931): handleMessage: E msg.what=131155
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1911272990] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1911272989] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931):  get link layer stats 0,
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1369): environment dirty rate=0 [0][0][0],
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72,
E/WifiConfigStore(  931): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  931): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.05 txretriesrate=0.00 rxrate=0.80 userTriggerdPenalty0
E/WifiStateMachine(  931):  good link -> stuck count =0
E/WifiStateMachine(  931):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  931):  isHighRSSI       ---> score=61,
E/WifiStateMachine(  931): handleMessage: X
D/WifiWatchdogStateMachine(  931): RSSI current: 3 new: -60, 3
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=340
,E/WifiDataStallTracker(  931): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  931): updateDataStallInfo: mDataStallTxRxSum={txSum=236 rxSum=239} preTxRxSum={txSum=236 rxSum=239},
D/WifiDataStallTracker(  931): updateDataStallInfo: NONE
D/WifiDataStallTracker(  931): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  931): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6376 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  931): acquireWL(37ad7539): PARTIAL_WAKE_LOCK  *alarm* 0x1 931 1000 WorkSource{10076}
V/AlarmManager(  931): sending alarm PendingIntent{31a8777e: PendingIntentRecord{229774df com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454082641764, Int=60000
D/PMS     (  931): releaseWL(37ad7539): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=341
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  931): notifying of data activity 1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/art     (  426): Explicit concurrent mark sweep GC freed 8639(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 210us total 28.336ms
,I/art     (  426): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 212us total 27.436ms
,D/SMSBackup( 6376): SMSBackupAgentService started,
D/SMSBackup( 6376): Checking restore status
,D/SMSBackup( 6376): Restore complete,
D/SMSBackup( 6376): cancelCheckAlarm
,D/SMSBackup( 6376): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  931): killProcessQuiet, pid=5830
I/ActivityManager(  931): Killing 5830:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  426): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 176us total 22.711ms
,I/ActivityManager(  931): Recipient 5830,
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1222): WifiActivity: 0
,E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=341
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  931): notifying of data activity 0
,E/WifiStateMachine(  931): handleMessage: E msg.what=131155,
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1911269968] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
,E/WifiStateMachine(  931):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1911269966] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931):  get link layer stats 0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1369): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  931): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  931): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.03 txretriesrate=0.00 rxrate=0.90 userTriggerdPenalty0
,E/WifiStateMachine(  931):  good link -> stuck count =0
E/WifiStateMachine(  931):  badRSSI count0 lowRSSI count0 --> score 56
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  931):  isHighRSSI       ---> score=61
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiWatchdogStateMachine(  931): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  931): handleMessage: X
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=341
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=342
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  931): notifying of data activity 1,
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=342
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  931): notifying of data activity 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiDataStallTracker(  931): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  931): updateDataStallInfo: mDataStallTxRxSum={txSum=236 rxSum=239} preTxRxSum={txSum=236 rxSum=239}
D/WifiDataStallTracker(  931): updateDataStallInfo: NONE
D/WifiDataStallTracker(  931): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  931): handleMessage: E msg.what=131155,
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1911266945] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1911266944] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931):  get link layer stats 0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1369): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1369): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  931): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  931): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.01 txretriesrate=0.00 rxrate=0.95 userTriggerdPenalty0
E/WifiStateMachine(  931):  good link -> stuck count =0
E/WifiStateMachine(  931):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  931):  isHighRSSI       ---> score=61
E/WifiStateMachine(  931): handleMessage: X
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
,D/WifiWatchdogStateMachine(  931): RSSI current: 3 new: -60, 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  931): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@15f977f1
I/PMS     (  931): Going to sleep due to screen timeout (uid 1000)...,
W/SensorService(  931): Following SensorService logs are not warning, just make sure they are printed
D/ActivityManager(  931): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{13672bf5 #7 A=.Prism U=0 sz=1}
W/SensorService(  931): disable: get sensor name = Accelerometer Sensor
W/PMS     (  931): mWirelessDisplayManager is null
W/SensorService(  931): pid=931, uid=1000
I/PMS     (  931): Sleeping (uid 1000)...
W/SensorService(  931): Active sensors: size = 4
D/XAN-DPS (  931): prepareColorFade 1
W/SensorService(  931): Accelerometer Sensor (handle=0x00000000, connections=1)
W/PMN     (  931): goingToSleep
W/SensorService(  931): CM32181 Light sensor (handle=0x00000003, connections=1)
D/PMS     (  931): acquireWL(26d08d8a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 931 1000 null
W/SensorService(  931): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/PMS     (  931): mWirelessDisplayManager is still null
W/SensorService(  931): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  931): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@15f977f1, eanble = 0, strlen(mName) = 91
W/SensorService(  931): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  931): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@2d287425
W/SensorService(  931): Listener[1] = com.htc.smartdim.sensor_eye@5478883
W/SensorService(  931): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/Adreno-EGL(  931): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  931): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  931): Build Date: 03/09/15 Mon
I/Adreno-EGL(  931): Local Branch: 
I/Adreno-EGL(  931): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  931): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  931):                  d74aa161a12b9c6fc6332151
,W/PMN     (  931): goingToSleep done,
I/FeedHostManager( 1489): [onPause]
I/FeedProviderManager( 1489): onPause
I/FeedHostManager( 1489): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@1fdb2a23
I/SocialFeedProvider( 1489): +onPause
I/SocialFeedProvider( 1489): -onPause
W/HtcLockScreen( 1222): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  931): releaseWL(26d08d8a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/ActivityManager(  931): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6400 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/AlarmManager(  931): ACTION_SCREEN_ON
I/AlarmManager(  931): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  931): [AlarmQueuing] done recovering
I/AlarmManager(  931): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  931): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  931):  packet count Tx=253 Rx=342
E/WifiDataStallTracker(  931): ENABLE_DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  931): updateDataStallInfo: mDataStallTxRxSum={txSum=236 rxSum=239} preTxRxSum={txSum=236 rxSum=239}
D/WifiDataStallTracker(  931): updateDataStallInfo: NONE
D/WifiDataStallTracker(  931): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  931): handleMessage: E msg.what=131167
,E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0,
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  931): processMsg: ConnectModeState
,E/WifiStateMachine(  931):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
D/WifiDisplayAdapter(  931): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  931):     Client/Owner: Client
D/WifiDisplayAdapter(  931):     GroupId: 
D/WifiDisplayAdapter(  931):     Passphrase: 
D/WifiDisplayAdapter(  931):     SessionId: 0
D/WifiDisplayAdapter(  931):     IP Address: }
E/WifiStateMachine(  931): processMsg: DriverStartedState
E/WifiStateMachine(  931):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
E/WifiStateMachine(  931):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  931): processMsg: DefaultState
E/WifiStateMachine(  931):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  931):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1369): SET_SCREEN_ON:On
I/wpa_supplicant( 1369): htc_wext_set_keepalive +
I/wpa_supplicant( 1369): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1369): getPrivFuncNum +	
I/wpa_supplicant( 1369): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1369): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1369): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1369): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1369): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  931): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  931): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  931): handleScreenStateChanged Exit: true
E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL true Token 12 num clients 6
,E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=131154
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SIGNAL_POLL'
,V/SRS_Proc(  420): ParamSet string: screen_state=on
E/audio_a2dp_hw(  420): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  931): handleMessage: E msg.what=155650,
D/NetworkPolicy(  931): updateScreenOn: false
D/WifiController(  931): processMsg: DeviceActiveState
V/NetworkPolicy(  931): updateIfacesLocked()
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/wpa_supplicant( 1369): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  931): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=131127
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  931): processMsg: ConnectModeState
,E/WifiStateMachine(  931):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
D/NetworkManagementService(  931): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=131129
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
,E/WifiStateMachine(  931):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1369): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1369): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  931): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=33 dispatchEvent: BLACKLIST CLEAR 
,E/WifiStateMachine(  931): handleMessage: X
,W/ResourcesManager( 6400): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/XAN-DPS (  931): prepareColorFade done
D/XAN-DPS (  931): setBrightness to 0
,I/CalendarProvider2( 6400): Created com.android.providers.calendar.CalendarAlarmManager@19a7bba3(com.htc.providers.calendar.HtcCalendarProvider@aa8bea0)
,I/SensorManager(  931): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@2d287425
,W/SensorService(  931): Following SensorService logs are not warning, just make sure they are printed
I/DisplayManagerService(  931): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  931): disable: get sensor name = CM32181 Light sensor
V/ActivityManager(  931): Display changed displayId=0
D/DotMatrix( 1310): [EventService]  onDisplayChanged: 0
W/SensorService(  931): pid=931, uid=1000
W/SensorService(  931): Active sensors: size = 3
W/SensorService(  931): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  931): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  931): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  931): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@2d287425, eanble = 0, strlen(mName) = 67
W/SensorService(  931): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  931): Listener[0] = com.htc.smartdim.sensor_eye@5478883
W/SensorService(  931): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
,D/CalendarProvider2( 6400): wait start:true
,D/DotMatrix( 1310): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/CalendarProvider2( 6400): wait end:false
,D/GpsLocationProvider(  931): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
,I/IntentController( 1222): receive(android.intent.action.SCREEN_ON,1,false),
,D/PMS     (  931): acquireWL(31aff15c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1813 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): acquireWL(c9bfc65): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1813 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(31aff15c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(c9bfc65): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  931): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6429 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/AlarmManager(  931): ACTION_SCREEN_OFF
,I/AlarmManager(  931): [AlarmQueuing] screen off now: 
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 12
I/AlarmManager(  931): [AlarmQueuing] data connection: true
D/WifiDataStallTracker(  931): stopDataStallAlarm 
I/AlarmManager(  931): [AlarmQueuing] wifi connection: true
,E/WifiDataStallTracker(  931): ENABLE_DATA_MONITOR_POLL false Token 2
,E/WifiStateMachine(  931): handleMessage: E msg.what=131167
,D/WifiDisplayAdapter(  931): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  931):     Client/Owner: Client
D/WifiDisplayAdapter(  931):     GroupId: 
D/WifiDisplayAdapter(  931):     Passphrase: 
D/WifiDisplayAdapter(  931):     SessionId: 0
D/WifiDisplayAdapter(  931):     IP Address: }
E/WifiStateMachine(  931): processMsg: ConnectedState
D/NetworkPolicy(  931): updateScreenOn: false
E/WifiStateMachine(  931):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
V/NetworkPolicy(  931): updateIfacesLocked()
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  931): processMsg: DriverStartedState
E/WifiStateMachine(  931):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  420): ParamSet string: screen_state=off
D/NetworkManagementService(  931): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
E/audio_a2dp_hw(  420): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  931):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  931): processMsg: DefaultState
E/WifiStateMachine(  931):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  931):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1369): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1369): SET_SCREEN_ON:Off
I/wpa_supplicant( 1369): htc_wext_set_keepalive +
,I/wpa_supplicant( 1369): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1369): getPrivFuncNum +	
I/wpa_supplicant( 1369): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1369): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1369): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1369): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1369): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  931): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiController(  931): handleMessage: E msg.what=155651
D/WifiStateMachine(  931): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  931): handleScreenStateChanged Exit: false
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=131154
E/WifiStateMachine(  931): processMsg: ConnectedState
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
E/WifiStateMachine(  931):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  931): handleMessage: X
D/GpsLocationProvider(  931): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/SensorManager( 1222): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@327eb612, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
D/DotMatrix( 1310): [EventService] getTotalRam: 1842 Mb
W/SensorService(  931): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  931): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  931): pid=1222, uid=10041
W/SensorService(  931): Active sensors: size = 4
,W/SensorService(  931): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  931): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  931): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  931): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  931): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@327eb612, eanble = 1, strlen(mName) = 57
W/SensorService(  931): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  931): Listener[0] = com.htc.smartdim.sensor_eye@5478883,
W/SensorService(  931): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@327eb612
W/SensorService(  931): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  931): Excessive delay in setPowerMode(): 297ms
D/PMS     (  931): Setting HAL interactive mode to false
D/PMS     (  931): Setting HAL interactive mode to false done
,D/PMS     (  931): Setting HAL auto-suspend mode to true
D/PMS     (  931): Setting HAL auto-suspend mode done
,W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006,
I/InputMethodManagerService(  931): screenObserver, isScreenOn=false
D/StatusBarManagerService(  931): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
I/InputMethodManagerService(  931): Disable input method client, pid=1489
D/HABCtrl (  931): TPE algorithm. remove timeout.
D/PMS     (  931): OOBE c monitor 11
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PMS     (  931): acquireWL(1bf8c748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/UsbnetService(  931): onReceive BATTERY_CHANGED
I/BatteryService(  931): n_update end
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  931): releaseWL(1bf8c748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/NotificationService(  931): plugged=true pluggin=true
D/HtcPowerSaver(  931): updateBatteryInfo
D/PMS     (  931): runPSCheck
D/HtcPowerSaver(  931): Checking...
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1459): ScreenObserver: OFF,
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/ContactMessageStore( 1435): start background delete task...
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  931): << updateStatus
D/NfcService( 1459): applyRouting - 0
D/PMS     (  931): acquireWL(1f54f9e1): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1459 1027 null
D/NfcService( 1459): applyRouting -2
D/NfcService( 1459): applyRouting
D/NfcService( 1459): Ignore this applyRouting...
D/PMS     (  931): releaseWL(1f54f9e1): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/ContactMessageStore( 1435): size: 0 , 0
,D/ContactMessageStore( 1435): Background delete complete
,I/IntentController( 1222): receive(android.intent.action.SCREEN_OFF,1,false)
,W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  931): acquireWL(20572306): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1813 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(20572306): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): acquireWL(38770ff4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1813 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(38770ff4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6429): MY_DEBUG = false,
,I/InputManager(  931): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1222): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/SmartSyncUtils( 6429): isEpsOn(), nState = 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/RemoteViews( 1222): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  931): acquireWL(1cb26992): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6429 1000 null,
,I/RemoteViews( 1222): apply : com.htc.updater 0 13 1 36
,W/ContextImpl(  931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
I/ClockController( 1222): stop clock update:screen off
,D/SmartDim(  931): Init customizeScreenOffDelayClass error,
,D/PMS     (  931): releaseWL(1cb26992): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6429): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6429): isEpsOn(), nState = 0
,W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  931): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  931): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@5478883
W/SensorService(  931): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  931): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  931): pid=931, uid=1000,
W/SensorService(  931): Active sensors: size = 3
W/SensorService(  931): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  931): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  931): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  931): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@5478883, eanble = 0, strlen(mName) = 35
W/SensorService(  931): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  931): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@327eb612
W/SensorService(  931): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  931): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  931): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  931): pid=931, uid=1000,
W/SensorService(  931): Active sensors: size = 2
W/SensorService(  931): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  931): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  931): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@5478883, eanble = 0, strlen(mName) = 35
,W/SensorService(  931): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  931): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@327eb612,
W/SensorService(  931): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/ActivityThread(  931): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@235f3a00 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  931): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@235f3a00 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  931): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  931): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  931): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  931): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  931): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  931): ,	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  931): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  931): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  931): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  931): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  931): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  931): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  931): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  931): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  931): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  931): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  931): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  931): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/SensorManager(  931): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@5478883
,I/ActivityManager(  931): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6462 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/PowerUsageList:PowerUsageHelper( 6429): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6429): gen(), null == sipper.uidObj, userId = 0,
,D/Process (  931): killProcessQuiet, pid=4567
I/ActivityManager(  931): Killing 4567:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6429): getMobilePolicyEnabled, result = true,
,D/WifiService(  931): New client listening to asynchronous messages
,E/WifiTrafficPoller(  931): ADD_CLIENT: 7
,I/ActivityManager(  931): Recipient 4567
,D/PowerUsageList:PowerUsageHelper( 6429): MY_DEBUG = false
,E/WifiTrafficPoller(  931): TRAFFIC_STATS_POLL false Token 13 num clients 7
,D/Process (  931): killProcessQuiet, pid=5986
I/ActivityManager(  931): Killing 5986:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/CalendarProvider2( 6400): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6400): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  931): Recipient 5986
,I/ActivityManager(  931): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6486 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  931): killProcessQuiet, pid=5898
I/ActivityManager(  931): Killing 5898:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  427): Explicit concurrent mark sweep GC freed 8680(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 666us total 49.606ms,
,I/art     (  427): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 378us total 29.775ms
,I/art     (  427): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 400us total 27.138ms
,I/ActivityManager(  931): Recipient 5898
,W/ResourcesManager( 6486): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6486): onCreate
,D/ProviderChangeReceiver( 6486): ---------------------------------------------------
D/ProviderChangeReceiver( 6486): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  931): killProcessQuiet, pid=6184
I/ActivityManager(  931): Killing 6184:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6486): start to updateAlertNotification!
,D/PMS     (  931): releaseWL(102ef442): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  931): Recipient 6184
,D/HtcAlertService( 6486): No fired or scheduled alerts
,D/HtcAlertUtils( 6486): -- cancelReminderNotification --
,D/HtcAlertUtils( 6486): broadcastExistReminder!
,D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  931): handleMessage: E msg.what=131155
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1911263923] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
,E/WifiStateMachine(  931):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1911263921] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931): handleMessage: X
,E/WifiStateMachine(  931): handleMessage: E msg.what=131155
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:401] from screen [on:0 period:-1911263519] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1911263517] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  931): handleMessage: X
,D/HtcUPManager( 1222): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  931): DATA_MONITOR_POLL false Token 3
,E/WifiDataStallTracker(  931): DATA_MONITOR_POLL false Token 3
,D/ContactMessageStore( 1435): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1435): MSG_NOTIFY_CS_TO_SYNC <<,
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/Process (  931): killProcessQuiet, pid=5551
,I/ActivityManager(  931): Killing 5551:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 5551
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  931): acquireWL(2fa0419): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000}
V/AlarmManager(  931): sending alarm PendingIntent{27d50a53: PendingIntentRecord{2e0cdf90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=125933, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{36098cde: PendingIntentRecord{3cb0cebf android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454082674759, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{1d00698c: PendingIntentRecord{279dc8d5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143209, Int=0
D/PMS     (  931): acquireWL(1b1d98ea): PARTIAL_WAKE_LOCK  *backup* 0x1 931 1000 null
,D/PMS     (  931): releaseWL(2fa0419): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/BackupManagerService(  931): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  931): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  931): releaseWL(1b1d98ea): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  931): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  931): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  931): acquireWL(3f2d97db): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 931 1000 null
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  931): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  931): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  931): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  931): [NET] android_getaddrinfo_proxy+
D/libc    (  931): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  413): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  413): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  413): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  413): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  931): [NET] android_getaddrinfo_proxy-, success,
D/libc    (  931): [NET] android_getaddrinfofornet+,hn 12(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  931): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  931): [reportHTCStatus] eventMask = 3 , status = 0
D/PMS     (  931): acquireWL(fe3d6b7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 931 1000 null
D/GpsLocationProvider(  931): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  931): releaseWL(3f2d97db): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  931):  [handleDownloadXtraData]inject done.
D/PMS     (  931): releaseWL(fe3d6b7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  931): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
,W/ContextImpl(  931): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  931): acquireWL(37f85e24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null,
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(37f85e24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  931): updateBatteryInfo
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): handleMessage: E msg.what=155652
D/PMS     (  931): runPSCheck
D/WifiController(  931): processMsg: DeviceActiveState
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): processMsg: StaEnabledState
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1435): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  931): acquireWL(35473d8d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000},
V/AlarmManager(  931): sending alarm PendingIntent{27d50a53: PendingIntentRecord{2e0cdf90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=185933, Int=0
,V/AlarmManager(  931): sending alarm PendingIntent{c245b42: PendingIntentRecord{16552753 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203179, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{316f3890: PendingIntentRecord{3ef72589 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190140, Int=0
,D/PMS     (  931): acquireWL(2da0e98e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(35473d8d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  931): acquireWL(2680e5af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(2da0e98e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1915): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  931): releaseWL(2680e5af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): acquireWL(22f0fcc1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(22f0fcc1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  931): acquireWL(be49c66): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(be49c66): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  931): acquireWL(14e1dba7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): acquireWL(3f419854): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): acquireWL(88e18f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(14e1dba7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1915): Vacuum at: now=1454082737504 tag=VacuumService
,D/PMS     (  931): releaseWL(88e18f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): acquireWL(3e49e5c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(3e49e5c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  931): acquireWL(3bf782f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): releaseWL(3bf782f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(3f419854): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  931): acquireWL(37e0d23e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(37e0d23e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): acquireWL(24bc989f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(24bc989f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  931): acquireWL(4c79dec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): acquireWL(2ba455b5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(4c79dec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1915): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1915): No account for auth token provided,
,D/libc    ( 1915): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1915): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1915): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1915): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1915): [NET] android_getaddrinfo_proxy+
D/libc    ( 1915): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  413): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  413): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  413): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1915): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1915): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1915): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1915): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1915): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1915): No account for auth token provided,
,W/Uploader( 1915): No account for auth token provided,
,W/Uploader( 1915):  no longer exists, so no auth token.,
,W/Uploader( 1915): No account for auth token provided,
,I/GLSUser ( 1915): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1915): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1915): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1915): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1915): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1915): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1915): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1915): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1915): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1915): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1915): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235),
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1915): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/GLSUser ( 1915): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1915): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1915): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1915): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1915): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1915): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1915): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1915): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1915): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1915): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1915): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1915): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,I/GLSUser ( 1915): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1915): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1915): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1915): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1915): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1915): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1915): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1915): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1915): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1915): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1915): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1915): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1915): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  931): releaseWL(2ba455b5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  931): acquireWL(1ea2e723): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(1ea2e723): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): acquireWL(15db4420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(15db4420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  931): Explicit concurrent mark sweep GC freed 43925(2MB) AllocSpace objects, 9(1296KB) LOS objects, 33% free, 18MB/28MB, paused 2.254ms total 212.690ms
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1569): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@625ccea
I/ActivityManager(  931): Killing 6207:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  931): killProcessQuiet, pid=6207
,D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 6207
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  931): acquireWL(2dddf1d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PMS     (  931): releaseWL(2dddf1d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  931): updateBatteryInfo
,D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/PMS     (  931): runPSCheck
D/WifiController(  931): handleMessage: E msg.what=155652
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): processMsg: DeviceActiveState
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): processMsg: StaEnabledState
,D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DefaultState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1369): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
,D/wpa_supplicant( 1369): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1369): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1369): wlan0: BSS: Remove id 1 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 38:f8:89:11:e9:11]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 38:f8:89:11:e9:11
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  931): acquireWL(e06479e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  931): n_update end
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  931): releaseWL(e06479e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  931): updateBatteryInfo
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  931): Checking...
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  931): >> updateStatus
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  931): acquireWL(24b2d27f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000}
,V/AlarmManager(  931): sending alarm PendingIntent{27d50a53: PendingIntentRecord{2e0cdf90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=245933, Int=0
,V/AlarmManager(  931): sending alarm PendingIntent{2980824c: PendingIntentRecord{2632d295 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454082834189, Int=1800000
V/AlarmManager(  931): sending alarm PendingIntent{3dac179b: PendingIntentRecord{e597738 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454082874525, Int=0
,D/PMS     (  931): acquireWL(bbb0311): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4465 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(24b2d27f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
D/PMS     (  931): acquireWL(362a9277): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4465 10024 WorkSource{10024 com.google.android.gms}
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  931): releaseWL(bbb0311): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms},
,I/EventLogService( 4465): Aggregate from 1454082599744 (log), 1454081034152 (data)
,D/PMS     (  931): releaseWL(362a9277): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1915): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1915): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1915): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1915): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1915): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1915): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1915): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1915): ,	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1915): 	at com.google.android.gms.auth.p.d(SourceFile:599),
W/GLSActivity( 1915): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1915): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1915): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1915): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 5945): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5945): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5945): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5945): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5945): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5945): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5945): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1222): reapply : com.google.android.gms 4 40
,W/System  ( 5945): Ignoring header User-Agent because its value was null.
,D/libc    ( 5945): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5945): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 5945): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5945): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5945): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5945): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  413): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  413): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  413): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5945): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  931): acquireWL(37f1b914): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  931): n_update end
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  931): releaseWL(37f1b914): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  931): updateBatteryInfo
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): handleMessage: E msg.what=155652
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  931): acquireWL(31c815bd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
,D/PMS     (  931): releaseWL(31c815bd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  931): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  931): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  931): Checking...
D/UsbnetService(  931): onReceive BATTERY_CHANGED
,I/HtcPowerSaver(  931): >> updateStatus
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): processMsg: DeviceActiveState
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  931): processMsg: StaEnabledState
I/HtcPowerSaver(  931): << updateStatus
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  931): processMsg: DefaultState
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
D/WifiController(  931): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  931): acquireWL(35ff07b2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000},
V/AlarmManager(  931): sending alarm PendingIntent{27d50a53: PendingIntentRecord{2e0cdf90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=365933, Int=0
,I/ActivityManager(  931): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6524 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  931): sending alarm PendingIntent{179ab303: PendingIntentRecord{26bb5280 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454083012664, Int=0,
,D/PMS     (  931): releaseWL(35ff07b2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,E/cutils-trace( 6545): Error opening trace file: Permission denied (13),
,I/dex2oat ( 6545): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6545): dex2oat: override thread count:4
,I/dex2oat ( 6545): dex2oat took 709.546ms (threads: 4)
,I/PushClient( 6524): ApplicationMonitor {101d0315}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6524): ApplicationMonitor {101d0315}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6524): ApplicationMonitor {101d0315}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6524): ApplicationMonitor {101d0315}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6524): ApplicationMonitor {101d0315}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk,
I/PushClient( 6524): ApplicationMonitor {101d0315}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6524): ApplicationMonitor {101d0315}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6524): ApplicationMonitor {101d0315}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6524): ApplicationMonitor {101d0315}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6524): PnsModel {39eb24cc}: update(): Update registration caused by: alarm
,I/PushClient( 6524): PnsConfigModel {18ced393}: <init>(): Use dm-client for provisioning.
,W/System.err( 6524): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6524): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6524): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6524): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  931): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6552 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6552): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6552 dbg=false s=true,
,I/DeviceManagement( 6552): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6552): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6552): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6552): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6552): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@39eb24cc] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6552): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6552): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6552): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6552): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6552): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6552): SessionStateController: Checking invariants...
,I/DeviceManagement( 6552): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6552): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@39eb24cc],
,I/DeviceManagement( 6552): WorkflowService: Stopping workflow service,
,D/Process (  931): killProcessQuiet, pid=5920,
I/ActivityManager(  931): Killing 5920:com.android.settings/1000 (adj 15): empty #17
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 5920
,I/PushClient( 6524): PnsModel {39eb24cc}: update(): The registration record has not expired yet. No need to update.,
I/ActivityManager(  931): Killing 6238:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  931): killProcessQuiet, pid=6238
,D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 6238
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  931): acquireWL(208ee82d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/UsbnetService(  931): BroadcastReceiver::onReceive+
I/BatteryService(  931): n_update end
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/PMS     (  931): releaseWL(208ee82d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/NotificationService(  931): plugged=true pluggin=true
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
D/HtcPowerSaver(  931): updateBatteryInfo
D/WifiController(  931): processMsg: StaEnabledState
D/PMS     (  931): runPSCheck
D/WifiController(  931): processMsg: DefaultState
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): handleMessage: X
I/HtcPowerSaver(  931): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  450): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  931): acquireWL(2764c162): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null,
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(2764c162): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/HtcPowerSaver(  931): updateBatteryInfo
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  931): Checking...
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  931): processMsg: StaEnabledState
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  931): processMsg: DefaultState
I/HtcPowerSaver(  931): << updateStatus
D/WifiController(  931): handleMessage: X
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1435): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1435): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1435): sku_id=118
D/ContactMessageStore( 1435): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1435): start background delete task...
,D/ContactMessageStore( 1435): size: 0 , 0
,D/ContactMessageStore( 1435): Background delete complete
,D/PMS     (  931): acquireWL(2c9e62f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
,I/BatteryService(  931): n_update end
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PMS     (  931): releaseWL(2c9e62f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  931): updateBatteryInfo
,D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/PMS     (  931): runPSCheck
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  931): Checking...
I/HtcPowerSaver(  931): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  931): << updateStatus
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  931): acquireWL(3c885bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  931): n_update end
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  931): releaseWL(3c885bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  931): updateBatteryInfo
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/PMS     (  931): runPSCheck
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): handleMessage: E msg.what=155652
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): processMsg: DeviceActiveState
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  931): acquireWL(2c1eda29): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000}
V/AlarmManager(  931): sending alarm PendingIntent{27d50a53: PendingIntentRecord{2e0cdf90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=485933, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{145191ae: PendingIntentRecord{1bb23b4f com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940284, Int=0
I/bt-btm  ( 3048): Received oneshot timer event complete
,I/bt-btm  ( 3048): btm_ble_timeout
I/bt-btm  ( 3048): btm_gen_resolvable_private_addr
,D/PMS     (  931): acquireWL(70f82dc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3048 1002 null
,D/bt-btm  ( 3048): btm_ble_rand_enc_complete
I/bt-btm  ( 3048): btm_gen_resolve_paddr_low
D/bt-smp  ( 3048): smp_encrypt_data
W/bt-smp  ( 3048): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3048): Plain text(LSB ~ MSB) = f8 a6 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3048): Encrypted text(LSB ~ MSB) = c9 a3 7e 28 71 73 59 5d 25 ee 86 61 31 06 0f 70 
I/bt-btm  ( 3048): btm_gen_resolve_paddr_cmpl
,W/bt-btm  ( 3048): Stopping oneshot timer
,D/PMS     (  931): releaseWL(2c1eda29): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/bt-btm  ( 3048): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  931): releaseWL(70f82dc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  931): acquireWL(da1efe5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(da1efe5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  931): updateBatteryInfo
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  931): Checking...
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  931): >> updateStatus
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  931): battery changed pluggedType: 2
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  931): acquireWL(15291aba): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000},
V/AlarmManager(  931): sending alarm PendingIntent{27d50a53: PendingIntentRecord{2e0cdf90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=965933, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{2e813d6b: PendingIntentRecord{197ff0c8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454083547388, Int=0
,D/SmartSyncUtils( 6429): isEpsOn(), nState = 0,
,D/PMS     (  931): acquireWL(1986a561): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6429 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6429): [updateNmRange] bManual = false,
D/PMS     (  931): releaseWL(15291aba): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6429): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6429): AlarmOnTime = -1
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 6429): SettingOnTime = 1454133600000, randomSettingOnTime = 1454132711000
D/SmartSyncScreenOnOffTimeReceiver( 6429): SettingOffTime = 1454112000000, randomSettingOffTime = 1454114617000
,D/SmartSyncScreenOnOffTimeReceiver( 6429): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6429): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6429): bNightModeTurnOffOnce = false
,D/PMS     (  931): releaseWL(1986a561): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  931): acquireWL(2ebe2886): PARTIAL_WAKE_LOCK  *alarm* 0x1 931 1000 WorkSource{1000},
V/AlarmManager(  931): sending alarm PendingIntent{3c5c111f: PendingIntentRecord{1d64ec6c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805810, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{27d50a53: PendingIntentRecord{2e0cdf90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1025933, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{34f44547: PendingIntentRecord{15075174 android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1048164, Int=0
,V/AlarmManager(  931): sending alarm PendingIntent{22a7369d: PendingIntentRecord{e444712 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=972289, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{2aa5eee3: PendingIntentRecord{3922ee9a com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454083497083, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{1e0210e0: PendingIntentRecord{15459f99 com.htc.task broadcastIntent}}, i=com.htc.task.statistics, t=1, cnt=1, w=1454083582379, Int=0
,D/HtcSystemUPManager(  931): UPAlarmListener onAlarmArrival
D/HtcSystemUPManager(  931): UPAlarmListener [SYSTEM_UP_UPLOAD] cur = 1454083582391, last = 1453997182231, freq = 86400000
D/HtcSystemUPManager(  931): AlarmScheduler_INEXACT [onReceive] end
D/HtcSystemUPManager(  931): com.htc.upm.AlarmScheduler$SchedulerBase$1@162f260d
,D/PMS     (  931): acquireWL(e9bc25e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  931): releaseWL(e9bc25e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PowerUsageList:PowerUsageHelper( 6429): MY_DEBUG = false
,I/ActivityManager(  931): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=6585 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,D/PowerUsageService( 6429): repeat time = 1454084482441
,W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability,
,W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability,
,W/ResourcesManager( 6585): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,D/PMS     (  931): acquireWL(275b0c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1915 10024 WorkSource{10024 com.google.android.gms},
D/HtcSystemUPManager(  931): HtcSystemUPHandler sendService() has been called
D/HtcSystemUPManager(  931): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
I/HtcSystemUPManager(  931): HtcSystemUPDataStore Send UPLOAD message to UP service 
,D/HtcAppUPService( 1569): HtcUPDataProvider bulkInsert() has been called.,
D/PMS     (  931): acquireWL(5c79c55): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1915 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(2ebe2886): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10069},
,I/GCM     ( 4465): Message from null null
E/GCM     ( 4465): Dropping message from null
,D/PMS     (  931): releaseWL(5c79c55): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcAppUPService( 1569): HtcUPServiceStore Store Version: 1 Data version: 1 File total length: 9 bytes.  Data length: 0bytes,
I/HtcAppUPService( 1569): HtcUPServiceStore Uploading is triggered by System...
D/HtcSystemUPManager(  931): HtcSystemUPHandler send to UPService takes: 41 ms
D/HtcAppUPService( 1569): HtcUPService onCreate()
,D/HtcAppUPService( 1569): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.SYSTEM_UP_NOTIFY cmp=com.htc.sense.hsp/.upservice.HtcUPService (has extras) }, this = com.htc.sense.hsp.upservice.HtcUPService@37e45f16
D/HtcAppUPService( 1569): PolicyStore [Init] Get cached policy bundle
,D/HtcAppUPService( 1569): appid: tellhtc_client, category: usage_report, key: enable, value: 1, due date: -1, current time: 1454083582568, default value: null
D/HtcAppUPService( 1569): HtcUPServicePreference Upload schedule enable? false
D/HtcAppUPService( 1569): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.SYSTEM_UP_NOTIFY
,D/HtcAppUPService( 1569): ReportUploader User Profiling function had been closed by user
,I/HtcAppUPService( 1569): HtcUPServiceStore Clear data store!
,D/HtcAppUPService( 1569): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
D/HtcAppUPService( 1569): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
,D/HtcAppUPService( 1569): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@37e45f16
,D/GCM     ( 1915): Message class com.google.f.a.a.i
,D/PMS     (  931): releaseWL(275b0c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6429): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6429): gen(), null == sipper.uidObj, userId = 0,
,I/ActivityManager(  931): Killing 4846:com.google.android.gms.wearable/u0a24 (adj 15): empty #17,
D/Process (  931): killProcessQuiet, pid=4846
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 4846
,D/PMS     (  931): acquireWL(29751bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null,
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(29751bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  931): updateBatteryInfo,
D/NotificationService(  931): plugged=true pluggin=true
,D/PMS     (  931): runPSCheck
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  931): Checking...
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  931): >> updateStatus
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1222): closing low battery warning: level=100
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
,D/UsbnetService(  931): BroadcastReceiver::onReceive+,
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  931): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  931): << updateStatus
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  931): acquireWL(2f32a8d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(2f32a8d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  931): updateBatteryInfo,
D/PMS     (  931): runPSCheck
D/HtcPowerSaver(  931): Checking...
,I/HtcPowerSaver(  931): >> updateStatus
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  931): acquireWL(2aa7bf36): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(2aa7bf36): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  931): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  931): runPSCheck
D/HtcPowerSaver(  931): Checking...
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  931): >> updateStatus
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  931): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  931): << updateStatus
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  931): User[0] Flushing usage stats to disk
,D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PMS     (  931): acquireWL(1f730e37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/UsbnetService(  931): onReceive BATTERY_CHANGED
I/BatteryService(  931): n_update end
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  931): releaseWL(1f730e37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/NotificationService(  931): plugged=true pluggin=true
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): processMsg: StaEnabledState
D/HtcPowerSaver(  931): updateBatteryInfo
D/WifiController(  931): processMsg: DefaultState
,D/PMS     (  931): runPSCheck
D/WifiController(  931): handleMessage: X
D/HtcPowerSaver(  931): Checking...
D/HeadsetStateMachine( 3048): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  931): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  931): << updateStatus
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
