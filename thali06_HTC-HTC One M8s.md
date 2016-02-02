#### Test 579720943a29850_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:2879] from screen [on:0 period:-1579067148] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579067147] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1344): environment dirty rate=12 [16][2][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.10 txretriesrate=0.00 rxrate=6.60 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  968): handleMessage: X
--------- beginning of system
D/WIFI_ICON( 1241): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/cutils-trace( 6412): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6412): ====startRecUseTime====
D/htc.customization.log.level( 6412):  is 
W/CustomizationLogLevel( 6412): Level value is invalid, use default level 2
D/CustomizationManager( 6412):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 6412): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6412): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6412): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6412): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6412): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6412): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6412): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6412): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6412): Parsing tag category name = system
I/CustomizationCIDLoader( 6412): Parsing tag category name = application
I/CustomizationCIDLoader( 6412): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6412): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6412): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6412): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6412): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6412): add string-array item, value = 42507
I/CustomizationCIDLoader( 6412): add string-array item, value = 21902
I/CustomizationCIDLoader( 6412): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6412): add string-array item, value = 23420
I/CustomizationCIDLoader( 6412): add string-array item, value = 22299
I/CustomizationCIDLoader( 6412): add string-array item, value = 24002
I/CustomizationCIDLoader( 6412): add string-array item, value = 23210
I/CustomizationCIDLoader( 6412): add string-array item, value = 23205
I/CustomizationCIDLoader( 6412): add string-array item, value = 23806
I/CustomizationCIDLoader( 6412): add string-array item, value = 23430
I/CustomizationCIDLoader( 6412): add string-array item, value = 23408
I/CustomizationCIDLoader( 6412): add string-array item, value = 27205
I/CustomizationCIDLoader( 6412): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6412): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6412):  Read CID file spent 0.093 (s)
D/CustomizationManager( 6412):  All configurations done spent 0.093 (s)
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6412 on display 0
D/PMS     (  968): acquireHCC(371dd375): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 968 1000 null
D/PMS     (  968): acquireHCC(f9edf0a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 968 1000 null
D/PMS     (  968): acquireWL(60531f1): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 968 1000 null
I/AnimationUtil(  968): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1563): [onPause]
I/FeedProviderManager( 1563): onPause
I/FeedHostManager( 1563): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3308e44b
I/SocialFeedProvider( 1563): +onPause
I/SocialFeedProvider( 1563): -onPause
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6430 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  451): Explicit concurrent mark sweep GC freed 8665(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 248us total 19.220ms
I/art     (  451): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 241us total 14.631ms
I/art     (  451): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 358us total 16.702ms
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
D/StatusBarManagerService(  968): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
I/TrimMemoryManager( 1563): [trimMemory] 20
,I/WebViewFactory( 6430): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6430): Time to load native libraries: 12 ms (timestamps 853-865)
I/LibraryLoader( 6430): Expected native library version number "",actual native library version number ""
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=141 Rx=229
E/WifiTrafficPoller(  968): notifying of data activity 0
V/WebViewChromiumFactoryProvider( 6430): Binding Chromium to main looper Looper (main, tid 1) {157633a7}
I/LibraryLoader( 6430): Expected native library version number "",actual native library version number ""
I/chromium( 6430): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/WIFI_ICON( 1241): WifiActivity: 0
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/BrowserStartupController( 6430): Initializing chromium process, singleProcess=true
W/art     ( 6430): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6430): ApplicationContext is null in ApplicationStatus
W/chromium( 6430): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6430): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6430): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6430): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6430): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6430): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6430): Local Branch: 
I/Adreno-EGL( 6430): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6430): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6430):                  d74aa161a12b9c6fc6332151
W/System.err(  968): java.lang.Throwable: stack dump
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28866c86:true
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6430): 516449091: getState(). Returning 12
W/art     ( 6430): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6430): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6430): CordovaWebView is running on device made by: HTC
W/art     ( 6430): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6430): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6430): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6430): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/HtcModeClient( 3237): handler message = 4011
E/HtcModeClient( 3237): Check connection and retry 12 times.
I/InputMethodManager( 6430): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1fc936f0, mServedView=org.apache.cordova.engine.SystemWebView{509b469 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@c4ffeee
I/InputMethodManagerService(  968): Disable input method client, pid=1563
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  968): Enable input method client, pid=6430
I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +818ms
D/PMS     (  968): releaseWL(60531f1): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1241): setImeWindowStatus(false,false)
W/BindingManager( 6430): Cannot call determinedVisibility() - never saw a connection for the pid: 6430
W/XT9_C   ( 1405): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1405): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1405): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1405): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/JsMessageQueue( 6430): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6430): JniHelper::setJavaVM(0xaaf468f8), pthread_self() = -1406627384
I/chromium( 6430): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=141 Rx=229
,D/PMS     (  968): releaseHCC(371dd375): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  968): releaseHCC(f9edf0a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6430): Initializing JXcore engine,
W/jxcore-log( 6430): JXcore engine is ready
,W/jxcore-log( 6430): Starting JXcore engine,
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1241): WifiActivity: 1,
E/WifiTrafficPoller(  968):  packet count Tx=141 Rx=230
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 1
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=6.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1579064135] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=6.6 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1579064133] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1344): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.05 txretriesrate=0.00 rxrate=3.80 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
,E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  968):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -60, 3
,E/WifiStateMachine(  968): handleMessage: X
D/WIFI_ICON( 1241): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=123 rxSum=109} preTxRxSum={txSum=107 rxSum=97},
D/WifiDataStallTracker(  968): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  968): Killing 5811:com.google.android.gm/u0a106 (adj 15): empty #17,
D/Process (  968): killProcessQuiet, pid=5811
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5811
,D/Process (  968): killProcessQuiet, pid=5860
I/ActivityManager(  968): Killing 5860:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=141 Rx=230
E/WifiTrafficPoller(  968): notifying of data activity 0
D/WIFI_ICON( 1241): WifiActivity: 0
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  968): Recipient 5860
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  968):  packet count Tx=141 Rx=230
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1241): WifiActivity: 1
E/WifiTrafficPoller(  968):  packet count Tx=141 Rx=231
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 1
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1579061115] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579061114] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1344): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
,E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.03 txretriesrate=0.00 rxrate=2.40 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  968):  isHighRSSI       ---> score=61
E/WifiStateMachine(  968): handleMessage: X
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1241): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 6430): Platform android,
W/jxcore-log( 6430): 
W/jxcore-log( 6430): Process ARCH arm
W/jxcore-log( 6430): 
,I/HtcModeClient( 3237): handler message = 4011,
,E/HtcModeClient( 3237): Check connection and retry 12 times. Stop service and kill this process.,
D/HtcModeClient( 3237): Don't start project servcice
,D/HtcModeClient( 3237): setEject: MEDIA_EJECT_STATE = true,
,D/HtcModeClient( 3237): connectState: CONNECTION_READY = false
D/SilentMusic( 3237): call stop,
D/HtcModeClient( 3237): close connection
W/HtcModeClient( 3237): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3237): read the terminate packet, so break
,I/ActivityManager(  968): Killing 3237:com.htc.autobot/u0a47 (adj 15): empty #17
,D/Process (  968): killProcessQuiet, pid=3237
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 3237
,I/jxcore-log( 6430): JXcore Cordova bridge is ready!,
I/jxcore-log( 6430): 
W/jxcore-log( 6430): JXcore engine is started
,I/jxcore-log( 6430): Toggling radios to true
I/jxcore-log( 6430): 
,D/BluetoothAdapter( 6430): enable(): BT is already enabled..!,
,D/WifiService(  968): New client listening to asynchronous messages,
E/WifiTrafficPoller(  968): ADD_CLIENT: 7
,D/WifiManager( 6430): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
W/Settings:Agent(  968): MONITOR_LOG
D/WifiService(  968): setWifiEnabled: true pid=6430, uid=10366
W/Settings:Agent(  968): name: wifi_on
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  968): value: 2
I/WifiService(  968): isSprintWifiRestricted(): false
W/Settings:Agent(  968): >> traceCallingStack()
I/WifiService(  968): isMdmWifiRestricted(): false
W/Settings:Agent(  968): Process.myPid(): 968
W/Settings:Agent(  968): Process.myTid(): 1680
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
W/System.err(  968): java.lang.Throwable: stack dump
,W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  968): 	,at android.provider.Settings$Global.putInt(Settings.java:7503)
,W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  968): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  968): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 12(ms)
D/WifiController(  968): handleMessage: E msg.what=155656
D/WifiManager( 6430): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131145
D/WifiManager( 6430): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1344): wlan0: Cancelling scan request
D/wpa_supplicant( 1344): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1344): TDLS: Tear down peers
I/jxcore-log( 6430): Radios toggled
I/jxcore-log( 6430): 
D/wpa_supplicant( 1344): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6430): My device name is: HTC-HTC One M8s
I/jxcore-log( 6430): 
,D/wpa_supplicant( 1344): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1344): wlan0: Deauthentication notification
D/wpa_supplicant( 1344): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1344): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1344): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1344): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1344): enter disconnect check
I/wpa_supplicant( 1344): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1344): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1344): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  968): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,E/WifiMonitor(  968): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  968): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  968): TetherInterfaceSM: wlan0: enter UnavailableState
,E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  968): acquireWL(10b1430e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/UsbnetService(  968): BroadcastReceiver::onReceive-
,D/wpa_supplicant( 1344): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1344): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1344): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1344): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1344): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x559156af88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1344):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1344): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1344): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1344): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1344): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1344): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1344): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1344): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1344): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1344): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1344): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1344): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1344): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1344): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1344): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1344): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1344): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1344): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1344): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1344): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  968): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: ConnectedState
E/WifiStateMachine(  968): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  968): release()
E/WifiStateMachine(  968): PerfLock released for exiting ConnectedState
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  968): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/TetherSettings( 5953): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/wpa_supplicant( 1344): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/        ( 5953): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5953): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5953): Cust_ConnectToPC   : spcsc>false
D/wpa_supplicant( 1344): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/        ( 5953): Cust_ConnectToPC   : IPT>true
D/wpa_supplicant( 1344): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/        ( 5953): Cust_ConnectToPC   : Singel_USB>false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1344): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1344): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1344): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1344): Power_Mode_Type mode = 0
I/wpa_supplicant( 1344): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1344): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 5953): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiDataStallTracker(  968): setDhcpActive: false
E/SmartNS_Utility( 5953): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5953): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5953): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
V/NativeCrypto( 1959): Read error: ssl=0x557b006f50: I/O error during system call, Connection timed out
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/PMS     (  968): acquireWL(8bc012f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WIFI_ICON( 1241): WifiActivity: 0
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  968):  packet count Tx=141 Rx=231
D/PMS     (  968): releaseWL(10b1430e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiTrafficPoller(  968): notifying of data activity 0
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
E/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
V/NetworkPolicy(  968): updateNotificationsLocked()
E/WifiStateMachine(  968): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  968): NetworkAgent != null
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  968): stopDataStallAlarm 
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  968):  packet count Tx=141 Rx=231
W/ContextImpl( 5953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 1
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): autoRoamSetBSSID any key="NG700"WPA_PSK
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1344): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
V/NativeCrypto( 1959): SSL shutdown failed: ssl=0x557b006f50: I/O error during system call, Broken pipe
I/SmartNS_Utility( 5953): setISNotification,
D/wpa_supplicant( 1344): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1344): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 13
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1344): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1344): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1344): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1344): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/SmartNS_Utility( 5953): usb_cable_connect = 1
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  968):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  968): Start Disconnecting Watchdog 1
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131146
E/WifiStateMachine(  968): processMsg: DisconnectingState
D/SmartNS_Utility( 5953): usb_denied = 0
E/WifiStateMachine(  968):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_RECONNECT 0 0
D/ConnectivityService(  968): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1344): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1344): Fast associate: Old scan results
D/wpa_supplicant( 1344): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1344): wpa_supplicant_scan enter
D/wpa_supplicant( 1344): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1344): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1344): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1344): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1344): WPS:  * Request Type
D/wpa_supplicant( 1344): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1344): WPS:  * UUID-E
D/wpa_supplicant( 1344): WPS:  * Primary Device Type
D/wpa_supplicant( 1344): WPS:  * RF Bands (3)
E/WifiStateMachine(  968): handleMessage: X
D/wpa_supplicant( 1344): WPS:  * Association State
D/wpa_supplicant( 1344): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1344): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1344): WPS:  * Manufacturer
D/wpa_supplicant( 1344): WPS:  * Model Name
D/wpa_supplicant( 1344): WPS:  * Model Number
D/wpa_supplicant( 1344): WPS:  * Device Name
E/WifiStateMachine(  968): handleMessage: E msg.what=147460
D/wpa_supplicant( 1344): WPS:  * Version2 (0x20)
E/WifiStateMachine(  968): processMsg: DisconnectingState
D/wpa_supplicant( 1344): P2P: * P2P IE header
D/wpa_supplicant( 1344): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1344): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1344): wlan0: Add radio work 'scan'@0x559154d860
D/wpa_supplicant( 1344): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1344): wlan0: Starting radio work 'scan'@0x559154d860 after 0.000064 second wait
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/wpa_supplicant( 1344): wlan0: nl80211: scan request
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Forcing reevaluation
E/WifiStateMachine(  968):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106903
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/SmartNS_PSService( 5953): usb notificaiton:true
D/wpa_supplicant( 1344): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  968):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106903
D/wpa_supplicant( 1344): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1344): wlan0: nl80211: Scan trigger
E/WifiStateMachine(  968): ConnectModeState: Network connection lost 
D/wpa_supplicant( 1344): wlan0: Event SCAN_STARTED (49) received
E/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
D/wpa_supplicant( 1344): wlan0: Own scan request started a scan in 0.000132 seconds
I/wpa_supplicant( 1344): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  968): DisconnectedState call setCountryCode()
E/WifiStateMachine(  968):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1344): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1344): Pending scan scheduled - reject new request
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  968): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
E/WifiStateMachine(  968):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=106908  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=106908  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/PMS     (  968): releaseWL(8bc012f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
I/ActionCombine( 5953): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
D/WifiNetworkAgent(  968): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=106919  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false,
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): NetworkAgent == null
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  968): New client listening to asynchronous messages
D/SmartNS_Utility( 5953): usb_cable_connect = 1
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/SmartNS_Utility( 5953): usb_denied = 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
I/SmartNS_PSService( 5953): usb notificaiton:true
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=106924  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/RemoteViews( 1241): reapply : com.android.settings 1 36
D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_NSReceiver( 5953): Tethered state change:false isNSOpening:false
I/RemoteViews( 1241): reapply : com.android.settings 1 36
D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WISPrService( 5953): >>>>>WISPrService start isConnected = true<<<<<
E/WifiTrafficPoller(  968): ADD_CLIENT: 8
I/QuickSettingWifi( 1241): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): handleMessage: X
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:4
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:1
W/WISPrService( 5953): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5953): trigger connection
D/WISPrService( 5953): continue
D/WISPrService( 5953): start DataConnection
D/libc    ( 5953): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5953): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    ( 5953): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5953): [NET] android_getaddrinfofornet-, pass to proxy
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5953): [NET] android_getaddrinfo_proxy+
D/libc    ( 5953): [NET] android_getaddrinfo_proxy get netid:0
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/ConnectivityService(  968): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:2
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  398): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/ConnectivityService(  968): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  398): [NET] android_getaddrinfofornet-, err=7
D/Nat464Xlat(  968): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 1241): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    ( 5953): [NET] android_getaddrinfo_proxy-, NODATA
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Disconnected - quitting
I/SecurityController( 1241): onLost 100
,D/WIFI    (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  968): Removing idletimer
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  968): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/PMS     (  968): acquireWL(1f6cd8c5): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 968 1000 null
,D/CSLegacyTypeTracker(  968): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,I/ActivityManager(  968): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6498 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  968): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
,D/PMS     (  968): acquireWL(38c2821a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
E/ConnectivityService(  968): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/DATA_ICON( 1241): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateIfacesLocked()
D/DATA_ICON( 1241): dataConnected: false/false
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  968): updateNotificationsLocked()
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/libc    ( 5953): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5953): [NET] android_getaddrinfofornet-, err=8
,D/WISPrService( 5953): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  968): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6511 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/PMS     (  968): releaseWL(38c2821a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency,
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,W/ResourcesManager( 6498): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,I/ActivityManager(  968): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6541 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/CalendarProvider2( 6498): Created com.android.providers.calendar.CalendarAlarmManager@157633a7(com.htc.providers.calendar.HtcCalendarProvider@13b1054)
,W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead
,D/CalendarProvider2( 6498): wait start:true
,D/AccTypeManager( 1750): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 1563): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
W/Prism.AllAppsManager( 1563): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1563): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false,
D/AccTypeManager( 1750): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1563): Deferring update until onResume
D/Launcher( 1563): waitUntilResume // bindAppsUpdated
,W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1750): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1510): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  968): Killing 5931:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=5931
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/ExternalAccountType( 1750): Unsupported attribute readOnly
,W/PackageManager(  968): Unable to load service info ResolveInfo{27cdc1a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  968): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  968): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  968): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  968): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  968): Recipient 5931
,V/GmsNetworkLocationProvi( 1846): DISABLE,
,I/BackupManagerService(  968): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1846): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 6498): wait end:false
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/MdScPhnSt( 6541): [5cb.2.]  listen tmrbb8,
D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,I/art     (  968): Explicit concurrent mark sweep GC freed 43372(2MB) AllocSpace objects, 5(292KB) LOS objects, 33% free, 16MB/25MB, paused 2.017ms total 145.294ms,
,D/LocationProviderProxy(  968): applying state to connected service
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false,
D/PMS     (  968): acquireWL(7c0d7f2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(7c0d7f2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
D/MdProvGlob( 6511): add item 101 (2:g3d9) for 15:android.intent.action.ANY_DATA_STATE
,D/LocationProviderProxy(  968): applying state to connected service
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,D/PMS     (  968): acquireWL(268f10b5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1846 10024 WorkSource{10024 com.google.android.gms},
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false,
D/PMS     (  968): releaseWL(268f10b5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(22ff734a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1846 10024 WorkSource{10024 com.google.android.gms},
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false
D/PMS     (  968): releaseWL(22ff734a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6511): remove item 101 (p3d3in57) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 6541): [5cb.2.] summary 118:p3 ignore
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6511): remove item 101 (p3in7) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6511): remove item 101 (p3in10) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false,
,D/MdProvGlob( 6511): remove item 101 (p3d1in13) for 15:android.intent.action.ANY_DATA_STATE,
D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6511): remove item 101 (p3in12) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6511): remove item 101 (p3in7) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false,
,D/MdProvGlob( 6511): remove item 101 (p3d1in11) for 15:android.intent.action.ANY_DATA_STATE
D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,D/PMS     (  968): acquireWL(3120d2bb): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5779 10112 null
D/MdProvGlob( 6511): remove item 101 (p3in8) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6511): remove item 101 (p3d1in13) for 15:android.intent.action.ANY_DATA_STATE,
,I/[PluginManager]RegisterService( 1617): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1617): handle notify Blinkfeed plugin client changed
D/PMS     (  968): releaseWL(3120d2bb): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/MdProvGlob( 6511): remove item 101 (p3in16) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6511): remove item 101 (p3d1in17) for 15:android.intent.action.ANY_DATA_STATE
,D/PackageBroadcastService( 4429): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4429): Null package name or gms related package.  Ignoreing.
D/PMS     (  968): acquireWL(2268e11c): PARTIAL_WAKE_LOCK  AsyncService 0x1 6046 10167 null
D/MdProvGlob( 6511): remove item 101 (p3in17) for 15:android.intent.action.ANY_DATA_STATE
D/PMS     (  968): releaseWL(2268e11c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  968): acquireWL(340342fa): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6046 10167 null
,D/PMS     (  968): acquireWL(2b27e0ab): PARTIAL_WAKE_LOCK  Icing 0x1 4429 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(340342fa): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/Icing   ( 4429): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 5893): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/FlexNetS( 6498): updateSvcAllowedInSettings:false
,D/PMS     (  968): releaseWL(2b27e0ab): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/UpdateIcingCorporaServi( 5893): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 16 num clients 8,
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 16 num clients 8,
,I/CalendarProvider2( 6498): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6498): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  968): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6587 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  968): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6600 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  968): acquireWL(6941aa1): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10076}
V/AlarmManager(  968): sending alarm PendingIntent{26b294c6: PendingIntentRecord{3a81dc87 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454414854469, Int=60000
D/PMS     (  968): releaseWL(6941aa1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,W/ResourcesManager( 6587): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/SMSBackup( 6600): SMSBackupAgentService started,
D/SMSBackup( 6600): Checking restore status
,D/SMSBackup( 6600): Restore complete
D/SMSBackup( 6600): cancelCheckAlarm
D/SMSBackup( 6600): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/CalendarApplication( 6587): onCreate,
D/ProviderChangeReceiver( 6587): ---------------------------------------------------,
D/ProviderChangeReceiver( 6587): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
D/Process (  968): killProcessQuiet, pid=6231
I/ActivityManager(  968): Killing 6231:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,D/HtcAlertService( 6587): start to updateAlertNotification!
,I/ActivityManager(  968): Recipient 6231,
,D/Process (  968): killProcessQuiet, pid=6254
I/ActivityManager(  968): Killing 6254:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/Prism.ItemManager( 1563): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1563): loadItems() com.htc.launcher.pageview.WidgetManager@184a7b6 +
I/Prism.WidgetManager( 1563): onLoadItems() +
,I/ActivityManager(  968): Recipient 6254
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 2
W/ResourcesManager( 1563): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/HtcAlertService( 6587): No fired or scheduled alerts
D/HtcAlertUtils( 6587): -- cancelReminderNotification --
,D/HtcAlertUtils( 6587): broadcastExistReminder!
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/ResourcesManager( 1563): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1563): Copying FileAsset 0x557b4520c0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,D/wpa_supplicant( 1344): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1344): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1344): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1344): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1344): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1344): wlan0: Scan completed in 2.048568 seconds
D/wpa_supplicant( 1344): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1344): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1344): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1344): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1344): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 1344): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1344): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1344): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1344): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1344): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1344): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1344): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1344): wlan0: Radio work 'scan'@0x559154d860 done in 2.049539 seconds
D/wpa_supplicant( 1344): wlan0: Selecting BSS from priority group 590
D/wpa_supplicant( 1344): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-52 wps
D/wpa_supplicant( 1344): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1344): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1344): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 1344): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1344): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1344): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1344):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1344): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1344): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x559156cc00  current_ssid=0x0
D/wpa_supplicant( 1344): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1344): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1344): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1344): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1344): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1344): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1344): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1344): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1344): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1344): wlan0: Add radio work 'connect'@0x559154d860
D/wpa_supplicant( 1344): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1344): wlan0: Starting radio work 'connect'@0x559154d860 after 0.000045 second wait
I/wpa_supplicant( 1344): check if in concurrent case
I/wpa_supplicant( 1344): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_,supplicant( 1344): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1344): wlan0: Cancelling scan request
D/wpa_supplicant( 1344): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1344): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1344): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1344): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1344): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1344): RSN: PMKSA cache search - network_ctx=0x559156cc00 try_opportunistic=0
D/wpa_supplicant( 1344): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1344): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1344): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1344): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1344): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1344): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1344): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1344): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1344): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1344): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1344): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1344): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1344): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1344): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1344): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1344): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1344): nl80211: Unsubscribe mgmt frames handle 0x888888dd19de4989 (mode change)
D/wpa_supplicant( 1344): nl80211: Subscribe to mgmt frames with non-AP handle 0x559156c100
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=0104
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=040a
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=040b
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=040c
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=040d
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=090a
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=090b
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=090c
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=090d
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=0409506f9a09
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=7f506f9a09
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=0801
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=040e
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=06
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=0a07
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=0a11
D/wpa_supplicant( 1344): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559156c100 match=0a1a
D/wpa_supplicant(, 1344): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1344):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344):   * freq=2412
D/wpa_supplicant( 1344):   * freq_hint=2412
D/wpa_supplicant( 1344):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1344):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1344):   * WPA Versions 0x2
D/wpa_supplicant( 1344):   * pairwise=0xfac04
D/wpa_supplicant( 1344):   * group=0xfac04
D/wpa_supplicant( 1344):   * akm=0xfac02
D/wpa_supplicant( 1344):   * Auth Type 0
D/wpa_supplicant( 1344): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x559156cc3a
D/wpa_supplicant( 1344): nl80211: Connect request send successfully
D/wpa_supplicant( 1344): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1344): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1344): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1344): EAPOL: External notification - portControl=Auto
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  968): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiStateMachine(  968): handleMessage: E msg.what=147461
E/WifiStateMachine(  968): processMsg: DisconnectedState
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  968):  DisconnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:96 bcn=0
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=37 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  968): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:96 bcn=0
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=38 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:96 bcn=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:96 bcn=0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1344): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  968): [1,454,414,855,250 ms] noteScanEnd no scan source
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1344): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  968): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2605836c sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  968): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  968): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  968): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  968):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  968): Gonzos 38:f8:89:11:e9:11 rssi=-80 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  968): 01ABC c2:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  968): ageScanResultsOut delay 40000 size 4 now 1454414855253
E/WifiAutoJoinController (  968): newSupplicantResults size=4 known=1 true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1344): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  968): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  968): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  968): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  968): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  968): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  968):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-1579058088] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579058087] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579058086] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1579058086] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579058085] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131213
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108971
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108972
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108972
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108972
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=108973  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info0x
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=108977  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  968): handleMessage: X
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/Prism.WidgetManager( 1563): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1563): onLoadItems() -
I/Prism.ItemManager( 1563): loadItems() com.htc.launcher.pageview.WidgetManager@184a7b6 -
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1344): Wireless event: cmd=0x8c02 len=271,
I/wpa_supplicant( 1344): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1344): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1344): Wireless event: cmd=0x8c02 len=152
,I/wpa_supplicant( 1344): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1344): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1344): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1344): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1344): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1344): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
D/wpa_supplicant( 1344): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1344): nl80211: Connect event
D/wpa_supplicant( 1344): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1344): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1344): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1344): wlan0: Association info event
D/wpa_supplicant( 1344): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1344): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1344): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1344): wlan0: freq=2412 MHz
D/wpa_supplicant( 1344): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1344): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1344): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1344): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1344): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1344): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1344): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1344): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1344): wlan0: WPA: Association event - clear replay counter
,D/wpa_supplicant( 1344): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1344): TDLS: Remove peers on association
D/wpa_supplicant( 1344): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1344): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1344): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1344): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1344): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1344): EAPOL: enable timer tick
D/wpa_supplicant( 1344): EAPOL: SUPP_BE entering state IDLE
,D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
,D/wpa_supplicant( 1344): wlan0: Setting authentication timeout: 10 sec 0 usec
D/PMS     (  968): acquireWL(8b4c94c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/wpa_supplicant( 1344): wlan0: Cancelling scan request
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1344): wlan0: Process pending EAPOL frame that was received just before association notification
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1344): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1344): wlan0: Setting authentication timeout: 10 sec 0 usec
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1344): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1344): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1344): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1344): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1344):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1344):   key_nonce - hexdump(len=32): 6e de 17 21 52 a2 d4 31 26 41 c7 cb 7e fb dd 89 f0 ae 65 18 65 d0 19 7d 8f fb c2 15 db 71 04 b2
D/wpa_supplicant( 1344):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1344):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1344):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1344):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1344): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1344): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1344): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 1344): WPA: Renewed SNonce - hexdump(len=32): 42 b0 5d 9b f9 d7 df 12 0c 3a cc 63 43 df 26 5e 32 35 6c 3a ca 44 21 28 3b 45 d2 b5 08 64 9c 3f
D/wpa_supplicant( 1344): WPA: Nonce1 - hexdump(len=32): 42 b0 5d 9b f9 d7 df 12 0c 3a cc 63 43 df 26 5e 32 35 6c 3a ca 44 21 28 3b 45 d2 b5 08 64 9c 3f
D/wpa_supplicant( 1344): WPA: Nonce2 - hexdump(len=32): 6e de 17 21 52 a2 d4 31 26 41 c7 cb 7e fb dd 89 f0 ae 65 18 65 d0 19 7d 8f fb c2 15 db 71 04 b2
D/wpa_supplicant( 1344): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1344): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1344): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1344): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1344): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1344): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1344): WPA: Derived Key MIC - hexdump(len=16): 75 aa 21 99 0f ec 7a bd 46 d6 b5 80 4b 87 be 92
I/wpa_supplicant( 1344): htc_wext_set_keepalive +
I/wpa_supplicant( 1344): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1344): getPrivFuncNum +	
I/wpa_supplicant( 1344): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1344): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1344): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' fre,q=2412]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=41 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/HTCRequest(  968): WifiMonitor:getFreqFromEventString() 2412
D/PMS     (  968): releaseWL(8b4c94c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
D/HTCRequest(  968): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
V/NetworkPolicy(  968): updateNotificationsLocked()
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  968): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  968): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=109062  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=109062  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147500
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/Tethering(  968): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  968): Enter handleAssociatedWithEvent
D/WifiStateMachine(  968): Associated
V/Tethering(  968): TetherInterfaceSM: wlan0: enter InitialState
D/WifiStateMachine(  968): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  968): Exit handleAssociatedWithEvent
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiSta,teMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=109064  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/Tethering(  968): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1344): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1344): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1344): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1344): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1344): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1344):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1344):   key_nonce - hexdump(len=32): 6e de 17 21 52 a2 d4 31 26 41 c7 cb 7e fb dd 89 f0 ae 65 18 65 d0 19 7d 8f fb c2 15 db 71 04 b2
D/wpa_supplicant( 1344):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1344):   key_rsc - hexdump(len=8): 18 02 00 00 00 00 00 00
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 18
D/wpa_supplicant( 1344):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1344):   key_mic - hexdump(len=16): 0e 8d 6f bf 4a 68 70 49 ee b1 03 a2 b1 ec b3 36
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1344): RSN: encrypted key data - hexdump(len=56): bc d0 ab 16 16 d8 39 c7 35 25 05 07 13 5b 2f 02 3d 7f 9a d8 05 cc 2a be af 72 35 09 ed 49 97 5f ...
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1344): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
W/ContextImpl( 5953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1344): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/wpa_supplicant( 1344): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1344): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 cb bd ...
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1344): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1344): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1344): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1344): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1344): WPA: Derived Key MIC - hexdump(len=16): 57 fb f9 61 9d 3e 51 37 c0 a1 94 c9 d5 a5 c5 06
D/wpa_supplicant( 1344): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1344): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x559156d390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1344): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1344): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1344):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1344): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1344): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1344): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1344): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1344): WPA: RSC - hexdump(len=6): 18 02 00 00 00 00
D/wpa_supplicant( 1344): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5555854e68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1344): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1344): nl80211: KEY_SEQ - hexdump(len=6): 18 02 00 00 00 00
D/wpa_supplicant( 1344):    broadcast key
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1344): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1344): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1344): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1344): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1344): wlan0: Radio work 'connect'@0x559154d860 done in 0.116334 seconds
I/wpa_supplicant( 1344): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine(  968): processMsg: ConnectModeState
I/wpa_supplicant( 1344): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/ConnectivityService(  968): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/ConnectivityService(  968): Got NetworkAgent Messenger
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=44 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=109069  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  968): handleMessage: X
D/ConnectivityService(  968): NetworkAgent connected
E/wpa_supplicant( 1344): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1344): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1344): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=45 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1344): set send_ind_to_ndc = 0
E/WifiMonitor(  968): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1344): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1344): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1344): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1344): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1344): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1344): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1344): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1344): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1344): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1344): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1344): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1344): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WifiMonitor(  968): Event [IFNAME=wlan0 Connect to SSID: NG700]
D/wpa_supplicant( 1344): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=47 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  968): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/Tethering(  968): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/TetherSettings( 5953): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5953): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5953): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5953): Cust_ConnectToPC   : spcsc>false
D/        ( 5953): Cust_ConnectToPC   : IPT>true
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/        ( 5953): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5953): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  968):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/SmartNS_Utility( 5953): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5953): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5953): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  968):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=109074  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=109075  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147459
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109076
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109076
E/WifiStateMachine(  968): Network connection established
D/WifiStateMachine(  968): fetchFrequency(), freq = 2412
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 20
E/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  968): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
I/SmartNS_Utility( 5953): setISNotification
D/SmartNS_Utility( 5953): usb_cable_connect = 1
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 22
D/SmartNS_Utility( 5953): usb_denied = 0
I/SmartNS_PSService( 5953): usb notificaiton:true
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1344): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1344): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1344): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1344): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1344): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1344): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  968): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  968): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1344): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1344): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1344): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1344): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1344): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1344): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/SmartNS_Utility( 5953): usb_cable_connect = 1
E/WifiStateMachine(  968): Start Dhcp Watchdog 2
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=109093  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/SmartNS_Utility( 5953): usb_denied = 0
I/SmartNS_PSService( 5953): usb notificaiton:true
E/WifiStateMachine(  968):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=109094  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=109094  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:125] from screen [on:0 period:-1579057960] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579057959] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
I/RemoteViews( 1241): reapply : com.android.settings 1 36
I/wpa_supplicant( 1344): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=70.50 txretriesrate=0.00 rxrate=115.50 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
E/WifiStateMachine(  968): calculateWifiScore() report new score 60
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/SmartNS_NSReceiver( 5953): Tethered state change:false isNSOpening:false
D/ConnectivityService(  968): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  968):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WIFI_ICON( 1241): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=196612
E/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  968):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=141,0,0
D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=141,0,0
D/WifiStateMachine(  968): handlePreDhcpSetup Held wake lock during DHCP
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/PMS     (  968): acquireWL(34298c50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 968 1000 null
D/WifiStateMachine(  968): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  968): setDhcpActive: true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1344): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/native  (  968): do suspend false
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/WifiP2pService(  968): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b68f1f0 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b68f1f0 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1344): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1344): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1344): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1344): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1344): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1344): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1344): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): noteBatchedScanstop()
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  968): handleMessage: X
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5953): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5953): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/RemoteViews( 1241): reapply : com.android.settings 2 36
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1241): receive.wifiConnect:false wifiAPname:null elapse:1
,D/PhoneApp( 1510): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1510): -- N1 =0
D/PhoneApp( 1510): -- N2 =0
D/PhoneApp( 1510): -- N3 =0
,E/dhcpcd  ( 6636): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6636): version 5.5.6 starting
E/dhcpcd  ( 6636): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6636): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6636): autoip env[11]:autoip=DISABLE
,I/dhcpcd  ( 6636): wlan0: rebinding lease of 192.168.1.130
,I/dhcpcd  ( 6636): wlan0: sending REQUEST (xid 0x1d17c94d), next in 1.05 seconds
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  968): acquireWL(34514e49): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  968): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: false
I/ConnectivityHelper( 1563): [onReceive] WIFI(1): DISCONNECTED
,D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ActivityManager(  968): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6645 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/wpa_supplicant( 1344): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1344): EAPOL: disable timer tick
,E/GpsLocationProvider(  968): No APN found to select.
,D/PMS     (  968): releaseWL(34514e49): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6541): [909.1.]  listen tmrbb8
,D/MdScDataSum( 6541): [909.1.] summary 118:p1 ignore
,I/MusicStore( 6645): Database version: 120
,D/VoldConnector(  968): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6645): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
,E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
,D/VoldConnector(  968): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6645): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  968): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 6645): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6645): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6645): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6645): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6645): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6645): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24e4156b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6645): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6645): GMSCore installation verified
,I/ConfigStore( 6645): Config Database version: 1,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6645, uid=10159, userID:0,
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: ,
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,D/MediaRouterService(  968): Client com.google.android.music (pid 6645): Registered
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client,
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,I/MediaRouter( 6645): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6645): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/dhcpcd  ( 6636): wlan0: sending REQUEST (xid 0x1d17c94d), next in 2.78 seconds,
,I/dhcpcd  ( 6636): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6645, uid=10159, userID:0
,D/AutoSetting( 1617): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,D/AutoSetting( 1617): Util - no network available!,
,D/MobileConnectivityChangeReceiver( 6383): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6383): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1617): service - onCreate()
,I/GHttpClientFactory( 6645): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6645): Using platform SSLCertificateSocketFactory,
,D/AutoSetting( 1617): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
I/iu.Environment( 4429): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/LocationManagerService(  968): request 7e8b0bc passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  968): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1617): service - mHandler: cancel location update,
D/AutoSetting( 1617): service -           changes count: 0
I/iu.UploadsManager( 4429): num queued entries: 0
,I/iu.UploadsManager( 4429): num updated entries: 0
,I/iu.SyncManager( 4429): NEXT; no task,
,D/ChimeraCfgMgr( 4429): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Babel   ( 5779): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6688 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  968): Killing 6018:com.google.android.gms:car/u0a24 (adj 15): empty #17,
D/Process (  968): killProcessQuiet, pid=6018
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6636): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6636): autoip env[11]:autoip=DISABLE
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
,E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
,E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  968): handleMessage: X
,D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/ActivityManager(  968): Recipient 6018
,I/dhcpcd  ( 6636): bind_interface: daemonise
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  968): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  968): releaseWL(34298c50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=196613
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4,
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1344): Power_Mode_Type mode = 0
I/wpa_supplicant( 1344): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1344): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  968): setDhcpActive: false,
E/WifiStateMachine(  968): handlePostDhcpSetup release wake lock during DHCP
D/WIFI_ICON( 1241): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968): WifiStateMachine DHCP successful
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  968): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  968): link address 192.168.1.130/24
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  968): gateway: /192.168.1.1
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1344): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1344): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  968): handleMessage: X
D/ConnectivityService(  968): Adding iface wlan0 to network 101
E/WifiStateMachine(  968): handleMessage: E msg.what=131210
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1344): environment dirty rate=0 [5][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
D/HtcWifiWanDetect(  968): WAN detection
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
D/WIFI_ICON( 1241): WifiActivity: 3
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/HtcWifiWanDetect(  968): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
D/wpa_supplicant( 1344): wlan0: Control interface command 'BLACKLIST clear'
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/wpa_supplicant( 1344): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=49 dispatchEvent: BLACKLIST CLEAR 
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  968): NetworkAgent != null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS,_POLL true Token 23
E/WifiTrafficPoller(  968):  packet count Tx=144 Rx=233
E/WifiTrafficPoller(  968): notifying of data activity 3
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL true Token 2
D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  968): updateDataStallInfo: NONE
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): transitionTo: destState=ConnectedState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  968): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 24
E/WifiTrafficPoller(  968):  packet count Tx=144 Rx=233
E/WifiStateMachine(  968): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiTrafficPoller(  968): notifying of data activity 0
D/WIFI_ICON( 1241): WifiActivity: 0
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
I/GAv4    ( 6688): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6688):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6688):   adb logcat -s GAv4
D/VoldConnector(  968): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,I/IntentController( 1241): receive(android.net.wifi.STATE_CHANGE,1,false)
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6688): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/WISPrService( 5953): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  968): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  968): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  968): ConnectedState Enter  mScreenOn=true scanperiod=20000
E/WifiStateMachine(  968): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968): handleMessage: X
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
E/WifiStateMachine(  968): processMsg: ConnectedState
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/ConnectivityService(  968): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  968):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: X
,D/ConnectivityService(  968): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/WIFI_ICON( 1241): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  968): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/VoldConnector(  968): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/Nat464Xlat(  968): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Connected
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): currentScore = 0, newScore = 20
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):    accepting network in place of null
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  968): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WISPrService( 5953): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  968): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  968): acquireWL(37ec0910): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
D/ConnectivityService(  968): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048,576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1241): CM callback handler got msg 524290
D/DATA_ICON( 1241): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/SecurityController( 1241): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1241): CM callback handler got msg 524290
,W/ContextImpl( 6688): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
I/SecurityController( 1241): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
D/ConnectivityManager.CallbackHandler( 1241): CM callback handler got msg 524290
V/NetworkPolicy(  968): updateIfacesLocked()
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SecurityController( 1241): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  968): updateNotificationsLocked()
D/PMS     (  968): releaseWL(37ec0910): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1241): dataConnected: false/false
,D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
,V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
W/GAv4    ( 6688): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/DATA_ICON( 1241): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,D/DATA_ICON( 1241): dataConnected: false/false
,D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/VoldConnector(  968): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6688): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  968): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/GAv4    ( 6688): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 6688): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/QuickSettingWifi( 1241): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1241): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,W/GAv4    ( 6688): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/global  ( 6688): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6688): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6688): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6688): Time to load native libraries: 11 ms (timestamps 1202-1213),
,I/LibraryLoader( 6688): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6688): Binding Chromium to main looper Looper (main, tid 1) {3f3f1668},
,I/LibraryLoader( 6688): Expected native library version number "",actual native library version number ""
,I/chromium( 6688): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6688): Initializing chromium process, singleProcess=true
,W/art     ( 6688): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6688): ApplicationContext is null in ApplicationStatus
,W/chromium( 6688): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6688): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6688): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6688): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6688): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6688): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6688): Local Branch: 
I/Adreno-EGL( 6688): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6688): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6688):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6688): Requires BLUETOOTH permission,
,I/NSApplication( 6688): Starting up...,
,I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6771 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  968): Killing 6285:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=6285
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  968): Recipient 6285,
,D/PMS     (  968): acquireWL(344c24ed): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
V/AlarmManager(  968): sending alarm PendingIntent{33fa1f22: PendingIntentRecord{d47cdb3 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=111360, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{7b12a8e: PendingIntentRecord{393a92af android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454414857442, Int=20000
,D/Process (  968): killProcessQuiet, pid=5603
I/ActivityManager(  968): Killing 5603:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,I/ActivityManager(  968): Recipient 5603,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131168,
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): handleMessage: X
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8,
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8
,E/WifiTrafficPoller(  968):  packet count Tx=144 Rx=234
D/WIFI_ICON( 1241): WifiActivity: 1
E/WifiTrafficPoller(  968): notifying of data activity 1
,D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  968): releaseWL(1f6cd8c5): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  968): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/PMS     (  968): acquireWL(1367920f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  968): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,E/WifiStateMachine(  968): handleMessage: E msg.what=131143
D/PMS     (  968): releaseWL(344c24ed): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:96 rssi=-59 f=2412 sc=60 link=72 tx=70.5, 0.0, 0.0  rx=115.5 list=2412 [on:0 tx:0 rx:0 period:2882] from screen [on:0 period:-1579055072]
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:96 rssi=-59 f=2412 sc=60 link=72 tx=70.5, 0.0, 0.0  rx=115.5 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579055071]
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=70.50 rxSuccessRate=115.50 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-59
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN with age=73967 interval=40000 maxinterval=300000
D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1959): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN try full band scan age=73967 interval=40000 maxinterval=300000
,E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=70.50 rx=115.50
E/WifiStateMachine(  968): handleMessage: X
,D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1959): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1959): [NET] android_getaddrinfo_proxy+
D/libc    ( 1959): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  398): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1959): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1959): [NET] android_getaddrinfofornet-, err=8
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=70.5, 0.0, 0.0  rx=115.5 bcn=0 [on:0 tx:0 rx:0 period:115] from screen [on:0 period:-1579054954] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=70.5, 0.0, 0.0  rx=115.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579054953] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1344): environment dirty rate=20 [5][1][0]
D/WIFI_ICON( 1241): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiStateMachine(  968): BroadcastRSSIForIMS, newrssi =-60 , oldRssi= -200
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=38.75 txretriesrate=0.00 rxrate=60.25 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
E/WifiStateMachine(  968): handleMessage: X
,D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1241): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1959): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  968): acquireWL(1833f29c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1959): Connected
D/PMS     (  968): releaseWL(1367920f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(1833f29c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): acquireWL(22b204a5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1959): Message class com.google.f.a.a.p
,D/PMS     (  968): releaseWL(22b204a5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/Process (  968): killProcessQuiet, pid=5407,
I/ActivityManager(  968): Killing 5407:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5407
,D/Process (  968): killProcessQuiet, pid=6338,
I/ActivityManager(  968): Killing 6338:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1af53bbf,
I/PMS     (  968): Going to sleep due to screen timeout (uid 1000)...
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  968): pid=968, uid=1000
W/SensorService(  968): Active sensors: size = 4
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1af53bbf, eanble = 0, strlen(mName) = 91
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  968): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3a56e90e
W/SensorService(  968): Listener[1] = com.htc.smartdim.sensor_eye@98bc19f
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMN     (  968): goingToSleep
,W/HtcLockScreen( 1241): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off,
,I/ActivityManager(  968): Recipient 6338
,W/PMS     (  968): mWirelessDisplayManager is null,
D/PMS     (  968): acquireWL(3fd4707a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 968 1000 null
W/PMS     (  968): mWirelessDisplayManager is still null
,W/PMN     (  968): goingToSleep done
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/PMS     (  968): Sleeping (uid 1000)...
D/XAN-DPS (  968): prepareColorFade 1
D/PMS     (  968): releaseWL(3fd4707a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8
E/WifiTrafficPoller(  968):  packet count Tx=153 Rx=243
E/WifiTrafficPoller(  968): notifying of data activity 3
D/AlarmManager(  968): ACTION_SCREEN_ON
I/AlarmManager(  968): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  968): [AlarmQueuing] done recovering
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 25
I/AlarmManager(  968): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  968): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  968):  packet count Tx=153 Rx=243
E/WifiTrafficPoller(  968): notifying of data activity 0
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL true Token 3
,I/Adreno-EGL(  968): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  968): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  968): Build Date: 03/09/15 Mon
I/Adreno-EGL(  968): Local Branch: 
I/Adreno-EGL(  968): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  968): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  968):                  d74aa161a12b9c6fc6332151
,E/WifiStateMachine(  968): handleMessage: E msg.what=131167
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=131 rxSum=117} preTxRxSum={txSum=131 rxSum=117}
D/WifiDataStallTracker(  968): updateDataStallInfo: NONE
E/WifiStateMachine(  968):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  968):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: DefaultState
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1344): SET_SCREEN_ON:On
I/wpa_supplicant( 1344): htc_wext_set_keepalive +
I/wpa_supplicant( 1344): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1344): getPrivFuncNum +	
I/wpa_supplicant( 1344): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1344): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1344): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1344): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1344): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  968): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
,D/WIFI_ICON( 1241): WifiActivity: 3
D/WifiStateMachine(  968): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  968): handleScreenStateChanged Exit: true
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131154
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
V/SRS_Proc(  417): ParamSet string: screen_state=on
E/audio_a2dp_hw(  417): adev_set_parameters: ERROR: set param called even when stream out is null
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/wpa_supplicant( 1344): environment dirty rate=0 [5][0][0]
D/WIFI_ICON( 1241): WifiActivity: 0
,D/WifiController(  968): handleMessage: E msg.what=155650
D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
D/WifiController(  968): handleMessage: X
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  968): handleMessage: X
,E/WifiStateMachine(  968): handleMessage: E msg.what=131127
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131129
D/NetworkPolicy(  968): updateScreenOn: false
E/WifiStateMachine(  968): processMsg: ConnectedState
V/NetworkPolicy(  968): updateIfacesLocked()
E/WifiStateMachine(  968):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
,E/WifiStateMachine(  968):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1344): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1344): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=50 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  968): handleMessage: X
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1241): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1241): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  968): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6808 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/art     (  450): Explicit concurrent mark sweep GC freed 8640(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 162us total 18.629ms
,I/IntentController( 1241): receive(android.intent.action.SCREEN_ON,1,false)
,I/art     (  450): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 142us total 16.333ms,
,I/art     (  450): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 127us total 15.706ms,
,W/ContextImpl( 6808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/XAN-DPS (  968): prepareColorFade done
D/XAN-DPS (  968): setBrightness to 0
,D/PMS     (  968): acquireWL(58d235d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@3a56e90e
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = CM32181 Light sensor
D/PMS     (  968): acquireWL(14cc94d2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
I/DisplayManagerService(  968): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DotMatrix( 1351): [EventService]  onDisplayChanged: 0
V/ActivityManager(  968): Display changed displayId=0
W/SensorService(  968): pid=968, uid=1000
W/SensorService(  968): Active sensors: size = 3
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@3a56e90e, eanble = 0, strlen(mName) = 67
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.smartdim.sensor_eye@98bc19f
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  968): releaseWL(58d235d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(14cc94d2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/DotMatrix( 1351): [EventService] mbHDMIConnect: false, mCoverOn:false
,W/ContextImpl( 6808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6808): MY_DEBUG = false
,D/SmartSyncUtils( 6808): isEpsOn(), nState = 0
,D/AlarmManager(  968): ACTION_SCREEN_OFF,
I/AlarmManager(  968): [AlarmQueuing] screen off now: ,
I/AlarmManager(  968): [AlarmQueuing] data connection: true
I/AlarmManager(  968): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 26
D/WifiDataStallTracker(  968): stopDataStallAlarm 
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  968): handleMessage: E msg.what=131167
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1344): SET_SCREEN_ON:Off
I/wpa_supplicant( 1344): htc_wext_set_keepalive +
I/wpa_supplicant( 1344): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1344): getPrivFuncNum +	
I/wpa_supplicant( 1344): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1344): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1344): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1344): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1344): htc_wext_set_keepalive - ret = 0
D/NetworkPolicy(  968): updateScreenOn: false
E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
V/NetworkPolicy(  968): updateIfacesLocked()
V/SRS_Proc(  417): ParamSet string: screen_state=off
E/audio_a2dp_hw(  417): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  968): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  968): handleScreenStateChanged Exit: false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131154
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  968): handleMessage: X
D/WifiController(  968): handleMessage: E msg.what=155651
D/WifiController(  968): processMsg: DeviceActiveState
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,D/PMS     (  968): acquireWL(3e2f74a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6808 1000 null
,I/SensorManager( 1241): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@134f25e7, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  968): enable: get sensor name = hTC Gesture Motion HIDI
W/SensorService(  968): pid=1241, uid=10041
W/SensorService(  968): Active sensors: size = 4
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@134f25e7, eanble = 1, strlen(mName) = 57
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  968): Listener[0] = com.htc.smartdim.sensor_eye@98bc19f
W/SensorService(  968): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@134f25e7
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartDim(  968): Init customizeScreenOffDelayClass error
,D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1351): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PMS     (  968): releaseWL(3e2f74a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/IntentController( 1241): receive(android.intent.action.SCREEN_OFF,1,false),
D/ContactMessageStore( 1510): start background delete task...
,D/PMS     (  968): acquireWL(37d9859): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(37d9859): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1510): size: 0 , 0
D/PMS     (  968): acquireWL(2ebb2c1e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1510): Background delete complete
,D/PMS     (  968): releaseWL(2ebb2c1e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
D/SmartSyncUtils( 6808): isEpsOn(), nState = 0
,W/ContextImpl( 6808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@98bc19f
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  968): pid=968, uid=1000
,W/SensorService(  968): Active sensors: size = 3
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@98bc19f, eanble = 0, strlen(mName) = 35
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@134f25e7
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = CM36686 Proximity sensor
I/RemoteViews( 1241): setHTCTheme(com.htc.updater,true,33751145)
W/SensorService(  968): pid=968, uid=1000
W/SensorService(  968): Active sensors: size = 2
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@98bc19f, eanble = 0, strlen(mName) = 35
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@134f25e7
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  968): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@98bc19f
E/ActivityThread(  968): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@57a12ec that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  968): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@57a12ec that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  968): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  968): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  968): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  968): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  968): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  968): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  968): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  968): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  968): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  968): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  968): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  968): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  968): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  968): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/RemoteViews( 1241): apply : com.htc.updater 0 9 0 36
D/AutoSetting( 1617): service - mHandler: cancel location update
,D/AutoSetting( 1617): service -           changes count: 0
,I/art     (  968): Explicit concurrent mark sweep GC freed 57259(3MB) AllocSpace objects, 3(660KB) LOS objects, 33% free, 18MB/28MB, paused 1.414ms total 155.197ms
,I/PowerUsageList:PowerUsageHelper( 6808): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/SmartSyncUtils( 6808): isEpsOn(), nState = 0
,D/PowerUsageList:BatterySipperExt( 6808): gen(), null == sipper.uidObj, userId = 0,
,D/SmartSyncUtils( 6808): getMobilePolicyEnabled, result = true
,D/WifiService(  968): New client listening to asynchronous messages
E/WifiTrafficPoller(  968): ADD_CLIENT: 9
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  968): Setting HAL interactive mode to false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  968): Excessive delay in setPowerMode(): 293ms
,D/PMS     (  968): Setting HAL interactive mode to false done,
D/PMS     (  968): Setting HAL auto-suspend mode to true
D/PMS     (  968): Setting HAL auto-suspend mode done
,W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,I/InputMethodManagerService(  968): screenObserver, isScreenOn=false
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  968): Disable input method client, pid=6430
,I/InputMethodManager( 6430): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{509b469 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@ddd3b5
I/InputManager(  968): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
D/PMS     (  968): acquireWL(3e273acc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/HABCtrl (  968): TPE algorithm. remove timeout.
D/PMS     (  968): releaseWL(3e273acc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  968): OOBE c monitor 11
,I/PhoneStatusBar( 1241): setImeWindowStatus(false,false)
I/IntentController( 1241): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/HtcPowerSaver(  968): updateBatteryInfo
D/PowerUI ( 1241): closing low battery warning: level=100
D/PowerUI ( 1241): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1241): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PMS     (  968): runPSCheck
D/WifiController(  968): handleMessage: E msg.what=155652
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): processMsg: DeviceActiveState
I/HtcPowerSaver(  968): >> updateStatus
,D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/NfcService( 1533): ScreenObserver: OFF
,D/NfcService( 1533): applyRouting - 0
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus,
D/PMS     (  968): acquireWL(30666115): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1533 1027 null
D/NfcService( 1533): applyRouting -2
,D/NfcService( 1533): applyRouting
D/NfcService( 1533): Ignore this applyRouting...
D/PMS     (  968): releaseWL(30666115): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ClockController( 1241): stop clock update:screen off
,I/BatteryController( 1241): status:5 level:100 unsupport:false plugged:true
,D/PowerUsageList:PowerUsageHelper( 6808): MY_DEBUG = false
,D/Process (  968): killProcessQuiet, pid=5977
,I/ActivityManager(  968): Killing 5977:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5977
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
,D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
,D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: true,
,I/ConnectivityHelper( 1563): [onReceive] WIFI(1): CONNECTED,
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  968): acquireWL(3869ec2a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/PMS     (  968): acquireWL(1d8a8a1b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 968 1000 null
,D/PMS     (  968): releaseWL(1d8a8a1b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE,
D/GpsLocationProvider(  968): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  968): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
,I/NetworkMonitor( 6645): type=WIFI subType= reason=null isConnected=true
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 27 num clients 9
,E/GpsLocationProvider(  968): No APN found to select.
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 27 num clients 9
,V/MusicLeanback( 6645): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/PMS     (  968): releaseWL(3869ec2a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/AutoSetting( 1617): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6383): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 6383): onReceive CONNECTIVITY_CHANGE networkType=1
,D/MdScPhnSt( 6541): [81f.1.]  listen tmrbb8,
,D/AutoSetting( 1617): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1617): service - onStartCommand() screen is off, don't request location
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4429, uid=10024, userID:0
,D/PMS     (  968): acquireWL(3029dcd): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,D/ConnectivityService(  968): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10024
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
I/iu.Environment( 4429): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Forcing reevaluation
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
,D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/MdScDataSum( 6541): [81f.1.] summary 118:p1 ignore
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/iu.UploadsManager( 4429): num queued entries: 0
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/iu.UploadsManager( 4429): num updated entries: 0
D/PMS     (  968): releaseWL(3029dcd): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
I/iu.SyncManager( 4429): NEXT; no task
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1241): CM callback handler got msg 524290
I/SecurityController( 1241): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ChimeraCfgMgr( 4429): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4429): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc    ( 5779): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5779): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5779): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5779): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5779): [NET] android_getaddrinfo_proxy+
D/libc    ( 5779): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5779): [NET] android_getaddrinfo_proxy-, success
,I/GLSUser ( 1959): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1959): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1959): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1959): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4429): [AccountUtils] Account not ready
W/Kids    ( 4429): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4429): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4429): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4429): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4429): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4429): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4429): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4429): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4429): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4429): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4429): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4429): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1351): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1241): reapply : com.google.android.gms 1 40
,I/Babel   ( 5779): connection state changed from DISCONNECTED to CONNECTED
,D/PMS     (  968): releaseWL(169fc14e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1579051942] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1579051938] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  968): handleMessage: X
,D/PMS     (  968): acquireWL(cfdc1e7): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6645 10159 null,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6645, uid=10159, userID:0,
,D/PMS     (  968): releaseWL(cfdc1e7): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6645): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6645): Stop autocaching.,
,D/WearableService( 5686): callingUid 10024, callindPid: 5686,
,E/GmsUtils( 6645): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 6645): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 5
,D/PMS     (  968): acquireWL(16d5d256): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024}
V/AlarmManager(  968): sending alarm PendingIntent{23a4f2d7: PendingIntentRecord{d47cdb3 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=115944, Int=0,
,D/PMS     (  968): acquireWL(188317c4): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(16d5d256): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1959): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1959): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1959): [NET] android_getaddrinfo_proxy+
D/libc    ( 1959): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1959): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1959): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1959): [NET] android_getaddrinfofornet-, err=8
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:923] from screen [on:0 period:-1579051012] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1579051010] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  968): handleMessage: X
,D/PMS     (  968): acquireWL(6a706ad): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1959 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1959): Connected
,D/PMS     (  968): releaseWL(188317c4): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(6a706ad): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): acquireWL(ff4bde2): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1959 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1959): Message class com.google.f.a.a.p
,D/PMS     (  968): releaseWL(ff4bde2): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1241): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,I/jxcore-log( 6430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6430): 
,I/jxcore-log( 6430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6430): 
,I/jxcore-log( 6430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6430): 
,I/jxcore-log( 6430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6430): 
,I/jxcore-log( 6430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 6430): 
,I/jxcore-log( 6430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 6430): 
,I/jxcore-log( 6430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 6430): 
,I/jxcore-log( 6430): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6430): 
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 5,
,D/ContactMessageStore( 1510): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1510): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6430): Test app app.js loaded,
I/jxcore-log( 6430): 
,I/chromium( 6430): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): ,	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6430): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27f27a4a added. We now have 1 listener(s),
D/BluetoothAdapter( 6430): 516449091: getState(). Returning 12
I/jxcore-log( 6430): BLE advertisement is supported
I/jxcore-log( 6430): 
,D/Process (  968): killProcessQuiet, pid=5578
,I/ActivityManager(  968): Killing 5578:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/ActivityManager(  968): Recipient 5578,
,D/PMS     (  968): acquireWL(1bdbe573): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
,V/AlarmManager(  968): sending alarm PendingIntent{20024133: PendingIntentRecord{31457cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=133712, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{67bec30: PendingIntentRecord{21da60a9 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143384, Int=0
,D/PMS     (  968): releaseWL(1bdbe573): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1241): Weather sync is On,
W/WeatherTimeKeeper( 1241): [refreshWeatherData] no weather data
,D/AutoSetting( 1617): service - handleMessage() stop self
,D/AutoSetting( 1617): service - handleMessage() quit looper
D/AutoSetting( 1617): service - onDestroy() END,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  968): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
D/PMS     (  968): acquireWL(1f24d62e): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 968 1000 null
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  968): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  398): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  968): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  968): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  968): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  968):  [handleDownloadXtraData]inject done.
D/PMS     (  968): acquireWL(372c273a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  968): releaseWL(1f24d62e): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  968): releaseWL(372c273a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/WifiStateMachine(  968): handleMessage: E msg.what=131165,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState,
E/WifiStateMachine(  968):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): handleMessage: X
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4
,E/WifiStateMachine(  968): handleMessage: E msg.what=131326,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState what:131326 2 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  968): handleMessage: X
,D/PMS     (  968): acquireWL(29c8feb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(29c8feb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  968): updateBatteryInfo
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  968): runPSCheck
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
,D/HtcPowerSaver(  968): Checking...
I/IntentController( 1241): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PowerUI ( 1241): closing low battery warning: level=100
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1241): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): handleMessage: E msg.what=155652
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/BatteryController( 1241): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1510): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  968): acquireWL(b451148): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{1000},
V/AlarmManager(  968): sending alarm PendingIntent{3d5c7be1: PendingIntentRecord{3f257d06 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454414913809, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{20024133: PendingIntentRecord{31457cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=193712, Int=0,
D/PMS     (  968): acquireWL(7b23fc7): PARTIAL_WAKE_LOCK  *backup* 0x1 968 1000 null
,V/AlarmManager(  968): sending alarm PendingIntent{313df9f4: PendingIntentRecord{2043f51d android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203289, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{230c6392: PendingIntentRecord{7891163 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191052, Int=0
,W/BackupManagerService(  968): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  968): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  968): releaseWL(7b23fc7): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  968): acquireWL(e3ac160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(b451148): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/WeatherUtility( 1241): Weather sync is On
W/WeatherTimeKeeper( 1241): [refreshWeatherData] no weather data
,D/PMS     (  968): acquireWL(262fc619): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(e3ac160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  968): releaseWL(262fc619): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(3b6549db): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(3b6549db): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): acquireWL(21035c78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(21035c78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(116b1f51): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(17cd33b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(2d4dc824): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(116b1f51): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1959): Vacuum at: now=1454414949891 tag=VacuumService,
,I/GoogleURLConnFactory( 1959): Using platform SSLCertificateSocketFactory,
D/PMS     (  968): releaseWL(17cd33b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(21f0d542): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1959): No account for auth token provided
,D/PMS     (  968): releaseWL(21f0d542): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(7911953): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(7911953): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1959): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1959): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1959): [NET] android_getaddrinfo_proxy+
D/libc    ( 1959): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  398): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  398): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  398): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  398): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1959): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1959): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1959): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1959): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1959): No account for auth token provided,
,W/Uploader( 1959): No account for auth token provided,
,W/Uploader( 1959):  no longer exists, so no auth token.
,W/Uploader( 1959): No account for auth token provided,
,I/GLSUser ( 1959): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1959): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1959): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1959): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1351): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1241): reapply : com.google.android.gms 4 40
,E/Uploader( 1959): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1959): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1959): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1959): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1959): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1959): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1959): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1959): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1959): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1959): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1959): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1959): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1959): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1959): No account for auth token provided,
,D/PMS     (  968): releaseWL(2d4dc824): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): acquireWL(34bb2da7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(34bb2da7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(31c58254): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1959 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(31c58254): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1241): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
D/HtcAppUPService( 1617): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@296ad45f
D/HtcUPManager( 1241): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  968): killProcessQuiet, pid=5893
I/ActivityManager(  968): Killing 5893:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5893
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  968): acquireWL(3fc645fd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(3fc645fd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1241): closing low battery warning: level=100
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
I/IntentController( 1241): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1241): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1241): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6430): --= Surplus to requirements =--,
I/jxcore-log( 6430): 
I/jxcore-log( 6430): ****TEST TOOK:  ms ****
I/jxcore-log( 6430): 
I/jxcore-log( 6430): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 6430): 
,E/cutils-trace( 6885): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 6885): ====startRecUseTime====,
D/htc.customization.log.level( 6885):  is 
W/CustomizationLogLevel( 6885): Level value is invalid, use default level 2
,D/CustomizationManager( 6885):  Read ACC file spent 0.046 (s)
,D/CIDMapFileReader( 6885): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6885): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6885): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6885): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6885): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6885): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6885): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 6885): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6885): Parsing tag category name = system
,I/CustomizationCIDLoader( 6885): Parsing tag category name = application
,I/CustomizationCIDLoader( 6885): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 6885): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6885): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 6885): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6885): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 6885): add string-array item, value = 42507
,I/CustomizationCIDLoader( 6885): add string-array item, value = 21902
I/CustomizationCIDLoader( 6885): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6885): add string-array item, value = 23420
I/CustomizationCIDLoader( 6885): add string-array item, value = 22299
I/CustomizationCIDLoader( 6885): add string-array item, value = 24002
,I/CustomizationCIDLoader( 6885): add string-array item, value = 23210
I/CustomizationCIDLoader( 6885): add string-array item, value = 23205
I/CustomizationCIDLoader( 6885): add string-array item, value = 23806
I/CustomizationCIDLoader( 6885): add string-array item, value = 23430,
I/CustomizationCIDLoader( 6885): add string-array item, value = 23408
I/CustomizationCIDLoader( 6885): add string-array item, value = 27205
I/CustomizationCIDLoader( 6885): add string-array item, value = 42507:C:1:0,
I/CustomizationCIDLoader( 6885): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6885): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6885): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6885): add string-array item, value = 22299:D:0:0
,I/CustomizationCIDLoader( 6885): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6885): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6885): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6885): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6885): add string-array item, value = 23430:C:1:0,
I/CustomizationCIDLoader( 6885): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6885): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6885):  Read CID file spent 0.098 (s)
D/CustomizationManager( 6885):  All configurations done spent 0.098 (s)
,D/PackageManager(  968): deletePackageAsUser: pkg=com.test.thalitest, pid=6885, uid=2000 userid=0,
,D/Process (  968): killProcessQuiet, pid=6430,
I/ActivityManager(  968): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
,I/ActivityManager(  968): Killing 6430:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  968): Skipping PackageSetting{b289c8f com.example.hello/10374} due to missing metadata
,I/ActivityManager(  968): Recipient 6430,
E/InputEventReceiver( 1405): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{19950237 uid 10366 pid 6430} (c)'
I/WindowState(  968): WIN DEATH: Window{19090336 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  968): Client connection lost with reason: 4
,E/libprocessgroup(  968): failed to kill 1 processes for processgroup 6430,
,I/ActivityManager(  968):   Force finishing activity ActivityRecord{1a56337b u0 com.test.thalitest/.MainActivity t8}
,I/ActivityManager(  968): Force stopping com.test.thalitest appid=10366 user=0: pkg removed,
,I/ActivityManager(  968):   Force finishing activity ActivityRecord{1a56337b u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  968): Duplicate finish request for ActivityRecord{1a56337b u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  968): Spurious death for ProcessRecord{2f6d12f2 6430:com.test.thalitest/u0a366}, curProc for 6430: null
,D/DotMatrix( 1351): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1351): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1351): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/PMS     (  968): acquireWL(662fd43): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1750): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
W/GeofencerStateMachine( 1846): Ignoring removeGeofence because network location is disabled.
D/PMS     (  968): releaseWL(662fd43): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1750): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PhoneApp( 1510): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
D/VoicemailCleanupService( 1713): Cleaning up data for package: com.test.thalitest
I/[PluginManager]RegisterService( 1617): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,D/AccTypeManager( 1750): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/[PluginManager]RegisterService( 1617): handle notify Blinkfeed plugin client changed
,I/art     ( 1563): Explicit concurrent mark sweep GC freed 23660(1412KB) AllocSpace objects, 7(492KB) LOS objects, 34% free, 30MB/46MB, paused 972us total 97.275ms
,D/Prism.PackageStateRece_( 1563): action: android.intent.action.PACKAGE_REMOVED
,I/Prism.ItemManager( 1563): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1563): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,E/ExternalAccountType( 1750): Unsupported attribute readOnly
,I/ActivityManager(  968): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6905 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/Launcher( 1563): Deferring update until onResume
,D/Launcher( 1563): waitUntilResume // bindAppsRemoved
,I/InputMethodManagerService(  968): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/StatusBarManagerService(  968): setSystemUiVisibility(0x700),
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  968): hiding MENU key
,I/art     (  968): Explicit concurrent mark sweep GC freed 35468(2MB) AllocSpace objects, 6(584KB) LOS objects, 33% free, 18MB/28MB, paused 5.308ms total 245.902ms
D/StatusBarManagerService(  968): setSystemUiVisibility(0xc0000700)
I/art     (  968): WaitForGcToComplete blocked for 183.396ms for cause Explicit
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
,D/FindExtension( 1563): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,W/ContextImpl( 6905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
I/ThreadedRenderer( 1563): Defer allocateBuffers to drawing time
,W/InputMethodManagerService(  968): Got RemoteException sending setActive(false) notification to pid 6430 uid 10366
,D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
,I/ActivityManager(  968): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6931 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  968): killProcessQuiet, pid=6587
,I/ActivityManager(  968): Killing 6587:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  968): Unable to load service info ResolveInfo{16ce4549 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  968): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  968): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  968): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  968): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  968): Explicit concurrent mark sweep GC freed 9087(578KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 18MB/28MB, paused 1.900ms total 160.850ms
,I/ActivityManager(  968): Recipient 6587,
,D/JobSchedulerService(  968): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  968): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  968): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/PhoneStatusBar( 1241): setImeWindowStatus(false,false)
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6931, uid=10072, userID:0,
,W/global  ( 6931): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6931): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 6931): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6931): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 6931): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  968): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6970 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 6931): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 6931): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SQLiteDatabase( 6931): Failed to open database '/data/data/com.android.vending/databases/library.db'.,
E/SQLiteDatabase( 6931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
,E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
,E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267),
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 6931): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6931): 	,at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6931): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6931): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6931): FATAL EXCEPTION: libraries-thread,
E/AndroidRuntime( 6931): Process: com.android.vending, PID: 6931
E/AndroidRuntime( 6931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6931): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6931): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 6931): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 6931): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 6931): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6931): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6931): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6931): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  968): App crashed! Process: com.android.vending
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6931, uid=10072, userID:0
,E/SQLiteDatabase( 6931): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55),
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 6931): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6931): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6931): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6931): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService(  968): Can't write: system_app_crash
E/DropBoxManagerService(  968): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  968): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  968): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  968): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  968): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  968): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  968): 	... 5 more
D/Process ( 6931): killProcess, pid=6931
E/AndroidRuntime_2_crash( 6931): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 6931): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 6931): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 6931): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 6931): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 6931): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 6931): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 6931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 6931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 6931): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 6931): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 6931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 6931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 6931): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 6931): 	at com.goog,le.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 6931): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 6931): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 6931): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 6931): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 6931): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 6931): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 6931): 	... 4 more
E/SQLiteDatabase( 6931): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 6931): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 6931): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6931): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6931): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6931): 	at java.lang.Thread.run(Thread.java:818)
,E/AndroidRuntime_3_crash( 6931): crash in the same process: AsyncTask #2
E/AndroidRuntime_3_crash( 6931): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 6931): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 6931): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 6931): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 6931): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 6931): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 6931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 6931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 6931): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 6931): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 6931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 6931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 6931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 6931): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 6931): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 6931): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 6931): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 6931): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 6931): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 6931): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 6931): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 6931): 	... 4 more
,D/Process ( 6931): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
W/ResourcesManager( 6970): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6970): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6970): VM with version 2.1.0 has multidex support,
I/MultiDex( 6970): install
I/MultiDex( 6970): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  968): Recipient 6931
,I/ActivityManager(  968): Process com.android.vending (pid 6931) has died
,V/JNIHelp ( 6970): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6970): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6970): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e059b49: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6970): Installed default security provider GmsCore_OpenSSL
,E/SQLiteLog( 1959): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1959): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x557afb7f60
E/AndroidRuntime( 1959): FATAL EXCEPTION: main
E/AndroidRuntime( 1959): Process: com.google.process.gapps, PID: 1959
E/AndroidRuntime( 1959): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1959): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1959): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1959): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1959): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1959): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1959): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1959): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1959): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1959): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1959): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1959): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1959): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1959): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1959): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1959): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1959): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1959): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1959): 	... 9 more
,E/ActivityManager(  968): App crashed! Process: com.google.process.gapps
D/Process ( 1959): killProcess, pid=1959
,D/Process ( 1959): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  968): Can't write: system_app_crash,
E/DropBoxManagerService(  968): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  968): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  968): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  968): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  968): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  968): 	,at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  968): 	... 5 more
,W/NativeLibraryUtils( 6970): Failed to open lock file,
W/NativeLibraryUtils( 6970): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6970): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 6970): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 6970): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 6970): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6970): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6970): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 6970): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 6970): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 6970): 	... 3 more
,E/JavaBinder( 6970): !!! FAILED BINDER TRANSACTION !!!,
,E/JavaBinder( 6970): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 6970): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 6970): !!! FAILED BINDER TRANSACTION !!!,
,E/JavaBinder( 6970): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 6970): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 6970): !!! FAILED BINDER TRANSACTION !!!,
,E/JavaBinder( 6970): !!! FAILED BINDER TRANSACTION !!!,
,E/JavaBinder( 6970): !!! FAILED BINDER TRANSACTION !!!,
,D/Process (  968): killProcessQuiet, pid=6600,
,I/ActivityManager(  968): Killing 6600:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/lowmemorykiller(  382): Error writing /proc/1959/oom_score_adj; errno=22
,I/ActivityManager(  968): Recipient 1959
,I/ActivityManager(  968): Recipient 6600
,I/ActivityManager(  968): Process com.google.process.gapps (pid 1959) has died
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 20999ms
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,I/ActivityManager(  968): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=7007 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 7007): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7007): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7007): VM with version 2.1.0 has multidex support,
I/MultiDex( 7007): install,
,I/MultiDex( 7007): VM has multidex support, MultiDex support library is disabled.
,I/GservicesProvider( 7007): Gservices pushing to system: true; secure/global: true,
,E/SQLiteDatabase( 7007): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.,
E/SQLiteDatabase( 7007): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737),
E/SQLiteDatabase( 7007): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7007): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7007): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7007): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7007): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7007): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7007): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7007): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7007): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7007): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7007): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424),
E/SQLiteDatabase( 7007): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7007): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7007): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7007): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7007): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7007): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7007): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824),
,E/AndroidRuntime( 7007): FATAL EXCEPTION: main,
E/AndroidRuntime( 7007): Process: com.google.process.gapps, PID: 7007
E/AndroidRuntime( 7007): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7007): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7007): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7007): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7007): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7007): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7007): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7007): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7007): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7007): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7007): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7007): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7007): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7007): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185),
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7007): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7007): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7007): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7007): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7007): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7007): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7007): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7007): 	... 11 more
,E/ActivityManager(  968): App crashed! Process: com.google.process.gapps
D/Process ( 7007): killProcess, pid=7007
E/DropBoxManagerService(  968): Can't write: system_app_crash
E/DropBoxManagerService(  968): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  968): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  968): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  968): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  968): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  968): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  968): 	... 5 more
D/Process ( 7007): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/Prism.ItemManager( 1563): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1563): loadItems() com.htc.launcher.pageview.WidgetManager@184a7b6 +
I/Prism.WidgetManager( 1563): onLoadItems() +
,I/ActivityManager(  968): Recipient 7007
,I/ActivityManager(  968): Process com.google.process.gapps (pid 7007) has died,
W/ActivityManager(  968): Service crashed 2 times, stopping: ServiceRecord{375f87a8 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
W/ActivityManager(  968): Service crashed 2 times, stopping: ServiceRecord{33e5b14c u0 com.google.android.gms/.gcm.GcmService}
W/ActivityManager(  968): Service crashed 2 times, stopping: ServiceRecord{1246993f u0 com.google.android.gms/.gcm.http.GoogleHttpService},
W/ActivityManager(  968): Service crashed 2 times, stopping: ServiceRecord{72ca8ae u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,W/ResourcesManager( 1563): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/PMS     (  968): acquireWL(af9b21f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000},
V/AlarmManager(  968): sending alarm PendingIntent{20024133: PendingIntentRecord{31457cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=253712, Int=0
,I/ActivityManager(  968): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7030 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,V/AlarmManager(  968): sending alarm PendingIntent{2390796c: PendingIntentRecord{13cec472 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454415013272, Int=0
,D/PMS     (  968): releaseWL(af9b21f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1241): Weather sync is On,
,W/WeatherTimeKeeper( 1241): [refreshWeatherData] no weather data,

```
