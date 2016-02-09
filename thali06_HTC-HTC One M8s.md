#### Test 586983493da948e_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  972): handleMessage: E msg.what=131155
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1007618128] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1007618127] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1371): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  972): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.45 txretriesrate=0.00 rxrate=0.82 userTriggerdPenalty0
E/WifiStateMachine(  972):  good link -> stuck count =0
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  972):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -64, 3
E/WifiStateMachine(  972): handleMessage: X
--------- beginning of system
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiDataStallTracker(  972): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  972): updateDataStallInfo: mDataStallTxRxSum={txSum=143 rxSum=143} preTxRxSum={txSum=143 rxSum=143}
D/WifiDataStallTracker(  972): updateDataStallInfo: NONE
D/WifiDataStallTracker(  972): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/cutils-trace( 6363): Error opening trace file: Permission denied (13)
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  972):  packet count Tx=162 Rx=256
D/CustomizationManager( 6363): ====startRecUseTime====
D/htc.customization.log.level( 6363):  is 
W/CustomizationLogLevel( 6363): Level value is invalid, use default level 2
D/CustomizationManager( 6363):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6363): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6363): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6363): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6363): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6363): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6363): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6363): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6363): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6363): Parsing tag category name = system
I/CustomizationCIDLoader( 6363): Parsing tag category name = application
I/CustomizationCIDLoader( 6363): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6363): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6363): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6363): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6363): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6363): add string-array item, value = 42507
I/CustomizationCIDLoader( 6363): add string-array item, value = 21902
I/CustomizationCIDLoader( 6363): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6363): add string-array item, value = 23420
I/CustomizationCIDLoader( 6363): add string-array item, value = 22299
I/CustomizationCIDLoader( 6363): add string-array item, value = 24002
I/CustomizationCIDLoader( 6363): add string-array item, value = 23210
I/CustomizationCIDLoader( 6363): add string-array item, value = 23205
I/CustomizationCIDLoader( 6363): add string-array item, value = 23806
I/CustomizationCIDLoader( 6363): add string-array item, value = 23430
I/CustomizationCIDLoader( 6363): add string-array item, value = 23408
I/CustomizationCIDLoader( 6363): add string-array item, value = 27205
I/CustomizationCIDLoader( 6363): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6363): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6363):  Read CID file spent 0.102 (s)
D/CustomizationManager( 6363):  All configurations done spent 0.103 (s)
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6363 on display 0
D/PMS     (  972): acquireHCC(2afe8e96): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 972 1000 null
D/PMS     (  972): acquireHCC(3bd89a17): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 972 1000 null
W/asset   (  972): Copying FileAsset 0x55ab80de30 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  972): acquireWL(58cfe22): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 972 1000 null
I/AnimationUtil(  972): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1520): [onPause]
I/FeedProviderManager( 1520): onPause
I/SocialFeedProvider( 1520): +onPause
I/SocialFeedProvider( 1520): -onPause
I/FeedHostManager( 1520): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2ffa858b
W/HtcSystemUPManager(  972): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  972): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6381 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  409): Explicit concurrent mark sweep GC freed 8670(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 266us total 27.370ms
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 234us total 15.588ms
D/StatusBarManagerService(  972): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 311us total 16.556ms
W/asset   ( 6381): Copying FileAsset 0xabffdf18 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1520): [trimMemory] 20
,I/HtcModeClient( 3200): handler message = 4011
,E/HtcModeClient( 3200): Check connection and retry 11 times.
,I/WebViewFactory( 6381): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6381): Time to load native libraries: 13 ms (timestamps 4454-4467)
,I/LibraryLoader( 6381): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6381): Binding Chromium to main looper Looper (main, tid 1) {2124e982}
,I/LibraryLoader( 6381): Expected native library version number "",actual native library version number ""
,I/chromium( 6381): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6381): Initializing chromium process, singleProcess=true
,W/art     ( 6381): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6381): ApplicationContext is null in ApplicationStatus
,W/chromium( 6381): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6381): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6381): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6381): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6381): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6381): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6381): Local Branch: 
I/Adreno-EGL( 6381): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6381): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6381):                  d74aa161a12b9c6fc6332151
W/System.err(  972): java.lang.Throwable: stack dump
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c7d3ca3:true
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6381): 98880239: getState(). Returning 12
W/art     ( 6381): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6381): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6381): CordovaWebView is running on device made by: HTC
W/art     ( 6381): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6381): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6381): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6381): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  972):  packet count Tx=162 Rx=257
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  972): notifying of data activity 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/InputMethodManager( 6381): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@38844ddf, mServedView=org.apache.cordova.engine.SystemWebView{39894a2c VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1e162cf5
I/InputMethodManagerService(  972): Disable input method client, pid=1520
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  972): Enable input method client, pid=6381
D/PMS     (  972): releaseWL(58cfe22): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
I/ActivityManager(  972): Displayed com.test.thalitest/.MainActivity: +875ms
W/XT9_C   ( 1393): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1393): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1393): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1393): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6381): Cannot call determinedVisibility() - never saw a connection for the pid: 6381
D/JsMessageQueue( 6381): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6381): JniHelper::setJavaVM(0xaae918f8), pthread_self() = -1407553208
I/chromium( 6381): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/PMS     (  972): acquireWL(1d72d5e8): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{10072}
V/AlarmManager(  972): sending alarm PendingIntent{2081f401: PendingIntentRecord{297362a6 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454986294913, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{93c4e7: PendingIntentRecord{36936894 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454986297592, Int=536832000
V/AlarmManager(  972): sending alarm PendingIntent{afd3fda: PendingIntentRecord{13e4cc0b android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454986290470, Int=20000
V/CheckinService( 4408): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
D/PMS     (  972): acquireWL(1d18cf3d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4408 10024 WorkSource{10024 com.google.android.gms}
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
E/WifiStateMachine(  972): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  972): handleMessage: E msg.what=131143
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):3 dur:74 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 list=2412 [on:0 tx:0 rx:0 period:2381] from screen [on:0 period:-1007615727]
D/PMS     (  972): releaseWL(1d72d5e8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):5 dur:74 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1007615726]
E/WifiStateMachine(  972): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.45 rxSuccessRate=0.82 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-64
E/WifiStateMachine(  972): WifiStateMachine CMD_START_SCAN with age=59038 interval=60000 maxinterval=300000
E/WifiStateMachine(  972): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  972): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  972): has c0:ff:d4:d3:aa:48 freq=2412 age=2388 ?=true
E/WifiStateMachine(  972): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1371): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1371): wpa_supplicant_scan enter
D/wpa_supplicant( 1371): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1371): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1371): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1371): WPS:  * Request Type
D/wpa_supplicant( 1371): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1371): WPS:  * UUID-E
D/wpa_supplicant( 1371): WPS:  * Primary Device Type
D/wpa_supplicant( 1371): WPS:  * RF Bands (3)
D/wpa_supplicant( 1371): WPS:  * Association State
D/wpa_supplicant( 1371): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1371): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1371): WPS:  * Manufacturer
D/wpa_supplicant( 1371): WPS:  * Model Name
D/PMS     (  972): acquireWL(e4dc883): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4408 10024 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1371): WPS:  * Model Number
D/wpa_supplicant( 1371): WPS:  * Device Name
D/wpa_supplicant( 1371): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1371): P2P: * P2P IE header
D/wpa_supplicant( 1371): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1371): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1371): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1371): wlan0: Add radio work 'scan'@0x55b0961860
D/wpa_supplicant( 1371): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1371): wlan0: Starting radio work 'scan'@0x55b0961860 after 0.000236 second wait
D/wpa_supplicant( 1371): wlan0: nl80211: scan request
D/wpa_supplicant( 1371): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1371): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1371): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1371): wlan0: Own scan request started a scan in 0.000160 seconds
I/wpa_supplicant( 1371): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  972): [1,454,986,297,626 ms] noteScanstart no scan source
E/WifiStateMachine(  972): handleMessage: X
D/PMS     (  972): releaseWL(1d18cf3d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/art     ( 6381): Background sticky concurrent mark sweep GC freed 9451(1252KB) AllocSpace objects, 0(0B) LOS objects, 7% free, 7MB/8MB, paused 7.103ms total 38.287ms
I/CheckinService( 4408): Checking schedule, now: 1454986297657 next: 1454986297592
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4408, uid=10024, userID:0
I/CheckinService( 4408): active receiver: enabled
I/CheckinService( 4408): Preparing to send checkin request
I/EventLogService( 4408): Accumulating logs since 1454986262109
I/CheckinRequestBuilder( 4408): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  972): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4408): Failed to find provider info for com.google.android.wearable.settings
D/wpa_supplicant( 1371): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1371): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1371): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1371): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1371): wlan0: Scan completed in 0.076457 seconds
D/wpa_supplicant( 1371): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1371): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1371): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1371): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1371): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-55
I/wpa_supplicant( 1371): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-64
I/wpa_supplicant( 1371): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-64
I/wpa_supplicant( 1371): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
D/wpa_supplicant( 1371): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1371): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1371): wlan0: Scan-only results received
D/wpa_supplicant( 1371): wlan0: Radio work 'scan'@0x55b0961860 done in 0.077874 seconds
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  972): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  972): handleMessage: E msg.what=147461
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1371): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  972): [1,454,986,297,706 ms] noteScanEnd no scan source
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1371): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  972): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3dfc1e6f sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  972): NG7005g c0:ff:d4:d3:aa:4a rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  972): NG700 c0:ff:d4:d3:aa:48 rssi=-64 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  972): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  972): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  972):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-64 freq=2412
E/WifiAutoJoinController (  972): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  972): 01ABC c2:ff:d4:d3:aa:48 rssi=-64 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  972): ageScanResultsOut delay 40000 size 4 now 1454986297708
E/WifiAutoJoinController (  972): newSupplicantResults size=4 known=1 true
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1371): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  972): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  972): ssid=NG700
E/WifiAutoJoinController (  972): id=0
E/WifiAutoJoinController (  972): mode=station
E/WifiAutoJoinController (  972): pairwise_cipher=CCMP
E/WifiAutoJoinController (  972): group_cipher=CCMP
E/WifiAutoJoinController (  972): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  972): wpa_state=COMPLETED
E/WifiAutoJoinController (  972): ip_address=192.168.1.130
E/WifiAutoJoinController (  972): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  972): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  972): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  972): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  972): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-64,-127) num=(1,0)
E/WifiAutoJoinController (  972): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  972): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-64 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  972): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  972): Done attemptAutoJoin status=0
E/WifiConfigStore(  972):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  972): handleMessage: X
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  972):  packet count Tx=162 Rx=257
E/WifiTrafficPoller(  972): notifying of data activity 0
D/WIFI_ICON( 1223): WifiActivity: 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/GLSUser ( 1886): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1886): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1886): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1886): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/CheckinRequestBuilder( 4408): awaiting user notification for token
D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1223): reapply : com.google.android.gms 1 40
I/ActivityManager(  972): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6436 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 6436): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6436): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6436): VM with version 2.1.0 has multidex support
I/MultiDex( 6436): install
I/MultiDex( 6436): VM has multidex support, MultiDex support library is disabled.
D/PMS     (  972): releaseHCC(2afe8e96): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  972): releaseHCC(3bd89a17): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
V/JNIHelp ( 6436): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 5979): [607] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5979): [1] 5.onFinished: Installation state replication succeeded.
,W/ActivityThread( 6436): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6436): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7fe27bf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6436): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1886): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1886): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4408): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4408, uid=10024, userID:0,
D/WearableService( 5689): callingUid 10024, callindPid: 5689
,E/MDM     ( 1819): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155
,E/WifiStateMachine(  972): processMsg: ConnectedState
,E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:609] from screen [on:0 period:-1007615107] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState,
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1007615106] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1371): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  972): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.23 txretriesrate=0.00 rxrate=0.91 userTriggerdPenalty0
E/WifiStateMachine(  972):  good link -> stuck count =0
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  972):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -64, 3
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  972): handleMessage: X
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/LocationInitializer( 4408): Restart initialization of location
,I/WVCdm   (  401): CdmEngine::OpenSession,
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
,D/QSEECOMAPI: (  401): Loaded image: APP id = 8
,D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
,D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf493c000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf493c000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  538): got the req here! ret=0
D/DrmLibTime(  538): command id, time_cmd_id = 770
D/DrmLibTime(  538): time_getutcsec starts!,
D/DrmLibTime(  538): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  538): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  538): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  538): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  538): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  538): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  538): QSEE Time Listener: Retrieved Android system time: 1454986298
D/DrmLibTime(  538): time_getutcsec returns 0, sec = 1454986298; nsec = 0
D/DrmLibTime(  538): time_getutcsec finished! 
D/DrmLibTime(  538): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  538): before calling ioctl to read the next time_cmd
E/QC-time-services(  466): Daemon: Time-services: Waiting to acceptconnection
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
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xfff12a08
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab3aa410, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab3ab438, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab3ac410, idLength=0xf4b686f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b6870e, maximum = 0xf4b6870f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b6877c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=3596357409
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab2c3950
D/DrmWidevineDash(  401): message_length=1611, signature=0xab2d8bd0, signature_length=0xf4b686dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/jxcore-log( 6381): Initializing JXcore engine,
W/jxcore-log( 6381): JXcore engine is ready
,W/jxcore-log( 6381): Starting JXcore engine,
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
,D/QSEECOMAPI: (  401): Loaded image: APP id = 9,
,D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf493c000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf493c000
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/DrmLibTime(  538): got the req here! ret=0
D/DrmLibTime(  538): command id, time_cmd_id = 770
D/DrmLibTime(  538): time_getutcsec starts!
D/DrmLibTime(  538): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  538): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  538): QSEE Time Listener: time_get_modem_time,
D/DrmLibTime(  538): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  538): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  538): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  538): QSEE Time Listener: Retrieved Android system time: 1454986298
D/DrmLibTime(  538): time_getutcsec returns 0, sec = 1454986298; nsec = 0
D/DrmLibTime(  538): time_getutcsec finished! 
D/DrmLibTime(  538): iotcl_continue_command finished! and return 0 
,D/DrmLibTime(  538): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
E/QC-time-services(  466): Daemon: Time-services: Waiting to acceptconnection
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
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
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xfff12a08
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab3aa600, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab3ab438, wrapped_rsa_key_length=1280,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab3ac430, idLength=0xf4a686f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/jxcore-log( 6381): Platform android
W/jxcore-log( 6381): 
W/jxcore-log( 6381): Process ARCH arm
W/jxcore-log( 6381): 
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4a6870e, maximum = 0xf4a6870f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4a6877c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=1086106741
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab3aabe0
D/DrmWidevineDash(  401): message_length=1646, signature=0xab2d8bd0, signature_length=0xf4a686dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  401): CdmEngine::CloseSession,
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  972):  packet count Tx=162 Rx=257
,E/cutils-trace( 6469): Error opening trace file: Permission denied (13),
I/dex2oat ( 6469): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6469): dex2oat: override thread count:4
,I/dex2oat ( 6469): dex2oat took 34.824ms (threads: 4)
,I/jxcore-log( 6381): JXcore Cordova bridge is ready!,
I/jxcore-log( 6381): 
W/jxcore-log( 6381): JXcore engine is started
,I/Adreno-EGL( 6436): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6436): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6436): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6436): Local Branch: 
I/Adreno-EGL( 6436): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6436): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6436):                  d74aa161a12b9c6fc6332151
,E/jxcore  ( 6381): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6381): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6381): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PMS     (  972): acquireWL(3b2e63a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 972 1000 null
W/PluginManager( 6381): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 43ms. Plugin should use CordovaInterface.getThreadPool().
W/HtcSystemUPManager(  972): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/Adreno-EGL( 6436): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6436): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6436): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6436): Local Branch: 
I/Adreno-EGL( 6436): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6436): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6436):                  d74aa161a12b9c6fc6332151
,I/FeedHostManager( 1520): [onResume],
I/FeedProviderManager( 1520): onResume
I/SocialFeedProvider( 1520): +onResume
I/SocialFeedProvider( 1520): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1520): -onResume
,D/StatusBarManagerService(  972): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
,D/FindExtension( 1520): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1520): Defer allocateBuffers to drawing time,
,I/InputMethodManagerService(  972): Disable input method client, pid=6381
,D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
I/InputMethodManagerService(  972): Enable input method client, pid=1520
,W/IInputConnectionWrapper( 6381): reportFullscreenMode on inactive InputConnection
,D/PMS     (  972): releaseWL(3b2e63a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
,I/CheckinRequestBuilder( 4408): Classify the device as Phone.
,W/BindingManager( 6381): Cannot call determinedVisibility() - never saw a connection for the pid: 6381,
,D/libc    ( 4408): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
,D/libc    ( 4408): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4408): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4408): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4408): [NET] android_getaddrinfo_proxy+
D/libc    ( 4408): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 4408): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4408): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4408): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4408): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4408): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4408): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4408): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4408): Sending checkin request (8419 bytes),
,W/OpenGLRenderer( 1520): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,I/CheckinRequestBuilder( 4408): Checkin reason type: 11 attempt count: 1,
I/ActivityManager(  972): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4408): Failed to find provider info for com.google.android.wearable.settings
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1223): WifiActivity: 3
E/WifiTrafficPoller(  972):  packet count Tx=179 Rx=271
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  972): notifying of data activity 3
,I/art     (  972): Explicit concurrent mark sweep GC freed 26422(1364KB) AllocSpace objects, 4(144KB) LOS objects, 33% free, 18MB/28MB, paused 1.571ms total 157.464ms
,I/art     ( 1886): Explicit concurrent mark sweep GC freed 9730(499KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 672us total 34.776ms
,I/GLSUser ( 1886): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1886): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1886): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1886): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4408): awaiting user notification for token,
,D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 1 40,
,I/CheckinRequestBuilder( 4408): Classify the device as Phone.
,I/CheckinTask( 4408): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4408): Checking schedule, now: 1454986300113 next: 1455523132108,
I/CheckinService( 4408): active receiver: disabled
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4408, uid=10024, userID:0
,D/PMS     (  972): releaseWL(e4dc883): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6482 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/PhoneMonitor( 6482): Register our PhoneStateListener,
,V/SetupWizard( 6482): Connected to Gservices successfully,
,D/ChimeraCfgMgr( 4408): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/Kids    ( 4408): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PhoneMonitor( 6482): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6482): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/GCM     ( 1886): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/WifiDataStallTracker(  972): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  972): updateDataStallInfo: mDataStallTxRxSum={txSum=160 rxSum=156} preTxRxSum={txSum=143 rxSum=143},
D/WifiDataStallTracker(  972): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  972): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  972):  packet count Tx=179 Rx=271
E/WifiTrafficPoller(  972): notifying of data activity 0
D/WIFI_ICON( 1223): WifiActivity: 0
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155,
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1007612096] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1007612094] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1371): environment dirty rate=29 [17][5][0]
,E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
,E/WifiStateMachine(  972): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.61 txretriesrate=0.00 rxrate=7.46 userTriggerdPenalty0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
,E/WifiStateMachine(  972):  good link -> stuck count =0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  972):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -64, 3
E/WifiStateMachine(  972): handleMessage: X
,I/HtcModeClient( 3200): handler message = 4011,
E/HtcModeClient( 3200): Check connection and retry 12 times.
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  972):  packet count Tx=179 Rx=271
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  972):  packet count Tx=179 Rx=271
,D/Process (  972): killProcessQuiet, pid=5778
I/ActivityManager(  972): Killing 5778:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5778,
,D/Process (  972): killProcessQuiet, pid=5931
I/ActivityManager(  972): Killing 5931:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5931,
,D/Process (  972): killProcessQuiet, pid=5817
I/ActivityManager(  972): Killing 5817:com.google.android.talk/u0a112 (adj 15): empty #18
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5817
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1223): WifiActivity: 3
,E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=272
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  972): notifying of data activity 3
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155,
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1007609076] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1007609075] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1371): environment dirty rate=0 [2][0][0],
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
,E/WifiStateMachine(  972): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.31 txretriesrate=0.00 rxrate=4.23 userTriggerdPenalty0
E/WifiStateMachine(  972):  good link -> stuck count =0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3,
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 60
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  972):  isHighRSSI       ---> score=65
E/WifiStateMachine(  972): handleMessage: X
D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -64, 3
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=272
E/WifiTrafficPoller(  972): notifying of data activity 0
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiDataStallTracker(  972): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  972): updateDataStallInfo: mDataStallTxRxSum={txSum=162 rxSum=157} preTxRxSum={txSum=160 rxSum=156}
D/WifiDataStallTracker(  972): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  972): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=273
D/WIFI_ICON( 1223): WifiActivity: 1
,E/WifiTrafficPoller(  972): notifying of data activity 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 3200): handler message = 4011,
,E/HtcModeClient( 3200): Check connection and retry 12 times. Stop service and kill this process.,
D/HtcModeClient( 3200): Don't start project servcice,
D/HtcModeClient( 3200): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3200): connectState: CONNECTION_READY = false
D/SilentMusic( 3200): call stop
D/HtcModeClient( 3200): close connection
,W/HtcModeClient( 3200): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3200): read the terminate packet, so break
D/Process (  972): killProcessQuiet, pid=3200
I/ActivityManager(  972): Killing 3200:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 3200,
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=273
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  972): notifying of data activity 0
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155,
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1007606050] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1007606048] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1371): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
,E/WifiStateMachine(  972): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.65 txretriesrate=0.00 rxrate=2.61 userTriggerdPenalty0
E/WifiStateMachine(  972):  good link -> stuck count =0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  972):  isHighRSSI       ---> score=61
E/WifiStateMachine(  972): handleMessage: X
D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -64, 3
,W/SystemReader(  972): Cannot find grip_rejection_width, use default value instead
,I/Prism.ItemManager( 1520): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1520): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1520): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
D/AccTypeManager( 1710): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1710): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6508 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager(  972): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneApp( 1456): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AccTypeManager( 1710): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1710): Unsupported attribute readOnly,
,W/ResourcesManager( 6508): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/PackageManager(  972): Unable to load service info ResolveInfo{4632fee com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  972): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  972): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  972): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  972): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  972): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  972): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  972): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  972): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  972): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  972): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029),
W/PackageManager(  972): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1819): DISABLE
,I/GCoreNlp( 1819): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,I/BackupManagerService(  972): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/PMS     (  972): acquireWL(28b35f6a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=273
D/PMS     (  972): releaseWL(28b35f6a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/LocationProviderProxy(  972): applying state to connected service
,D/LocationProviderProxy(  972): applying state to connected service
,D/PMS     (  972): acquireWL(210f9e0d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(20dc71c2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(210f9e0d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(20dc71c2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  972): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6533 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  972): acquireWL(2691bbd3): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{10076}
V/AlarmManager(  972): sending alarm PendingIntent{2b797310: PendingIntentRecord{12250e09 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454986307959, Int=60000
D/PMS     (  972): releaseWL(2691bbd3): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,I/Babel_SMS( 6508): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 6508): MmsConfig.loadMmsSettings
,I/ActivityManager(  972): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6561 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6508, uid=10112, userID:0
,D/SMSBackup( 6533): SMSBackupAgentService started,
D/SMSBackup( 6533): Checking restore status
D/SMSBackup( 6533): Restore complete
D/SMSBackup( 6533): cancelCheckAlarm
,D/SMSBackup( 6533): SMSBackupAgentService completed: completed in 0.0 seconds
,W/HtcWrapAdjustableCursorFactory( 6561): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,W/Settings( 6508): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 6561): onCreate
,D/MmsCustomizationProvider( 6561): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 6561): GetPrviateResource
,V/GetPrviateResource( 6561): GetPrviateResource
I/Babel_Crash( 6508): startup - clean
,D/MessageCustFlag( 6561): sense_version=6.0
,D/BTAccessoryUtil( 6561): createReceiver
,I/Babel   ( 6508): deleted: false for 0
,D/BTAccessoryUtil( 6561): registerReceiver return intent = null
,D/MmsCustomizationProvider( 6561): query uri: content://htc-mms-customization/mms-ua/ua_profile,
,D/MessageCustFlag( 6561): sku_id=118
,I/Babel_SMS( 6508): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 6508): MmsConfig.loadFromDatabase
,D/HtcBuildUtils( 6561): getRATByHtcTelephonyCapability:1
,W/SystemReader( 6561): Cannot find qct_8960_interface, use default value instead
,E/Babel_SMS( 6508): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6508): MmsConfig.loadFromResources
,E/Babel_SMS( 6508): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6508): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6508, uid=10112, userID:0,
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6508, uid=10112, userID:0,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6508, uid=10112, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6508, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6508, uid=10112, userID:0
,D/PMS     (  972): acquireWL(1d0edaca): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6508 10112 null
,W/VideoCapabilities( 6508): Unrecognized profile 2130706433 for video/avc
,I/[PluginManager]RegisterService( 1595): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1595): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4408): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4408): Null package name or gms related package.  Ignoreing.
,D/PMS     (  972): acquireWL(15849104): PARTIAL_WAKE_LOCK  AsyncService 0x1 6047 10167 null
D/PMS     (  972): releaseWL(15849104): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  972): acquireWL(7319fb3): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6047 10167 null
,D/PMS     (  972): acquireWL(263bb970): PARTIAL_WAKE_LOCK  Icing 0x1 4408 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(7319fb3): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5897): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Icing   ( 4408): updateResources: need to parse f{com.google.android.gms}
,W/VideoCapabilities( 6508): Unsupported mime video/x-ms-wmv,
,W/Utils   ( 6508): could not parse size range '64x64-1920X1080'
W/AudioCapabilities( 6508): Unsupported mime audio/qcelp
W/AudioCapabilities( 6508): Unsupported mime audio/x-ms-wma
,D/PMS     (  972): releaseWL(263bb970): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/AudioCapabilities( 6508): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6508): Unsupported mime video/x-ms-wmv,
,I/UpdateIcingCorporaServi( 5897): UpdateCorporaTask done [took 48 ms] updated apps [took 48 ms] ,
,I/VideoCapabilities( 6508): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6508): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6508): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6508): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6508): Unrecognized profile 2130706433 for video/avc
,D/Process (  972): killProcessQuiet, pid=6230
I/ActivityManager(  972): Killing 6230:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  972): Recipient 6230,
,I/vclib   ( 6508): onServiceConnected,
,W/Babel   ( 6508): Attempted to change video mute state without an active call.,
,D/PMS     (  972): releaseWL(1d0edaca): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6508): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6508): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6508): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6508): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6508): Installed default security provider GmsCore_OpenSSL
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=273
,I/Prism.ItemManager( 1520): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1520): loadItems() com.htc.launcher.pageview.WidgetManager@2576bbcc +
I/Prism.WidgetManager( 1520): onLoadItems() +
,W/ResourcesManager( 1520): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/asset   ( 1520): Copying FileAsset 0x55ab6a5b60 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1520): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1520): onLoadItems() -
I/Prism.ItemManager( 1520): loadItems() com.htc.launcher.pageview.WidgetManager@2576bbcc -
,D/PhoneApp( 1456): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1456): -- N1 =0
,D/PhoneApp( 1456): -- N2 =0,
,D/PhoneApp( 1456): -- N3 =0
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=273
,D/Messaging( 6561): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6561): networkCode: 
,D/MessageCustFlag( 6561): sku_id=118
D/MmsConfig( 6561): SIE smsPri: null
D/MmsConfig( 6561): networkCode: 
,D/MmsConfig( 6561): packageName: com.htc.vvm.att does not exist,
,D/Messaging( 6561): mNeedToUpdateDate2 start
D/ReportIndicatorCache( 6561): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6561): 
D/MmsAsyncWorkHandler( 6561): HM tk = 20001
D/ReportIndicatorCache( 6561): MSG_QUERY_REPORTS >>
,D/SettingsManager( 6561): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@38693893,
,D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1456): sku_id=118,
D/DraftCache( 6561): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6561): [DraftCache/1] refresh
,D/DraftCache( 6561): [DraftCache/161] rebuildCache
,D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1456):  slotId = -1000,
D/MmsSmsV2Provider( 1456): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66,
D/MmsSmsV2Provider( 1456):  slotId = -1000
D/MmsSmsV2Provider( 1456): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 6561): networkCode: 
,I/Messaging( 6561): mccmnc> 
D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1456):  slotId = -1000,
D/MmsSmsV2Provider( 1456): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 6561): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
D/Jerry   ( 1456): URI_DRAFT
,D/Messaging( 6561): ViewCache CreatePreloadOnlyConversationList,
,D/DraftCache( 6561): hasDraft() = false mNeedNotifyChange = true
D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1456):  slotId = -1000
D/MmsSmsV2Provider( 1456): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 6561): [DraftCache/161] rebuildCache time: 13
D/MmsAsyncWorkHandler( 6561): 
D/MmsAsyncWorkHandler( 6561): HM tk = 20002
,D/Messaging( 6561): mNeedToUpdateDate2: false,
D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
D/AccFlag ( 1456): sku_id=118
,D/MessageCustFlag( 6561): sense_version=6.0
D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/Jerry   ( 6561): start to preload cursor >>>>>>>
D/AccFlag ( 1456): sku_id=118
,D/PhoneStorageUtil( 6561): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6561): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6561): createReceiver
,D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66,
D/MmsSmsV2Provider( 1456):  slotId = -1000
,D/TelephUtils( 1456): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
V/MmsProvider( 1456): Update uri=content://mms, match=0
V/MmsProvider( 1456): selection=st=129 AND m_type!=134
D/Messaging( 6561): ViewCache CreatePreload
D/Messaging( 6561): ViewCache CreatePreloadOnlyMultipleOpsList
D/Messaging( 6561): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6561): TransactionService is going to be woken up.,
,V/TransactionService( 6561): 1-Creating TransactionService
,D/Cust_MMSMS( 6561): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6561): def_index: 0
,D/MsgPreferenceUtils( 6561): globalIndex = 1
,D/MsgPreferenceUtils( 6561): phone state: true,
D/MsgPreferenceUtils( 6561): sd state: false
D/MsgPreferenceUtils( 6561): vIndex = 0
,V/TransactionService( 6561): onStartCommand: 1,
D/MmsSystemEventReceiver( 6561): unRegisterForConnectionStateChanges
,V/TransactionService( 6561): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
V/TransactionService( 6561): Loading previous transactions.
,D/TelephUtils( 1456): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1456): device_type: 1
,D/TransactionService( 6561): Force clearing mTransactionList,
D/TransactionService( 6561): Force set service start id to 1
V/TransactionService( 6561): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6561): unRegisterForConnectionStateChanges
V/TransactionService( 6561): Destroying TransactionService
D/TransactionService( 6561): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 6561): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155,
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1007603029] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1007603028] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1371): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1371): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
,E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK,
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  972): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.33 txretriesrate=0.00 rxrate=1.31 userTriggerdPenalty0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  972):  good link -> stuck count =0
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  972):  isHighRSSI       ---> score=61
E/WifiStateMachine(  972): handleMessage: X
,D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -64, 3
,E/WifiDataStallTracker(  972): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  972): updateDataStallInfo: mDataStallTxRxSum={txSum=162 rxSum=157} preTxRxSum={txSum=162 rxSum=157},
D/WifiDataStallTracker(  972): updateDataStallInfo: NONE
D/WifiDataStallTracker(  972): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  972): WiFiStateMachine SCAN ALARM
D/PMS     (  972): acquireWL(f68f8fc): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{1000}
E/WifiStateMachine(  972): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
E/WifiStateMachine(  972): processMsg: ConnectedState
V/AlarmManager(  972): sending alarm PendingIntent{afd3fda: PendingIntentRecord{13e4cc0b android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454986310470, Int=20000
E/WifiStateMachine(  972):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:80 rssi=-64 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 list=2412 [on:0 tx:0 rx:0 period:143] from screen [on:0 period:-1007602871]
D/PMS     (  972): releaseWL(f68f8fc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:80 rssi=-64 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 list=2412 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1007602871]
E/WifiStateMachine(  972): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.33 rxSuccessRate=1.31 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-64
E/WifiStateMachine(  972): WifiStateMachine CMD_START_SCAN with age=71893 interval=60000 maxinterval=300000
E/WifiStateMachine(  972): WifiStateMachine CMD_START_SCAN try full band scan age=71893 interval=60000 maxinterval=300000
E/WifiStateMachine(  972): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  972): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1371): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1371): wpa_supplicant_scan enter
D/wpa_supplicant( 1371): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1371): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1371): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1371): WPS:  * Request Type
D/wpa_supplicant( 1371): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1371): WPS:  * UUID-E
D/wpa_supplicant( 1371): WPS:  * Primary Device Type
D/wpa_supplicant( 1371): WPS:  * RF Bands (3)
D/wpa_supplicant( 1371): WPS:  * Association State
D/wpa_supplicant( 1371): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1371): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1371): WPS:  * Manufacturer
D/wpa_supplicant( 1371): WPS:  * Model Name
D/wpa_supplicant( 1371): WPS:  * Model Number
D/wpa_supplicant( 1371): WPS:  * Device Name
D/wpa_supplicant( 1371): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1371): P2P: * P2P IE header
D/wpa_supplicant( 1371): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1371): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1371): wlan0: Add radio work 'scan'@0x55b0961860
D/wpa_supplicant( 1371): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1371): wlan0: Starting radio work 'scan'@0x55b0961860 after 0.000054 second wait
D/wpa_supplicant( 1371): wlan0: nl80211: scan request
E/WifiStateMachine(  972): [1,454,986,310,475 ms] noteScanstart no scan source
D/wpa_supplicant( 1371): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1371): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1371): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1371): wlan0: Own scan request started a scan i,n 0.000115 seconds
I/wpa_supplicant( 1371): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  972): handleMessage: X
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=273
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=273
,D/ActivityManager(  972): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{1a76fb85 #7 A=.Prism U=0 sz=1},
W/PMS     (  972): mWirelessDisplayManager is null
W/PMS     (  972): mWirelessDisplayManager is still null
,I/SensorManager(  972): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1b8360a0
I/PMS     (  972): Going to sleep due to screen timeout (uid 1000)...
W/SensorService(  972): Following SensorService logs are not warning, just make sure they are printed
I/PMS     (  972): Sleeping (uid 1000)...
W/SensorService(  972): disable: get sensor name = Accelerometer Sensor
D/XAN-DPS (  972): prepareColorFade 1
W/SensorService(  972): pid=972, uid=1000
W/PMN     (  972): goingToSleep
W/SensorService(  972): Active sensors: size = 4
D/PMS     (  972): acquireWL(1329cdda): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 972 1000 null
W/SensorService(  972): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  972): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  972): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  972): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  972): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1b8360a0, eanble = 0, strlen(mName) = 91
W/SensorService(  972): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  972): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@9bbe94c
W/SensorService(  972): Listener[1] = com.htc.smartdim.sensor_eye@1c7ffb5d
W/SensorService(  972): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/Adreno-EGL(  972): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  972): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  972): Build Date: 03/09/15 Mon
I/Adreno-EGL(  972): Local Branch: 
I/Adreno-EGL(  972): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  972): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  972):                  d74aa161a12b9c6fc6332151
W/PMN     (  972): goingToSleep done
,I/FeedHostManager( 1520): [onPause]
I/FeedProviderManager( 1520): onPause
,I/SocialFeedProvider( 1520): +onPause
I/FeedHostManager( 1520): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2ffa858b
I/SocialFeedProvider( 1520): -onPause
,W/HtcLockScreen( 1223): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/ActivityManager(  972): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6627 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
D/AlarmManager(  972): ACTION_SCREEN_ON
,W/HtcSystemUPManager(  972): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  972): releaseWL(1329cdda): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/AlarmManager(  972): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  972): [AlarmQueuing] done recovering
I/AlarmManager(  972): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  972): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL true Token 11
,E/WifiTrafficPoller(  972):  packet count Tx=181 Rx=273,
E/WifiDataStallTracker(  972): ENABLE_DATA_MONITOR_POLL true Token 1
,E/WifiStateMachine(  972): handleMessage: E msg.what=131167
E/WifiStateMachine(  972): processMsg: ConnectedState
,E/WifiStateMachine(  972):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
E/WifiStateMachine(  972):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
D/wpa_supplicant( 1371): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1371): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1371): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1371): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1371): wlan0: Scan completed in 2.098976 seconds
D/WifiDataStallTracker(  972): updateDataStallInfo: mDataStallTxRxSum={txSum=162 rxSum=157} preTxRxSum={txSum=162 rxSum=157}
D/wpa_supplicant( 1371): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1371): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1371): nl80211: Received scan results (5 BSSes)
D/WifiDataStallTracker(  972): updateDataStallInfo: NONE
D/wpa_supplicant( 1371): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1371): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-55
I/wpa_supplicant( 1371): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-64
I/wpa_supplicant( 1371): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-64
D/WifiDataStallTracker(  972): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/wpa_supplicant( 1371): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
I/wpa_supplicant( 1371): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1371): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1371): wlan0: BSS: Add new id 4 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 1371): BSS: last_scan_res_used=5/32
D/wpa_supplicant( 1371): wlan0: Scan-only results received
D/wpa_supplicant( 1371): wlan0: Radio work 'scan'@0x55b0961860 done in 2.100270 seconds
E/WifiStateMachine(  972):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  972): processMsg: DefaultState
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 38:f8:89:11:e9:11]
E/WifiStateMachine(  972):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  972): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  972):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
,D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1371): SET_SCREEN_ON:On
I/wpa_supplicant( 1371): htc_wext_set_keepalive +
I/wpa_supplicant( 1371): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1371): getPrivFuncNum +	
I/wpa_supplicant( 1371): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1371): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1371): htc_wext_set_keepalive - ret = 0
D/NetworkPolicy(  972): updateScreenOn: false
I/wpa_supplicant( 1371): htc_wext_set_TX_TRACKING (1)+
V/NetworkPolicy(  972): updateIfacesLocked()
I/wpa_supplicant( 1371): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  972): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  972): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  972): handleScreenStateChanged Exit: true
V/SRS_Proc(  401): ParamSet string: screen_state=on
E/WifiStateMachine(  972): handleMessage: X
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  972): handleMessage: E msg.what=147461
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
D/NetworkManagementService(  972): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  972):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1371): wlan0: Control interface command 'LIST_DONGLES'
D/WifiController(  972): handleMessage: E msg.what=155650
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
E/WifiStateMachine(  972): [1,454,986,312,583 ms] noteScanEnd no scan source
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1371): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  972): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3dfc1e6f sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  972): NG7005g c0:ff:d4:d3:aa:4a rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,E/WifiAutoJoinController (  972): NG700 c0:ff:d4:d3:aa:48 rssi=-64 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  972): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  972): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  972):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-64 freq=2412
E/WifiAutoJoinController (  972): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  972): 01ABC c2:ff:d4:d3:aa:48 rssi=-64 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  972): Gonzos 38:f8:89:11:e9:11 rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  972): ageScanResultsOut delay 40000 size 5 now 1454986312588
E/WifiAutoJoinController (  972): newSupplicantResults size=5 known=1 true
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1371): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  972): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  972): ssid=NG700
E/WifiAutoJoinController (  972): id=0
E/WifiAutoJoinController (  972): mode=station
E/WifiAutoJoinController (  972): pairwise_cipher=CCMP
E/WifiAutoJoinController (  972): group_cipher=CCMP
E/WifiAutoJoinController (  972): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  972): wpa_state=COMPLETED
E/WifiAutoJoinController (  972): ip_address=192.168.1.130
E/WifiAutoJoinController (  972): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  972): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  972): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  972): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  972): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-64,-127) num=(1,0)
E/WifiAutoJoinController (  972): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  972): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-64 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  972): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  972): Done attemptAutoJoin status=0
E/WifiConfigStore(  972):  writeKnownNetworkHistory() num networks:1 needWrite=false
,E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131154
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
,E/WifiStateMachine(  972): processMsg: L2ConnectedState
D/WifiManager( 1819): getScanResults: Base Package Name=com.google.android.gms, uid=10024
E/WifiStateMachine(  972):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1371): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
,E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131127
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  972): handleMessage: X
,E/WifiStateMachine(  972): handleMessage: E msg.what=131129
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
,E/WifiStateMachine(  972):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
W/ResourcesManager( 6627): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/WifiStateMachine(  972):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1371): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1371): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  972): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiStateMachine(  972): handleMessage: X
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=35 dispatchEvent: BLACKLIST CLEAR 
,D/GpsLocationProvider(  972): receive broadcast intent, action: android.intent.action.SCREEN_ON,
,D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
,I/CalendarProvider2( 6627): Created com.android.providers.calendar.CalendarAlarmManager@d541ccd(com.htc.providers.calendar.HtcCalendarProvider@2124e982),
D/XAN-DPS (  972): prepareColorFade done
,I/IntentController( 1223): receive(android.intent.action.SCREEN_ON,1,false)
D/XAN-DPS (  972): setBrightness to 0
,D/CalendarProvider2( 6627): wait start:true,
,I/SensorManager(  972): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@9bbe94c
W/SensorService(  972): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  972): disable: get sensor name = CM32181 Light sensor
,I/DisplayManagerService(  972): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DotMatrix( 1313): [EventService]  onDisplayChanged: 0
V/ActivityManager(  972): Display changed displayId=0
,D/DotMatrix( 1313): [EventService] mbHDMIConnect: false, mCoverOn:false
W/SensorService(  972): pid=972, uid=1000
,W/SensorService(  972): Active sensors: size = 3
W/SensorService(  972): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  972): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  972): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  972): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@9bbe94c, eanble = 0, strlen(mName) = 66
W/SensorService(  972): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  972): Listener[0] = com.htc.smartdim.sensor_eye@1c7ffb5d
W/SensorService(  972): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/PMS     (  972): acquireWL(335a992c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  972): acquireWL(1c46cff5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(1c46cff5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(335a992c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 6627): wait end:false,
,I/ActivityManager(  972): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6656 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/AlarmManager(  972): ACTION_SCREEN_OFF,
I/AlarmManager(  972): [AlarmQueuing] screen off now: 
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 12
,I/AlarmManager(  972): [AlarmQueuing] data connection: true
D/WifiDataStallTracker(  972): stopDataStallAlarm 
I/AlarmManager(  972): [AlarmQueuing] wifi connection: true
E/WifiDataStallTracker(  972): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  972): handleMessage: E msg.what=131167
E/WifiStateMachine(  972): processMsg: ConnectedState
,E/WifiStateMachine(  972):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
V/SRS_Proc(  401): ParamSet string: screen_state=off
E/WifiStateMachine(  972):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  972):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  972):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1371): SET_SCREEN_ON:Off
I/wpa_supplicant( 1371): htc_wext_set_keepalive +
I/wpa_supplicant( 1371): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
D/wpa_supplicant( 1371): getPrivFuncNum +	
I/wpa_supplicant( 1371): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1371): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1371): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1371): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1371): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  972): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  972): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  972): handleScreenStateChanged Exit: false
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131154
E/WifiStateMachine(  972): processMsg: ConnectedState
,E/WifiStateMachine(  972):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  972): handleMessage: X
D/WifiController(  972): handleMessage: E msg.what=155651
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/NetworkPolicy(  972): updateScreenOn: false
V/NetworkPolicy(  972): updateIfacesLocked()
,D/GpsLocationProvider(  972): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/SensorManager( 1223): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@2e534736, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
D/NetworkManagementService(  972): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/SensorService(  972): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  972): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  972): pid=1223, uid=10041
W/SensorService(  972): Active sensors: size = 4
W/SensorService(  972): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  972): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  972): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  972): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  972): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@2e534736, eanble = 1, strlen(mName) = 57
W/SensorService(  972): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  972): Listener[0] = com.htc.smartdim.sensor_eye@1c7ffb5d
W/SensorService(  972): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@2e534736
W/SensorService(  972): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1313): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1456): start background delete task...
,I/IntentController( 1223): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1456): size: 0 , 0,
D/ContactMessageStore( 1456): Background delete complete
,D/PMS     (  972): acquireWL(306e1c18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  972): releaseWL(306e1c18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
W/ContextImpl( 6656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  972): acquireWL(3e017671): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(3e017671): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6656): MY_DEBUG = false,
D/SmartSyncUtils( 6656): isEpsOn(), nState = 0
,I/RemoteViews( 1223): setHTCTheme(com.htc.updater,true,33751145),
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL false Token 13 num clients 6
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  972): Excessive delay in setPowerMode(): 296ms
D/PMS     (  972): acquireWL(2634e1c4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6656 1000 null
D/PMS     (  972): Setting HAL interactive mode to false
D/PMS     (  972): Setting HAL interactive mode to false done
D/PMS     (  972): Setting HAL auto-suspend mode to true
D/PMS     (  972): Setting HAL auto-suspend mode done
I/RemoteViews( 1223): apply : com.htc.updater 0 13 2 36
I/InputMethodManagerService(  972): screenObserver, isScreenOn=false
W/HtcSystemUPManager(  972): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  972): Disable input method client, pid=1520
,D/HABCtrl (  972): TPE algorithm. remove timeout.
,D/PMS     (  972): OOBE c monitor 11
I/InputManager(  972): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1223): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  972): acquireWL(2e608ad): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
,I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2e608ad): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  972): plugged=true pluggin=true
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
,D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NfcService( 1484): ScreenObserver: OFF
D/NfcService( 1484): applyRouting - 0
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/PowerUI ( 1223): closing low battery warning: level=100
,D/PMS     (  972): acquireWL(356497e2): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1484 1027 null
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NfcService( 1484): applyRouting -2
D/NfcService( 1484): applyRouting
D/NfcService( 1484): Ignore this applyRouting...
D/PMS     (  972): releaseWL(356497e2): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ActivityManager(  972): Killing 6254:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=6254
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  972): releaseWL(2634e1c4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ClockController( 1223): stop clock update:screen off
I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/art     (  972): Explicit concurrent mark sweep GC freed 36112(2014KB) AllocSpace objects, 4(464KB) LOS objects, 33% free, 18MB/28MB, paused 1.367ms total 153.433ms,
,I/ActivityManager(  972): Recipient 6254,
,W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartDim(  972): Init customizeScreenOffDelayClass error
,W/ContextImpl( 6656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 6656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 6656): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6656): isEpsOn(), nState = 0
,W/ContextImpl( 6656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
,I/SensorManager(  972): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1c7ffb5d,
W/SensorService(  972): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  972): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  972): pid=972, uid=1000
,W/SensorService(  972): Active sensors: size = 3
W/SensorService(  972): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  972): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  972): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  972): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1c7ffb5d, eanble = 0, strlen(mName) = 36
W/SensorService(  972): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  972): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2e534736
W/SensorService(  972): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  972): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  972): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  972): pid=972, uid=1000,
W/SensorService(  972): Active sensors: size = 2
W/SensorService(  972): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  972): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  972): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1c7ffb5d, eanble = 0, strlen(mName) = 36
W/SensorService(  972): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  972): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2e534736
,W/SensorService(  972): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  972): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1c7ffb5d
,E/ActivityThread(  972): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@28028cd2 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  972): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@28028cd2 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  972): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  972): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  972): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  972): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  972): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  972): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  972): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  972): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  972): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  972): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  972): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  972): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  972): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  972): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  972): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  972): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  972): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  972): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  972): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155
,E/WifiStateMachine(  972): processMsg: ConnectedState
I/ActivityManager(  972): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6690 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
E/WifiStateMachine(  972):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2857] from screen [on:0 period:-1007600012] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
I/PowerUsageList:PowerUsageHelper( 6656): PowerProfile::POWER_SCREEN_FULL = 154.8
E/WifiStateMachine(  972):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1007600011] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972): handleMessage: X,
,D/PowerUsageList:BatterySipperExt( 6656): gen(), null == sipper.uidObj, userId = 0,
,D/Process (  972): killProcessQuiet, pid=6021,
I/ActivityManager(  972): Killing 6021:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6656): getMobilePolicyEnabled, result = true
,D/WifiService(  972): New client listening to asynchronous messages
,E/WifiTrafficPoller(  972): ADD_CLIENT: 7
,I/ActivityManager(  972): Recipient 6021
,D/Process (  972): killProcessQuiet, pid=5421
I/ActivityManager(  972): Killing 5421:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL false Token 13 num clients 7
,I/ActivityManager(  972): Recipient 5421
,D/PowerUsageList:PowerUsageHelper( 6656): MY_DEBUG = false
,I/CalendarProvider2( 6627): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6627): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 6326): ---------------------------------------------------
D/ProviderChangeReceiver( 6326): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 6326): start to updateAlertNotification!
,I/ActivityManager(  972): Killing 6283:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  972): killProcessQuiet, pid=6283
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6283
,D/PMS     (  972): releaseWL(3dd44fc4): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/HtcAlertService( 6326): No fired or scheduled alerts
,D/HtcAlertUtils( 6326): -- cancelReminderNotification --
,D/HtcAlertUtils( 6326): broadcastExistReminder!
,D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  972): killProcessQuiet, pid=5453
,I/ActivityManager(  972): Killing 5453:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5453
,E/WifiDataStallTracker(  972): DATA_MONITOR_POLL false Token 3
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2272] from screen [on:0 period:-1007597738] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1007597735] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972): handleMessage: X
,D/HtcUPManager( 1223): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  972): DATA_MONITOR_POLL false Token 3
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  972): killProcessQuiet, pid=5607
I/ActivityManager(  972): Killing 5607:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5607
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/ContactMessageStore( 1456): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1456): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  972): acquireWL(300782a9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
,V/AlarmManager(  972): sending alarm PendingIntent{3084e5ad: PendingIntentRecord{375eb0e2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=118106, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{34b8502e: PendingIntentRecord{c7c57cf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141028, Int=0
,D/PMS     (  972): releaseWL(300782a9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  972): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  972): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  972): acquireWL(2ccca55c): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 972 1000 null
,D/libc    (  972): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  972): [NET] android_getaddrinfofornet-, err=8
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  972): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  972): [NET] android_getaddrinfo_proxy+
D/libc    (  972): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  972): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  972): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  972): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  972): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  972): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  972):  [handleDownloadXtraData]inject done.
D/PMS     (  972): acquireWL(3e2cbb48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 972 1000 null
D/GpsLocationProvider(  972): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  972): releaseWL(2ccca55c): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  972): releaseWL(3e2cbb48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  972): acquireWL(3bcbdde1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
,D/PMS     (  972): releaseWL(3bcbdde1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true,
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PMS     (  972): runPSCheck
D/WifiController(  972): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: StaEnabledState
,D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): << updateStatus
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1456): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  972): acquireWL(106e3706): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{285571c7: PendingIntentRecord{3bf643f4 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454986367984, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{3084e5ad: PendingIntentRecord{375eb0e2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=178106, Int=0,
V/AlarmManager(  972): sending alarm PendingIntent{1347771d: PendingIntentRecord{3926bd92 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=199210, Int=0
D/PMS     (  972): acquireWL(142d6363): PARTIAL_WAKE_LOCK  *backup* 0x1 972 1000 null
,V/AlarmManager(  972): sending alarm PendingIntent{2d2dab60: PendingIntentRecord{12e96819 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189889, Int=0
,D/PMS     (  972): acquireWL(76f20de): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  972): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  972): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  972): releaseWL(142d6363): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  972): releaseWL(106e3706): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  972): acquireWL(1008d2bf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): releaseWL(76f20de): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  972): releaseWL(1008d2bf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(23770151): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(23770151): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  972): acquireWL(31b86db6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(31b86db6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(2db85ab7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(3ac9224): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(2855af42): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): releaseWL(2db85ab7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1886): Vacuum at: now=1454986401397 tag=VacuumService
,D/PMS     (  972): releaseWL(3ac9224): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): acquireWL(1632ac90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1886): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1886): No account for auth token provided,
,D/PMS     (  972): releaseWL(1632ac90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(2b878989): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(2b878989): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1886): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1886): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1886): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1886): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1886): [NET] android_getaddrinfo_proxy+
D/libc    ( 1886): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1886): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1886): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1886): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1886): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1886): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1886): No account for auth token provided
,W/Uploader( 1886):  no longer exists, so no auth token.,
,W/Uploader( 1886): No account for auth token provided,
,W/Uploader( 1886): No account for auth token provided,
,I/GLSUser ( 1886): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1886): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1886): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1886): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 2 40
E/Uploader( 1886): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1886): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1886): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1886): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1886): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1886): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1886): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1886): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1886): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1886): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1886): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
,E/Uploader( 1886): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1886): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  972): releaseWL(2855af42): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  972): acquireWL(dbc6cf2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(dbc6cf2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  972): acquireWL(37984f43): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(37984f43): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1595): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@9c772bc
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
I/ActivityManager(  972): Killing 6381:com.test.thalitest/u0a366 (adj 15): empty #17
,D/Process (  972): killProcessQuiet, pid=6381
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6381
E/InputEventReceiver( 1393): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{7443cd0 uid 10366 pid 6381} (c)'
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  972): acquireWL(24d259c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/BatteryService(  972): n_update end
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): releaseWL(24d259c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/NotificationService(  972): plugged=true pluggin=true
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: StaEnabledState
D/HtcPowerSaver(  972): updateBatteryInfo
D/WifiController(  972): processMsg: DefaultState
D/PMS     (  972): runPSCheck
D/WifiController(  972): handleMessage: X
,D/HtcPowerSaver(  972): Checking...
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 4
,D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/PMS     (  972): acquireWL(2f68e6f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  972): n_update end
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): releaseWL(2f68e6f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PMS     (  972): runPSCheck
,D/WifiController(  972): handleMessage: E msg.what=155652
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1371): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 4 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  972): acquireWL(3a0663e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{3084e5ad: PendingIntentRecord{375eb0e2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=238106, Int=0,
V/AlarmManager(  972): sending alarm PendingIntent{3d6351ec: PendingIntentRecord{2ec7f9b5 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454986541722, Int=0
,D/PMS     (  972): releaseWL(3a0663e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  972): acquireWL(3038a84a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(3038a84a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): runPSCheck
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): Checking...
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  972): >> updateStatus
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): << updateStatus
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1886): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1886): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1886): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1886): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1886): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1886): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1886): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1886): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1886): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1886): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1886): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5979): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5979): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5979): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5979): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5979): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5979): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5979): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/System  ( 5979): Ignoring header User-Agent because its value was null.
,D/libc    ( 5979): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5979): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5979): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5979): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5979): [NET] android_getaddrinfo_proxy+
D/libc    ( 5979): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5979): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): acquireWL(1dd50e1c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/BatteryService(  972): n_update end
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/PMS     (  972): releaseWL(1dd50e1c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/NotificationService(  972): plugged=true pluggin=true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  972): updateBatteryInfo
D/PMS     (  972): runPSCheck
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): Checking...
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  972): acquireWL(23abba25): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): releaseWL(23abba25): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972): onReceive BATTERY_CHANGED,
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PMS     (  972): runPSCheck
D/WifiController(  972): handleMessage: E msg.what=155652
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): << updateStatus
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  972): acquireWL(2073b7fa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2073b7fa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo
D/PMS     (  972): runPSCheck
D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): << updateStatus
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 5
,D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/PMS     (  972): acquireWL(18afb1ab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  972): n_update end
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): releaseWL(18afb1ab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1456): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1456): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1456): sku_id=118
,D/ContactMessageStore( 1456): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1456): start background delete task...
,D/ContactMessageStore( 1456): size: 0 , 0,
D/ContactMessageStore( 1456): Background delete complete
,D/PMS     (  972): acquireWL(2032f008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2032f008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HtcPowerSaver(  972): updateBatteryInfo
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
,D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(2902d3a1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2902d3a1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo,
,D/PMS     (  972): runPSCheck,
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): Checking...
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): << updateStatus
,D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(223559c6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(223559c6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo
,D/UsbnetService(  972): BroadcastReceiver::onReceive+,
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(735bd87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(735bd87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): runPSCheck
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): << updateStatus
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(f0b04b4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
,V/AlarmManager(  972): sending alarm PendingIntent{3084e5ad: PendingIntentRecord{375eb0e2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=358106, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{1a5808dd: PendingIntentRecord{21d4c52 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=939643, Int=0
,I/bt-btm  ( 3083): Received oneshot timer event complete
I/bt-btm  ( 3083): btm_ble_timeout
I/bt-btm  ( 3083): btm_gen_resolvable_private_addr
,D/PMS     (  972): acquireWL(2d26ab23): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3083 1002 null
,D/PMS     (  972): releaseWL(f0b04b4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/bt-btm  ( 3083): btm_ble_rand_enc_complete
I/bt-btm  ( 3083): btm_gen_resolve_paddr_low
D/bt-smp  ( 3083): smp_encrypt_data
W/bt-smp  ( 3083): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3083): Plain text(LSB ~ MSB) = 42 5d 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 3083): Encrypted text(LSB ~ MSB) = 97 40 3a 58 f9 ce a4 c3 98 2d 73 2e 9d 60 2c df 
I/bt-btm  ( 3083): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3083): Stopping oneshot timer
D/bt-btm  ( 3083): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  972): releaseWL(2d26ab23): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  972): acquireWL(1adb820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
,I/BatteryService(  972): n_update end,
D/PMS     (  972): releaseWL(1adb820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): processMsg: DefaultState
D/NotificationService(  972): plugged=true pluggin=true
D/WifiController(  972): handleMessage: X
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(2dd155d9): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{1000},
,V/AlarmManager(  972): sending alarm PendingIntent{363dc458: PendingIntentRecord{1e2f99b1 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805165, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{3084e5ad: PendingIntentRecord{375eb0e2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=958106, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{11aed67f: PendingIntentRecord{387ab731 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454986840245, Int=0
,D/Finsky  ( 5979): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  972): sending alarm PendingIntent{3206364c: PendingIntentRecord{3bf87695 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936338, Int=0
D/PMS     (  972): acquireWL(92a13aa): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(92a13aa): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  972): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6729 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  972): sending alarm PendingIntent{2b866b38: PendingIntentRecord{2236e711 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454987132390, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{1111e34d: PendingIntentRecord{2ce516a7 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454987167434, Int=0
,D/PMS     (  972): acquireWL(126d6e02): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  972): acquireWL(182f6950): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1886): Message class com.google.f.a.a.i
D/PMS     (  972): releaseWL(2dd155d9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/WeatherUtility( 1223): Weather sync is On
,D/PowerUsageList:PowerUsageHelper( 6656): MY_DEBUG = false
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
D/PMS     (  972): releaseWL(182f6950): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageService( 6656): repeat time = 1454988067527
,D/PMS     (  972): acquireWL(948684e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): releaseWL(126d6e02): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1886): Using platform SSLCertificateSocketFactory,
,I/PowerUsageList:PowerUsageHelper( 6656): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6656): gen(), null == sipper.uidObj, userId = 0,
,I/GLSUser ( 1886): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1886): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1886): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1886): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/cutils-trace( 6753): Error opening trace file: Permission denied (13)
I/dex2oat ( 6753): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6753): dex2oat: override thread count:4
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  972): releaseWL(948684e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(1b32caac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
W/Finsky  ( 5979): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/PMS     (  972): releaseWL(1b32caac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  972): acquireWL(2bf141f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): releaseWL(2bf141f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1886): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1886): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1886): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1886): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1886): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1886): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1886): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1886): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5979): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1886): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1886): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1886): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1886): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 6753): dex2oat took 691.608ms (threads: 4),
,W/Finsky  ( 5979): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 5979): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,I/PushClient( 6729): ApplicationMonitor {1c1969fc}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,D/Finsky  ( 5979): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5979): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2),
I/PushClient( 6729): ApplicationMonitor {1c1969fc}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6729): ApplicationMonitor {1c1969fc}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6729): ApplicationMonitor {1c1969fc}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6729): ApplicationMonitor {1c1969fc}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6729): ApplicationMonitor {1c1969fc}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
D/DeviceConnectionService( 1819): client connected with version: 7571000
I/PushClient( 6729): ApplicationMonitor {1c1969fc}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6729): ApplicationMonitor {1c1969fc}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6729): ApplicationMonitor {1c1969fc}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/PushClient( 6729): PnsModel {5e4caef}: update(): Update registration caused by: alarm
,I/PushClient( 6729): PnsConfigModel {1aeeb732}: <init>(): Use dm-client for provisioning.
,W/System.err( 6729): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6729): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6729): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6729): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  972): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6764 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6764): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6764 dbg=false s=true,
,I/DeviceManagement( 6764): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6764): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6764): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6764): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6764): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2ebc1bce] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6764): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6764): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6764): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6764): SessionStateController: Checking invariants...
,I/art     (  972): Explicit concurrent mark sweep GC freed 36449(1880KB) AllocSpace objects, 8(1580KB) LOS objects, 33% free, 18MB/28MB, paused 1.696ms total 156.875ms,
,I/DeviceManagement( 6764): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 6764): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6764): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6764): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2ebc1bce],
,I/DeviceManagement( 6764): WorkflowService: Stopping workflow service
,I/PushClient( 6729): PnsModel {5e4caef}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  972): killProcessQuiet, pid=6482
,I/ActivityManager(  972): Killing 6482:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6482,
,D/Process (  972): killProcessQuiet, pid=6436
I/ActivityManager(  972): Killing 6436:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6436
,D/PMS     (  972): acquireWL(1b90509): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{10072}
,V/AlarmManager(  972): sending alarm PendingIntent{946130e: PendingIntentRecord{1778912f com.android.vending startService}}, i=null, t=0, cnt=1, w=1454987183035, Int=0
D/PMS     (  972): releaseWL(1b90509): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 5979): [607] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5979): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  972): acquireWL(33ec533c): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{1000}
,V/AlarmManager(  972): sending alarm PendingIntent{3963e8c5: PendingIntentRecord{2dd4521a com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454987213277, Int=0
,D/SmartSyncUtils( 6656): isEpsOn(), nState = 0,
,D/PMS     (  972): releaseWL(33ec533c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  972): acquireWL(e87114b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6656 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6656): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6656): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6656): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6656): SettingOnTime = 1454997600000, randomSettingOnTime = 1454994366000
D/SmartSyncScreenOnOffTimeReceiver( 6656): SettingOffTime = 1455062400000, randomSettingOffTime = 1455063973000
,D/SmartSyncScreenOnOffTimeReceiver( 6656): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6656): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6656): bNightModeTurnOffOnce = false
,D/PMS     (  972): acquireWL(1c96728): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{111f4c41: PendingIntentRecord{ed575e6 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1454987213322, Int=0
,D/PMS     (  972): releaseWL(e87114b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncDataLinkTurnOffService( 6656): SMARTSYNC_TURN_OFF_NETWORK, current time = 1454987213342, randomOffTime = 1455063973000, newRandomOffTime = 1455063973000,
,D/SmartSyncDataLinkTurnOffService( 6656): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 1454994366000, randomMobileOnTime = 1454994366000
,D/SmartSyncUtils( 6656): getMobilePolicyEnabled, result = true,
D/SmartSyncDataLinkTurnOffService( 6656): turnOffMobile bPolicyEnabled = true
,D/SmartSyncUtils( 6656): isWifiHotSpotEnabled = false,
,D/SmartSyncDataLinkTurnOffService( 6656): turnOffMobile bCheckMobileData = false
,D/PMS     (  972): releaseWL(1c96728): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/LocationManagerService(  972): getProviders()=[gps, network]
,D/LocationManagerService(  972): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  972): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 6656): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6656): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 6656): turnOffWifi ui setting = true
,D/SmartSyncUtils( 6656): isWifiHotSpotEnabled = false,
,I/ActivityManager(  972): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6656): Failed to find provider info for com.htc.vowifi
,D/SmartSyncUtils( 6656): state = 0
,D/SmartSyncDataLinkTurnOffService( 6656): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 6656): turnOffWifi bWifiConnected = true,
,D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): acquireWL(39e1cdd4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
I/BatteryService(  972): n_update end
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): releaseWL(39e1cdd4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PMS     (  972): runPSCheck
D/WifiController(  972): handleMessage: E msg.what=155652
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(37d36b7d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): releaseWL(37d36b7d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): updateBatteryInfo
,D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): handleMessage: X
D/NotificationService(  972): plugged=true pluggin=true
D/WifiController(  972): battery changed pluggedType: 2
,D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(f730a72): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
I/BatteryService(  972): n_update end
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): releaseWL(f730a72): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  972): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(27565ec3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
,V/AlarmManager(  972): sending alarm PendingIntent{3084e5ad: PendingIntentRecord{375eb0e2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1018106, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{1e77f340: PendingIntentRecord{28b04279 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1454987393431, Int=0
W/ContextImpl( 6656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  972): releaseWL(27565ec3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
D/SmartSyncDataLinkTurnOffService( 6656): turnOffWifi ui setting = true
D/SmartSyncUtils( 6656): isWifiHotSpotEnabled = false
,I/ActivityManager(  972): Cannot resolve ContentProvider=com.htc.vowifi,
E/ActivityThread( 6656): Failed to find provider info for com.htc.vowifi
,D/SmartSyncUtils( 6656): state = 0
,D/SmartSyncDataLinkTurnOffService( 6656): turnOffWifi bCheckWifiData = false,
D/SmartSyncDataLinkTurnOffService( 6656): turnOffWifi bWifiConnected = true
,D/LocationManagerService(  972): getProviders()=[gps, network]
D/LocationManagerService(  972): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  972): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1],
D/SmartSyncDataLinkTurnOffService( 6656): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6656): isCharging status = 5,
,D/PMS     (  972): acquireWL(eb6241f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(eb6241f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  972): Checking...
,I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
,D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  972): User[0] Flushing usage stats to disk
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  972): acquireWL(1189036c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/BatteryService(  972): n_update end
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): releaseWL(1189036c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  972): updateBatteryInfo
D/WifiController(  972): handleMessage: E msg.what=155652
D/PMS     (  972): runPSCheck
D/WifiController(  972): processMsg: DeviceActiveState
D/HtcPowerSaver(  972): Checking...
D/HeadsetStateMachine( 3083): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
