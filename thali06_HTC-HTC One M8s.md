#### Test 583805003a0697c_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=133
,E/cutils-trace( 6570): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6570): ====startRecUseTime====
D/htc.customization.log.level( 6570):  is 
W/CustomizationLogLevel( 6570): Level value is invalid, use default level 2
D/CustomizationManager( 6570):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 6570): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6570): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6570): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6570): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6570): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6570): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6570): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6570): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6570): Parsing tag category name = system
I/CustomizationCIDLoader( 6570): Parsing tag category name = application
I/CustomizationCIDLoader( 6570): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6570): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6570): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6570): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6570): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6570): add string-array item, value = 42507
I/CustomizationCIDLoader( 6570): add string-array item, value = 21902
I/CustomizationCIDLoader( 6570): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6570): add string-array item, value = 23420
I/CustomizationCIDLoader( 6570): add string-array item, value = 22299
I/CustomizationCIDLoader( 6570): add string-array item, value = 24002
I/CustomizationCIDLoader( 6570): add string-array item, value = 23210
I/CustomizationCIDLoader( 6570): add string-array item, value = 23205
I/CustomizationCIDLoader( 6570): add string-array item, value = 23806
I/CustomizationCIDLoader( 6570): add string-array item, value = 23430
I/CustomizationCIDLoader( 6570): add string-array item, value = 23408
I/CustomizationCIDLoader( 6570): add string-array item, value = 27205
I/CustomizationCIDLoader( 6570): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6570): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6570):  Read CID file spent 0.098 (s)
D/CustomizationManager( 6570):  All configurations done spent 0.098 (s)
E/WifiStateMachine(  970): handleMessage: E msg.what=131155
--------- beginning of system
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6570 on display 0
E/WifiStateMachine(  970): processMsg: ConnectedState
D/PMS     (  970): acquireHCC(f23b85e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-937734204] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/PMS     (  970): acquireHCC(b16543f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-937734203] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SIGNAL_POLL'
W/asset   (  970): Copying FileAsset 0x559fbb7a90 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  970): acquireWL(66efc6a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
I/wpa_supplicant( 1367): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.25 txretriesrate=0.00 rxrate=2.45 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
I/AnimationUtil(  970): isHTCRecent(ThaliTest/Recent screens.)/0
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -64, 3
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/FeedHostManager( 1494): [onPause]
I/FeedProviderManager( 1494): onPause
I/FeedHostManager( 1494): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@200a400f
I/SocialFeedProvider( 1494): +onPause
I/SocialFeedProvider( 1494): -onPause
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  970): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6588 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  970): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
W/asset   ( 6588): Copying FileAsset 0xac0a6428 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1494): [trimMemory] 20
,I/WebViewFactory( 6588): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6588): Time to load native libraries: 9 ms (timestamps 3510-3519)
I/LibraryLoader( 6588): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6588): Binding Chromium to main looper Looper (main, tid 1) {f98b0ee}
I/LibraryLoader( 6588): Expected native library version number "",actual native library version number ""
I/chromium( 6588): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=133
I/BrowserStartupController( 6588): Initializing chromium process, singleProcess=true
W/art     ( 6588): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6588): ApplicationContext is null in ApplicationStatus
W/chromium( 6588): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6588): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6588): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6588): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6588): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6588): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6588): Local Branch: 
I/Adreno-EGL( 6588): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6588): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6588):                  d74aa161a12b9c6fc6332151
W/System.err(  970): java.lang.Throwable: stack dump
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@198aeb4b:true
W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6588): 914206635: getState(). Returning 12
W/art     ( 6588): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6588): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6588): CordovaWebView is running on device made by: HTC
W/art     ( 6588): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6588): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6588): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6588): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6588): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1cadd99b, mServedView=org.apache.cordova.engine.SystemWebView{17351138 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@16279511
I/InputMethodManagerService(  970): Disable input method client, pid=1494
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Enable input method client, pid=6588
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
D/PMS     (  970): releaseWL(66efc6a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  970): Displayed com.test.thalitest/.MainActivity: +818ms
W/XT9_C   ( 1382): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1382): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1382): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1382): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6588): Cannot call determinedVisibility() - never saw a connection for the pid: 6588
D/JsMessageQueue( 6588): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6588): JniHelper::setJavaVM(0xaaf3b8f8), pthread_self() = -1406860168
I/chromium( 6588): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=133
I/HtcModeClient( 3173): handler message = 4011
E/HtcModeClient( 3173): Check connection and retry 11 times.
,D/PMS     (  970): releaseHCC(f23b85e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  970): releaseHCC(b16543f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6588): Initializing JXcore engine
W/jxcore-log( 6588): JXcore engine is ready
,W/jxcore-log( 6588): Starting JXcore engine
,W/jxcore-log( 6588): Platform android
W/jxcore-log( 6588): 
W/jxcore-log( 6588): Process ARCH arm
W/jxcore-log( 6588): 
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=109 rxSum=115} preTxRxSum={txSum=109 rxSum=115}
,D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1215): WifiActivity: 1
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=134
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 1
,I/jxcore-log( 6588): JXcore Cordova bridge is ready!
I/jxcore-log( 6588): 
W/jxcore-log( 6588): JXcore engine is started
,E/jxcore  ( 6588): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6588): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6588): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PMS     (  970): acquireWL(3c5c18b3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
,W/PluginManager( 6588): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 51ms. Plugin should use CordovaInterface.getThreadPool().
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1494): [onResume]
I/FeedProviderManager( 1494): onResume,
I/SocialFeedProvider( 1494): +onResume
I/SocialFeedProvider( 1494): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1494): -onResume
,D/StatusBarManagerService(  970): setSystemUiVisibility(0x700),
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/FindExtension( 1494): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1494): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  970): Disable input method client, pid=6588,
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
I/InputMethodManagerService(  970): Enable input method client, pid=1494
W/IInputConnectionWrapper( 6588): reportFullscreenMode on inactive InputConnection
,D/PMS     (  970): releaseWL(3c5c18b3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
,D/Process (  970): killProcessQuiet, pid=6168,
I/ActivityManager(  970): Killing 6168:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-937731184] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-937731183] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1367): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.12 txretriesrate=0.00 rxrate=1.73 userTriggerdPenalty0
,E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
,I/ActivityManager(  970): Recipient 6168
,E/WifiStateMachine(  970): handleMessage: X,
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -65, 3
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/OpenGLRenderer( 1494): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1215): WifiActivity: 0
,E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=134
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 0
,D/PMS     (  970): acquireWL(7500146): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10072}
V/AlarmManager(  970): sending alarm PendingIntent{3f980f07: PendingIntentRecord{ebcb834 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455056182679, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{2e8b10d9: PendingIntentRecord{112e7a9e android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455056176673, Int=20000
E/WifiStateMachine(  970): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): handleMessage: E msg.what=131143
D/PMS     (  970): releaseWL(7500146): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_START_SCAN -2 -2 ic=6 proc(ms):1 dur:220 rssi=-65 f=2412 sc=60 link=65 tx=1.1, 0.0, 0.0  rx=1.7 list=2412 [on:0 tx:0 rx:0 period:490] from screen [on:0 period:-937730656]
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=6 proc(ms):2 dur:220 rssi=-65 f=2412 sc=60 link=65 tx=1.1, 0.0, 0.0  rx=1.7 list=2412 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-937730656]
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.12 rxSuccessRate=1.73 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-65
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN with age=1455056182689 interval=40000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN try full band scan age=1455056182689 interval=40000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN bump interval =60000
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1367): wlan0: Setting scan request: 0.000000 sec
,I/wpa_supplicant( 1367): wpa_supplicant_scan enter
D/wpa_supplicant( 1367): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1367): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1367): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1367): WPS:  * Request Type
D/wpa_supplicant( 1367): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1367): WPS:  * UUID-E
D/wpa_supplicant( 1367): WPS:  * Primary Device Type
D/wpa_supplicant( 1367): WPS:  * RF Bands (3)
D/wpa_supplicant( 1367): WPS:  * Association State
D/wpa_supplicant( 1367): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1367): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1367): WPS:  * Manufacturer
,D/wpa_supplicant( 1367): WPS:  * Model Name
,D/wpa_supplicant( 1367): WPS:  * Model Number
D/wpa_supplicant( 1367): WPS:  * Device Name
D/wpa_supplicant( 1367): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1367): P2P: * P2P IE header
D/wpa_supplicant( 1367): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1367): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1367): wlan0: Add radio work 'scan'@0x55986ee680
D/wpa_supplicant( 1367): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1367): wlan0: Starting radio work 'scan'@0x55986ee680 after 0.000033 second wait
D/wpa_supplicant( 1367): wlan0: nl80211: scan request
D/wpa_supplicant( 1367): Scan requested (ret=0) - scan timeout 30 seconds
,D/wpa_supplicant( 1367): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1367): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1367): wlan0: Own scan request started a scan in 0.000074 seconds
I/wpa_supplicant( 1367): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  970): [1,455,056,182,690 ms] noteScanstart no scan source
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  970): handleMessage: X
,D/Finsky  ( 6211): [632] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6211): [1] 5.onFinished: Installation state replication succeeded.
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=134
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=134
,D/wpa_supplicant( 1367): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1367): wlan0: nl80211: New scan results available
,D/wpa_supplicant( 1367): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1367): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1367): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1367): wlan0: Scan completed in 2.073068 seconds,
D/wpa_supplicant( 1367): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1367): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1367): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1367): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1367): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
,I/wpa_supplicant( 1367): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-65
I/wpa_supplicant( 1367): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
D/wpa_supplicant( 1367): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1367): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1367): wlan0: Scan-only results received
D/wpa_supplicant( 1367): wlan0: Radio work 'scan'@0x55986ee680 done in 2.073909 seconds
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1367): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  970): [1,455,056,184,767 ms] noteScanEnd no scan source
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1367): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@282bfb2b sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  970): NG7005g c0:ff:d4:d3:aa:4a rssi=-50 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): NG700 c0:ff:d4:d3:aa:48 rssi=-65 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-65 freq=2412
E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 3 now 1455056184769
E/WifiAutoJoinController (  970): newSupplicantResults size=3 known=1 true
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1367): wlan0: Control interface command 'STATUS-NO_EVENTS'
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
,E/WifiAutoJoinController (  970): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  970): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-65 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  970): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  970): Done attemptAutoJoin status=0
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  970): handleMessage: X
D/WifiManager( 1807): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.1, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:2487] from screen [on:0 period:-937728165] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.1, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-937728164] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1367): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.56 txretriesrate=0.00 rxrate=0.86 userTriggerdPenalty0,
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -61, 3
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=134
,I/HtcModeClient( 3173): handler message = 4011,
E/HtcModeClient( 3173): Check connection and retry 12 times.
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=109 rxSum=115} preTxRxSum={txSum=109 rxSum=115}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=134
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=134
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-937725147] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-937725146] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SIGNAL_POLL',
,I/wpa_supplicant( 1367): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.28 txretriesrate=0.00 rxrate=0.93 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -60, 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1215): WifiActivity: 1
,E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=135
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 1
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=135
E/WifiTrafficPoller(  970): notifying of data activity 0
,D/WIFI_ICON( 1215): WifiActivity: 0
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1579): service - handleMessage() stop self
,D/AutoSetting( 1579): service - handleMessage() quit looper
D/AutoSetting( 1579): service - onDestroy() END
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=135
,I/HtcModeClient( 3173): handler message = 4011,
,E/HtcModeClient( 3173): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3173): Don't start project servcice,
,D/HtcModeClient( 3173): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3173): connectState: CONNECTION_READY = false
D/SilentMusic( 3173): call stop
D/HtcModeClient( 3173): close connection
W/HtcModeClient( 3173): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3173): read the terminate packet, so break
,D/Process (  970): killProcessQuiet, pid=3173
I/ActivityManager(  970): Killing 3173:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 3173
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-937722126] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-937722124] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1367): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.14 txretriesrate=0.00 rxrate=0.47 userTriggerdPenalty0
,E/WifiStateMachine(  970):  good link -> stuck count =0
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61,
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -63, 3
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=109 rxSum=115} preTxRxSum={txSum=109 rxSum=115}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=135
,I/ActivityManager(  970): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6646 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  970): acquireWL(32b2765d): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10076}
V/AlarmManager(  970): sending alarm PendingIntent{1efaebd2: PendingIntentRecord{1b1c94a3 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455056192432, Int=60000
D/PMS     (  970): releaseWL(32b2765d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076},
,D/SMSBackup( 6646): SMSBackupAgentService started
,D/SMSBackup( 6646): Checking restore status
,D/SMSBackup( 6646): Restore complete
,D/SMSBackup( 6646): cancelCheckAlarm
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1215): WifiActivity: 1
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=138
E/WifiTrafficPoller(  970): notifying of data activity 1
,D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
D/SMSBackup( 6646): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  970): killProcessQuiet, pid=6291,
I/ActivityManager(  970): Killing 6291:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6291
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=139
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-937719102] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-937719101] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1367): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.07 txretriesrate=0.00 rxrate=2.23 userTriggerdPenalty0
,E/WifiStateMachine(  970):  good link -> stuck count =0
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -61, 3,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1215): WifiActivity: 0
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=139
,D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 0
,E/WifiStateMachine(  970): handleMessage: E msg.what=131165,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  970): handleMessage: X
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=139
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=109 rxSum=115} preTxRxSum={txSum=109 rxSum=115}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=139
,D/PMS     (  970): acquireWL(39251b59): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{2e8b10d9: PendingIntentRecord{112e7a9e android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455056196673, Int=20000
E/WifiStateMachine(  970): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): handleMessage: E msg.what=131143
D/PMS     (  970): releaseWL(39251b59): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_START_SCAN -2 -2 ic=7 proc(ms):1 dur:2077 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=2.2 fiv=60000 [on:0 tx:0 rx:0 period:2421] from screen [on:0 period:-937716668]
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=7 proc(ms):3 dur:2077 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=2.2 fiv=60000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-937716667]
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.07 rxSuccessRate=2.23 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-61,
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN with age=13988 interval=60000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  970): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  970): has c0:ff:d4:d3:aa:48 freq=2412 age=2425 ?=true
E/WifiStateMachine(  970): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1367): wlan0: Setting scan request: 0.000000 sec,
I/wpa_supplicant( 1367): wpa_supplicant_scan enter
D/wpa_supplicant( 1367): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1367): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1367): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1367): WPS:  * Request Type
D/wpa_supplicant( 1367): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1367): WPS:  * UUID-E,
D/wpa_supplicant( 1367): WPS:  * Primary Device Type
D/wpa_supplicant( 1367): WPS:  * RF Bands (3)
D/wpa_supplicant( 1367): WPS:  * Association State
D/wpa_supplicant( 1367): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1367): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1367): WPS:  * Manufacturer
D/wpa_supplicant( 1367): WPS:  * Model Name
D/wpa_supplicant( 1367): WPS:  * Model Number
D/wpa_supplicant( 1367): WPS:  * Device Name
D/wpa_supplicant( 1367): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1367): P2P: * P2P IE header
D/wpa_supplicant( 1367): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1367): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1367): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1367): wlan0: Add radio work 'scan'@0x55986ee680
,D/wpa_supplicant( 1367): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1367): wlan0: Starting radio work 'scan'@0x55986ee680 after 0.000039 second wait
D/wpa_supplicant( 1367): wlan0: nl80211: scan request
D/wpa_supplicant( 1367): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1367): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1367): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1367): wlan0: Own scan request started a scan in 0.000083 seconds
I/wpa_supplicant( 1367): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  970): [1,455,056,196,679 ms] noteScanstart no scan source
E/WifiStateMachine(  970): handleMessage: X
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1367): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1367): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1367): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1367): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1367): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1367): wlan0: Scan completed in 0.051620 seconds
D/wpa_supplicant( 1367): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1367): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1367): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1367): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1367): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1367): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1367): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
D/wpa_supplicant( 1367): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1367): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1367): wlan0: Scan-only results received
D/wpa_supplicant( 1367): wlan0: Radio work 'scan'@0x55986ee680 done in 0.052459 seconds
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  970):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1367): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  970): [1,455,056,196,736 ms] noteScanEnd no scan source
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1367): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@282bfb2b sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  970): NG7005g c0:ff:d4:d3:aa:4a rssi=-50 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): NG700 c0:ff:d4:d3:aa:48 rssi=-61 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-61 freq=2412
E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 3 now 1455056196738
E/WifiAutoJoinController (  970): newSupplicantResults size=3 known=1 true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1367): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  970): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
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
E/WifiAutoJoinController (  970): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-61,-127) num=(1,0)
E/WifiAutoJoinController (  970): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  970): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-61 freq=2412 Current: c0:ff:d4:d3:aa:48
,D/HtcWifiControlRoamOffload: (  970): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  970): Done attemptAutoJoin status=0
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  970): handleMessage: X
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:578] from screen [on:0 period:-937716087] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-937716086] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1367): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.04 txretriesrate=0.00 rxrate=1.62 userTriggerdPenalty0
,E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
,E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -61, 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  970): Going to sleep due to screen timeout (uid 1000)...,
,D/ActivityManager(  970): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{22f7f31e #7 A=.Prism U=0 sz=1}
W/PMS     (  970): mWirelessDisplayManager is null
W/PMS     (  970): mWirelessDisplayManager is still null
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@32c238e1
I/PMS     (  970): Sleeping (uid 1000)...
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
D/XAN-DPS (  970): prepareColorFade 1
W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@32c238e1, eanble = 0, strlen(mName) = 91
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
I/Adreno-EGL(  970): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  970): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  970): Build Date: 03/09/15 Mon
I/Adreno-EGL(  970): Local Branch: 
I/Adreno-EGL(  970): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  970): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  970):                  d74aa161a12b9c6fc6332151
,W/SensorService(  970): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3e033258
,W/PMN     (  970): goingToSleep
W/SensorService(  970): Listener[1] = com.htc.smartdim.sensor_eye@13ef7c3a
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  970): acquireWL(16d9d7ff): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 970 1000 null
,W/HtcLockScreen( 1215): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/FeedHostManager( 1494): [onPause]
,W/PMN     (  970): goingToSleep done
I/FeedProviderManager( 1494): onPause
I/FeedHostManager( 1494): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@200a400f
I/SocialFeedProvider( 1494): +onPause
I/SocialFeedProvider( 1494): -onPause
,W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
D/AlarmManager(  970): ACTION_SCREEN_ON
I/AlarmManager(  970): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done recovering
,I/AlarmManager(  970): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=140
E/WifiTrafficPoller(  970): notifying of data activity 1
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 1
D/PMS     (  970): releaseWL(16d9d7ff): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/WifiStateMachine(  970): handleMessage: E msg.what=131167
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0,
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
D/WIFI_ICON( 1215): WifiActivity: 1
E/WifiStateMachine(  970): processMsg: DefaultState
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
V/SRS_Proc(  399): ParamSet string: screen_state=on
D/NetworkPolicy(  970): updateScreenOn: false
D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=109 rxSum=115} preTxRxSum={txSum=109 rxSum=115}
V/NetworkPolicy(  970): updateIfacesLocked()
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1367): SET_SCREEN_ON:On
I/wpa_supplicant( 1367): htc_wext_set_keepalive +
I/wpa_supplicant( 1367): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1367): getPrivFuncNum +	
I/wpa_supplicant( 1367): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1367): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1367): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1367): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1367): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  970): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  970): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  970): handleScreenStateChanged Exit: true
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: ConnectedState
D/WifiController(  970): handleMessage: E msg.what=155650
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/WifiController(  970): handleMessage: X
E/WifiStateMachine(  970):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SIGNAL_POLL'
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/wpa_supplicant( 1367): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
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
E/WifiStateMachine(  970):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1367): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1367): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=38 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): handleMessage: X
I/IntentController( 1215): receive(android.intent.action.SCREEN_ON,1,false)
,D/PMS     (  970): acquireWL(efdf51b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1807 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(30b1c6b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1807 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(efdf51b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 12 num clients 6,
D/PMS     (  970): releaseWL(30b1c6b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  970): prepareColorFade done,
,D/XAN-DPS (  970): setBrightness to 0
,I/ActivityManager(  970): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6675 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@3e033258
,W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
,I/DisplayManagerService(  970): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  970): disable: get sensor name = CM32181 Light sensor
V/ActivityManager(  970): Display changed displayId=0
D/DotMatrix( 1310): [EventService]  onDisplayChanged: 0
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@3e033258, eanble = 0, strlen(mName) = 67
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@13ef7c3a
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1310): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/AlarmManager(  970): ACTION_SCREEN_OFF
,I/AlarmManager(  970): [AlarmQueuing] screen off now: 
I/AlarmManager(  970): [AlarmQueuing] data connection: true
I/AlarmManager(  970): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  970): stopDataStallAlarm 
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  970): handleMessage: E msg.what=131167
E/WifiStateMachine(  970): processMsg: ConnectedState
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
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_SCREEN_ON 0'
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
I/wpa_supplicant( 1367): SET_SCREEN_ON:Off
V/SRS_Proc(  399): ParamSet string: screen_state=off
I/wpa_supplicant( 1367): htc_wext_set_keepalive +
I/wpa_supplicant( 1367): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1367): getPrivFuncNum +	
I/wpa_supplicant( 1367): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1367): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1367): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1367): htc_wext_set_keepalive gateway addr = c0a80101
E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
I/wpa_supplicant( 1367): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  970): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  970): backgroundScan enabled=true startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  970): handleScreenStateChanged Exit: false
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): handleMessage: X
,D/WifiController(  970): handleMessage: E msg.what=155651
,D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
,D/WifiController(  970): handleMessage: X
D/NetworkPolicy(  970): updateScreenOn: false
V/NetworkPolicy(  970): updateIfacesLocked()
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1310): [EventService] getTotalRam: 1842 Mb
,I/SensorManager( 1215): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@313503e2, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  970): pid=1215, uid=10041
W/SensorService(  970): Active sensors: size = 4
,W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@313503e2, eanble = 1, strlen(mName) = 57
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@13ef7c3a
W/SensorService(  970): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@313503e2
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/ContextImpl( 6675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/IntentController( 1215): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1439): start background delete task...
D/ContactMessageStore( 1439): size: 0 , 0
D/PMS     (  970): acquireWL(3c189664): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1807 10024 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1439): Background delete complete
D/PMS     (  970): releaseWL(3c189664): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(9a2b0cd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1807 10024 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 6675): MY_DEBUG = false
D/PMS     (  970): releaseWL(9a2b0cd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6675): isEpsOn(), nState = 0
,D/PMS     (  970): acquireWL(21abec93): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6675 1000 null
,I/RemoteViews( 1215): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  970): releaseWL(21abec93): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/RemoteViews( 1215): apply : com.htc.updater 1 14 1 36,
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
D/SmartDim(  970): Init customizeScreenOffDelayClass error
,W/ContextImpl( 6675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 6675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 6675): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6675): isEpsOn(), nState = 0
,W/ContextImpl( 6675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl(  970): Excessive delay in setPowerMode(): 279ms
D/PMS     (  970): Setting HAL interactive mode to false
I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@13ef7c3a
D/PMS     (  970): Setting HAL interactive mode to false done
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
D/PMS     (  970): Setting HAL auto-suspend mode to true
,W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
D/PMS     (  970): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  970): screenObserver, isScreenOn=false
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,I/InputMethodManagerService(  970): Disable input method client, pid=1494
,D/HABCtrl (  970): TPE algorithm. remove timeout.,
W/SensorService(  970): pid=970, uid=1000
D/PMS     (  970): OOBE c monitor 11
W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@13ef7c3a, eanble = 0, strlen(mName) = 36
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@313503e2
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = CM36686 Proximity sensor
W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 2
D/PMS     (  970): acquireWL(3b155fce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@13ef7c3a, eanble = 0, strlen(mName) = 36
I/BatteryService(  970): n_update end
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@313503e2
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  970): releaseWL(3b155fce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NfcService( 1456): ScreenObserver: OFF
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@13ef7c3a
D/NfcService( 1456): applyRouting - 0
,I/InputManager(  970): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,D/PMS     (  970): acquireWL(129ebeef): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1456 1027 null
,D/NfcService( 1456): applyRouting -2
,D/NfcService( 1456): applyRouting
D/NfcService( 1456): Ignore this applyRouting...
D/PMS     (  970): releaseWL(129ebeef): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6709 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
D/HtcPowerSaver(  970): updateBatteryInfo
E/ActivityThread(  970): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3adc0eb that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3adc0eb that was originally registered here. Are you missing a call to unregisterReceiver()?
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
I/IntentController( 1215): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/PowerUsageList:PowerUsageHelper( 6675): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6675): gen(), null == sipper.uidObj, userId = 0,
,I/ClockController( 1215): stop clock update:screen off
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/Process (  970): killProcessQuiet, pid=6383
I/ActivityManager(  970): Killing 6383:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6675): getMobilePolicyEnabled, result = true,
,D/WifiService(  970): New client listening to asynchronous messages
,E/WifiTrafficPoller(  970): ADD_CLIENT: 7
,I/ActivityManager(  970): Recipient 6383
,D/PowerUsageList:PowerUsageHelper( 6675): MY_DEBUG = false
,I/ActivityManager(  970): Killing 6417:com.htc.mediamanager/u0a28 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=6417
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,I/ActivityManager(  970): Recipient 6417
,D/PMS     (  970): releaseWL(1449234a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-937713066] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-937713065] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): handleMessage: X
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:165] from screen [on:0 period:-937712899] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-937712897] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): handleMessage: X
,D/HtcUPManager( 1215): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 3,
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 3,
,D/ContactMessageStore( 1439): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1439): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/Process (  970): killProcessQuiet, pid=5197
,I/ActivityManager(  970): Killing 5197:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5197,
,E/WifiStateMachine(  970): handleMessage: E msg.what=131326,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState what:131326 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState what:131326 1 0
E/WifiStateMachine(  970): handleMessage: X
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  970): acquireWL(279e4dfc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{311b5f4d: PendingIntentRecord{23f3a02 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=134046, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{27122c85: PendingIntentRecord{202baada android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455056226986, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{3f425b0b: PendingIntentRecord{1c804de8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141767, Int=0
,D/PMS     (  970): acquireWL(23ce0c01): PARTIAL_WAKE_LOCK  *backup* 0x1 970 1000 null,
,W/BackupManagerService(  970): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  970): Requested init for com.google.android.gms.backup.BackupTransportService but not found,
,D/PMS     (  970): releaseWL(23ce0c01): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  970): releaseWL(279e4dfc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On,
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  970): acquireWL(10299aa6): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 970 1000 null
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  970): [NET] android_getaddrinfo_proxy-, success,
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  970): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  970): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  970): acquireWL(c4bb32): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/GpsLocationProvider(  970): [reportHTCStatus] INJECT_XTRA_DATA, status: 0,
D/PMS     (  970): releaseWL(10299aa6): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  970):  [handleDownloadXtraData]inject done.,
D/PMS     (  970): releaseWL(c4bb32): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  970): acquireWL(3f792083): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  970): n_update end
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(3f792083): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1439): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  970): acquireWL(16ccf200): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{311b5f4d: PendingIntentRecord{23f3a02 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=194046, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{12ff3a39: PendingIntentRecord{1b7f587e android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=197992, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{31a341df: PendingIntentRecord{320f2e2c com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=184611, Int=0
,D/PMS     (  970): acquireWL(129040f5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(16ccf200): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  970): acquireWL(db47e8a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(129040f5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  970): Explicit concurrent mark sweep GC freed 54278(3MB) AllocSpace objects, 9(1176KB) LOS objects, 33% free, 18MB/28MB, paused 2.010ms total 156.138ms,
,D/PMS     (  970): releaseWL(db47e8a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(2a4716c4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(2a4716c4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(8cc99ad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(8cc99ad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1ebe54e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1db33073): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1c4623a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(1ebe54e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1878): Vacuum at: now=1455056284457 tag=VacuumService
,I/GoogleURLConnFactory( 1878): Using platform SSLCertificateSocketFactory,
,D/PMS     (  970): releaseWL(1db33073): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(10660cf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(10660cf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(10507a5c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(10507a5c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1878): No account for auth token provided,
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1878): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1878): [NET] android_getaddrinfo_proxy+
D/libc    ( 1878): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1878): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1878): No account for auth token provided
,W/Uploader( 1878):  no longer exists, so no auth token.
,W/Uploader( 1878): No account for auth token provided,
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1215): reapply : com.google.android.gms 4 40
,E/Uploader( 1878): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1878): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1878): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1878): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1878): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1878): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1878): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1878): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337),
E/Uploader( 1878): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1878): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1878): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1878): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1878): ,	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1878): No account for auth token provided,
,W/Uploader( 1878): No account for auth token provided,
,D/PMS     (  970): releaseWL(1c4623a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(10924919): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(10924919): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(2e4edde): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(2e4edde): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1579): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@68b0ac8
,D/Process (  970): killProcessQuiet, pid=6441
I/ActivityManager(  970): Killing 6441:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6441,
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  970): acquireWL(13a71bbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(13a71bbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo,
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  970): acquireWL(3d55328c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(3d55328c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck,
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1367): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1367): wlan0: BSS: Remove id 1 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
,D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 a0:c5:62:7a:49:97]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  970): acquireWL(36f55dd5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{311b5f4d: PendingIntentRecord{23f3a02 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=254046, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{3bbb4db: PendingIntentRecord{468eb78 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1455056426316, Int=0,
,D/PMS     (  970): releaseWL(36f55dd5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  970): acquireWL(2f3b0251): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{327adab6: PendingIntentRecord{bb6c3b7 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=373587, Int=0
D/PMS     (  970): acquireWL(2fd4724): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 970 1000 null
D/PMS     (  970): acquireWL(1b5c728d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
D/PMS     (  970): releaseWL(2f3b0251): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  970): releaseWL(2fd4724): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null,
,D/PMS     (  970): releaseWL(1b5c728d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1878): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1878): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1878): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1878): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 6211): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6211): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6211): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6211): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6211): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6211): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6211): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1215): reapply : com.google.android.gms 4 40
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/System  ( 6211): Ignoring header User-Agent because its value was null.,
,D/libc    ( 6211): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6211): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6211): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6211): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6211): [NET] android_getaddrinfo_proxy+
D/libc    ( 6211): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6211): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PMS     (  970): acquireWL(5ca08a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(5ca08a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652,
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: StaEnabledState
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): << updateStatus
,D/WifiController(  970): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  970): acquireWL(1dd2c154): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(1dd2c154): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo,
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1215): closing low battery warning: level=100
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/NotificationService(  970): plugged=true pluggin=true
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  970): runPSCheck
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): Checking...
,D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/PMS     (  970): acquireWL(49c18fd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{311b5f4d: PendingIntentRecord{23f3a02 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=374046, Int=0
,I/ActivityManager(  970): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6745 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  970): sending alarm PendingIntent{16c1e9f2: PendingIntentRecord{29048843 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1455056580242, Int=0
,D/PMS     (  970): releaseWL(49c18fd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,E/cutils-trace( 6766): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6766): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6766): dex2oat: override thread count:4
,I/dex2oat ( 6766): dex2oat took 563.503ms (threads: 4)
,I/PushClient( 6745): ApplicationMonitor {84c1608}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6745): ApplicationMonitor {84c1608}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6745): ApplicationMonitor {84c1608}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6745): ApplicationMonitor {84c1608}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6745): ApplicationMonitor {84c1608}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6745): ApplicationMonitor {84c1608}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6745): ApplicationMonitor {84c1608}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6745): ApplicationMonitor {84c1608}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6745): ApplicationMonitor {84c1608}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6745): PnsModel {367dafab}: update(): Update registration caused by: alarm
,I/PushClient( 6745): PnsConfigModel {2289319e}: <init>(): Use dm-client for provisioning.
,W/System.err( 6745): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6745): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6745): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6745): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  970): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6773 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6773): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6773 dbg=false s=true,
,I/DeviceManagement( 6773): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6773): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6773): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6773): WorkflowService: Starting workflow service
,I/DeviceManagement( 6773): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@8e2edfa] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6773): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6773): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6773): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6773): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6773): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6773): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6773): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6773): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@8e2edfa],
,I/DeviceManagement( 6773): WorkflowService: Stopping workflow service,
,D/Process (  970): killProcessQuiet, pid=6253
I/ActivityManager(  970): Killing 6253:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6253,
,I/PushClient( 6745): PnsModel {367dafab}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  970): killProcessQuiet, pid=6189
I/ActivityManager(  970): Killing 6189:com.android.settings/1000 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6189,
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  970): acquireWL(3d32784): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3d32784): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
,D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/HtcPowerSaver(  970): updateBatteryInfo,
,D/PMS     (  970): runPSCheck
,D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,W/Atfwd_Sendcmd(  440): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1439): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1439): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1439): sku_id=118
D/ContactMessageStore( 1439): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1439): start background delete task...
,D/ContactMessageStore( 1439): size: 0 , 0
,D/ContactMessageStore( 1439): Background delete complete
,D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/PMS     (  970): acquireWL(b0a3b6d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  970): n_update end
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(b0a3b6d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): processMsg: StaEnabledState
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): battery changed pluggedType: 2
,D/WifiController(  970): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(34c4b3a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(34c4b3a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1215): closing low battery warning: level=100
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  970): updateBatteryInfo
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
,D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(37c80833): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/BatteryService(  970): n_update end
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): releaseWL(37c80833): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/bt-btm  ( 3092): Received oneshot timer event complete,
D/PMS     (  970): acquireWL(3d1d37f0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{311b5f4d: PendingIntentRecord{23f3a02 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=554046, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{201c2169: PendingIntentRecord{3e5e67ee com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940223, Int=0
,I/bt-btm  ( 3092): btm_ble_timeout,
D/PMS     (  970): acquireWL(21f0f48f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3092 1002 null
I/bt-btm  ( 3092): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3092): btm_ble_rand_enc_complete
I/bt-btm  ( 3092): btm_gen_resolve_paddr_low
,D/bt-smp  ( 3092): smp_encrypt_data
W/bt-smp  ( 3092): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3092): Plain text(LSB ~ MSB) = a2 67 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 3092): Encrypted text(LSB ~ MSB) = 14 7f d1 6c f4 6c dd 8d 9d 6a 9d e7 0e 83 36 5b 
I/bt-btm  ( 3092): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3092): Stopping oneshot timer
D/bt-btm  ( 3092): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  970): releaseWL(3d1d37f0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  970): releaseWL(21f0f48f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  970): acquireWL(13b5e31c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(13b5e31c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
,D/UsbnetService(  970): BroadcastReceiver::onReceive+,
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/HtcPowerSaver(  970): updateBatteryInfo
D/PMS     (  970): runPSCheck
,D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(134c6b25): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
,V/AlarmManager(  970): sending alarm PendingIntent{93b2d75: PendingIntentRecord{138a310a android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804721, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{311b5f4d: PendingIntentRecord{23f3a02 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=974046, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{3cd14fa: PendingIntentRecord{e124aab com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455056903684, Int=1800000
V/AlarmManager(  970): sending alarm PendingIntent{3bcc1508: PendingIntentRecord{307d94a1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=974566, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{3e4786c6: PendingIntentRecord{1476484e com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455057046403, Int=0,
,D/WeatherUtility( 1215): Weather sync is On
D/PMS     (  970): acquireWL(12a8e687): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4370 10024 WorkSource{10024 com.google.android.gms}
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data,
,D/PMS     (  970): acquireWL(53dd9dd): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(31a54952): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4370 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(53dd9dd): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): releaseWL(12a8e687): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  970): releaseWL(134c6b25): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6675): MY_DEBUG = false
,D/PowerUsageService( 6675): repeat time = 1455057960583,
,I/EventLogService( 4370): Aggregate from 1455056156686 (log), 1455055103651 (data)
,D/PMS     (  970): releaseWL(31a54952): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(13e1f7f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1878): Message class com.google.f.a.a.i
D/PMS     (  970): releaseWL(13e1f7f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6675): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6675): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  970): acquireWL(10464b4c): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{21a76795: PendingIntentRecord{814b0aa com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455057097820, Int=0
,D/SmartSyncUtils( 6675): isEpsOn(), nState = 0
,D/PMS     (  970): releaseWL(10464b4c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  970): acquireWL(c1f349b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6675 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6675): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6675): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6675): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6675): SettingOnTime = 1455084000000, randomSettingOnTime = 1455081167000
,D/SmartSyncScreenOnOffTimeReceiver( 6675): SettingOffTime = 1455062400000, randomSettingOffTime = 1455067786000,
,D/SmartSyncScreenOnOffTimeReceiver( 6675): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6675): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6675): bNightModeTurnOffOnce = false
,D/PMS     (  970): releaseWL(c1f349b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  970): acquireWL(3632d038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3632d038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive-,
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
D/PMS     (  970): runPSCheck
D/WifiController(  970): processMsg: DeviceActiveState
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: StaEnabledState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(1263e811): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(1263e811): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo
,D/DotMatrix( 1310): [EventService] reorderNotification, total:1
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=98
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/PMS     (  970): runPSCheck
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): updateStatus (8000,98,-1,false,false,false,-1)
,D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
W/ContextImpl( 6675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
D/WifiController(  970): processMsg: StaEnabledState
D/HeadsetPhoneState( 3092): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3092): Disconnected process message: 11, size: 0
,I/ActivityManager(  970): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=6806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/BatteryController( 1215): status:2 level:98 unsupport:false plugged:true,
,I/art     (  407): Explicit concurrent mark sweep GC freed 8653(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 247us total 32.356ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 22.149ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 159us total 22.130ms
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6806): -onCreate(),
,V/Settings:HtcSettingsApplication( 6806): [6806/6806] onCreate()
,D/TetherSettings( 6806): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 6806): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6806): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6806): Cust_ConnectToPC   : spcsc>false
D/        ( 6806): Cust_ConnectToPC   : IPT>true
D/        ( 6806): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 6806): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false,
,D/SmartNS_NSReceiver( 6806): Index of the first 1 = -1
,W/ContextImpl( 6806): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 ,
,W/Settings( 6806): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SmartNS_Utility( 6806): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6806): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6806): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 6806): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 6806): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,I/ActivityManager(  970): Killing 5636:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=5636
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  970): Recipient 5636
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  970): acquireWL(35327f77): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/BatteryService(  970): n_update end
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  970): releaseWL(35327f77): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): closing low battery warning: level=98
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
,D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:2 level:98 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  970): User[0] Flushing usage stats to disk
,D/PMS     (  970): acquireWL(1660b7e4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
,I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(1660b7e4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1215): closing low battery warning: level=99
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: StaEnabledState
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  970): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:2 level:99 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms)
```
