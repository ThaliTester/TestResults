#### Test 575312431745da8_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  966):  packet count Tx=156 Rx=249
E/cutils-trace( 6344): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6344): ====startRecUseTime====
D/htc.customization.log.level( 6344):  is 
W/CustomizationLogLevel( 6344): Level value is invalid, use default level 2
D/CustomizationManager( 6344):  Read ACC file spent 0.045 (s)
D/CIDMapFileReader( 6344): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6344): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6344): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6344): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6344): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6344): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6344): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6344): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6344): Parsing tag category name = system
I/CustomizationCIDLoader( 6344): Parsing tag category name = application
I/CustomizationCIDLoader( 6344): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6344): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6344): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6344): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6344): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6344): add string-array item, value = 42507
I/CustomizationCIDLoader( 6344): add string-array item, value = 21902
I/CustomizationCIDLoader( 6344): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6344): add string-array item, value = 23420
I/CustomizationCIDLoader( 6344): add string-array item, value = 22299
I/CustomizationCIDLoader( 6344): add string-array item, value = 24002
I/CustomizationCIDLoader( 6344): add string-array item, value = 23210
I/CustomizationCIDLoader( 6344): add string-array item, value = 23205
I/CustomizationCIDLoader( 6344): add string-array item, value = 23806
I/CustomizationCIDLoader( 6344): add string-array item, value = 23430
I/CustomizationCIDLoader( 6344): add string-array item, value = 23408
I/CustomizationCIDLoader( 6344): add string-array item, value = 27205
I/CustomizationCIDLoader( 6344): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6344): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6344):  Read CID file spent 0.090 (s)
D/CustomizationManager( 6344):  All configurations done spent 0.090 (s)
--------- beginning of system
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6344 on display 0
D/PMS     (  966): acquireHCC(1ad837fe): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 966 1000 null
D/PMS     (  966): acquireHCC(1b936b5f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 966 1000 null
W/asset   (  966): Copying FileAsset 0x55b249b050 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  966): acquireWL(167bd60a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 966 1000 null
I/AnimationUtil(  966): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1488): [onPause]
I/FeedProviderManager( 1488): onPause
I/FeedHostManager( 1488): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@33b28c1d
I/SocialFeedProvider( 1488): +onPause
I/SocialFeedProvider( 1488): -onPause
W/HtcSystemUPManager(  966): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6362 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  407): Explicit concurrent mark sweep GC freed 8683(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 354us total 21.795ms
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 236us total 14.262ms
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 654us total 19.781ms
D/StatusBarManagerService(  966): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
W/asset   ( 6362): Copying FileAsset 0xac11cf48 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1488): [trimMemory] 20
,I/WebViewFactory( 6362): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6362): Time to load native libraries: 11 ms (timestamps 627-638)
I/LibraryLoader( 6362): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6362): Binding Chromium to main looper Looper (main, tid 1) {1e083847}
I/LibraryLoader( 6362): Expected native library version number "",actual native library version number ""
I/chromium( 6362): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6362): Initializing chromium process, singleProcess=true
W/art     ( 6362): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6362): ApplicationContext is null in ApplicationStatus
W/chromium( 6362): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6362): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6362): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6362): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6362): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6362): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6362): Local Branch: 
I/Adreno-EGL( 6362): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6362): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6362):                  d74aa161a12b9c6fc6332151
E/WifiDataStallTracker(  966): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  966): updateDataStallInfo: mDataStallTxRxSum={txSum=138 rxSum=114} preTxRxSum={txSum=122 rxSum=101}
D/WifiDataStallTracker(  966): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  966): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
W/System.err(  966): java.lang.Throwable: stack dump
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32cedc6b:true
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  966): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6362): 1015419363: getState(). Returning 12
E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  966):  packet count Tx=156 Rx=250
D/WIFI_ICON( 1212): WifiActivity: 1
E/WifiTrafficPoller(  966): notifying of data activity 1
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  966): handleMessage: E msg.what=131155
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400858580] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400858579] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  966):  get link layer stats 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1365): environment dirty rate=6 [16][1][0]
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  966): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  966): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.11 txretriesrate=0.00 rxrate=7.71 userTriggerdPenalty0
E/WifiStateMachine(  966):  good link -> stuck count =0
E/WifiStateMachine(  966):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  966):  isHighRSSI       ---> score=65
E/WifiStateMachine(  966): handleMessage: X
D/WIFI_ICON( 1212): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  966): RSSI current: 3 new: -57, 3
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/art     ( 6362): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6362): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6362): CordovaWebView is running on device made by: HTC
W/art     ( 6362): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6362): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6362): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6362): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6362): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@264c1910, mServedView=org.apache.cordova.engine.SystemWebView{3069bc09 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@c45fe0e
I/InputMethodManagerService(  966): Disable input method client, pid=1488
I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +781ms
D/StatusBarManagerService(  966): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  966): Enable input method client, pid=6362
D/PMS     (  966): releaseWL(167bd60a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1212): setImeWindowStatus(false,false)
W/BindingManager( 6362): Cannot call determinedVisibility() - never saw a connection for the pid: 6362
W/XT9_C   ( 1382): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1382): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1382): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1382): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/JsMessageQueue( 6362): Set native->JS mode to OnlineEventsBridgeMode
I/HtcModeClient( 3199): handler message = 4011
E/HtcModeClient( 3199): Check connection and retry 12 times.
D/jxcore_app_log( 6362): JniHelper::setJavaVM(0xaafc28f8), pthread_self() = -1406378840
I/chromium( 6362): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  966):  packet count Tx=156 Rx=250
E/WifiTrafficPoller(  966): notifying of data activity 0
D/WIFI_ICON( 1212): WifiActivity: 0
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  966): releaseHCC(1ad837fe): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  966): releaseHCC(1b936b5f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6362): Initializing JXcore engine
W/jxcore-log( 6362): JXcore engine is ready
,W/jxcore-log( 6362): Starting JXcore engine
,W/jxcore-log( 6362): Platform android
W/jxcore-log( 6362): 
,W/jxcore-log( 6362): Process ARCH arm
W/jxcore-log( 6362): 
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  966):  packet count Tx=156 Rx=250
,I/jxcore-log( 6362): JXcore Cordova bridge is ready!,
I/jxcore-log( 6362): 
W/jxcore-log( 6362): JXcore engine is started,
,E/jxcore  ( 6362): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6362): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6362): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,W/PluginManager( 6362): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 60ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  966): acquireWL(180095d3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 966 1000 null
W/HtcSystemUPManager(  966): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/ActivityManager(  966): Killing 5769:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=5769
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.resumeTopActivityInnerLocked:1873 
,I/ActivityManager(  966): Recipient 5769
,D/Process (  966): killProcessQuiet, pid=6097
I/ActivityManager(  966): Killing 6097:com.nero.android.htc.sync/u0a5 (adj 15): empty #18
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.resumeTopActivityInnerLocked:1873 
,I/ActivityManager(  966): Recipient 6097
D/WifiService(  966): Client connection lost with reason: 4
,I/FeedHostManager( 1488): [onResume]
I/FeedProviderManager( 1488): onResume
I/SocialFeedProvider( 1488): +onResume
I/SocialFeedProvider( 1488): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1488): -onResume
,D/StatusBarManagerService(  966): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
D/FindExtension( 1488): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1488): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  966): Disable input method client, pid=6362
I/PhoneStatusBar( 1212): setImeWindowStatus(false,false)
D/StatusBarManagerService(  966): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 6362): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  966): Enable input method client, pid=1488
,D/PMS     (  966): releaseWL(180095d3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  966): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  966): hiding MENU key
,D/Process (  966): killProcessQuiet, pid=5737
I/ActivityManager(  966): Killing 5737:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 ,
,I/ActivityManager(  966): Recipient 5737
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1212): WifiActivity: 3
E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=252
,E/WifiTrafficPoller(  966): notifying of data activity 3
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/OpenGLRenderer( 1488): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,E/WifiStateMachine(  966): handleMessage: E msg.what=131155
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1400855557] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
,E/WifiStateMachine(  966):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1400855555] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  966):  get link layer stats 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1365): environment dirty rate=50 [2][1][0]
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  966): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  966): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.06 txretriesrate=0.00 rxrate=4.86 userTriggerdPenalty0
E/WifiStateMachine(  966):  good link -> stuck count =0
E/WifiStateMachine(  966):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  966):  isHighRSSI       ---> score=65
D/WIFI_ICON( 1212): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  966): RSSI current: 3 new: -57, 3
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  966): handleMessage: X
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1212): WifiActivity: 0
,E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=252
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  966): notifying of data activity 0
,E/WifiDataStallTracker(  966): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  966): updateDataStallInfo: mDataStallTxRxSum={txSum=140 rxSum=115} preTxRxSum={txSum=138 rxSum=114},
D/WifiDataStallTracker(  966): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  966): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=252
,I/HtcModeClient( 3199): handler message = 4011,
,E/HtcModeClient( 3199): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3199): Don't start project servcice
,D/HtcModeClient( 3199): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3199): connectState: CONNECTION_READY = false
,D/SilentMusic( 3199): call stop
,D/HtcModeClient( 3199): close connection
,W/HtcModeClient( 3199): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3199): read the terminate packet, so break
,I/ActivityManager(  966): Killing 3199:com.htc.autobot/u0a47 (adj 15): empty #17
,D/Process (  966): killProcessQuiet, pid=3199
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 3199
,D/AccTypeManager( 1713): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 1488): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1488): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1488): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader(  966): Cannot find grip_rejection_width, use default value instead,
W/ResourcesManager(  966): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  966): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6419 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/AccTypeManager( 1713): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1713): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1432): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,E/ExternalAccountType( 1713): Unsupported attribute readOnly,
,W/ResourcesManager( 6419): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/WifiStateMachine(  966): handleMessage: E msg.what=131155
,E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400852548] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1400852546] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  966):  get link layer stats 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1365): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  966): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  966): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.53 txretriesrate=0.00 rxrate=2.93 userTriggerdPenalty0
E/WifiStateMachine(  966):  good link -> stuck count =0
E/WifiStateMachine(  966):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  966):  isHighRSSI       ---> score=61
E/WifiStateMachine(  966): handleMessage: X
,D/WIFI_ICON( 1212): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/PackageManager(  966): Unable to load service info ResolveInfo{3f77534 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  966): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  966): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  966): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  966): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  966): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  966): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  966): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  966): ,	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1828): DISABLE
,I/GCoreNlp( 1828): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6,
I/BackupManagerService(  966): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=253
D/WIFI_ICON( 1212): WifiActivity: 1
E/WifiTrafficPoller(  966): notifying of data activity 1
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiWatchdogStateMachine(  966): RSSI current: 3 new: -57, 3
,D/LocationProviderProxy(  966): applying state to connected service
D/PMS     (  966): acquireWL(7fbf3bc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  966): releaseWL(7fbf3bc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  966): applying state to connected service
,D/PMS     (  966): acquireWL(29f23f45): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): acquireWL(1d45a943): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  966): releaseWL(29f23f45): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(1d45a943): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel_SMS( 6419): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6419): MmsConfig.loadMmsSettings,
,I/ActivityManager(  966): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6449 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6419, uid=10112, userID:0,
,I/art     (  966): Explicit concurrent mark sweep GC freed 30086(1638KB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 19MB/28MB, paused 1.528ms total 141.957ms,
,W/Settings( 6419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6419): startup - clean
,W/HtcWrapAdjustableCursorFactory( 6449): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 6449): onCreate
,I/Babel   ( 6419): deleted: false for 0
,V/GetPrviateResource( 6449): GetPrviateResource
,D/MmsCustomizationProvider( 6449): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 6449): GetPrviateResource
,D/MessageCustFlag( 6449): sense_version=6.0
,D/BTAccessoryUtil( 6449): createReceiver,
D/MmsCustomizationProvider( 6449): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/BTAccessoryUtil( 6449): registerReceiver return intent = null
,I/Babel_SMS( 6419): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
D/MessageCustFlag( 6449): sku_id=118
I/Babel_SMS( 6419): MmsConfig.loadFromDatabase
,D/HtcBuildUtils( 6449): getRATByHtcTelephonyCapability:1,
W/SystemReader( 6449): Cannot find qct_8960_interface, use default value instead
,E/Babel_SMS( 6419): canonicalizeMccMnc: invalid mccmnc ,
I/Babel_SMS( 6419): MmsConfig.loadFromResources
,E/Babel_SMS( 6419): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6419): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6419, uid=10112, userID:0,
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6419, uid=10112, userID:0
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6419, uid=10112, userID:0
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6419, uid=10112, userID:0
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6419, uid=10112, userID:0
,D/PMS     (  966): acquireWL(2964746d): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6419 10112 null,
,I/[PluginManager]RegisterService( 1585): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1585): handle notify Blinkfeed plugin client changed
,W/VideoCapabilities( 6419): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 4391): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4391): Null package name or gms related package.  Ignoreing.
,D/PMS     (  966): acquireWL(38f4001c): PARTIAL_WAKE_LOCK  Icing 0x1 4391 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  966): acquireWL(994c425): PARTIAL_WAKE_LOCK  AsyncService 0x1 6004 10167 null
,D/PMS     (  966): releaseWL(994c425): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  966): acquireWL(2948cbab): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6004 10167 null
I/Icing   ( 4391): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 5852): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
D/PMS     (  966): releaseWL(2948cbab): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/PMS     (  966): releaseWL(38f4001c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,W/VideoCapabilities( 6419): Unsupported mime video/x-ms-wmv,
,W/Utils   ( 6419): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 6419): Unsupported mime audio/qcelp,
,W/AudioCapabilities( 6419): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6419): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6419): Unsupported mime video/x-ms-wmv
,I/UpdateIcingCorporaServi( 5852): UpdateCorporaTask done [took 65 ms] updated apps [took 65 ms] ,
,I/VideoCapabilities( 6419): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6419): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6419): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6419): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6419): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 6419): onServiceConnected,
,W/Babel   ( 6419): Attempted to change video mute state without an active call.,
,D/PMS     (  966): releaseWL(2964746d): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null,
,W/ResourcesManager( 6419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6419): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6419): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6419): Installed default security provider GmsCore_OpenSSL
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1212): WifiActivity: 0
E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=253
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
E/WifiTrafficPoller(  966): notifying of data activity 0
,I/ActivityManager(  966): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6488 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  966): acquireWL(35fa0a20): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{10076}
V/AlarmManager(  966): sending alarm PendingIntent{1f4c3fd9: PendingIntentRecord{9c17d9e com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454593061901, Int=60000
D/PMS     (  966): releaseWL(35fa0a20): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6488): SMSBackupAgentService started
,D/SMSBackup( 6488): Checking restore status
,D/SMSBackup( 6488): Restore complete
,D/SMSBackup( 6488): cancelCheckAlarm
,D/SMSBackup( 6488): SMSBackupAgentService completed: completed in 0.0 seconds
,I/ActivityManager(  966): Killing 5883:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=5883,
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 5883,
,I/Prism.ItemManager( 1488): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1488): loadItems() com.htc.launcher.pageview.WidgetManager@2685cc44 +
I/Prism.WidgetManager( 1488): onLoadItems() +
,E/Prism.WidgetManager( 1488): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1488): onLoadItems() -
I/Prism.ItemManager( 1488): loadItems() com.htc.launcher.pageview.WidgetManager@2685cc44 -
,D/PhoneApp( 1432): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1432): -- N1 =0
D/PhoneApp( 1432): -- N2 =0
D/PhoneApp( 1432): -- N3 =0
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=253
,D/Messaging( 6449): supportCMAS(SIE)/init? false/true,
,D/MmsConfig( 6449): networkCode: 
,D/MessageCustFlag( 6449): sku_id=118
,D/MmsConfig( 6449): SIE smsPri: null
D/MmsConfig( 6449): networkCode: ,
,D/MmsConfig( 6449): packageName: com.htc.vvm.att does not exist,
,D/Messaging( 6449): mNeedToUpdateDate2 start,
D/ReportIndicatorCache( 6449): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6449): 
D/MmsAsyncWorkHandler( 6449): HM tk = 20001
D/ReportIndicatorCache( 6449): MSG_QUERY_REPORTS >>
D/SettingsManager( 6449): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@188fc874
,D/DraftCache( 6449): [DraftCache/1] DraftCache.constructor,
D/DraftCache( 6449): [DraftCache/1] refresh
,D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
,D/MmsSmsV2Provider( 1432):  slotId = -1000
D/MmsSmsV2Provider( 1432): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1432): sku_id=118
,I/Messaging( 6449): mccmnc> 
D/MmsConfig( 6449): networkCode: ,
,D/DraftCache( 6449): [DraftCache/162] rebuildCache
D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
,D/MmsSmsV2Provider( 1432):  slotId = -1000
D/MmsSmsV2Provider( 1432): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1432):  slotId = -1000
D/MmsSmsV2Provider( 1432): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
D/MmsSmsV2Provider( 1432):  slotId = -1000
D/MmsSmsV2Provider( 1432): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6449): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/Messaging( 6449): ViewCache CreatePreloadOnlyConversationList
,D/Messaging( 6449): mNeedToUpdateDate2: false
,D/PhoneStorageUtil( 6449): HtcWrapEnvironment.getSupportedStorages() >1,
D/PhoneStorageUtil( 6449): HtcWrapEnvironment.hasRemovableStorageSlot()() >true,
D/PhoneStorageUtil( 6449): createReceiver
D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/Jerry   ( 1432): URI_DRAFT
,D/DraftCache( 6449): hasDraft() = false mNeedNotifyChange = true,
D/DraftCache( 6449): [DraftCache/162] rebuildCache time: 10
D/MmsAsyncWorkHandler( 6449): 
D/MmsAsyncWorkHandler( 6449): HM tk = 20002
,D/TelephUtils( 1432): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
V/MmsProvider( 1432): Update uri=content://mms, match=0
V/MmsProvider( 1432): selection=st=129 AND m_type!=134
,D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
D/AccFlag ( 1432): sku_id=118
D/MessageCustFlag( 6449): sense_version=6.0
,D/Jerry   ( 6449): start to preload cursor >>>>>>>
D/Messaging( 6449): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6449): TransactionService is going to be woken up.,
,V/TransactionService( 6449): 1-Creating TransactionService
,D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1432):  slotId = -1000
,D/Messaging( 6449): ViewCache CreatePreload,
D/Messaging( 6449): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1432): sku_id=118
,V/TransactionService( 6449): onStartCommand: 1,
D/MmsSystemEventReceiver( 6449): unRegisterForConnectionStateChanges,
,V/TransactionService( 6449): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6449): Loading previous transactions.
,D/Cust_MMSMS( 6449): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6449): def_index: 0
,D/MsgPreferenceUtils( 6449): globalIndex = 1
,D/TelephUtils( 1432): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
,D/AccFlag ( 1432): device_type: 1
,D/TransactionService( 6449): Force clearing mTransactionList,
D/TransactionService( 6449): Force set service start id to 1
V/TransactionService( 6449): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6449): unRegisterForConnectionStateChanges,
,D/TransactionService( 6449): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 6449): Destroying TransactionService
D/MsgPreferenceUtils( 6449): phone state: true
D/MsgPreferenceUtils( 6449): sd state: false
D/MsgPreferenceUtils( 6449): vIndex = 0
V/TransactionService( 6449): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,E/WifiStateMachine(  966): handleMessage: E msg.what=131155,
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1400849523] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
,E/WifiStateMachine(  966):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400849522] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  966):  get link layer stats 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1365): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
,E/WifiConfigStore(  966): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  966): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.26 txretriesrate=0.00 rxrate=1.96 userTriggerdPenalty0
E/WifiStateMachine(  966):  good link -> stuck count =0
E/WifiStateMachine(  966):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  966):  isHighRSSI       ---> score=61,
,D/WifiWatchdogStateMachine(  966): RSSI current: 3 new: -57, 3
D/WIFI_ICON( 1212): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  966): handleMessage: X
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=254
,D/WIFI_ICON( 1212): WifiActivity: 1
E/WifiTrafficPoller(  966): notifying of data activity 1
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiDataStallTracker(  966): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  966): updateDataStallInfo: mDataStallTxRxSum={txSum=140 rxSum=115} preTxRxSum={txSum=140 rxSum=115}
D/WifiDataStallTracker(  966): updateDataStallInfo: NONE
D/WifiDataStallTracker(  966): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1212): WifiActivity: 0
E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=254
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  966): notifying of data activity 0,
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=254
,D/Process (  966): killProcessQuiet, pid=6161,
I/ActivityManager(  966): Killing 6161:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 6161
,I/PMS     (  966): Going to sleep due to screen timeout (uid 1000)...,
,D/ActivityManager(  966): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{2ae7d103 #7 A=.Prism U=0 sz=1}
W/PMS     (  966): mWirelessDisplayManager is null
,W/PMS     (  966): mWirelessDisplayManager is still null
,I/SensorManager(  966): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@133918b4
W/SensorService(  966): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  966): disable: get sensor name = Accelerometer Sensor
W/SensorService(  966): pid=966, uid=1000
W/SensorService(  966): Active sensors: size = 4
W/SensorService(  966): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  966): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  966): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  966): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  966): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@133918b4, eanble = 0, strlen(mName) = 91
W/SensorService(  966): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  966): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@269a182e
W/SensorService(  966): Listener[1] = com.htc.smartdim.sensor_eye@14285c86
W/SensorService(  966): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  966): Sleeping (uid 1000)...
D/XAN-DPS (  966): prepareColorFade 1
W/PMN     (  966): goingToSleep
,D/PMS     (  966): acquireWL(11b51880): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 966 1000 null
I/FeedHostManager( 1488): [onPause]
I/FeedProviderManager( 1488): onPause
W/PMN     (  966): goingToSleep done
I/FeedHostManager( 1488): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@33b28c1d
I/SocialFeedProvider( 1488): +onPause
I/SocialFeedProvider( 1488): -onPause
,I/ActivityManager(  966): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6537 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,D/AlarmManager(  966): ACTION_SCREEN_ON
I/AlarmManager(  966): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  966): [AlarmQueuing] done recovering
,I/AlarmManager(  966): [AlarmQueuing] recover EPS screen off blocked alarms
,I/Adreno-EGL(  966): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  966): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  966): Build Date: 03/09/15 Mon
I/Adreno-EGL(  966): Local Branch: 
I/Adreno-EGL(  966): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  966): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  966):                  d74aa161a12b9c6fc6332151
I/AlarmManager(  966): [AlarmQueuing] done EPS screen off alarm recovering
W/HtcSystemUPManager(  966): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/PMS     (  966): releaseWL(11b51880): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL true Token 11
,E/WifiTrafficPoller(  966):  packet count Tx=158 Rx=255
E/WifiTrafficPoller(  966): notifying of data activity 1
,E/WifiDataStallTracker(  966): ENABLE_DATA_MONITOR_POLL true Token 1
,D/WIFI_ICON( 1212): WifiActivity: 1
,D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
,D/WifiDataStallTracker(  966): updateDataStallInfo: mDataStallTxRxSum={txSum=140 rxSum=115} preTxRxSum={txSum=140 rxSum=115},
,D/WifiDataStallTracker(  966): updateDataStallInfo: NONE
D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
D/WifiDataStallTracker(  966): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  966): handleMessage: E msg.what=131167
E/WifiStateMachine(  966): processMsg: ConnectedState
W/HtcLockScreen( 1212): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
E/WifiStateMachine(  966):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  966): processMsg: SupplicantStartedState
E/WifiStateMachine(  966):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  966):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SET_SCREEN_ON 1'
,I/wpa_supplicant( 1365): SET_SCREEN_ON:On
I/wpa_supplicant( 1365): htc_wext_set_keepalive +
I/wpa_supplicant( 1365): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1365): getPrivFuncNum +	
I/wpa_supplicant( 1365): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1365): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1365): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1365): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1365): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  966): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  966): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  966): handleScreenStateChanged Exit: true
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131154
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SIGNAL_POLL'
V/SRS_Proc(  399): ParamSet string: screen_state=on
E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  966): handleMessage: E msg.what=155650
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
D/GpsLocationProvider(  966): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/wpa_supplicant( 1365): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  966): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
D/NetworkPolicy(  966): updateScreenOn: false
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131127
V/NetworkPolicy(  966): updateIfacesLocked()
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
D/NetworkManagementService(  966): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131129
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1365): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1365): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  966): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=31 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  966): handleMessage: X
,W/ResourcesManager( 6537): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/Process (  966): killProcessQuiet, pid=6184
I/ActivityManager(  966): Killing 6184:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/XAN-DPS (  966): prepareColorFade done
D/XAN-DPS (  966): setBrightness to 0
,I/ActivityManager(  966): Recipient 6184
,I/SensorManager(  966): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@269a182e,
I/DisplayManagerService(  966): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,W/SensorService(  966): Following SensorService logs are not warning, just make sure they are printed
V/ActivityManager(  966): Display changed displayId=0
W/SensorService(  966): disable: get sensor name = CM32181 Light sensor
D/DotMatrix( 1308): [EventService]  onDisplayChanged: 0
W/SensorService(  966): pid=966, uid=1000
W/SensorService(  966): Active sensors: size = 3
W/SensorService(  966): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  966): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  966): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  966): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@269a182e, eanble = 0, strlen(mName) = 67
W/SensorService(  966): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  966): Listener[0] = com.htc.smartdim.sensor_eye@14285c86
W/SensorService(  966): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
,D/DotMatrix( 1308): [EventService] mbHDMIConnect: false, mCoverOn:false
,I/IntentController( 1212): receive(android.intent.action.SCREEN_ON,1,false)
,I/CalendarProvider2( 6537): Created com.android.providers.calendar.CalendarAlarmManager@1e083847(com.htc.providers.calendar.HtcCalendarProvider@188fc874)
,D/CalendarProvider2( 6537): wait start:true
,D/PMS     (  966): acquireWL(bbd1762): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1828 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  966): acquireWL(146f00f3): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(bbd1762): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  966): releaseWL(146f00f3): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 6537): wait end:false
,I/ActivityManager(  966): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6568 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/AlarmManager(  966): ACTION_SCREEN_OFF,
,E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 12
I/AlarmManager(  966): [AlarmQueuing] screen off now: 
D/WifiDataStallTracker(  966): stopDataStallAlarm 
I/AlarmManager(  966): [AlarmQueuing] data connection: true
E/WifiDataStallTracker(  966): ENABLE_DATA_MONITOR_POLL false Token 2
I/AlarmManager(  966): [AlarmQueuing] wifi connection: true
E/WifiStateMachine(  966): handleMessage: E msg.what=131167
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  966): processMsg: SupplicantStartedState
E/WifiStateMachine(  966):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  399): ParamSet string: screen_state=off
E/WifiStateMachine(  966):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1365): SET_SCREEN_ON:Off
I/wpa_supplicant( 1365): htc_wext_set_keepalive +
I/wpa_supplicant( 1365): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1365): getPrivFuncNum +	
I/wpa_supplicant( 1365): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1365): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1365): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1365): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1365): htc_wext_set_keepalive - ret = 0
D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
E/WifiStateMachine(  966): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiController(  966): handleMessage: E msg.what=155651
D/WifiController(  966): processMsg: DeviceActiveState
,D/WifiController(  966): processMsg: StaEnabledState
D/NetworkPolicy(  966): updateScreenOn: false
D/WifiController(  966): processMsg: DefaultState
V/NetworkPolicy(  966): updateIfacesLocked()
D/WifiController(  966): handleMessage: X
D/GpsLocationProvider(  966): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/WifiStateMachine(  966): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  966): handleScreenStateChanged Exit: false
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/NetworkManagementService(  966): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  966): handleMessage: X
,E/WifiStateMachine(  966): handleMessage: E msg.what=131155
E/WifiStateMachine(  966): processMsg: ConnectedState
,E/WifiStateMachine(  966):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1400846503] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400846502] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  966): handleMessage: X
I/SensorManager( 1212): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@3fcf3ac6, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  966): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  966): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  966): pid=1212, uid=10041
,W/SensorService(  966): Active sensors: size = 4
W/SensorService(  966): Accelerometer Sensor (handle=0x00000000, connections=1)
,W/SensorService(  966): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  966): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  966): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  966): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@3fcf3ac6, eanble = 1, strlen(mName) = 57
,W/SensorService(  966): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  966): Listener[0] = com.htc.smartdim.sensor_eye@14285c86
W/SensorService(  966): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@3fcf3ac6
W/SensorService(  966): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL false Token 13 num clients 6
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] getTotalRam: 1842 Mb
,I/IntentController( 1212): receive(android.intent.action.SCREEN_OFF,1,false)
,D/PMS     (  966): acquireWL(14d947ae): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  966): releaseWL(14d947ae): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/ContactMessageStore( 1432): start background delete task...
D/PMS     (  966): acquireWL(32eeb94f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1828 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  966): releaseWL(32eeb94f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/ContactMessageStore( 1432): size: 0 , 0
D/ContactMessageStore( 1432): Background delete complete
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
W/ContextImpl( 6568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  966): Setting HAL interactive mode to false
D/SurfaceControl(  966): Excessive delay in setPowerMode(): 298ms
D/PMS     (  966): Setting HAL interactive mode to false done
D/PMS     (  966): Setting HAL auto-suspend mode to true
D/PMS     (  966): Setting HAL auto-suspend mode done
,W/HtcSystemUPManager(  966): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006,
D/PowerUsageList:PowerUsageHelper( 6568): MY_DEBUG = false
D/HABCtrl (  966): TPE algorithm. remove timeout.
I/InputMethodManagerService(  966): screenObserver, isScreenOn=false
D/StatusBarManagerService(  966): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  966): Disable input method client, pid=1488
D/PMS     (  966): OOBE c monitor 11
,I/PhoneStatusBar( 1212): setImeWindowStatus(false,false)
,D/PMS     (  966): acquireWL(357630ba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
,I/BatteryService(  966): n_update end
,D/PMS     (  966): releaseWL(357630ba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NfcService( 1452): ScreenObserver: OFF
,D/NfcService( 1452): applyRouting - 0
D/HtcPowerSaver(  966): updateBatteryInfo
,D/PMS     (  966): acquireWL(30079b6b): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1452 1027 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NfcService( 1452): applyRouting -2
D/NfcService( 1452): applyRouting
D/NfcService( 1452): Ignore this applyRouting...
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/PMS     (  966): releaseWL(30079b6b): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1212): closing low battery warning: level=100
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PMS     (  966): runPSCheck
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
,D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  966): << updateStatus
D/SmartSyncUtils( 6568): isEpsOn(), nState = 0
,I/InputManager(  966): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
I/IntentController( 1212): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/PMS     (  966): acquireWL(2459f6c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6568 1000 null
I/RemoteViews( 1212): setHTCTheme(com.htc.updater,true,33751145)
,I/RemoteViews( 1212): apply : com.htc.updater 1 17 1 36
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  966): releaseWL(2459f6c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartDim(  966): Init customizeScreenOffDelayClass error
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 6568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6568): isEpsOn(), nState = 0
D/SmartSyncUtils( 6568): isEpsOn(), nState = 0,
,W/ContextImpl( 6568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/ClockController( 1212): stop clock update:screen off
,W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  966): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@14285c86
W/SensorService(  966): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  966): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  966): pid=966, uid=1000
,W/SensorService(  966): Active sensors: size = 3
,W/SensorService(  966): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  966): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  966): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  966): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@14285c86, eanble = 0, strlen(mName) = 36
W/SensorService(  966): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  966): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3fcf3ac6
W/SensorService(  966): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  966): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  966): disable: get sensor name = CM36686 Proximity sensor
W/SensorService(  966): pid=966, uid=1000
W/SensorService(  966): Active sensors: size = 2
W/SensorService(  966): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  966): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  966): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@14285c86, eanble = 0, strlen(mName) = 36
W/SensorService(  966): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  966): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3fcf3ac6
W/SensorService(  966): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  966): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@14285c86
,E/ActivityThread(  966): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@37046947 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  966): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@37046947 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  966): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  966): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  966): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  966): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  966): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  966): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  966): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  966): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  966): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  966): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  966): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  966): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  966): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  966): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  966): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  966): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  966): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  966): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  966): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6602 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/PowerUsageList:PowerUsageHelper( 6568): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/SmartSyncUtils( 6568): getMobilePolicyEnabled, result = true
,D/Process (  966): killProcessQuiet, pid=5976
I/ActivityManager(  966): Killing 5976:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/PowerUsageList:BatterySipperExt( 6568): gen(), null == sipper.uidObj, userId = 0
,D/WifiService(  966): New client listening to asynchronous messages,
E/WifiTrafficPoller(  966): ADD_CLIENT: 7
,I/ActivityManager(  966): Recipient 5976,
,D/PowerUsageList:PowerUsageHelper( 6568): MY_DEBUG = false,
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL false Token 13 num clients 7
,I/ActivityManager(  966): Killing 6216:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
D/Process (  966): killProcessQuiet, pid=6216
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 6216
,I/CalendarProvider2( 6537): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6537): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  966): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6626 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  966): killProcessQuiet, pid=5616,
,I/ActivityManager(  966): Killing 5616:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 5616,
,W/ResourcesManager( 6626): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6626): onCreate
,D/ProviderChangeReceiver( 6626): ---------------------------------------------------
,D/ProviderChangeReceiver( 6626): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  966): killProcessQuiet, pid=5368
I/ActivityManager(  966): Killing 5368:com.htc.mediamanager/u0a28 (adj 15): empty #17
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6626): start to updateAlertNotification!
,I/ActivityManager(  966): Recipient 5368
,D/PMS     (  966): releaseWL(ace67b1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/HtcAlertService( 6626): No fired or scheduled alerts
D/HtcAlertUtils( 6626): -- cancelReminderNotification --
,D/HtcAlertUtils( 6626): broadcastExistReminder!
,D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  966): handleMessage: E msg.what=131155
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2730] from screen [on:0 period:-1400843771] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1400843769] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  966): handleMessage: X
,E/WifiDataStallTracker(  966): DATA_MONITOR_POLL false Token 3
,D/HtcUPManager( 1212): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  966): DATA_MONITOR_POLL false Token 3,
,D/ContactMessageStore( 1432): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1432): MSG_NOTIFY_CS_TO_SYNC <<,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/libc    (  966): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4,
D/PMS     (  966): acquireWL(2b828347): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{1000}
D/libc    (  966): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  966): sending alarm PendingIntent{1a7bb774: PendingIntentRecord{104aa49d android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=113222, Int=0
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
V/AlarmManager(  966): sending alarm PendingIntent{a278d3: PendingIntentRecord{c2fec10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=126071, Int=0
D/libc    (  966): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  966): [NET] android_getaddrinfo_proxy+
D/libc    (  966): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/PMS     (  966): releaseWL(2b828347): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1212): Weather sync is On,
W/WeatherTimeKeeper( 1212): [refreshWeatherData] no weather data
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  966): [NET] android_getaddrinfo_proxy-, success
,D/AlarmManager(  966): Ignore time set to 1454593080165 in setTime(); too close to current time 1454593080089,
,I/ActivityManager(  966): Killing 5524:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=5524,
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 5524
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  966): acquireWL(1c5e1d12): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{10024},
,V/AlarmManager(  966): sending alarm PendingIntent{eda0ce3: PendingIntentRecord{1d56d6e0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143069, Int=0
,D/PMS     (  966): releaseWL(1c5e1d12): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  966): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  966): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  966): acquireWL(4b1ed99): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 966 1000 null
,D/libc    (  966): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  966): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  966): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  966): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  966): [NET] android_getaddrinfo_proxy+
D/libc    (  966): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  966): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  966): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  966): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  966): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  966): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  966): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  966):  [handleDownloadXtraData]inject done.
D/PMS     (  966): acquireWL(3aaaca55): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 966 1000 null
,D/PMS     (  966): releaseWL(4b1ed99): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  966): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  966): releaseWL(3aaaca55): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1432): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1432): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  966): acquireWL(171c3c6a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null,
I/BatteryService(  966): n_update end
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): releaseWL(171c3c6a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): runPSCheck
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  966): Checking...
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  966): >> updateStatus
D/PowerUI ( 1212): closing low battery warning: level=100
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  966): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  966): << updateStatus
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1432): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  966): acquireWL(156a355b): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{19dca1f8: PendingIntentRecord{3a1ab6d1 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454593120933, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{a278d3: PendingIntentRecord{c2fec10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=186071, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{17b9b536: PendingIntentRecord{d0ccc37 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203278, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{1e35e5a4: PendingIntentRecord{9c2ef0d com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190868, Int=0
D/PMS     (  966): acquireWL(3de3eec2): PARTIAL_WAKE_LOCK  *backup* 0x1 966 1000 null
D/PMS     (  966): acquireWL(38d7f4d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  966): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  966): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  966): releaseWL(156a355b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/PMS     (  966): releaseWL(3de3eec2): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/WeatherUtility( 1212): Weather sync is On
W/WeatherTimeKeeper( 1212): [refreshWeatherData] no weather data
,D/PMS     (  966): acquireWL(2ebdb810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(38d7f4d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  966): releaseWL(2ebdb810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  966): acquireWL(ff4941a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  966): releaseWL(ff4941a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): acquireWL(365f2b4b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  966): releaseWL(365f2b4b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): acquireWL(2cb87928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): acquireWL(1c65f641): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  966): acquireWL(26f33127): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  966): releaseWL(2cb87928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1910): Vacuum at: now=1454593157458 tag=VacuumService
,I/GoogleURLConnFactory( 1910): Using platform SSLCertificateSocketFactory,
,D/PMS     (  966): releaseWL(1c65f641): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  966): acquireWL(1dab57d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(1dab57d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  966): acquireWL(9198c72): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1910): No account for auth token provided,
,D/PMS     (  966): releaseWL(9198c72): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1910): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1910): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1910): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1910): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1910): [NET] android_getaddrinfo_proxy+
D/libc    ( 1910): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1910): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1910): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1910): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1910): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1910): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1910): No account for auth token provided,
,W/Uploader( 1910): No account for auth token provided,
,W/Uploader( 1910):  no longer exists, so no auth token.,
,W/Uploader( 1910): No account for auth token provided,
,I/art     ( 1910): Explicit concurrent mark sweep GC freed 27650(1482KB) AllocSpace objects, 6(460KB) LOS objects, 47% free, 4MB/8MB, paused 1.562ms total 100.214ms,
,I/art     (  966): Explicit concurrent mark sweep GC freed 32088(1764KB) AllocSpace objects, 4(1052KB) LOS objects, 33% free, 18MB/28MB, paused 1.555ms total 165.801ms,
,I/GLSUser ( 1910): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1910): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1910): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1910): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1212): reapply : com.google.android.gms 2 40
,E/Uploader( 1910): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1910): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1910): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1910): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1910): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1910): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1910): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1910): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1910): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1910): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1910): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1910): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1910): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  966): releaseWL(26f33127): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): acquireWL(674b217): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(674b217): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  966): acquireWL(22bd0604): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(22bd0604): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1212): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
D/HtcUPManager( 1212): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1585): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@d0dbc1e
I/ActivityManager(  966): Killing 6315:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=6315
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 6315
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  966): acquireWL(d68f7ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(d68f7ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  966): updateBatteryInfo
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PowerUI ( 1212): closing low battery warning: level=100
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PMS     (  966): runPSCheck
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  966): >> updateStatus,
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  966): battery changed pluggedType: 2
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: X
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1365): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1365): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1365): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,D/PMS     (  966): acquireWL(1f89f622): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(1f89f622): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1212): closing low battery warning: level=100
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  966): battery changed pluggedType: 2
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): processMsg: DeviceActiveState
,D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  966): acquireWL(370858b3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000},
V/AlarmManager(  966): sending alarm PendingIntent{a278d3: PendingIntentRecord{c2fec10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=246072, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{32ea25e9: PendingIntentRecord{75526e com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454593295378, Int=0
,D/PMS     (  966): releaseWL(370858b3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1212): Weather sync is On
,W/WeatherTimeKeeper( 1212): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  966): acquireWL(2025cd0f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(2025cd0f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  966): updateBatteryInfo
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/NotificationService(  966): plugged=true pluggin=true
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1212): closing low battery warning: level=100
D/UsbnetService(  966): onReceive BATTERY_CHANGED
,D/PMS     (  966): runPSCheck
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  966): >> updateStatus
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: E msg.what=155652
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): processMsg: DeviceActiveState
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): processMsg: StaEnabledState
I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): processMsg: DefaultState
,D/WifiController(  966): handleMessage: X
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1910): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1910): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1910): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1910): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1212): reapply : com.google.android.gms 3 40
W/GLSActivity( 1910): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1910): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1910): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1910): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1910): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1910): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1910): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5934): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5934): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5934): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
,E/PlayEventLogger( 5934): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5934): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5934): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5934): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5934): Ignoring header User-Agent because its value was null.
,D/libc    ( 5934): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5934): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5934): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5934): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5934): [NET] android_getaddrinfo_proxy+
D/libc    ( 5934): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5934): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  966): acquireWL(1e5b5b59): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  966): n_update end
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): releaseWL(1e5b5b59): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  966): updateBatteryInfo
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/PowerUI ( 1212): closing low battery warning: level=100
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PMS     (  966): runPSCheck
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: DeviceActiveState
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): processMsg: StaEnabledState
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): processMsg: DefaultState
,I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): handleMessage: X
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  966): acquireWL(291331e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{a278d3: PendingIntentRecord{c2fec10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=366072, Int=0
,I/ActivityManager(  966): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6662 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  966): sending alarm PendingIntent{3c9a17ff: PendingIntentRecord{f2619cc com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454593407580, Int=0
,D/PMS     (  966): releaseWL(291331e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1212): Weather sync is On
W/WeatherTimeKeeper( 1212): [refreshWeatherData] no weather data
,E/cutils-trace( 6683): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6683): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6683): dex2oat: override thread count:4
,I/dex2oat ( 6683): dex2oat took 711.808ms (threads: 4)
,I/PushClient( 6662): ApplicationMonitor {2541fa99}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6662): ApplicationMonitor {2541fa99}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6662): ApplicationMonitor {2541fa99}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6662): ApplicationMonitor {2541fa99}: logBasicAppInfo(): VersionCode:             148001224,
I/PushClient( 6662): ApplicationMonitor {2541fa99}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6662): ApplicationMonitor {2541fa99}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6662): ApplicationMonitor {2541fa99}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false,
,I/PushClient( 6662): ApplicationMonitor {2541fa99}: logBasicAppInfo(): Htc_DEBUG_flag:          false,
,I/PushClient( 6662): ApplicationMonitor {2541fa99}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6662): PnsModel {171af7e0}: update(): Update registration caused by: alarm
,I/PushClient( 6662): PnsConfigModel {ae9c137}: <init>(): Use dm-client for provisioning.
,W/System.err( 6662): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 6662): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6662): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6662): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  966): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6691 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6691): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6691 dbg=false s=true
,I/DeviceManagement( 6691): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6691): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6691): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6691): WorkflowService: Starting workflow service
,I/DeviceManagement( 6691): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@171af7e0] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6691): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6691): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6691): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6691): SessionStateController: Checking invariants...
,I/DeviceManagement( 6691): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6691): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6691): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6691): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@171af7e0],
,I/DeviceManagement( 6691): WorkflowService: Stopping workflow service
,D/Process (  966): killProcessQuiet, pid=6271
I/ActivityManager(  966): Killing 6271:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 6271
,I/PushClient( 6662): PnsModel {171af7e0}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  966): killProcessQuiet, pid=6362
,I/ActivityManager(  966): Killing 6362:com.test.thalitest/u0a366 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/InputEventReceiver( 1382): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{21aa9fd1 uid 10366 pid 6362} (c)'
I/ActivityManager(  966): Recipient 6362
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  966): acquireWL(29fcccc9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(29fcccc9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  966): updateBatteryInfo
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1212): closing low battery warning: level=100
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): runPSCheck
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): handleMessage: E msg.what=155652
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  966): acquireWL(137e9fce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(137e9fce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1212): closing low battery warning: level=100
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0,
D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): runPSCheck
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  966): Checking...
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  966): acquireWL(8eefeef): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
,I/BatteryService(  966): n_update end
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): releaseWL(8eefeef): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/PowerUI ( 1212): closing low battery warning: level=100
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): battery changed pluggedType: 2
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): processMsg: DeviceActiveState
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true,
,D/HtcPowerSaver(  966): updateBatteryInfo
D/PMS     (  966): runPSCheck
D/HtcPowerSaver(  966): Checking...
,I/HtcPowerSaver(  966): >> updateStatus
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1432): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1432): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1432): sku_id=118
D/ContactMessageStore( 1432): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1432): start background delete task...
,D/ContactMessageStore( 1432): size: 0 , 0
,D/ContactMessageStore( 1432): Background delete complete
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): acquireWL(3b498dfc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
I/BatteryService(  966): n_update end
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): releaseWL(3b498dfc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/PowerUI ( 1212): closing low battery warning: level=100
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): runPSCheck
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  966): Checking...
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  966): processMsg: DefaultState
I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): handleMessage: X
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  966): acquireWL(347c6c85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(347c6c85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  966): battery changed pluggedType: 2
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/PMS     (  966): runPSCheck
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PowerUI ( 1212): closing low battery warning: level=100
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  966): acquireWL(35e8eada): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(35e8eada): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  966): updateBatteryInfo
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1212): closing low battery warning: level=100
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): Checking...
I/HtcPowerSaver(  966): >> updateStatus
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): processMsg: DeviceActiveState
,D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  966): acquireWL(2a569b0b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
,V/AlarmManager(  966): sending alarm PendingIntent{a278d3: PendingIntentRecord{c2fec10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=486071, Int=0
,I/bt-btm  ( 3072): Received oneshot timer event complete
D/PMS     (  966): acquireWL(1f9f8de8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3072 1002 null
I/bt-btm  ( 3072): btm_ble_timeout,
V/AlarmManager(  966): sending alarm PendingIntent{3d9c4c01: PendingIntentRecord{247adaa6 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941635, Int=0
I/bt-btm  ( 3072): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3072): btm_ble_rand_enc_complete
I/bt-btm  ( 3072): btm_gen_resolve_paddr_low
D/bt-smp  ( 3072): smp_encrypt_data
W/bt-smp  ( 3072): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3072): Plain text(LSB ~ MSB) = 55 67 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3072): Encrypted text(LSB ~ MSB) = d4 bf 73 bf de 61 2a 7c ab de 89 d5 de 59 13 db 
I/bt-btm  ( 3072): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3072): Stopping oneshot timer
D/bt-btm  ( 3072): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  966): releaseWL(2a569b0b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1212): Weather sync is On,
W/WeatherTimeKeeper( 1212): [refreshWeatherData] no weather data
,I/art     ( 1488): Background sticky concurrent mark sweep GC freed 66085(4MB) AllocSpace objects, 5(512KB) LOS objects, 12% free, 32MB/37MB, paused 15.076ms total 53.638ms,
,D/PMS     (  966): releaseWL(1f9f8de8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  966): acquireWL(3951dce7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(3951dce7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): Checking...
I/HtcPowerSaver(  966): >> updateStatus
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): processMsg: DeviceActiveState
I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): processMsg: StaEnabledState
D/PowerUI ( 1212): closing low battery warning: level=100
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: X
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  966): acquireWL(1ad3a094): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{4b051ee: PendingIntentRecord{41d968f android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806207, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{a278d3: PendingIntentRecord{c2fec10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=966072, Int=0
,D/Finsky  ( 5934): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  966): sending alarm PendingIntent{28e9fb32: PendingIntentRecord{958de0b com.android.vending startService}}, i=null, t=0, cnt=1, w=1454593639417, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{30d56083: PendingIntentRecord{36943200 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454593824340, Int=1800000
,V/AlarmManager(  966): sending alarm PendingIntent{b8987e: PendingIntentRecord{3c8381df com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=938077, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{270a6e2c: PendingIntentRecord{2052edda com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454593921738, Int=0
,D/PMS     (  966): acquireWL(17c64118): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4391 10024 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  966): acquireWL(38853956): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1910 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  966): acquireWL(16b5cdd7): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4391 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(38853956): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  966): releaseWL(17c64118): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  966): acquireWL(3e9f7073): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1212): Weather sync is On
W/WeatherTimeKeeper( 1212): [refreshWeatherData] no weather data
,W/ContextImpl( 6568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6568): MY_DEBUG = false
,D/PMS     (  966): releaseWL(1ad3a094): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageService( 6568): repeat time = 1454594821819
,I/EventLogService( 4391): Aggregate from 1454593050664 (log), 1454592024300 (data)
,D/PMS     (  966): acquireWL(1a9bba5c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1910): Message class com.google.f.a.a.i,
,D/PMS     (  966): acquireWL(63e9165): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(1a9bba5c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(3e9f7073): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(16b5cdd7): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/GLSUser ( 1910): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1910): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1910): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1910): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5934): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 6568): PowerProfile::POWER_SCREEN_FULL = 154.8,
I/GLSUser ( 1910): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1910): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1910): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1910): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerUsageList:BatterySipperExt( 6568): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  966): releaseWL(63e9165): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  966): acquireWL(237ff4db): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  966): releaseWL(237ff4db): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/PMS     (  966): acquireWL(6c08724): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1910 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(6c08724): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GLSUser ( 1910): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1910): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1910): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1910): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5934): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1910): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1910): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1910): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1910): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1910): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5934): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
D/Finsky  ( 5934): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5934): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5934): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2),
,D/DeviceConnectionService( 1828): client connected with version: 7571000,
,D/PMS     (  966): acquireWL(30a0c843): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{10072}
V/AlarmManager(  966): sending alarm PendingIntent{184bdec0: PendingIntentRecord{3670cab com.android.vending startService}}, i=null, t=0, cnt=1, w=1454593937139, Int=0
D/PMS     (  966): releaseWL(30a0c843): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 5934): [592] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5934): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  966): acquireWL(3eac87f9): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{1000},
V/AlarmManager(  966): sending alarm PendingIntent{2479f33e: PendingIntentRecord{ffda59f com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454593967096, Int=0
D/SmartSyncUtils( 6568): isEpsOn(), nState = 0
,D/PMS     (  966): releaseWL(3eac87f9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  966): acquireWL(f7026ec): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6568 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6568): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6568): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6568): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6568): SettingOnTime = 1454652000000, randomSettingOnTime = 1454650329000
D/SmartSyncScreenOnOffTimeReceiver( 6568): SettingOffTime = 1454630400000, randomSettingOffTime = 1454633869000
D/SmartSyncScreenOnOffTimeReceiver( 6568): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6568): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6568): bNightModeTurnOffOnce = false
,D/PMS     (  966): releaseWL(f7026ec): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  966): acquireWL(524aab5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(524aab5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  966): updateBatteryInfo
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1212): closing low battery warning: level=100
,D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  966): >> updateStatus
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
,D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  966): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: E msg.what=155652,
I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  966): acquireWL(199e054a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(199e054a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  966): updateBatteryInfo
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): battery changed pluggedType: 2
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1212): closing low battery warning: level=100
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true,
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): acquireWL(2f20fcbb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
D/UsbnetService(  966): onReceive BATTERY_CHANGED
I/BatteryService(  966): n_update end
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  966): releaseWL(2f20fcbb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/NotificationService(  966): plugged=true pluggin=true
D/PowerUI ( 1212): closing low battery warning: level=100
D/WifiController(  966): handleMessage: E msg.what=155652
D/PMS     (  966): runPSCheck
D/WifiController(  966): processMsg: DeviceActiveState
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): processMsg: StaEnabledState
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
D/WifiController(  966): battery changed pluggedType: 2
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  966): User[0] Flushing usage stats to disk
,D/PMS     (  966): acquireWL(11aec5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(11aec5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
,D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1212): closing low battery warning: level=100
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): updateBatteryInfo
D/WifiController(  966): handleMessage: E msg.what=155652
D/PMS     (  966): runPSCheck
D/WifiController(  966): processMsg: DeviceActiveState
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): processMsg: StaEnabledState
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,W/ContextImpl( 6568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5905): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5905): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5905): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5905): Cust_ConnectToPC   : spcsc>false
D/        ( 5905): Cust_ConnectToPC   : IPT>true
,D/        ( 5905): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 5905): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 5905): Index of the first 1 = -1
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 5905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5905): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5905): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5905): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5905): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5905): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 5905): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,TIME-OUT KILL (timeout was 1200000ms)
```
