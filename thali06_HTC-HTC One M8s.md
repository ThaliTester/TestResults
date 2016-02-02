#### Test 5797209499148df_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
E/WifiStateMachine(  946): handleMessage: E msg.what=131155
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1577343941] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1577343940] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1356): environment dirty rate=0 [17][0][0]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.69 txretriesrate=0.00 rxrate=7.71 userTriggerdPenalty0
E/WifiStateMachine(  946):  good link -> stuck count =0
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  946):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -59, 3
--------- beginning of system
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  946): handleMessage: X
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/cutils-trace( 6456): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6456): ====startRecUseTime====
D/htc.customization.log.level( 6456):  is 
W/CustomizationLogLevel( 6456): Level value is invalid, use default level 2
W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
D/CustomizationManager( 6456):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6456): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6456): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6456): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6456): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6456): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6456): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6456): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6456): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6456): Parsing tag category name = system
I/CustomizationCIDLoader( 6456): Parsing tag category name = application
I/CustomizationCIDLoader( 6456): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6456): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6456): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6456): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6456): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6456): add string-array item, value = 42507
I/CustomizationCIDLoader( 6456): add string-array item, value = 21902
I/CustomizationCIDLoader( 6456): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6456): add string-array item, value = 23420
I/CustomizationCIDLoader( 6456): add string-array item, value = 22299
I/CustomizationCIDLoader( 6456): add string-array item, value = 24002
I/CustomizationCIDLoader( 6456): add string-array item, value = 23210
I/CustomizationCIDLoader( 6456): add string-array item, value = 23205
I/CustomizationCIDLoader( 6456): add string-array item, value = 23806
I/CustomizationCIDLoader( 6456): add string-array item, value = 23430
I/CustomizationCIDLoader( 6456): add string-array item, value = 23408
I/CustomizationCIDLoader( 6456): add string-array item, value = 27205
I/CustomizationCIDLoader( 6456): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6456): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6456):  Read CID file spent 0.095 (s)
D/CustomizationManager( 6456):  All configurations done spent 0.096 (s)
D/PMS     (  946): acquireHCC(1575a756): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 946 1000 null
I/ActivityManager(  946): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6456 on display 0
W/asset   (  946): Copying FileAsset 0x558732c890 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  946): acquireHCC(3e98a3d7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 946 1000 null
D/PMS     (  946): acquireWL(13ce2e2): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 946 1000 null
I/FeedHostManager( 1495): [onPause]
I/FeedProviderManager( 1495): onPause
I/FeedHostManager( 1495): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@12e381c
I/SocialFeedProvider( 1495): +onPause
I/SocialFeedProvider( 1495): -onPause
I/AnimationUtil(  946): isHTCRecent(ThaliTest/Recent screens.)/6
W/HtcSystemUPManager(  946): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  946): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6474 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  431): Explicit concurrent mark sweep GC freed 8668(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 366us total 23.106ms
E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=235
E/WifiTrafficPoller(  946): notifying of data activity 0
D/WIFI_ICON( 1223): WifiActivity: 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 228us total 15.751ms
I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 359us total 18.383ms
W/asset   ( 6474): Copying FileAsset 0xac2f7520 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/StatusBarManagerService(  946): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  946): hiding MENU key
I/TrimMemoryManager( 1495): [trimMemory] 20
,I/WebViewFactory( 6474): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6474): Time to load native libraries: 9 ms (timestamps 9955-9964)
I/LibraryLoader( 6474): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6474): Binding Chromium to main looper Looper (main, tid 1) {2252b909}
I/LibraryLoader( 6474): Expected native library version number "",actual native library version number ""
I/chromium( 6474): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6474): Initializing chromium process, singleProcess=true
W/art     ( 6474): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6474): ApplicationContext is null in ApplicationStatus
W/chromium( 6474): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6474): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6474): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6474): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6474): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6474): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6474): Local Branch: 
I/Adreno-EGL( 6474): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6474): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6474):                  d74aa161a12b9c6fc6332151
W/System.err(  946): java.lang.Throwable: stack dump
D/BluetoothManagerService(  946): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  946): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bf91263:true
W/System.err(  946): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  946): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  946): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  946): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6474): 467983557: getState(). Returning 12
I/HtcModeClient( 3230): handler message = 4011
E/HtcModeClient( 3230): Check connection and retry 12 times.
W/art     ( 6474): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6474): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6474): CordovaWebView is running on device made by: HTC
W/art     ( 6474): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6474): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6474): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6474): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6474): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@387659ca, mServedView=org.apache.cordova.engine.SystemWebView{15fbf73b VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@143e6e58
I/InputMethodManagerService(  946): Disable input method client, pid=1495
D/StatusBarManagerService(  946): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  946): Enable input method client, pid=6474
I/ActivityManager(  946): Displayed com.test.thalitest/.MainActivity: +798ms
D/PMS     (  946): releaseWL(13ce2e2): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
W/BindingManager( 6474): Cannot call determinedVisibility() - never saw a connection for the pid: 6474
W/XT9_C   ( 1389): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1389): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1389): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1389): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/JsMessageQueue( 6474): Set native->JS mode to OnlineEventsBridgeMode
E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=235
D/jxcore_app_log( 6474): JniHelper::setJavaVM(0xab18a8f8), pthread_self() = -1404423648
I/chromium( 6474): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  946): releaseHCC(1575a756): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
,D/PMS     (  946): releaseHCC(3e98a3d7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6474): Initializing JXcore engine,
W/jxcore-log( 6474): JXcore engine is ready
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=236
D/WIFI_ICON( 1223): WifiActivity: 1
,E/WifiTrafficPoller(  946): notifying of data activity 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 6474): Starting JXcore engine,
,W/jxcore-log( 6474): Platform android,
W/jxcore-log( 6474): 
W/jxcore-log( 6474): Process ARCH arm
W/jxcore-log( 6474): 
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.7, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1577340921] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.7, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1577340920] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1356): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.34 txretriesrate=0.00 rxrate=4.35 userTriggerdPenalty0
E/WifiStateMachine(  946):  good link -> stuck count =0
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  946):  isHighRSSI       ---> score=61
E/WifiStateMachine(  946): handleMessage: X
,D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -59, 3
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 6474): JXcore Cordova bridge is ready!
I/jxcore-log( 6474): 
W/jxcore-log( 6474): JXcore engine is started
,E/jxcore  ( 6474): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6474): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6474): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,W/PluginManager( 6474): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 54ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  946): acquireWL(3c61c0cb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 946 1000 null
W/HtcSystemUPManager(  946): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/Process (  946): killProcessQuiet, pid=5801
I/ActivityManager(  946): Killing 5801:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.resumeTopActivityInnerLocked:1873 
,I/ActivityManager(  946): Recipient 5801
,D/Process (  946): killProcessQuiet, pid=6179
,I/ActivityManager(  946): Killing 6179:com.nero.android.htc.sync/u0a5 (adj 15): empty #18
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.resumeTopActivityInnerLocked:1873 
,I/ActivityManager(  946): Recipient 6179
,D/WifiService(  946): Client connection lost with reason: 4
,I/FeedHostManager( 1495): [onResume]
I/FeedProviderManager( 1495): onResume
I/SocialFeedProvider( 1495): +onResume
,I/SocialFeedProvider( 1495): updateAccounts - Accounts is no change,
I/SocialFeedProvider( 1495): -onResume
,D/StatusBarManagerService(  946): setSystemUiVisibility(0x700)
E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  946): hiding MENU key
,E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=236
E/WifiTrafficPoller(  946): notifying of data activity 0
D/WIFI_ICON( 1223): WifiActivity: 0
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/FindExtension( 1495): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1495): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  946): Disable input method client, pid=6474
D/StatusBarManagerService(  946): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  946): Enable input method client, pid=1495
,I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6474): reportFullscreenMode on inactive InputConnection
,D/PMS     (  946): releaseWL(3c61c0cb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  946): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  946): hiding MENU key
,D/Process (  946): killProcessQuiet, pid=5873
I/ActivityManager(  946): Killing 5873:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  946): Recipient 5873
,W/OpenGLRenderer( 1495): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,E/WifiDataStallTracker(  946): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  946): updateDataStallInfo: mDataStallTxRxSum={txSum=126 rxSum=113} preTxRxSum={txSum=126 rxSum=113}
D/WifiDataStallTracker(  946): updateDataStallInfo: NONE
D/WifiDataStallTracker(  946): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=238
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  946): notifying of data activity 1
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=239
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1577337899] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1577337897] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1356): environment dirty rate=0 [0][0][0],
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72,
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.17 txretriesrate=0.00 rxrate=3.68 userTriggerdPenalty0
E/WifiStateMachine(  946):  good link -> stuck count =0
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  946):  isHighRSSI       ---> score=61
E/WifiStateMachine(  946): handleMessage: X,
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -59, 3
,I/HtcModeClient( 3230): handler message = 4011,
,E/HtcModeClient( 3230): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3230): Don't start project servcice
D/HtcModeClient( 3230): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3230): connectState: CONNECTION_READY = false
,D/SilentMusic( 3230): call stop
D/HtcModeClient( 3230): close connection
,W/HtcModeClient( 3230): leaveProjectMode: It does not enter ProjectMode,
W/CANMesgAgentLocalSocket( 3230): read the terminate packet, so break
,I/ActivityManager(  946): Killing 3230:com.htc.autobot/u0a47 (adj 15): empty #17
,D/Process (  946): killProcessQuiet, pid=3230
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 3230
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1223): WifiActivity: 0
,E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=239
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  946): notifying of data activity 0
,W/SystemReader(  946): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1732): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  946): acquireWL(220a13e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5753 10112 null
,I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1495): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,D/AccTypeManager( 1732): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  946): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneApp( 1439): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  946): releaseWL(220a13e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/[PluginManager]RegisterService( 1588): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1588): handle notify Blinkfeed plugin client changed
D/AccTypeManager( 1732): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PackageBroadcastService( 4444): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4444): Null package name or gms related package.  Ignoreing.,
E/ExternalAccountType( 1732): Unsupported attribute readOnly
,D/PMS     (  946): acquireWL(1a1dad95): PARTIAL_WAKE_LOCK  AsyncService 0x1 6063 10167 null,
,D/PMS     (  946): releaseWL(1a1dad95): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  946): acquireWL(26bdea9b): PARTIAL_WAKE_LOCK  Icing 0x1 4444 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): acquireWL(22f88e11): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6063 10167 null
,I/Icing   ( 4444): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  946): releaseWL(22f88e11): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5905): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  946): releaseWL(26bdea9b): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/UpdateIcingCorporaServi( 5905): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
,W/PackageManager(  946): Unable to load service info ResolveInfo{b462605 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  946): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  946): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  946): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  946): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  946): 	,at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  946): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  946): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  946): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  946): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  946): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  946): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1866): DISABLE
,I/GCoreNlp( 1866): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  946): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,D/LocationProviderProxy(  946): applying state to connected service
,D/PMS     (  946): acquireWL(1af6c4ed): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): releaseWL(1af6c4ed): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  946): applying state to connected service
,D/PMS     (  946): acquireWL(27603f22): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(d836db3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1866 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  946): releaseWL(d836db3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(27603f22): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(35de907a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1866 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): releaseWL(35de907a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  946): Explicit concurrent mark sweep GC freed 30596(1648KB) AllocSpace objects, 6(312KB) LOS objects, 33% free, 18MB/28MB, paused 1.603ms total 158.296ms,
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=239
,I/ActivityManager(  946): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6543 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  946): acquireWL(3824e02b): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{10076}
V/AlarmManager(  946): sending alarm PendingIntent{3042bc88: PendingIntentRecord{3b0be621 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454416577780, Int=60000
D/PMS     (  946): releaseWL(3824e02b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1495): loadItems() com.htc.launcher.pageview.WidgetManager@3f4d361f +,
I/Prism.WidgetManager( 1495): onLoadItems() +
,D/SMSBackup( 6543): SMSBackupAgentService started,
D/SMSBackup( 6543): Checking restore status,
D/SMSBackup( 6543): Restore complete,
,D/SMSBackup( 6543): cancelCheckAlarm
,D/SMSBackup( 6543): SMSBackupAgentService completed: completed in 0.0 seconds
,W/ResourcesManager( 1495): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=239
,W/asset   ( 1495): Copying FileAsset 0x5586f0f6f0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1495): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1495): onLoadItems() -
I/Prism.ItemManager( 1495): loadItems() com.htc.launcher.pageview.WidgetManager@3f4d361f -
,D/PhoneApp( 1439): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1439): -- N1 =0
,D/PhoneApp( 1439): -- N2 =0,
,D/PhoneApp( 1439): -- N3 =0
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1577334875] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
,E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1577334873] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SIGNAL_POLL',
,I/wpa_supplicant( 1356): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.09 txretriesrate=0.00 rxrate=2.34 userTriggerdPenalty0
E/WifiStateMachine(  946):  good link -> stuck count =0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  946):  isHighRSSI       ---> score=61
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  946): handleMessage: X
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -59, 3
,E/WifiDataStallTracker(  946): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  946): updateDataStallInfo: mDataStallTxRxSum={txSum=126 rxSum=113} preTxRxSum={txSum=126 rxSum=113},
D/WifiDataStallTracker(  946): updateDataStallInfo: NONE
D/WifiDataStallTracker(  946): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  946): WiFiStateMachine SCAN ALARM,
D/PMS     (  946): acquireWL(170f5407): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{1000}
E/WifiStateMachine(  946): handleMessage: E msg.what=131143
,D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
E/WifiStateMachine(  946): processMsg: ConnectedState
V/AlarmManager(  946): sending alarm PendingIntent{20a73cd7: PendingIntentRecord{10899c4 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454416578990, Int=20000
,E/WifiStateMachine(  946):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:78 rssi=-59 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=2.3 list=2412 [on:0 tx:0 rx:0 period:504] from screen [on:0 period:-1577334351]
D/PMS     (  946): releaseWL(170f5407): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:78 rssi=-59 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=2.3 list=2412 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1577334349]
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.09 rxSuccessRate=2.34 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-59
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN with age=71496 interval=60000 maxinterval=300000
,E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN try full band scan age=71496 interval=60000 maxinterval=300000
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  946): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1356): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1356): wpa_supplicant_scan enter
D/wpa_supplicant( 1356): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1356): WPS: Building WPS IE for Probe Request
,D/wpa_supplicant( 1356): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1356): WPS:  * Request Type
D/wpa_supplicant( 1356): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1356): WPS:  * UUID-E
D/wpa_supplicant( 1356): WPS:  * Primary Device Type
D/wpa_supplicant( 1356): WPS:  * RF Bands (3)
D/wpa_supplicant( 1356): WPS:  * Association State
,D/wpa_supplicant( 1356): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1356): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1356): WPS:  * Manufacturer
D/wpa_supplicant( 1356): WPS:  * Model Name
D/wpa_supplicant( 1356): WPS:  * Model Number
D/wpa_supplicant( 1356): WPS:  * Device Name
D/wpa_supplicant( 1356): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1356): P2P: * P2P IE header
,D/wpa_supplicant( 1356): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1356): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1356): wlan0: Add radio work 'scan'@0x5586f9b860
D/wpa_supplicant( 1356): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1356): wlan0: Starting radio work 'scan'@0x5586f9b860 after 0.000040 second wait
D/wpa_supplicant( 1356): wlan0: nl80211: scan request
D/wpa_supplicant( 1356): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1356): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1356): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1356): wlan0: Own scan request started a scan in 0.000085 seconds
,I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  946): [1,454,416,578,997 ms] noteScanstart no scan source
E/WifiStateMachine(  946): handleMessage: X
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  946): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  946): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=240
E/WifiTrafficPoller(  946): notifying of data activity 1
,D/WIFI_ICON( 1223): WifiActivity: 1,
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=240
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  946): notifying of data activity 0
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=240
,D/wpa_supplicant( 1356): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1356): wlan0: nl80211: New scan results available
W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1356): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1356): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1356): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1356): wlan0: Scan completed in 2.132712 seconds
D/wpa_supplicant( 1356): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1356): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1356): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1356): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1356): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1356): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
D/wpa_supplicant( 1356): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1356): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1356): wlan0: Scan-only results received
D/wpa_supplicant( 1356): wlan0: Radio work 'scan'@0x5586f9b860 done in 2.133683 seconds
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  946): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  946): handleMessage: E msg.what=147461
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
,E/WifiStateMachine(  946):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  946): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1356): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  946): [1,454,416,581,138 ms] noteScanEnd no scan source
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1356): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  946): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@37bb90ab sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  946): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  946): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  946): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  946): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  946):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  946): Gonzos 38:f8:89:11:e9:11 rssi=-78 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  946): 01ABC c2:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  946): ageScanResultsOut delay 40000 size 4 now 1454416581141
E/WifiAutoJoinController (  946): newSupplicantResults size=4 known=1 true
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1356): wlan0: Control interface command 'STATUS-NO_EVENTS'
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
E/WifiAutoJoinController (  946): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-59,-127) num=(1,0)
E/WifiAutoJoinController (  946): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  946): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-59 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  946): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  946): Done attemptAutoJoin status=0
E/WifiConfigStore(  946):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  946): handleMessage: X
D/WifiManager( 1866): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:2493] from screen [on:0 period:-1577331854] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1577331853] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946):  get link layer stats 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1356): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  946): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.54 txretriesrate=0.00 rxrate=1.17 userTriggerdPenalty0
,E/WifiStateMachine(  946):  good link -> stuck count =0
E/WifiStateMachine(  946):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  946):  isHighRSSI       ---> score=61
E/WifiStateMachine(  946): handleMessage: X
D/WifiWatchdogStateMachine(  946): RSSI current: 3 new: -59, 3
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/Process (  946): killProcessQuiet, pid=6243
I/ActivityManager(  946): Killing 6243:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6243,
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=240
,I/PMS     (  946): Going to sleep due to screen timeout (uid 1000)...
,I/SensorManager(  946): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3edaad1f
W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  946): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  946): pid=946, uid=1000
W/PMN     (  946): goingToSleep
W/SensorService(  946): Active sensors: size = 4
W/SensorService(  946): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  946): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  946): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3edaad1f, eanble = 0, strlen(mName) = 91
W/SensorService(  946): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  946): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1c4df9d8
W/SensorService(  946): Listener[1] = com.htc.smartdim.sensor_eye@13876a2a
W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/ActivityManager(  946): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{18b1934 #7 A=.Prism U=0 sz=1}
W/PMS     (  946): mWirelessDisplayManager is null
W/PMS     (  946): mWirelessDisplayManager is still null
D/PMS     (  946): acquireWL(3c1fc35d): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 946 1000 null
,I/FeedHostManager( 1495): [onPause]
W/PMN     (  946): goingToSleep done
I/FeedProviderManager( 1495): onPause
I/FeedHostManager( 1495): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@12e381c
I/SocialFeedProvider( 1495): +onPause
I/SocialFeedProvider( 1495): -onPause
,I/PMS     (  946): Sleeping (uid 1000)...
D/XAN-DPS (  946): prepareColorFade 1
,I/ActivityManager(  946): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6566 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,W/HtcSystemUPManager(  946): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/AlarmManager(  946): ACTION_SCREEN_ON
I/AlarmManager(  946): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  946): [AlarmQueuing] done recovering
I/AlarmManager(  946): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  946): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/PMS     (  946): releaseWL(3c1fc35d): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/WifiTrafficPoller(  946):  packet count Tx=143 Rx=240
E/WifiDataStallTracker(  946): ENABLE_DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  946): updateDataStallInfo: mDataStallTxRxSum={txSum=126 rxSum=113} preTxRxSum={txSum=126 rxSum=113}
,D/WifiDataStallTracker(  946): updateDataStallInfo: NONE
D/WifiDataStallTracker(  946): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  946): handleMessage: E msg.what=131167
,E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
,E/WifiStateMachine(  946):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946): processMsg: DefaultState
,E/WifiStateMachine(  946):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  946):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1356): SET_SCREEN_ON:On
,I/wpa_supplicant( 1356): htc_wext_set_keepalive +
I/wpa_supplicant( 1356): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
,D/wpa_supplicant( 1356): getPrivFuncNum +	
I/wpa_supplicant( 1356): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1356): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1356): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1356): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1356): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  946): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  946): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  946): handleScreenStateChanged Exit: true
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131154
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/SRS_Proc(  422): ParamSet string: screen_state=on
D/wpa_supplicant( 1356): wlan0: Control interface command 'SIGNAL_POLL'
E/audio_a2dp_hw(  422): adev_set_parameters: ERROR: set param called even when stream out is null
I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  946): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  946): Build Date: 03/09/15 Mon
I/Adreno-EGL(  946): Local Branch: 
I/Adreno-EGL(  946): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  946): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  946):                  d74aa161a12b9c6fc6332151
D/WifiController(  946): handleMessage: E msg.what=155650
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,W/HtcLockScreen( 1223): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
I/wpa_supplicant( 1356): environment dirty rate=0 [0][0][0]
D/NetworkPolicy(  946): updateScreenOn: false
V/NetworkPolicy(  946): updateIfacesLocked()
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  946): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  946): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131127
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
,E/WifiStateMachine(  946):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131129
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0,
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1356): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1356): wlan0: BLACKLIST CLEAR 
D/NetworkManagementService(  946): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  946): handleMessage: X
D/WifiMonitor(  946): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=33 dispatchEvent: BLACKLIST CLEAR 
,D/GpsLocationProvider(  946): receive broadcast intent, action: android.intent.action.SCREEN_ON
,W/ResourcesManager( 6566): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
,I/IntentController( 1223): receive(android.intent.action.SCREEN_ON,1,false),
,I/CalendarProvider2( 6566): Created com.android.providers.calendar.CalendarAlarmManager@117b8fe9(com.htc.providers.calendar.HtcCalendarProvider@eab746e),
,D/CalendarProvider2( 6566): wait start:true
,D/PMS     (  946): acquireWL(34cf4cf7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(23c13764): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(34cf4cf7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(23c13764): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  946): prepareColorFade done,
,D/XAN-DPS (  946): setBrightness to 0
,D/AlarmManager(  946): ACTION_SCREEN_OFF,
I/AlarmManager(  946): [AlarmQueuing] screen off now: 
I/AlarmManager(  946): [AlarmQueuing] data connection: true
I/AlarmManager(  946): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  946): stopDataStallAlarm 
E/WifiDataStallTracker(  946): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  946): handleMessage: E msg.what=131167
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
,E/WifiStateMachine(  946):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  946):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_SCREEN_ON 0'
,I/wpa_supplicant( 1356): SET_SCREEN_ON:Off
I/wpa_supplicant( 1356): htc_wext_set_keepalive +
I/wpa_supplicant( 1356): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1356): getPrivFuncNum +	
I/wpa_supplicant( 1356): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1356): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1356): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1356): htc_wext_set_keepalive gateway addr = c0a80101
V/SRS_Proc(  422): ParamSet string: screen_state=off
I/wpa_supplicant( 1356): htc_wext_set_keepalive - ret = 0
E/audio_a2dp_hw(  422): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  946): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
D/WifiStateMachine(  946): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  946): handleScreenStateChanged Exit: false
E/WifiStateMachine(  946): handleMessage: X
D/WifiController(  946): handleMessage: E msg.what=155651
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,D/GpsLocationProvider(  946): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/NetworkPolicy(  946): updateScreenOn: false
I/SensorManager(  946): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@1c4df9d8
V/NetworkPolicy(  946): updateIfacesLocked()
W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  946): disable: get sensor name = CM32181 Light sensor
E/WifiStateMachine(  946): handleMessage: E msg.what=131154
,E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
D/NetworkManagementService(  946): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  946):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  946): handleMessage: X
,I/DisplayManagerService(  946): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,W/SensorService(  946): pid=946, uid=1000
W/SensorService(  946): Active sensors: size = 3
W/SensorService(  946): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  946): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@1c4df9d8, eanble = 0, strlen(mName) = 67
W/SensorService(  946): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  946): Listener[0] = com.htc.smartdim.sensor_eye@13876a2a
W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/CalendarProvider2( 6566): wait end:false
V/ActivityManager(  946): Display changed displayId=0
D/DotMatrix( 1312): [EventService]  onDisplayChanged: 0
E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,D/DotMatrix( 1312): [EventService] mbHDMIConnect: false, mCoverOn:false,
,I/SensorManager( 1223): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@33400029, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  946): enable: get sensor name = hTC Gesture Motion HIDI
I/ActivityManager(  946): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6597 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,W/SensorService(  946): pid=1223, uid=10041
,W/SensorService(  946): Active sensors: size = 4
W/SensorService(  946): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  946): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@33400029, eanble = 1, strlen(mName) = 57
W/SensorService(  946): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  946): Listener[0] = com.htc.smartdim.sensor_eye@13876a2a
W/SensorService(  946): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@33400029
,W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1439): start background delete task...,
,D/ContactMessageStore( 1439): size: 0 , 0,
D/ContactMessageStore( 1439): Background delete complete
,I/IntentController( 1223): receive(android.intent.action.SCREEN_OFF,1,false),
,D/PMS     (  946): acquireWL(1f21c193): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1866 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  946): releaseWL(1f21c193): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(150c65d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(150c65d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,I/RemoteViews( 1223): setHTCTheme(com.htc.updater,true,33751145),
,D/PowerUsageList:PowerUsageHelper( 6597): MY_DEBUG = false,
,D/SmartSyncUtils( 6597): isEpsOn(), nState = 0,
,I/RemoteViews( 1223): apply : com.htc.updater 0 13 0 36
,D/PMS     (  946): acquireWL(1a1ce3ef): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6597 1000 null,
,W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/SmartDim(  946): Init customizeScreenOffDelayClass error
D/PMS     (  946): releaseWL(1a1ce3ef): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL false Token 13 num clients 6
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl(  946): Excessive delay in setPowerMode(): 298ms
D/PMS     (  946): Setting HAL interactive mode to false
W/HtcSystemUPManager(  946): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  946): Setting HAL interactive mode to false done
D/PMS     (  946): Setting HAL auto-suspend mode to true
D/PMS     (  946): Setting HAL auto-suspend mode done
I/InputMethodManagerService(  946): screenObserver, isScreenOn=false
D/HABCtrl (  946): TPE algorithm. remove timeout.
D/StatusBarManagerService(  946): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  946): Disable input method client, pid=1495
D/PMS     (  946): OOBE c monitor 11
,I/InputManager(  946): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1223): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
,D/PMS     (  946): acquireWL(259a0efc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(259a0efc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  946): plugged=true pluggin=true
D/NfcService( 1455): ScreenObserver: OFF
,D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
D/HtcPowerSaver(  946): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  946): runPSCheck
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  946): Checking...
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): >> updateStatus
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NfcService( 1455): applyRouting - 0
D/PMS     (  946): acquireWL(6115985): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1455 1027 null
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  946): << updateStatus
D/NfcService( 1455): applyRouting -2
D/NfcService( 1455): applyRouting
D/NfcService( 1455): Ignore this applyRouting...
,D/PMS     (  946): releaseWL(6115985): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/ContextImpl( 6597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6597): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6597): isEpsOn(), nState = 0
,I/ClockController( 1223): stop clock update:screen off
,W/ContextImpl( 6597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  946): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@13876a2a
W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  946): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  946): pid=946, uid=1000
W/SensorService(  946): Active sensors: size = 3
W/SensorService(  946): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@13876a2a, eanble = 0, strlen(mName) = 36
W/SensorService(  946): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  946): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@33400029
W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  946): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  946): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  946): pid=946, uid=1000
W/SensorService(  946): Active sensors: size = 2
W/SensorService(  946): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  946): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  946): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@13876a2a, eanble = 0, strlen(mName) = 36
W/SensorService(  946): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  946): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@33400029
W/SensorService(  946): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  946): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@13876a2a
,I/ActivityManager(  946): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6631 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,E/ActivityThread(  946): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@197d301b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  946): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@197d301b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  946): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  946): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  946): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775),
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
,I/PowerUsageList:PowerUsageHelper( 6597): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6597): gen(), null == sipper.uidObj, userId = 0,
,D/Process (  946): killProcessQuiet, pid=6269,
I/ActivityManager(  946): Killing 6269:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6597): getMobilePolicyEnabled, result = true
,D/WifiService(  946): New client listening to asynchronous messages
E/WifiTrafficPoller(  946): ADD_CLIENT: 7
,I/ActivityManager(  946): Recipient 6269,
,D/PowerUsageList:PowerUsageHelper( 6597): MY_DEBUG = false
,E/WifiTrafficPoller(  946): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,D/Process (  946): killProcessQuiet, pid=6295,
I/ActivityManager(  946): Killing 6295:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6295
,I/CalendarProvider2( 6566): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6566): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar),
,I/ActivityManager(  946): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6655 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  946): killProcessQuiet, pid=6324
,I/ActivityManager(  946): Killing 6324:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiDataStallTracker(  946): DATA_MONITOR_POLL false Token 3
,I/ActivityManager(  946): Recipient 6324
,W/ResourcesManager( 6655): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6655): onCreate,
,D/ProviderChangeReceiver( 6655): ---------------------------------------------------
,D/ProviderChangeReceiver( 6655): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/ActivityManager(  946): Killing 5410:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  946): killProcessQuiet, pid=5410
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/PMS     (  946): releaseWL(170fe95c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/HtcAlertService( 6655): start to updateAlertNotification!
,I/ActivityManager(  946): Recipient 5410
,D/HtcAlertService( 6655): No fired or scheduled alerts,
D/HtcAlertUtils( 6655): -- cancelReminderNotification --
,D/HtcAlertUtils( 6655): broadcastExistReminder!
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
E/WifiStateMachine(  946):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1577328844] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
,E/WifiStateMachine(  946):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1577328843] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  946): handleMessage: X
,E/WifiStateMachine(  946): handleMessage: E msg.what=131155,
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1088] from screen [on:0 period:-1577327753] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1577327750] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  946): handleMessage: X
,D/HtcUPManager( 1223): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  946): DATA_MONITOR_POLL false Token 3
,D/ContactMessageStore( 1439): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1439): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  946): killProcessQuiet, pid=5578
I/ActivityManager(  946): Killing 5578:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 5578
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  946): acquireWL(24f71ee8): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{10024}
,V/AlarmManager(  946): sending alarm PendingIntent{18130901: PendingIntentRecord{49f53a6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142658, Int=0
,D/PMS     (  946): releaseWL(24f71ee8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  946): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  946): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
D/PMS     (  946): acquireWL(1bb761e7): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 946 1000 null
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  946): [NET] android_getaddrinfofornet-, err=8
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  946): [NET] android_getaddrinfofornet-, pass to proxy,
,D/libc    (  946): [NET] android_getaddrinfo_proxy+
D/libc    (  946): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  946): [NET] android_getaddrinfo_proxy-, success,
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  946): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  946): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  946): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  946):  [handleDownloadXtraData]inject done.,
D/PMS     (  946): acquireWL(348e3583): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 946 1000 null
D/GpsLocationProvider(  946): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  946): releaseWL(1bb761e7): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/PMS     (  946): releaseWL(348e3583): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  946): acquireWL(1b2ce300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
,I/BatteryService(  946): n_update end
D/UsbnetService(  946): BroadcastReceiver::onReceive+
,D/PMS     (  946): releaseWL(1b2ce300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/NotificationService(  946): plugged=true pluggin=true
D/WifiController(  946): handleMessage: E msg.what=155652
D/PMS     (  946): runPSCheck
D/WifiController(  946): processMsg: DeviceActiveState
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): handleMessage: X
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  946): << updateStatus
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1439): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  946): acquireWL(1146d739): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000},
V/AlarmManager(  946): sending alarm PendingIntent{362f323f: PendingIntentRecord{f21c70c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149710, Int=0
,V/AlarmManager(  946): sending alarm PendingIntent{1fd3317e: PendingIntentRecord{2b74a6df android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454416636561, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{3afd2f2c: PendingIntentRecord{2a34adf5 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203189, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{5ece78a: PendingIntentRecord{1326d1fb com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=188847, Int=0
D/PMS     (  946): acquireWL(1ea41218): PARTIAL_WAKE_LOCK  *backup* 0x1 946 1000 null
,D/PMS     (  946): acquireWL(1fef3471): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(1146d739): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/BackupManagerService(  946): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  946): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  946): releaseWL(1ea41218): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  946): acquireWL(3b39f256): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): releaseWL(1fef3471): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  946): releaseWL(3b39f256): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): acquireWL(32bf0c30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): releaseWL(32bf0c30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(2e2f00a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(2e2f00a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): acquireWL(27ecf62e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(87b05cf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(1acdfe65): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): releaseWL(27ecf62e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1913): Vacuum at: now=1454416673761 tag=VacuumService,
,I/GoogleURLConnFactory( 1913): Using platform SSLCertificateSocketFactory
,D/PMS     (  946): releaseWL(87b05cf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): acquireWL(34c2feb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(34c2feb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  946): acquireWL(18cc3148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(18cc3148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1913): No account for auth token provided,
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:100, mark:917604,
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1913): No account for auth token provided,
,W/Uploader( 1913): No account for auth token provided
,W/Uploader( 1913):  no longer exists, so no auth token.,
,W/Uploader( 1913): No account for auth token provided,
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1913): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337),
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1913): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 4 40
,D/PMS     (  946): releaseWL(1acdfe65): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  946): acquireWL(f544ad5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(f544ad5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  946): acquireWL(2b6ef2ea): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(2b6ef2ea): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1588): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@36ef3248
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
I/ActivityManager(  946): Killing 5836:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  946): killProcessQuiet, pid=5836
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 5836
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  946): acquireWL(173ce9db): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(173ce9db): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/WifiController(  946): battery changed pluggedType: 2
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): handleMessage: E msg.what=155652
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DeviceActiveState
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): << updateStatus
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1356): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
,D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
,D/PMS     (  946): acquireWL(2e927c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
,D/PMS     (  946): releaseWL(2e927c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): handleMessage: E msg.what=155652
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  946): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  946): handleMessage: X
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false),
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1356): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  946): acquireWL(331bbf51): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(331bbf51): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/PMS     (  946): runPSCheck
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): handleMessage: E msg.what=155652
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1913): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1913): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1913): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1913): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5988): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5988): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5988): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5988): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5988): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5988): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5988): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,W/System  ( 5988): Ignoring header User-Agent because its value was null.,
D/libc    ( 5988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5988): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5988): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5988): [NET] android_getaddrinfo_proxy+
D/libc    ( 5988): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  397): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5988): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  946): acquireWL(3687ffcb): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000}
V/AlarmManager(  946): sending alarm PendingIntent{362f323f: PendingIntentRecord{f21c70c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209710, Int=0
,D/PMS     (  946): releaseWL(3687ffcb): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data,
,D/PMS     (  946): acquireWL(35fa1ec1): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{10109}
,V/AlarmManager(  946): sending alarm PendingIntent{3b241666: PendingIntentRecord{2614cda7 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454416811070, Int=0
,V/AlarmManager(  946): sending alarm PendingIntent{3aea254: PendingIntentRecord{27c8e5fd com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454416882895, Int=1800000
,D/PMS     (  946): acquireWL(54b32f2): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4444 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): releaseWL(35fa1ec1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/PMS     (  946): acquireWL(1d7d8fc0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4444 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): releaseWL(54b32f2): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms},
,I/EventLogService( 4444): Aggregate from 1454416566256 (log), 1454415082829 (data),
,D/PMS     (  946): releaseWL(1d7d8fc0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/PMS     (  946): acquireWL(348be7ec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  946): n_update end
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  946): releaseWL(348be7ec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/WifiController(  946): battery changed pluggedType: 2
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/PMS     (  946): runPSCheck
D/WifiController(  946): handleMessage: E msg.what=155652
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): processMsg: DeviceActiveState
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  946): processMsg: DefaultState
I/HtcPowerSaver(  946): << updateStatus
D/WifiController(  946): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  946): acquireWL(cc3d7b5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(cc3d7b5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  946): updateBatteryInfo
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  946): plugged=true pluggin=true
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  946): >> updateStatus
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): battery changed pluggedType: 2
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  946): processMsg: DefaultState
I/HtcPowerSaver(  946): << updateStatus
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  946): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  946): acquireWL(261a2e4a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000}
,V/AlarmManager(  946): sending alarm PendingIntent{362f323f: PendingIntentRecord{f21c70c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=449709, Int=0
,I/ActivityManager(  946): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6691 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  946): sending alarm PendingIntent{a7c71bb: PendingIntentRecord{134596d8 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454417038797, Int=0
,D/PMS     (  946): releaseWL(261a2e4a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,E/cutils-trace( 6713): Error opening trace file: Permission denied (13),
I/dex2oat ( 6713): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=15 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6713): dex2oat: override thread count:4
,I/dex2oat ( 6713): dex2oat took 907.593ms (threads: 4),
,I/PushClient( 6691): ApplicationMonitor {3033254b}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6691): ApplicationMonitor {3033254b}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6691): ApplicationMonitor {3033254b}: logBasicAppInfo(): VersionName:             1.2.853019,
I/PushClient( 6691): ApplicationMonitor {3033254b}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6691): ApplicationMonitor {3033254b}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6691): ApplicationMonitor {3033254b}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
I/PushClient( 6691): ApplicationMonitor {3033254b}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6691): ApplicationMonitor {3033254b}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6691): ApplicationMonitor {3033254b}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6691): PnsModel {2114361a}: update(): Update registration caused by: alarm
,I/PushClient( 6691): PnsConfigModel {d1ef679}: <init>(): Use dm-client for provisioning.
,W/System.err( 6691): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6691): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6691): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6691): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  946): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6720 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6720): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6720 dbg=false s=true,
,I/DeviceManagement( 6720): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6720): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6720): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6720): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6720): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1d1e697a] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6720): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6720): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6720): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6720): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6720): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6720): SessionStateController: Checking invariants...,
,I/art     (  946): Explicit concurrent mark sweep GC freed 40579(2MB) AllocSpace objects, 6(1184KB) LOS objects, 33% free, 18MB/28MB, paused 1.929ms total 167.035ms,
,I/DeviceManagement( 6720): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6720): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1d1e697a],
I/DeviceManagement( 6720): WorkflowService: Stopping workflow service
,D/Process (  946): killProcessQuiet, pid=6426,
I/ActivityManager(  946): Killing 6426:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6426
,I/PushClient( 6691): PnsModel {2114361a}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  946): killProcessQuiet, pid=6380
,I/ActivityManager(  946): Killing 6380:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6380
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1439): MSG_CHECK_DELETION >>,
D/ContactMessageStore( 1439): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1439): sku_id=118
D/ContactMessageStore( 1439): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1439): start background delete task...
,D/ContactMessageStore( 1439): size: 0 , 0
,D/ContactMessageStore( 1439): Background delete complete
,D/PMS     (  946): acquireWL(3f5b1825): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
D/UsbnetService(  946): BroadcastReceiver::onReceive+
I/BatteryService(  946): n_update end
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/PMS     (  946): releaseWL(3f5b1825): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/NotificationService(  946): plugged=true pluggin=true
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
,D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): handleMessage: X
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  946): updateBatteryInfo
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  946): runPSCheck
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  946): Checking...
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  946): >> updateStatus,
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(cc2bdfa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/PMS     (  946): releaseWL(cc2bdfa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  946): updateBatteryInfo
D/WifiController(  946): handleMessage: E msg.what=155652
D/PMS     (  946): runPSCheck
D/WifiController(  946): processMsg: DeviceActiveState
D/HtcPowerSaver(  946): Checking...
,D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): >> updateStatus
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): handleMessage: X
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): << updateStatus
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(2e293fab): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000},
V/AlarmManager(  946): sending alarm PendingIntent{362f323f: PendingIntentRecord{f21c70c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=569710, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{22386608: PendingIntentRecord{334a11a1 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940387, Int=0
,I/bt-btm  ( 3104): Received oneshot timer event complete
D/PMS     (  946): acquireWL(2b6ebfc6): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3104 1002 null
I/bt-btm  ( 3104): btm_ble_timeout
I/bt-btm  ( 3104): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3104): btm_ble_rand_enc_complete,
I/bt-btm  ( 3104): btm_gen_resolve_paddr_low
D/bt-smp  ( 3104): smp_encrypt_data
W/bt-smp  ( 3104): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3104): Plain text(LSB ~ MSB) = f3 b5 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3104): Encrypted text(LSB ~ MSB) = d1 5e b8 09 4c b8 8d ac 8c d0 13 c7 07 d5 df e2 
I/bt-btm  ( 3104): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3104): Stopping oneshot timer
D/bt-btm  ( 3104): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  946): releaseWL(2e293fab): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  946): releaseWL(2b6ebfc6): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  946): acquireWL(15ba2b87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(15ba2b87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1223): closing low battery warning: level=100
D/NotificationService(  946): plugged=true pluggin=true
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  946): updateBatteryInfo
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/PMS     (  946): runPSCheck
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  946): >> updateStatus
,D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(2af1dab4): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{10024},
V/AlarmManager(  946): sending alarm PendingIntent{14d526dd: PendingIntentRecord{3c871252 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936885, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{c67806e: PendingIntentRecord{1447630f android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804604, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{2a83f923: PendingIntentRecord{1ef9619f com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454417436395, Int=0
,D/PMS     (  946): acquireWL(242bee20): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  946): releaseWL(242bee20): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
W/ContextImpl( 6597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  946): releaseWL(2af1dab4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6597): MY_DEBUG = false
,D/PowerUsageService( 6597): repeat time = 1454418336432
,D/PMS     (  946): acquireWL(760019e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1913): Message class com.google.f.a.a.i
D/PMS     (  946): releaseWL(760019e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6597): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6597): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  946): acquireWL(293047f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000}
V/AlarmManager(  946): sending alarm PendingIntent{362f323f: PendingIntentRecord{f21c70c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=989710, Int=0
,V/AlarmManager(  946): sending alarm PendingIntent{1d31cc4c: PendingIntentRecord{293b5495 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454417483098, Int=0
,D/SmartSyncUtils( 6597): isEpsOn(), nState = 0
,D/PMS     (  946): releaseWL(293047f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  946): acquireWL(224699aa): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6597 1000 null
,D/WeatherUtility( 1223): Weather sync is On
,D/SmartSyncScreenOnOffTimeReceiver( 6597): [updateNmRange] bManual = false,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6597): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6597): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6597): SettingOnTime = 1454479200000, randomSettingOnTime = 1454477866000
D/SmartSyncScreenOnOffTimeReceiver( 6597): SettingOffTime = 1454457600000, randomSettingOffTime = 1454461439000
,D/SmartSyncScreenOnOffTimeReceiver( 6597): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6597): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6597): bNightModeTurnOffOnce = false
,D/PMS     (  946): releaseWL(224699aa): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  946): acquireWL(1e5d699b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  946): n_update end
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  946): releaseWL(1e5d699b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/PMS     (  946): runPSCheck
D/HtcPowerSaver(  946): Checking...
I/HtcPowerSaver(  946): >> updateStatus
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(2cd56138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(2cd56138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1223): closing low battery warning: level=100
D/HtcPowerSaver(  946): updateBatteryInfo
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/PMS     (  946): runPSCheck
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  946): >> updateStatus
,D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  946): processMsg: DefaultState
I/HtcPowerSaver(  946): << updateStatus,
D/WifiController(  946): handleMessage: X
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  946): acquireWL(3c9a511): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(3c9a511): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  946): runPSCheck
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): handleMessage: E msg.what=155652
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  946): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  946): handleMessage: X
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  946): << updateStatus
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  946): User[0] Flushing usage stats to disk
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  946): acquireWL(94ca676): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  946): n_update end
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  946): releaseWL(94ca676): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  946): updateBatteryInfo
D/HeadsetStateMachine( 3104): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/NotificationService(  946): plugged=true pluggin=true
,D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): handleMessage: E msg.what=155652
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms)
```
