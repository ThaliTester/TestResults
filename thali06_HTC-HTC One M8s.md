#### Test 58380500962e22b_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=201
E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2935] from screen [on:0 period:-1020533704] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1020533703] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1355): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.24 txretriesrate=0.00 rxrate=0.36 userTriggerdPenalty0
--------- beginning of system
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970):  good link -> stuck count =0
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -64, 3
,E/cutils-trace( 6270): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6270): ====startRecUseTime====
D/htc.customization.log.level( 6270):  is 
W/CustomizationLogLevel( 6270): Level value is invalid, use default level 2
D/CustomizationManager( 6270):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 6270): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6270): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6270): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6270): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6270): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6270): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6270): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6270): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6270): Parsing tag category name = system
I/CustomizationCIDLoader( 6270): Parsing tag category name = application
I/CustomizationCIDLoader( 6270): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6270): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6270): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6270): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6270): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6270): add string-array item, value = 42507
I/CustomizationCIDLoader( 6270): add string-array item, value = 21902
I/CustomizationCIDLoader( 6270): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6270): add string-array item, value = 23420
I/CustomizationCIDLoader( 6270): add string-array item, value = 22299
I/CustomizationCIDLoader( 6270): add string-array item, value = 24002
I/CustomizationCIDLoader( 6270): add string-array item, value = 23210
I/CustomizationCIDLoader( 6270): add string-array item, value = 23205
I/CustomizationCIDLoader( 6270): add string-array item, value = 23806
I/CustomizationCIDLoader( 6270): add string-array item, value = 23430
I/CustomizationCIDLoader( 6270): add string-array item, value = 23408
I/CustomizationCIDLoader( 6270): add string-array item, value = 27205
I/CustomizationCIDLoader( 6270): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6270): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6270):  Read CID file spent 0.098 (s)
D/CustomizationManager( 6270):  All configurations done spent 0.099 (s)
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=201
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6270 on display 0
D/PMS     (  970): acquireHCC(3f2c553a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
D/PMS     (  970): acquireHCC(cb425eb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
D/PMS     (  970): acquireWL(31fa8b06): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
I/FeedHostManager( 1491): [onPause]
I/FeedProviderManager( 1491): onPause
I/FeedHostManager( 1491): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@21544a9c
I/SocialFeedProvider( 1491): +onPause
I/SocialFeedProvider( 1491): -onPause
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  970): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6288 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=104 rxSum=95} preTxRxSum={txSum=104 rxSum=95}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/AnimationUtil(  970): isHTCRecent(ThaliTest/Recent screens.)/14
I/TrimMemoryManager( 1491): [trimMemory] 20
D/StatusBarManagerService(  970): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
I/WebViewFactory( 6288): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6288): Time to load native libraries: 9 ms (timestamps 7584-7593)
I/LibraryLoader( 6288): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6288): Binding Chromium to main looper Looper (main, tid 1) {2f4c138f}
I/LibraryLoader( 6288): Expected native library version number "",actual native library version number ""
I/chromium( 6288): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6288): Initializing chromium process, singleProcess=true
W/art     ( 6288): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6288): ApplicationContext is null in ApplicationStatus
W/chromium( 6288): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6288): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6288): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6288): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6288): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6288): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6288): Local Branch: 
I/Adreno-EGL( 6288): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6288): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6288):                  d74aa161a12b9c6fc6332151
W/System.err(  970): java.lang.Throwable: stack dump
W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27891eb7:true
D/BluetoothAdapter( 6288): 528505259: getState(). Returning 12
W/art     ( 6288): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6288): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6288): CordovaWebView is running on device made by: HTC
W/art     ( 6288): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6288): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6288): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6288): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6288): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@a7ff338, mServedView=org.apache.cordova.engine.SystemWebView{9e5cf11 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@34168876
I/InputMethodManagerService(  970): Disable input method client, pid=1491
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Enable input method client, pid=6288
I/ActivityManager(  970): Displayed com.test.thalitest/.MainActivity: +745ms
I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
D/PMS     (  970): releaseWL(31fa8b06): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/XT9_C   ( 1384): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1384): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1384): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1384): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6288): Cannot call determinedVisibility() - never saw a connection for the pid: 6288
D/JsMessageQueue( 6288): Set native->JS mode to OnlineEventsBridgeMode
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=201
,D/jxcore_app_log( 6288): JniHelper::setJavaVM(0xab0928f8), pthread_self() = -1405441552
,I/chromium( 6288): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=202
E/WifiTrafficPoller(  970): notifying of data activity 1
D/WIFI_ICON( 1217): WifiActivity: 1
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 6288): Initializing JXcore engine
W/jxcore-log( 6288): JXcore engine is ready
,D/PMS     (  970): releaseHCC(3f2c553a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
,D/PMS     (  970): releaseHCC(cb425eb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6288): Starting JXcore engine,
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
,E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1020530675] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1020530673] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1355): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.12 txretriesrate=0.00 rxrate=0.68 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
,E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -64, 3
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): handleMessage: X
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 6288): Platform android,
W/jxcore-log( 6288): 
W/jxcore-log( 6288): Process ARCH arm
W/jxcore-log( 6288): 
,I/HtcModeClient( 3488): handler message = 4011,
E/HtcModeClient( 3488): Check connection and retry 11 times.
,I/jxcore-log( 6288): JXcore Cordova bridge is ready!,
I/jxcore-log( 6288): 
W/jxcore-log( 6288): JXcore engine is started
,E/jxcore  ( 6288): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6288): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6288): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PMS     (  970): acquireWL(24e4e09f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
W/PluginManager( 6288): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 55ms. Plugin should use CordovaInterface.getThreadPool().
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1491): [onResume],
I/FeedProviderManager( 1491): onResume
I/SocialFeedProvider( 1491): +onResume
I/SocialFeedProvider( 1491): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1491): -onResume
,D/StatusBarManagerService(  970): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/FindExtension( 1491): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1491): Defer allocateBuffers to drawing time
,I/PhoneStatusBar( 1217): setImeWindowStatus(false,false),
I/InputMethodManagerService(  970): Disable input method client, pid=6288
,W/IInputConnectionWrapper( 6288): reportFullscreenMode on inactive InputConnection
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Enable input method client, pid=1491
,D/PMS     (  970): releaseWL(24e4e09f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
,D/Process (  970): killProcessQuiet, pid=5589,
,I/ActivityManager(  970): Killing 5589:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  970): Recipient 5589
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=202
E/WifiTrafficPoller(  970): notifying of data activity 0
,D/WIFI_ICON( 1217): WifiActivity: 0,
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/OpenGLRenderer( 1491): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=202
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=202
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=104 rxSum=95} preTxRxSum={txSum=104 rxSum=95}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1020527651] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1020527650] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1355): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.06 txretriesrate=0.00 rxrate=0.34 userTriggerdPenalty0
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970):  good link -> stuck count =0
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
,E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -64, 3
E/WifiStateMachine(  970): handleMessage: X
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=203
E/WifiTrafficPoller(  970): notifying of data activity 1
,D/WIFI_ICON( 1217): WifiActivity: 1
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=203
D/WIFI_ICON( 1217): WifiActivity: 0
E/WifiTrafficPoller(  970): notifying of data activity 0
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/art     (  970): Explicit concurrent mark sweep GC freed 36098(1932KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 18MB/28MB, paused 1.717ms total 178.677ms,
,I/HtcModeClient( 3488): handler message = 4011,
E/HtcModeClient( 3488): Check connection and retry 12 times.
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=203
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1020524629] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1020524628] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1355): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.03 txretriesrate=0.00 rxrate=1.17 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -64, 3
E/WifiStateMachine(  970): handleMessage: X
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=204
E/WifiTrafficPoller(  970): notifying of data activity 1
D/WIFI_ICON( 1217): WifiActivity: 1
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1217): WifiActivity: 0
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=204
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 0
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=104 rxSum=95} preTxRxSum={txSum=104 rxSum=95}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/PMS     (  970): acquireWL(2c350e6d): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
E/WifiStateMachine(  970): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,E/WifiStateMachine(  970): handleMessage: E msg.what=131143
V/AlarmManager(  970): sending alarm PendingIntent{fb54bae: PendingIntentRecord{23d46d4f android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454973390807, Int=20000
E/WifiStateMachine(  970): processMsg: ConnectedState
D/PMS     (  970): releaseWL(2c350e6d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  970):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:88 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=1.2 list=2412 [on:0 tx:0 rx:0 period:2074] from screen [on:0 period:-1020522535]
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:88 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=1.2 list=2412 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1020522533]
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.03 rxSuccessRate=1.17 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-64
,E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN with age=70901 interval=60000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN try full band scan age=70901 interval=60000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1355): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1355): wpa_supplicant_scan enter
D/wpa_supplicant( 1355): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1355): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1355): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 1355): WPS:  * Request Type
D/wpa_supplicant( 1355): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1355): WPS:  * UUID-E
D/wpa_supplicant( 1355): WPS:  * Primary Device Type
D/wpa_supplicant( 1355): WPS:  * RF Bands (3)
D/wpa_supplicant( 1355): WPS:  * Association State
D/wpa_supplicant( 1355): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1355): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1355): WPS:  * Manufacturer
D/wpa_supplicant( 1355): WPS:  * Model Name
,D/wpa_supplicant( 1355): WPS:  * Model Number
D/wpa_supplicant( 1355): WPS:  * Device Name
D/wpa_supplicant( 1355): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1355): P2P: * P2P IE header
D/wpa_supplicant( 1355): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1355): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1355): wlan0: Add radio work 'scan'@0x5589950860
D/wpa_supplicant( 1355): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1355): wlan0: Starting radio work 'scan'@0x5589950860 after 0.000044 second wait
D/wpa_supplicant( 1355): wlan0: nl80211: scan request
D/wpa_supplicant( 1355): Scan requested (ret=0) - scan timeout 30 seconds
,D/wpa_supplicant( 1355): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1355): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1355): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1355): wlan0: Own scan request started a scan in 0.000090 seconds
I/wpa_supplicant( 1355): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  970): [1,454,973,390,814 ms] noteScanstart no scan source
E/WifiStateMachine(  970): handleMessage: X
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=204
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:922] from screen [on:0 period:-1020521608] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1020521606] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1355): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.02 txretriesrate=0.00 rxrate=0.58 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
,E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): handleMessage: X
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -64, 3
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=204
,I/HtcModeClient( 3488): handler message = 4011,
E/HtcModeClient( 3488): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3488): Don't start project servcice
,D/HtcModeClient( 3488): setEject: MEDIA_EJECT_STATE = true,
,D/HtcModeClient( 3488): connectState: CONNECTION_READY = false
D/SilentMusic( 3488): call stop
,D/HtcModeClient( 3488): close connection
W/HtcModeClient( 3488): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3488): read the terminate packet, so break
I/ActivityManager(  970): Killing 3488:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=3488
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 3488
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=204
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=204
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1020518546] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1020518545] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1355): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.01 txretriesrate=0.00 rxrate=0.29 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -65, 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=121 Rx=204
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=104 rxSum=95} preTxRxSum={txSum=104 rxSum=95},
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  970): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6346 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  970): acquireWL(124a8aa2): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10076}
V/AlarmManager(  970): sending alarm PendingIntent{1b469333: PendingIntentRecord{2a5866f0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454973395931, Int=60000
,D/PMS     (  970): releaseWL(124a8aa2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6346): SMSBackupAgentService started,
D/SMSBackup( 6346): Checking restore status,
,D/SMSBackup( 6346): Restore complete
,D/SMSBackup( 6346): cancelCheckAlarm
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4,
D/PMS     (  970): acquireWL(23eaaeee): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  970): sending alarm PendingIntent{64d2f8f: PendingIntentRecord{af5021c android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=110607, Int=0
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/PMS     (  970): releaseWL(23eaaeee): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/SMSBackup( 6346): SMSBackupAgentService completed: completed in 0.0 seconds
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
,I/ActivityManager(  970): Killing 6091:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=6091
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6091,
D/WifiService(  970): Client connection lost with reason: 4
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1217): WifiActivity: 2
E/WifiTrafficPoller(  970):  packet count Tx=122 Rx=204
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,E/WifiTrafficPoller(  970): notifying of data activity 2
,D/wpa_supplicant( 1355): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1355): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1355): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1355): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1355): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1355): wlan0: Scan completed in 6.112830 seconds
D/wpa_supplicant( 1355): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1355): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1355): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1355): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1355): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-55
I/wpa_supplicant( 1355): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-65
,I/wpa_supplicant( 1355): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-82
W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/wpa_supplicant( 1355): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1355): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1355): BSS: last_scan_res_used=4/32,
D/wpa_supplicant( 1355): wlan0: Scan-only results received
D/wpa_supplicant( 1355): wlan0: Radio work 'scan'@0x5589950860 done in 6.113755 seconds
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState,
E/WifiStateMachine(  970):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0,
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1355): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  970): [1,454,973,396,932 ms] noteScanEnd no scan source
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1355): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@1a43b321 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  970): NG7005g c0:ff:d4:d3:aa:4a rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): NG700 c0:ff:d4:d3:aa:48 rssi=-65 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-65 freq=2412
E/WifiAutoJoinController (  970): Gonzos 38:f8:89:11:e9:11 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  970): UPC503894600 a0:c5:62:7a:49:97 rssi=-82 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 4 now 1454973396936
E/WifiAutoJoinController (  970): newSupplicantResults size=4 known=1 true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1355): wlan0: Control interface command 'STATUS-NO_EVENTS'
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
E/WifiAutoJoinController (  970): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-65,-127) num=(1,0)
E/WifiAutoJoinController (  970): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  970): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-65 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  970): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  970): Done attemptAutoJoin status=0
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  970): handleMessage: X
,D/WifiManager( 1850): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1217): WifiActivity: 0
E/WifiTrafficPoller(  970):  packet count Tx=122 Rx=204
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 0
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1020515528] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1020515527] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1355): environment dirty rate=0 [1][0][0]
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.50 txretriesrate=0.00 rxrate=0.15 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X,
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -64, 3
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  970):  packet count Tx=122 Rx=204
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=122 Rx=204
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=122 Rx=204
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=104 rxSum=95} preTxRxSum={txSum=104 rxSum=95}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1020512505] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1020512504] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SIGNAL_POLL',
,I/wpa_supplicant( 1355): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.25 txretriesrate=0.00 rxrate=0.07 userTriggerdPenalty0
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970):  good link -> stuck count =0
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -65, 3
,I/PMS     (  970): Going to sleep due to screen timeout (uid 1000)...,
D/ActivityManager(  970): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{e9e9e25 #7 A=.Prism U=0 sz=1}
W/PMS     (  970): mWirelessDisplayManager is null
W/PMS     (  970): mWirelessDisplayManager is still null
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1f8df7a9,
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/PMN     (  970): goingToSleep
W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
D/PMS     (  970): acquireWL(356cbfa): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 970 1000 null
W/SensorService(  970): pid=970, uid=1000
I/PMS     (  970): Sleeping (uid 1000)...
W/SensorService(  970): Active sensors: size = 4
D/XAN-DPS (  970): prepareColorFade 1
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/PMN     (  970): goingToSleep done
,W/SensorService(  970): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1f8df7a9, eanble = 0, strlen(mName) = 91
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  970): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@20c25e96
W/SensorService(  970): Listener[1] = com.htc.smartdim.sensor_eye@3a9c50dd
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  970): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6371 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,D/AlarmManager(  970): ACTION_SCREEN_ON
,I/FeedHostManager( 1491): [onPause]
I/FeedProviderManager( 1491): onPause
I/FeedHostManager( 1491): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@21544a9c
I/SocialFeedProvider( 1491): +onPause
I/SocialFeedProvider( 1491): -onPause
,W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/Adreno-EGL(  970): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  970): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  970): Build Date: 03/09/15 Mon
I/Adreno-EGL(  970): Local Branch: 
I/Adreno-EGL(  970): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  970): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  970):                  d74aa161a12b9c6fc6332151
,W/HtcLockScreen( 1217): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/AlarmManager(  970): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done recovering
I/AlarmManager(  970): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  970): releaseWL(356cbfa): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 11,
E/WifiTrafficPoller(  970):  packet count Tx=122 Rx=204
,E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=104 rxSum=95} preTxRxSum={txSum=104 rxSum=95},
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  970): handleMessage: E msg.what=131167
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1355): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1355): SET_SCREEN_ON:On
I/wpa_supplicant( 1355): htc_wext_set_keepalive +
I/wpa_supplicant( 1355): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1355): getPrivFuncNum +	
I/wpa_supplicant( 1355): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1355): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1355): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1355): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1355): htc_wext_set_TX_TRACKING - ret = 0
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
D/wpa_supplicant( 1355): wlan0: Control interface command 'SIGNAL_POLL'
V/SRS_Proc(  399): ParamSet string: screen_state=on
E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
I/wpa_supplicant( 1355): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  970): handleMessage: X
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
E/Wifi,StateMachine(  970):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1355): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1355): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=34 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): handleMessage: X
D/WifiController(  970): handleMessage: E msg.what=155650
D/NetworkPolicy(  970): updateScreenOn: false
D/WifiController(  970): processMsg: DeviceActiveState
V/NetworkPolicy(  970): updateIfacesLocked()
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/ResourcesManager( 6371): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1217): receive(android.intent.action.SCREEN_ON,1,false)
,I/CalendarProvider2( 6371): Created com.android.providers.calendar.CalendarAlarmManager@2f4c138f(com.htc.providers.calendar.HtcCalendarProvider@f4161c)
,D/CalendarProvider2( 6371): wait start:true
,D/PMS     (  970): acquireWL(310b2a4c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1850 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(b6c5a95): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1850 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(310b2a4c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(b6c5a95): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
D/XAN-DPS (  970): prepareColorFade done
D/XAN-DPS (  970): setBrightness to 0
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@20c25e96,
,I/DisplayManagerService(  970): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
V/ActivityManager(  970): Display changed displayId=0
W/SensorService(  970): disable: get sensor name = CM32181 Light sensor
D/AlarmManager(  970): ACTION_SCREEN_OFF,
D/CalendarProvider2( 6371): wait end:false
D/DotMatrix( 1313): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1313): [EventService] mbHDMIConnect: false, mCoverOn:false
W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@20c25e96, eanble = 0, strlen(mName) = 67,
I/AlarmManager(  970): [AlarmQueuing] screen off now: 
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
I/AlarmManager(  970): [AlarmQueuing] data connection: true
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@3a9c50dd
I/AlarmManager(  970): [AlarmQueuing] wifi connection: true
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  970): stopDataStallAlarm 
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  970): handleMessage: E msg.what=131167
E/WifiStateMachine(  970): processMsg: ConnectedState
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
E/WifiStateMachine(  970):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
V/SRS_Proc(  399): ParamSet string: screen_state=off
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
D/wpa_supplicant( 1355): wlan0: Control interface command 'SET_SCREEN_ON 0'
,I/wpa_supplicant( 1355): SET_SCREEN_ON:Off
I/wpa_supplicant( 1355): htc_wext_set_keepalive +
I/wpa_supplicant( 1355): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1355): getPrivFuncNum +	
I/wpa_supplicant( 1355): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1355): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1355): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1355): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1355): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  970): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/WifiController(  970): handleMessage: E msg.what=155651
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiStateMachine(  970): backgroundScan enabled=true startBackgroundScanIfNeeded:false
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
E/WifiStateMachine(  970): handleScreenStateChanged Exit: false
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: ConnectedState
D/WifiController(  970): handleMessage: X
E/WifiStateMachine(  970):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
,E/WifiStateMachine(  970): handleMessage: X
D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/NetworkPolicy(  970): updateScreenOn: false
V/NetworkPolicy(  970): updateIfacesLocked()
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/ActivityManager(  970): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6401 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/SensorManager( 1217): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@bbf2024, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  970): pid=1217, uid=10041
,W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@bbf2024, eanble = 1, strlen(mName) = 56
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@3a9c50dd
W/SensorService(  970): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@bbf2024
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1313): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1438): start background delete task...
,I/IntentController( 1217): receive(android.intent.action.SCREEN_OFF,1,false)
W/ContextImpl( 6401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/ContactMessageStore( 1438): size: 0 , 0
D/ContactMessageStore( 1438): Background delete complete
,W/ContextImpl( 6401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  970): acquireWL(3eab1476): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1850 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(3eab1476): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1857da77): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1850 10024 WorkSource{10024 com.google.android.gms}
D/PowerUsageList:PowerUsageHelper( 6401): MY_DEBUG = false
,D/PMS     (  970): releaseWL(1857da77): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/SmartSyncUtils( 6401): isEpsOn(), nState = 0,
,D/PMS     (  970): acquireWL(110276e4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6401 1000 null
,I/RemoteViews( 1217): setHTCTheme(com.htc.updater,true,33751145)
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
D/SmartDim(  970): Init customizeScreenOffDelayClass error
,I/RemoteViews( 1217): apply : com.htc.updater 1 13 1 36,
,E/SQLiteLog( 6401): (539) recovered 3 pages from /data/data/com.htc.htcpowermanager/databases/SmartSync.db-journal
,W/ContextImpl( 6401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
D/PMS     (  970): releaseWL(110276e4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 6401): isEpsOn(), nState = 0,
D/SmartSyncUtils( 6401): isEpsOn(), nState = 0
,W/ContextImpl( 6401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 13 num clients 6
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3a9c50dd,
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3a9c50dd, eanble = 0, strlen(mName) = 36
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@bbf2024
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = CM36686 Proximity sensor
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  970): Excessive delay in setPowerMode(): 296ms
D/PMS     (  970): Setting HAL interactive mode to false
D/PMS     (  970): Setting HAL interactive mode to false done
D/PMS     (  970): Setting HAL auto-suspend mode to true
D/PMS     (  970): Setting HAL auto-suspend mode done
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 2
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3a9c50dd, eanble = 0, strlen(mName) = 36
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@bbf2024
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/InputMethodManagerService(  970): screenObserver, isScreenOn=false
D/HABCtrl (  970): TPE algorithm. remove timeout.
D/PMS     (  970): OOBE c monitor 11
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Disable input method client, pid=1491
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3a9c50dd
,I/InputManager(  970): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
E/ActivityThread(  970): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3d1ff452 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3d1ff452 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  970): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  970): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  970): 	at android.app.Service.onStartCommand(Service.java:458)
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
I/IntentController( 1217): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  970): acquireWL(a65a713): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/NfcService( 1454): ScreenObserver: OFF
,D/NfcService( 1454): applyRouting - 0
,D/PMS     (  970): acquireWL(31e21d50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1454 1027 null
I/BatteryService(  970): n_update end
,D/NfcService( 1454): applyRouting -2
D/PMS     (  970): releaseWL(a65a713): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NfcService( 1454): applyRouting
D/NfcService( 1454): Ignore this applyRouting...
D/PMS     (  970): releaseWL(31e21d50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6435 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/HtcPowerSaver(  970): updateBatteryInfo
,D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  970): runPSCheck
D/HeadsetStateMachine( 3387): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): >> updateStatus
,D/UsbnetService(  970): onReceive BATTERY_CHANGED
,D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/ClockController( 1217): stop clock update:screen off
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,I/PowerUsageList:PowerUsageHelper( 6401): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6401): gen(), null == sipper.uidObj, userId = 0,
,I/ActivityManager(  970): Killing 5919:com.google.android.gm/u0a106 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=5919
D/PMS     (  970): releaseWL(23322b75): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6401): getMobilePolicyEnabled, result = true
,E/WifiTrafficPoller(  970): ADD_CLIENT: 7
D/WifiService(  970): New client listening to asynchronous messages
,I/ActivityManager(  970): Recipient 5919
,D/PowerUsageList:PowerUsageHelper( 6401): MY_DEBUG = false
,D/Process (  970): killProcessQuiet, pid=6011
I/ActivityManager(  970): Killing 6011:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 13 num clients 7
,I/ActivityManager(  970): Recipient 6011
,I/CalendarProvider2( 6371): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,W/ContentResolver( 6371): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/ActivityManager(  970): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6459 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  970): Killing 6132:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
,D/Process (  970): killProcessQuiet, pid=6132,
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  406): Explicit concurrent mark sweep GC freed 8688(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 355us total 38.390ms
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 292us total 25.936ms
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 288us total 19.606ms
I/ActivityManager(  970): Recipient 6132
,W/ResourcesManager( 6459): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6459): onCreate
,D/ProviderChangeReceiver( 6459): ---------------------------------------------------
,D/ProviderChangeReceiver( 6459): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  970): killProcessQuiet, pid=6157
I/ActivityManager(  970): Killing 6157:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 6459): start to updateAlertNotification!
,I/ActivityManager(  970): Recipient 6157
,D/HtcAlertService( 6459): No fired or scheduled alerts
,D/HtcAlertUtils( 6459): -- cancelReminderNotification --
,D/HtcAlertUtils( 6459): broadcastExistReminder!
,D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1020509482] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1020509481] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  970): handleMessage: X
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:278] from screen [on:0 period:-1020509203] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1020509201] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): handleMessage: X
,D/HtcUPManager( 1217): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 3
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 3,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Process (  970): killProcessQuiet, pid=5797
I/ActivityManager(  970): Killing 5797:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5797
,D/PMS     (  970): acquireWL(1e150b49): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{3bdc3c4e: PendingIntentRecord{979a16f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454973414310, Int=0
D/PMS     (  970): acquireWL(22d3be7c): PARTIAL_WAKE_LOCK  *backup* 0x1 970 1000 null,
D/PMS     (  970): releaseWL(1e150b49): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  970): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  970): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  970): releaseWL(22d3be7c): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  970): acquireWL(281a1305): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 970 1000 null
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604,
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
,D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  970): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  970): [reportHTCStatus] eventMask = 3 , status = 0
D/PMS     (  970): acquireWL(7adda81): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/GpsLocationProvider(  970): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  970): releaseWL(281a1305): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  970):  [handleDownloadXtraData]inject done.
D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  970): releaseWL(7adda81): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  970): acquireWL(3e5f8726): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{191b5e14: PendingIntentRecord{1ec956bd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=136740, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{173e4f67: PendingIntentRecord{32636114 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=148206, Int=0
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
D/PMS     (  970): releaseWL(3e5f8726): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/PMS     (  970): acquireWL(255c9dbd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(255c9dbd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3387): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1217): closing low battery warning: level=100
,D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1438): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  970): acquireWL(1dacefb2): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  970): sending alarm PendingIntent{64d2f8f: PendingIntentRecord{af5021c android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=192751, Int=0
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
V/AlarmManager(  970): sending alarm PendingIntent{191b5e14: PendingIntentRecord{1ec956bd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=196740, Int=0
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
V/AlarmManager(  970): sending alarm PendingIntent{29567b03: PendingIntentRecord{1a9f7a80 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=200436, Int=0
D/libc    (  970): [NET] android_getaddrinfo_proxy+
V/AlarmManager(  970): sending alarm PendingIntent{2c3a58b9: PendingIntentRecord{33f654fe com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191099, Int=0
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/PMS     (  970): acquireWL(283bc45f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1dacefb2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/PMS     (  970): acquireWL(17c1beac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms},
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  970): releaseWL(283bc45f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1940): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AlarmManager(  970): Ignore time set to 1454973484171 in setTime(); too close to current time 1454973483839,
,D/PMS     (  970): releaseWL(17c1beac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(152e05d6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(152e05d6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(23e3e057): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(23e3e057): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(10ab3744): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(655702d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(28dc2af3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(10ab3744): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1940): Vacuum at: now=1454973484047 tag=VacuumService,
,D/PMS     (  970): releaseWL(655702d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(1bc5e229): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1940): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1940): No account for auth token provided,
,D/PMS     (  970): releaseWL(1bc5e229): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(32dff9ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(32dff9ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1940): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1940): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1940): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1940): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1940): [NET] android_getaddrinfo_proxy+
D/libc    ( 1940): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1940): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1940): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1940): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1940): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1940): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1940): No account for auth token provided,
,W/Uploader( 1940): No account for auth token provided
,W/Uploader( 1940): No account for auth token provided
,W/Uploader( 1940):  no longer exists, so no auth token.,
,I/GLSUser ( 1940): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1940): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1940): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1940): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1940): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1940): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1940): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1940): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1940): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1940): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1940): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1940): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1940): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1940): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1940): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1940): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1940): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1940): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1217): reapply : com.google.android.gms 5 40
,D/PMS     (  970): releaseWL(28dc2af3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(35e5b6e3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(35e5b6e3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(71a38e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1940 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(71a38e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
D/HtcAppUPService( 1593): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@176e8d74
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
I/ActivityManager(  970): Killing 6181:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=6181
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6181
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  970): acquireWL(20bea799): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  970): n_update end
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): releaseWL(20bea799): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): updateBatteryInfo
,D/HeadsetStateMachine( 3387): Disconnected process message: 10, size: 0
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1355): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1355): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1355): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
,D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,D/PMS     (  970): acquireWL(1942a5e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(1942a5e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): updateBatteryInfo
D/HeadsetStateMachine( 3387): Disconnected process message: 10, size: 0
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  970): acquireWL(33b2de3f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{191b5e14: PendingIntentRecord{1ec956bd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=256740, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{3c92455: PendingIntentRecord{14748e6a com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454973628948, Int=0
,D/PMS     (  970): releaseWL(33b2de3f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/GLSActivity( 1940): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1940): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1940): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1940): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1940): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1940): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1940): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1940): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
,W/GLSActivity( 1940): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1940): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1940): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1940): 	,at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1940): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5518): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5518): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5518): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5518): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5518): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5518): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5518): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1217): reapply : com.google.android.gms 3 40,
,W/System  ( 5518): Ignoring header User-Agent because its value was null.,
,D/libc    ( 5518): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5518): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5518): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5518): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5518): [NET] android_getaddrinfo_proxy+
D/libc    ( 5518): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5518): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1438): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1438): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1438): sku_id=118
D/ContactMessageStore( 1438): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1438): start background delete task...
,D/ContactMessageStore( 1438): size: 0 , 0
,D/ContactMessageStore( 1438): Background delete complete
,D/PMS     (  970): acquireWL(3d2a473c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3d2a473c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
,D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3387): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(11cccc5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): releaseWL(11cccc5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
,D/PMS     (  970): runPSCheck
D/WifiController(  970): processMsg: DeviceActiveState
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: StaEnabledState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  970): handleMessage: X
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3387): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,I/bt-btm  ( 3387): Received oneshot timer event complete
D/PMS     (  970): acquireWL(2505661a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
I/bt-btm  ( 3387): btm_ble_timeout
V/AlarmManager(  970): sending alarm PendingIntent{191b5e14: PendingIntentRecord{1ec956bd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=376740, Int=0
I/bt-btm  ( 3387): btm_gen_resolvable_private_addr
V/AlarmManager(  970): sending alarm PendingIntent{3a84954b: PendingIntentRecord{12f29b28 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=945288, Int=0
D/PMS     (  970): acquireWL(25827041): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3387 1002 null
,D/bt-btm  ( 3387): btm_ble_rand_enc_complete,
I/bt-btm  ( 3387): btm_gen_resolve_paddr_low
D/bt-smp  ( 3387): smp_encrypt_data
W/bt-smp  ( 3387): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3387): Plain text(LSB ~ MSB) = a7 89 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3387): Encrypted text(LSB ~ MSB) = 22 5a c5 ea cb 52 37 36 e9 b4 73 67 55 ce 38 3a 
I/bt-btm  ( 3387): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3387): Stopping oneshot timer
D/bt-btm  ( 3387): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  970): releaseWL(2505661a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/PMS     (  970): releaseWL(25827041): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  970): acquireWL(a03c9e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024}
,V/AlarmManager(  970): sending alarm PendingIntent{39053b27: PendingIntentRecord{66a41d4 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454973754242, Int=1800000
,V/AlarmManager(  970): sending alarm PendingIntent{1944cf7d: PendingIntentRecord{31329e72 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936623, Int=0,
,V/AlarmManager(  970): sending alarm PendingIntent{2ff50a30: PendingIntentRecord{259026a9 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804911, Int=0
,D/PMS     (  970): acquireWL(1d0062c3): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4207 10024 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  970): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6496 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  970): sending alarm PendingIntent{1d13a740: PendingIntentRecord{39d3e679 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454974130460, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{efc681f: PendingIntentRecord{875a2af com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454974249897, Int=0
,D/PMS     (  970): acquireWL(302bf76c): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4207 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1d0062c3): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(31a37135): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1940 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(31a37135): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  970): releaseWL(a03c9e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6401): MY_DEBUG = false
,D/PowerUsageService( 6401): repeat time = 1454975149981
,I/EventLogService( 4207): Aggregate from 1454973324012 (log), 1454971954195 (data)
,D/PMS     (  970): releaseWL(302bf76c): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,E/cutils-trace( 6519): Error opening trace file: Permission denied (13),
I/dex2oat ( 6519): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6519): dex2oat: override thread count:4
I/PowerUsageList:PowerUsageHelper( 6401): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6401): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  970): acquireWL(e1d3c17): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1940 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1940): Message class com.google.f.a.a.i
,D/PMS     (  970): releaseWL(e1d3c17): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/dex2oat ( 6519): dex2oat took 929.017ms (threads: 4),
,I/PushClient( 6496): ApplicationMonitor {9a7bba1}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6496): ApplicationMonitor {9a7bba1}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6496): ApplicationMonitor {9a7bba1}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6496): ApplicationMonitor {9a7bba1}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6496): ApplicationMonitor {9a7bba1}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6496): ApplicationMonitor {9a7bba1}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6496): ApplicationMonitor {9a7bba1}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6496): ApplicationMonitor {9a7bba1}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6496): ApplicationMonitor {9a7bba1}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6496): PnsModel {a3a7808}: update(): Update registration caused by: alarm,
,I/PushClient( 6496): PnsConfigModel {371efe7f}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6496): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6496): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6496): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6496): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  970): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6527 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/art     (  970): Explicit concurrent mark sweep GC freed 45989(2MB) AllocSpace objects, 9(1920KB) LOS objects, 33% free, 18MB/28MB, paused 1.853ms total 212.953ms,
,I/DeviceManagement( 6527): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6527 dbg=false s=true,
,I/DeviceManagement( 6527): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6527): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6527): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6527): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6527): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@a3a7808] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6527): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6527): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6527): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6527): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6527): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6527): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6527): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6527): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@a3a7808],
,I/DeviceManagement( 6527): WorkflowService: Stopping workflow service,
,D/Process (  970): killProcessQuiet, pid=4621
I/ActivityManager(  970): Killing 4621:com.android.settings/1000 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4621,
,I/PushClient( 6496): PnsModel {a3a7808}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  970): killProcessQuiet, pid=5197
I/ActivityManager(  970): Killing 5197:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5197
,D/PMS     (  970): acquireWL(91e952b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{191b5e14: PendingIntentRecord{1ec956bd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=976740, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{3dbacd88: PendingIntentRecord{32592321 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454974301544, Int=0
D/SmartSyncUtils( 6401): isEpsOn(), nState = 0
,D/PMS     (  970): acquireWL(252e3346): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6401 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6401): [updateNmRange] bManual = false,
D/PMS     (  970): releaseWL(91e952b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 6401): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/WeatherUtility( 1217): Weather sync is On
D/SmartSyncScreenOnOffTimeReceiver( 6401): AlarmOnTime = -1
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 6401): SettingOnTime = 1454997600000, randomSettingOnTime = 1454995184000,
,D/SmartSyncScreenOnOffTimeReceiver( 6401): SettingOffTime = 1454976000000, randomSettingOffTime = 1454977838000
D/SmartSyncScreenOnOffTimeReceiver( 6401): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6401): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6401): bNightModeTurnOffOnce = false,
,D/PMS     (  970): releaseWL(252e3346): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  970): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
