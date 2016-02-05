#### Test 5838050069f842e_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=176 rxSum=157} preTxRxSum={txSum=176 rxSum=157}
D/WifiDataStallTracker(  937): updateDataStallInfo: NONE
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292738984] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292738983] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1322): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.52 txretriesrate=0.00 rxrate=1.68 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56
--------- beginning of system
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  937): handleMessage: X
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -58, 3
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=196 Rx=287
E/cutils-trace( 6555): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6555): ====startRecUseTime====
D/htc.customization.log.level( 6555):  is 
W/CustomizationLogLevel( 6555): Level value is invalid, use default level 2
D/CustomizationManager( 6555):  Read ACC file spent 0.045 (s)
D/CIDMapFileReader( 6555): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6555): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6555): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6555): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6555): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6555): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6555): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6555): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6555): Parsing tag category name = system
I/CustomizationCIDLoader( 6555): Parsing tag category name = application
I/CustomizationCIDLoader( 6555): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6555): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6555): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6555): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6555): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6555): add string-array item, value = 42507
I/CustomizationCIDLoader( 6555): add string-array item, value = 21902
I/CustomizationCIDLoader( 6555): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6555): add string-array item, value = 23420
I/CustomizationCIDLoader( 6555): add string-array item, value = 22299
I/CustomizationCIDLoader( 6555): add string-array item, value = 24002
I/CustomizationCIDLoader( 6555): add string-array item, value = 23210
I/CustomizationCIDLoader( 6555): add string-array item, value = 23205
I/CustomizationCIDLoader( 6555): add string-array item, value = 23806
I/CustomizationCIDLoader( 6555): add string-array item, value = 23430
I/CustomizationCIDLoader( 6555): add string-array item, value = 23408
I/CustomizationCIDLoader( 6555): add string-array item, value = 27205
I/CustomizationCIDLoader( 6555): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6555): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6555):  Read CID file spent 0.095 (s)
D/CustomizationManager( 6555):  All configurations done spent 0.095 (s)
I/ActivityManager(  937): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6555 on display 0
D/PMS     (  937): acquireHCC(14c5d659): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 937 1000 null
D/PMS     (  937): acquireHCC(161921e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 937 1000 null
D/PMS     (  937): acquireWL(20f47f15): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 937 1000 null
I/AnimationUtil(  937): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1615): [onPause]
I/FeedProviderManager( 1615): onPause
I/FeedHostManager( 1615): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2257a308
I/SocialFeedProvider( 1615): +onPause
I/SocialFeedProvider( 1615): -onPause
W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  937): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6573 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  937): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
I/TrimMemoryManager( 1615): [trimMemory] 20
,I/WebViewFactory( 6573): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6573): Time to load native libraries: 9 ms (timestamps 4951-4960)
I/LibraryLoader( 6573): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6573): Binding Chromium to main looper Looper (main, tid 1) {2b85855d}
I/LibraryLoader( 6573): Expected native library version number "",actual native library version number ""
I/chromium( 6573): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6573): Initializing chromium process, singleProcess=true
W/art     ( 6573): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6573): ApplicationContext is null in ApplicationStatus
W/chromium( 6573): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6573): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6573): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6573): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6573): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6573): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6573): Local Branch: 
I/Adreno-EGL( 6573): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6573): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6573):                  d74aa161a12b9c6fc6332151
W/System.err(  937): java.lang.Throwable: stack dump
D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  937): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ad1f9da:true
W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  937): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  937): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6573): 228203097: getState(). Returning 12
W/art     ( 6573): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6573): onDetachedFromWindow called when already detached. Ignoring
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=196 Rx=288
E/WifiTrafficPoller(  937): notifying of data activity 1
D/WIFI_ICON( 1219): WifiActivity: 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/SystemWebViewEngine( 6573): CordovaWebView is running on device made by: HTC
W/art     ( 6573): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6573): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6573): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6573): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6573): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1be2b2ce, mServedView=org.apache.cordova.engine.SystemWebView{b5515ef VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@25c358fc
I/ActivityManager(  937): Displayed com.test.thalitest/.MainActivity: +827ms
I/InputMethodManagerService(  937): Disable input method client, pid=1615
D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  937): Enable input method client, pid=6573
D/PMS     (  937): releaseWL(20f47f15): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
W/XT9_C   ( 1387): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1387): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1387): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1387): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6573): Cannot call determinedVisibility() - never saw a connection for the pid: 6573
,D/JsMessageQueue( 6573): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6573): JniHelper::setJavaVM(0xaac898f8), pthread_self() = -1409504304
I/chromium( 6573): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=196 Rx=288
E/WifiTrafficPoller(  937): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/HtcModeClient( 3227): handler message = 4011
E/HtcModeClient( 3227): Check connection and retry 11 times.
,D/PMS     (  937): releaseHCC(14c5d659): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  937): releaseHCC(161921e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
W/jxcore-log( 6573): Initializing JXcore engine
W/jxcore-log( 6573): JXcore engine is ready
,W/jxcore-log( 6573): Starting JXcore engine
,W/jxcore-log( 6573): Platform android
W/jxcore-log( 6573): 
W/jxcore-log( 6573): Process ARCH arm
W/jxcore-log( 6573): 
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155,
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292735961] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292735960] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1322): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.26 txretriesrate=0.00 rxrate=1.34 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -59, 3
E/WifiStateMachine(  937): handleMessage: X
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  937):  packet count Tx=196 Rx=288
,I/jxcore-log( 6573): JXcore Cordova bridge is ready!,
I/jxcore-log( 6573): 
,W/jxcore-log( 6573): JXcore engine is started
,E/jxcore  ( 6573): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6573): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6573): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/PMS     (  937): acquireWL(362943e2): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 937 1000 null,
W/PluginManager( 6573): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 50ms. Plugin should use CordovaInterface.getThreadPool().
,W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1615): [onResume]
I/FeedProviderManager( 1615): onResume
I/SocialFeedProvider( 1615): +onResume
I/SocialFeedProvider( 1615): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1615): -onResume
,D/StatusBarManagerService(  937): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
D/FindExtension( 1615): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1615): Defer allocateBuffers to drawing time
I/InputMethodManagerService(  937): Disable input method client, pid=6573
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  937): Enable input method client, pid=1615
,W/IInputConnectionWrapper( 6573): reportFullscreenMode on inactive InputConnection
,D/PMS     (  937): releaseWL(362943e2): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  937): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
,D/Process (  937): killProcessQuiet, pid=6271,
,I/ActivityManager(  937): Killing 6271:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  937): Recipient 6271,
,W/OpenGLRenderer( 1615): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,D/PMS     (  937): acquireWL(13c0f9e1): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{10072}
V/AlarmManager(  937): sending alarm PendingIntent{1a532306: PendingIntentRecord{26b5edc7 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454701173344, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{18d30ff4: PendingIntentRecord{2b72531d com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454701178490, Int=536832000
V/AlarmManager(  937): sending alarm PendingIntent{3170ddb0: PendingIntentRecord{16ba3429 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454701169517, Int=20000
,V/CheckinService( 4416): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) }),
,D/PMS     (  937): acquireWL(3a6e6992): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4416 10024 WorkSource{10024 com.google.android.gms},
,E/WifiStateMachine(  937): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
E/WifiStateMachine(  937): handleMessage: E msg.what=131143
D/PMS     (  937): releaseWL(13c0f9e1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  937): processMsg: ConnectedState
D/PMS     (  937): acquireWL(290b3760): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4416 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  937):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:82 rssi=-59 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.3 list=2412 [on:0 tx:0 rx:0 period:1114] from screen [on:0 period:-1292734828]
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):3 dur:82 rssi=-59 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.3 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292734827]
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.26 rxSuccessRate=1.34 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-59
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN with age=60478 interval=60000 maxinterval=300000,
,E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN try full band scan age=60478 interval=60000 maxinterval=300000
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN full=true
D/PMS     (  937): releaseWL(3a6e6992): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1322): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1322): wpa_supplicant_scan enter,
D/wpa_supplicant( 1322): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1322): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1322): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1322): WPS:  * Request Type
,D/wpa_supplicant( 1322): WPS:  * Config Methods (4288)
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
,D/wpa_supplicant( 1322): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1322): wlan0: Add radio work 'scan'@0x5594270860
D/wpa_supplicant( 1322): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1322): wlan0: Starting radio work 'scan'@0x5594270860 after 0.000046 second wait
D/wpa_supplicant( 1322): wlan0: nl80211: scan request
D/wpa_supplicant( 1322): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1322): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1322): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1322): wlan0: Own scan request started a scan in 0.000096 seconds
I/wpa_supplicant( 1322): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  937): [1,454,701,178,519 ms] noteScanstart no scan source
E/WifiStateMachine(  937): handleMessage: X
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  937): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  937): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/CheckinService( 4416): Checking schedule, now: 1454701178540 next: 1454701178490,
I/CheckinService( 4416): active receiver: enabled
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4416, uid=10024, userID:0
,I/CheckinService( 4416): Preparing to send checkin request
,I/EventLogService( 4416): Accumulating logs since 1454701142299
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  937):  packet count Tx=196 Rx=288
,I/CheckinRequestBuilder( 4416): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  937): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4416): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1799): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1799): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1799): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1799): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1799): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1323): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1323): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 1 40,
,W/CheckinRequestBuilder( 4416): awaiting user notification for token
,I/ActivityManager(  937): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6629 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 6629): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6629): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6629): VM with version 2.1.0 has multidex support
,I/MultiDex( 6629): install
I/MultiDex( 6629): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6629): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 6013): [607] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6013): [1] 5.onFinished: Installation state replication succeeded.
,W/ActivityThread( 6629): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6629): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2263b02e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6629): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1799): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1799): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4416): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,D/WearableService( 4926): callingUid 10024, callindPid: 4926,
,E/MDM     ( 1894): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4416, uid=10024, userID:0
,I/WVCdm   (  402): CdmEngine::OpenSession
I/WVCdm   (  402): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  402): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/LocationInitializer( 4416): Restart initialization of location
,D/DrmWidevineDash(  402): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  402): Service_Initialize: starts!
D/QSEECOMAPI: (  402): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  402): App is not loaded in QSEE
,E/QSEECOMAPI: (  402): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  402): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  402): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  402): App is not loaded in QSEE
,D/QSEECOMAPI: (  402): Loaded image: APP id = 8,
D/DrmWidevineDash(  402): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  402): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  402): qsapps_get_capabilities: returns 0
,D/DrmWidevineDash(  402): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4c50000
E/DrmWidevineDash(  402): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4c50000
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  539): got the req here! ret=0,
D/DrmLibTime(  539): command id, time_cmd_id = 770
D/DrmLibTime(  539): time_getutcsec starts!
D/DrmLibTime(  539): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  539): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  539): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  539): QSEE Time Listener: Checking if ATS_MODEM is set or not.,
E/QC-time-services(  539): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  539): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  539): QSEE Time Listener: Retrieved Android system time: 1454701179
D/DrmLibTime(  539): time_getutcsec returns 0, sec = 1454701179; nsec = 0
D/DrmLibTime(  539): time_getutcsec finished! 
D/DrmLibTime(  539): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  539): before calling ioctl to read the next time_cmd
E/QC-time-services(  472): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  402): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  402): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: starts! SID=0xf4d7c928
D/DrmWidevineDash(  402): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: starts! randomData=0xab2caf60, dataLength=8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab2db268, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  402): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  402): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  402): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  402): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: starts! deviceID=0xab301418, idLength=0xf4e7c6f8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4e7c70e, maximum = 0xf4e7c70f
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4e7c77c
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  402): PrepareKeyRequest: nonce=3160033412
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab3f75b8
D/DrmWidevineDash(  402): message_length=1611, signature=0xab2d8d50, signature_length=0xf4e7c6dc
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/WVCdm   (  402): CdmEngine::OpenSession,
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature returns 0
,D/DrmWidevineDash(  402): OEMCrypto_OpenSession: starts! SID=0xf4d7c928
D/DrmWidevineDash(  402): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_OpenSession SID = 2
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: starts! randomData=0xab2d5508, dataLength=8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/WVCdm   (  402): CdmEngine::CloseSession
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: starts! SID=2, wrapped_rsa_key=0xab2c88b0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  402): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  402): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  402): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  402): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: starts! deviceID=0xab301438, idLength=0xf4d7c6f8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: ends! returns 0
,D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4d7c70e, maximum = 0xf4d7c70f
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9,
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: starts! SID=2, nonce=0xf4d7c77c
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  402): PrepareKeyRequest: nonce=210876751
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature starts! SID=2, message=0xab2d8700
D/DrmWidevineDash(  402): message_length=1645, signature=0xab2e0628, signature_length=0xf4d7c6dc
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=176 rxSum=157} preTxRxSum={txSum=176 rxSum=157}
D/WifiDataStallTracker(  937): updateDataStallInfo: NONE
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  402): CdmEngine::CloseSession,
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: starts! SID=2
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  402): L3 Terminate.
D/DrmWidevineDash(  402): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): Service_Uninitialize: starts!,
D/QSEECOMAPI: (  402): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  402): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  402): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  402): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6661): Error opening trace file: Permission denied (13)
I/dex2oat ( 6661): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6661): dex2oat: override thread count:4
,I/dex2oat ( 6661): dex2oat took 40.606ms (threads: 4),
,I/Adreno-EGL( 6629): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6629): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6629): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6629): Local Branch: 
I/Adreno-EGL( 6629): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6629): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6629):                  d74aa161a12b9c6fc6332151
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  937):  packet count Tx=196 Rx=288
,I/Adreno-EGL( 6629): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6629): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6629): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6629): Local Branch: 
I/Adreno-EGL( 6629): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6629): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6629):                  d74aa161a12b9c6fc6332151
,I/CheckinRequestBuilder( 4416): Classify the device as Phone.
,I/art     (  937): Explicit concurrent mark sweep GC freed 23207(1173KB) AllocSpace objects, 5(164KB) LOS objects, 33% free, 18MB/28MB, paused 2.001ms total 162.689ms,
,D/libc    ( 4416): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4416): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4416): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4416): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4416): [NET] android_getaddrinfo_proxy+,
D/libc    ( 4416): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4416): [NET] android_getaddrinfo_proxy-, success,
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155,
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:1885] from screen [on:0 period:-1292732939] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292732938] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1219): WifiActivity: 2,
E/WifiTrafficPoller(  937):  packet count Tx=197 Rx=288
E/WifiTrafficPoller(  937): notifying of data activity 2,
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T],
,I/wpa_supplicant( 1322): environment dirty rate=0 [1][0][0]
D/wpa_supplicant( 1322): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1322): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1322): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1322): Got an original EVENT_SCAN_RESULTS
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/wpa_supplicant( 1322): wlan0: Scan completed in 2.106912 seconds
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/wpa_supplicant( 1322): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1322): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1322): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1322): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-53
I/wpa_supplicant( 1322): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1322): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1322): wlan0: BSS: Start scan result update 5
,D/wpa_supplicant( 1322): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1322): wlan0: Scan-only results received
D/wpa_supplicant( 1322): wlan0: Radio work 'scan'@0x5594270860 done in 2.107838 seconds
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  937): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.63 txretriesrate=0.00 rxrate=0.67 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -59, 3
E/WifiStateMachine(  937): handleMessage: X
,E/WifiStateMachine(  937): handleMessage: E msg.what=147461
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: DriverStartedState
E/WifiStateMachine(  937):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  937): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1322): wlan0: Control interface command 'LIST_DONGLES'
,W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  937): [1,454,701,180,642 ms] noteScanEnd no scan source
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1322): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  937): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@233b979e sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  937): NG7005g c0:ff:d4:d3:aa:4a rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  937): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  937): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  937): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  937):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  937): Gonzos 38:f8:89:11:e9:11 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  937): ageScanResultsOut delay 40000 size 3 now 1454701180644
E/WifiAutoJoinController (  937): newSupplicantResults size=3 known=1 true
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1322): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  937): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  937): ssid=NG700
E/WifiAutoJoinController (  937): id=0
E/WifiAutoJoinController (  937): mode=station
E/WifiAutoJoinController (  937): pairwise_cipher=CCMP
E/WifiAutoJoinController (  937): group_cipher=CCMP
E/WifiAutoJoinController (  937): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  937): wpa_state=COMPLETED
E/WifiAutoJoinController (  937): ip_address=192.168.1.130
E/WifiAutoJoinController (  937): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  937): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  937): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  937): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  937): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-59,-127) num=(1,0)
E/WifiAutoJoinController (  937): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  937): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-59 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  937): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  937): Done attemptAutoJoin status=0
E/WifiConfigStore(  937):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  937): handleMessage: X
,D/WifiManager( 1894): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,D/libc    ( 4416): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4416): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4416): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4416): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4416): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4416): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4416): Sending checkin request (8412 bytes),
,I/CheckinRequestBuilder( 4416): Checkin reason type: 11 attempt count: 1,
,I/ActivityManager(  937): Cannot resolve ContentProvider=com.google.android.wearable.settings,
E/ActivityThread( 4416): Failed to find provider info for com.google.android.wearable.settings,
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1219): WifiActivity: 3
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=302
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  937): notifying of data activity 3
,I/GLSUser ( 1799): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
,I/GLSUser ( 1799): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1799): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1799): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1799): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1799): Explicit concurrent mark sweep GC freed 9697(505KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.024ms total 55.839ms
,I/HtcModeClient( 3227): handler message = 4011
,E/HtcModeClient( 3227): Check connection and retry 12 times.
,W/CheckinRequestBuilder( 4416): awaiting user notification for token
D/DotMatrix( 1323): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1323): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,I/CheckinRequestBuilder( 4416): Classify the device as Phone.,
,I/CheckinTask( 4416): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4416): Checking schedule, now: 1454701181774 next: 1455238013768,
I/CheckinService( 4416): active receiver: disabled
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4416, uid=10024, userID:0
,D/PMS     (  937): releaseWL(290b3760): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  937): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6674 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/PhoneMonitor( 6674): Register our PhoneStateListener
,V/SetupWizard( 6674): Connected to Gservices successfully,
,D/ChimeraCfgMgr( 4416): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PhoneMonitor( 6674): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/Kids    ( 4416): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PhoneMonitor( 6674): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/GCM     ( 1799): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=302
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
E/WifiTrafficPoller(  937): notifying of data activity 0
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=302,
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155,
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1292729707] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292729706] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1322): environment dirty rate=5 [17][1][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.82 txretriesrate=0.00 rxrate=7.34 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  937):  isHighRSSI       ---> score=65
E/WifiStateMachine(  937): handleMessage: X
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -59, 3
,D/Process (  937): killProcessQuiet, pid=6055,
I/ActivityManager(  937): Killing 6055:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 6055
,D/Process (  937): killProcessQuiet, pid=6297
I/ActivityManager(  937): Killing 6297:com.htc.providers.settings:remote/u0a13 (adj 15): empty #18
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=194 rxSum=170} preTxRxSum={txSum=176 rxSum=157}
D/WifiDataStallTracker(  937): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  937): Recipient 6297
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=303
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  937): notifying of data activity 1
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=303
E/WifiTrafficPoller(  937): notifying of data activity 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=303
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155,
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.8, 0.0, 0.0  rx=7.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1292726684] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.8, 0.0, 0.0  rx=7.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292726683] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1322): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.41 txretriesrate=0.00 rxrate=4.17 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -59, 3
,D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  937): handleMessage: X
,I/HtcModeClient( 3227): handler message = 4011,
,E/HtcModeClient( 3227): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3227): Don't start project servcice
,D/HtcModeClient( 3227): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3227): connectState: CONNECTION_READY = false
D/SilentMusic( 3227): call stop
D/HtcModeClient( 3227): close connection
W/HtcModeClient( 3227): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3227): read the terminate packet, so break
,D/Process (  937): killProcessQuiet, pid=3227
I/ActivityManager(  937): Killing 3227:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 3227,
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=304
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  937): notifying of data activity 1
,I/ActivityManager(  937): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6700 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  937): acquireWL(187d9831): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{10076}
,V/AlarmManager(  937): sending alarm PendingIntent{18beeb16: PendingIntentRecord{1deefc97 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454701188021, Int=60000
D/PMS     (  937): releaseWL(187d9831): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6700): SMSBackupAgentService started
,D/SMSBackup( 6700): Checking restore status
,D/SMSBackup( 6700): Restore complete
,D/SMSBackup( 6700): cancelCheckAlarm
,D/SMSBackup( 6700): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  937): killProcessQuiet, pid=5405
I/ActivityManager(  937): Killing 5405:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 5405
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=304
,E/WifiTrafficPoller(  937): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  937): acquireWL(2462866d): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6448 10112 null
,I/Prism.ItemManager( 1615): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1615): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1615): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1775): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  937): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1775): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  937): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PMS     (  937): releaseWL(2462866d): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PhoneApp( 1553): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/[PluginManager]RegisterService( 1528): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1528): handle notify Blinkfeed plugin client changed
W/ResourcesManager( 6448): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6448): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AccTypeManager( 1775): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1775): Unsupported attribute readOnly
,D/PackageBroadcastService( 4416): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4416): Null package name or gms related package.  Ignoreing.
,D/PMS     (  937): acquireWL(34b7596f): PARTIAL_WAKE_LOCK  Icing 0x1 4416 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(2a2b167c): PARTIAL_WAKE_LOCK  AsyncService 0x1 6368 10167 null
D/PMS     (  937): releaseWL(2a2b167c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/Icing   ( 4416): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  937): acquireWL(3d86e75a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6368 10167 null
,D/PMS     (  937): releaseWL(3d86e75a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 6400): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  937): releaseWL(34b7596f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/UpdateIcingCorporaServi( 6400): UpdateCorporaTask done [took 57 ms] updated apps [took 57 ms] ,
W/PackageManager(  937): Unable to load service info ResolveInfo{2aa6b303 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  937): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  937): 	,at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  937): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  937): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  937): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  937): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  937): ,	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  937): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  937): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,V/GmsNetworkLocationProvi( 1894): DISABLE,
,I/GCoreNlp( 1894): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,D/LocationProviderProxy(  937): applying state to connected service
,D/PMS     (  937): acquireWL(e3f9da0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): releaseWL(e3f9da0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  937): applying state to connected service
,D/PMS     (  937): acquireWL(3cdd0d59): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(3cdd0d59): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(3005fd1e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(3005fd1e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=194 rxSum=170} preTxRxSum={txSum=194 rxSum=170}
D/WifiDataStallTracker(  937): updateDataStallInfo: NONE
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=304,
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
,E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1292723662] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292723661] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1322): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.20 txretriesrate=0.00 rxrate=2.58 userTriggerdPenalty0
,E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  937): handleMessage: X
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -59, 3
,I/Prism.ItemManager( 1615): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1615): loadItems() com.htc.launcher.pageview.WidgetManager@59f4f22 +
I/Prism.WidgetManager( 1615): onLoadItems() +
,W/ResourcesManager( 1615): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1615): Copying FileAsset 0x5578362300 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1615): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1615): onLoadItems() -
,I/Prism.ItemManager( 1615): loadItems() com.htc.launcher.pageview.WidgetManager@59f4f22 -
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=305
,E/WifiTrafficPoller(  937): notifying of data activity 1
D/WIFI_ICON( 1219): WifiActivity: 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PhoneApp( 1553): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1553): -- N1 =0
,D/PhoneApp( 1553): -- N2 =0
,D/PhoneApp( 1553): -- N3 =0,
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  937):  packet count Tx=214 Rx=305
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  937): notifying of data activity 0
,E/WifiStateMachine(  937): WiFiStateMachine SCAN ALARM,
D/PMS     (  937): acquireWL(28e019ff): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{1000}
,E/WifiStateMachine(  937): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
E/WifiStateMachine(  937): processMsg: ConnectedState
V/AlarmManager(  937): sending alarm PendingIntent{3170ddb0: PendingIntentRecord{16ba3429 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454701189517, Int=20000
E/WifiStateMachine(  937):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2123 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.6 fiv=90000 [on:0 tx:0 rx:0 period:2722] from screen [on:0 period:-1292720922]
V/AlarmManager(  937): sending alarm PendingIntent{990f3cc: PendingIntentRecord{18c82615 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=112051, Int=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:2123 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.6 fiv=90000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292720921]
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.20 rxSuccessRate=2.58 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-59
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN with age=13906 interval=90000 maxinterval=300000
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  937): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  937): has c0:ff:d4:d3:aa:48 freq=2412 age=2726 ?=true
E/WifiStateMachine(  937): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/PMS     (  937): releaseWL(28e019ff): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/wpa_supplicant( 1322): wlan0: Setting scan request: 0.000000 sec
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
D/wpa_supplicant( 1322): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1322): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1322): wlan0: Add radio work 'scan'@0x5594270860
D/wpa_supplicant( 1322): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1322): wlan0: Starting radio work 'scan'@0x5594270860 after 0.000039 second wait
D/wpa_supplicant( 1322): wlan0: nl80211: scan request
D/wpa_supplicant( 1322): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1322): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: Scan trigger
D/wpa_suppli,cant( 1322): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1322): wlan0: Own scan request started a scan in 0.000082 seconds
I/wpa_supplicant( 1322): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  937): [1,454,701,192,425 ms] noteScanstart no scan source
E/WifiStateMachine(  937): handleMessage: X
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  937): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  937): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/libc    (  937): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  937): [NET] android_getaddrinfofornet-, err=8
D/libc    (  937): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  937): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  937): [NET] android_getaddrinfo_proxy+
D/libc    (  937): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  937): [NET] android_getaddrinfo_proxy-, success
,D/wpa_supplicant( 1322): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1322): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1322): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1322): wlan0: Event SCAN_RESULTS (3) received
,I/wpa_supplicant( 1322): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1322): wlan0: Scan completed in 0.080231 seconds
D/wpa_supplicant( 1322): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1322): nl80211: Associated with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1322): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1322): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1322): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-53
I/wpa_supplicant( 1322): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1322): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1322): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1322): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1322): wlan0: Scan-only results received
D/wpa_supplicant( 1322): wlan0: Radio work 'scan'@0x5594270860 done in 0.081040 seconds
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  937): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  937): handleMessage: E msg.what=147461
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: DriverStartedState
E/WifiStateMachine(  937):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  937): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1322): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  937): [1,454,701,192,511 ms] noteScanEnd no scan source
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1322): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987',
E/WifiStateMachine(  937): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@233b979e sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  937): NG7005g c0:ff:d4:d3:aa:4a rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  937): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  937): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  937): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  937):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
,E/WifiAutoJoinController (  937): Gonzos 38:f8:89:11:e9:11 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  937): ageScanResultsOut delay 40000 size 3 now 1454701192513
E/WifiAutoJoinController (  937): newSupplicantResults size=3 known=1 true
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1322): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  937): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  937): ssid=NG700
E/WifiAutoJoinController (  937): id=0
E/WifiAutoJoinController (  937): mode=station
,E/WifiAutoJoinController (  937): pairwise_cipher=CCMP
E/WifiAutoJoinController (  937): group_cipher=CCMP
E/WifiAutoJoinController (  937): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  937): wpa_state=COMPLETED
E/WifiAutoJoinController (  937): ip_address=192.168.1.130
E/WifiAutoJoinController (  937): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  937): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  937): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  937): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  937): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-59,-127) num=(1,0)
E/WifiAutoJoinController (  937): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  937): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-59 freq=2412 Current: c0:ff:d4:d3:aa:48
,D/HtcWifiControlRoamOffload: (  937): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  937): Done attemptAutoJoin status=0
E/WifiConfigStore(  937):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  937): handleMessage: X
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  937):  packet count Tx=215 Rx=305
E/WifiTrafficPoller(  937): notifying of data activity 2
D/WIFI_ICON( 1219): WifiActivity: 2
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155,
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:276] from screen [on:0 period:-1292720643] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
,E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1292720641] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1322): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.60 txretriesrate=0.00 rxrate=1.79 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
,D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -59, 3
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  937): handleMessage: X
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,I/PMS     (  937): Going to sleep due to screen timeout (uid 1000)...
,I/SensorManager(  937): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1886bb0d
D/ActivityManager(  937): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{1210cd2a #7 A=.Prism U=0 sz=1}
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed
W/PMS     (  937): mWirelessDisplayManager is null
W/SensorService(  937): disable: get sensor name = Accelerometer Sensor
W/PMS     (  937): mWirelessDisplayManager is still null
,W/SensorService(  937): pid=937, uid=1000
W/PMN     (  937): goingToSleep
W/SensorService(  937): Active sensors: size = 4
W/SensorService(  937): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  937): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  937): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  937): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1886bb0d, eanble = 0, strlen(mName) = 91
W/SensorService(  937): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  937): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@217d958f
W/SensorService(  937): Listener[1] = com.htc.smartdim.sensor_eye@1c9532b
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/PMS     (  937): Sleeping (uid 1000)...
D/XAN-DPS (  937): prepareColorFade 1
,D/PMS     (  937): acquireWL(2826571b): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 937 1000 null
W/PMN     (  937): goingToSleep done
I/FeedHostManager( 1615): [onPause]
I/FeedProviderManager( 1615): onPause
,I/SocialFeedProvider( 1615): +onPause
I/SocialFeedProvider( 1615): -onPause
I/FeedHostManager( 1615): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2257a308
,I/Adreno-EGL(  937): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  937): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  937): Build Date: 03/09/15 Mon
I/Adreno-EGL(  937): Local Branch: 
I/Adreno-EGL(  937): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  937): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  937):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  937): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6737 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
D/AlarmManager(  937): ACTION_SCREEN_ON
W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  937): releaseWL(2826571b): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/AlarmManager(  937): [AlarmQueuing] recover blocked alarms,
I/AlarmManager(  937): [AlarmQueuing] done recovering
I/AlarmManager(  937): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  937): [AlarmQueuing] done EPS screen off alarm recovering
,W/HtcLockScreen( 1219): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,E/WifiTrafficPoller(  937): ENABLE_TRAFFIC_STATS_POLL true Token 11
,E/WifiTrafficPoller(  937):  packet count Tx=215 Rx=306
E/WifiTrafficPoller(  937): notifying of data activity 1,
,D/WIFI_ICON( 1219): WifiActivity: 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiDataStallTracker(  937): ENABLE_DATA_MONITOR_POLL true Token 1
,E/WifiStateMachine(  937): handleMessage: E msg.what=131167,
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
,E/WifiStateMachine(  937):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: DriverStartedState
E/WifiStateMachine(  937):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: DefaultState
E/WifiStateMachine(  937):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
,W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
,D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_SCREEN_ON 1'
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
I/wpa_supplicant( 1322): SET_SCREEN_ON:On
D/NetworkPolicy(  937): updateScreenOn: false
I/wpa_supplicant( 1322): htc_wext_set_keepalive +
V/NetworkPolicy(  937): updateIfacesLocked()
I/wpa_supplicant( 1322): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1322): getPrivFuncNum +	
I/wpa_supplicant( 1322): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1322): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1322): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1322): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1322): htc_wext_set_TX_TRACKING - ret = 0
D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=194 rxSum=170} preTxRxSum={txSum=194 rxSum=170}
D/WifiDataStallTracker(  937): updateDataStallInfo: NONE
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  937): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  937): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/NetworkManagementService(  937): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  937): handleScreenStateChanged Exit: true
E/WifiStateMachine(  937): handleMessage: X
V/SRS_Proc(  402): ParamSet string: screen_state=on
E/WifiStateMachine(  937): handleMessage: E msg.what=131154
E/WifiStateMachine(  937): processMsg: ConnectedState
E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  937):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiController(  937): handleMessage: E msg.what=155650
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
I/wpa_supplicant( 1322): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131127
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
,E/WifiStateMachine(  937):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131129
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
,W/ResourcesManager( 6737): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
,E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
,W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1322): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1322): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  937): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=33 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  937): handleMessage: X
,D/DotMatrix( 1323): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/GpsLocationProvider(  937): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/IntentController( 1219): receive(android.intent.action.SCREEN_ON,1,false)
,I/CalendarProvider2( 6737): Created com.android.providers.calendar.CalendarAlarmManager@fc6a334(com.htc.providers.calendar.HtcCalendarProvider@2b85855d),
,D/CalendarProvider2( 6737): wait start:true,
,D/PMS     (  937): acquireWL(1b1ee7fc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1894 10024 WorkSource{10024 com.google.android.gms},
,D/XAN-DPS (  937): prepareColorFade done,
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 12 num clients 6,
D/XAN-DPS (  937): setBrightness to 0
D/PMS     (  937): acquireWL(108ed4da): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(108ed4da): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(1b1ee7fc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/SensorManager(  937): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@217d958f,
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  937): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  937): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,W/SensorService(  937): pid=937, uid=1000
W/SensorService(  937): Active sensors: size = 3
W/SensorService(  937): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  937): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  937): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@217d958f, eanble = 0, strlen(mName) = 67
W/SensorService(  937): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  937): Listener[0] = com.htc.smartdim.sensor_eye@1c9532b
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
,V/ActivityManager(  937): Display changed displayId=0
D/DotMatrix( 1323): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1323): [EventService] mbHDMIConnect: false, mCoverOn:false
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/CalendarProvider2( 6737): wait end:false
,D/AlarmManager(  937): ACTION_SCREEN_OFF
,I/AlarmManager(  937): [AlarmQueuing] screen off now: 
I/AlarmManager(  937): [AlarmQueuing] data connection: true
I/AlarmManager(  937): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  937): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  937): stopDataStallAlarm 
,E/WifiDataStallTracker(  937): ENABLE_DATA_MONITOR_POLL false Token 2
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
E/WifiStateMachine(  937): handleMessage: E msg.what=131167
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: DriverStartedState
E/WifiStateMachine(  937):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: DefaultState
E/WifiStateMachine(  937):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1322): SET_SCREEN_ON:Off
I/wpa_supplicant( 1322): htc_wext_set_keepalive +
I/wpa_supplicant( 1322): htc_wext_set_keepalive: enable=1, type=2, interval=15
,D/wpa_supplicant( 1322): getPrivFuncNum +	
I/wpa_supplicant( 1322): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1322): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1322): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1322): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1322): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  937): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  937): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  937): handleScreenStateChanged Exit: false
E/WifiStateMachine(  937): handleMessage: X
,E/WifiStateMachine(  937): handleMessage: E msg.what=131154
E/WifiStateMachine(  937): processMsg: ConnectedState
V/SRS_Proc(  402): ParamSet string: screen_state=off
E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  937):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  937): handleMessage: X
D/WifiController(  937): handleMessage: E msg.what=155651
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,I/SensorManager( 1219): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@14355847, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,I/ActivityManager(  937): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6769 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  937): enable: get sensor name = hTC Gesture Motion HIDI
D/NetworkPolicy(  937): updateScreenOn: false
V/NetworkPolicy(  937): updateIfacesLocked()
,D/NetworkManagementService(  937): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/SensorService(  937): pid=1219, uid=10041,
W/SensorService(  937): Active sensors: size = 4
W/SensorService(  937): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  937): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  937): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  937): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@14355847, eanble = 1, strlen(mName) = 57
,W/SensorService(  937): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  937): Listener[0] = com.htc.smartdim.sensor_eye@1c9532b
W/SensorService(  937): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@14355847
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1323): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  937): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/ContactMessageStore( 1553): start background delete task...
,I/IntentController( 1219): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1553): size: 0 , 0
D/PMS     (  937): acquireWL(2ec2be01): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1553): Background delete complete
D/PMS     (  937): releaseWL(2ec2be01): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(349564a6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(349564a6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6769): MY_DEBUG = false
,D/SmartSyncUtils( 6769): isEpsOn(), nState = 0
,I/RemoteViews( 1219): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  937): acquireWL(2f9c393d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6769 1000 null
,I/RemoteViews( 1219): apply : com.htc.updater 1 14 1 36,
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl(  937): Excessive delay in setPowerMode(): 300ms
D/PMS     (  937): Setting HAL interactive mode to false
D/PMS     (  937): Setting HAL interactive mode to false done
W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  937): Setting HAL auto-suspend mode to true
D/PMS     (  937): Setting HAL auto-suspend mode done
D/PMS     (  937): releaseWL(2f9c393d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/HABCtrl (  937): TPE algorithm. remove timeout.
D/PMS     (  937): OOBE c monitor 11
I/InputManager(  937): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/InputMethodManagerService(  937): screenObserver, isScreenOn=false
D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
,I/IntentController( 1219): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  937): acquireWL(21232532): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/InputMethodManagerService(  937): Disable input method client, pid=1615
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(21232532): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  937): updateBatteryInfo
,D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1323): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1569): ScreenObserver: OFF
D/NotificationService(  937): plugged=true pluggin=true
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  937): Checking...
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  937): >> updateStatus
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  937): battery changed pluggedType: 2
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/PMS     (  937): acquireWL(7f84283): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1569 1027 null
D/WifiController(  937): handleMessage: E msg.what=155652
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/NfcService( 1569): applyRouting - 0
D/WifiController(  937): handleMessage: X
,D/NfcService( 1569): applyRouting -2
,D/NfcService( 1569): applyRouting
D/NfcService( 1569): Ignore this applyRouting...
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,D/PMS     (  937): releaseWL(7f84283): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  937): Init customizeScreenOffDelayClass error
,W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,I/ClockController( 1219): stop clock update:screen off
W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6769): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6769): isEpsOn(), nState = 0
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  937): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1c9532b
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  937): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  937): pid=937, uid=1000
W/SensorService(  937): Active sensors: size = 3
W/SensorService(  937): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  937): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  937): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1c9532b, eanble = 0, strlen(mName) = 35
W/SensorService(  937): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  937): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@14355847
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  937): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  937): pid=937, uid=1000
,W/SensorService(  937): Active sensors: size = 2
W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  937): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  937): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1c9532b, eanble = 0, strlen(mName) = 35
W/SensorService(  937): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  937): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@14355847
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  937): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1c9532b
,I/ActivityManager(  937): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6801 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,E/ActivityThread(  937): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1851b388 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  937): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1851b388 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  937): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  937): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  937): 	,at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  937): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  937): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  937): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  937): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  937): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  937): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  937): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
,E/ActivityThread(  937): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  937): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  937): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  937): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  937): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  937): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  417): Explicit concurrent mark sweep GC freed 8656(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 230us total 29.623ms,
,I/art     (  417): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 189us total 27.212ms
,I/art     (  417): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 167us total 23.799ms
,I/PowerUsageList:PowerUsageHelper( 6769): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/SmartSyncUtils( 6769): getMobilePolicyEnabled, result = true
,D/Process (  937): killProcessQuiet, pid=6326
I/ActivityManager(  937): Killing 6326:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/WifiService(  937): New client listening to asynchronous messages
,E/WifiTrafficPoller(  937): ADD_CLIENT: 7
,D/PowerUsageList:BatterySipperExt( 6769): gen(), null == sipper.uidObj, userId = 0
,I/ActivityManager(  937): Recipient 6326
,D/PowerUsageList:PowerUsageHelper( 6769): MY_DEBUG = false,
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL false Token 3,
,I/ActivityManager(  937): Killing 5845:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  937): killProcessQuiet, pid=5845
,D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,D/PMS     (  937): releaseWL(10538883): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/ActivityManager(  937): Recipient 5845
,I/CalendarProvider2( 6737): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6737): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 6423): ---------------------------------------------------,
D/ProviderChangeReceiver( 6423): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!,
,D/HtcAlertService( 6423): start to updateAlertNotification!
,D/Process (  937): killProcessQuiet, pid=6481
I/ActivityManager(  937): Killing 6481:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 6481
,D/HtcAlertService( 6423): No fired or scheduled alerts
D/HtcAlertUtils( 6423): -- cancelReminderNotification --
D/HtcAlertUtils( 6423): broadcastExistReminder!,
,D/DotMatrix( 1323): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292717631] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
,E/WifiStateMachine(  937):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1292717629] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  937): handleMessage: X
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
,E/WifiStateMachine(  937):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:811] from screen [on:0 period:-1292716816] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1292716814] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): handleMessage: X
,D/HtcUPManager( 1219): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL false Token 3
,D/ContactMessageStore( 1553): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1553): MSG_NOTIFY_CS_TO_SYNC <<,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/ActivityManager(  937): Killing 5596:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  937): killProcessQuiet, pid=5596
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 5596,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  937): acquireWL(145a627e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
,D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  937): n_update end
D/DotMatrix( 1323): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  937): releaseWL(145a627e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/NotificationService(  937): plugged=true pluggin=true
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  937): Checking...
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  937): >> updateStatus
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): handleMessage: E msg.what=155652
D/PowerUI ( 1219): closing low battery warning: level=100
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  937): acquireWL(1ff283df): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 937 1000 WorkSource{1000}
V/AlarmManager(  937): sending alarm PendingIntent{27e6b393: PendingIntentRecord{3ea36fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=119632, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{1bea482c: PendingIntentRecord{2c652f5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143491, Int=0
,D/PMS     (  937): releaseWL(1ff283df): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1219): Weather sync is On,
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  937): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  937): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  937): acquireWL(3a36288a): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 937 1000 null
,D/libc    (  937): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  937): [NET] android_getaddrinfofornet-, err=8
D/libc    (  937): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  937): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  937): [NET] android_getaddrinfo_proxy+
D/libc    (  937): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  937): [NET] android_getaddrinfo_proxy-, success
D/libc    (  937): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  937): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  937): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  937): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  937): acquireWL(11564356): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 937 1000 null
D/GpsLocationProvider(  937): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  937): releaseWL(3a36288a): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  937):  [handleDownloadXtraData]inject done.
D/GpsLocationProvider(  937): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
D/PMS     (  937): releaseWL(11564356): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/art     (  937): Explicit concurrent mark sweep GC freed 45781(2MB) AllocSpace objects, 6(1132KB) LOS objects, 33% free, 18MB/28MB, paused 1.978ms total 212.717ms,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/TelephonyReceiver( 1553): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  937): acquireWL(14c30fd7): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{1000},
V/AlarmManager(  937): sending alarm PendingIntent{1d2b70c4: PendingIntentRecord{2372ebad android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454701248870, Int=0
,V/AlarmManager(  937): sending alarm PendingIntent{27e6b393: PendingIntentRecord{3ea36fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=179632, Int=0
D/PMS     (  937): acquireWL(108b3ee2): PARTIAL_WAKE_LOCK  *backup* 0x1 937 1000 null
,V/AlarmManager(  937): sending alarm PendingIntent{990f3cc: PendingIntentRecord{18c82615 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=192061, Int=0
,V/AlarmManager(  937): sending alarm PendingIntent{3d3ed273: PendingIntentRecord{2fd0d530 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=198621, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{fff95a9: PendingIntentRecord{1922672e com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190186, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{2aaa22cf: PendingIntentRecord{3c26145c com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454701288405, Int=1800000
,D/libc    (  937): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
W/BackupManagerService(  937): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
D/libc    (  937): [NET] android_getaddrinfofornet-, err=8
D/libc    (  937): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
E/BackupManagerService(  937): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/libc    (  937): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  937): [NET] android_getaddrinfo_proxy+
D/PMS     (  937): releaseWL(108b3ee2): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/libc    (  937): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/PMS     (  937): acquireWL(1192e365): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(1f1c83a): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4416 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/PMS     (  937): releaseWL(14c30fd7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/PMS     (  937): acquireWL(3b2e1a48): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4416 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  937): releaseWL(1f1c83a): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  937): [NET] android_getaddrinfo_proxy-, success
D/PMS     (  937): acquireWL(1a5350e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/AlarmManager(  937): Ignore time set to 1454701288134 in setTime(); too close to current time 1454701288494,
D/PMS     (  937): releaseWL(1192e365): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4416): Aggregate from 1454701178578 (log), 1454699488361 (data),
,V/GLSActivity( 1799): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  937): releaseWL(1a5350e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): acquireWL(120cf7de): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): releaseWL(120cf7de): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(36bf5dbf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(36bf5dbf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(1ec54c8c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(3b2e1a48): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(379c6fd5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): acquireWL(2d1616db): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(1ec54c8c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1799): Vacuum at: now=1454701288672 tag=VacuumService
,D/PMS     (  937): releaseWL(379c6fd5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): acquireWL(8413451): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms},
I/GoogleURLConnFactory( 1799): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1799): No account for auth token provided
,D/PMS     (  937): releaseWL(8413451): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(295a24b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(295a24b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1799): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1799): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1799): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1799): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1799): [NET] android_getaddrinfo_proxy+
D/libc    ( 1799): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1799): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1799): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1799): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1799): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1799): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1799): No account for auth token provided
,W/Uploader( 1799): No account for auth token provided,
,W/Uploader( 1799):  no longer exists, so no auth token.,
,W/Uploader( 1799): No account for auth token provided,
,I/GLSUser ( 1799): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1799): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1799): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1799): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1799): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1323): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1323): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40,
E/Uploader( 1799): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1799): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1799): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1799): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1799): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1799): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1799): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1799): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1799): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1799): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1799): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1799): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1799): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1799): No account for auth token provided,
,D/PMS     (  937): releaseWL(2d1616db): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  937): acquireWL(2f866ccb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(2f866ccb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  937): acquireWL(21645ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(21645ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1528): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@26f8b2bf
,D/Process (  937): killProcessQuiet, pid=5506,
I/ActivityManager(  937): Killing 5506:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 5506
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  937): acquireWL(1de6d3c1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null,
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(1de6d3c1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  937): updateBatteryInfo
,D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/NotificationService(  937): plugged=true pluggin=true
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  937): runPSCheck
D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  937): Checking...
D/DotMatrix( 1323): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  937): >> updateStatus
D/UsbnetService(  937): onReceive BATTERY_CHANGED,
D/WifiController(  937): battery changed pluggedType: 2
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  937): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  937): handleMessage: E msg.what=155652
I/HtcPowerSaver(  937): << updateStatus
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1322): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1322): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  937): acquireWL(18132766): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 937 1000 WorkSource{1000}
V/AlarmManager(  937): sending alarm PendingIntent{27e6b393: PendingIntentRecord{3ea36fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=239632, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{33f69b54: PendingIntentRecord{3a4beafd com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454701422063, Int=0
,D/PMS     (  937): releaseWL(18132766): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1799): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1799): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1799): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1799): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1799): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1799): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1799): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1799): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1799): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1799): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1799): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1799): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1799): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1323): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1323): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 6013): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6013): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6013): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6013): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6013): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6013): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6013): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,W/System  ( 6013): Ignoring header User-Agent because its value was null.,
,D/libc    ( 6013): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6013): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6013): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6013): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6013): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6013): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6013): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  937): acquireWL(977eb97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null,
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(977eb97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/NotificationService(  937): plugged=true pluggin=true
,D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  937): Checking...
D/WifiController(  937): handleMessage: E msg.what=155652
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): processMsg: DeviceActiveState
,D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: StaEnabledState
D/PowerUI ( 1219): closing low battery warning: level=100
D/WifiController(  937): processMsg: DefaultState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  937): handleMessage: X
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  937): << updateStatus
D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1323): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  937): acquireWL(1fa18184): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null,
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(1fa18184): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  937): plugged=true pluggin=true,
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  937): Checking...
D/WifiController(  937): processMsg: DeviceActiveState
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): processMsg: StaEnabledState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1323): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  937): acquireWL(1d528d6d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(1d528d6d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  937): updateBatteryInfo
D/PMS     (  937): runPSCheck
D/HtcPowerSaver(  937): Checking...
I/HtcPowerSaver(  937): >> updateStatus
,I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1219): closing low battery warning: level=100
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1323): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1323): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  937): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  937): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  937): << updateStatus
,D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1553): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1553): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1553): sku_id=118
D/ContactMessageStore( 1553): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1553): start background delete task...
,D/ContactMessageStore( 1553): size: 0 , 0
D/ContactMessageStore( 1553): Background delete complete
,D/PMS     (  937): acquireWL(328b9da2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 937 1000 WorkSource{1000}
V/AlarmManager(  937): sending alarm PendingIntent{27e6b393: PendingIntentRecord{3ea36fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=359632, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{1cc5aa33: PendingIntentRecord{107731f0 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941497, Int=0,
I/bt-btm  ( 3102): Received oneshot timer event complete
I/bt-btm  ( 3102): btm_ble_timeout
I/bt-btm  ( 3102): btm_gen_resolvable_private_addr
,D/PMS     (  937): acquireWL(23979369): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3102 1002 null,
,D/bt-btm  ( 3102): btm_ble_rand_enc_complete,
I/bt-btm  ( 3102): btm_gen_resolve_paddr_low
D/bt-smp  ( 3102): smp_encrypt_data
W/bt-smp  ( 3102): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3102): Plain text(LSB ~ MSB) = 7b 44 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3102): Encrypted text(LSB ~ MSB) = 35 26 95 0f 7e 44 40 04 9c a9 59 cb b5 7a 0a 57 
I/bt-btm  ( 3102): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3102): Stopping oneshot timer
D/bt-btm  ( 3102): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  937): releaseWL(328b9da2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On,
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data,
,D/PMS     (  937): releaseWL(23979369): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  937): acquireWL(2a9f1ee): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{1000}
V/AlarmManager(  937): sending alarm PendingIntent{373217a3: PendingIntentRecord{2e99eaa0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805828, Int=0,
V/AlarmManager(  937): sending alarm PendingIntent{27e6b393: PendingIntentRecord{3ea36fd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=959632, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{3626b68f: PendingIntentRecord{1bb57d1c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937626, Int=0
,D/PMS     (  937): acquireWL(380cfd25): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1799 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): releaseWL(380cfd25): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  937): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6845 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  937): sending alarm PendingIntent{2473efa: PendingIntentRecord{1ce22cab com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454701790945, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{2d2b4f08: PendingIntentRecord{36b77942 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454702047269, Int=0
,D/PMS     (  937): acquireWL(15b546a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6769): MY_DEBUG = false
,D/PMS     (  937): releaseWL(2a9f1ee): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/PowerUsageService( 6769): repeat time = 1454702947329
,D/PMS     (  937): acquireWL(1caa53b4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(15b546a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 6769): PowerProfile::POWER_SCREEN_FULL = 154.8
,E/cutils-trace( 6869): Error opening trace file: Permission denied (13)
I/dex2oat ( 6869): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6869): dex2oat: override thread count:4
D/PowerUsageList:BatterySipperExt( 6769): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  937): releaseWL(1caa53b4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  937): acquireWL(2bfab352): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(2bfab352): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): acquireWL(1fcd8623): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(1fcd8623): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(b72f720): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1799): Message class com.google.f.a.a.i
,D/PMS     (  937): releaseWL(b72f720): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/dex2oat ( 6869): dex2oat took 1.005s (threads: 4),
,I/PushClient( 6845): ApplicationMonitor {3a3c6eff}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6845): ApplicationMonitor {3a3c6eff}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6845): ApplicationMonitor {3a3c6eff}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6845): ApplicationMonitor {3a3c6eff}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6845): ApplicationMonitor {3a3c6eff}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6845): ApplicationMonitor {3a3c6eff}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6845): ApplicationMonitor {3a3c6eff}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6845): ApplicationMonitor {3a3c6eff}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6845): ApplicationMonitor {3a3c6eff}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6845): PnsModel {387a861e}: update(): Update registration caused by: alarm
,I/PushClient( 6845): PnsConfigModel {30d77fcd}: <init>(): Use dm-client for provisioning.
,W/System.err( 6845): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6845): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6845): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6845): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  937): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6876 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6876): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6876 dbg=false s=true
,I/DeviceManagement( 6876): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6876): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6876): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6876): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6876): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@d9a1a59] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6876): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6876): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6876): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6876): SessionStateController: Checking invariants...
,I/DeviceManagement( 6876): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6876): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6876): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6876): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@d9a1a59],
,I/DeviceManagement( 6876): WorkflowService: Stopping workflow service
,D/Process (  937): killProcessQuiet, pid=6573,
I/ActivityManager(  937): Killing 6573:com.test.thalitest/u0a366 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 6573,
E/InputEventReceiver( 1387): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{d7b2818 uid 10366 pid 6573} (c)'
,I/PushClient( 6845): PnsModel {387a861e}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  937): killProcessQuiet, pid=6674
I/ActivityManager(  937): Killing 6674:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 6674
,D/PMS     (  937): acquireWL(246411e4): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{1000}
V/AlarmManager(  937): sending alarm PendingIntent{3667464d: PendingIntentRecord{df29502 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454702094007, Int=0
,D/SmartSyncUtils( 6769): isEpsOn(), nState = 0
,D/PMS     (  937): releaseWL(246411e4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  937): acquireWL(1b3c3e13): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6769 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6769): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6769): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6769): AlarmOnTime = -1,
,D/SmartSyncScreenOnOffTimeReceiver( 6769): SettingOnTime = 1454738400000, randomSettingOnTime = 1454736959000
,D/SmartSyncScreenOnOffTimeReceiver( 6769): SettingOffTime = 1454716800000, randomSettingOffTime = 1454721957000
,D/SmartSyncScreenOnOffTimeReceiver( 6769): bDayMode = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6769): bNightMode = true,
D/SmartSyncScreenOnOffTimeReceiver( 6769): bNightModeTurnOffOnce = false
,D/PMS     (  937): releaseWL(1b3c3e13): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  937): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
