#### Test 584164489c56086_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  942):  packet count Tx=192 Rx=277
E/WifiStateMachine(  942): handleMessage: E msg.what=131155
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-984275636] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-984275634] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1359): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  942): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  942): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.50 txretriesrate=0.00 rxrate=0.88 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  942):  isHighRSSI       ---> score=61
E/WifiStateMachine(  942): handleMessage: X
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
--------- beginning of system
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiDataStallTracker(  942): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  942): updateDataStallInfo: mDataStallTxRxSum={txSum=172 rxSum=163} preTxRxSum={txSum=172 rxSum=163}
D/WifiDataStallTracker(  942): updateDataStallInfo: NONE
D/WifiDataStallTracker(  942): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  942):  packet count Tx=192 Rx=278
D/WIFI_ICON( 1220): WifiActivity: 1
E/WifiTrafficPoller(  942): notifying of data activity 1
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/HtcModeClient( 3199): handler message = 4011
E/HtcModeClient( 3199): Check connection and retry 11 times.
E/cutils-trace( 6397): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6397): ====startRecUseTime====
D/htc.customization.log.level( 6397):  is 
W/CustomizationLogLevel( 6397): Level value is invalid, use default level 2
D/CustomizationManager( 6397):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6397): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6397): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6397): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6397): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6397): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6397): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6397): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6397): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6397): Parsing tag category name = system
I/CustomizationCIDLoader( 6397): Parsing tag category name = application
I/CustomizationCIDLoader( 6397): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6397): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6397): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6397): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6397): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6397): add string-array item, value = 42507
I/CustomizationCIDLoader( 6397): add string-array item, value = 21902
I/CustomizationCIDLoader( 6397): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6397): add string-array item, value = 23420
I/CustomizationCIDLoader( 6397): add string-array item, value = 22299
I/CustomizationCIDLoader( 6397): add string-array item, value = 24002
I/CustomizationCIDLoader( 6397): add string-array item, value = 23210
I/CustomizationCIDLoader( 6397): add string-array item, value = 23205
I/CustomizationCIDLoader( 6397): add string-array item, value = 23806
I/CustomizationCIDLoader( 6397): add string-array item, value = 23430
I/CustomizationCIDLoader( 6397): add string-array item, value = 23408
I/CustomizationCIDLoader( 6397): add string-array item, value = 27205
I/CustomizationCIDLoader( 6397): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6397): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6397):  Read CID file spent 0.099 (s)
D/CustomizationManager( 6397):  All configurations done spent 0.100 (s)
I/ActivityManager(  942): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6397 on display 0
D/PMS     (  942): acquireHCC(16b1608d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 942 1000 null
D/PMS     (  942): acquireHCC(2eff4242): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 942 1000 null
W/asset   (  942): Copying FileAsset 0x55a2d064d0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  942): acquireWL(30607889): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 942 1000 null
I/AnimationUtil(  942): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1622): [onPause]
I/FeedProviderManager( 1622): onPause
I/SocialFeedProvider( 1622): +onPause
I/SocialFeedProvider( 1622): -onPause
I/FeedHostManager( 1622): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3a2997e6
W/HtcSystemUPManager(  942): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  942): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6415 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  942): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  942): hiding MENU key
W/asset   ( 6415): Copying FileAsset 0xac5b7968 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1622): [trimMemory] 20
,I/WebViewFactory( 6415): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6415): Time to load native libraries: 10 ms (timestamps 5779-5789)
,I/LibraryLoader( 6415): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6415): Binding Chromium to main looper Looper (main, tid 1) {355773c1}
,I/LibraryLoader( 6415): Expected native library version number "",actual native library version number ""
,I/chromium( 6415): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6415): Initializing chromium process, singleProcess=true
,W/art     ( 6415): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6415): ApplicationContext is null in ApplicationStatus
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
W/chromium( 6415): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/WifiTrafficPoller(  942):  packet count Tx=192 Rx=278
D/WIFI_ICON( 1220): WifiActivity: 0
E/WifiTrafficPoller(  942): notifying of data activity 0
,D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/libEGL  ( 6415): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6415): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6415): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6415): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6415): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6415): Local Branch: 
I/Adreno-EGL( 6415): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6415): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6415):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  942): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29fd0cec:true
,W/System.err(  942): java.lang.Throwable: stack dump
W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  942): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  942): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6415): 673614589: getState(). Returning 12
,W/art     ( 6415): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6415): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6415): CordovaWebView is running on device made by: HTC,
,W/art     ( 6415): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6415): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6415): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/FindExtension( 6415): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6415): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@36e43369, mServedView=org.apache.cordova.engine.SystemWebView{130a11ee VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@38d4568f
,I/InputMethodManagerService(  942): Disable input method client, pid=1622,
I/ActivityManager(  942): Displayed com.test.thalitest/.MainActivity: +778ms
D/StatusBarManagerService(  942): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  942): Enable input method client, pid=6415
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
,D/PMS     (  942): releaseWL(30607889): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/BindingManager( 6415): Cannot call determinedVisibility() - never saw a connection for the pid: 6415,
,W/XT9_C   ( 1400): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1400): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/JsMessageQueue( 6415): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6415): JniHelper::setJavaVM(0xab45e8f8), pthread_self() = -1401510384
,I/chromium( 6415): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  942):  packet count Tx=192 Rx=278
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155,
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-984272614] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-984272613] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1359): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72,
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  942): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  942): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.25 txretriesrate=0.00 rxrate=0.94 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  942):  isHighRSSI       ---> score=61
,D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  942): handleMessage: X
,W/jxcore-log( 6415): Initializing JXcore engine
W/jxcore-log( 6415): JXcore engine is ready
,D/PMS     (  942): releaseHCC(16b1608d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  942): releaseHCC(2eff4242): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null,
,W/jxcore-log( 6415): Starting JXcore engine
,W/jxcore-log( 6415): Platform android
W/jxcore-log( 6415): 
W/jxcore-log( 6415): Process ARCH arm
W/jxcore-log( 6415): ,
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  942):  packet count Tx=192 Rx=280
D/WIFI_ICON( 1220): WifiActivity: 1
E/WifiTrafficPoller(  942): notifying of data activity 1
,D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 6415): JXcore Cordova bridge is ready!,
I/jxcore-log( 6415): 
W/jxcore-log( 6415): JXcore engine is started
,D/PMS     (  942): acquireWL(17947dd): PARTIAL_WAKE_LOCK  *alarm* 0x1 942 1000 WorkSource{10072}
,V/AlarmManager(  942): sending alarm PendingIntent{6771f52: PendingIntentRecord{17af8223 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455009636946, Int=0
V/AlarmManager(  942): sending alarm PendingIntent{19734320: PendingIntentRecord{3f4784d9 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455009641576, Int=536832000
,V/AlarmManager(  942): sending alarm PendingIntent{322ba950: PendingIntentRecord{2e0da749 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455009633577, Int=20000
,V/CheckinService( 4411): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,D/PMS     (  942): acquireWL(14c3de9e): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4411 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  942): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
E/WifiStateMachine(  942): handleMessage: E msg.what=131143
E/WifiStateMachine(  942): processMsg: ConnectedState
D/PMS     (  942): releaseWL(17947dd): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  942):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):0 dur:177 rssi=-62 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.9 list=2412 [on:0 tx:0 rx:0 period:865] from screen [on:0 period:-984271740]
E/WifiStateMachine(  942): processMsg: L2ConnectedState
,E/WifiStateMachine(  942):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:177 rssi=-62 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.9 list=2412 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-984271738]
E/WifiStateMachine(  942): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.25 rxSuccessRate=0.94 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-62
E/WifiStateMachine(  942): WifiStateMachine CMD_START_SCAN with age=60511 interval=60000 maxinterval=300000
E/WifiStateMachine(  942): WifiStateMachine CMD_START_SCAN try full band scan age=60511 interval=60000 maxinterval=300000
E/WifiStateMachine(  942): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  942): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1359): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1359): wpa_supplicant_scan enter
D/wpa_supplicant( 1359): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1359): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1359): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1359): WPS:  * Request Type
D/wpa_supplicant( 1359): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1359): WPS:  * UUID-E
D/wpa_supplicant( 1359): WPS:  * Primary Device Type
D/wpa_supplicant( 1359): WPS:  * RF Bands (3)
,D/wpa_supplicant( 1359): WPS:  * Association State
D/wpa_supplicant( 1359): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1359): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1359): WPS:  * Manufacturer
D/wpa_supplicant( 1359): WPS:  * Model Name
D/wpa_supplicant( 1359): WPS:  * Model Number
,D/wpa_supplicant( 1359): WPS:  * Device Name
D/wpa_supplicant( 1359): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1359): P2P: * P2P IE header
D/wpa_supplicant( 1359): P2P: * Capability dev=25 group=00
D/PMS     (  942): acquireWL(819714c): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4411 10024 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1359): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/PMS     (  942): releaseWL(14c3de9e): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1359): wlan0: Add radio work 'scan'@0x55840b9680
D/wpa_supplicant( 1359): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1359): wlan0: Starting radio work 'scan'@0x55840b9680 after 0.000040 second wait
D/wpa_supplicant( 1359): wlan0: nl80211: scan request
D/wpa_supplicant( 1359): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1359): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1359): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1359): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1359): wlan0: Own scan request started a scan in 0.000092 seconds
I/wpa_supplicant( 1359): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  942): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  942): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  942): [1,455,009,641,608 ms] noteScanstart no scan source
E/WifiStateMachine(  942): handleMessage: X
,I/CheckinService( 4411): Checking schedule, now: 1455009641628 next: 1455009641576
I/CheckinService( 4411): active receiver: enabled
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4411, uid=10024, userID:0
,I/CheckinService( 4411): Preparing to send checkin request
I/EventLogService( 4411): Accumulating logs since 1455009604278
,I/CheckinRequestBuilder( 4411): Checkin reason type: 11 attempt count: 1
,I/ActivityManager(  942): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4411): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 6415): Toggling radios to true,
I/jxcore-log( 6415): 
,D/BluetoothAdapter( 6415): enable(): BT is already enabled..!
,D/WifiManager( 6415): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366,
D/WifiService(  942): New client listening to asynchronous messages
E/WifiTrafficPoller(  942): ADD_CLIENT: 7
D/WifiService(  942): setWifiEnabled: true pid=6415, uid=10366
W/Settings:Agent(  942): MONITOR_LOG
E/WifiService(  942): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  942): name: wifi_on
I/WifiService(  942): isSprintWifiRestricted(): false
W/Settings:Agent(  942): value: 2
I/WifiService(  942): isMdmWifiRestricted(): false
W/Settings:Agent(  942): >> traceCallingStack()
W/Settings:Agent(  942): Process.myPid(): 942
W/Settings:Agent(  942): Process.myTid(): 987
W/Settings:Agent(  942): Process.myUid(): 1000
W/Settings:Agent(  942): 
W/Settings:Agent(  942): 
W/System.err(  942): java.lang.Throwable: stack dump
,W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  942): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  942): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  942): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  942): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  942): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  942): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
,W/System.err(  942): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  942): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  942): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  942): 
W/Settings:Agent(  942): << traceCallingStack(): 16(ms)
D/WifiController(  942): handleMessage: E msg.what=155656
D/WifiController(  942): processMsg: DeviceActiveState
D/WifiController(  942): processMsg: StaEnabledState
D/WifiController(  942): handleMessage: X
D/WifiManager( 6415): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  942): handleMessage: E msg.what=131145
E/WifiStateMachine(  942): processMsg: ConnectedState
D/WifiManager( 6415): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  942):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1359): wlan0: Cancelling scan request
D/wpa_supplicant( 1359): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1359): TDLS: Tear down peers
D/wpa_supplicant( 1359): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6415): Radios toggled
I/jxcore-log( 6415): 
,I/jxcore-log( 6415): My device name is: HTC-HTC One M8s
I/jxcore-log( 6415): 
,I/GLSUser ( 1870): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1870): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1870): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1870): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/wpa_supplicant( 1359): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1359): wlan0: Deauthentication notification
D/wpa_supplicant( 1359): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1359): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1359): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1359): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1359): enter disconnect check
I/wpa_supplicant( 1359): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
,D/wpa_supplicant( 1359): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1359): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  942): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  942): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  942): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  942): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
D/Tethering(  942): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  942): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  942): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  942): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  942): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1359): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1359): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1359): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1359): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1359): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55840b6f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1359):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1359): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1359): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1359): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1359): EAPOL: SUPP_PAE entering state DISCONNECTED
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
D/wpa_supplicant( 1359): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1359): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1359): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1359): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1359): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1359): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1359): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1359): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1359): EAPOL: External notification - portEnabled=0
D/UsbDeviceManager(  942): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1359): EAPOL: External notification - portValid=0
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1359): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1359): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/PMS     (  942): acquireWL(1065649): PARTIAL_WAKE_LOCK  NetworkStats 0x1 942 1000 null
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1359): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1359): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1359): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  942): transitionTo: destState=DisconnectingState
D/wpa_supplicant( 1359): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1359): wlan0: nl80211: New scan results available
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
D/wpa_supplicant( 1359): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1359): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1359): Got an original EVENT_SCAN_RESULTS
E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/wpa_supplicant( 1359): wlan0: Scan completed in 0.209945 seconds
E/WifiStateMachine(  942): invokeExitMethods: ConnectedState
E/WifiStateMachine(  942): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  942): release()
D/wpa_supplicant( 1359): nl80211: Received scan results (5 BSSes)
E/WifiStateMachine(  942): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  942): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
I/wpa_supplicant( 1359): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-53
I/wpa_supplicant( 1359): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1359): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1359): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
I/wpa_supplicant( 1359): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1359): w,lan0: BSS: Start scan result update 5
D/WifiMonitor(  942): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/wpa_supplicant( 1359): wlan0: BSS: Add new id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 1359): BSS: last_scan_res_used=5/32
D/wpa_supplicant( 1359): wlan0: Scan-only results received
D/wpa_supplicant( 1359): wlan0: Radio work 'scan'@0x55840b9680 done in 0.210849 seconds
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  942): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  942): invokeExitMethods: L2ConnectedState
D/UsbnetService(  942): BroadcastReceiver::onReceive+
D/UsbnetService(  942): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  942): BroadcastReceiver::onReceive-
E/WifiStateMachine(  942): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  942): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  942): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  942): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  942): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1359): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1359): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1359): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1359): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1359): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1359): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  942): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1359): Power_Mode_Type mode = 0
I/wpa_supplicant( 1359): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1359): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  942): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  942): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  942): setDhcpActive: false
V/NativeCrypto( 1870): Read error: ssl=0x55a2a55a50: I/O error during system call, Connection timed out
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  942): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  942): setDetailed state send new extra info<unknown ssid>
D/PMS     (  942): acquireWL(23732b4e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  942): NetworkAgent != null
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  942): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/ConnectivityService(  942): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  942):  packet count Tx=192 Rx=280
E/WifiTrafficPoller(  942): notifying of data activity 0
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WIFI_ICON( 1220): WifiActivity: 0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  942): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/PMS     (  942): releaseWL(1065649): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiDataStallTracker(  942): stopDataStallAlarm 
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 12
V/NetworkPolicy(  942): updateNotificationsLocked()
E/WifiDataStallTracker(  942): ENABLE_DATA_MONITOR_POLL false Token 1
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  942): autoRoamSetBSSID any key="NG700"WPA_PSK
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiConfigStore(  942): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  942): QCOM Debug skip set_network part for security concern!
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1359): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1359): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1359): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1359): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1359): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1359): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=4
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  942): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  942):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  942): Start Disconnecting Watchdog 1
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131146
E/WifiStateMachine(  942): processMsg: DisconnectingState
E/WifiStateMachine(  942):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
V/NativeCrypto( 1870): SSL shutdown failed: ssl=0x55a2a55a50: I/O error during system call, Broken pipe
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  942):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1359): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1359): wlan0: Selecting BSS from priority group 650
D/wpa_supplicant( 1359): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-53 wps
D/wpa_supplicant( 1359): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1359): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1359): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-61 wps
D/wpa_supplicant( 1359): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1359): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1359): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1359):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1359): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1359): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x55840b8c00  current_ssid=0x0
D/wpa_supplicant( 1359): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1359): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1359): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1359): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1359): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1359): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1359): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1359): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1359): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1359): wlan0: Add radio work 'connect'@0x55840b9680
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
D/wpa_supplicant( 1359): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1359): wlan0: Starting radio work 'connect'@0x55840b9680 after 0.000108 second wait
I/wpa_supplicant( 1359): check if in concurrent case
I/wpa_supplicant( 1359): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  942): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=147460
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=35 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  942): processMsg: DisconnectingState
E/WifiStateMachine(  942):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=98274
E/WifiStateMachine(  942): processMsg: ConnectModeState
D/TetherSettings( 5947): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5947): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5947): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5947): Cust_ConnectToPC   : spcsc>false
D/        ( 5947): Cust_ConnectToPC   : IPT>true
D/        ( 5947): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  942):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=98275
D/ConnectivityService(  942): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  942): ConnectModeState: Network connection lost 
D/ConnectivityService(  942): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  942): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
D/wpa_supplicant( 1359): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1359): wlan0: Cancelling scan request
E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/wpa_supplicant( 1359): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1359): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1359): wpas_start_assoc_cb, 1910
E/WifiStateMachine(  942): invokeExitMethods: DisconnectingState
D/wpa_supplicant( 1359): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1359): wlan0: Automatic auth_alg selection: 0x1
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=4
D/wpa_supplicant( 1359): RSN: PMKSA cache search - network_ctx=0x55840b8c00 try_opportunistic=0
D/wpa_supplicant( 1359): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): RSN: No PMKSA cache entry found
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/wpa_supplicant( 1359): wlan0: RSN: using IEEE 802.11i/D9.0
E/WifiStateMachine(  942): invokeEnterMethods: DisconnectedState
D/wpa_supplicant( 1359): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
E/WifiStateMachine(  942): DisconnectedState call setCountryCode()
D/wpa_supplicant( 1359): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1359): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1359): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1359): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1359): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1359): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1359): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1359): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1359): wlan0: State: DISCONNECTED -> ASSOCIATING
E/WifiStateMachine(  942):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
D/wpa_supplicant( 1359): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1359): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1359): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1359): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1359): nl80211: Unsubscribe mgmt frames handle 0x888888dd0c830989 (mode change)
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  942): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1359): nl80211: Subscribe to mgmt frames with non-AP handle 0x55840b8100
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=0104
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=040a
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=040b
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=040c
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=040d
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=090a
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=090b
D/WifiMonitor(  942): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=090c
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=090d
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=0409506f9a09
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=7f506f9a09
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=0801
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=040e
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=06
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=0a07
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=0a11
D/wpa_supplicant( 1359): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55840b8100 match=0a1a
D/wpa_supplicant( 1359): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1359):   * bssid=c0:ff:d4:d3:aa:48
W/ContextImpl(  942): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1359):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359):   * freq=2412
D/wpa_supplicant( 1359):   * freq_hint=2412
D/wpa_supplicant( 1359):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1359):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1359):   * WPA Versions 0x2
D/wpa_supplicant( 1359):   * pairwise=0xfac04
D/wpa_supplicant( 1359):   * group=0xfac04
D/wpa_supplicant( 1359):   * akm=0xfac02
D/wpa_supplicant( 1359):   * Auth Type 0
D/wpa_supplicant( 1359): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55840b8c3a
D/wpa_supplicant( 1359): nl80211: Connect request send successfully
D/wpa_supplicant( 1359): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1359): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1359): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1359): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1359): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1359): Ongoing scan action - reject new request
E/WifiStateMachine(  942): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=147462
E/WifiStateMachine(  942): processMsg: DisconnectedState
W/Settings( 5947): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  942):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=98279  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  942): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  942): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  942): processMsg: ConnectModeState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=98280  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=147461
E/WifiStateMachine(  942): processMsg: DisconnectedState
E/WifiStateMachine(  942):  DisconnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  942): proces,sMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
D/PMS     (  942): releaseWL(23732b4e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  942):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  942): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1359): wlan0: Control interface command 'LIST_DONGLES'
E/SmartNS_Utility( 5947): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5947): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5947): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Validated
E/WifiStateMachine(  942): [1,455,009,641,853 ms] noteScanEnd no scan source
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1359): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  942): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@6158179 sup_state=DISCONNECTED debouncing=false
E/WifiAutoJoinController (  942): NG7005g c0:ff:d4:d3:aa:4a rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  942): NG700 c0:ff:d4:d3:aa:48 rssi=-61 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  942): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  942): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  942):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-61 freq=2412
E/WifiAutoJoinController (  942): Gonzos 38:f8:89:11:e9:11 rssi=-80 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  942): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  942): 01ABC c2:ff:d4:d3:aa:48 rssi=-61 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  942): ageScanResultsOut delay 40000 size 5 now 1455009641860
E/WifiAutoJoinController (  942): newSupplicantResults size=5 known=1 true
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1359): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  942): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  942): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  942): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  942): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  942): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  942):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131101
E/WifiStateMachine(  942): processMsg: DisconnectedState
E/WifiStateMachine(  942):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiManager( 1799): getScanResults: Base Package Name=com.google.android.gms, uid=10024
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/WifiStateMachine(  942):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  942): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  942): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: DisconnectedState
E/WifiStateMachine(  942):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
W/CheckinRequestBuilder( 4411): awaiting user notification for token
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
I/RemoteViews( 1220): reapply : com.google.android.gms 2 40
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: DisconnectedState
E/WifiStateMachine(  942):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
W/ContextImpl( 5947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5947): setISNotification
E/WifiStateMachine(  942): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
D/WifiNetworkAgent(  942): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: DisconnectedState
E/WifiStateMachine(  942):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131213
E/WifiStateMachine(  942): processMsg: DisconnectedState
D/SmartNS_Utility( 5947): usb_cable_connect = 1
E/WifiStateMachine(  942):  DisconnectedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=98310
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=98311
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=98311
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
D/SmartNS_Utility( 5947): usb_denied = 0
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=98311
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=147462
E/WifiStateMachine(  942): processMsg: DisconnectedState
E/WifiStateMachine(  942):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=98312  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  942): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  942): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  942): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  942): NetworkAgent == null
I/SmartNS_PSService( 5947): usb notificaiton:true
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=98316  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  942): handleMessage: X
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
I/ActionCombine( 5947): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1220): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:2
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:5
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
,D/SmartNS_Utility( 5947): usb_cable_connect = 1,
I/RemoteViews( 1220): reapply : com.android.settings 2 36
D/SmartNS_Utility( 5947): usb_denied = 0
I/SmartNS_PSService( 5947): usb notificaiton:true
,E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/ActivityManager(  942): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6476 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/SmartNS_NSReceiver( 5947): Tethered state change:false isNSOpening:false
,D/ConnectivityService(  942): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  942): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  942): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Disconnected - quitting
D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/SecurityController( 1220): onLost 100
,I/RemoteViews( 1220): reapply : com.android.settings 1 36,
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:1,
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  942): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  942): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  942): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  942):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  942): Removing idletimer
D/usbnet  (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI    (  942): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  942):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  942): enter WifiNetworkFactory startNetwork. mIPTStart:false
,D/wpa_supplicant( 1359): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1359): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1359): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1359): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1359): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1359): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1359): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1359): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1359): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1359): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1359): nl80211: Connect event
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
D/Tethering(  942): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1359): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1359): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1359): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1359): wlan0: Association info event
D/wpa_supplicant( 1359): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1359): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1359): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1359): wlan0: freq=2412 MHz
D/wpa_supplicant( 1359): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1359): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1359): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1359): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1359): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1359): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): wlan0: WPA: clearing AP WPA IE
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
D/Tethering(  942): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1359): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1359): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1359): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1359): wlan0: WPA: Clear old PTK
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/wpa_supplicant( 1359): TDLS: Remove peers on association
D/wpa_supplicant( 1359): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1359): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1359): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1359): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1359): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1359): EAPOL: enable timer tick
D/wpa_supplicant( 1359): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1359): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1359): wlan0: Cancelling scan request
I/wpa_supplicant( 1359): htc_wext_set_keepalive +
I/wpa_supplicant( 1359): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1359): getPrivFuncNum +	
I/wpa_supplicant( 1359): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1359): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1359): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1359): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1359): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1359): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1359): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1359): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1359):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1359):   key_nonce - hexdump(len=32): 55 7e 58 98 f2 fb 50 4a 04 fe 48 d4 0e 64 8a 81 24 12 21 a9 cd 82 03 5f 66 7c 46 c7 89 4d 68 dd
D/wpa_supplicant( 1359):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1359):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1359):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1359):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1359): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1359): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1359): RSN: msg 1/4 key data - hexdump(len=0):
,D/Tethering(  942): interfaceLinkStateChanged wlan0, false
D/Tethering(  942): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  942): interfaceLinkStateChanged wlan0, true
D/Tethering(  942): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  942): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1359): WPA: Renewed SNonce - hexdump(len=32): fb 17 26 19 96 54 4d 63 d8 55 f4 ad 2e 66 7e f0 d3 db e2 fa e6 b0 90 20 dd 3d 17 dc bc 1d b3 3b
D/wpa_supplicant( 1359): WPA: Nonce1 - hexdump(len=32): fb 17 26 19 96 54 4d 63 d8 55 f4 ad 2e 66 7e f0 d3 db e2 fa e6 b0 90 20 dd 3d 17 dc bc 1d b3 3b
D/wpa_supplicant( 1359): WPA: Nonce2 - hexdump(len=32): 55 7e 58 98 f2 fb 50 4a 04 fe 48 d4 0e 64 8a 81 24 12 21 a9 cd 82 03 5f 66 7c 46 c7 89 4d 68 dd
D/wpa_supplicant( 1359): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1359): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1359): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1359): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1359): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1359): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1359): WPA: Derived Key MIC - hexdump(len=16): 31 39 3e df 5f 8d bb e2 01 42 3f f5 ab b0 ed 10
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  942): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  942): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  942): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  942): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  942): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  942): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  942): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  942): handleMessage: E msg.what=147462
E/WifiStateMachine(  942): processMsg: DisconnectedState
,D/HTCRequest(  942): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  942): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  942): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  942): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  942): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  942):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=98388  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  942): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  942): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  942): setDetailed state send new extra info0x
D/WifiMonitor(  942): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5947): >>>>>WISPrService start isConnected = true<<<<<
,D/PMS     (  942): acquireWL(31eb4814): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 942 1000 null
D/wpa_supplicant( 1359): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/CSLegacyTypeTracker(  942): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/wpa_supplicant( 1359): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/ConnectivityService(  942): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/wpa_supplicant( 1359): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1359): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1359): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1359):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1359):   key_nonce - hexdump(len=32): 55 7e 58 98 f2 fb 50 4a 04 fe 48 d4 0e 64 8a 81 24 12 21 a9 cd 82 03 5f 66 7c 46 c7 89 4d 68 dd
D/wpa_supplicant( 1359):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1359):   key_rsc - hexdump(len=8): 7d e7 00 00 00 00 00 00
D/wpa_supplicant( 1359):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1359):   key_mic - hexdump(len=16): f0 30 8d 38 6f 70 33 42 d1 20 ca 53 ce 7e 19 76
D/wpa_supplicant( 1359): RSN: encrypted key data - hexdump(len=56): ff 46 77 67 a7 c2 20 0b 01 37 bc 56 1b 78 83 7e fd 5a a7 3f 04 67 b1 77 88 b7 0e 17 19 e8 cc 5b ...
D/wpa_supplicant( 1359): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1359): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1359): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
,D/wpa_supplicant( 1359): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 3e 04 ...
D/wpa_supplicant( 1359): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1359): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1359): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1359): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1359): WPA: Derived Key MIC - hexdump(len=16): 57 7c 91 5c 3f 59 f6 d3 71 2f c7 38 05 8a 8c 79
D/wpa_supplicant( 1359): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1359): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55840b9390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1359): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1359): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1359):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1359): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1359): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1359): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1359): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
,D/wpa_supplicant( 1359): WPA: RSC - hexdump(len=6): 7d e7 00 00 00 00
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1359): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5577dfde68 key_idx=1 set_tx=0 seq_len=6 key_len=16
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1359): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1359): nl80211: KEY_SEQ - hexdump(len=6): 7d e7 00 00 00 00
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiService(  942): New client listening to asynchronous messages
D/wpa_supplicant( 1359):    broadcast key
D/HTCRequest(  942): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1359): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1359): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1359): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1359): wlan0: Radio work 'connect'@0x55840b9680 done in 0.124674 seconds
D/WifiMonitor(  942): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1359): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1359): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  942): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  942): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  942): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=42 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  942): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1359): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1359): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1359): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 1359): set send_ind_to_ndc = 0
I/wpa_supplicant( 1359): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1359): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1359): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1359): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1359): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1359): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1359): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1359): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1359): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1359): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1359): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1359): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/Tethering(  942): interfaceLinkStateChanged wlan0, true
D/Tethering(  942): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1359): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiTrafficPoller(  942): ADD_CLIENT: 8
D/WifiMonitor(  942): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=44 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  942): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  942): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
I/ActivityManager(  942): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6500 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/Tethering(  942): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
,E/WifiStateMachine(  942):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=98408  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=147500
E/WifiStateMachine(  942): processMsg: DisconnectedState
,E/WifiStateMachine(  942):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  942): Enter handleAssociatedWithEvent
D/WifiStateMachine(  942): Associated
D/WifiStateMachine(  942): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  942): Exit handleAssociatedWithEvent
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=147462
E/WifiStateMachine(  942): processMsg: DisconnectedState
E/WifiStateMachine(  942):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=98410  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  942): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  942): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  942): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/UsbnetService(  942): BroadcastReceiver::onReceive+
,D/UsbDeviceManager(  942): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  942): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  942): acquireWL(1b60aeb2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 942 1000 null
D/UsbnetService(  942): BroadcastReceiver::onReceive-
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  942): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  942): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
E/ConnectivityService(  942): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine(  942): NetworkAgent == null
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/Tethering(  942): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  942): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  942): ensureActiveMobilePolicyLocked()
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/DATA_ICON( 1220): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
,E/WifiStateMachine(  942): processMsg: ConnectModeState
D/PMS     (  942): releaseWL(1b60aeb2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 18
D/PMS     (  942): acquireWL(2d10ce03): PARTIAL_WAKE_LOCK  NetworkStats 0x1 942 1000 null
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/NetworkPolicy(  942): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
V/NetworkPolicy(  942): updateIfacesLocked(),
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  942): updateNotificationsLocked()
E/WifiStateMachine(  942):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=98423  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=147462
E/WifiStateMachine(  942): processMsg: DisconnectedState
E/WifiStateMachine(  942):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=98426  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  942): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
D/DATA_ICON( 1220): dataConnected: false/false
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  942): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=98427  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=147459
E/WifiStateMachine(  942): processMsg: DisconnectedState
E/WifiStateMachine(  942):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=98428
,E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=98428
E/WifiStateMachine(  942): Network connection established
D/WifiStateMachine(  942): fetchFrequency(), freq = 2412
E/WifiStateMachine(  942): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  942): NetworkAgent == null
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 19
V/NetworkPolicy(  942): updateNotificationsLocked()
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  942): transitionTo: destState=ObtainingIpState
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
,E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  942): invokeExitMethods: DisconnectedState
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  942): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 20
,D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
E/WifiStateMachine(  942): moveTempStackToStateStack: i=1,j=4
D/NetworkManagementService(  942): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=5
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  942): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  942): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  942): NetworkAgent == null
W/ResourcesManager( 6476): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 21
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ResourcesManager( 6476): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/PMS     (  942): releaseWL(2d10ce03): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,E/WifiStateMachine(  942): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  942): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  942): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  942): Got NetworkAgent Messenger
E/WifiConfigStore(  942): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  942): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
W/WifiHW  (  942): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  942): NetworkAgent connected
D/wpa_supplicant( 1359): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1359): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1359): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1359): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1359): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1359): CTRL_IFACE: SAVE_CONFIG - Configuration updated
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
E/WifiStateMachine(  942): invokeEnterMethods: ObtainingIpState
V/NetworkPolicy(  942): updateNotificationsLocked()
E/WifiStateMachine(  942): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  942): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  942): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  942): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  942): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1359): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1359): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1359): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1359): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1359): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1359): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/libc    (  942): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
,D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  942): Start Dhcp Watchdog 2
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=147462
,E/WifiStateMachine(  942): processMsg: ObtainingIpState
E/WifiStateMachine(  942):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=98455  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=98456  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  942): processMsg: ConnectModeState
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
E/WifiStateMachine(  942):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=98457  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131131
E/WifiStateMachine(  942): processMsg: ObtainingIpState
E/WifiStateMachine(  942):  ObtainingIpState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  942): handleMessage: X
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
E/WifiStateMachine(  942): handleMessage: E msg.what=131101
E/WifiStateMachine(  942): processMsg: ObtainingIpState
E/WifiStateMachine(  942):  ObtainingIpState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  942): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  942): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131155
E/WifiStateMachine(  942): processMsg: ObtainingIpState
E/WifiStateMachine(  942):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:422] from screen [on:0 period:-984271313] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
I/MultiDex( 6476): VM with version 2.1.0 has multidex support
I/MultiDex( 6476): install
,I/MultiDex( 6476): VM has multidex support, MultiDex support library is disabled.
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-984271312] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/WISPrService( 5947): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5947): trigger connection
D/WISPrService( 5947): continue
D/wpa_supplicant( 1359): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1359): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
,E/WifiConfigStore(  942): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
E/WifiStateMachine(  942): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=96.50 txretriesrate=0.00 rxrate=140.00 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
E/WifiStateMachine(  942): calculateWifiScore() report new score 60
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
,E/WifiStateMachine(  942): handleMessage: X
,E/WifiStateMachine(  942): handleMessage: E msg.what=131212
D/ConnectivityService(  942): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  942): processMsg: ObtainingIpState
E/WifiStateMachine(  942):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
E/WifiStateMachine(  942):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
,D/WISPrService( 5947): start DataConnection
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  942): processMsg: DefaultState
D/ConnectivityService(  942): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    ( 5947): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 5947): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/libc    ( 5947): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5947): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5947): [NET] android_getaddrinfo_proxy+
D/libc    ( 5947): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5947): [NET] android_getaddrinfo_proxy-, NODATA
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
,I/ActivityManager(  942): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6526 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,E/WifiStateMachine(  942): handleMessage: E msg.what=196612
D/WifiStateMachine(  942): handlePreDhcpSetup Held wake lock during DHCP
,E/WifiStateMachine(  942): processMsg: ObtainingIpState
D/PMS     (  942): acquireWL(256594d6): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 942 1000 null
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  942): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  942):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=193,0,0
D/WifiP2pService(  942): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22608538 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): processMsg: L2ConnectedState
D/WifiP2pService(  942): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22608538 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=193,0,0
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  942): setDhcpActive: true
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1359): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  942): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  942): do suspend false
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1359): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1359): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1359): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1359): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1359): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1359): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1359): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  942): Unexpected BatchedScanResults :null
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false,
E/wpa_supplicant( 1359): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
E/WifiStateMachine(  942): noteBatchedScanstop()
E/WifiStateMachine(  942): handleMessage: X
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
V/JNIHelp ( 6476): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/libc    ( 5947): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5947): [NET] android_getaddrinfofornet-, err=8
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WISPrService( 5947): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/ActivityManager(  942): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6547 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false,
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,W/ActivityThread( 6476): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6476): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c20b502: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6476): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 6526): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6526): Created com.android.providers.calendar.CalendarAlarmManager@23b37ca8(com.htc.providers.calendar.HtcCalendarProvider@355773c1)
,D/CalendarProvider2( 6526): wait start:true
,D/Finsky  ( 5972): [597] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5972): [1] 5.onFinished: Installation state replication succeeded.,
,E/dhcpcd  ( 6575): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6575): version 5.5.6 starting
E/dhcpcd  ( 6575): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6575): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6575): autoip env[11]:autoip=DISABLE
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 6526): wait end:false
,D/TetherSettings( 5947): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
W/ContextImpl( 5947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 5947): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5947): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5947): Cust_ConnectToPC   : spcsc>false
D/        ( 5947): Cust_ConnectToPC   : IPT>true
D/        ( 5947): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5947): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5947): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5947): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5947): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
I/SmartNS_Utility( 5947): setISNotification
,D/MdScPhnSt( 6547): [bc.2.]  listen tmrbb8
D/SmartNS_Utility( 5947): usb_cable_connect = 1
D/SmartNS_Utility( 5947): usb_denied = 0
I/SmartNS_PSService( 5947): usb notificaiton:true
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 5947): usb_cable_connect = 1
,D/SmartNS_Utility( 5947): usb_denied = 0
,I/dhcpcd  ( 6575): wlan0: rebinding lease of 192.168.1.130
I/SmartNS_PSService( 5947): usb notificaiton:true
I/dhcpcd  ( 6575): wlan0: sending REQUEST (xid 0xac22c176), next in 1.64 seconds
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/WVCdm   (  399): CdmEngine::OpenSession
I/WVCdm   (  399): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  399): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
I/RemoteViews( 1220): reapply : com.android.settings 2 36
,D/SmartNS_NSReceiver( 5947): Tethered state change:false isNSOpening:false
D/DrmWidevineDash(  399): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  399): Service_Initialize: starts!
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
E/QSEECOMAPI: (  399): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  399): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1220): reapply : com.android.settings 3 36
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/QSEECOMAPI: (  399): Loaded image: APP id = 8
,D/DrmWidevineDash(  399): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  399): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  399): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49cc000
E/DrmWidevineDash(  399): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49cc000
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  537): got the req here! ret=0,
D/DrmLibTime(  537): command id, time_cmd_id = 770
D/DrmLibTime(  537): time_getutcsec starts!
D/DrmLibTime(  537): QSEE Time Listener: time_getutcsec,
D/DrmLibTime(  537): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  537): QSEE Time Listener: time_get_modem_time,
D/DrmLibTime(  537): QSEE Time Listener: Checking if ATS_MODEM is set or not.
D/FlexNetS( 6526): updateSvcAllowedInSettings:false
E/QC-time-services(  537): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  537): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,D/DrmLibTime(  537): QSEE Time Listener: Retrieved Android system time: 1455009642
D/DrmLibTime(  537): time_getutcsec returns 0, sec = 1455009642; nsec = 0
D/DrmLibTime(  537): time_getutcsec finished! ,
D/DrmLibTime(  537): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  537): before calling ioctl to read the next time_cmd
E/QC-time-services(  470): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/MdProvGlob( 6500): remove item 101 (p2d27in295) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6547): [bc.2.] summary 118:p2 ignore
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  399): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xf4bf6928
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xaaf1d308, dataLength=8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaaf19f20, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xaaf079f0, idLength=0xf4cf66f8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL false Token 22 num clients 8
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false,
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4cf670e, maximum = 0xf4cf670f
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
,D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4cf677c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  399): PrepareKeyRequest: nonce=2594869790
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaaf16140
D/DrmWidevineDash(  399): message_length=1611, signature=0xaaf14f08, signature_length=0xf4cf66dc
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/FlexNetS( 6526): updateSvcAllowedInSettings:false
,D/GCM     ( 1870): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1870): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4411): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4411, uid=10024, userID:0
,D/WearableService( 5687): callingUid 10024, callindPid: 5687
,E/MDM     ( 1799): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4411): Restart initialization of location
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
,D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  399): CdmEngine::CloseSession
,D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  399): L3 Terminate.
D/DrmWidevineDash(  399): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  399): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  399): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  399): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  399): OEMCrypto_Terminate: ends! returns 0
I/art     (  942): Explicit concurrent mark sweep GC freed 49825(2MB) AllocSpace objects, 4(144KB) LOS objects, 33% free, 16MB/25MB, paused 8.958ms total 163.523ms
,I/WVCdm   (  399): CdmEngine::OpenSession,
I/WVCdm   (  399): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  399): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  399): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  399): Service_Initialize: starts!
,D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
E/QSEECOMAPI: (  399): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  399): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
,D/QSEECOMAPI: (  399): Loaded image: APP id = 9,
,D/DrmWidevineDash(  399): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  399): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  399): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49cc000
E/DrmWidevineDash(  399): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49cc000
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  537): got the req here! ret=0,
D/DrmLibTime(  537): command id, time_cmd_id = 770
D/DrmLibTime(  537): time_getutcsec starts!
D/DrmLibTime(  537): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  537): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  537): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  537): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  537): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  537): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  537): QSEE Time Listener: Retrieved Android system time: 1455009642
,D/DrmLibTime(  537): time_getutcsec returns 0, sec = 1455009642; nsec = 0
D/DrmLibTime(  537): time_getutcsec finished! 
D/DrmLibTime(  537): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  537): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
E/QC-time-services(  470): Daemon: Time-services: Waiting to acceptconnection
,D/DrmWidevineDash(  399): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  399): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xf4bf6928,
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xaaef6df0, dataLength=8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaaf16140, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xaaf07a10, idLength=0xff9f46d8
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xff9f46ee, maximum = 0xff9f46ef
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xff9f475c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0,
D/WVCdm   (  399): PrepareKeyRequest: nonce=3172090712
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaaf117e8
D/DrmWidevineDash(  399): message_length=1646, signature=0xaaf11e60, signature_length=0xff9f46bc
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL false Token 22 num clients 8,
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  399): CdmEngine::CloseSession,
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  399): L3 Terminate.
D/DrmWidevineDash(  399): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): Service_Uninitialize: starts!
D/QSEECOMAPI: (  399): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  399): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  399): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  399): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6599): Error opening trace file: Permission denied (13),
I/dex2oat ( 6599): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6599): dex2oat: override thread count:4
,D/wpa_supplicant( 1359): EAPOL: startWhen --> 0
D/wpa_supplicant( 1359): EAPOL: disable timer tick
,I/dex2oat ( 6599): dex2oat took 52.368ms (threads: 4),
,I/Adreno-EGL( 6476): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6476): OpenGL ES Shader Compiler Version: E031.25.03.01,
I/Adreno-EGL( 6476): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6476): Local Branch: 
I/Adreno-EGL( 6476): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6476): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6476):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6476): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6476): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6476): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6476): Local Branch: 
I/Adreno-EGL( 6476): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6476): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6476):                  d74aa161a12b9c6fc6332151
,W/ContextImpl(  942): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/libc    (  942): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
,D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  942): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: ObtainingIpState
E/WifiStateMachine(  942):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
,E/WifiStateMachine(  942):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  942): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
,I/CalendarProvider2( 6526): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6526): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/CheckinRequestBuilder( 4411): Classify the device as Phone.
,I/ActivityManager(  942): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6608 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  942): Killing 5925:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=5925
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiDataStallTracker(  942): DATA_MONITOR_POLL false Token 2,
,I/ActivityManager(  942): Recipient 5925
,W/ResourcesManager( 6608): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/libc    ( 4411): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4411): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4411): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    ( 4411): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4411): [NET] android_getaddrinfo_proxy+
D/libc    ( 4411): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4411): [NET] android_getaddrinfo_proxy-, NODATA
E/CheckinTask( 4411): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinService( 4411): Checking schedule, now: 1455009643454 next: 1455009653445
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4411, uid=10024, userID:0
,I/CheckinService( 4411): active receiver: disabled
,D/CalendarApplication( 6608): onCreate
,D/ProviderChangeReceiver( 6608): ---------------------------------------------------
D/ProviderChangeReceiver( 6608): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  942): killProcessQuiet, pid=6188
I/ActivityManager(  942): Killing 6188:com.htc.cs.dm/u0a99 (adj 15): empty #17,
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/dhcpcd  ( 6575): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,D/HtcAlertService( 6608): start to updateAlertNotification!
,I/dhcpcd  ( 6575): wlan0: leased 192.168.1.130 for 86400 seconds
I/dhcpcd  ( 6575): autoip env[11]:autoip=DISABLE
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: ObtainingIpState
,E/WifiStateMachine(  942):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
I/ActivityManager(  942): Recipient 6188
E/WifiStateMachine(  942): processMsg: L2ConnectedState
D/ConnectivityService(  942): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  942):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  942): handleMessage: X
,D/PMS     (  942): releaseWL(819714c): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  942): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6636 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/HtcAlertService( 6608): No fired or scheduled alerts
D/HtcAlertUtils( 6608): -- cancelReminderNotification --
,D/HtcAlertUtils( 6608): broadcastExistReminder!
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PhoneMonitor( 6636): Register our PhoneStateListener,
,D/Process (  942): killProcessQuiet, pid=6210
I/ActivityManager(  942): Killing 6210:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/dhcpcd  ( 6575): bind_interface: daemonise,
,D/PhoneMonitor( 6636): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
E/WifiStateMachine(  942): handleMessage: E msg.what=131155
E/WifiStateMachine(  942): processMsg: ObtainingIpState
,E/WifiStateMachine(  942):  ObtainingIpState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=96.5, 0.0, 0.0  rx=140.0 bcn=0 [on:0 tx:0 rx:0 period:1694] from screen [on:0 period:-984269607] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=96.5, 0.0, 0.0  rx=140.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-984269605] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/PhoneMonitor( 6636): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
E/WifiStateMachine(  942): handleMessage: X
,I/HtcModeClient( 3199): handler message = 4011,
E/HtcModeClient( 3199): Check connection and retry 12 times.
,I/ActivityManager(  942): Recipient 6210
,D/ChimeraCfgMgr( 4411): Loading module com.google.android.gms.kids from APK com.google.android.gms,
D/GCM     ( 1870): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Kids    ( 4411): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/libc    (  942): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  942): handleMessage: E msg.what=196613
E/WifiStateMachine(  942): processMsg: ObtainingIpState
,E/WifiStateMachine(  942):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  942): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1359): Power_Mode_Type mode = 0
I/wpa_supplicant( 1359): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1359): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  942): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  942): setDhcpActive: false
D/WifiP2pService(  942): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): handlePostDhcpSetup release wake lock during DHCP
D/PMS     (  942): releaseWL(256594d6): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  942): WifiStateMachine DHCP successful
,E/WifiStateMachine(  942): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  942): link address 192.168.1.130/24
,E/WifiStateMachine(  942): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0},
D/ConnectivityService(  942): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  942): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  942): gateway: /192.168.1.1
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
,D/wpa_supplicant( 1359): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1359): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  942): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131210
E/WifiStateMachine(  942): processMsg: ObtainingIpState
E/WifiStateMachine(  942):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0,
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1359): environment dirty rate=33 [3][1][0]
,E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  942): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1359): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1359): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  942): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=46 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  942): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
,D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  942): NetworkAgent != null
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  942): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  942): Adding iface wlan0 to network 101
V/NetworkPolicy(  942): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiDataStallTracker(  942): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  942): WAN detection
D/HtcWifiWanDetect(  942): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiStateMachine(  942): transitionTo: destState=ConnectedState
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  942): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  942): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  942): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL true Token 22
E/WifiStateMachine(  942): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/NetworkPolicy(  942): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED connected
,I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  942):  packet count Tx=195 Rx=281
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  942): notifying of data activity 3
,D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiDataStallTracker(  942): ENABLE_DATA_MONITOR_POLL true Token 2
D/WIFI_ICON( 1220): WifiActivity: 3
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL true Token 23
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiDataStallTracker(  942): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WIFI_ICON( 1220): WifiActivity: 0
D/WifiDataStallTracker(  942): updateDataStallInfo: NONE
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiDataStallTracker(  942): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/ConnectivityService(  942): Unexpected mtu value: 0, wlan0
E/WifiTrafficPoller(  942):  packet count Tx=195 Rx=281
D/ConnectivityService(  942): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiTrafficPoller(  942): notifying of data activity 0
E/WifiStateMachine(  942): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  942): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  942): handleMessage: X
D/ConnectivityService(  942): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5947): >>>>>WISPrService start isConnected = true<<<<<
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  942): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  942): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  942): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  942): handleMessage: E msg.what=131131
E/WifiStateMachine(  942): processMsg: ConnectedState
,D/Nat464Xlat(  942): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
E/WifiStateMachine(  942):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  942): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  942): processMsg: L2ConnectedState
D/ConnectivityService(  942): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  942):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  942): handleMessage: X
D/ConnectivityService(  942): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  942):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Connected
D/ConnectivityService(  942):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  942):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Validated
D/ConnectivityService(  942): currentScore = 0, newScore = 20
D/WIFI    (  942): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  942):    accepting network in place of null
,D/WIFI    (  942):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  942): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  942): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/usbnet  (  942):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  942): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/WISPrService( 5947): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  942): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  942): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  942): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  942): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  942): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  942): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  942): ensureActiveMobilePolicyLocked()
D/PMS     (  942): acquireWL(1c703636): PARTIAL_WAKE_LOCK  NetworkStats 0x1 942 1000 null
,D/ConnectivityService(  942): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/DATA_ICON( 1220): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
,D/NetworkPolicy(  942): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
V/NetworkPolicy(  942): updateIfacesLocked()
V/NetworkPolicy(  942): updateNotificationsLocked()
D/DATA_ICON( 1220): dataConnected: false/false
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/NetworkManagementService(  942): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  942): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Validated
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  942): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524290
D/ConnectivityService(  942): Validated NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  942): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  942): rematching NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  942): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  942):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  942):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  942):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  942): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/WIFI    (  942):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  942): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SecurityController( 1220): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524290
D/ConnectivityService(  942): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1220): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  942): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  942): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  942): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  942): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  942): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  942):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  942):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  942): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  942): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  942): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PMS     (  942): acquireWL(300fb937): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4411 10024 WorkSource{10024 com.google.android.gms}
D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524290
D/DATA_ICON( 1220): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,I/SecurityController( 1220): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/DATA_ICON( 1220): dataConnected: false/false
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/QuickSettingWifi( 1220): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/PMS     (  942): releaseWL(1c703636): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  942): acquireWL(2288240d): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4411 10024 WorkSource{10024 com.google.android.gms}
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
V/NetworkPolicy(  942): updateNotificationsLocked()
D/PMS     (  942): releaseWL(300fb937): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/QuickSettingWifi( 1220): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/CheckinService( 4411): Checking schedule, now: 1455009643991 next: 1455009641576
,I/CheckinService( 4411): active receiver: enabled
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4411, uid=10024, userID:0
,I/CheckinService( 4411): Preparing to send checkin request
I/EventLogService( 4411): Accumulating logs since 1455009641652
,I/CheckinRequestBuilder( 4411): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  942): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4411): Failed to find provider info for com.google.android.wearable.settings,
,I/GLSUser ( 1870): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1870): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1870): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1870): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4411): awaiting user notification for token,
D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1220): reapply : com.google.android.gms 2 40
,I/WVCdm   (  399): CdmEngine::OpenSession
I/WVCdm   (  399): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  399): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  399): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  399): Service_Initialize: starts!
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
E/QSEECOMAPI: (  399): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  399): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
,D/QSEECOMAPI: (  399): Loaded image: APP id = 10
,D/DrmWidevineDash(  399): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  399): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  399): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49cc000
,E/DrmWidevineDash(  399): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49cc000
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  537): got the req here! ret=0,
D/DrmLibTime(  537): command id, time_cmd_id = 770
D/DrmLibTime(  537): time_getutcsec starts!
D/DrmLibTime(  537): QSEE Time Listener: time_getutcsec
,D/DrmLibTime(  537): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  537): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  537): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  537): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  537): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  537): QSEE Time Listener: Retrieved Android system time: 1455009644,
D/DrmLibTime(  537): time_getutcsec returns 0, sec = 1455009644; nsec = 0
D/DrmLibTime(  537): time_getutcsec finished! 
D/DrmLibTime(  537): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  537): before calling ioctl to read the next time_cmd
E/QC-time-services(  470): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  399): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xf4bf6928
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xaaf118c0, dataLength=8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaaf16140, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xaaf079d0, idLength=0xf4cf66f8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4cf670e, maximum = 0xf4cf670f
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4cf677c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  399): PrepareKeyRequest: nonce=473067377
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaaf15c50
D/DrmWidevineDash(  399): message_length=1611, signature=0xaaf46c90, signature_length=0xf4cf66dc
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/WVCdm   (  399): CdmEngine::OpenSession,
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xf4bf6928
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/WVCdm   (  399): CdmEngine::CloseSession
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 2
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xaaef6df0, dataLength=8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=2, wrapped_rsa_key=0xaaf137d0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xaaf07a10, idLength=0xf4af66f8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4af670e, maximum = 0xf4af670f
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=2, nonce=0xf4af677c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  399): PrepareKeyRequest: nonce=2961395320,
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=2, message=0xaaf8c730
D/DrmWidevineDash(  399): message_length=1646, signature=0xaaf1c570, signature_length=0xf4af66dc
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  399): CdmEngine::CloseSession
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=2
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  399): L3 Terminate.
D/DrmWidevineDash(  399): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): Service_Uninitialize: starts!
D/QSEECOMAPI: (  399): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  399): QSEECom_shutdown_app, app_id = 10
,D/DrmWidevineDash(  399): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  399): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 6476): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6476): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6476): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6476): Local Branch: 
I/Adreno-EGL( 6476): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6476): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6476):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6476): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6476): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6476): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6476): Local Branch: 
I/Adreno-EGL( 6476): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6476): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6476):                  d74aa161a12b9c6fc6332151
,I/CheckinRequestBuilder( 4411): Classify the device as Phone.,
,D/libc    ( 4411): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4411): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4411): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4411): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4411): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4411): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4411): [NET] android_getaddrinfo_proxy-, success,
,D/libc    ( 4411): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4411): [NET] android_getaddrinfofornet-, err=8
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8,
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1220): WifiActivity: 3
E/WifiTrafficPoller(  942):  packet count Tx=203 Rx=288
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiTrafficPoller(  942): notifying of data activity 3
,D/libc    ( 4411): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4411): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 4411): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4411): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4411): Sending checkin request (8418 bytes)
,D/PMS     (  942): releaseWL(31eb4814): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  942): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  942): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  942): [AlarmQueuing] connectivity wifi: false
,D/GpsLocationProvider(  942): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  942): acquireWL(24b74e3c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 942 1000 null
,D/PMS     (  942): acquireWL(3a4ac7c5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 942 1000 null
D/htcCheckinService(  942): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  942): releaseWL(3a4ac7c5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  942): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  942): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ConnectivityHelper( 1622): [onReceive] WIFI(1): CONNECTED
,I/art     ( 6476): Background sticky concurrent mark sweep GC freed 0(0B) AllocSpace objects, 0(0B) LOS objects, 2% free, 4MB/4MB, paused 6.156ms total 9.833ms
,I/ActivityManager(  942): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6692 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  942): No APN found to select.
,D/PMS     (  942): releaseWL(24b74e3c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155
,E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=96.5, 0.0, 0.0  rx=140.0 bcn=0 [on:0 tx:0 rx:0 period:1300] from screen [on:0 period:-984268303] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=96.5, 0.0, 0.0  rx=140.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-984268302] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/MdScPhnSt( 6547): [aaa.1.]  listen tmrbb8
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1359): environment dirty rate=17 [17][3][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiStateMachine(  942): BroadcastRSSIForIMS, newrssi =-62 , oldRssi= -200
E/WifiConfigStore(  942): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
,E/WifiStateMachine(  942): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=57.25 txretriesrate=0.00 rxrate=76.50 userTriggerdPenalty0
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  942):  good link -> stuck count =0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60
,E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
,E/WifiStateMachine(  942): handleMessage: X
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/MdScDataSum( 6547): [aaa.1.] summary 118:p1 ignore
,I/MusicStore( 6692): Database version: 120,
,D/VoldConnector(  942): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6692): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  942): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6692): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  942): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6692): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 6692): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6692): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6692): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6692): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6692): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a08c5dc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6692): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6692): GMSCore installation verified
,I/ConfigStore( 6692): Config Database version: 1,
,I/art     ( 1870): Explicit concurrent mark sweep GC freed 10451(549KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 618us total 34.093ms,
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6692, uid=10159, userID:0
,I/CheckinRequestBuilder( 4411): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  942): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4411): Failed to find provider info for com.google.android.wearable.settings
,D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
,D/MediaRouterService(  942): Client com.google.android.music (pid 6692): Registered,
,D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
,I/MediaRouter( 6692): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6692): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6692): type=WIFI subType= reason=null isConnected=true,
,I/GLSUser ( 1870): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1870): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1870): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1870): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NetworkMonitor( 6692): type=WIFI subType= reason=null isConnected=true,
V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6692, uid=10159, userID:0
,D/AutoSetting( 1543): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1543): service - onCreate()
,D/MobileConnectivityChangeReceiver( 6636): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 6636): onReceive CONNECTIVITY_CHANGE networkType=1
,D/PMS     (  942): acquireWL(3ca50191): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4411 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(3ca50191): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/AutoSetting( 1543): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/LocationManagerService(  942): request 2f9c6b8a passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  942): provider request: passive ProviderRequest[ON interval=0]
,I/GHttpClientFactory( 6692): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1543): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1543): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1543): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1543): service - handleMessage() setting current location null
,I/GoogleURLConnFactory( 6692): Using platform SSLCertificateSocketFactory
,W/CheckinRequestBuilder( 4411): awaiting user notification for token,
D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1220): reapply : com.google.android.gms 2 40
,I/CheckinRequestBuilder( 4411): Classify the device as Phone.,
,D/ChimeraCfgMgr( 4411): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 4411): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  942): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6738 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 6286): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 6286): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6286): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6286): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6286): [NET] android_getaddrinfo_proxy+
D/libc    ( 6286): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605,
,I/CheckinTask( 4411): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4411): Checking schedule, now: 1455009645655 next: 1455546477642,
I/CheckinService( 4411): active receiver: disabled
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4411, uid=10024, userID:0
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6286): [NET] android_getaddrinfo_proxy-, success
,I/CheckinService( 4411): Checking schedule, now: 1455009645676 next: 1455546477642
I/CheckinService( 4411): active receiver: disabled
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4411, uid=10024, userID:0
,D/PMS     (  942): releaseWL(2288240d): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel   ( 6286): connection state changed from UNKNOWN to CONNECTED,
,D/Process (  942): killProcessQuiet, pid=5351
I/ActivityManager(  942): Killing 5351:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  942): Recipient 5351
,D/VoldConnector(  942): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  942): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6738): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6738):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6738):   adb logcat -s GAv4
,D/VoldConnector(  942): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  942): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,W/ContextImpl( 6738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files,
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/GAv4    ( 6738): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6738): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6738): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  942):  packet count Tx=217 Rx=299
,I/art     (  942): Explicit concurrent mark sweep GC freed 30216(1688KB) AllocSpace objects, 6(248KB) LOS objects, 33% free, 16MB/25MB, paused 1.857ms total 136.653ms,
,W/global  ( 6738): [apache-http] Connection GC has been deprecated!
,W/global  ( 6738): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6738): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6738): Time to load native libraries: 1 ms (timestamps 2738-2739),
I/LibraryLoader( 6738): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6738): Binding Chromium to main looper Looper (main, tid 1) {56a9205}
,I/LibraryLoader( 6738): Expected native library version number "",actual native library version number "",
,I/chromium( 6738): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6738): Initializing chromium process, singleProcess=true,
,W/art     ( 6738): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6738): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6738): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6738): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6738): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6738): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6738): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6738): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6738): Local Branch: 
I/Adreno-EGL( 6738): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6738): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6738):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6738): Requires BLUETOOTH permission,
,I/NSApplication( 6738): Starting up...
,I/ActivityManager(  942): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6799 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  942): killProcessQuiet, pid=6241
I/ActivityManager(  942): Killing 6241:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  942): Recipient 6241
,E/WifiStateMachine(  942): handleMessage: E msg.what=131168,
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  942): processMsg: DefaultState,
E/WifiStateMachine(  942):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  942): handleMessage: X
,D/libc    (  942): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, err=8
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  942): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    (  942): [NET] android_getaddrinfo_proxy+
,D/libc    (  942): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8
E/WifiTrafficPoller(  942):  packet count Tx=218 Rx=299
E/WifiTrafficPoller(  942): notifying of data activity 2
,D/WIFI_ICON( 1220): WifiActivity: 2
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/ConnectivityService(  942): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  942): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ConnectivityHelper( 1622): [onReceive] WIFI(1): CONNECTED
I/AlarmManager(  942): [AlarmQueuing] connectivity wifi: true
,D/PMS     (  942): acquireWL(3e730f3a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 942 1000 null
D/PMS     (  942): acquireWL(267d57eb): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 942 1000 null
,D/PMS     (  942): releaseWL(267d57eb): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NetworkMonitor( 6692): type=WIFI subType= reason=null isConnected=true
,D/htcCheckinService(  942): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/GpsLocationProvider(  942): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  942): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,E/GpsLocationProvider(  942): No APN found to select.
,D/PMS     (  942): releaseWL(3e730f3a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6547): [168.1.]  listen tmrbb8,
,D/MdScDataSum( 6547): [168.1.] summary 118:p1 ignore
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/HtcWifiWanDetect(  942): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  942): [NET] android_getaddrinfo_proxy-, success
,D/Process (  942): killProcessQuiet, pid=5803,
I/ActivityManager(  942): Killing 5803:com.google.android.gm/u0a106 (adj 15): empty #17,
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  942): Recipient 5803
,V/SetupWizard( 6636): Connected to Gservices successfully
,D/ChimeraCfgMgr( 4411): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 4411): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,V/MusicLeanback( 6692): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PMS     (  942): acquireWL(1dbad963): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1870): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    ( 1870): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1870): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1870): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1870): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1870): [NET] android_getaddrinfo_proxy+
D/libc    ( 1870): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/MobileConnectivityChangeReceiver( 6636): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6636): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1543): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1543): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1543): Util - check NLP state, Allowned:false, Enabled:false,
,D/AutoSetting( 1543): service - requestNLP() NetworkLocationProvider not enabled,
D/AutoSetting( 1543): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1543): service - handleMessage() setting current location null
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4411, uid=10024, userID:0
,D/ChimeraCfgMgr( 4411): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,I/Kids    ( 4411): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
D/libc    ( 1870): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1870): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1870): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1870): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1870): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  942): acquireWL(23f7a8bf): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1870 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1870): Connected
,D/PMS     (  942): releaseWL(1dbad963): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(8973b8c): PARTIAL_WAKE_LOCK  *alarm* 0x1 942 1000 WorkSource{1000}
,E/WifiStateMachine(  942): WiFiStateMachine SCAN ALARM
V/AlarmManager(  942): sending alarm PendingIntent{322ba950: PendingIntentRecord{2e0da749 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455009644151, Int=20000
E/WifiStateMachine(  942): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
E/WifiStateMachine(  942): processMsg: ConnectedState
D/PMS     (  942): releaseWL(8973b8c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  942):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):0 dur:245 rssi=-62 f=2412 sc=60 link=72 tx=57.2, 0.0, 0.0  rx=76.5 fiv=40000 [on:0 tx:0 rx:0 period:2430] from screen [on:0 period:-984265863]
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:245 rssi=-62 f=2412 sc=60 link=72 tx=57.2, 0.0, 0.0  rx=76.5 fiv=40000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-984265861]
E/WifiStateMachine(  942): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=57.25 rxSuccessRate=76.50 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-62
E/WifiStateMachine(  942): WifiStateMachine CMD_START_SCAN with age=5877 interval=40000 maxinterval=300000
E/WifiStateMachine(  942): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  942): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=57.25 rx=76.50
E/WifiStateMachine(  942): handleMessage: X
,D/PMS     (  942): releaseWL(23f7a8bf): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(16d132d5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1870): Message class com.google.f.a.a.p
,D/PMS     (  942): releaseWL(16d132d5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  942): killProcessQuiet, pid=6016
I/ActivityManager(  942): Killing 6016:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 6016
,D/Process (  942): killProcessQuiet, pid=6320,
I/ActivityManager(  942): Killing 6320:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.appDiedLocked:5130 
,I/jxcore-log( 6415): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6415): 
,I/ActivityManager(  942): Recipient 6320
,D/Process (  942): killProcessQuiet, pid=5883
I/ActivityManager(  942): Killing 5883:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #18
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.appDiedLocked:5130 
,I/ActivityManager(  942): Recipient 5883
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1220): WifiActivity: 3
,E/WifiTrafficPoller(  942):  packet count Tx=230 Rx=311
,E/WifiTrafficPoller(  942): notifying of data activity 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155,
,E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=57.2, 0.0, 0.0  rx=76.5 bcn=0 [on:0 tx:0 rx:0 period:567] from screen [on:0 period:-984265293] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=57.2, 0.0, 0.0  rx=76.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-984265291] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1359): environment dirty rate=5 [19][1][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  942): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
,E/WifiStateMachine(  942): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=38.12 txretriesrate=0.00 rxrate=47.25 userTriggerdPenalty0
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  942):  good link -> stuck count =0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  942): handleMessage: X
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 6415): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6415): 
,I/jxcore-log( 6415): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6415): 
,I/jxcore-log( 6415): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6415): 
,I/jxcore-log( 6415): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 6415): 
,I/jxcore-log( 6415): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
I/jxcore-log( 6415): 
,I/HtcModeClient( 3199): handler message = 4011
,E/HtcModeClient( 3199): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3199): Don't start project servcice
D/HtcModeClient( 3199): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3199): connectState: CONNECTION_READY = false
D/SilentMusic( 3199): call stop
D/HtcModeClient( 3199): close connection
W/HtcModeClient( 3199): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3199): read the terminate packet, so break
D/Process (  942): killProcessQuiet, pid=3199
I/ActivityManager(  942): Killing 3199:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 3199
,E/WifiDataStallTracker(  942): DATA_MONITOR_POLL true Token 3,
,D/WifiDataStallTracker(  942): updateDataStallInfo: mDataStallTxRxSum={txSum=202 rxSum=187} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  942): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  942): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1220): WifiActivity: 0
E/WifiTrafficPoller(  942):  packet count Tx=230 Rx=311
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  942): notifying of data activity 0
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  942):  packet count Tx=230 Rx=311
,D/PMS     (  942): acquireWL(1d0811db): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6692 10159 null,
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6692, uid=10159, userID:0,
,D/PMS     (  942): releaseWL(1d0811db): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6692): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6692): Stop autocaching.
,D/WearableService( 5687): callingUid 10024, callindPid: 5687,
,I/ActivityManager(  942): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6846 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  942): acquireWL(13c2b29a): PARTIAL_WAKE_LOCK  *alarm* 0x1 942 1000 WorkSource{10076}
V/AlarmManager(  942): sending alarm PendingIntent{396d27cb: PendingIntentRecord{79bfba8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455009650520, Int=60000,
D/PMS     (  942): releaseWL(13c2b29a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6846): SMSBackupAgentService started,
D/SMSBackup( 6846): Checking restore status
D/SMSBackup( 6846): Restore complete
D/SMSBackup( 6846): cancelCheckAlarm
,E/GmsUtils( 6692): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 6692): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/SMSBackup( 6846): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  942): killProcessQuiet, pid=5447
I/ActivityManager(  942): Killing 5447:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 5447
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1220): WifiActivity: 3
,E/WifiTrafficPoller(  942):  packet count Tx=231 Rx=312
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  942): notifying of data activity 3
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155,
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=38.1, 0.0, 0.0  rx=47.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-984262270] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
,E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=38.1, 0.0, 0.0  rx=47.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-984262269] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1359): environment dirty rate=0 [2][0][0]
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
E/WifiConfigStore(  942): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
,D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  942): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=19.56 txretriesrate=0.00 rxrate=24.12 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
E/WifiStateMachine(  942): handleMessage: X
,D/AccTypeManager( 1764): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  942): Cannot find grip_rejection_width, use default value instead
,D/PMS     (  942): acquireWL(362475a7): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6286 10112 null
,D/AccTypeManager( 1764): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1622): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1622): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1622): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1622): Deferring update until onResume
D/Launcher( 1622): waitUntilResume // bindAppsUpdated
,W/ResourcesManager(  942): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  942): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6874 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
D/AccTypeManager( 1764): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1561): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,D/PMS     (  942): releaseWL(362475a7): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,E/ExternalAccountType( 1764): Unsupported attribute readOnly
,W/ResourcesManager( 6286): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6286): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/PackageManager(  942): Unable to load service info ResolveInfo{3790919b com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  942): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
,W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  942): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  942): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  942): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  942): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  942): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  942): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1799): DISABLE
,I/GCoreNlp( 1799): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  942): acquireWL(32c5201a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1799 10024 WorkSource{10024 com.google.android.gms},
I/BackupManagerService(  942): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/PMS     (  942): releaseWL(32c5201a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8
,D/LocationProviderProxy(  942): applying state to connected service
E/WifiTrafficPoller(  942):  packet count Tx=232 Rx=312
E/WifiTrafficPoller(  942): notifying of data activity 2
D/WIFI_ICON( 1220): WifiActivity: 2
D/LocationProviderProxy(  942): applying state to connected service
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  942): acquireWL(bef9872): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(2fa2d4c3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(bef9872): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(2fa2d4c3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationManagerService(  942): getProviders()=[passive],
,I/ActivityManager(  942): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6903 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/art     (  408): Explicit concurrent mark sweep GC freed 8644(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 21.079ms
,I/[PluginManager]RegisterService( 1543): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1543): handle notify Blinkfeed plugin client changed
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 162us total 17.100ms
D/PackageBroadcastService( 4411): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4411): Null package name or gms related package.  Ignoreing.
D/PMS     (  942): acquireWL(5a7a1e9): PARTIAL_WAKE_LOCK  Icing 0x1 4411 10024 WorkSource{10024 com.google.android.gms}
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 151us total 16.180ms
D/PMS     (  942): acquireWL(1eeb1e6e): PARTIAL_WAKE_LOCK  AsyncService 0x1 6045 10167 null
,D/PMS     (  942): releaseWL(1eeb1e6e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/Icing   ( 4411): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  942): acquireWL(1035bd9c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6045 10167 null
,D/PMS     (  942): releaseWL(1035bd9c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 6874): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,D/PMS     (  942): releaseWL(5a7a1e9): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/UpdateIcingCorporaServi( 6874): UpdateCorporaTask done [took 105 ms] updated apps [took 105 ms] 
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8,
D/WIFI_ICON( 1220): WifiActivity: 0
E/WifiTrafficPoller(  942):  packet count Tx=232 Rx=312
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  942): notifying of data activity 0
,I/Prism.ItemManager( 1622): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1622): loadItems() com.htc.launcher.pageview.WidgetManager@2052b4db +
I/Prism.WidgetManager( 1622): onLoadItems() +
,W/ResourcesManager( 1622): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 1622): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1622): Copying FileAsset 0x55a2f93e70 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1622): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1622): onLoadItems() -
I/Prism.ItemManager( 1622): loadItems() com.htc.launcher.pageview.WidgetManager@2052b4db -
,D/PhoneApp( 1561): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1561): -- N1 =0
,D/PhoneApp( 1561): -- N2 =0
,D/PhoneApp( 1561): -- N3 =0,
,E/WifiDataStallTracker(  942): DATA_MONITOR_POLL true Token 3,
D/WifiDataStallTracker(  942): updateDataStallInfo: mDataStallTxRxSum={txSum=202 rxSum=187} preTxRxSum={txSum=202 rxSum=187}
D/WifiDataStallTracker(  942): updateDataStallInfo: NONE,
D/WifiDataStallTracker(  942): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8
,D/WIFI_ICON( 1220): WifiActivity: 1
E/WifiTrafficPoller(  942):  packet count Tx=232 Rx=313
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  942): notifying of data activity 1
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155,
E/WifiStateMachine(  942): processMsg: ConnectedState
,E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=19.6, 0.0, 0.0  rx=24.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-984259253] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=19.6, 0.0, 0.0  rx=24.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-984259252] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
,W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1359): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  942): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
E/WifiStateMachine(  942): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=10.28 txretriesrate=0.00 rxrate=12.56 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60,
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
E/WifiStateMachine(  942): handleMessage: X
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -62, 3
,I/jxcore-log( 6415): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 6415): 
,I/jxcore-log( 6415): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 6415): 
,I/jxcore-log( 6415): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6415): 
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  942):  packet count Tx=232 Rx=313
D/WIFI_ICON( 1220): WifiActivity: 0
E/WifiTrafficPoller(  942): notifying of data activity 0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 6415): Test app app.js loaded,
I/jxcore-log( 6415): 
,I/chromium( 6415): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): 	Bluetooth MAC address: 90:E7:C4:F6:69:77, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6415): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b6f2949 added. We now have 1 listener(s),
D/BluetoothAdapter( 6415): 673614589: getState(). Returning 12
,I/jxcore-log( 6415): BLE advertisement is supported,
I/jxcore-log( 6415): 
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  942):  packet count Tx=233 Rx=317
,D/WIFI_ICON( 1220): WifiActivity: 3
E/WifiTrafficPoller(  942): notifying of data activity 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/PMS     (  942): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  942): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@d4bbda8
W/SensorService(  942): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  942): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  942): pid=942, uid=1000
W/SensorService(  942): Active sensors: size = 4
W/SensorService(  942): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  942): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  942): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  942): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  942): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@d4bbda8, eanble = 0, strlen(mName) = 90
W/PMN     (  942): goingToSleep
W/SensorService(  942): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  942): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@21f17fd3
W/SensorService(  942): Listener[1] = com.htc.smartdim.sensor_eye@ef465af
W/SensorService(  942): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1220): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  942): mWirelessDisplayManager is null
D/PMS     (  942): acquireWL(2aeb37a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 942 1000 null
,W/PMN     (  942): goingToSleep done
W/HtcSystemUPManager(  942): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/PMS     (  942): mWirelessDisplayManager is still null
D/AlarmManager(  942): ACTION_SCREEN_ON
I/AlarmManager(  942): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  942): [AlarmQueuing] done recovering
I/AlarmManager(  942): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  942): [AlarmQueuing] done EPS screen off alarm recovering
I/PMS     (  942): Sleeping (uid 1000)...
D/XAN-DPS (  942): prepareColorFade 1
,E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL true Token 24
E/WifiTrafficPoller(  942):  packet count Tx=233 Rx=317
E/WifiTrafficPoller(  942): notifying of data activity 0
,D/PMS     (  942): releaseWL(2aeb37a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/WifiDataStallTracker(  942): ENABLE_DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  942): updateDataStallInfo: mDataStallTxRxSum={txSum=203 rxSum=188} preTxRxSum={txSum=203 rxSum=188}
D/WifiDataStallTracker(  942): updateDataStallInfo: NONE
D/WifiDataStallTracker(  942): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  942): handleMessage: E msg.what=131167
,E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
,E/WifiStateMachine(  942):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  942):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1359): SET_SCREEN_ON:On
I/wpa_supplicant( 1359): htc_wext_set_keepalive +
I/wpa_supplicant( 1359): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1359): getPrivFuncNum +	
I/wpa_supplicant( 1359): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1359): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1359): htc_wext_set_keepalive - ret = 0
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
I/wpa_supplicant( 1359): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1359): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  942): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  942): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  942): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131154
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1359): wlan0: Control interface command 'SIGNAL_POLL'
,V/SRS_Proc(  399): ParamSet string: screen_state=on
,E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
I/wpa_supplicant( 1359): environment dirty rate=0 [1][0][0]
D/WifiController(  942): handleMessage: E msg.what=155650
D/WifiController(  942): processMsg: DeviceActiveState
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiController(  942): processMsg: StaEnabledState
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
D/WifiController(  942): processMsg: DefaultState
E/WifiConfigStore(  942): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131127
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
D/WifiController(  942): handleMessage: X
E/WifiStateMachine(  942):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0,
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131129
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
,E/WifiStateMachine(  942):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1359): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1359): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  942): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
,E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  942): handleMessage: X
,D/NetworkPolicy(  942): updateScreenOn: false,
V/NetworkPolicy(  942): updateIfacesLocked()
I/Adreno-EGL(  942): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  942): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  942): Build Date: 03/09/15 Mon
I/Adreno-EGL(  942): Local Branch: 
I/Adreno-EGL(  942): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  942): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  942):                  d74aa161a12b9c6fc6332151
D/NetworkManagementService(  942): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WIFI_ICON( 1220): WifiActivity: 0,
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
,I/ActivityManager(  942): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6941 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/GpsLocationProvider(  942): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/IntentController( 1220): receive(android.intent.action.SCREEN_ON,1,false)
,D/PMS     (  942): acquireWL(fe48d46): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1799 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  942): acquireWL(317fab07): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(fe48d46): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  942): prepareColorFade done
D/PMS     (  942): releaseWL(317fab07): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  942): setBrightness to 0
W/ContextImpl( 6941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  942): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@21f17fd3
W/SensorService(  942): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  942): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  942): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,W/ContextImpl( 6941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,W/SensorService(  942): pid=942, uid=1000,
W/SensorService(  942): Active sensors: size = 3
W/SensorService(  942): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  942): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  942): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  942): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@21f17fd3, eanble = 0, strlen(mName) = 67
W/SensorService(  942): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  942): Listener[0] = com.htc.smartdim.sensor_eye@ef465af
V/ActivityManager(  942): Display changed displayId=0
W/SensorService(  942): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1330): [EventService]  onDisplayChanged: 0
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/DotMatrix( 1330): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/PowerUsageList:PowerUsageHelper( 6941): MY_DEBUG = false
,D/AlarmManager(  942): ACTION_SCREEN_OFF
,E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 25
I/AlarmManager(  942): [AlarmQueuing] screen off now: 
D/WifiDataStallTracker(  942): stopDataStallAlarm 
I/AlarmManager(  942): [AlarmQueuing] data connection: true
E/WifiDataStallTracker(  942): ENABLE_DATA_MONITOR_POLL false Token 4
I/AlarmManager(  942): [AlarmQueuing] wifi connection: true
E/WifiStateMachine(  942): handleMessage: E msg.what=131167
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
V/SRS_Proc(  399): ParamSet string: screen_state=off
E/WifiStateMachine(  942):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  942):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
D/wpa_supplicant( 1359): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1359): SET_SCREEN_ON:Off
I/wpa_supplicant( 1359): htc_wext_set_keepalive +
I/wpa_supplicant( 1359): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1359): getPrivFuncNum +	
I/wpa_supplicant( 1359): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1359): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1359): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1359): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1359): htc_wext_set_keepalive - ret = 0
D/NetworkPolicy(  942): updateScreenOn: false
E/WifiStateMachine(  942): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
V/NetworkPolicy(  942): updateIfacesLocked()
D/WifiStateMachine(  942): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  942): handleScreenStateChanged Exit: false
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131154
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
D/NetworkManagementService(  942): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiController(  942): handleMessage: E msg.what=155651
E/WifiStateMachine(  942):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  942): handleMessage: X
D/WifiController(  942): processMsg: DeviceActiveState
D/WifiController(  942): processMsg: StaEnabledState,
D/WifiController(  942): processMsg: DefaultState
,D/WifiController(  942): handleMessage: X
D/SmartSyncUtils( 6941): isEpsOn(), nState = 0
,D/PMS     (  942): acquireWL(3d974fa0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6941 1000 null
,I/SensorManager( 1220): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@995b0b, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  942): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  942): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  942): pid=1220, uid=10041
W/SensorService(  942): Active sensors: size = 4
W/SensorService(  942): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  942): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  942): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  942): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  942): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@995b0b, eanble = 1, strlen(mName) = 55
W/SensorService(  942): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  942): Listener[0] = com.htc.smartdim.sensor_eye@ef465af
W/SensorService(  942): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@995b0b
,W/SensorService(  942): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1330): [EventService] getTotalRam: 1842 Mb
D/GpsLocationProvider(  942): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/PMS     (  942): releaseWL(3d974fa0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ContactMessageStore( 1561): start background delete task...
I/IntentController( 1220): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1561): size: 0 , 0
D/ContactMessageStore( 1561): Background delete complete
,D/PMS     (  942): acquireWL(96fd759): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1799 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  942): releaseWL(96fd759): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  942): acquireWL(11ff1e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(11ff1e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/AutoSetting( 1543): service - mHandler: cancel location update,
D/AutoSetting( 1543): service -           changes count: 0
,I/RemoteViews( 1220): setHTCTheme(com.htc.updater,true,33751145)
,I/RemoteViews( 1220): apply : com.htc.updater 0 11 1 36,
,I/PowerUsageList:PowerUsageHelper( 6941): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/Process (  942): killProcessQuiet, pid=6608,
I/ActivityManager(  942): Killing 6608:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  942): Explicit concurrent mark sweep GC freed 37331(1988KB) AllocSpace objects, 2(680KB) LOS objects, 33% free, 18MB/28MB, paused 1.909ms total 203.884ms,
,D/PowerUsageList:BatterySipperExt( 6941): gen(), null == sipper.uidObj, userId = 0,
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  942): Setting HAL interactive mode to false
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  942): Excessive delay in setPowerMode(): 290ms
,D/PMS     (  942): Setting HAL interactive mode to false done
D/PMS     (  942): Setting HAL auto-suspend mode to true
D/PMS     (  942): Setting HAL auto-suspend mode done
,I/ActivityManager(  942): Recipient 6608
D/PMS     (  942): acquireWL(3298f3ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 942 1000 null
,I/BatteryService(  942): n_update end,
D/PMS     (  942): releaseWL(3298f3ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  942): updateBatteryInfo,
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/InputMethodManagerService(  942): screenObserver, isScreenOn=false
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/StatusBarManagerService(  942): swetImeWindowStatus vis=0 backDisposition=0
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/InputMethodManagerService(  942): Disable input method client, pid=6415
I/InputMethodManager( 6415): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{130a11ee VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@45f024e
D/PowerUI ( 1220): closing low battery warning: level=100
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/HtcSystemUPManager(  942): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HABCtrl (  942): TPE algorithm. remove timeout.
,D/PMS     (  942): OOBE c monitor 11
I/InputManager(  942): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,D/UsbnetService(  942): BroadcastReceiver::onReceive+
D/NotificationService(  942): plugged=true pluggin=true
I/IntentController( 1220): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  942): runPSCheck
D/UsbnetService(  942): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  942): Checking...
D/UsbnetService(  942):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  942): >> updateStatus
D/UsbnetService(  942): BroadcastReceiver::onReceive-
D/WifiController(  942): battery changed pluggedType: 2
D/WifiController(  942): handleMessage: E msg.what=155652
D/WifiController(  942): processMsg: DeviceActiveState
D/WifiController(  942): processMsg: StaEnabledState
D/WifiController(  942): processMsg: DefaultState
D/WifiController(  942): handleMessage: X
D/NfcService( 1575): ScreenObserver: OFF
,I/HtcPowerSaver(  942): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  942): << updateStatus
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
D/NfcService( 1575): applyRouting - 0
W/ContextImpl(  942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  942): acquireWL(1bb1c5cc): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1575 1027 null
D/NfcService( 1575): applyRouting -2
D/NfcService( 1575): applyRouting
D/NfcService( 1575): Ignore this applyRouting...
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL false Token 26 num clients 8
D/PMS     (  942): releaseWL(1bb1c5cc): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/SmartDim(  942): Init customizeScreenOffDelayClass error
,W/ContextImpl( 6941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/Process (  942): killProcessQuiet, pid=6500,
I/ActivityManager(  942): Killing 6500:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,I/ClockController( 1220): stop clock update:screen off
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155,
E/WifiStateMachine(  942): processMsg: ConnectedState
,E/WifiStateMachine(  942):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-984256232] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  942): processMsg: L2ConnectedState
,E/WifiStateMachine(  942):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-984256231] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
,E/WifiStateMachine(  942): handleMessage: X
,I/ActivityManager(  942): Recipient 6500,
,W/ContextImpl( 6941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6941): MY_DEBUG = false
D/SmartSyncUtils( 6941): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6941): isEpsOn(), nState = 0
,W/ContextImpl( 6941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  942): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  942): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@ef465af
W/SensorService(  942): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  942): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  942): pid=942, uid=1000
W/SensorService(  942): Active sensors: size = 3
W/SensorService(  942): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  942): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  942): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  942): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@ef465af, eanble = 0, strlen(mName) = 35
W/SensorService(  942): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  942): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@995b0b
W/SensorService(  942): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  942): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  942): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  942): pid=942, uid=1000
W/SensorService(  942): Active sensors: size = 2
W/SensorService(  942): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  942): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  942): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@ef465af, eanble = 0, strlen(mName) = 35
W/SensorService(  942): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  942): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@995b0b
W/SensorService(  942): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/ActivityThread(  942): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@2964cdbc that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  942): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@2964cdbc that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  942): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  942): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  942): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  942): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  942): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  942): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  942): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  942): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  942): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  942): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  942): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  942): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  942): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  942): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/SensorManager(  942): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@ef465af
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL false Token 26 num clients 8
,I/ActivityManager(  942): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6975 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/SmartSyncUtils( 6941): getMobilePolicyEnabled, result = true,
,D/Process (  942): killProcessQuiet, pid=6547
I/ActivityManager(  942): Killing 6547:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 ,
,D/WifiService(  942): New client listening to asynchronous messages
E/WifiTrafficPoller(  942): ADD_CLIENT: 9
,I/ActivityManager(  942): Recipient 6547
,D/PMS     (  942): releaseWL(3f49b987): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/Process (  942): killProcessQuiet, pid=6636
I/ActivityManager(  942): Killing 6636:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 6636
,E/WifiDataStallTracker(  942): DATA_MONITOR_POLL false Token 5
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2183] from screen [on:0 period:-984254046] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
,E/WifiStateMachine(  942):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-984254044] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942): handleMessage: X
,D/HtcUPManager( 1220): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  942): DATA_MONITOR_POLL false Token 5
,D/ContactMessageStore( 1561): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1561): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/Process (  942): killProcessQuiet, pid=5601
,I/ActivityManager(  942): Killing 5601:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 5601,
,E/WifiStateMachine(  942): handleMessage: E msg.what=131165,
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  942): handleMessage: X
,D/PMS     (  942): acquireWL(1d92d11b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 942 1000 WorkSource{1000},
V/AlarmManager(  942): sending alarm PendingIntent{14ff5782: PendingIntentRecord{2dee0e93 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=116434, Int=0
V/AlarmManager(  942): sending alarm PendingIntent{291b72b8: PendingIntentRecord{ff41891 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143163, Int=0
,D/PMS     (  942): releaseWL(1d92d11b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On,
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/AutoSetting( 1543): service - handleMessage() stop self,
,D/AutoSetting( 1543): service - onDestroy() END,
D/AutoSetting( 1543): service - handleMessage() quit looper
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  942): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  942): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  942): acquireWL(3b90d3f6): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 942 1000 null
,D/libc    (  942): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  942): [NET] android_getaddrinfofornet-, err=8
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  942): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  942): [NET] android_getaddrinfo_proxy+
D/libc    (  942): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  942): [NET] android_getaddrinfo_proxy-, success
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  942): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  942): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  942): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  942):  [handleDownloadXtraData]inject done.
D/PMS     (  942): acquireWL(fee3982): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 942 1000 null
D/GpsLocationProvider(  942): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  942): releaseWL(3b90d3f6): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  942): releaseWL(fee3982): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/WifiStateMachine(  942): handleMessage: E msg.what=131326,
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState what:131326 2 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  942): handleMessage: X
,W/ContextImpl(  942): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  942): acquireWL(1a804893): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 942 1000 null
I/BatteryService(  942): n_update end
D/PMS     (  942): releaseWL(1a804893): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  942): updateBatteryInfo
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): closing low battery warning: level=100
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/NotificationService(  942): plugged=true pluggin=true
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  942): runPSCheck
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  942): Checking...
D/UsbnetService(  942): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  942): >> updateStatus
D/UsbnetService(  942): onReceive BATTERY_CHANGED
D/WifiController(  942): battery changed pluggedType: 2
D/UsbnetService(  942):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  942): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  942): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  942): handleMessage: E msg.what=155652
I/HtcPowerSaver(  942): << updateStatus
D/WifiController(  942): processMsg: DeviceActiveState
,D/WifiController(  942): processMsg: StaEnabledState
D/WifiController(  942): processMsg: DefaultState
D/WifiController(  942): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1561): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  942): acquireWL(136de0d0): PARTIAL_WAKE_LOCK  *alarm* 0x1 942 1000 WorkSource{1000},
,V/AlarmManager(  942): sending alarm PendingIntent{8ca6bce: PendingIntentRecord{1a5cdaef android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455009711973, Int=0
,D/PMS     (  942): acquireWL(312848c9): PARTIAL_WAKE_LOCK  *backup* 0x1 942 1000 null
V/AlarmManager(  942): sending alarm PendingIntent{14ff5782: PendingIntentRecord{2dee0e93 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=176434, Int=0
V/AlarmManager(  942): sending alarm PendingIntent{81839fc: PendingIntentRecord{28e3a885 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=199134, Int=0
V/AlarmManager(  942): sending alarm PendingIntent{222576da: PendingIntentRecord{3ac6370b com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190634, Int=0
,D/PMS     (  942): acquireWL(8acf9e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  942): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  942): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  942): releaseWL(312848c9): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  942): releaseWL(136de0d0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/PMS     (  942): acquireWL(173b4801): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(8acf9e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  942): releaseWL(173b4801): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  942): acquireWL(341c7c83): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(341c7c83): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  942): acquireWL(2e631e00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(2e631e00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(2757f639): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(368f647e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  942): acquireWL(adc1a2c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  942): releaseWL(2757f639): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1870): Vacuum at: now=1455009743010 tag=VacuumService,
,D/PMS     (  942): releaseWL(368f647e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  942): acquireWL(17b94a8a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1870): Using platform SSLCertificateSocketFactory
,D/PMS     (  942): releaseWL(17b94a8a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  942): acquireWL(3f56f8fb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(3f56f8fb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1870): No account for auth token provided
,D/libc    ( 1870): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1870): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1870): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
,D/libc    ( 1870): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1870): [NET] android_getaddrinfo_proxy+
D/libc    ( 1870): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605,
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1870): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1870): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1870): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1870): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1870): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1870): No account for auth token provided,
,W/Uploader( 1870): No account for auth token provided,
,W/Uploader( 1870):  no longer exists, so no auth token.,
,W/Uploader( 1870): No account for auth token provided,
,I/GLSUser ( 1870): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1870): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1870): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1870): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1220): reapply : com.google.android.gms 3 40
,E/Uploader( 1870): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1870): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1870): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1870): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1870): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1870): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1870): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1870): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1870): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1870): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1870): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1870): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1870): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1870): No account for auth token provided
,D/PMS     (  942): releaseWL(adc1a2c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  942): acquireWL(a027ccf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(a027ccf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  942): acquireWL(1c30665c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(1c30665c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1543): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@c0c7203
,I/ActivityManager(  942): Killing 6476:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=6476
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 6476
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  942): acquireWL(6f3cd65): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 942 1000 null
,I/BatteryService(  942): n_update end
D/PMS     (  942): releaseWL(6f3cd65): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  942): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  942): updateBatteryInfo
D/UsbnetService(  942): onReceive BATTERY_CHANGED
D/NotificationService(  942): plugged=true pluggin=true
D/UsbnetService(  942):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  942): runPSCheck
D/UsbnetService(  942): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  942): Checking...
I/HtcPowerSaver(  942): >> updateStatus
D/WifiController(  942): handleMessage: E msg.what=155652
D/WifiController(  942): battery changed pluggedType: 2
D/WifiController(  942): processMsg: DeviceActiveState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  942): processMsg: StaEnabledState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  942): processMsg: DefaultState
,I/HtcPowerSaver(  942): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  942): handleMessage: X
I/HtcPowerSaver(  942): << updateStatus
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6415): --= Surplus to requirements =--
I/jxcore-log( 6415): 
,I/jxcore-log( 6415): ****TEST TOOK:  ms ****
I/jxcore-log( 6415): 
I/jxcore-log( 6415): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6415): 
,E/cutils-trace( 7014): Error opening trace file: Permission denied (13),
,D/CustomizationManager( 7014): ====startRecUseTime====,
D/htc.customization.log.level( 7014):  is 
W/CustomizationLogLevel( 7014): Level value is invalid, use default level 2
,D/CustomizationManager( 7014):  Read ACC file spent 0.047 (s)
,D/CIDMapFileReader( 7014): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7014): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 7014): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7014): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7014): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7014): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7014): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 7014): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7014): Parsing tag category name = system
,I/CustomizationCIDLoader( 7014): Parsing tag category name = application
,I/CustomizationCIDLoader( 7014): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7014): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 7014): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7014): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7014): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 7014): add string-array item, value = 42507,
I/CustomizationCIDLoader( 7014): add string-array item, value = 21902
I/CustomizationCIDLoader( 7014): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7014): add string-array item, value = 23420,
I/CustomizationCIDLoader( 7014): add string-array item, value = 22299
I/CustomizationCIDLoader( 7014): add string-array item, value = 24002
I/CustomizationCIDLoader( 7014): add string-array item, value = 23210,
I/CustomizationCIDLoader( 7014): add string-array item, value = 23205
I/CustomizationCIDLoader( 7014): add string-array item, value = 23806
I/CustomizationCIDLoader( 7014): add string-array item, value = 23430
I/CustomizationCIDLoader( 7014): add string-array item, value = 23408,
I/CustomizationCIDLoader( 7014): add string-array item, value = 27205
I/CustomizationCIDLoader( 7014): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7014): add string-array item, value = 21902:C:1:0,
I/CustomizationCIDLoader( 7014): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7014): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7014): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7014): add string-array item, value = 24002:D:0:0
,I/CustomizationCIDLoader( 7014): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7014): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7014): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7014): add string-array item, value = 23430:C:1:0
,I/CustomizationCIDLoader( 7014): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7014): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7014):  Read CID file spent 0.099 (s)
,D/CustomizationManager( 7014):  All configurations done spent 0.099 (s)
,D/PackageManager(  942): deletePackageAsUser: pkg=com.test.thalitest, pid=7014, uid=2000 userid=0,
,D/Process (  942): killProcessQuiet, pid=6415,
I/ActivityManager(  942): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  942): Killing 6415:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  942): Skipping PackageSetting{20d45af0 com.example.hello/10374} due to missing metadata,
,I/ActivityManager(  942): Recipient 6415
I/WindowState(  942): WIN DEATH: Window{3dd3891c u0 com.test.thalitest/com.test.thalitest.MainActivity},
D/WifiService(  942): Client connection lost with reason: 4
,E/InputEventReceiver( 1400): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2bd22afa uid 10366 pid 6415} (c)'
,E/libprocessgroup(  942): failed to kill 1 processes for processgroup 6415,
,I/ActivityManager(  942):   Force finishing activity ActivityRecord{9eb8253 u0 com.test.thalitest/.MainActivity t8}
,I/ActivityManager(  942): Force stopping com.test.thalitest appid=10366 user=0: pkg removed,
,I/ActivityManager(  942):   Force finishing activity ActivityRecord{9eb8253 u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  942): Duplicate finish request for ActivityRecord{9eb8253 u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  942): Spurious death for ProcessRecord{3f816a3a 6415:com.test.thalitest/u0a366}, curProc for 6415: null,
,D/DotMatrix( 1330): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
D/DotMatrix( 1330): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/SystemReader(  942): Cannot find grip_rejection_width, use default value instead
D/PMS     (  942): acquireWL(268b8c48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,W/GeofencerStateMachine( 1799): Ignoring removeGeofence because network location is disabled.
D/PMS     (  942): releaseWL(268b8c48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 1764): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1764): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/art     ( 1622): Explicit concurrent mark sweep GC freed 24785(1484KB) AllocSpace objects, 4(244KB) LOS objects, 34% free, 29MB/45MB, paused 814us total 98.055ms
,I/Prism.ItemManager( 1622): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1622): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/VoicemailCleanupService( 1723): Cleaning up data for package: com.test.thalitest
D/PhoneApp( 1561): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1543): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest,
D/AccTypeManager( 1764): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Launcher( 1622): Deferring update until onResume
D/Launcher( 1622): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1622): action: android.intent.action.PACKAGE_REMOVED
,E/ExternalAccountType( 1764): Unsupported attribute readOnly
,I/[PluginManager]RegisterService( 1543): handle notify Blinkfeed plugin client changed,
,I/ActivityManager(  942): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7034 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/InputMethodManagerService(  942): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/ResourcesManager(  942): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  942): Explicit concurrent mark sweep GC freed 30541(2MB) AllocSpace objects, 5(496KB) LOS objects, 33% free, 18MB/28MB, paused 20.721ms total 253.587ms
,I/art     (  942): WaitForGcToComplete blocked for 232.140ms for cause Explicit
,D/StatusBarManagerService(  942): setSystemUiVisibility(0x8700),
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  942): hiding MENU key
,D/StatusBarManagerService(  942): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  942): hiding MENU key
,D/FindExtension( 1622): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1622): Defer allocateBuffers to drawing time
W/ContextImpl( 7034): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,W/InputMethodManagerService(  942): Got RemoteException sending setActive(false) notification to pid 6415 uid 10366
D/StatusBarManagerService(  942): swetImeWindowStatus vis=0 backDisposition=0
,I/ActivityManager(  942): Killing 6738:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
,D/Process (  942): killProcessQuiet, pid=6738
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  942): Unable to load service info ResolveInfo{25cf7816 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  942): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  942): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  942): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  942): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  942): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  942): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  942): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/JobSchedulerService(  942): Receieved: android.intent.action.PACKAGE_REMOVED,
,I/ActivityManager(  942): Recipient 6738,
,I/art     (  942): Explicit concurrent mark sweep GC freed 7759(428KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 18MB/28MB, paused 4.054ms total 266.722ms,
,W/asset   (  942): Copying FileAsset 0x55a30c8cb0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.,
,E/NetworkScheduler.SchedulerReceiver( 1870): Invalid parameter app,
E/NetworkScheduler.SchedulerReceiver( 1870): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  942): acquireWL(1be27698): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1870 10024 WorkSource{10024 com.google.android.gms}
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
,D/TaskPersister(  942): removeObsoleteFile: deleting file=8_task.xml
,D/TaskPersister(  942): removeObsoleteFile: deleting file=8_task_thumbnail.png
,D/PMS     (  942): releaseWL(1be27698): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4411): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4411): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 4411): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
,D/ChimeraCfgMgr( 4411): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4411): Module APK com.google.android.play.games already loaded
D/AccountUtils( 4411): Clearing selected account for com.test.thalitest
,I/ActivityManager(  942): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7065 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/LocationSettingsChecker( 4411): Removing dialog suppression flag for package com.test.thalitest,
,D/GOOGLEHELP_CompatibleDatabase( 4411): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1,
D/GOOGLEHELP_CompatibleDatabase( 4411): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 4411): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4411): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4411): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1,
D/GOOGLEHELP_CompatibleDatabase( 4411): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4411): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4411): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 4411): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 4411): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1,
,D/GOOGLEHELP_CompatibleDatabase( 4411): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 4411): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 4411): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 4411): Using Auth Proxy for data requests.
,I/ConfigService( 1870): onCreate,
,I/ConfigFetchService( 4411): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  942): acquireWL(269cf586): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4411 10024 null
,W/BaseAppContext( 4411): Using Auth Proxy for data requests.
D/PMS     (  942): releaseWL(269cf586): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/PeopleContactsSync( 4411): CP2 sync disabled
,D/PMS     (  942): acquireWL(19c2e412): PARTIAL_WAKE_LOCK  Icing 0x1 4411 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4411, uid=10024, userID:0
,I/Icing   ( 4411): doRemovePackageData com.test.thalitest
,D/PMS     (  942): releaseWL(19c2e412): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 1870): Explicit concurrent mark sweep GC freed 29920(1664KB) AllocSpace objects, 11(560KB) LOS objects, 47% free, 4MB/8MB, paused 1.432ms total 43.154ms,
,W/DriveInitializer( 4411): Awaiting to be initialized
,W/DriveInitializer( 4411): Background init thread started
,E/SQLiteLog( 4411): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
,E/SQLiteDBG( 4411): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55a2a7d640
,I/GAv4    ( 7065): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7065):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7065):   adb logcat -s GAv4
,E/DocListDatabase( 4411): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 4411): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4411): 	,at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4411): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/DocListDatabase( 4411): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4411): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4411): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/DocListDatabase( 4411): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 4411): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 4411): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,W/DriveInitializer( 4411): Background init thread ended
,E/SQLiteLog( 4411): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4411): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55a2a7d640
E/AndroidRuntime( 4411): FATAL EXCEPTION: Background initialization thread,
E/AndroidRuntime( 4411): Process: com.google.android.gms, PID: 4411
E/AndroidRuntime( 4411): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4411): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4411): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 4411): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4411): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4411): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
,E/AndroidRuntime( 4411): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 4411): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 4411): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/ActivityManager(  942): App crashed! Process: com.google.android.gms
E/DriveAsyncService( 4411): disk I/O error (code 3850)
E/DriveAsyncService( 4411): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4411): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4411): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4411): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4411): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4411): ,	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4411): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/DriveAsyncService( 4411): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4411): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 4411): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4411): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4411): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 4411): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/DriveAsyncService( 4411): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4411): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 7065): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/Process ( 4411): killProcess, pid=4411
,W/GAv4    ( 7065): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,E/SharedPreferencesImpl( 7065): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 7065): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,D/Process ( 4411): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  942): Can't write: system_app_crash
E/DropBoxManagerService(  942): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  942): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  942): 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  942): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  942): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  942): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  942): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  942): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  942): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  942): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  942): 	... 5 more
,W/GAv4    ( 7065): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,E/SharedPreferencesImpl( 7065): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 7065): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,E/SQLiteDatabase( 7065): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 7065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
E/SQLiteDatabase( 7065): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7065): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7065): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7065): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7065): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7065): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/SQLiteDatabase( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7065): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7065): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7065): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 7065): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
E/SQLiteDatabase( 7065): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7065): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7065): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7065): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7065): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7065): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7065): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7065): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7065): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 7065): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 7065): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7065): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 7065): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7065): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 7065): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7065): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 7065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7065): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7065): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7065): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7065): 	at aen.run(PG:536)
,E/lowmemorykiller(  381): Error writing /proc/4411/oom_score_adj; errno=22,
,E/JavaBinder(  942): !!! FAILED BINDER TRANSACTION !!!,
W/ActivityManager(  942): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,D/VoldConnector(  942): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 7065): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,D/PMS     (  942): acquireWL(2253cc36): PARTIAL_WAKE_LOCK  AsyncService 0x1 6045 10167 null
,E/SQLiteDatabase( 7065): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7065): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7065): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7065): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7065): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7065): 	at aej.c(PG:139)
E/SQLiteDatabase( 7065): 	at aej.b(PG:398)
E/SQLiteDatabase( 7065): 	at agf.f(PG:417)
E/SQLiteDatabase( 7065): 	at oe.run(PG:1112)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7065): 	at java.lang.Thread.run(Thread.java:818)
D/PMS     (  942): releaseWL(2253cc36): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,E/AbstractDatabaseInstance( 7065): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 7065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
,E/AbstractDatabaseInstance( 7065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7065): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7065): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7065): 	at hix$a.a(PG:125),
E/AbstractDatabaseInstance( 7065): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7065): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 7065): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 7065): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 7065): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 7065): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7065): 	at java.lang.Thread.run(Thread.java:818)
D/PMS     (  942): acquireWL(373f54a4): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6045 10167 null
W/ResourcesManager( 7065): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  942): Recipient 4411
D/WifiService(  942): Client connection lost with reason: 4
,I/ActivityManager(  942): Process com.google.android.gms (pid 4411) has died
,W/ActivityManager(  942): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10917ms
W/ActivityManager(  942): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10917ms
W/ActivityManager(  942): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10917ms
,I/ConfigService( 1870): onDestroy
D/PMS     (  942): releaseWL(373f54a4): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 6874): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  942): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=7115 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,V/JNIHelp ( 7065): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 6874): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
,E/SQLiteDBG( 6874): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55a292eba0
,W/System  ( 7065): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 7065): Installed default security provider GmsCore_OpenSSL,
,I/ActivityManager(  942): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=7137 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,E/SharedPreferencesImpl( 6874): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
,E/AndroidRuntime( 6874): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6874): Process: com.google.android.googlequicksearchbox:search, PID: 6874
E/AndroidRuntime( 6874): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6874): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method),
E/AndroidRuntime( 6874): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 6874): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6874): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6874): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 6874): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 6874): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 6874): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 6874): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 6874): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 6874): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 6874): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 6874): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 6874): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 6874): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 6874): 	at com.google.android.search.core.icingsync,.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 6874): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6874): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6874): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 7065): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7065): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7065): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7065): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7065): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7065): 	at aej.c(PG:139)
E/SQLiteDatabase( 7065): 	at aej.a(PG:358)
E/SQLiteDatabase( 7065): 	at aej.a(PG:345),
E/SQLiteDatabase( 7065): 	at agf.c(PG:884)
E/SQLiteDatabase( 7065): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 7065): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7065): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7065): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 7065): Failed to query Account133 object
,E/AbstractDatabaseInstance( 7065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7065): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7065): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7065): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7065): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7065): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7065): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 7065): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 7065): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 7065): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 7065): ,	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 7065): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7065): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7065): 	at java.lang.Thread.run(Thread.java:818)
E/ActivityManager(  942): App crashed! Process: com.google.android.googlequicksearchbox:search
,I/DeviceManagement( 7115): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7115 dbg=false s=true
D/Process ( 6874): killProcess, pid=6874
D/Process ( 6874): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
,I/DeviceManagement( 7115): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
E/DropBoxManagerService(  942): Can't write: system_app_crash
E/DropBoxManagerService(  942): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  942): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  942): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  942): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  942): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  942): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  942): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  942): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  942): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  942): 	... 5 more
,I/DeviceManagement( 7115): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DeviceManagement( 7115): WorkflowService: Starting workflow service
,I/DeviceManagement( 7115): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@127eaaa7] args=[Bundle[mParcelledData.dataSize=112]]
I/DeviceManagement( 7115): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 7115): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 7115): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 7115): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  942): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7166 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
,E/SharedPreferencesImpl( 7065): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak,
,I/DeviceManagement( 7115): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 7115): SessionStateController: Checking invariants...
,I/ActivityManager(  942): Recipient 6874
,I/ActivityManager(  942): Process com.google.android.googlequicksearchbox:search (pid 6874) has died
W/ActivityManager(  942): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10630ms,
,E/SQLiteDatabase( 7166): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
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
E/SQLiteDatabase( 7166): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 7166): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 7166): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 7166): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 7166): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 7166): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 7166): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 7166): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 7166): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7166): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7166): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7166): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7166): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7166): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7166): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/AndroidRuntime( 7166): FATAL EXCEPTION: main
E/AndroidRuntime( 7166): Process: com.android.documentsui, PID: 7166
E/AndroidRuntime( 7166): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7166): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 7166): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 7166): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 7166): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7166): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7166): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7166): 	,at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7166): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7166): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7166): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7166): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7166): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7166): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7166): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7166): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 7166): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 7166): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 7166): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 7166): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 7166): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 7166): 	... 9 more
I/Prism.ItemManager( 1622): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1622): loadItems() com.htc.launcher.pageview.WidgetManager@2052b4db +
I/Prism.WidgetManager( 1622): onLoadItems() +
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4,
I/ActivityManager(  942): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=7190 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  942): Start proc com.google.android.gms for service com.google.android.gms/.feedback.FeedbackService: pid=7205 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 1622): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  942): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=7229 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a
E/ActivityManager(  942): App crashed! Process: com.android.documentsui
D/ErrorReport(  942): HtcErrorReportManager Begin---add error logs to dropbox
,W/System.err(  942): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  942): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,W/System.err(  942): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  942): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  942): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  942): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  942): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  942): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  942): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  942): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  942): 	at libcore.io.Posix.open(Native Method)
W/System.err(  942): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err(  942): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  942): 	... 12 more
E/SQLiteDatabase( 7115): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 7115): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 7115): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 7115): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 7115): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 7115): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7115): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 7115): 	at com.htc.cs.util.model.BaseModel.handleFetch(Bas,eModel.java:197)
E/SQLiteDatabase( 7115): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 7115): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 7115): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 7115): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7115): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7115): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7115): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(  942): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  942): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  942): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  942): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  942): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  942): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  942): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  942): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  942): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  942): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  942): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  942): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  942): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  942): 	at libcore.io.Posix.open(Native Method)
W/System.err(  942): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  942): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  942): 	... 14 more
I/DeviceManagement( 7115): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 7115): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 7115): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
W/System.err(  942): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  942): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  942): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  942): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  942): 	at com.htc.server.report.error.ErrorR,eportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  942): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  942): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  942): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  942): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  942): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  942): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  942): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  942): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  942): 	at libcore.io.Posix.open(Native Method)
W/System.err(  942): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  942): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  942): 	... 14 more
E/SQLiteDatabase( 7115): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7115): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 7115): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 7115): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 7115): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 7115): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 7115): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 7115): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7115): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7115): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 7115): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@127eaaa7]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/DeviceManagement( 7115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
W/DeviceManagement( 7115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/DeviceManagement( 7115): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 7115): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 7115): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 7115): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 7115): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 7115): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 7115): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 7115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 7115): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 7115): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 7115): WorkflowService: Stopping workflow service
D/Process ( 7166): killProcess, pid=7166
I/ActivityManager(  942): Killing 6799:com.android.chrome/u0a96 (adj 15): empty #17
D/Process ( 7166): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/Process (  942): killProcessQuiet, pid=6799
W/ResourcesManager( 7190): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/ErrorReport(  942): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  942): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455009818481.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  942): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  942): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  942): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  942): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  942): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  942): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  942): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  942): 	... 4 more
W/ResourcesManager( 7205): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7205): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7205): VM with version 2.1.0 has multidex support
I/MultiDex( 7205): install
I/MultiDex( 7205): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  942): Recipient 6799
,W/ResourcesManager( 1622): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  942): Recipient 7166
,D/Process (  942): killProcessQuiet, pid=6692
I/ActivityManager(  942): Killing 6692:com.google.android.music:main/u0a159 (adj 15): empty #17
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,W/asset   ( 1622): Copying FileAsset 0x55a2ef3820 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1622): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1622): onLoadItems() -
I/Prism.ItemManager( 1622): loadItems() com.htc.launcher.pageview.WidgetManager@2052b4db -
,E/SQLiteLog( 1622): (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=75] disk I/O error
E/SQLiteDBG( 1622): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0x55a2906890
,E/AndroidRuntime( 1622): FATAL EXCEPTION: TaskWorker
E/AndroidRuntime( 1622): Process: com.htc.launcher, PID: 1622
E/AndroidRuntime( 1622): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1622): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1622): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1622): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1622): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1622): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1622): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1622): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 1622): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 1622): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1622): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1622): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1622): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1622): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  942): Recipient 6692
,D/MediaRouterService(  942): Client com.google.android.music (pid 6692): Died!

```
