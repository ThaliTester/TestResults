#### Test 5753124305d96c2_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiDataStallTracker(  941): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  941): updateDataStallInfo: mDataStallTxRxSum={txSum=121 rxSum=107} preTxRxSum={txSum=104 rxSum=95}
D/WifiDataStallTracker(  941): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  941): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 11 num clients 6
--------- beginning of system
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  941):  packet count Tx=139 Rx=227
E/WifiTrafficPoller(  941): notifying of data activity 1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  941): handleMessage: E msg.what=131155
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1571352395] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1571352393] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  941):  get link layer stats 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1325): environment dirty rate=0 [17][0][0]
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  941): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  941): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.60 txretriesrate=0.00 rxrate=7.15 userTriggerdPenalty0
E/WifiStateMachine(  941):  good link -> stuck count =0
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  941):  badRSSI count0 lowRSSI count0 --> score 60
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  941):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  941): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  941): handleMessage: X
W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  941):  packet count Tx=139 Rx=227
E/WifiTrafficPoller(  941): notifying of data activity 0
D/WIFI_ICON( 1222): WifiActivity: 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/HtcModeClient( 3257): handler message = 4011
E/HtcModeClient( 3257): Check connection and retry 12 times.
,E/cutils-trace( 6425): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6425): ====startRecUseTime====
D/htc.customization.log.level( 6425):  is 
W/CustomizationLogLevel( 6425): Level value is invalid, use default level 2
D/CustomizationManager( 6425):  Read ACC file spent 0.044 (s)
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6425): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6425): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6425): Parsing tag category name = system
I/CustomizationCIDLoader( 6425): Parsing tag category name = application
I/CustomizationCIDLoader( 6425): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6425): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6425): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6425): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6425): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6425): add string-array item, value = 42507
I/CustomizationCIDLoader( 6425): add string-array item, value = 21902
I/CustomizationCIDLoader( 6425): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6425): add string-array item, value = 23420
I/CustomizationCIDLoader( 6425): add string-array item, value = 22299
I/CustomizationCIDLoader( 6425): add string-array item, value = 24002
I/CustomizationCIDLoader( 6425): add string-array item, value = 23210
I/CustomizationCIDLoader( 6425): add string-array item, value = 23205
I/CustomizationCIDLoader( 6425): add string-array item, value = 23806
I/CustomizationCIDLoader( 6425): add string-array item, value = 23430
I/CustomizationCIDLoader( 6425): add string-array item, value = 23408
I/CustomizationCIDLoader( 6425): add string-array item, value = 27205
I/CustomizationCIDLoader( 6425): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6425): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6425):  Read CID file spent 0.088 (s)
D/CustomizationManager( 6425):  All configurations done spent 0.089 (s)
I/ActivityManager(  941): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6425 on display 0
D/PMS     (  941): acquireHCC(38ca673c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 941 1000 null
D/PMS     (  941): acquireHCC(2e0a6cc5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 941 1000 null
W/asset   (  941): Copying FileAsset 0x55a6543dd0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  941): acquireWL(3874bb28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 941 1000 null
I/FeedHostManager( 1618): [onPause]
I/FeedProviderManager( 1618): onPause
I/FeedHostManager( 1618): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@1956b5cd
I/SocialFeedProvider( 1618): +onPause
I/SocialFeedProvider( 1618): -onPause
I/AnimationUtil(  941): isHTCRecent(ThaliTest/Recent screens.)/5
W/HtcSystemUPManager(  941): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  941): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6443 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  443): Explicit concurrent mark sweep GC freed 8675(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 232us total 16.924ms
I/art     (  443): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 403us total 16.217ms
I/art     (  443): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 393us total 16.120ms
W/asset   ( 6443): Copying FileAsset 0xac444160 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  941):  packet count Tx=139 Rx=227
D/StatusBarManagerService(  941): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
I/TrimMemoryManager( 1618): [trimMemory] 20
I/WebViewFactory( 6443): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6443): Time to load native libraries: 9 ms (timestamps 2141-2150),
,I/LibraryLoader( 6443): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6443): Binding Chromium to main looper Looper (main, tid 1) {1f34ed11},
I/LibraryLoader( 6443): Expected native library version number "",actual native library version number "",
,I/chromium( 6443): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6443): Initializing chromium process, singleProcess=true
,W/art     ( 6443): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6443): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6443): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6443): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6443): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6443): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6443): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6443): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6443): Local Branch: 
I/Adreno-EGL( 6443): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6443): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
,I/Adreno-EGL( 6443):                  d74aa161a12b9c6fc6332151
,W/System.err(  941): java.lang.Throwable: stack dump
D/BluetoothManagerService(  941): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  941): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bf68bb1:true
,W/System.err(  941): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  941): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  941): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  941): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6443): 116017485: getState(). Returning 12,
,W/art     ( 6443): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6443): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6443): CordovaWebView is running on device made by: HTC,
,W/art     ( 6443): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6443): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6443): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/Process (  941): killProcessQuiet, pid=5868
I/ActivityManager(  941): Killing 5868:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  941): Recipient 5868
,D/Process (  941): killProcessQuiet, pid=5820
I/ActivityManager(  941): Killing 5820:com.google.android.gm/u0a106 (adj 15): empty #18
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  941): Recipient 5820
,D/FindExtension( 6443): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6443): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@79049b2, mServedView=org.apache.cordova.engine.SystemWebView{208fcd03 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1036480,
,I/InputMethodManagerService(  941): Disable input method client, pid=1618
D/StatusBarManagerService(  941): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  941): Enable input method client, pid=6443
,I/ActivityManager(  941): Displayed com.test.thalitest/.MainActivity: +977ms
,D/PMS     (  941): releaseWL(3874bb28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false),
,W/BindingManager( 6443): Cannot call determinedVisibility() - never saw a connection for the pid: 6443,
,W/XT9_C   ( 1390): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1390): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1390): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1390): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/JsMessageQueue( 6443): Set native->JS mode to OnlineEventsBridgeMode,
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  941):  packet count Tx=139 Rx=228,
E/WifiTrafficPoller(  941): notifying of data activity 1
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  941): handleMessage: E msg.what=131155
E/WifiStateMachine(  941): processMsg: ConnectedState
,E/WifiStateMachine(  941):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1571349376] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1571349375] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  941):  get link layer stats 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1325): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1325): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  941): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
,E/WifiStateMachine(  941): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.30 txretriesrate=0.00 rxrate=4.08 userTriggerdPenalty0
E/WifiStateMachine(  941):  good link -> stuck count =0
E/WifiStateMachine(  941):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  941):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  941): RSSI current: 3 new: -58, 3
,D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  941): handleMessage: X
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/jxcore_app_log( 6443): JniHelper::setJavaVM(0xab2d78f8), pthread_self() = -1403027016
,I/chromium( 6443): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,D/PMS     (  941): releaseHCC(38ca673c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  941): releaseHCC(2e0a6cc5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  941):  packet count Tx=139 Rx=228
E/WifiTrafficPoller(  941): notifying of data activity 0
D/WIFI_ICON( 1222): WifiActivity: 0
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 6443): Initializing JXcore engine
W/jxcore-log( 6443): JXcore engine is ready
,W/jxcore-log( 6443): Starting JXcore engine
,W/jxcore-log( 6443): Platform android,
W/jxcore-log( 6443): 
W/jxcore-log( 6443): Process ARCH arm
W/jxcore-log( 6443): 
,I/jxcore-log( 6443): JXcore Cordova bridge is ready!
I/jxcore-log( 6443): 
W/jxcore-log( 6443): JXcore engine is started
,I/jxcore-log( 6443): Toggling radios to true
I/jxcore-log( 6443): 
,D/BluetoothAdapter( 6443): enable(): BT is already enabled..!
,D/WifiService(  941): New client listening to asynchronous messages
E/WifiTrafficPoller(  941): ADD_CLIENT: 7
,D/WifiManager( 6443): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
W/Settings:Agent(  941): MONITOR_LOG
D/WifiService(  941): setWifiEnabled: true pid=6443, uid=10366
W/Settings:Agent(  941): name: wifi_on
E/WifiService(  941): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  941): value: 2
I/WifiService(  941): isSprintWifiRestricted(): false
W/Settings:Agent(  941): >> traceCallingStack()
I/WifiService(  941): isMdmWifiRestricted(): false
W/Settings:Agent(  941): Process.myPid(): 941
W/Settings:Agent(  941): Process.myTid(): 1513
W/Settings:Agent(  941): Process.myUid(): 1000
W/Settings:Agent(  941): 
W/Settings:Agent(  941): 
W/System.err(  941): java.lang.Throwable: stack dump
,W/System.err(  941): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  941): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  941): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  941): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  941): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  941): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  941): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  941): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  941): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  941): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  941): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  941): 
W/Settings:Agent(  941): << traceCallingStack(): 18(ms)
D/WifiController(  941): handleMessage: E msg.what=155656
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): handleMessage: X
D/WifiManager( 6443): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  941): handleMessage: E msg.what=131145
D/WifiManager( 6443): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/jxcore-log( 6443): Radios toggled
I/jxcore-log( 6443): 
D/wpa_supplicant( 1325): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1325): wlan0: Cancelling scan request
D/wpa_supplicant( 1325): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1325): TDLS: Tear down peers
D/wpa_supplicant( 1325): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6443): My device name is: HTC-HTC One M8s
I/jxcore-log( 6443): 
,D/wpa_supplicant( 1325): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1325): wlan0: Deauthentication notification
D/wpa_supplicant( 1325): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1325): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1325): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1325): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1325): enter disconnect check
I/wpa_supplicant( 1325): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1325): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1325): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  941): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  941): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  941): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/Tethering(  941): interfaceLinkStateChanged wlan0, false
D/Tethering(  941): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  941): interfaceLinkStateChanged wlan0, false
D/Tethering(  941): interfaceStatusChanged wlan0, false
,D/Tethering(  941): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  941): TetherInterfaceSM: wlan0: exit InitialState
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  941): TetherInterfaceSM: wlan0: enter UnavailableState
,E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): TDLS: Remove peers on disassociation
D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
D/wpa_supplicant( 1325): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x556c1e4f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1325):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1325): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1325): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1325): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1325): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1325): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1325): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1325): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1325): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1325): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1325): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1325): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  941): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  941): handleMessage: new destination call exit/enter
E/WifiStateMachine(  941): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  941): invokeExitMethods: ConnectedState
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  941): WifiStateMachine: Leaving Connected state
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiPerfLock(  941): release()
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  941): PerfLock released for exiting ConnectedState
D/HTCRequest(  941): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  941): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  941): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  941): invokeExitMethods: L2ConnectedState
D/Tethering(  941): sendTetherStateChangedBroadcast 0, 0, 0
E/,WifiStateMachine(  941): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  941): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  941): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  941): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1325): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1325): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1325): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1325): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1325): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  941): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1325): Power_Mode_Type mode = 0
I/wpa_supplicant( 1325): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/PMS     (  941): acquireWL(207db559): PARTIAL_WAKE_LOCK  NetworkStats 0x1 941 1000 null
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/WifiDataStallTracker(  941): setDhcpActive: false
D/UsbnetService(  941): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbDeviceManager(  941): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiP2pService(  941): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  941): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1917): Read error: ssl=0x55a5ff9780: I/O error during system call, Connection timed out
D/PMS     (  941): acquireWL(3e9d851e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  941): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  941): setDetailed state send new extra info<unknown ssid>
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  941): NetworkAgent != null
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  941): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
V/NetworkPolicy(  941): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL true Token 11
,D/libc    (  941): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1917): SSL shutdown failed: ssl=0x55a5ff9780: I/O error during system call, Broken pipe
E/WifiTrafficPoller(  941):  packet count Tx=139 Rx=228
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  941): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
,D/WifiDataStallTracker(  941): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  941): stopDataStallAlarm 
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): DefaultState{ when=-2ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): Forcing reevaluation
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiDataStallTracker(  941): ENABLE_DATA_MONITOR_POLL false Token 1
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): Validated
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  941): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  941): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  941): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1325): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1325): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SAVE_CONFIG'
D/PMS     (  941): releaseWL(3e9d851e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1325): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1325): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1325): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  941): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  941): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  941): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  941):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  941): Start Disconnecting Watchdog 1
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131146
E/WifiStateMachine(  941): processMsg: DisconnectingState
,E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/TetherSettings( 5961): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5961): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5961): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5961): Cust_ConnectToPC   : spcsc>false
D/        ( 5961): Cust_ConnectToPC   : IPT>true
D/        ( 5961): Cust_ConnectToPC   : Singel_USB>false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  941):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
W/Settings( 5961): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/wpa_supplicant( 1325): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1325): Fast associate: Old scan results
D/wpa_supplicant( 1325): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1325): wpa_supplicant_scan enter
D/wpa_supplicant( 1325): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1325): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1325): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1325): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1325): WPS:  * Request Type
D/wpa_supplicant( 1325): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1325): WPS:  * UUID-E
D/wpa_supplicant( 1325): WPS:  * Primary Device Type
D/wpa_supplicant( 1325): WPS:  * RF Bands (3)
D/wpa_supplicant( 1325): WPS:  * Association State
D/wpa_supplicant( 1325): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1325): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1325): WPS:  * Manufacturer
D/wpa_supplicant( 1325): WPS:  * Model Name
D/wpa_supplicant( 1325): WPS:  * Model Number
D/wpa_supplicant( 1325): WPS:  * Device Name
D/wpa_supplicant( 1325): WPS:  * Version2 (0x20)
D/PMS     (  941): releaseWL(207db559): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1325): P2P: * P2P IE header
D/wpa_supplicant( 1325): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1325): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1325): wlan0: Add radio work 'scan'@0x556c1c7860
D/wpa_supplicant( 1325): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1325): wlan0: Starting radio work 'scan'@0x556c1c7860 after 0.000125 second wait
D/wpa_supplicant( 1325): wlan0: nl80211: scan request
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  941): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1325): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1325): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1325): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1325): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1325): wlan0: Own scan request started a scan in 0.000338 seconds
I/wpa_supplicant( 1325): wlan0: CTRL-EVENT-SCAN-STARTED 
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  941): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147460
E/WifiStateMachi,ne(  941): processMsg: DisconnectingState
E/WifiMonitor(  941): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  941):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=104841
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiMonitor(  941): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/SmartNS_Utility( 5961): hasRemovableStorageSlot: true
E/WifiStateMachine(  941):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=104842
E/WifiStateMachine(  941): ConnectModeState: Network connection lost 
E/WifiStateMachine(  941): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  941): handleMessage: new destination call exit/enter
D/SmartNS_Utility( 5961): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
E/WifiStateMachine(  941): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  941): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  941): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  941): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  941): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  941): DisconnectedState call setCountryCode()
D/SmartNS_NSReceiver( 5961): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  941):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1325): Pending scan scheduled - reject new request
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  941): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
V/NetworkPolicy(  941): updateNotificationsLocked()
D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147462
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  941):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=104847  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  941): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  941): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=104848  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131101
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
,E/WifiStateMachine(  941):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  941): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  941): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131212
E/WifiStateMachine(  941): processMsg: DisconnectedState
,E/WifiStateMachine(  941):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  941): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131212
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
E/WifiStateMachine(  941): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  941): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  941): handleMessage: X
D/WifiNetworkAgent(  941): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  941): handleMessage: E msg.what=131212
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
W/ContextImpl( 5961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  941): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  941): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147462
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=104861  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  941): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  941): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  941): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  941): NetworkAgent == null
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  941): processMsg: ConnectModeState
,E/WifiStateMachine(  941):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=104865  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  941): handleMessage: X
I/SmartNS_Utility( 5961): setISNotification
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false),
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/SmartNS_Utility( 5961): usb_cable_connect = 1
,D/SmartNS_Utility( 5961): usb_denied = 0
I/SmartNS_PSService( 5961): usb notificaiton:true
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 5961): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:5
E/WifiDataStallTracker(  941): DATA_MONITOR_POLL false Token 2
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
,D/SmartNS_Utility( 5961): usb_cable_connect = 1
,D/SmartNS_Utility( 5961): usb_denied = 0
I/SmartNS_PSService( 5961): usb notificaiton:true
,E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5961): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): reapply : com.android.settings 0 36,
D/ConnectivityService(  941): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  941):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  941): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  941): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): Disconnected - quitting,
,D/ConnectivityService(  941): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  941): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  941): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  941): Removing idletimer
D/usbnet  (  941):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  941):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  941): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI    (  941): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  941): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524292
I/SecurityController( 1222): onLost 100
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,I/ActivityManager(  941): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6504 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/PMS     (  941): acquireWL(3d87bbcc): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 941 1000 null
D/CSLegacyTypeTracker(  941): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  941): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  941): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  941): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  941): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  941): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  941): acquireWL(19cb4e15): PARTIAL_WAKE_LOCK  NetworkStats 0x1 941 1000 null
E/ConnectivityService(  941): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
V/NetworkPolicy(  941): ensureActiveMobilePolicyLocked()
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
,D/DATA_ICON( 1222): dataConnected: false/false
D/WISPrService( 5961): >>>>>WISPrService start isConnected = true<<<<<
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/NetworkPolicy(  941): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
V/NetworkPolicy(  941): updateIfacesLocked()
V/NetworkPolicy(  941): updateNotificationsLocked(),
D/PMS     (  941): releaseWL(19cb4e15): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WifiService(  941): New client listening to asynchronous messages,
E/WifiTrafficPoller(  941): ADD_CLIENT: 8
,D/NetworkManagementService(  941): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency,
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
V/NetworkPolicy(  941): updateNotificationsLocked()
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL false Token 16 num clients 8
,E/WifiStateMachine(  941): handleMessage: E msg.what=131131
,E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  941): handleMessage: X
,I/ActivityManager(  941): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6527 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,W/WISPrService( 5961): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5961): trigger connection
D/WISPrService( 5961): continue
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5961): start DataConnection
D/libc    ( 5961): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5961): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5961): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5961): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5961): [NET] android_getaddrinfo_proxy+
D/libc    ( 5961): [NET] android_getaddrinfo_proxy get netid:0
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/libc    (  423): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  423): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  423): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  423): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5961): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs,
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/libc    ( 5961): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5961): [NET] android_getaddrinfofornet-, err=8
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/WISPrService( 5961): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname,
,W/ResourcesManager( 6527): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  941): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6551 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/Process (  941): killProcessQuiet, pid=5934
I/ActivityManager(  941): Killing 5934:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  941): Recipient 5934
,I/CalendarProvider2( 6527): Created com.android.providers.calendar.CalendarAlarmManager@6456f11(com.htc.providers.calendar.HtcCalendarProvider@b8da876),
,D/CalendarProvider2( 6527): wait start:true
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false,
D/CalendarProvider2( 6527): wait end:false
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6504): add item 101 (2:g3d21) for 15:android.intent.action.ANY_DATA_STATE
D/FlexNetS( 6527): updateSvcAllowedInSettings:false
D/MdScPhnSt( 6551): [e95.2.]  listen tmrbb8
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6504): remove item 101 (p3d6in88) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6551): [e95.2.] summary 118:p3 ignore
,D/FlexNetS( 6527): updateSvcAllowedInSettings:false
,I/art     (  941): Explicit concurrent mark sweep GC freed 35665(1848KB) AllocSpace objects, 5(292KB) LOS objects, 33% free, 16MB/25MB, paused 1.586ms total 152.788ms
,D/Process (  941): killProcessQuiet, pid=6240,
I/ActivityManager(  941): Killing 6240:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6240,
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL false Token 16 num clients 8,
,E/WifiStateMachine(  941): handleMessage: E msg.what=131155,
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1571346358] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1571346358] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1571346357] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1571346357] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1571346356] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  941): handleMessage: X
,I/HtcModeClient( 3257): handler message = 4011
,E/HtcModeClient( 3257): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3257): Don't start project servcice
,D/HtcModeClient( 3257): setEject: MEDIA_EJECT_STATE = true
,W/SystemReader(  941): Cannot find grip_rejection_width, use default value instead
,D/HtcModeClient( 3257): connectState: CONNECTION_READY = false
D/PMS     (  941): acquireWL(3b28dcda): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5787 10112 null
D/SilentMusic( 3257): call stop
D/HtcModeClient( 3257): close connection
W/HtcModeClient( 3257): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3257): read the terminate packet, so break
D/AccTypeManager( 1749): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/Prism.ItemManager( 1618): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1618): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1618): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,D/AccTypeManager( 1749): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Launcher( 1618): Deferring update until onResume
D/Launcher( 1618): waitUntilResume // bindAppsUpdated
,I/CalendarProvider2( 6527): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,W/ContentResolver( 6527): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/ResourcesManager(  941): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/AccTypeManager( 1749): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  941): Killing 3257:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  941): killProcessQuiet, pid=3257
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  941): releaseWL(3b28dcda): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PhoneApp( 1556): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
E/ExternalAccountType( 1749): Unsupported attribute readOnly
,W/PackageManager(  941): Unable to load service info ResolveInfo{3421421d com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  941): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  941): 	,at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  941): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  941): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  941): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  941): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  941): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  941): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  941): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  941): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  941): Recipient 3257,
,I/BackupManagerService(  941): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,I/[PluginManager]RegisterService( 1514): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
,I/[PluginManager]RegisterService( 1514): handle notify Blinkfeed plugin client changed,
,I/GCoreNlp( 1786): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,D/PackageBroadcastService( 4446): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4446): Null package name or gms related package.  Ignoreing.
,D/PMS     (  941): acquireWL(19a14ab2): PARTIAL_WAKE_LOCK  AsyncService 0x1 6055 10167 null
,D/PMS     (  941): acquireWL(696cd80): PARTIAL_WAKE_LOCK  Icing 0x1 4446 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(31d2afb9): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6055 10167 null
D/PMS     (  941): acquireWL(a555ffe): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): releaseWL(19a14ab2): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/LocationProviderProxy(  941): applying state to connected service
D/PMS     (  941): releaseWL(a555ffe): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4446): updateResources: need to parse f{com.google.android.gms}
,D/LocationProviderProxy(  941): applying state to connected service
,D/PMS     (  941): releaseWL(31d2afb9): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5899): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  941): acquireWL(fbfe67b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1786 10024 WorkSource{10024 com.google.android.gms},
,V/GmsNetworkLocationProvi( 1786): DISABLE
,D/PMS     (  941): releaseWL(fbfe67b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): releaseWL(696cd80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  941): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6595 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/PMS     (  941): acquireWL(2b10cc98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(2b10cc98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/ResourcesManager( 6595): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
I/UpdateIcingCorporaServi( 5899): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
D/CalendarApplication( 6595): onCreate
D/ProviderChangeReceiver( 6595): ---------------------------------------------------
D/ProviderChangeReceiver( 6595): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
D/HtcAlertService( 6595): start to updateAlertNotification!
D/HtcAlertService( 6595): No fired or scheduled alerts
,D/HtcAlertUtils( 6595): -- cancelReminderNotification --
,D/HtcAlertUtils( 6595): broadcastExistReminder!
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/wpa_supplicant( 1325): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1325): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1325): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1325): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1325): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1325): wlan0: Scan completed in 2.075256 seconds
D/wpa_supplicant( 1325): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1325): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1325): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1325): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1325): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 1325): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1325): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1325): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1325): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1325): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1325): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1325): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1325): wlan0: Radio work 'scan'@0x556c1c7860 done in 2.077223 seconds
D/wpa_supplicant( 1325): wlan0: Selecting BSS from priority group 599
D/wpa_supplicant( 1325): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/wpa_supplicant( 1325): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1325): wlan0:    skip - SSID mismatch
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1325): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58 wps
D/wpa_supplicant( 1325): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
E/WifiMonitor(  941): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1325): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1325): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1325):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1325): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1325): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x556c1e6c00  current_ssid=0x0
D/wpa_supplicant( 1325): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/WifiMonitor(  941): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiStateMachine(  941): handleMessage: E msg.what=147461
D/wpa_supplicant( 1325): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1325): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): TDLS: TDLS is allowed in the target BSS
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=37 dispatchEvent: WPS-,AP-AVAILABLE 
E/WifiStateMachine(  941): processMsg: DisconnectedState
D/wpa_supplicant( 1325): wlan0: Add radio work 'connect'@0x556c1c7860
D/wpa_supplicant( 1325): wlan0: First radio work item in the queue - schedule start immediately
W/WifiMonitor(  941): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1325): wlan0: Starting radio work 'connect'@0x556c1c7860 after 0.000110 second wait
I/wpa_supplicant( 1325): check if in concurrent case
I/wpa_supplicant( 1325): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  941): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=38 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1325): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1325): wlan0: Cancelling scan request
D/wpa_supplicant( 1325): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1325): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1325): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1325): wlan0: WPA: clearing own WPA/RSN IE
W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1325): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1325): RSN: PMKSA cache search - network_ctx=0x556c1e6c00 try_opportunistic=0
D/wpa_supplicant( 1325): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1325): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1325): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1325): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1325): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1325): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1325): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1325): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1325): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1325): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  941):  DisconnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:51 bcn=0
E/WifiStateMachine(  941): processMsg: ConnectModeState
D/wpa_supplicant( 1325): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1325): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1325): nl80211: Unsubscribe mgmt frames handle 0x888888dde496e989 (mode change)
D/wpa_supplicant( 1325): nl80211: Subscribe to mgmt frames with non-AP handle 0x556c1e6100
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=0104
E/WifiStateMachine(  941):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:51 bcn=0
E/WifiStateMachine(  941): processMsg: DriverStartedState
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=040a
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=040b
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=040c
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=040d
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=090a
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=090b
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=090c
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=090d
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=0409506f9a09
E/WifiStateMachine(  941):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:51 bcn=0
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=7f506f9a09
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=0801
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=040e
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=06
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=0a07
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=0a11
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556c1e6100 match=0a1a
D/wpa_supplicant( 1325): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1325):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325):   * freq=2412
D/wpa_supplicant( 1325):   * freq_hint=2412
D/wpa_supplicant( 1325):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1325):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1325):   * WPA Versions 0x2
D/wpa_supplicant( 1325):   * pairwise=0xfac04
D/wpa_supplicant( 1325):   * group=0xfac04
D/wpa_supplicant( 1325):   * akm=0xfac02
D/wpa_supplicant( 1325):   * Auth Type 0
D/wpa_supplicant( 1325): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x556c1e6c3a
E/WifiStateMachine(  941):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:51 bcn=0
D/WifiStateMachine(  941): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  941): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1325): nl80211: Connect request send successfully
D/wpa_supplicant( 1325): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1325): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1325): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1325): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1325): wlan0: Control interface command 'LIST_DONGLES'
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  941): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  941): [1,454,422,567,870 ms] noteScanEnd no scan source
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1325): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  941): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@a90c1ce sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  941): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  941): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  941): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  941): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  941):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  941): 01ABC c2:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  941): Gonzos 38:f8:89:11:e9:11 rssi=-80 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  941): ageScanResultsOut delay 40000 size 4 now 1454422567873
E/WifiAutoJoinController (  941): newSupplicantResults size=4 known=1 true
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1325): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  941): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  941): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  941): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  941): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  941): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  941):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131213
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106926
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106926
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106926
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106926
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147462
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=106927  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  941): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  941): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  941): setDetailed state send new extra info0x
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  941): NetworkAgent == null
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/WifiStateMachine(  941): processMsg: ConnectModeState
,E/WifiStateMachine(  941):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=106937  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  941): handleMessage: X
,E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0,
,I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0,
,D/wpa_supplicant( 1325): Wireless event: cmd=0x8c02 len=271
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1325): WEXT: Custom wireless event: 'BEACONIEs='
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/Tethering(  941): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1325): Wireless event: cmd=0x8c02 len=46
I/wpa_supplicant( 1325): WEXT: Custom wireless event: 'BEACONIEs='
D/Tethering(  941): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1325): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1325): nl80211: Connect event
D/wpa_supplicant( 1325): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1325): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1325): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1325): wlan0: Association info event
D/wpa_supplicant( 1325): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): wlan0: freq=2412 MHz
D/wpa_supplicant( 1325): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1325): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1325): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1325): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1325): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1325): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1325): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1325): TDLS: Remove peers on association
D/wpa_supplicant( 1325): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1325): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1325): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1325): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1325): EAPOL: enable timer tick
D/wpa_supplicant( 1325): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1325): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1325): wlan0: Cancelling scan request
I/wpa_supplicant( 1325): htc_wext_set_keepalive +
I/wpa_supplicant( 1325): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/Tethering(  941): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1325): getPrivFuncNum +	
D/Tethering(  941): interfaceStatusChanged wlan0, false
D/UsbDeviceM,anager(  941): [USBNET] bCheckSuppFunc: cdc_network
I/wpa_supplicant( 1325): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1325): htc_wext_set_keepalive fnum = 0x8bf6
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
I/wpa_supplicant( 1325): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1325): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1325): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1325): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1325): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/PMS     (  941): acquireWL(fa1f929): PARTIAL_WAKE_LOCK  NetworkStats 0x1 941 1000 null
D/wpa_supplicant( 1325): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1325):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1325):   key_nonce - hexdump(len=32): d6 d1 75 4d 0b f5 14 b4 4b 84 21 3e 16 21 7a df ef a4 5e 87 53 28 f7 0c cc 53 6b c8 9d 3c 1c 61
D/wpa_supplicant( 1325):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1325): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1325): RSN: msg 1/4 key data - hexdump(len=0):
D/Tethering(  941): interfaceLinkStateChanged wlan0, false
D/Tethering(  941): interfaceStatusChanged wlan0, false
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  941): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  941): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  941): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=41 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  941): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  941): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  941): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  941): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  941): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  941): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  941): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  941): handleAssociatedWithEvent. bLFR =false
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  941): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1325): WPA: Renewed SNonce - hexdump(len=32): 4f 34 76 a5 27 fc c9 22 64 41 ca 9f b8 50 b9 8d 42 7a 91 6f 27 a5 d2 bf 81 e0 58 9b 55 6e 97 84
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1325): WPA: Nonce1 - hexdump(len=32): 4f 34 76 a5 27 fc c9 22 64 41 ca 9f b8 50 b9 8d 42 7a 91 6f 27 a5 d2 bf 81 e0 58 9b 55 6e 97 84
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1325): WPA: Nonce2 - hexdump(len=32): d6 d1 75 4d 0b f5 14 b4 4b 84 21 3e 16 21 7a df ef a4 5e 87 53 28 f7 0c cc 53 6b c8 9d 3c 1c 61
D/wpa_supplicant( 1325): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1325): WPA: PTK - hexdump(len=48): [REMOVED]
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  941): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1325): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1325): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1325): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): WPA: Derived Key MIC - hexdump(len=16): cb 22 1b a1 c6 e4 1d 6b d1 41 c4 b4 bb cb b2 96
E/WifiStateMachine(  941): handleMessage: E msg.what=147462
E/WifiStateMachine(  941): processMsg: DisconnectedState
D/Tethering(  941): interfaceLinkStateChanged wlan0, true
D/Tethering(  941): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  941):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=107024  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  941): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  941): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  941): processMsg: ConnectModeState
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  941): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  941):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=107024  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147500
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  941): Enter handleAssociatedWithEvent
D/WifiStateMachine(  941): Associated
D/WifiStateMachine(  941): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  941): Exit handleAssociatedWithEvent
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147462
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=107026  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  941): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  941): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  941): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  941): NetworkAgent == null
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
V/Tethering(  941): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1325): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1325): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/PMS     (  941): releaseWL(fa1f929): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1325): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1325):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1325):   key_nonce - hexdump(len=32): d6 d1 75 4d 0b f5 14 b4 4b 84 21 3e 16 21 7a df ef a4 5e 87 53 28 f7 0c cc 53 6b c8 9d 3c 1c 61
D/wpa_supplicant( 1325):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_rsc - hexdump(len=8): 93 24 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_mic - hexdump(len=16): dd 1b e8 41 c6 76 a3 eb 55 74 93 20 53 48 8d ef
D/wpa_supplicant( 1325): RSN: encrypted key data - hexdump(len=56): f9 aa 96 8e 2f 16 2b aa af 72 e6 96 85 9d 49 33 f8 8e 76 d9 92 71 ff ea 6c 1f 58 c4 1e b0 0a 05 ...
D/wpa_supplicant( 1325): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1325): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1325): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1325): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 cb bd ...
D/wpa_supplicant( 1325): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1325): wlan0: WPA: Sending EAPOL-Key 4/4
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1325): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): WPA: Derived Key MIC - hexdump(len=16): de 99 3d 02 82 c8 b3 2f 8d b5 c9 9c 85 9d 2e 10
D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
D/wpa_supplicant( 1325): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x556c1e7390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1325): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1325):    addr=c0:ff:d4:d3:aa:48
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=1
V/NetworkPolicy(  941): updateNotificationsLocked()
D/wpa_supplicant( 1325): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1325): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1325): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1325): WPA: RSC - hexdump(len=6): 93 24 00 00 00 00
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x555e6efe68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1325): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): nl80211: KEY_SEQ - hexdump(len=6): 93 24 00 00 00 00
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1325):    broadcast key
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 1325): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1325): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1325): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1325): wlan0: Radio work 'connect'@0x556c1c7860 done in 0.118000 seconds
I/wpa_supplicant( 1325): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1325): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  941): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1325): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  941): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  941): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=44 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiMonitor(  941): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiMonitor(  941): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=45 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/ConnectivityService(  941): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  941): processMsg: ConnectModeState
D/ConnectivityService(  941): Got NetworkAgent Messenger
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
D/ConnectivityService(  941): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/ConnectivityService(  941): NetworkAgent connected
E/WifiMonitor(  941): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1325): set send_ind_to_ndc = 0
I/wpa_supplicant( 1325): htc_wext_set_TX_TRACKING (1)+
D/WifiMonitor(  941): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=47 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  941): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1325): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1325): EAPOL: External notification - EAP success=1
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1325): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1325): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1325): EAP: EAP entering state DISABLED
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1325): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1325): EAPOL: Supplicant port status: Authorized
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1325): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  941): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  941): interfaceLinkStateChanged wlan0, true
D/Tethering(  941): interfaceStatusChanged wlan0, true
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1325): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1325): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WifiMonitor(  941): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  941):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=107033  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering(  941): sendTetherStateChangedBroadcast 1, 0, 0
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiStateMachine(  941): handleMessage: X
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  941): handleMessage: E msg.what=147462
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiStateMachine(  941):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=107037  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  941): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  941): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=107038  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147459
E/WifiStateMachine(  941): processMsg: DisconnectedState
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  941):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107039
E/WifiStateMachine(  941): processMsg: ConnectModeState
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/UsbnetService(  941): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
E/WifiStateMachine(  941):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107040
E/WifiStateMachine(  941): Network connection established
D/WifiStateMachine(  941): fetchFrequency(), freq = 2412
E/WifiStateMachine(  941): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  941): NetworkAgent == null
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 20
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  941): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  941): handleMessage: new destination call exit/enter
E/WifiStateMachine(  941): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  941): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  941): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  941): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  941): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  941): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  941): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  941): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  941): NetworkAgent == null
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 22
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  941): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  941): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  941): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1325): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1325): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1325): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1325): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1325): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  941): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  941): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  941): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  941): ObtainingIpAddress "NG700" nid=0
W/ContextImpl( 5961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiConfigStore(  941): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1325): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1325): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1325): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1325): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1325): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  941): Start Dhcp Watchdog 2
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147462
E/WifiStateMachine(  941): processMsg: ObtainingIpState
D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
D/TetherSettings( 5961): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
E/WifiStateMachine(  941):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=107061  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  941): processMsg: L2ConnectedState
D/        ( 5961): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5961): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5961): Cust_ConnectToPC   : spcsc>false
D/        ( 5961): Cust_ConnectToPC   : IPT>true
D/        ( 5961): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5961): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5961): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5961): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5961): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  941):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=107062  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  941): processMsg: ConnectModeState
D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  941):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=107062  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  941): handleMessage: E msg.what=131101
E/WifiStateMachine(  941): processMsg: ObtainingIpState
E/WifiStateMachine(  941):  ObtainingIpState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
I/SmartNS_Utility( 5961): setISNotification
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  941): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  941): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131155
E/WifiStateMachine(  941): processMsg: ObtainingIpState
D/SmartNS_Utility( 5961): usb_cable_connect = 1
E/WifiStateMachine(  941):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1027] from screen [on:0 period:-1571345329] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
D/SmartNS_Utility( 5961): usb_denied = 0
I/SmartNS_PSService( 5961): usb notificaiton:true
E/WifiStateMachine(  941):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1571345328] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  941):  get link layer stats 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1325): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  941): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  941): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=70.00 txretriesrate=0.00 rxrate=114.00 userTriggerdPenalty0
E/WifiStateMachine(  941):  good link -> stuck count =0
E/WifiStateMachine(  941):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  941):  isHighRSSI       ---> score=65
E/WifiStateMachine(  941): calculateWifiScore() report new score 60
D/WifiWatchdogStateMachine(  941): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131212
D/ConnectivityService(  941): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  941): processMsg: ObtainingIpState
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  941):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  941): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
D/SmartNS_Utility( 5961): usb_cable_connect = 1
E/WifiStateMachine(  941):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiStateMachine(  941): handlePreDhcpSetup Held wake lock during DHCP
D/SmartNS_Utility( 5961): usb_denied = 0
E/WifiStateMachine(  941): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
I/SmartNS_PSService( 5961): usb notificaiton:true
D/PMS     (  941): acquireWL(1529c74): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 941 1000 null
E/WifiStateMachine(  941): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=196612
E/WifiStateMachine(  941): processMsg: ObtainingIpState
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiStateMachine(  941): handlePreDhcpSetup mBluetoothConnectionActive: false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  941):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=140,0,0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=140,0,0
D/WifiDataStallTracker(  941): setDhcpActive: true
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  941): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  941): do suspend false
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1325): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1325): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1325): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
I/RemoteViews( 1222): reapply : com.android.settings 1 36
E/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  941): Unexpected BatchedScanResults :null
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  941): noteBatchedScanstop()
E/WifiStateMachine(  941): handleMessage: X
D/SmartNS_NSReceiver( 5961): Tethered state change:false isNSOpening:false
D/WifiP2pService(  941): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b1e5bfe target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
D/WifiP2pService(  941): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b1e5bfe target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WISPrService( 5961): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5961): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/RemoteViews( 1222): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
,E/dhcpcd  ( 6623): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6623): version 5.5.6 starting
E/dhcpcd  ( 6623): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6623): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6623): autoip env[11]:autoip=DISABLE
,I/dhcpcd  ( 6623): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6623): wlan0: sending REQUEST (xid 0xe192bdc9), next in 0.89 seconds
,I/Prism.ItemManager( 1618): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1618): loadItems() com.htc.launcher.pageview.WidgetManager@3583123 +
I/Prism.WidgetManager( 1618): onLoadItems() +
,W/ResourcesManager( 1618): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 1618): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/ConnectivityService(  941): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  941): [AlarmQueuing] connectivity wifi: false
,D/htcCheckinService(  941): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  941): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/GpsLocationProvider(  941): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  941): acquireWL(3190259d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 941 1000 null,
,D/GpsLocationProvider(  941): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  941): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ConnectivityHelper( 1618): [onReceive] WIFI(1): DISCONNECTED
,W/asset   ( 1618): Copying FileAsset 0x55a655cae0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/ActivityManager(  941): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6632 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  941): No APN found to select.
,D/PMS     (  941): releaseWL(3190259d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6551): [29d.1.]  listen tmrbb8
,D/wpa_supplicant( 1325): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1325): EAPOL: disable timer tick
,D/MdScDataSum( 6551): [29d.1.] summary 118:p1 ignore
,E/Prism.WidgetManager( 1618): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1618): onLoadItems() -
I/Prism.ItemManager( 1618): loadItems() com.htc.launcher.pageview.WidgetManager@3583123 -,
,D/libc    (  941): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/ConnectivityService(  941): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  941): handleMessage: E msg.what=131212
E/WifiStateMachine(  941): processMsg: ObtainingIpState
E/WifiStateMachine(  941):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  941): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  941): handleMessage: X,
,I/MusicStore( 6632): Database version: 120,
,D/VoldConnector(  941): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  941): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  941): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 6632): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6632): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6632): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/PhoneApp( 1556): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1556): -- N1 =0
,D/PhoneApp( 1556): -- N2 =0
,D/PhoneApp( 1556): -- N3 =0
,W/ActivityThread( 6632): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6632): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@338b9535: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6632): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6632): GMSCore installation verified
,I/ConfigStore( 6632): Config Database version: 1,
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6632, uid=10159, userID:0,
,I/dhcpcd  ( 6623): wlan0: sending REQUEST (xid 0xe192bdc9), next in 2.64 seconds,
,D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
,D/MediaRouterService(  941): Client com.google.android.music (pid 6632): Registered
,D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0,
D/WifiDisplayAdapter(  941):     IP Address: }
,I/MediaRouter( 6632): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/dhcpcd  ( 6623): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,V/MusicLeanback( 6632): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  941): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6667 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  941): acquireWL(3b1b3d79): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{10076}
,V/AlarmManager(  941): sending alarm PendingIntent{36807a6c: PendingIntentRecord{35893835 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454422569373, Int=60000
D/PMS     (  941): releaseWL(3b1b3d79): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6632, uid=10159, userID:0
,D/AutoSetting( 1514): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/dhcpcd  ( 6623): wlan0: leased 192.168.1.130 for 86400 seconds
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
I/dhcpcd  ( 6623): autoip env[11]:autoip=DISABLE
,E/WifiStateMachine(  941): handleMessage: E msg.what=131212
E/WifiStateMachine(  941): processMsg: ObtainingIpState
,E/WifiStateMachine(  941):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  941): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  941): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  941): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  941): handleMessage: X
,D/MobileConnectivityChangeReceiver( 6394): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 6394): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1514): Util - no network available!
,D/SMSBackup( 6667): SMSBackupAgentService started
,D/SMSBackup( 6667): Checking restore status
D/SMSBackup( 6667): Restore complete
D/SMSBackup( 6667): cancelCheckAlarm
I/GHttpClientFactory( 6632): Using our fixed implementation of GMSCore's GoogleHttpClient
D/AutoSetting( 1514): service - onCreate()
D/SMSBackup( 6667): SMSBackupAgentService completed: completed in 0.0 seconds
,I/GoogleURLConnFactory( 6632): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate,
D/LocationManagerService(  941): request 3a3814bc passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
I/ActivityManager(  941): Killing 6263:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  941): killProcessQuiet, pid=6263
D/LocationManagerService(  941): provider request: passive ProviderRequest[ON interval=0]
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/AutoSetting( 1514): service - mHandler: cancel location update
D/AutoSetting( 1514): service -           changes count: 0
,I/ActivityManager(  941): Recipient 6263,
,I/dhcpcd  ( 6623): bind_interface: daemonise
,I/iu.Environment( 4446): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*,
I/iu.UploadsManager( 4446): num queued entries: 0
,I/iu.UploadsManager( 4446): num updated entries: 0,
,D/ChimeraCfgMgr( 4446): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 4446): NEXT; no task
,I/Babel   ( 5787): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  941): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6716 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  941): killProcessQuiet, pid=6027
I/ActivityManager(  941): Killing 6027:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    (  941): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  941): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  941): handleMessage: E msg.what=196613
E/WifiStateMachine(  941): processMsg: ObtainingIpState
E/WifiStateMachine(  941):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine(  941): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1325): Power_Mode_Type mode = 0
I/wpa_supplicant( 1325): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  941): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  941): setDhcpActive: false
D/WifiP2pService(  941): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  941): handlePostDhcpSetup release wake lock during DHCP
D/PMS     (  941): releaseWL(1529c74): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/WifiStateMachine(  941): WifiStateMachine DHCP successful
E/WifiStateMachine(  941): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  941): link address 192.168.1.130/24
,E/WifiStateMachine(  941): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  941): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  941): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  941): gateway: /192.168.1.1
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1325): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  941): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131210
E/WifiStateMachine(  941): processMsg: ObtainingIpState
E/WifiStateMachine(  941):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1325): environment dirty rate=0 [4][0][0]
,E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
,I/ActivityManager(  941): Recipient 6027
,E/WifiConfigStore(  941): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK,
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1325): wlan0: Control interface command 'BLACKLIST clear',
D/ConnectivityService(  941): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/wpa_supplicant( 1325): wlan0: BLACKLIST CLEAR 
D/ConnectivityService(  941): Adding iface wlan0 to network 101
D/WifiMonitor(  941): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
V/NetworkPolicy(  941): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=49 dispatchEvent: BLACKLIST CLEAR 
V/NetworkPolicy(  941): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  941): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  941): NetworkAgent != null
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  941): transitionTo: destState=ConnectedState
E/WifiStateMachine(  941): handleMessage: new destination call exit/enter
E/WifiStateMachine(  941): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  941): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  941): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  941): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  941): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  941): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  941): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  941): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL true Token 23
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/HtcWifiWanDetect(  941): WAN detection
D/HtcWifiWanDetect(  941): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  941):  packet count Tx=142 Rx=230
E/WifiTrafficPoller(  941): notifying of data activity 3
E/WifiDataStallTracker(  941): ENABLE_DATA_MONITOR_POLL true Token 2
D/WifiWatchdogStateMachine(  941): RSSI current: 3 new: -58, 3
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL true Token 24
E/WifiTrafficPoller(  941):  packet count Tx=142 Rx=230
E/WifiTrafficPoller(  941): notifying of data activity 0
D/WifiDataStallTracker(  941): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  941): updateDataStallInfo: NONE
D/WifiDataStallTracker(  941): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/WISPrService( 5961): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  941): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  941): Adding Route [fe80::/64 -> :: wlan0] to network 101
,E/WifiStateMachine(  941): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/libc    (  423): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
E/WifiStateMachine(  941): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131131
E/WifiStateMachine(  941): processMsg: ConnectedState
D/ConnectivityService(  941): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,E/WifiStateMachine(  941):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1,
D/WIFI_ICON( 1222): WifiActivity: 3
E/WifiStateMachine(  941): processMsg: L2ConnectedState
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  941):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WIFI_ICON( 1222): WifiActivity: 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  941):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/libc    (  423): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  941): handleMessage: X
,D/WISPrService( 5961): >>>>>WISPrService start isConnected = true<<<<<
,D/ConnectivityService(  941): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  423): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  941): Setting Dns servers for network 101 to [/192.168.1.1]
,D/libc    (  941): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  423): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/Nat464Xlat(  941): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): Connected
D/ConnectivityService(  941): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  941): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): Validated
D/ConnectivityService(  941): rematching NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  941): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  941): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  941):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  941):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  941):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  941): currentScore = 0, newScore = 20
,D/usbnet  (  941): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  941):    accepting network in place of null
D/WIFI    (  941): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  941): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/CSLegacyTypeTracker(  941): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  941): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  941): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  941): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  941): sendGeneralBroadcastDelayed, restrictEnable=false
D/Tethering(  941): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  941): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  941): acquireWL(833375d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 941 1000 null
V/NetworkPolicy(  941): ensureActiveMobilePolicyLocked()
D/ConnectivityService(  941): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  941): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): Validated
D/ConnectivityService(  941):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkPolicy(  941): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/ConnectivityService(  941): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
V/NetworkPolicy(  941): updateIfacesLocked()
D/ConnectivityService(  941): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  941): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  941):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  941):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  941): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  941): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  941):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941):  send,ing notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/ConnectivityService(  941): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  941): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  941): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  941):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  941): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  941): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  941): Validated NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  941): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  941):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  941):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  941): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  941):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  941): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  941): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
V/NetworkPolicy(  941): updateNotificationsLocked()
D/ConnectivityService(  941):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  941): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/NetworkManagementService(  941): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/PMS     (  941): releaseWL(833375d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1222): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
,I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1222): dataConnected: false/false
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
V/NetworkPolicy(  941): updateNotificationsLocked()
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/VoldConnector(  941): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6716): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  941): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
W/ContextImpl( 6716): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,I/GAv4    ( 6716): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6716):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6716):   adb logcat -s GAv4
,D/VoldConnector(  941): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6716): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 6716): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/VoldConnector(  941): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6716): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6716): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6716): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6716): [apache-http] Connection GC has been deprecated!
,W/global  ( 6716): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6716): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6716): Time to load native libraries: 16 ms (timestamps 9299-9315),
,I/LibraryLoader( 6716): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6716): Binding Chromium to main looper Looper (main, tid 1) {2a09e26a},
I/LibraryLoader( 6716): Expected native library version number "",actual native library version number ""
,I/chromium( 6716): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6716): Initializing chromium process, singleProcess=true
,W/art     ( 6716): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6716): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6716): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6716): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6716): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6716): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6716): OpenGL ES Shader Compiler Version: E031.25.03.01,
I/Adreno-EGL( 6716): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6716): Local Branch: 
I/Adreno-EGL( 6716): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6716): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6716):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6716): Requires BLUETOOTH permission,
,I/NSApplication( 6716): Starting up...
,I/ActivityManager(  941): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6779 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  941): killProcessQuiet, pid=6295
I/ActivityManager(  941): Killing 6295:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  441): Explicit concurrent mark sweep GC freed 8643(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 25.431ms
,I/art     (  441): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 128us total 15.755ms
,I/art     (  441): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 126us total 15.128ms
,I/ActivityManager(  941): Recipient 6295,
,D/Process (  941): killProcessQuiet, pid=5701,
I/ActivityManager(  941): Killing 5701:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/WifiStateMachine(  941): handleMessage: E msg.what=131168,
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): handleMessage: X
,I/ActivityManager(  941): Recipient 5701
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 25 num clients 8,
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 25 num clients 8
E/WifiTrafficPoller(  941):  packet count Tx=143 Rx=231
D/WIFI_ICON( 1222): WifiActivity: 3
E/WifiTrafficPoller(  941): notifying of data activity 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  941): releaseWL(3d87bbcc): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  941): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  941): handleMessage: E msg.what=131155,
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=70.0, 0.0, 0.0  rx=114.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1571342323] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=70.0, 0.0, 0.0  rx=114.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1571342321] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  941):  get link layer stats 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1325): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiStateMachine(  941): BroadcastRSSIForIMS, newrssi =-58 , oldRssi= -200
,E/WifiConfigStore(  941): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  941): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=36.50 txretriesrate=0.00 rxrate=58.50 userTriggerdPenalty0
E/WifiStateMachine(  941):  good link -> stuck count =0
E/WifiStateMachine(  941):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  941):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  941): RSSI current: 3 new: -58, 3
D/WifiWatchdogStateMachine(  941): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  941): handleMessage: X
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 6443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6443): 
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 25 num clients 8
D/WIFI_ICON( 1222): WifiActivity: 2
E/WifiTrafficPoller(  941):  packet count Tx=144 Rx=231
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
E/WifiTrafficPoller(  941): notifying of data activity 2
,I/jxcore-log( 6443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6443): 
,I/jxcore-log( 6443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6443): 
,I/jxcore-log( 6443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 6443): 
,I/jxcore-log( 6443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6443): 
,D/Process (  941): killProcessQuiet, pid=5400
I/ActivityManager(  941): Killing 5400:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 5400
,D/Process (  941): killProcessQuiet, pid=6350
I/ActivityManager(  941): Killing 6350:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6350
,D/libc    (  941): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
,D/libc    (  941): [NET] android_getaddrinfofornet-, err=8
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  941): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  941): [NET] android_getaddrinfo_proxy+
D/libc    (  941): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  423): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  423): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 25 num clients 8,
E/WifiTrafficPoller(  941):  packet count Tx=145 Rx=231
,D/ConnectivityService(  941): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
I/AlarmManager(  941): [AlarmQueuing] connectivity wifi: true
D/libc    (  423): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  941): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  941): [NET] android_getaddrinfo_proxy-, success
D/GpsLocationProvider(  941): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/htcCheckinService(  941): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/PMS     (  941): acquireWL(6878b39): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 941 1000 null
D/htcCheckinService(  941): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/ConnectivityHelper( 1618): [onReceive] WIFI(1): CONNECTED
,D/PMS     (  941): acquireWL(17467adf): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 941 1000 null
,I/NetworkMonitor( 6632): type=WIFI subType= reason=null isConnected=true
,D/PMS     (  941): releaseWL(17467adf): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MdScPhnSt( 6551): [2d3.1.]  listen tmrbb8,
,V/MusicLeanback( 6632): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AutoSetting( 1514): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6394): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 6394): onReceive CONNECTIVITY_CHANGE networkType=1
,D/MdScDataSum( 6551): [2d3.1.] summary 118:p1 ignore
,D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1514): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1514): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1514): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1514): service - handleMessage() setting current location null
,D/PMS     (  941): acquireWL(27439618): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,D/GpsLocationProvider(  941): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  941): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true,
,D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1917): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1917): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1917): [NET] android_getaddrinfo_proxy+
D/libc    ( 1917): [NET] android_getaddrinfo_proxy get netid:0
I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4446, uid=10024, userID:0
D/libc    (  423): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  423): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  423): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1917): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1917): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1917): [NET] android_getaddrinfofornet-, err=8
,I/art     (  941): Explicit concurrent mark sweep GC freed 54233(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.613ms total 142.503ms
E/GpsLocationProvider(  941): No APN found to select.
D/PMS     (  941): releaseWL(6878b39): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/iu.Environment( 4446): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
I/iu.UploadsManager( 4446): num queued entries: 0
,I/iu.UploadsManager( 4446): num updated entries: 0
,I/iu.SyncManager( 4446): NEXT; no task
,D/ChimeraCfgMgr( 4446): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4446): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc    ( 5787): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5787): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5787): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5787): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5787): [NET] android_getaddrinfo_proxy+
D/libc    ( 5787): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  423): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  423): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  423): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5787): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4446): [AccountUtils] Account not ready
W/Kids    ( 4446): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4446): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4446): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4446): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4446): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4446): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 1 40
,D/PMS     (  941): acquireWL(154af265): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1917): Connected
,D/PMS     (  941): releaseWL(27439618): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  941): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
D/PMS     (  941): acquireWL(5e22b3a): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{3b1cfcb2: PendingIntentRecord{24020403 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454422570074, Int=20000
E/WifiStateMachine(  941): handleMessage: E msg.what=131143
D/PMS     (  941): releaseWL(5e22b3a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  941): processMsg: ConnectedState
,E/WifiStateMachine(  941):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:51 rssi=-58 f=2412 sc=60 link=72 tx=36.5, 0.0, 0.0  rx=58.5 list=2412 [on:0 tx:0 rx:0 period:2225] from screen [on:0 period:-1571340089]
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:51 rssi=-58 f=2412 sc=60 link=72 tx=36.5, 0.0, 0.0  rx=58.5 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1571340088]
E/WifiStateMachine(  941): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=36.50 rxSuccessRate=58.50 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-58
E/WifiStateMachine(  941): WifiStateMachine CMD_START_SCAN with age=74904 interval=40000 maxinterval=300000
,E/WifiStateMachine(  941): WifiStateMachine CMD_START_SCAN try full band scan age=74904 interval=40000 maxinterval=300000
E/WifiStateMachine(  941): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  941): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  941): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
,E/WifiConfigStore(  941): has c0:ff:d4:d3:aa:48 freq=2412 age=2230 ?=true
E/WifiStateMachine(  941): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1325): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1325): wpa_supplicant_scan enter
D/wpa_supplicant( 1325): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1325): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1325): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1325): WPS:  * Request Type
D/wpa_supplicant( 1325): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1325): WPS:  * UUID-E
D/PMS     (  941): releaseWL(154af265): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1325): WPS:  * Primary Device Type
D/wpa_supplicant( 1325): WPS:  * RF Bands (3)
D/wpa_supplicant( 1325): WPS:  * Association State
D/wpa_supplicant( 1325): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1325): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1325): WPS:  * Manufacturer
D/wpa_supplicant( 1325): WPS:  * Model Name
D/wpa_supplicant( 1325): WPS:  * Model Number
D/wpa_supplicant( 1325): WPS:  * Device Name
D/wpa_supplicant( 1325): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1325): P2P: * P2P IE header
D/wpa_supplicant( 1325): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1325): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1325): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1325): wlan0: Add radio work 'scan'@0x556c1c7860
D/wpa_supplicant( 1325): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1325): wlan0: Starting radio work 'scan'@0x556c1c7860 after 0.000028 second wait
,D/PMS     (  941): acquireWL(135443eb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1325): wlan0: nl80211: scan request
D/wpa_supplicant( 1325): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1325): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1325): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1325): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1325): wlan0: Own scan request started a scan in 0.000062 seconds
I/wpa_supplicant( 1325): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  941): [1,454,422,573,258 ms] noteScanstart no scan source
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  941): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  941): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  941): handleMessage: X
,D/GCM     ( 1917): Message class com.google.f.a.a.p
,D/PMS     (  941): releaseWL(135443eb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/Babel   ( 5787): connection state changed from DISCONNECTED to CONNECTED,
,D/wpa_supplicant( 1325): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1325): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1325): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1325): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1325): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1325): wlan0: Scan completed in 0.061793 seconds
D/wpa_supplicant( 1325): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1325): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1325): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1325): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1325): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1325): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1325): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 1325): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1325): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1325): wlan0: Scan-only results received
D/wpa_supplicant( 1325): wlan0: Radio work 'scan'@0x556c1c7860 done in 0.062512 seconds
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  941): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  941): handleMessage: E msg.what=147461
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  941): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1325): wlan0: Control interface command 'LIST_DONGLES'
,W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  941): [1,454,422,573,323 ms] noteScanEnd no scan source
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1325): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  941): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@16590693 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  941): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  941): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  941): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  941): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  941):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  941): 01ABC c2:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  941): Gonzos 38:f8:89:11:e9:11 rssi=-80 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  941): ageScanResultsOut delay 40000 size 4 now 1454422573325
E/WifiAutoJoinController (  941): newSupplicantResults size=4 known=1 true
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1325): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  941): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  941): ssid=NG700
E/WifiAutoJoinController (  941): id=0
E/WifiAutoJoinController (  941): mode=station
E/WifiAutoJoinController (  941): pairwise_cipher=CCMP
E/WifiAutoJoinController (  941): group_cipher=CCMP
E/WifiAutoJoinController (  941): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  941): wpa_state=COMPLETED
E/WifiAutoJoinController (  941): ip_address=192.168.1.130
E/WifiAutoJoinController (  941): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  941): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  941): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  941): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  941): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-58,-127) num=(1,0)
E/WifiAutoJoinController (  941): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
,E/WifiAutoJoinController (  941): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-58 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  941): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  941): Done attemptAutoJoin status=0
E/WifiConfigStore(  941):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  941): handleMessage: X
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL true Token 25 num clients 8
,E/WifiTrafficPoller(  941):  packet count Tx=160 Rx=246
E/WifiTrafficPoller(  941): notifying of data activity 3
D/WIFI_ICON( 1222): WifiActivity: 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiStateMachine(  941): handleMessage: E msg.what=131155,
E/WifiStateMachine(  941): processMsg: ConnectedState
,E/WifiStateMachine(  941):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=36.5, 0.0, 0.0  rx=58.5 bcn=0 [on:0 tx:0 rx:0 period:772] from screen [on:0 period:-1571339314] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
,E/WifiStateMachine(  941):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=36.5, 0.0, 0.0  rx=58.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1571339313] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  941):  get link layer stats 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1325): environment dirty rate=0 [17][0][0]
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  941): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  941): RSSI current: 3 new: -58, 3
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  941): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=26.75 txretriesrate=0.00 rxrate=36.75 userTriggerdPenalty0
E/WifiStateMachine(  941):  good link -> stuck count =0
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  941):  badRSSI count0 lowRSSI count0 --> score 60
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  941):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  941): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  941): handleMessage: X
,I/PMS     (  941): Going to sleep due to screen timeout (uid 1000)...
,I/SensorManager(  941): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@5e18f59
W/SensorService(  941): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  941): disable: get sensor name = Accelerometer Sensor
W/SensorService(  941): pid=941, uid=1000
W/SensorService(  941): Active sensors: size = 4
W/SensorService(  941): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  941): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  941): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  941): Significant Motion (handle=0x0000000d, connections=1)
W/PMN     (  941): goingToSleep
W/SensorService(  941): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@5e18f59, eanble = 0, strlen(mName) = 90
W/SensorService(  941): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  941): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@342e1ba0
W/SensorService(  941): Listener[1] = com.htc.smartdim.sensor_eye@3735dabd
W/SensorService(  941): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/PMS     (  941): mWirelessDisplayManager is null
,W/PMS     (  941): mWirelessDisplayManager is still null
D/PMS     (  941): acquireWL(1a54b548): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 941 1000 null
,W/PMN     (  941): goingToSleep done
,D/AlarmManager(  941): ACTION_SCREEN_ON,
I/AlarmManager(  941): [AlarmQueuing] recover blocked alarms,
,I/AlarmManager(  941): [AlarmQueuing] done recovering,
W/HtcLockScreen( 1222): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
I/AlarmManager(  941): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  941): [AlarmQueuing] done EPS screen off alarm recovering
,W/HtcSystemUPManager(  941): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/PMS     (  941): Sleeping (uid 1000)...
,D/PMS     (  941): releaseWL(1a54b548): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/XAN-DPS (  941): prepareColorFade 1
,E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL true Token 25
E/WifiTrafficPoller(  941):  packet count Tx=160 Rx=246
E/WifiTrafficPoller(  941): notifying of data activity 0
,E/WifiDataStallTracker(  941): ENABLE_DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  941): updateDataStallInfo: mDataStallTxRxSum={txSum=133 rxSum=118} preTxRxSum={txSum=133 rxSum=118}
D/WifiDataStallTracker(  941): updateDataStallInfo: NONE
D/WifiDataStallTracker(  941): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  941): handleMessage: E msg.what=131167
E/WifiStateMachine(  941): processMsg: ConnectedState
,E/WifiStateMachine(  941):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
,E/WifiStateMachine(  941):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
,E/WifiStateMachine(  941):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  941):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1325): SET_SCREEN_ON:On
I/wpa_supplicant( 1325): htc_wext_set_keepalive +
,I/wpa_supplicant( 1325): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1325): getPrivFuncNum +	
I/wpa_supplicant( 1325): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1325): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1325): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1325): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1325): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  941): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
D/WifiStateMachine(  941): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  941): handleScreenStateChanged Exit: true
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131154
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
,E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1325): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiStateMachine(  941): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
E/WifiConfigStore(  941): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131127
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131129
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
,D/wpa_supplicant( 1325): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1325): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  941): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=52 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  941): handleMessage: X
,I/Adreno-EGL(  941): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  941): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  941): Build Date: 03/09/15 Mon
I/Adreno-EGL(  941): Local Branch: 
I/Adreno-EGL(  941): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  941): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  941):                  d74aa161a12b9c6fc6332151
,V/SRS_Proc(  429): ParamSet string: screen_state=on
E/audio_a2dp_hw(  429): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiWatchdogStateMachine(  941): RSSI current: 3 new: -58, 3
,D/WifiController(  941): handleMessage: E msg.what=155650
D/NetworkPolicy(  941): updateScreenOn: false
D/WifiController(  941): processMsg: DeviceActiveState
V/NetworkPolicy(  941): updateIfacesLocked()
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/NetworkManagementService(  941): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WIFI_ICON( 1222): WifiActivity: 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  941): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6829 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
D/GpsLocationProvider(  941): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/IntentController( 1222): receive(android.intent.action.SCREEN_ON,1,false),
,D/XAN-DPS (  941): prepareColorFade done
,D/PMS     (  941): acquireWL(ba3ddf4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
D/XAN-DPS (  941): setBrightness to 0
W/ContextImpl( 6829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  941): acquireWL(9fee792): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
,I/SensorManager(  941): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@342e1ba0
D/PMS     (  941): releaseWL(ba3ddf4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/SensorService(  941): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  941): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  941): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  941): Display changed displayId=0
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
W/SensorService(  941): pid=941, uid=1000
W/SensorService(  941): Active sensors: size = 3
W/SensorService(  941): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  941): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  941): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  941): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@342e1ba0, eanble = 0, strlen(mName) = 67
W/SensorService(  941): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  941): Listener[0] = com.htc.smartdim.sensor_eye@3735dabd
W/SensorService(  941): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
D/PMS     (  941): releaseWL(9fee792): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6829): MY_DEBUG = false
,D/SmartSyncUtils( 6829): isEpsOn(), nState = 0,
,D/PMS     (  941): acquireWL(1e9feade): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6829 1000 null
,D/AlarmManager(  941): ACTION_SCREEN_OFF
,I/AlarmManager(  941): [AlarmQueuing] screen off now: 
I/AlarmManager(  941): [AlarmQueuing] data connection: true
I/AlarmManager(  941): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 26
D/WifiDataStallTracker(  941): stopDataStallAlarm 
E/WifiDataStallTracker(  941): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  941): handleMessage: E msg.what=131167
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  941):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1325): SET_SCREEN_ON:Off
I/wpa_supplicant( 1325): htc_wext_set_keepalive +
I/wpa_supplicant( 1325): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1325): getPrivFuncNum +	
I/wpa_supplicant( 1325): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1325): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
I/wpa_supplicant( 1325): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1325): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1325): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  941): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
V/SRS_Proc(  429): ParamSet string: screen_state=off
E/audio_a2dp_hw(  429): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  941): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  941): handleScreenStateChanged Exit: false
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131154
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
I/SensorManager( 1222): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@34bb4024, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
E/WifiStateMachine(  941):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  941): handleMessage: X
D/WifiController(  941): handleMessage: E msg.what=155651
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
W/SensorService(  941): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  941): enable: get sensor name = hTC Gesture Motion HIDI
,D/NetworkPolicy(  941): updateScreenOn: false
V/NetworkPolicy(  941): updateIfacesLocked()
D/NetworkManagementService(  941): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/SensorService(  941): pid=1222, uid=10041
W/SensorService(  941): Active sensors: size = 4
W/SensorService(  941): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  941): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  941): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  941): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
W/SensorService(  941): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@34bb4024, eanble = 1, strlen(mName) = 57
W/SensorService(  941): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  941): Listener[0] = com.htc.smartdim.sensor_eye@3735dabd
W/SensorService(  941): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@34bb4024
W/SensorService(  941): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  941): releaseWL(1e9feade): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/DotMatrix( 1311): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  941): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/SmartDim(  941): Init customizeScreenOffDelayClass error
,D/PMS     (  941): acquireWL(3338f78c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6632 10159 null,
,D/ContactMessageStore( 1556): start background delete task...
,I/IntentController( 1222): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1556): size: 0 , 0
D/ContactMessageStore( 1556): Background delete complete
,D/PMS     (  941): acquireWL(1278738d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1786 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  941): releaseWL(1278738d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(3c8c5942): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): releaseWL(3c8c5942): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/RemoteViews( 1222): setHTCTheme(com.htc.updater,true,33751145)
D/AutoSetting( 1514): service - mHandler: cancel location update
D/AutoSetting( 1514): service -           changes count: 0
,I/RemoteViews( 1222): apply : com.htc.updater 0 9 1 36
,I/PowerUsageList:PowerUsageHelper( 6829): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6632, uid=10159, userID:0,
D/PMS     (  941): releaseWL(3338f78c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6632): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6632): Stop autocaching.
,D/WearableService( 5666): callingUid 10024, callindPid: 5666
,D/PowerUsageList:BatterySipperExt( 6829): gen(), null == sipper.uidObj, userId = 0
,W/ContextImpl( 6829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
E/GmsUtils( 6632): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,E/GmsUtils( 6632): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/PMS     (  941): Setting HAL interactive mode to false
D/SurfaceControl(  941): Excessive delay in setPowerMode(): 279ms
,D/PMS     (  941): Setting HAL interactive mode to false done
W/HtcSystemUPManager(  941): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  941): Setting HAL auto-suspend mode to true
D/PMS     (  941): Setting HAL auto-suspend mode done
I/InputManager(  941): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,D/HABCtrl (  941): TPE algorithm. remove timeout.
,D/PMS     (  941): OOBE c monitor 11
W/ContextImpl( 6829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/IntentController( 1222): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/InputMethodManagerService(  941): screenObserver, isScreenOn=false
,D/StatusBarManagerService(  941): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  941): Disable input method client, pid=6443
D/PMS     (  941): acquireWL(8efce9a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(8efce9a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/InputMethodManager( 6443): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{208fcd03 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@11cb3b05
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,D/SmartSyncUtils( 6829): isEpsOn(), nState = 0
D/HtcPowerSaver(  941): updateBatteryInfo
D/PowerUI ( 1222): closing low battery warning: level=100
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/SmartSyncUtils( 6829): isEpsOn(), nState = 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
,D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): BroadcastReceiver::onReceive-
,D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,W/ContextImpl( 6829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,E/WifiDataStallTracker(  941): DATA_MONITOR_POLL false Token 5
D/NfcService( 1572): ScreenObserver: OFF
D/NfcService( 1572): applyRouting - 0
D/PMS     (  941): acquireWL(31f477a8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1572 1027 null
W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
D/NfcService( 1572): applyRouting -2
,D/NfcService( 1572): applyRouting,
,D/NfcService( 1572): Ignore this applyRouting...
I/SensorManager(  941): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3735dabd
D/PMS     (  941): releaseWL(31f477a8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/SensorService(  941): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  941): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  941): pid=941, uid=1000
W/SensorService(  941): Active sensors: size = 3
W/SensorService(  941): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  941): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  941): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  941): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3735dabd, eanble = 0, strlen(mName) = 36
W/SensorService(  941): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  941): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@34bb4024
W/SensorService(  941): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  941): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  941): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  941): pid=941, uid=1000
W/SensorService(  941): Active sensors: size = 2
W/SensorService(  941): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  941): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  941): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3735dabd, eanble = 0, strlen(mName) = 36
,W/SensorService(  941): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  941): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@34bb4024
W/SensorService(  941): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL false Token 27 num clients 8
I/SensorManager(  941): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3735dabd
E/ActivityThread(  941): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@15c1e8b2 that was originally registered here. Are you missing a call to unregisterReceiver()?
,E/ActivityThread(  941): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@15c1e8b2 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  941): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  941): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  941): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  941): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  941): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  941): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  941): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  941): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  941): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  941): ,	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  941): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  941): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  941): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  941): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  941): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  941): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  941): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ClockController( 1222): stop clock update:screen off
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/SmartSyncUtils( 6829): getMobilePolicyEnabled, result = true,
,D/WifiService(  941): New client listening to asynchronous messages,
E/WifiTrafficPoller(  941): ADD_CLIENT: 9
,D/PowerUsageList:PowerUsageHelper( 6829): MY_DEBUG = false,
,I/ActivityManager(  941): Killing 5986:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  941): killProcessQuiet, pid=5986
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 5986
,E/WifiTrafficPoller(  941): TRAFFIC_STATS_POLL false Token 27 num clients 9,
,D/PMS     (  941): releaseWL(f37860d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,E/WifiStateMachine(  941): handleMessage: E msg.what=131155,
E/WifiStateMachine(  941): processMsg: ConnectedState,
E/WifiStateMachine(  941):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1571336301] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
,E/WifiStateMachine(  941):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1571336297] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  941): handleMessage: X
,E/WifiStateMachine(  941): handleMessage: E msg.what=131155,
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:264] from screen [on:0 period:-1571336030] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1571336027] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  941): handleMessage: X
,D/HtcUPManager( 1222): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,I/jxcore-log( 6443): Test app app.js loaded,
I/jxcore-log( 6443): 
,I/chromium( 6443): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6443): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a61d75a added. We now have 1 listener(s)
,D/BluetoothAdapter( 6443): 116017485: getState(). Returning 12
I/jxcore-log( 6443): BLE advertisement is supported
I/jxcore-log( 6443): 
,E/WifiDataStallTracker(  941): DATA_MONITOR_POLL false Token 5
,D/ContactMessageStore( 1556): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1556): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/Process (  941): killProcessQuiet, pid=5569,
I/ActivityManager(  941): Killing 5569:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 5569
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  941): acquireWL(357c52c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{10024},
V/AlarmManager(  941): sending alarm PendingIntent{296c3a66: PendingIntentRecord{2dc421a7 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143742, Int=0
,D/PMS     (  941): releaseWL(357c52c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/AutoSetting( 1514): service - handleMessage() stop self,
,D/AutoSetting( 1514): service - handleMessage() quit looper
D/AutoSetting( 1514): service - onDestroy() END
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  941): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  941): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
D/PMS     (  941): acquireWL(2ced6654): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 941 1000 null
,D/libc    (  941): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  941): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  941): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  941): [NET] android_getaddrinfo_proxy+
D/libc    (  941): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  423): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  423): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  423): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  941): [NET] android_getaddrinfo_proxy-, success
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
,D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  941): [handleDownloadXtraData] calling native_inject_xtra_data,
,E/WifiStateMachine(  941): handleMessage: E msg.what=131165,
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0,
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
D/PMS     (  941): acquireWL(15e493c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 941 1000 null
E/WifiStateMachine(  941):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/PMS     (  941): releaseWL(2ced6654): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  941): [reportHTCStatus] eventMask = 3 , status = 0,
E/WifiStateMachine(  941): processMsg: DefaultState
D/GpsLocationProvider(  941): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
E/WifiStateMachine(  941):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/PMS     (  941): releaseWL(15e493c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/WifiStateMachine(  941): handleMessage: X
D/GpsLocationProvider(  941):  [handleDownloadXtraData]inject done.
D/GpsLocationProvider(  941): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,E/WifiStateMachine(  941): handleMessage: E msg.what=131326,
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState what:131326 2 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  941): handleMessage: X
,D/PMS     (  941): acquireWL(3dd798f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(3dd798f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  941): updateBatteryInfo
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  941): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1556): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  941): acquireWL(efe303e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{2729703d: PendingIntentRecord{19059032 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=159051, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{22e19e9f: PendingIntentRecord{265f2bec android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454422627435, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{3a6fcbb5: PendingIntentRecord{34a9124a android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202384, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{1ecb85bb: PendingIntentRecord{9091ad8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190345, Int=0
,D/PMS     (  941): acquireWL(3a1e6e31): PARTIAL_WAKE_LOCK  *backup* 0x1 941 1000 null
,D/PMS     (  941): acquireWL(2f6e0916): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
,W/BackupManagerService(  941): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  941): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  941): releaseWL(3a1e6e31): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
D/PMS     (  941): releaseWL(efe303e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  941): acquireWL(15a2c297): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): releaseWL(2f6e0916): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  941): releaseWL(15a2c297): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(c53b269): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): releaseWL(c53b269): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(263524ee): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(33f56d8f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(39ec0c25): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): releaseWL(263524ee): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(e6553ab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(e6553ab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1917): Vacuum at: now=1454422663632 tag=VacuumService
,D/PMS     (  941): releaseWL(33f56d8f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  941): acquireWL(21e4ea08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1917): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1917): No account for auth token provided,
,D/PMS     (  941): releaseWL(21e4ea08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): acquireWL(37f645a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(37f645a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1917): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1917): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1917): [NET] android_getaddrinfo_proxy+
D/libc    ( 1917): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  423): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  423): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  423): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1917): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1917): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1917): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1917): No account for auth token provided,
,W/Uploader( 1917): No account for auth token provided,
,W/Uploader( 1917):  no longer exists, so no auth token.,
,W/Uploader( 1917): No account for auth token provided,
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,E/Uploader( 1917): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1917): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1917): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1917): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1917): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1917): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1917): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1917): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1917): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1917): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1917): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1917): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1917): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  941): releaseWL(39ec0c25): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(33f14895): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(33f14895): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(1a177daa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): releaseWL(1a177daa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1514): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3adf8e10
,I/ActivityManager(  941): Killing 5899:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  941): killProcessQuiet, pid=5899
,D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 5899,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  941): acquireWL(1fc67d9b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(1fc67d9b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): Checking...
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): handleMessage: E msg.what=155652
,D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  941): acquireWL(2aae538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(2aae538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  941): plugged=true pluggin=true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1325): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1325): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1325): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
,D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  941): acquireWL(35ead911): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(35ead911): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: E msg.what=155652
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  941): acquireWL(3747ca76): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
,V/AlarmManager(  941): sending alarm PendingIntent{2729703d: PendingIntentRecord{19059032 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=219051, Int=0
,D/PMS     (  941): releaseWL(3747ca76): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  941): acquireWL(3ac51ce4): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{10109},
V/AlarmManager(  941): sending alarm PendingIntent{1112f54d: PendingIntentRecord{125e1802 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454422802065, Int=0
,I/ActivityManager(  941): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6894 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  941): sending alarm PendingIntent{10ed0513: PendingIntentRecord{2c292350 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454422899082, Int=0,
D/PMS     (  941): releaseWL(3ac51ce4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10071}
,E/cutils-trace( 6916): Error opening trace file: Permission denied (13),
I/dex2oat ( 6916): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6916): dex2oat: override thread count:4
,I/dex2oat ( 6916): dex2oat took 704.338ms (threads: 4)
,I/PushClient( 6894): ApplicationMonitor {16c67913}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6894): ApplicationMonitor {16c67913}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6894): ApplicationMonitor {16c67913}: logBasicAppInfo(): VersionName:             1.2.853019,
I/PushClient( 6894): ApplicationMonitor {16c67913}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6894): ApplicationMonitor {16c67913}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6894): ApplicationMonitor {16c67913}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6894): ApplicationMonitor {16c67913}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false,
,I/PushClient( 6894): ApplicationMonitor {16c67913}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6894): ApplicationMonitor {16c67913}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/PushClient( 6894): PnsModel {12a4dc02}: update(): Update registration caused by: alarm,
,I/PushClient( 6894): PnsConfigModel {2c9a3c81}: <init>(): Use dm-client for provisioning.
,W/System.err( 6894): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6894): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6894): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6894): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  941): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6923 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6923): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6923 dbg=false s=true
,I/DeviceManagement( 6923): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6923): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6923): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6923): WorkflowService: Starting workflow service
,I/DeviceManagement( 6923): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@823d602] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6923): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6923): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6923): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6923): SessionStateController: Checking invariants...
,I/DeviceManagement( 6923): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6923): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6923): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6923): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@823d602],
,I/DeviceManagement( 6923): WorkflowService: Stopping workflow service
,I/ActivityManager(  941): Killing 6595:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  941): killProcessQuiet, pid=6595
,D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6595,
,I/PushClient( 6894): PnsModel {12a4dc02}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  941): killProcessQuiet, pid=6667,
I/ActivityManager(  941): Killing 6667:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6667
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  941): acquireWL(1558cbbd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(1558cbbd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  941): updateBatteryInfo
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): BroadcastReceiver::onReceive-
,D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X,
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  941): acquireWL(361085b2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(361085b2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  941): updateBatteryInfo
,D/PMS     (  941): runPSCheck
D/HtcPowerSaver(  941): Checking...
I/HtcPowerSaver(  941): >> updateStatus
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  941): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  941): << updateStatus
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: E msg.what=155652
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
,D/WifiController(  941): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  941): acquireWL(27715903): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
,V/AlarmManager(  941): sending alarm PendingIntent{2729703d: PendingIntentRecord{19059032 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=459051, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{2fb40080: PendingIntentRecord{9091ad8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=544536, Int=0
,D/PMS     (  941): acquireWL(acb66b9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(27715903): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  941): acquireWL(3dfd4afe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): releaseWL(acb66b9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  941): Explicit concurrent mark sweep GC freed 41890(2MB) AllocSpace objects, 6(1188KB) LOS objects, 33% free, 18MB/28MB, paused 2.170ms total 210.247ms,
,E/Ads     ( 4446): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,D/PMS     (  941): releaseWL(3dfd4afe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): acquireWL(1fb67029): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): releaseWL(1fb67029): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): acquireWL(3f906fae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): releaseWL(3f906fae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): acquireWL(211ac14f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(211ac14f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  941): plugged=true pluggin=true,
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  941): updateBatteryInfo,
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  941): runPSCheck
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: DefaultState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): handleMessage: X
D/WifiController(  941): battery changed pluggedType: 2
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1556): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1556): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1556): sku_id=118
D/ContactMessageStore( 1556): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1556): start background delete task...
,D/ContactMessageStore( 1556): size: 0 , 0
,D/ContactMessageStore( 1556): Background delete complete
,D/PMS     (  941): acquireWL(116490dc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{2729703d: PendingIntentRecord{19059032 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=579051, Int=0,
,I/ActivityManager(  941): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=6952 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
V/AlarmManager(  941): sending alarm PendingIntent{321ce5e5: PendingIntentRecord{1d311ccd com.android.vending startService}}, i=null, t=0, cnt=1, w=1454423098600, Int=0
,D/PMS     (  941): releaseWL(116490dc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6952, uid=10072, userID:0
,W/global  ( 6952): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 6952): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 6952): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6952): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 6952): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  941): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6990 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 6952): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 6952): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6952, uid=10072, userID:0,
,D/Finsky  ( 6952): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/ResourcesManager( 6990): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6990): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6952): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6952): [1] 2.run: Finished loading 1 libraries.
V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6952): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/MultiDex( 6990): VM with version 2.1.0 has multidex support
I/MultiDex( 6990): install
I/MultiDex( 6990): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6952): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 6990): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6952): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityThread( 6990): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6990): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19cdfae3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6990): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1917): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1917): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4446): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4446, uid=10024, userID:0,
D/WearableService( 5666): callingUid 10024, callindPid: 5666
,E/MDM     ( 1786): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/LocationInitializer( 4446): Restart initialization of location
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1917): Explicit concurrent mark sweep GC freed 40871(2MB) AllocSpace objects, 10(668KB) LOS objects, 47% free, 4MB/8MB, paused 913us total 69.127ms
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6952): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/Finsky  ( 6952): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,E/AndroidHttpClient( 6952): Leak found
E/AndroidHttpClient( 6952): java.lang.IllegalStateException: AndroidHttpClient created and never closed,
E/AndroidHttpClient( 6952): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 6952): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 6952): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 6952): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 6952): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 6952): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 6952): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 6952): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 6952): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 6952): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 6952): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 6952): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 6952): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 6952): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 6952): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 6952): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/Finsky  ( 6952): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  941): acquireWL(1204799c): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{10072}
V/AlarmManager(  941): sending alarm PendingIntent{339d7fa5: PendingIntentRecord{1d311ccd com.android.vending startService}}, i=null, t=0, cnt=1, w=1454423099894, Int=0
D/PMS     (  941): releaseWL(1204799c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6952): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6952): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6952): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 6952): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6952): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6952): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1786): client connected with version: 7571000,
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6952): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
D/Finsky  ( 6952): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6952): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6952): [1] DailyHygiene.reschedule: Scheduling new run in 87 minutes (failures=3),
,D/DeviceConnectionService( 1786): client connected with version: 7571000,
,D/Process (  941): killProcessQuiet, pid=5961
,I/ActivityManager(  941): Killing 5961:com.android.settings/1000 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 5961
D/WifiService(  941): Client connection lost with reason: 4
,I/ActivityManager(  941): Killing 6504:com.htc.mobiledata/u0a46 (adj 15): empty #17
,D/Process (  941): killProcessQuiet, pid=6504
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6504
,D/PMS     (  941): acquireWL(3318d5d7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{2729703d: PendingIntentRecord{19059032 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=639051, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{39bd21ad: PendingIntentRecord{2e983ce2 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454423115092, Int=0
,D/PMS     (  941): releaseWL(3318d5d7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/Finsky  ( 6952): [698] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 6952): [1] 5.onFinished: Installation state replication succeeded.,
,D/PMS     (  941): acquireWL(322af873): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(322af873): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  941): updateBatteryInfo
,D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PMS     (  941): runPSCheck
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  941): >> updateStatus
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  941): handleMessage: E msg.what=155652
,D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  941): acquireWL(ff10330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(ff10330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  941): plugged=true pluggin=true
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  941): >> updateStatus,
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  941): acquireWL(1fb72ba9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{2729703d: PendingIntentRecord{19059032 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=699051, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{2cc78114: PendingIntentRecord{3be3dbd android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805665, Int=0,
,D/PMS     (  941): releaseWL(1fb72ba9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  941): acquireWL(3e01452e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(3e01452e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/NotificationService(  941): plugged=true pluggin=true
,D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): Checking...
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  941): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: X
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  941): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1917): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1917): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1917): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1917): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1917): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1917): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1917): 	at android.os.Binder.execTransact(Binder.java:454),
,E/PlayEventLogger( 6952): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6952): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6952): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6952): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6952): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6952): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6952): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6952): Ignoring header User-Agent because its value was null.
,D/libc    ( 6952): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6952): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6952): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6952): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 6952): [NET] android_getaddrinfo_proxy+
D/libc    ( 6952): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  423): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  423): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  423): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  423): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6952): [NET] android_getaddrinfo_proxy-, success
,I/art     (  941): Explicit concurrent mark sweep GC freed 24142(1140KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 18MB/28MB, paused 2.522ms total 190.563ms
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40,
,D/PMS     (  941): acquireWL(16a39860): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
,V/AlarmManager(  941): sending alarm PendingIntent{2729703d: PendingIntentRecord{19059032 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=819051, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{36555119: PendingIntentRecord{335f55de com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940747, Int=0
,I/bt-btm  ( 3121): Received oneshot timer event complete
,I/bt-btm  ( 3121): btm_ble_timeout
I/bt-btm  ( 3121): btm_gen_resolvable_private_addr
,D/PMS     (  941): acquireWL(337563bf): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3121 1002 null
,D/PMS     (  941): releaseWL(16a39860): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/bt-btm  ( 3121): btm_ble_rand_enc_complete
I/bt-btm  ( 3121): btm_gen_resolve_paddr_low
,D/bt-smp  ( 3121): smp_encrypt_data
W/bt-smp  ( 3121): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3121): Plain text(LSB ~ MSB) = d5 f4 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 3121): Encrypted text(LSB ~ MSB) = ea 79 8b b2 14 11 4e c2 2a 50 1d f9 e9 9b fe b9 ,
I/bt-btm  ( 3121): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3121): Stopping oneshot timer
D/bt-btm  ( 3121): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  941): releaseWL(337563bf): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  941): acquireWL(1219da8c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
,V/AlarmManager(  941): sending alarm PendingIntent{2729703d: PendingIntentRecord{19059032 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=999051, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{29e0e5d5: PendingIntentRecord{3286f1ea com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012328, Int=0
,D/PMS     (  941): acquireWL(26267cdb): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,V/AlarmManager(  941): sending alarm PendingIntent{24d01378: PendingIntentRecord{28fd1146 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454423428554, Int=0
D/PMS     (  941): releaseWL(26267cdb): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6829): MY_DEBUG = false,
,D/PMS     (  941): releaseWL(1219da8c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PowerUsageService( 6829): repeat time = 1454424373325
,D/PMS     (  941): acquireWL(1ada42b6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1917): Message class com.google.f.a.a.i
,D/PMS     (  941): releaseWL(1ada42b6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6829): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6829): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  941): acquireWL(3e060bb7): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000},
,V/AlarmManager(  941): sending alarm PendingIntent{6aeef24: PendingIntentRecord{3f30fa8d com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454423474851, Int=0
,D/SmartSyncUtils( 6829): isEpsOn(), nState = 0
,D/PMS     (  941): releaseWL(3e060bb7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  941): acquireWL(2a3fd442): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6829 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6829): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6829): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6829): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6829): SettingOnTime = 1454479200000, randomSettingOnTime = 1454476822000
D/SmartSyncScreenOnOffTimeReceiver( 6829): SettingOffTime = 1454457600000, randomSettingOffTime = 1454464787000
,D/SmartSyncScreenOnOffTimeReceiver( 6829): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6829): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6829): bNightModeTurnOffOnce = false
,D/PMS     (  941): releaseWL(2a3fd442): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  941): acquireWL(1ce5ac53): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
D/UsbnetService(  941): BroadcastReceiver::onReceive+
I/BatteryService(  941): n_update end
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PMS     (  941): releaseWL(1ce5ac53): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): updateBatteryInfo
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): battery changed pluggedType: 2
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  941): runPSCheck
D/HtcPowerSaver(  941): Checking...
I/HtcPowerSaver(  941): >> updateStatus
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  941): acquireWL(237dd990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(237dd990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  941): runPSCheck
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): onReceive BATTERY_CHANGED
,D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  941): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
