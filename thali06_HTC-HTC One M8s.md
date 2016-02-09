#### Test 58135655e9e7eb8_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
I/HtcModeClient( 3181): handler message = 4011
E/HtcModeClient( 3181): Check connection and retry 10 times.
E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  971):  packet count Tx=156 Rx=221
E/cutils-trace( 6423): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6423): ====startRecUseTime====
D/htc.customization.log.level( 6423):  is 
W/CustomizationLogLevel( 6423): Level value is invalid, use default level 2
E/WifiStateMachine(  971): handleMessage: E msg.what=131155
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-972422402] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-972422401] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971):  get link layer stats 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1327): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  971): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  971): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.54 txretriesrate=0.00 rxrate=0.71 userTriggerdPenalty0
E/WifiStateMachine(  971):  good link -> stuck count =0
E/WifiStateMachine(  971):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  971):  isHighRSSI       ---> score=61
E/WifiStateMachine(  971): handleMessage: X
D/WifiWatchdogStateMachine(  971): RSSI current: 3 new: -64, 3
--------- beginning of system
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/CustomizationManager( 6423):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6423): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6423): Parsing tag category name = system
I/CustomizationCIDLoader( 6423): Parsing tag category name = application
I/CustomizationCIDLoader( 6423): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6423): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6423): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6423): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6423): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6423): add string-array item, value = 42507
I/CustomizationCIDLoader( 6423): add string-array item, value = 21902
I/CustomizationCIDLoader( 6423): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6423): add string-array item, value = 23420
I/CustomizationCIDLoader( 6423): add string-array item, value = 22299
I/CustomizationCIDLoader( 6423): add string-array item, value = 24002
I/CustomizationCIDLoader( 6423): add string-array item, value = 23210
I/CustomizationCIDLoader( 6423): add string-array item, value = 23205
I/CustomizationCIDLoader( 6423): add string-array item, value = 23806
I/CustomizationCIDLoader( 6423): add string-array item, value = 23430
I/CustomizationCIDLoader( 6423): add string-array item, value = 23408
I/CustomizationCIDLoader( 6423): add string-array item, value = 27205
I/CustomizationCIDLoader( 6423): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6423):  Read CID file spent 0.094 (s)
D/CustomizationManager( 6423):  All configurations done spent 0.094 (s)
I/ActivityManager(  971): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6423 on display 0
D/PMS     (  971): acquireHCC(19045847): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 971 1000 null
D/PMS     (  971): acquireHCC(7a96874): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 971 1000 null
D/PMS     (  971): acquireWL(3b2431e3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 971 1000 null
I/FeedHostManager( 1626): [onPause]
I/FeedProviderManager( 1626): onPause
I/FeedHostManager( 1626): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2ddf0359
I/SocialFeedProvider( 1626): +onPause
I/SocialFeedProvider( 1626): -onPause
I/AnimationUtil(  971): isHTCRecent(ThaliTest/Recent screens.)/5
W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  971): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6441 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  971): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
I/TrimMemoryManager( 1626): [trimMemory] 20
,I/WebViewFactory( 6441): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6441): Time to load native libraries: 12 ms (timestamps 2048-2060)
I/LibraryLoader( 6441): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6441): Binding Chromium to main looper Looper (main, tid 1) {25ede9b}
I/LibraryLoader( 6441): Expected native library version number "",actual native library version number ""
I/chromium( 6441): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6441): Initializing chromium process, singleProcess=true
W/art     ( 6441): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6441): ApplicationContext is null in ApplicationStatus
W/chromium( 6441): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6441): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6441): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6441): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6441): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6441): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6441): Local Branch: 
I/Adreno-EGL( 6441): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6441): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6441):                  d74aa161a12b9c6fc6332151
W/System.err(  971): java.lang.Throwable: stack dump
W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7f68c0d:true
D/BluetoothAdapter( 6441): 549636471: getState(). Returning 12
W/art     ( 6441): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6441): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6441): CordovaWebView is running on device made by: HTC
W/art     ( 6441): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6441): Attempt to remove local handle scope entry from IRT, ignoring
E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  971):  packet count Tx=156 Rx=221
W/chromium( 6441): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6441): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6441): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3e33e414, mServedView=org.apache.cordova.engine.SystemWebView{70e64bd VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@b00aab2
I/InputMethodManagerService(  971): Disable input method client, pid=1626
D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  971): Enable input method client, pid=6441
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
I/ActivityManager(  971): Displayed com.test.thalitest/.MainActivity: +818ms
W/XT9_C   ( 1410): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1410): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1410): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1410): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  971): releaseWL(3b2431e3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/BindingManager( 6441): Cannot call determinedVisibility() - never saw a connection for the pid: 6441
D/JsMessageQueue( 6441): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6441): JniHelper::setJavaVM(0xab1608f8), pthread_self() = -1404515064
I/chromium( 6441): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  971):  packet count Tx=156 Rx=222
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  971): notifying of data activity 1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 6441): Initializing JXcore engine
W/jxcore-log( 6441): JXcore engine is ready
,W/jxcore-log( 6441): Starting JXcore engine,
,D/PMS     (  971): releaseHCC(19045847): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  971): releaseHCC(7a96874): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6441): Platform android
W/jxcore-log( 6441): 
,W/jxcore-log( 6441): Process ARCH arm
W/jxcore-log( 6441): 
,I/jxcore-log( 6441): JXcore Cordova bridge is ready!
I/jxcore-log( 6441): 
,W/jxcore-log( 6441): JXcore engine is started
,E/jxcore  ( 6441): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6441): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6441): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/PMS     (  971): acquireWL(3483dd58): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 971 1000 null,
,W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/PluginManager( 6441): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 73ms. Plugin should use CordovaInterface.getThreadPool().
,I/FeedHostManager( 1626): [onResume]
,I/FeedProviderManager( 1626): onResume
I/SocialFeedProvider( 1626): +onResume
I/SocialFeedProvider( 1626): updateAccounts - Accounts is no change,
I/SocialFeedProvider( 1626): -onResume
,D/StatusBarManagerService(  971): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
,D/FindExtension( 1626): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1626): Defer allocateBuffers to drawing time
I/InputMethodManagerService(  971): Disable input method client, pid=6441
D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  971): Enable input method client, pid=1626
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
W/IInputConnectionWrapper( 6441): reportFullscreenMode on inactive InputConnection,
E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  971):  packet count Tx=156 Rx=222
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  971): notifying of data activity 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  971): releaseWL(3483dd58): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  971): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
,D/AutomaticBrightnessController(  971): setAmbientLux to brighter = 225.0
,D/HABCtrl (  971): lsvalue=160(3th)->225(4th), lValue=90->116
,D/Process (  971): killProcessQuiet, pid=5273
I/ActivityManager(  971): Killing 5273:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  971): Recipient 5273,
,E/WifiStateMachine(  971): handleMessage: E msg.what=131155,
E/WifiStateMachine(  971): processMsg: ConnectedState,
E/WifiStateMachine(  971):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-972419378] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-972419377] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971):  get link layer stats 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1327): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  971): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
,E/WifiStateMachine(  971): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.27 txretriesrate=0.00 rxrate=0.85 userTriggerdPenalty0,
E/WifiStateMachine(  971):  good link -> stuck count =0
E/WifiStateMachine(  971):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  971):  isHighRSSI       ---> score=61
,E/WifiStateMachine(  971): handleMessage: X
D/WifiWatchdogStateMachine(  971): RSSI current: 3 new: -63, 3
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/OpenGLRenderer( 1626): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,E/WifiDataStallTracker(  971): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  971): updateDataStallInfo: mDataStallTxRxSum={txSum=138 rxSum=121} preTxRxSum={txSum=138 rxSum=121}
D/WifiDataStallTracker(  971): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  971): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  971):  packet count Tx=156 Rx=222
,D/PMS     (  971): acquireWL(a33020f): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10072}
V/AlarmManager(  971): sending alarm PendingIntent{8f2a29c: PendingIntentRecord{1d82f4a5 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455021491499, Int=0
,V/AlarmManager(  971): sending alarm PendingIntent{13eaa07a: PendingIntentRecord{1027b02b com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455021495269, Int=536832000
,V/AlarmManager(  971): sending alarm PendingIntent{5f469f1: PendingIntentRecord{22beb9d6 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455021489675, Int=20000
,V/CheckinService( 4369): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,D/PMS     (  971): acquireWL(24d54c88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4369 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  971): WiFiStateMachine SCAN ALARM,
D/WifiDisplayAdapter(  971): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  971):     Client/Owner: Client,
D/WifiDisplayAdapter(  971):     GroupId: 
D/WifiDisplayAdapter(  971):     Passphrase: 
D/WifiDisplayAdapter(  971):     SessionId: 0
D/WifiDisplayAdapter(  971):     IP Address: }
E/WifiStateMachine(  971): handleMessage: E msg.what=131143
D/PMS     (  971): releaseWL(a33020f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  971): processMsg: ConnectedState
D/PMS     (  971): acquireWL(3d724a46): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4369 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  971):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):3 dur:83 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 list=2412 [on:0 tx:0 rx:0 period:1293] from screen [on:0 period:-972418043]
D/PMS     (  971): releaseWL(24d54c88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):4 dur:83 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-972418042]
E/WifiStateMachine(  971): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.27 rxSuccessRate=0.85 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-63
E/WifiStateMachine(  971): WifiStateMachine CMD_START_SCAN with age=57709 interval=60000 maxinterval=300000
E/WifiStateMachine(  971): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  971): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  971): has c0:ff:d4:d3:aa:48 freq=2412 age=1321 ?=true
E/WifiStateMachine(  971): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1327): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1327): wpa_supplicant_scan enter
D/wpa_supplicant( 1327): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1327): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1327): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1327): WPS:  * Request Type
D/wpa_supplicant( 1327): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1327): WPS:  * UUID-E
D/wpa_supplicant( 1327): WPS:  * Primary Device Type
D/wpa_supplicant( 1327): WPS:  * RF Bands (3)
D/wpa_supplicant( 1327): WPS:  * Association State
D/wpa_supplicant( 1327): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1327): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1327): WPS:  * Manufacturer
D/wpa_supplicant( 1327): WPS:  * Model Name
D/wpa_supplicant( 1327): WPS:  * Model Number
D/wpa_supplicant( 1327): WPS:  * Device Name
D/wpa_supplicant( 1327): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1327): P2P: * P2P IE header
D/wpa_supplicant( 1327): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1327): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1327): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1327): wlan0: Add radio work 'scan'@0x559e8fe680
D/wpa_supplicant( 1327): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1327): wlan0: Starting radio work 'scan'@0x559e8fe680 after 0.000039 second wait
D/wpa_supplicant( 1327): wlan0: nl80211: scan request
D/wpa_supplicant( 1327): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1327): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1327): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1327): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1327): wlan0: Own scan request started a scan in 0.000083 seconds
I/wpa_supplicant( 1327): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  971): [1,455,021,495,304 ms] noteScanstart no scan source
E/WifiStateMachine(  971): handleMessage: X
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  971): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  971): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/CheckinService( 4369): Checking schedule, now: 1455021495321 next: 1455021495269
I/CheckinService( 4369): active receiver: enabled
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4369, uid=10024, userID:0
,I/CheckinService( 4369): Preparing to send checkin request,
I/EventLogService( 4369): Accumulating logs since 1455021460516
,I/CheckinRequestBuilder( 4369): Checkin reason type: 11 attempt count: 1
,I/ActivityManager(  971): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4369): Failed to find provider info for com.google.android.wearable.settings
,D/wpa_supplicant( 1327): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1327): wlan0: nl80211: New scan results available
,D/wpa_supplicant( 1327): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1327): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1327): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1327): wlan0: Scan completed in 0.078984 seconds
D/wpa_supplicant( 1327): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1327): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1327): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1327): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
,I/wpa_supplicant( 1327): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
I/wpa_supplicant( 1327): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1327): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1327): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
D/wpa_supplicant( 1327): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1327): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1327): wlan0: Scan-only results received
D/wpa_supplicant( 1327): wlan0: Radio work 'scan'@0x559e8fe680 done in 0.079831 seconds
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  971): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  971): handleMessage: E msg.what=147461
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  971): processMsg: ConnectModeState
E/WifiStateMachine(  971):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  971): processMsg: DriverStartedState
E/WifiStateMachine(  971):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  971): processMsg: SupplicantStartedState
E/WifiStateMachine(  971):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  971): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1327): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  971): [1,455,021,495,389 ms] noteScanEnd no scan source
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1327): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  971): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3e51dcd sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  971): NG7005g c0:ff:d4:d3:aa:4a rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  971): NG700 c0:ff:d4:d3:aa:48 rssi=-63 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  971): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  971): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  971):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-63 freq=2412
E/WifiAutoJoinController (  971): Gonzos 38:f8:89:11:e9:11 rssi=-77 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  971): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  971): ageScanResultsOut delay 40000 size 4 now 1455021495392
E/WifiAutoJoinController (  971): newSupplicantResults size=4 known=1 true
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1327): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  971): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  971): ssid=NG700
E/WifiAutoJoinController (  971): id=0
E/WifiAutoJoinController (  971): mode=station
E/WifiAutoJoinController (  971): pairwise_cipher=CCMP
E/WifiAutoJoinController (  971): group_cipher=CCMP
E/WifiAutoJoinController (  971): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  971): wpa_state=COMPLETED
E/WifiAutoJoinController (  971): ip_address=192.168.1.130
E/WifiAutoJoinController (  971): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  971): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  971): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  971): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  971): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-63,-127) num=(1,0)
E/WifiAutoJoinController (  971): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  971): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-63 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  971): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  971): Done attemptAutoJoin status=0
E/WifiConfigStore(  971):  writeKnownNetworkHistory() num networks:1 needWrite=false
,E/WifiStateMachine(  971): handleMessage: X
,I/HtcModeClient( 3181): handler message = 4011
E/HtcModeClient( 3181): Check connection and retry 11 times.
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4369): awaiting user notification for token
,D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
,I/ActivityManager(  971): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6499 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/art     (  454): Explicit concurrent mark sweep GC freed 8668(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 232us total 27.754ms
,I/art     (  454): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 172us total 22.941ms,
D/Finsky  ( 5958): [587] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
W/ResourcesManager( 6499): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6499): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 5958): [1] 5.onFinished: Installation state replication succeeded.
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  971):  packet count Tx=156 Rx=225
E/WifiTrafficPoller(  971): notifying of data activity 1
,D/WIFI_ICON( 1222): WifiActivity: 1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/art     (  454): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 179us total 24.343ms
,I/MultiDex( 6499): VM with version 2.1.0 has multidex support,
,I/MultiDex( 6499): install
I/MultiDex( 6499): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6499): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6499): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6499): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b41059d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6499): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1962): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1962): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4369): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 5667): callingUid 10024, callindPid: 5667,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4369, uid=10024, userID:0
,E/MDM     ( 1795): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,I/WVCdm   (  406): CdmEngine::OpenSession,
I/WVCdm   (  406): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  406): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/LocationInitializer( 4369): Restart initialization of location
D/DrmWidevineDash(  406): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  406): Service_Initialize: starts!
D/QSEECOMAPI: (  406): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  406): App is not loaded in QSEE
E/QSEECOMAPI: (  406): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  406): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  406): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  406): App is not loaded in QSEE
,D/QSEECOMAPI: (  406): Loaded image: APP id = 8
,D/DrmWidevineDash(  406): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  406): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  406): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  406): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4c3e000
E/DrmWidevineDash(  406): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4c3e000
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  577): got the req here! ret=0
D/DrmLibTime(  577): command id, time_cmd_id = 770
D/DrmLibTime(  577): time_getutcsec starts!
D/DrmLibTime(  577): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  577): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  577): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  577): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  577): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  577): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  577): QSEE Time Listener: Retrieved Android system time: 1455021496
D/DrmLibTime(  577): time_getutcsec returns 0, sec = 1455021496; nsec = 0
D/DrmLibTime(  577): time_getutcsec finished! 
D/DrmLibTime(  577): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  577): before calling ioctl to read the next time_cmd
E/QC-time-services(  480): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  406): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  406): OEMCrypto_APIVersion: starts!
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): hlos api version =  9,
D/DrmWidevineDash(  406): tz api version =  9
D/DrmWidevineDash(  406): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  406): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  406): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  406): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  406): OEMCrypto_OpenSession: starts! SID=0xf4e68928,
D/DrmWidevineDash(  406): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  406): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  406): OEMCrypto_GetRandom: starts! randomData=0xab962488, dataLength=8,
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  406): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab943278, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  406): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  406): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  406): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  406): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  406): OEMCrypto_GetDeviceID: starts! deviceID=0xab936cc8, idLength=0xf41416f8
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  406): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  406): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  406): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  406): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  406): OEMCrypto_GetHDCPCapability: starts!, current = 0xf414170e, maximum = 0xf414170f
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_GetHDCPCapability: ends! returns 0
,D/DrmWidevineDash(  406): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): hlos api version =  9
D/DrmWidevineDash(  406): tz api version =  9
D/DrmWidevineDash(  406): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  406): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf414177c
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  406): PrepareKeyRequest: nonce=1071751503
D/DrmWidevineDash(  406): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaba81a50
D/DrmWidevineDash(  406): message_length=1611, signature=0xaba820a0, signature_length=0xf41416dc
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/WVCdm   (  406): CdmEngine::OpenSession,
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  406): OEMCrypto_GenerateRSASignature returns 0
D/DrmWidevineDash(  406): OEMCrypto_OpenSession: starts! SID=0xf4e68928,
D/DrmWidevineDash(  406): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_OpenSession SID = 2
D/DrmWidevineDash(  406): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  406): OEMCrypto_GetRandom: starts! randomData=0xab942a30, dataLength=8
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/WVCdm   (  406): CdmEngine::CloseSession
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  406): OEMCrypto_LoadDeviceRSAKey: starts! SID=2, wrapped_rsa_key=0xab943768, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  406): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  406): CdmEngine::QueryKeyControlInfo
D/DrmWidevineDash(  406): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_CloseSession: ends! returns 0
,W/WVCdm   (  406): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  406): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  406): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  406): OEMCrypto_GetDeviceID: starts! deviceID=0xab936ce8, idLength=0xf4e686f8
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  406): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  406): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  406): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  406): OEMCrypto_SupportsUsageTable: ends! returns 0
,D/DrmWidevineDash(  406): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4e6870e, maximum = 0xf4e6870f
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  406): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): hlos api version =  9
D/DrmWidevineDash(  406): tz api version =  9,
D/DrmWidevineDash(  406): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  406): OEMCrypto_GenerateNonce: starts! SID=2, nonce=0xf4e6877c
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  406): PrepareKeyRequest: nonce=3230982796
D/DrmWidevineDash(  406): OEMCrypto_GenerateRSASignature starts! SID=2, message=0xaba81a50
D/DrmWidevineDash(  406): message_length=1646, signature=0xaba820c8, signature_length=0xf4e686dc
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  406): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  406): CdmEngine::CloseSession
D/DrmWidevineDash(  406): OEMCrypto_CloseSession: starts! SID=2
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  406): L3 Terminate.
D/DrmWidevineDash(  406): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  406): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  406): Service_Uninitialize: starts!
D/QSEECOMAPI: (  406): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  406): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  406): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  406): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6530): Error opening trace file: Permission denied (13),
I/dex2oat ( 6530): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6530): dex2oat: override thread count:4
,I/dex2oat ( 6530): dex2oat took 68.072ms (threads: 4),
,I/Adreno-EGL( 6499): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6499): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6499): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6499): Local Branch: 
I/Adreno-EGL( 6499): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6499): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6499):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6499): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6499): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6499): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6499): Local Branch: 
I/Adreno-EGL( 6499): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6499): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6499):                  d74aa161a12b9c6fc6332151
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  971):  packet count Tx=156 Rx=225
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  971): notifying of data activity 0
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/CheckinRequestBuilder( 4369): Classify the device as Phone.
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 14654(792KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 861us total 40.195ms
,D/libc    ( 4369): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4369): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4369): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4369): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4369): [NET] android_getaddrinfo_proxy+
D/libc    ( 4369): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4369): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4369): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4369): [NET] android_getaddrinfofornet-, err=8
,E/WifiStateMachine(  971): handleMessage: E msg.what=131155,
E/WifiStateMachine(  971): processMsg: ConnectedState
,E/WifiStateMachine(  971):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1682] from screen [on:0 period:-972416357] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-972416355] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971):  get link layer stats 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1327): environment dirty rate=14 [7][1][0]
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
,E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  971): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
,E/WifiStateMachine(  971): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=3.63 txretriesrate=0.00 rxrate=4.43 userTriggerdPenalty0
E/WifiStateMachine(  971):  good link -> stuck count =0
E/WifiStateMachine(  971):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  971):  isHighRSSI       ---> score=61
E/WifiStateMachine(  971): handleMessage: X
D/WifiWatchdogStateMachine(  971): RSSI current: 3 new: -63, 3,
,D/libc    ( 4369): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4369): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4369): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4369): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4369): Sending checkin request (8411 bytes),
,I/CheckinRequestBuilder( 4369): Checkin reason type: 11 attempt count: 1,
,I/ActivityManager(  971): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4369): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/CheckinRequestBuilder( 4369): awaiting user notification for token
,D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/CheckinRequestBuilder( 4369): Classify the device as Phone.
,I/CheckinTask( 4369): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4369): Checking schedule, now: 1455021497602 next: 1455558329597
,I/CheckinService( 4369): active receiver: disabled
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4369, uid=10024, userID:0
,D/PMS     (  971): releaseWL(3d724a46): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6542 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/PhoneMonitor( 6542): Register our PhoneStateListener
,V/SetupWizard( 6542): Connected to Gservices successfully,
,D/PhoneMonitor( 6542): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6542): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/ChimeraCfgMgr( 4369): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     (  971): Explicit concurrent mark sweep GC freed 25944(1341KB) AllocSpace objects, 7(268KB) LOS objects, 33% free, 19MB/28MB, paused 1.619ms total 170.539ms
,I/Kids    ( 4369): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=238
E/WifiTrafficPoller(  971): notifying of data activity 3
,D/WIFI_ICON( 1222): WifiActivity: 3
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/GCM     ( 1962): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=239
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  971): notifying of data activity 1
,E/WifiDataStallTracker(  971): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  971): updateDataStallInfo: mDataStallTxRxSum={txSum=154 rxSum=133} preTxRxSum={txSum=138 rxSum=121}
D/WifiDataStallTracker(  971): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  971): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=241
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,E/WifiStateMachine(  971): handleMessage: E msg.what=131155
,E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-972413347] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-972413345] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971):  get link layer stats 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1327): environment dirty rate=33 [9][3][0],
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiConfigStore(  971): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  971): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=6.32 txretriesrate=0.00 rxrate=7.71 userTriggerdPenalty0
E/WifiStateMachine(  971):  good link -> stuck count =0
E/WifiStateMachine(  971):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  971):  isHighRSSI       ---> score=65
E/WifiStateMachine(  971): handleMessage: X
,D/WifiWatchdogStateMachine(  971): RSSI current: 3 new: -63, 3
,I/HtcModeClient( 3181): handler message = 4011,
E/HtcModeClient( 3181): Check connection and retry 12 times.
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=244
,D/Process (  971): killProcessQuiet, pid=6209
,I/ActivityManager(  971): Killing 6209:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 6209
,D/Process (  971): killProcessQuiet, pid=6178
I/ActivityManager(  971): Killing 6178:com.htc.providers.settings:remote/u0a13 (adj 15): empty #18
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 6178
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=249
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=249
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  971): notifying of data activity 0
,E/WifiStateMachine(  971): handleMessage: E msg.what=131155,
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-972410324] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-972410323] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  971):  get link layer stats 0
,W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1327): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  971): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  971): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=3.16 txretriesrate=0.00 rxrate=7.86 userTriggerdPenalty0
E/WifiStateMachine(  971):  good link -> stuck count =0
E/WifiStateMachine(  971):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  971):  isHighRSSI       ---> score=61
E/WifiStateMachine(  971): handleMessage: X
D/WifiWatchdogStateMachine(  971): RSSI current: 3 new: -64, 3
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7
,D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=250
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  971): notifying of data activity 1
,E/WifiDataStallTracker(  971): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  971): updateDataStallInfo: mDataStallTxRxSum={txSum=154 rxSum=133} preTxRxSum={txSum=154 rxSum=133}
D/WifiDataStallTracker(  971): updateDataStallInfo: NONE
D/WifiDataStallTracker(  971): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=253
,D/AccTypeManager( 1753): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/PMS     (  971): acquireWL(3097300): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6293 10112 null
,I/Prism.ItemManager( 1626): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,D/AccTypeManager( 1753): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1626): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1626): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/ResourcesManager( 1565): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/SystemReader(  971): Cannot find grip_rejection_width, use default value instead
,W/ResourcesManager(  971): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1753): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,I/[PluginManager]RegisterService( 1532): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1532): handle notify Blinkfeed plugin client changed
,D/PMS     (  971): releaseWL(3097300): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6293): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6293): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PhoneApp( 1565): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1753): Unsupported attribute readOnly
,D/PackageBroadcastService( 4369): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4369): Null package name or gms related package.  Ignoreing.
,D/PMS     (  971): acquireWL(de8d0bf): PARTIAL_WAKE_LOCK  Icing 0x1 4369 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): acquireWL(232f02ea): PARTIAL_WAKE_LOCK  AsyncService 0x1 6028 10167 null,
D/PMS     (  971): releaseWL(232f02ea): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  971): acquireWL(39a70f51): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6028 10167 null
,I/Icing   ( 4369): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  971): releaseWL(39a70f51): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
I/UpdateIcingCorporaServi( 5870): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/HtcModeClient( 3181): handler message = 4011,
,E/HtcModeClient( 3181): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3181): Don't start project servcice
D/PMS     (  971): releaseWL(de8d0bf): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcModeClient( 3181): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3181): connectState: CONNECTION_READY = false
D/SilentMusic( 3181): call stop
D/HtcModeClient( 3181): close connection
W/HtcModeClient( 3181): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3181): read the terminate packet, so break
,I/UpdateIcingCorporaServi( 5870): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
,W/PackageManager(  971): Unable to load service info ResolveInfo{1aa8e345 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  971): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  971): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  971): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  971): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  971): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  971): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  971): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  971): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  971): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  971): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  971): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1795): DISABLE
,I/GCoreNlp( 1795): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  971): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/PMS     (  971): acquireWL(3996fa2d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(3996fa2d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(1c0ddcdc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1795 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): releaseWL(1c0ddcdc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/LocationProviderProxy(  971): applying state to connected service,
D/LocationProviderProxy(  971): applying state to connected service
,D/PMS     (  971): acquireWL(195a41e5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(27a004ba): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(195a41e5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(27a004ba): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=254,
,E/WifiStateMachine(  971): handleMessage: E msg.what=131155
,E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-972407301] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-972407300] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971):  get link layer stats 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1327): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
,E/WifiConfigStore(  971): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  971): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.58 txretriesrate=0.00 rxrate=7.93 userTriggerdPenalty0
E/WifiStateMachine(  971):  good link -> stuck count =0
E/WifiStateMachine(  971):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  971):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  971): RSSI current: 3 new: -64, 3
E/WifiStateMachine(  971): handleMessage: X
,D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=257
,I/Prism.ItemManager( 1626): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1626): loadItems() com.htc.launcher.pageview.WidgetManager@4a2d325 +
I/Prism.WidgetManager( 1626): onLoadItems() +
,I/ActivityManager(  971): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6581 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  971): acquireWL(26edf6b): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10076}
,V/AlarmManager(  971): sending alarm PendingIntent{909eac8: PendingIntentRecord{3d721761 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455021506917, Int=60000
D/PMS     (  971): releaseWL(26edf6b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6581): SMSBackupAgentService started
,D/SMSBackup( 6581): Checking restore status
,D/SMSBackup( 6581): Restore complete
,D/SMSBackup( 6581): cancelCheckAlarm
,D/SMSBackup( 6581): SMSBackupAgentService completed: completed in 0.0 seconds,
,E/Prism.WidgetManager( 1626): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1626): onLoadItems() -
I/Prism.ItemManager( 1626): loadItems() com.htc.launcher.pageview.WidgetManager@4a2d325 -,
,D/PhoneApp( 1565): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1565): -- N1 =0,
D/PhoneApp( 1565): -- N2 =0
,D/PhoneApp( 1565): -- N3 =0,
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=257
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  971): notifying of data activity 0,
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=257
,E/WifiStateMachine(  971): handleMessage: E msg.what=131155,
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-972404277] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-972404276] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971):  get link layer stats 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1327): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
,D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiConfigStore(  971): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  971): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.79 txretriesrate=0.00 rxrate=3.96 userTriggerdPenalty0
E/WifiStateMachine(  971):  good link -> stuck count =0,
E/WifiStateMachine(  971):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  971):  isHighRSSI       ---> score=61
E/WifiStateMachine(  971): handleMessage: X
D/WifiWatchdogStateMachine(  971): RSSI current: 3 new: -63, 3
,E/WifiDataStallTracker(  971): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  971): updateDataStallInfo: mDataStallTxRxSum={txSum=154 rxSum=133} preTxRxSum={txSum=154 rxSum=133}
D/WifiDataStallTracker(  971): updateDataStallInfo: NONE
D/WifiDataStallTracker(  971): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,D/PMS     (  971): acquireWL(371a0747): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{1000},
V/AlarmManager(  971): sending alarm PendingIntent{5f469f1: PendingIntentRecord{22beb9d6 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455021509675, Int=20000
,D/WifiDisplayAdapter(  971): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  971):     Client/Owner: Client
D/WifiDisplayAdapter(  971):     GroupId: 
,D/WifiDisplayAdapter(  971):     Passphrase: 
D/WifiDisplayAdapter(  971):     SessionId: 0
D/WifiDisplayAdapter(  971):     IP Address: }
E/WifiStateMachine(  971): WiFiStateMachine SCAN ALARM
D/PMS     (  971): releaseWL(371a0747): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  971): handleMessage: E msg.what=131143
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):0 dur:85 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=4.0 list=2412 [on:0 tx:0 rx:0 period:592] from screen [on:0 period:-972403666]
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:85 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=4.0 list=2412 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-972403666]
E/WifiStateMachine(  971): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.79 rxSuccessRate=3.96 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-63
,E/WifiStateMachine(  971): WifiStateMachine CMD_START_SCAN with age=72085 interval=60000 maxinterval=300000
E/WifiStateMachine(  971): WifiStateMachine CMD_START_SCAN try full band scan age=72085 interval=60000 maxinterval=300000
E/WifiStateMachine(  971): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  971): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1327): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1327): wpa_supplicant_scan enter
D/wpa_supplicant( 1327): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1327): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1327): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1327): WPS:  * Request Type
D/wpa_supplicant( 1327): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1327): WPS:  * UUID-E
D/wpa_supplicant( 1327): WPS:  * Primary Device Type
D/wpa_supplicant( 1327): WPS:  * RF Bands (3)
D/wpa_supplicant( 1327): WPS:  * Association State
D/wpa_supplicant( 1327): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1327): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1327): WPS:  * Manufacturer
D/wpa_supplicant( 1327): WPS:  * Model Name
,D/wpa_supplicant( 1327): WPS:  * Model Number
D/wpa_supplicant( 1327): WPS:  * Device Name
D/wpa_supplicant( 1327): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1327): P2P: * P2P IE header
D/wpa_supplicant( 1327): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1327): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1327): wlan0: Add radio work 'scan'@0x559e8fe680
D/wpa_supplicant( 1327): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1327): wlan0: Starting radio work 'scan'@0x559e8fe680 after 0.000052 second wait
D/wpa_supplicant( 1327): wlan0: nl80211: scan request
D/wpa_supplicant( 1327): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1327): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1327): wlan0: nl80211: Scan trigger
,D/wpa_supplicant( 1327): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1327): wlan0: Own scan request started a scan in 0.000113 seconds
I/wpa_supplicant( 1327): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  971): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  971): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  971): [1,455,021,509,682 ms] noteScanstart no scan source
E/WifiStateMachine(  971): handleMessage: X
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=262
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  971): notifying of data activity 1
,D/Process (  971): killProcessQuiet, pid=3181,
I/ActivityManager(  971): Killing 3181:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 3181,
,D/Process (  971): killProcessQuiet, pid=6256
,I/ActivityManager(  971): Killing 6256:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 7
,D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=262
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  971): notifying of data activity 0
E/JavaBinder(  971): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager(  971): Recipient 6256
D/WifiService(  971): Client connection lost with reason: 4
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=262
,D/wpa_supplicant( 1327): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1327): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1327): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1327): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1327): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1327): wlan0: Scan completed in 2.094454 seconds
D/wpa_supplicant( 1327): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1327): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1327): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1327): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1327): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
I/wpa_supplicant( 1327): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1327): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1327): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
D/wpa_supplicant( 1327): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1327): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1327): wlan0: Scan-only results received
D/wpa_supplicant( 1327): wlan0: Radio work 'scan'@0x559e8fe680 done in 2.095693 seconds
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiMonitor(  971): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  971): handleMessage: E msg.what=147461
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  971): processMsg: ConnectModeState
E/WifiStateMachine(  971):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  971): processMsg: DriverStartedState
E/WifiStateMachine(  971):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  971): processMsg: SupplicantStartedState
E/WifiStateMachine(  971):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  971): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1327): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  971): [1,455,021,511,781 ms] noteScanEnd no scan source
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1327): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  971): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3e51dcd sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  971): NG7005g c0:ff:d4:d3:aa:4a rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  971): NG700 c0:ff:d4:d3:aa:48 rssi=-63 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,E/WifiConfigStore(  971): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  971): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  971):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-63 freq=2412
,E/WifiAutoJoinController (  971): Gonzos 38:f8:89:11:e9:11 rssi=-78 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  971): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  971): ageScanResultsOut delay 40000 size 4 now 1455021511784
E/WifiAutoJoinController (  971): newSupplicantResults size=4 known=1 true
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1327): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  971): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  971): ssid=NG700
E/WifiAutoJoinController (  971): id=0
E/WifiAutoJoinController (  971): mode=station
E/WifiAutoJoinController (  971): pairwise_cipher=CCMP
E/WifiAutoJoinController (  971): group_cipher=CCMP
E/WifiAutoJoinController (  971): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  971): wpa_state=COMPLETED
E/WifiAutoJoinController (  971): ip_address=192.168.1.130
E/WifiAutoJoinController (  971): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  971): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  971): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  971): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  971): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-63,-127) num=(1,0)
E/WifiAutoJoinController (  971): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  971): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-63 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  971): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  971): Done attemptAutoJoin status=0
E/WifiConfigStore(  971):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  971): handleMessage: X
,D/WifiManager( 1795): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,I/PMS     (  971): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  971): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3b7599ec
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  971): disable: get sensor name = Accelerometer Sensor
D/ActivityManager(  971): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{c36eb74 #7 A=.Prism U=0 sz=1}
,W/PMS     (  971): mWirelessDisplayManager is null
W/PMS     (  971): mWirelessDisplayManager is still null
W/SensorService(  971): pid=971, uid=1000
W/SensorService(  971): Active sensors: size = 4
W/SensorService(  971): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  971): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  971): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/PMN     (  971): goingToSleep
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3b7599ec, eanble = 0, strlen(mName) = 91
I/PMS     (  971): Sleeping (uid 1000)...
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 2
,D/XAN-DPS (  971): prepareColorFade 1
W/SensorService(  971): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3d808ad2
W/SensorService(  971): Listener[1] = com.htc.smartdim.sensor_eye@30059d9
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  971): acquireWL(3ed7c89d): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 971 1000 null
W/PMN     (  971): goingToSleep done
,W/HtcLockScreen( 1222): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/Adreno-EGL(  971): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  971): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  971): Build Date: 03/09/15 Mon
I/Adreno-EGL(  971): Local Branch: 
I/Adreno-EGL(  971): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  971): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  971):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  971): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6605 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,I/FeedHostManager( 1626): [onPause]
D/AlarmManager(  971): ACTION_SCREEN_ON
I/FeedProviderManager( 1626): onPause
I/AlarmManager(  971): [AlarmQueuing] recover blocked alarms
I/FeedHostManager( 1626): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2ddf0359
I/AlarmManager(  971): [AlarmQueuing] done recovering
I/SocialFeedProvider( 1626): +onPause
I/AlarmManager(  971): [AlarmQueuing] recover EPS screen off blocked alarms
I/SocialFeedProvider( 1626): -onPause
I/AlarmManager(  971): [AlarmQueuing] done EPS screen off alarm recovering
,W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
E/WifiTrafficPoller(  971): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/PMS     (  971): releaseWL(3ed7c89d): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/WifiTrafficPoller(  971):  packet count Tx=172 Rx=262
,E/WifiDataStallTracker(  971): ENABLE_DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  971): updateDataStallInfo: mDataStallTxRxSum={txSum=154 rxSum=133} preTxRxSum={txSum=154 rxSum=133}
,D/WifiDataStallTracker(  971): updateDataStallInfo: NONE
D/WifiDataStallTracker(  971): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  971): handleMessage: E msg.what=131167
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  971): processMsg: ConnectModeState
E/WifiStateMachine(  971):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  971): processMsg: DriverStartedState
E/WifiStateMachine(  971):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
D/WifiDisplayAdapter(  971): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  971):     Client/Owner: Client
D/WifiDisplayAdapter(  971):     GroupId: 
D/WifiDisplayAdapter(  971):     Passphrase: 
D/WifiDisplayAdapter(  971):     SessionId: 0
D/WifiDisplayAdapter(  971):     IP Address: }
E/WifiStateMachine(  971): processMsg: SupplicantStartedState
E/WifiStateMachine(  971):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  971):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1327): SET_SCREEN_ON:On
I/wpa_supplicant( 1327): htc_wext_set_keepalive +
I/wpa_supplicant( 1327): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1327): getPrivFuncNum +	
I/wpa_supplicant( 1327): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1327): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1327): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1327): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1327): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  971): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  971): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  971): handleScreenStateChanged Exit: true
,V/SRS_Proc(  406): ParamSet string: screen_state=on
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131154
E/audio_a2dp_hw(  406): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiController(  971): handleMessage: E msg.what=155650
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,D/NetworkPolicy(  971): updateScreenOn: false
V/NetworkPolicy(  971): updateIfacesLocked()
I/wpa_supplicant( 1327): environment dirty rate=0 [0][0][0]
D/NetworkManagementService(  971): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  971): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  971): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131127
E/WifiStateMachine(  971): processMsg: ConnectedState
,E/WifiStateMachine(  971):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  971): processMsg: ConnectModeState
E/WifiStateMachine(  971):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131129
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  971): processMsg: ConnectModeState
E/WifiStateMachine(  971):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1327): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1327): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  971): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=34 dispatchEvent: BLACKLIST CLEAR 
,E/WifiStateMachine(  971): handleMessage: X
,E/WifiStateMachine(  971): handleMessage: E msg.what=131155
E/WifiStateMachine(  971): processMsg: ConnectedState
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/GpsLocationProvider(  971): receive broadcast intent, action: android.intent.action.SCREEN_ON
E/WifiStateMachine(  971):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:2420] from screen [on:0 period:-972401242] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
,E/WifiStateMachine(  971):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-972401237] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  971): handleMessage: X
,I/IntentController( 1222): receive(android.intent.action.SCREEN_ON,1,false)
,W/ResourcesManager( 6605): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/PMS     (  971): acquireWL(38ed5199): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(13e8c5e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,I/CalendarProvider2( 6605): Created com.android.providers.calendar.CalendarAlarmManager@25ede9b(com.htc.providers.calendar.HtcCalendarProvider@311a3238)
,D/CalendarProvider2( 6605): wait start:true
D/XAN-DPS (  971): prepareColorFade done
,D/XAN-DPS (  971): setBrightness to 0
D/PMS     (  971): releaseWL(38ed5199): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/SensorManager(  971): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@3d808ad2
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  971): disable: get sensor name = CM32181 Light sensor
,I/DisplayManagerService(  971): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  971): Display changed displayId=0
D/DotMatrix( 1334): [EventService]  onDisplayChanged: 0
,D/DotMatrix( 1334): [EventService] mbHDMIConnect: false, mCoverOn:false
W/SensorService(  971): pid=971, uid=1000
W/SensorService(  971): Active sensors: size = 3
W/SensorService(  971): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  971): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@3d808ad2, eanble = 0, strlen(mName) = 67
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  971): Listener[0] = com.htc.smartdim.sensor_eye@30059d9
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/CalendarProvider2( 6605): wait end:false
,I/ActivityManager(  971): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6634 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/art     ( 1795): Explicit concurrent mark sweep GC freed 17164(945KB) AllocSpace objects, 7(140KB) LOS objects, 46% free, 4MB/8MB, paused 1.135ms total 91.441ms,
,E/DataBuffer( 1795): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@257c6894)
D/PMS     (  971): releaseWL(13e8c5e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/SensorManager( 1222): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@f6e3a8c, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
D/AlarmManager(  971): ACTION_SCREEN_OFF
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
I/AlarmManager(  971): [AlarmQueuing] screen off now: 
W/SensorService(  971): enable: get sensor name = hTC Gesture Motion HIDI
I/AlarmManager(  971): [AlarmQueuing] data connection: true
I/AlarmManager(  971): [AlarmQueuing] wifi connection: true
E/WifiTrafficPoller(  971): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  971): stopDataStallAlarm 
D/WifiDisplayAdapter(  971): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  971):     Client/Owner: Client
D/WifiDisplayAdapter(  971):     GroupId: 
D/WifiDisplayAdapter(  971):     Passphrase: 
D/WifiDisplayAdapter(  971):     SessionId: 0
D/WifiDisplayAdapter(  971):     IP Address: }
E/WifiDataStallTracker(  971): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  971): handleMessage: E msg.what=131167
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
E/WifiStateMachine(  971):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  971): processMsg: ConnectModeState
E/WifiStateMachine(  971):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  971): processMsg: DriverStartedState
E/WifiStateMachine(  971):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  971): processMsg: SupplicantStartedState
,E/WifiStateMachine(  971):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  971):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1327): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1327): SET_SCREEN_ON:Off
I/wpa_supplicant( 1327): htc_wext_set_keepalive +
I/wpa_supplicant( 1327): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1327): getPrivFuncNum +	
I/wpa_supplicant( 1327): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1327): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1327): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1327): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1327): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  971): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  971): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  971): handleScreenStateChanged Exit: false
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131154
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  971): processMsg: L2ConnectedState
V/SRS_Proc(  406): ParamSet string: screen_state=off
W/SensorService(  971): pid=1222, uid=10041
W/SensorService(  971): Active sensors: size = 4
W/SensorService(  971): Accelerometer Sensor (handle=0x00000000, connections=1)
E/WifiStateMachine(  971):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
W/SensorService(  971): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
E/WifiStateMachine(  971): handleMessage: X
E/audio_a2dp_hw(  406): adev_set_parameters: ERROR: set param called even when stream out is null
W/SensorService(  971): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@f6e3a8c, eanble = 1, strlen(mName) = 56
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  971): Listener[0] = com.htc.smartdim.sensor_eye@30059d9
W/SensorService(  971): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@f6e3a8c
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiController(  971): handleMessage: E msg.what=155651
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,D/NetworkPolicy(  971): updateScreenOn: false
V/NetworkPolicy(  971): updateIfacesLocked()
,D/NetworkManagementService(  971): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/ContextImpl( 6634): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  971): Setting HAL interactive mode to false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  971): Setting HAL interactive mode to false done
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): Setting HAL auto-suspend mode to true
D/SurfaceControl(  971): Excessive delay in setPowerMode(): 294ms
D/PMS     (  971): Setting HAL auto-suspend mode done
,W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006,
,I/InputMethodManagerService(  971): screenObserver, isScreenOn=false
,D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
D/DotMatrix( 1334): [EventService] getTotalRam: 1842 Mb
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,D/HABCtrl (  971): TPE algorithm. remove timeout.
D/PMS     (  971): OOBE c monitor 11
D/GpsLocationProvider(  971): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/InputMethodManagerService(  971): Disable input method client, pid=1626
,W/ContextImpl( 6634): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  971): acquireWL(207d2c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(207d2c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  971): updateBatteryInfo
D/NfcService( 1579): ScreenObserver: OFF
,D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
D/NfcService( 1579): applyRouting - 0
,D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PMS     (  971): runPSCheck
D/WifiController(  971): handleMessage: E msg.what=155652
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): processMsg: DeviceActiveState
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,D/PMS     (  971): acquireWL(35d4c90e): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1579 1027 null
,D/NfcService( 1579): applyRouting -2
D/NfcService( 1579): applyRouting
D/NfcService( 1579): Ignore this applyRouting...
D/PMS     (  971): releaseWL(35d4c90e): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PowerUsageList:PowerUsageHelper( 6634): MY_DEBUG = false
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  971): << updateStatus
,D/SmartSyncUtils( 6634): isEpsOn(), nState = 0
,I/IntentController( 1222): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1565): start background delete task...
,D/ContactMessageStore( 1565): size: 0 , 0
D/ContactMessageStore( 1565): Background delete complete
,D/PMS     (  971): acquireWL(fb00f2f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1795 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): releaseWL(fb00f2f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(3ff0f93c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(25f296c5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6634 1000 null
D/PMS     (  971): releaseWL(3ff0f93c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  971): releaseWL(25f296c5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,I/InputManager(  971): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1222): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/SmartDim(  971): Init customizeScreenOffDelayClass error
,I/RemoteViews( 1222): setHTCTheme(com.htc.updater,true,33751145)
W/ContextImpl( 6634): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6634): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/RemoteViews( 1222): apply : com.htc.updater 1 13 0 36
,D/SmartSyncUtils( 6634): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6634): isEpsOn(), nState = 0
,W/ContextImpl( 6634): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6634): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 ,
I/SensorManager(  971): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@30059d9,
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  971): disable: get sensor name = Accelerometer Sensor
W/SensorService(  971): pid=971, uid=1000
W/SensorService(  971): Active sensors: size = 3
W/SensorService(  971): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@30059d9, eanble = 0, strlen(mName) = 35
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  971): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@f6e3a8c
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  971): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  971): pid=971, uid=1000
W/SensorService(  971): Active sensors: size = 2
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@30059d9, eanble = 0, strlen(mName) = 35
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  971): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@f6e3a8c
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  971): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@30059d9
D/TetherSettings( 5932): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
E/ActivityThread(  971): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@395c8f9e that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  971): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@395c8f9e that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  971): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  971): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  971): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  971): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  971): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  971): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  971): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  971): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  971): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  971): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  971): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  971): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  971): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  971): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  971): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  971): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  971): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  971): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  971): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/        ( 5932): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5932): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5932): Cust_ConnectToPC   : spcsc>false
D/        ( 5932): Cust_ConnectToPC   : IPT>true
D/        ( 5932): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5932): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5932): Index of the first 1 = -1
,W/ContextImpl( 5932): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5932): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,I/ClockController( 1222): stop clock update:screen off,
,I/ActivityManager(  971): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6670 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,W/Settings( 5932): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SmartNS_Utility( 5932): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 5932): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false,
D/SmartNS_NSReceiver( 5932): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5932): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 5932): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,I/PowerUsageList:PowerUsageHelper( 6634): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6634): gen(), null == sipper.uidObj, userId = 0,
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL false Token 13 num clients 6
,D/Process (  971): killProcessQuiet, pid=6001
,I/ActivityManager(  971): Killing 6001:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6634): getMobilePolicyEnabled, result = true
,D/WifiService(  971): New client listening to asynchronous messages
E/WifiTrafficPoller(  971): ADD_CLIENT: 7
,I/ActivityManager(  971): Recipient 6001
,D/PowerUsageList:PowerUsageHelper( 6634): MY_DEBUG = false,
,D/Process (  971): killProcessQuiet, pid=5784
I/ActivityManager(  971): Killing 5784:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  971): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,I/ActivityManager(  971): Recipient 5784
,I/CalendarProvider2( 6605): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6605): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 6360): ---------------------------------------------------
D/ProviderChangeReceiver( 6360): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!,
,D/HtcAlertService( 6360): start to updateAlertNotification!
,D/Process (  971): killProcessQuiet, pid=6324
I/ActivityManager(  971): Killing 6324:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 6324
,D/HtcAlertService( 6360): No fired or scheduled alerts
,D/HtcAlertUtils( 6360): -- cancelReminderNotification --
,D/HtcAlertUtils( 6360): broadcastExistReminder!
,D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  971): releaseWL(1b001744): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,E/WifiDataStallTracker(  971): DATA_MONITOR_POLL false Token 3
,E/WifiStateMachine(  971): handleMessage: E msg.what=131155
E/WifiStateMachine(  971): processMsg: ConnectedState
E/WifiStateMachine(  971):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2987] from screen [on:0 period:-972398249] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  971): processMsg: L2ConnectedState
,E/WifiStateMachine(  971):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-972398247] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  971): handleMessage: X
,D/HtcUPManager( 1222): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  971): DATA_MONITOR_POLL false Token 3,
,D/ContactMessageStore( 1565): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1565): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  971): Killing 5537:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
D/Process (  971): killProcessQuiet, pid=5537
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5537
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  971): acquireWL(22eada41): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{2b5808b: PendingIntentRecord{2af44568 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=140684, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{3bc4ebe6: PendingIntentRecord{c9cb527 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143261, Int=0
,D/PMS     (  971): releaseWL(22eada41): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data,
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  971): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  971): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  971): acquireWL(211533d4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 971 1000 null
,D/libc    (  971): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  971): [NET] android_getaddrinfofornet-, err=8
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  971): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  971): [NET] android_getaddrinfo_proxy+
D/libc    (  971): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  971): [NET] android_getaddrinfo_proxy-, success
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  971): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  971): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  971): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  971): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  971):  [handleDownloadXtraData]inject done.
D/PMS     (  971): acquireWL(1c7bb940): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 971 1000 null
D/PMS     (  971): releaseWL(211533d4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  971): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  971): releaseWL(1c7bb940): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  971): acquireWL(1a9f9079): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
,D/UsbnetService(  971): BroadcastReceiver::onReceive+
I/BatteryService(  971): n_update end
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/PMS     (  971): releaseWL(1a9f9079): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): battery changed pluggedType: 2
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  971): handleMessage: E msg.what=155652
D/HtcPowerSaver(  971): updateBatteryInfo
,D/WifiController(  971): processMsg: DeviceActiveState
D/PMS     (  971): runPSCheck
D/WifiController(  971): processMsg: StaEnabledState
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): processMsg: DefaultState
,I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): handleMessage: X
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1565): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  971): acquireWL(2a8b91be): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{1ac9221f: PendingIntentRecord{3303296c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455021565683, Int=0
D/PMS     (  971): acquireWL(247fbb35): PARTIAL_WAKE_LOCK  *backup* 0x1 971 1000 null
V/AlarmManager(  971): sending alarm PendingIntent{356b0bca: PendingIntentRecord{467c13b com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190281, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{2baf7058: PendingIntentRecord{9fdd5b1 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=196602, Int=0
,D/PMS     (  971): acquireWL(10161a96): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(2a8b91be): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  971): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  971): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  971): releaseWL(247fbb35): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  971): acquireWL(3b873617): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(10161a96): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  971): releaseWL(3b873617): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): acquireWL(cc889e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): releaseWL(cc889e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): acquireWL(1e9de66e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(1e9de66e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(c84d10f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(cd9c59c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(1ec5fb7a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(c84d10f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1962): Vacuum at: now=1455021596229 tag=VacuumService,
,D/PMS     (  971): releaseWL(cd9c59c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): acquireWL(238b9f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1962): Using platform SSLCertificateSocketFactory
,D/PMS     (  971): releaseWL(238b9f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): acquireWL(183e8d21): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(183e8d21): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1962): No account for auth token provided,
,D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1962): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1962): [NET] android_getaddrinfo_proxy+
D/libc    ( 1962): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1962): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1962): No account for auth token provided,
,W/Uploader( 1962): No account for auth token provided
,W/Uploader( 1962):  no longer exists, so no auth token.,
,W/Uploader( 1962): No account for auth token provided,
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1962): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1962): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1962): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1962): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1962): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1962): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1962): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 4 40
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true,
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/Uploader( 1962): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1962): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1962): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1962): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1962): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1962): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1962): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1962): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,I/art     (  971): Explicit concurrent mark sweep GC freed 50355(2MB) AllocSpace objects, 6(1236KB) LOS objects, 33% free, 19MB/28MB, paused 2.130ms total 192.532ms,
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1962): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1962): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1962): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1962): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1962): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1962): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1962): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1962): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,D/PMS     (  971): releaseWL(1ec5fb7a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): acquireWL(98133ce): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(98133ce): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): acquireWL(92002ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(92002ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1532): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2c67bc2
,I/ActivityManager(  971): Killing 5417:com.htc.mediamanager/u0a28 (adj 15): empty #17
,D/Process (  971): killProcessQuiet, pid=5417
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5417
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  971): acquireWL(176041fc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  971): n_update end
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): releaseWL(176041fc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PMS     (  971): runPSCheck
D/WifiController(  971): handleMessage: E msg.what=155652
D/HtcPowerSaver(  971): Checking...
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
,D/WifiController(  971): handleMessage: X
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1327): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1327): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1327): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  971): acquireWL(cff1085): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(cff1085): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  971): updateBatteryInfo
,D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PMS     (  971): runPSCheck
D/WifiController(  971): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): processMsg: DeviceActiveState
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  971): acquireWL(b80beda): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{2b5808b: PendingIntentRecord{2af44568 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=200684, Int=0
D/HtcSystemUPManager(  971): UPAlarmListener onAlarmArrival
V/AlarmManager(  971): sending alarm PendingIntent{1693df0b: PendingIntentRecord{2586a786 android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=353163, Int=0
D/HtcSystemUPManager(  971): UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1455021758200, last = 1455000152478, freq = 21600000
V/AlarmManager(  971): sending alarm PendingIntent{386d81e8: PendingIntentRecord{5a53001 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455021717051, Int=1800000
,V/AlarmManager(  971): sending alarm PendingIntent{261f60e7: PendingIntentRecord{248cd494 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1455021758196, Int=0,
D/HtcSystemUPManager(  971): AlarmScheduler_INEXACT [onReceive] end
D/HtcSystemUPManager(  971): com.htc.upm.AlarmScheduler$SchedulerBase$1@1a12297c
,D/PMS     (  971): acquireWL(3733cb3d): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4369 10024 WorkSource{10024 com.google.android.gms}
,D/HtcSystemUPManager(  971): HtcSystemUPHandler sendService() has been called
,D/HtcSystemUPManager(  971): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
D/HtcSystemUPManager(  971): HtcSystemUPHandler send to UPService takes: 1 ms
,D/PMS     (  971): releaseWL(b80beda): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1222): Weather sync is On
D/PMS     (  971): acquireWL(36f72483): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4369 10024 WorkSource{10024 com.google.android.gms}
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  971): releaseWL(3733cb3d): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4369): Aggregate from 1455021495352 (log), 1455019916999 (data)
,I/art     ( 1626): Background sticky concurrent mark sweep GC freed 66207(4MB) AllocSpace objects, 4(400KB) LOS objects, 11% free, 32MB/37MB, paused 10.131ms total 79.997ms,
,D/PMS     (  971): releaseWL(36f72483): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1962): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1962): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1962): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1962): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1962): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1962): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1962): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5958): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5958): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5958): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5958): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5958): ,	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5958): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5958): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1334): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1334): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40,
,W/System  ( 5958): Ignoring header User-Agent because its value was null.
,D/libc    ( 5958): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5958): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5958): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5958): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5958): [NET] android_getaddrinfo_proxy+
D/libc    ( 5958): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5958): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  971): acquireWL(29358f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
,D/PMS     (  971): releaseWL(29358f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  971): updateBatteryInfo
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  477): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1565): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1565): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1565): sku_id=118
D/ContactMessageStore( 1565): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1565): start background delete task...
,D/ContactMessageStore( 1565): size: 0 , 0
,D/ContactMessageStore( 1565): Background delete complete
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
D/PMS     (  971): acquireWL(c8ec7a9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  971): n_update end
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): releaseWL(c8ec7a9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): handleMessage: E msg.what=155652
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  971): acquireWL(2f56b12e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
,I/bt-btm  ( 3082): Received oneshot timer event complete,
V/AlarmManager(  971): sending alarm PendingIntent{2b5808b: PendingIntentRecord{2af44568 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=380684, Int=0
I/bt-btm  ( 3082): btm_ble_timeout
V/AlarmManager(  971): sending alarm PendingIntent{979a4cf: PendingIntentRecord{201c6e5c com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941902, Int=0
I/bt-btm  ( 3082): btm_gen_resolvable_private_addr
,D/PMS     (  971): acquireWL(ce33565): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3082 1002 null
,D/bt-btm  ( 3082): btm_ble_rand_enc_complete
I/bt-btm  ( 3082): btm_gen_resolve_paddr_low
D/bt-smp  ( 3082): smp_encrypt_data
W/bt-smp  ( 3082): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3082): Plain text(LSB ~ MSB) = ad fb 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3082): Encrypted text(LSB ~ MSB) = 60 97 59 cd e0 9b 41 10 18 aa 38 2e cc 95 53 34 
I/bt-btm  ( 3082): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3082): Stopping oneshot timer
D/bt-btm  ( 3082): Starting oneshot timer type:103 timeout:900s
,I/ActivityManager(  971): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6711 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  971): sending alarm PendingIntent{2820b23a: PendingIntentRecord{1f15beeb com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1455022027104, Int=0
,D/PMS     (  971): releaseWL(2f56b12e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,E/cutils-trace( 6732): Error opening trace file: Permission denied (13),
I/dex2oat ( 6732): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,I/dex2oat ( 6732): dex2oat: override thread count:4
,I/dex2oat ( 6732): dex2oat took 717.837ms (threads: 4)
,I/PushClient( 6711): ApplicationMonitor {1c404e4d}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6711): ApplicationMonitor {1c404e4d}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6711): ApplicationMonitor {1c404e4d}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6711): ApplicationMonitor {1c404e4d}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6711): ApplicationMonitor {1c404e4d}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6711): ApplicationMonitor {1c404e4d}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6711): ApplicationMonitor {1c404e4d}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6711): ApplicationMonitor {1c404e4d}: logBasicAppInfo(): Htc_DEBUG_flag:          false
D/PMS     (  971): releaseWL(ce33565): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/PushClient( 6711): ApplicationMonitor {1c404e4d}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/PushClient( 6711): PnsModel {155c39e4}: update(): Update registration caused by: alarm,
,I/PushClient( 6711): PnsConfigModel {f70a48b}: <init>(): Use dm-client for provisioning.
,W/System.err( 6711): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6711): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6711): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6711): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  971): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6740 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6740): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6740 dbg=false s=true
,I/DeviceManagement( 6740): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6740): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6740): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6740): WorkflowService: Starting workflow service
,I/DeviceManagement( 6740): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@155c39e4] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6740): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6740): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6740): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6740): SessionStateController: Checking invariants...
,I/DeviceManagement( 6740): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6740): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6740): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6740): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@155c39e4],
,I/DeviceManagement( 6740): WorkflowService: Stopping workflow service,
,D/Process (  971): killProcessQuiet, pid=6441
I/ActivityManager(  971): Killing 6441:com.test.thalitest/u0a366 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6711): PnsModel {155c39e4}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  971): Recipient 6441,
,E/InputEventReceiver( 1410): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{26a7d979 uid 10366 pid 6441} (c)'
,D/Process (  971): killProcessQuiet, pid=6542
I/ActivityManager(  971): Killing 6542:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 6542
,D/PMS     (  971): acquireWL(2206268c): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10024}
V/AlarmManager(  971): sending alarm PendingIntent{38a541d5: PendingIntentRecord{382a1dea com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937730, Int=0
D/PMS     (  971): acquireWL(c0838db): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(c0838db): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  971): sending alarm PendingIntent{a17a9ba: PendingIntentRecord{1a6206b android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806289, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{35351f78: PendingIntentRecord{38ebf941 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455022366490, Int=0
,W/ContextImpl( 6634): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  971): releaseWL(2206268c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6634): MY_DEBUG = false,
,D/PowerUsageService( 6634): repeat time = 1455023266534,
,I/PowerUsageList:PowerUsageHelper( 6634): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6634): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  971): acquireWL(35842eb6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): acquireWL(264787b7): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,I/GCM     ( 4369): Message from null null,
E/GCM     ( 4369): Dropping message from null
,D/PMS     (  971): releaseWL(264787b7): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1962): Message class com.google.f.a.a.i
,D/PMS     (  971): releaseWL(35842eb6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(658bb24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  971): releaseWL(658bb24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/NotificationService(  971): plugged=true pluggin=true
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): runPSCheck
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  971): Checking...
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  971): >> updateStatus
D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  971): acquireWL(1ea4d68d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{2b5808b: PendingIntentRecord{2af44568 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=980684, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{39c8042: PendingIntentRecord{2dc2e853 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455022412630, Int=0
,D/SmartSyncUtils( 6634): isEpsOn(), nState = 0
,D/PMS     (  971): releaseWL(1ea4d68d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  971): acquireWL(21f86590): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6634 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6634): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6634): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6634): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6634): SettingOnTime = 1455084000000, randomSettingOnTime = 1455082455000
,D/SmartSyncScreenOnOffTimeReceiver( 6634): SettingOffTime = 1455062400000, randomSettingOffTime = 1455062478000
,D/SmartSyncScreenOnOffTimeReceiver( 6634): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6634): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6634): bNightModeTurnOffOnce = false
,D/PMS     (  971): releaseWL(21f86590): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  971): acquireWL(3154e89): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PMS     (  971): releaseWL(3154e89): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  971): updateBatteryInfo
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): runPSCheck
D/DotMatrix( 1334): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  971): Checking...
D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  971): >> updateStatus
D/DotMatrix( 1334): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,D/PowerUI ( 1222): closing low battery warning: level=100
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  971): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
