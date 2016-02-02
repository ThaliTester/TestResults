#### Test 575312431be71d2_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1574822877] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1574822876] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1320): environment dirty rate=0 [16][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
--------- beginning of system
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.11 txretriesrate=0.00 rxrate=7.27 userTriggerdPenalty0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
E/WifiStateMachine(  968): handleMessage: X
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  968):  packet count Tx=147 Rx=234
E/WifiTrafficPoller(  968): notifying of data activity 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=147 Rx=234
I/HtcModeClient( 3227): handler message = 4011
E/HtcModeClient( 3227): Check connection and retry 12 times.
E/cutils-trace( 6451): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6451): ====startRecUseTime====
D/htc.customization.log.level( 6451):  is 
W/CustomizationLogLevel( 6451): Level value is invalid, use default level 2
D/CustomizationManager( 6451):  Read ACC file spent 0.042 (s)
D/CIDMapFileReader( 6451): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6451): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6451): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6451): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6451): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6451): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6451): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6451): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6451): Parsing tag category name = system
I/CustomizationCIDLoader( 6451): Parsing tag category name = application
I/CustomizationCIDLoader( 6451): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6451): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6451): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6451): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6451): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6451): add string-array item, value = 42507
I/CustomizationCIDLoader( 6451): add string-array item, value = 21902
I/CustomizationCIDLoader( 6451): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6451): add string-array item, value = 23420
I/CustomizationCIDLoader( 6451): add string-array item, value = 22299
I/CustomizationCIDLoader( 6451): add string-array item, value = 24002
I/CustomizationCIDLoader( 6451): add string-array item, value = 23210
I/CustomizationCIDLoader( 6451): add string-array item, value = 23205
I/CustomizationCIDLoader( 6451): add string-array item, value = 23806
I/CustomizationCIDLoader( 6451): add string-array item, value = 23430
I/CustomizationCIDLoader( 6451): add string-array item, value = 23408
I/CustomizationCIDLoader( 6451): add string-array item, value = 27205
I/CustomizationCIDLoader( 6451): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6451): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6451):  Read CID file spent 0.087 (s)
D/CustomizationManager( 6451):  All configurations done spent 0.087 (s)
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6451 on display 0
D/PMS     (  968): acquireHCC(f6d7c19): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 968 1000 null
D/PMS     (  968): acquireHCC(1c3a4de): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 968 1000 null
D/PMS     (  968): acquireWL(13d0c0d5): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 968 1000 null
I/FeedHostManager( 1628): [onPause]
I/FeedProviderManager( 1628): onPause
I/FeedHostManager( 1628): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@fa1b649
I/SocialFeedProvider( 1628): +onPause
I/SocialFeedProvider( 1628): -onPause
I/AnimationUtil(  968): isHTCRecent(ThaliTest/Recent screens.)/5
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6469 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  439): Explicit concurrent mark sweep GC freed 8676(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 276us total 22.875ms
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 353us total 16.463ms
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 654us total 20.283ms
D/StatusBarManagerService(  968): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
I/TrimMemoryManager( 1628): [trimMemory] 20
,I/WebViewFactory( 6469): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6469): Time to load native libraries: 12 ms (timestamps 1295-1307)
,I/LibraryLoader( 6469): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6469): Binding Chromium to main looper Looper (main, tid 1) {296660e8}
I/LibraryLoader( 6469): Expected native library version number "",actual native library version number ""
,I/chromium( 6469): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6469): Initializing chromium process, singleProcess=true,
,W/art     ( 6469): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6469): ApplicationContext is null in ApplicationStatus
,W/chromium( 6469): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6469): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6469): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6469): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6469): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6469): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6469): Local Branch: 
I/Adreno-EGL( 6469): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6469): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6469):                  d74aa161a12b9c6fc6332151
,W/System.err(  968): java.lang.Throwable: stack dump
,W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c9fa89a:true
,D/BluetoothAdapter( 6469): 540601917: getState(). Returning 12
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  968):  packet count Tx=147 Rx=235
,E/WifiTrafficPoller(  968): notifying of data activity 1
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/art     ( 6469): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6469): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6469): CordovaWebView is running on device made by: HTC,
,W/art     ( 6469): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6469): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6469): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FindExtension( 6469): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6469): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1326e0ad, mServedView=org.apache.cordova.engine.SystemWebView{32d08fe2 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@19704f73,
,I/InputMethodManagerService(  968): Disable input method client, pid=1628
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  968): Enable input method client, pid=6469
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +855ms
D/Process (  968): killProcessQuiet, pid=5891
D/PMS     (  968): releaseWL(13d0c0d5): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  968): Killing 5891:com.htc.calendar/u0a10 (adj 15): empty #17
,W/XT9_C   ( 1401): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
I/XT9_C   ( 1401): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1401): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1401): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 6469): Cannot call determinedVisibility() - never saw a connection for the pid: 6469
,I/ActivityManager(  968): Recipient 5891
,I/ActivityManager(  968): Killing 5848:com.google.android.gm/u0a106 (adj 15): empty #18,
D/Process (  968): killProcessQuiet, pid=5848
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/JsMessageQueue( 6469): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  968): Recipient 5848
,D/jxcore_app_log( 6469): JniHelper::setJavaVM(0xaac178f8), pthread_self() = -1410145008,
,I/chromium( 6469): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=7.3 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1574819853] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=7.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1574819851] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1320): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
,E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.05 txretriesrate=0.00 rxrate=4.13 userTriggerdPenalty0
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968):  good link -> stuck count =0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 56
,E/WifiStateMachine(  968):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
,E/WifiStateMachine(  968): handleMessage: X
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  968):  packet count Tx=147 Rx=235,
E/WifiTrafficPoller(  968): notifying of data activity 0
D/WIFI_ICON( 1221): WifiActivity: 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  968): releaseHCC(f6d7c19): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  968): releaseHCC(1c3a4de): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6469): Initializing JXcore engine,
W/jxcore-log( 6469): JXcore engine is ready
,W/jxcore-log( 6469): Starting JXcore engine,
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=129 rxSum=112} preTxRxSum={txSum=128 rxSum=110}
D/WifiDataStallTracker(  968): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/jxcore-log( 6469): Platform android,
W/jxcore-log( 6469): 
W/jxcore-log( 6469): Process ARCH arm
W/jxcore-log( 6469): 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  968):  packet count Tx=147 Rx=235
,I/jxcore-log( 6469): JXcore Cordova bridge is ready!,
I/jxcore-log( 6469): 
W/jxcore-log( 6469): JXcore engine is started
,I/jxcore-log( 6469): Toggling radios to true
I/jxcore-log( 6469): 
,D/BluetoothAdapter( 6469): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  968): ADD_CLIENT: 7
,D/WifiService(  968): New client listening to asynchronous messages
,D/WifiManager( 6469): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  968): setWifiEnabled: true pid=6469, uid=10366
W/Settings:Agent(  968): MONITOR_LOG
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  968): name: wifi_on
I/WifiService(  968): isSprintWifiRestricted(): false
W/Settings:Agent(  968): value: 2
I/WifiService(  968): isMdmWifiRestricted(): false
W/Settings:Agent(  968): >> traceCallingStack()
W/Settings:Agent(  968): Process.myPid(): 968
,W/Settings:Agent(  968): Process.myTid(): 1007
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
W/System.err(  968): java.lang.Throwable: stack dump
,W/System.err(  968): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503),
,W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  968): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  968): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 20(ms)
D/WifiController(  968): handleMessage: E msg.what=155656
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): handleMessage: X
D/WifiManager( 6469): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiManager( 6469): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  968): handleMessage: E msg.what=131145
,E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1320): wlan0: Control interface command 'DISCONNECT'
I/jxcore-log( 6469): Radios toggled
I/jxcore-log( 6469): 
D/wpa_supplicant( 1320): wlan0: Cancelling scan request
D/wpa_supplicant( 1320): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1320): TDLS: Tear down peers
D/wpa_supplicant( 1320): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6469): My device name is: HTC-HTC One M8s
I/jxcore-log( 6469): 
,D/wpa_supplicant( 1320): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1320): wlan0: Deauthentication notification
D/wpa_supplicant( 1320): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1320): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
,I/wpa_supplicant( 1320): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1320): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1320): enter disconnect check
I/wpa_supplicant( 1320): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1320): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1320): wlan0: Ignore connection failure indication since interface has been put into disconnected state
E/WifiMonitor(  968): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
E/WifiMonitor(  968): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  968): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  968): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  968): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
D/Tethering(  968): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/UsbnetService(  968): BroadcastReceiver::onReceive+,
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1320): TDLS: Remove peers on disassociation
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/wpa_supplicant( 1320): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1320): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1320): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1320): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x559e128f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1320):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1320): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1320): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1320): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1320): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1320): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1320): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1320): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1320): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1320): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1320): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1320): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1320): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1320): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1320): EAPOL: External notification - portValid=0
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1320): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1320): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1320): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1320): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1320): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  968): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: ConnectedState
E/WifiStateMachine(  968): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  968): release()
E/WifiStateMachine(  968): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEn,abledtrue
E/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  968): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): handleNetworkDisconnect "NG700" nid=0
D/PMS     (  968): acquireWL(3c53aa2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1320): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1320): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1320): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1320): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1320): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1320): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiP2pService(  968): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1320): Power_Mode_Type mode = 0
I/wpa_supplicant( 1320): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1320): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  968): setDhcpActive: false
E/Netd    (  394): ifc_reset_connections failed on iface wlan0 for address 192.168.1.130/24 (Unknown error -1)
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  968): NetworkAgent != null
,E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 11
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  968):  packet count Tx=147 Rx=236
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiTrafficPoller(  968): notifying of data activity 1
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
,D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1221): WifiActivity: 1
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  968): stopDataStallAlarm 
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 1
,D/TetherSettings( 5994): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5994): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5994): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5994): Cust_ConnectToPC   : spcsc>false
D/        ( 5994): Cust_ConnectToPC   : IPT>true
D/        ( 5994): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  968): autoRoamSetBSSID any key="NG700"WPA_PSK
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/PMS     (  968): releaseWL(3c53aa2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1320): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1320): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
,D/wpa_supplicant( 1320): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1320): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1320): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1320): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1320): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  968):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  968): Start Disconnecting Watchdog 1
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131146
E/WifiStateMachine(  968): processMsg: DisconnectingState
E/WifiStateMachine(  968):  DisconnectingState !CMD_RECONNECT 0 0
,E/WifiStateMachine(  968): processMsg: ConnectModeState
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968):  ConnectModeState !CMD_RECONNECT 0 0
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1320): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1320): Fast associate: Old scan results
D/wpa_supplicant( 1320): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1320): wpa_supplicant_scan enter
D/wpa_supplicant( 1320): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1320): wlan0: Starting AP scan for wildcard SSID
,D/wpa_supplicant( 1320): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1320): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1320): WPS:  * Request Type
D/wpa_supplicant( 1320): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1320): WPS:  * UUID-E
D/wpa_supplicant( 1320): WPS:  * Primary Device Type
D/wpa_supplicant( 1320): WPS:  * RF Bands (3)
D/wpa_supplicant( 1320): WPS:  * Association State
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1320): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1320): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1320): WPS:  * Manufacturer
D/wpa_supplicant( 1320): WPS:  * Model Name
D/wpa_supplicant( 1320): WPS:  * Model Number
D/wpa_supplicant( 1320): WPS:  * Device Name
D/wpa_supplicant( 1320): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1320): P2P: * P2P IE header
D/wpa_supplicant( 1320): P2P: * Capability dev=25 group=00
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
D/wpa_supplicant( 1320): P2P: * Listen Channel: Regulatory Class 81 Channel 1
V/NetworkPolicy(  968): updateNotificationsLocked()
D/wpa_supplicant( 1320): wlan0: Add radio work 'scan'@0x559e12b680
D/wpa_supplicant( 1320): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1320): wlan0: Starting radio work 'scan'@0x559e12b680 after 0.000085 second wait
D/wpa_supplicant( 1320): wlan0: nl80211: scan request
E/WifiStateMachine(  968): handleMessage: X
W/Settings( 5994): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  968): handleMessage: E msg.what=147460
E/WifiStateMachine(  968): processMsg: DisconnectingState
D/wpa_supplicant( 1320): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1320): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1320): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1320): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1320): wlan0: Own scan request started a scan in 0.000224 seconds
I/wpa_supplicant( 1320): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  968):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=103906
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  968):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=103907
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  968): ConnectModeState: Network connection lost 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
,E/WifiStateMachine(  968): DisconnectedState call setCountryCode()
E/WifiStateMachine(  968):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1320): Pending scan scheduled - reject new request
E/WifiStateMachine(  968): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
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
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=103916  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=103917  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
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
E/SmartNS_Utility( 5994): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5994): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/SmartNS_NSReceiver( 5994): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_L,INKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
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
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=103926  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ContextImpl( 5994): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/SmartNS_Utility( 5994): setISNotification
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=103930  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): handleMessage: X
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_Utility( 5994): usb_cable_connect = 1
D/SmartNS_Utility( 5994): usb_denied = 0
I/SmartNS_PSService( 5994): usb notificaiton:true
I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
I/ActionCombine( 5994): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/SmartNS_Utility( 5994): usb_cable_connect = 1
D/SmartNS_Utility( 5994): usb_denied = 0
I/SmartNS_PSService( 5994): usb notificaiton:true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:10
I/RemoteViews( 1221): reapply : com.android.settings 0 36
D/SmartNS_NSReceiver( 5994): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
D/ConnectivityService(  968): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1221): onLost 100
D/ConnectivityService(  968): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  968): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  968): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  968): Removing idletimer
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI    (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  968): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Disconnected - quitting
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,I/ActivityManager(  968): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6530 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/WISPrService( 5994): >>>>>WISPrService start isConnected = true<<<<<
D/PMS     (  968): acquireWL(238a96f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 968 1000 null,
D/CSLegacyTypeTracker(  968): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiService(  968): New client listening to asynchronous messages,
,E/WifiTrafficPoller(  968): ADD_CLIENT: 8
,I/ActivityManager(  968): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6547 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  968): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
,E/WifiStateMachine(  968): processMsg: DisconnectedState,
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  968): acquireWL(99f9469): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  968):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/DATA_ICON( 1221): dataConnected: false/false
E/WifiStateMachine(  968):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): handleMessage: X
D/PMS     (  968): releaseWL(99f9469): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateIfacesLocked()
W/WISPrService( 5994): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  968): updateNotificationsLocked()
D/WISPrService( 5994): trigger connection
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 5994): continue
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5994): start DataConnection
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/libc    ( 5994): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5994): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/libc    ( 5994): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5994): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5994): [NET] android_getaddrinfo_proxy+
D/libc    ( 5994): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024,
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
W/ResourcesManager( 6530): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5994): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms,
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/libc    ( 5994): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5994): [NET] android_getaddrinfofornet-, err=8
I/CalendarProvider2( 6530): Created com.android.providers.calendar.CalendarAlarmManager@3c40c5da(com.htc.providers.calendar.HtcCalendarProvider@478da0b)
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/CalendarProvider2( 6530): wait start:true,
,D/WISPrService( 5994): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  968): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6580 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/Process (  968): killProcessQuiet, pid=5816,
I/ActivityManager(  968): Killing 5816:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false,
,D/CalendarProvider2( 6530): wait end:false
,I/ActivityManager(  968): Recipient 5816
,I/art     (  968): Explicit concurrent mark sweep GC freed 35347(1845KB) AllocSpace objects, 5(292KB) LOS objects, 33% free, 16MB/25MB, paused 1.596ms total 140.977ms
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false,
,D/MdProvGlob( 6547): add item 101 (2:g3d8) for 15:android.intent.action.PRECISE_DATA_CONNECTION_STATE_CHANGED
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6580): [ace.2.]  listen tmrbb8
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
D/MdProvGlob( 6547): remove item 101 (p3d10in83) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 6580): [ace.2.] summary 118:p3 ignore
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
D/MdProvGlob( 6547): remove item 101 (p3in9) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6547): remove item 101 (p3in7) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6547): remove item 101 (p3in10) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 6547): remove item 101 (p3in6) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6547): remove item 101 (p3d2in16) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 6547): remove item 101 (p3d1in10) for 15:android.intent.action.ANY_DATA_STATE
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 16 num clients 8
,D/Process (  968): killProcessQuiet, pid=5972
I/ActivityManager(  968): Killing 5972:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5972,
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 16 num clients 8,
,I/CalendarProvider2( 6530): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6530): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  968): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6612 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  968): killProcessQuiet, pid=6268
,I/ActivityManager(  968): Killing 6268:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6268
,W/ResourcesManager( 6612): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/CalendarApplication( 6612): onCreate,
,D/ProviderChangeReceiver( 6612): ---------------------------------------------------,
D/ProviderChangeReceiver( 6612): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  968): killProcessQuiet, pid=6291
I/ActivityManager(  968): Killing 6291:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6612): start to updateAlertNotification!
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1574816833] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1574816832] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1574816831] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1574816830] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: DefaultState
,E/WifiStateMachine(  968):  DefaultState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1574816829] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): handleMessage: X
,I/ActivityManager(  968): Recipient 6291
,D/HtcAlertService( 6612): No fired or scheduled alerts
D/HtcAlertUtils( 6612): -- cancelReminderNotification --
,D/HtcAlertUtils( 6612): broadcastExistReminder!
,D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcModeClient( 3227): handler message = 4011
,E/HtcModeClient( 3227): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3227): Don't start project servcice
,D/HtcModeClient( 3227): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3227): connectState: CONNECTION_READY = false
,D/SilentMusic( 3227): call stop
D/HtcModeClient( 3227): close connection
W/HtcModeClient( 3227): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3227): read the terminate packet, so break
,D/Process (  968): killProcessQuiet, pid=3227
I/ActivityManager(  968): Killing 3227:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 3227
,D/wpa_supplicant( 1320): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1320): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1320): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1320): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1320): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1320): wlan0: Scan completed in 2.115771 seconds
D/wpa_supplicant( 1320): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1320): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1320): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1320): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1320): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-87
D/wpa_supplicant( 1320): wlan0: BSS: Start scan result update 6
,D/wpa_supplicant( 1320): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1320): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1320): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1320): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1320): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1320): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1320): wlan0: Radio work 'scan'@0x559e12b680 done in 2.117480 seconds
D/wpa_supplicant( 1320): wlan0: Selecting BSS from priority group 595
D/wpa_supplicant( 1320): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/wpa_supplicant( 1320): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1320): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1320): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 1320): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1320): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1320): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1320):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1320): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1320): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x559e12ac00  current_ssid=0x0
D/wpa_supplicant( 1320): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1320): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1320): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1320): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1320): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1320): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1320): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1320): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1320): TDLS: TDLS is allowed in the target BSS
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1320): wlan0: Add radio work 'connect'@0x559e12b680
D/wpa_supplicant( 1320): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1320): wlan0: Starting radio work 'connect'@0x559e12b680 after 0.000045 second wait
I/wpa_supplicant( 1320): check if in concurrent case
I/wpa_supplicant( 1320): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1320): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1320): wlan0: Cancelling scan request
D/wpa_supplicant( 1320): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1320): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1320): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1320): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1320): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1320): RSN: PMKSA cach,e search - network_ctx=0x559e12ac00 try_opportunistic=0
D/wpa_supplicant( 1320): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1320): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1320): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1320): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1320): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1320): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1320): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1320): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1320): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1320): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1320): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1320): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1320): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1320): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1320): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1320): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1320): nl80211: Unsubscribe mgmt frames handle 0x888888dd169a2989 (mode change)
D/wpa_supplicant( 1320): nl80211: Subscribe to mgmt frames with non-AP handle 0x559e12a100
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=0104
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=040a
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=040b
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=040c
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=040d
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=090a
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=090b
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=090c
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=090d
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=0409506f9a09
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=7f506f9a09
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=0801
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=040e
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=06
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=0a07
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=0a11
D/wpa_supplicant( 1320): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559e12a100 match=0a1a
D/wpa_supplicant( 1320): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1320):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320):   * freq=2412
D/wpa_supplicant( 1320):   * freq_hint=2412
D/wpa_supplicant( 1320):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1320):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1320):   ,* WPA Versions 0x2
D/wpa_supplicant( 1320):   * pairwise=0xfac04
D/wpa_supplicant( 1320):   * group=0xfac04
D/wpa_supplicant( 1320):   * akm=0xfac02
D/wpa_supplicant( 1320):   * Auth Type 0
D/wpa_supplicant( 1320): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x559e12ac3a
D/wpa_supplicant( 1320): nl80211: Connect request send successfully
D/wpa_supplicant( 1320): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1320): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1320): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1320): EAPOL: External notification - portControl=Auto
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  968): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiStateMachine(  968): handleMessage: E msg.what=147461
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=37 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  968): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=38 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  968):  DisconnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:83 bcn=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:83 bcn=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:83 bcn=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:83 bcn=0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1320): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  968): [1,454,419,097,082 ms] noteScanEnd no scan source
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1320): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  968): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@dc57b03 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  968): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  968): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  968): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  968):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  968): 01ABC c2:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  968): Gonzos 38:f8:89:11:e9:11 rssi=-87 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  968): ageScanResultsOut delay 40000 size 4 now 1454419097084
E/WifiAutoJoinController (  968): newSupplicantResults size=4 known=1 true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1320): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  968): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  968): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  968): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  968): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  968): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  968):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131213
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106037
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106038
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106038
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106038
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=106039  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info0x
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): NetworkAgent == null
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=106043  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  968): handleMessage: X
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1320): Wireless event: cmd=0x8c02 len=271,
I/wpa_supplicant( 1320): WEXT: Custom wireless event: 'BEACONIEs='
,D/wpa_supplicant( 1320): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1320): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1320): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1320): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1320): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1320): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1320): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1320): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
D/wpa_supplicant( 1320): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1320): nl80211: Connect event
D/wpa_supplicant( 1320): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1320): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1320): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1320): wlan0: Association info event
D/wpa_supplicant( 1320): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1320): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1320): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1320): wlan0: freq=2412 MHz
D/wpa_supplicant( 1320): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1320): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1320): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1320): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1320): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1320): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1320): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1320): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1320): wlan0: WPA: Association event - clear replay counter
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1320): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1320): TDLS: Remove peers on association
D/wpa_supplicant( 1320): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1320): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1320): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1320): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1320): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1320): EAPOL: enable timer tick
D/wpa_supplicant( 1320): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1320): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1320): wlan0: Cancelling scan request
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1320): wlan0: Process pending EAPOL frame that was received just before association notification
D/wpa_supplicant( 1320): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1320): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1320): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1320): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1320): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1320):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1320):   key_nonce - hexdump(len=32): 7f 0b 10 6e f9 e,1 e3 b6 9f ee 09 6b 7a f0 c4 83 04 f0 78 04 83 e1 4d bd 65 a7 7d 10 dd 16 f1 79
D/wpa_supplicant( 1320):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1320):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1320):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1320):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1320): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1320): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1320): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=41 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1320): WPA: Renewed SNonce - hexdump(len=32): d9 d3 87 46 75 f2 80 85 4a f1 b7 a6 68 ac ea 20 3d 15 08 eb 55 9d 48 4c 49 a3 8d 11 dc 53 08 9c
D/wpa_supplicant( 1320): WPA: Nonce1 - hexdump(len=32): d9 d3 87 46 75 f2 80 85 4a f1 b7 a6 68 ac ea 20 3d 15 08 eb 55 9d 48 4c 49 a3 8d 11 dc 53 08 9c
D/wpa_supplicant( 1320): WPA: Nonce2 - hexdump(len=32): 7f 0b 10 6e f9 e1 e3 b6 9f ee 09 6b 7a f0 c4 83 04 f0 78 04 83 e1 4d bd 65 a7 7d 10 dd 16 f1 79
D/wpa_supplicant( 1320): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1320): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1320): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/HTCRequest(  968): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1320): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1320): wlan0: WPA: Sending EAPOL-Key 2/4
D/HTCRequest(  968): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1320): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1320): WPA: Derived Key MIC - hexdump(len=16): 5a db 2f 09 a9 b5 46 92 1d 76 c8 3d 9c 09 f7 44
I/wpa_supplicant( 1320): htc_wext_set_keepalive +
I/wpa_supplicant( 1320): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1320): getPrivFuncNum +	
I/wpa_supplicant( 1320): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1320): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1320): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  968): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  968): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/PMS     (  968): acquireWL(323bcf9b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiSt,ateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=106137  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=106138  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147500
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1320): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/Tethering(  968): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1320): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1320): wlan0:   EAPOL-Key type=2
E/WifiStateMachine(  968):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/wpa_supplicant( 1320): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1320): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1320):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1320):   key_nonce - hexdump(len=32): 7f 0b 10 6e f9 e1 e3 b6 9f ee 09 6b 7a f0 c4 83 04 f0 78 04 83 e1 4d bd 65 a7 7d 10 dd 16 f1 79
D/wpa_supplicant( 1320):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1320):   key_rsc - hexdump(len=8): 69 15 00 00 00 00 00 00
D/wpa_supplicant( 1320):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1320):   key_mic - hexdump(len=16): 19 8c 1a fb 87 20 5c 5a 10 16 c3 c7 ad 93 a8 0c
E/WifiStateMachine(  968):  ConnectModeState !what:147500 0 0
D/wpa_supplicant( 1320): RSN: encrypted key data - hexdump(len=56): 57 c2 a7 39 14 9c 2f 82 bf cf e5 2a 5a de 20 76 7b 10 12 5d 9d 0d c5 39 7d 89 36 9d 0e 1f fa 40 ...
D/WifiStateMachine(  968): Enter handleAssociatedWithEvent
D/wpa_supplicant( 1320): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1320): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  968): Associated
D/wpa_supplicant( 1320): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1320): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 cb bd ...
D/wpa_supplicant( 1320): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1320): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1320): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1320): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1320): WPA: Derived Key MIC - hexdump(len=16): 66 e7 d8 d5 a0 ae c9 e2 57 99 44 15 9f 48 a8 e2
D/wpa_supplicant( 1320): wlan0: WPA: Installing PTK to the driver
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/Tethering(  968): interfaceStatusChanged wlan0, true
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1320): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x559e12b390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1320): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1320): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1320):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  968): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  968): Exit handleAssociatedWithEvent
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/wpa_supplicant( 1320): EAPOL: External notification - portValid=1
V/Tethering(  968): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1320): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1320): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1320): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1320): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1320): WPA: RSC - hexdump(len=6): 69 15 00 00 00 00
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1320): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x555fce8e68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1320): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1320): nl80211: KEY_SEQ - hexdump(len=6): 69 15 00 00 00 00
D/wpa_supplicant( 1320):    broadcast key
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1320): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1320): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1320): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1320): wlan0: Radio work 'connect'@0x559e12b680 done in 0.118478 seconds
D/Tethering(  968): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 1320): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1320): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=44 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=106141  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=45 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
D/UsbnetService(  968): BroadcastReceiver::onReceive+
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1320): wlan0: Connect to SSID: NG700
E/WifiMonitor(  968): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/wpa_supplicant( 1320): nl80211: Set wlan0 operstate 0->1 (UP)
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/wpa_supplicant( 1320): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  968): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=47 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  968): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1320): set send_ind_to_ndc = 0
W/ContextImpl( 5994): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/wpa_supplicant( 1320): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1320): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1320): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1320): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1320): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1320): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1320): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1320): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1320): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1320): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1320): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1320): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1320): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1320): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/PMS     (  968): releaseWL(323bcf9b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/Tethering(  968): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=106148  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
D/TetherSettings( 5994): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
V/NetworkPolicy(  968): updateNotificationsLocked()
D/        ( 5994): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5994): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5994): Cust_ConnectToPC   : spcsc>false
D/        ( 5994): Cust_ConnectToPC   : IPT>true
D/        ( 5994): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  968): handleMessage: X
W/Settings( 5994): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5994): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5994): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5994): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 19
I/SmartNS_Utility( 5994): setISNotification
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=106153  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=106154  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147459
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=106157
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=106158
E/WifiStateMachine(  968): Network connection established
D/WifiStateMachine(  968): fetchFrequency(), freq = 2412
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_Utility( 5994): usb_cable_connect = 1
E/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
D/SmartNS_Utility( 5994): usb_denied = 0
E/WifiStateMachine(  968): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
I/SmartNS_PSService( 5994): usb notificaiton:true
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 22
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  968): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  968): Got NetworkAgent Messenger
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/wpa_supplicant( 1320): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/ConnectivityService(  968): NetworkAgent connected
D/wpa_supplicant( 1320): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1320): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1320): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1320): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1320): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  968): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  968): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1320): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1320): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1320): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1320): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1320): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1320): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/SmartNS_Utility( 5994): usb_cable_connect = 1
E/WifiStateMachine(  968): Start Dhcp Watchdog 2
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: ObtainingIpState
D/SmartNS_Utility( 5994): usb_denied = 0
I/SmartNS_PSService( 5994): usb notificaiton:true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=106173  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=106174  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=106175  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): handleMessage: X
D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ObtainingIpState
I/RemoteViews( 1221): reapply : com.android.settings 1 36
E/WifiStateMachine(  968):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:711] from screen [on:0 period:-1574816118] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1574816117] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1320): environment dirty rate=0 [2][0][0]
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=73.50 txretriesrate=0.00 rxrate=118.00 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
E/WifiStateMachine(  968): calculateWifiScore() report new score 60
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
D/SmartNS_NSReceiver( 5994): Tethered state change:false isNSOpening:false
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
D/ConnectivityService(  968): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  968):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/WifiStateMachine(  968): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  968): handleMessage: X
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  968): handleMessage: E msg.what=196612
D/PMS     (  968): acquireWL(31ed916f): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 968 1000 null
E/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  968):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=147,0,0
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@174142fb target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@174142fb target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=147,0,0
D/WifiDataStallTracker(  968): setDhcpActive: true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1320): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  968): do suspend false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1320): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1320): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1320): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1320): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1320): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1320): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1320): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): noteBatchedScanstop()
E/WifiStateMachine(  968): handleMessage: X
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
,D/AccTypeManager( 1763): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead
,W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
W/Prism.AllAppsManager( 1628): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1763): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6638 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Launcher( 1628): Deferring update until onResume
D/Launcher( 1628): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1763): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1568): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1763): Unsupported attribute readOnly,
,W/ResourcesManager( 6638): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/PackageManager(  968): Unable to load service info ResolveInfo{8531d61 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
,W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
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
,V/GmsNetworkLocationProvi( 1906): DISABLE
,I/GCoreNlp( 1906): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  968): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/PMS     (  968): acquireWL(241ac864): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1906 10024 WorkSource{10024 com.google.android.gms}
,E/dhcpcd  ( 6661): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6661): version 5.5.6 starting
D/PMS     (  968): releaseWL(241ac864): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
E/dhcpcd  ( 6661): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6661): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6661): autoip env[11]:autoip=DISABLE
D/LocationProviderProxy(  968): applying state to connected service
,D/LocationProviderProxy(  968): applying state to connected service
D/PMS     (  968): acquireWL(2adfb8ef): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1906 10024 WorkSource{10024 com.google.android.gms}
,I/art     ( 1833): Explicit concurrent mark sweep GC freed 11955(646KB) AllocSpace objects, 7(588KB) LOS objects, 49% free, 4MB/8MB, paused 1.022ms total 42.841ms
D/PMS     (  968): releaseWL(2adfb8ef): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(2374bffc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1906 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2374bffc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(244bdfe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1906 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(244bdfe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/dhcpcd  ( 6661): wlan0: rebinding lease of 192.168.1.130
,I/dhcpcd  ( 6661): wlan0: sending REQUEST (xid 0x64207d77), next in 1.43 seconds
,I/Babel_SMS( 6638): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6638): MmsConfig.loadMmsSettings
,I/ActivityManager(  968): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6676 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6638, uid=10112, userID:0,
,W/HtcWrapAdjustableCursorFactory( 6676): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 6676): onCreate
,D/MmsCustomizationProvider( 6676): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 6676): GetPrviateResource
V/GetPrviateResource( 6676): GetPrviateResource
,D/MmsCustomizationProvider( 6676): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/MessageCustFlag( 6676): sense_version=6.0
D/BTAccessoryUtil( 6676): createReceiver
D/BTAccessoryUtil( 6676): registerReceiver return intent = null
D/MessageCustFlag( 6676): sku_id=118
I/Babel_SMS( 6638): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6638): MmsConfig.loadFromDatabase
D/HtcBuildUtils( 6676): getRATByHtcTelephonyCapability:1
W/SystemReader( 6676): Cannot find qct_8960_interface, use default value instead
E/Babel_SMS( 6638): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6638): MmsConfig.loadFromResources
E/Babel_SMS( 6638): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6638): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
W/Settings( 6638): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6638): startup - clean
,I/Babel   ( 6638): deleted: false for 0,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6638, uid=10112, userID:0
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6638, uid=10112, userID:0,
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6638, uid=10112, userID:0,
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6638, uid=10112, userID:0
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6638, uid=10112, userID:0
,D/PMS     (  968): acquireWL(2bb8a171): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6638 10112 null
,I/[PluginManager]RegisterService( 1540): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1540): handle notify Blinkfeed plugin client changed
,W/VideoCapabilities( 6638): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 4465): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4465): Null package name or gms related package.  Ignoreing.,
D/PMS     (  968): acquireWL(d052d30): PARTIAL_WAKE_LOCK  Icing 0x1 4465 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4465): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  968): acquireWL(2190da9): PARTIAL_WAKE_LOCK  AsyncService 0x1 6087 10167 null
D/PMS     (  968): releaseWL(2190da9): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  968): acquireWL(394c5acf): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6087 10167 null
,I/UpdateIcingCorporaServi( 5938): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  968): releaseWL(394c5acf): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,W/VideoCapabilities( 6638): Unsupported mime video/x-ms-wmv
,D/PMS     (  968): releaseWL(d052d30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/Utils   ( 6638): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 6638): Unsupported mime audio/qcelp,
,W/AudioCapabilities( 6638): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6638): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6638): Unsupported mime video/x-ms-wmv,
,I/UpdateIcingCorporaServi( 5938): UpdateCorporaTask done [took 46 ms] updated apps [took 46 ms] 
,I/VideoCapabilities( 6638): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6638): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6638): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6638): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6638): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6638): onServiceConnected
,W/Babel   ( 6638): Attempted to change video mute state without an active call.
,D/PMS     (  968): releaseWL(2bb8a171): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6638): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6638): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6638): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6638): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6638): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  968): acquireWL(20b36af4): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
I/ConnectivityHelper( 1628): [onReceive] WIFI(1): DISCONNECTED
D/GpsLocationProvider(  968): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ActivityManager(  968): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6715 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  968): No APN found to select.
,D/PMS     (  968): releaseWL(20b36af4): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6580): [ea2.1.]  listen tmrbb8
,D/MdScDataSum( 6580): [ea2.1.] summary 118:p1 ignore,
,D/wpa_supplicant( 1320): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1320): EAPOL: disable timer tick
,I/MusicStore( 6715): Database version: 120,
,D/VoldConnector(  968): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6715): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  968): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6715): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  968): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6715): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6715): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6715): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6715): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6715): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6715): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b3c52ee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6715): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6715): GMSCore installation verified
,I/ConfigStore( 6715): Config Database version: 1,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6715, uid=10159, userID:0,
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client,
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,D/MediaRouterService(  968): Client com.google.android.music (pid 6715): Registered
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
,D/WifiDisplayAdapter(  968):     IP Address: }
,I/MediaRouter( 6715): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6715): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6715, uid=10159, userID:0,
D/AutoSetting( 1540): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1540): Util - no network available!,
,D/MobileConnectivityChangeReceiver( 6421): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1540): service - onCreate()
,D/MobileConnectivityChangeReceiver( 6421): onReceive CONNECTIVITY_CHANGE networkType=1
,I/GHttpClientFactory( 6715): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6715): Using platform SSLCertificateSocketFactory,
,I/iu.Environment( 4465): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4465): num queued entries: 0
,D/AutoSetting( 1540): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
I/iu.UploadsManager( 4465): num updated entries: 0
I/iu.SyncManager( 4465): NEXT; no task
,D/LocationManagerService(  968): request 63dd0a8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  968): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1540): service - mHandler: cancel location update
D/AutoSetting( 1540): service -           changes count: 0
D/ChimeraCfgMgr( 4465): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/Process (  968): killProcessQuiet, pid=6059,
I/ActivityManager(  968): Killing 6059:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  968): acquireWL(1bfdf525): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(1bfdf525): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  968): Recipient 6059
,I/dhcpcd  ( 6661): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1628): loadItems() com.htc.launcher.pageview.WidgetManager@2b9b4915 +
I/Prism.WidgetManager( 1628): onLoadItems() +
,W/ResourcesManager( 1628): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6758 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/Babel   ( 6638): connection state changed from UNKNOWN to DISCONNECTED
,I/dhcpcd  ( 6661): wlan0: leased 192.168.1.130 for 86400 seconds
I/dhcpcd  ( 6661): autoip env[11]:autoip=DISABLE
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  968): handleMessage: X
,I/ActivityManager(  968): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6791 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  968): acquireWL(3fe7e4ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10076}
V/AlarmManager(  968): sending alarm PendingIntent{24aaa708: PendingIntentRecord{13bdbea1 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454419098941, Int=60000
,D/PMS     (  968): releaseWL(3fe7e4ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,I/art     (  438): Explicit concurrent mark sweep GC freed 8633(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 20.823ms
,I/art     (  438): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 177us total 16.504ms,
,I/art     (  438): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 16.814ms
,I/dhcpcd  ( 6661): bind_interface: daemonise
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=196613
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1320): Power_Mode_Type mode = 0
I/wpa_supplicant( 1320): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  968): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1320): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  968): setDhcpActive: false
D/PMS     (  968): releaseWL(31ed916f): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  968): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  968): WifiStateMachine DHCP successful
,E/WifiStateMachine(  968): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  968): link address 192.168.1.130/24
,E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  968): gateway: /192.168.1.1
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1320): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1320): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131210
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1320): environment dirty rate=0 [4][0][0]
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/wpa_supplicant( 1320): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1320): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=49 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  968): NetworkAgent != null
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
,E/WifiStateMachine(  968): transitionTo: destState=ConnectedState
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  968): Adding iface wlan0 to network 101
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  968): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
D/HtcWifiWanDetect(  968): WAN detection
E/WifiStateMachine(  968): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/HtcWifiWanDetect(  968): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
,E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 23
,E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=238
E/WifiTrafficPoller(  968): notifying of data activity 3
,E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL true Token 2
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 24
D/WIFI_ICON( 1221): WifiActivity: 3
D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  968): updateDataStallInfo: NONE
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=238,
E/WifiTrafficPoller(  968): notifying of data activity 0
,E/ConnectivityService(  968): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  968): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1221): WifiActivity: 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  968): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  968): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  968): Setting Dns servers for network 101 to [/192.168.1.1]
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/Nat464Xlat(  968): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  968): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
,E/WifiStateMachine(  968): handleMessage: X
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Connected
D/ConnectivityService(  968): currentScore = 0, newScore = 20
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  968): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/usbnet  (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
D/PMS     (  968): acquireWL(353e2087): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/ConnectivityService(  968): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/ResourcesManager( 1628): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
D/PMS     (  968): releaseWL(353e2087): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1221): dataConnected: false/false
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
D/DATA_ICON( 1221): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/DATA_ICON( 1221): dataConnected: false/false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  968): identical MTU - not setting
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/Nat464Xlat(  968): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
E/WifiStateMachine(  968): processMsg: ConnectedState
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  968):  ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  968):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: DriverStartedState
,E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
E/WifiStateMachine(  968): handleMessage: X
,D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524295
D/ConnectivityService(  968): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ],
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524295
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/art     (  968): Explicit concurrent mark sweep GC freed 47155(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.529ms total 172.876ms
,D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
,V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateIfacesLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WISPrService( 5994): >>>>>WISPrService start isConnected = true<<<<<,
,D/VoldConnector(  968): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): handleMessage: X
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6758): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/WISPrService( 5994): >>>>>WISPrService start isConnected = true<<<<<
,I/GAv4    ( 6758): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6758):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6758):   adb logcat -s GAv4
D/VoldConnector(  968): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
D/SMSBackup( 6791): SMSBackupAgentService started
W/ContextImpl( 6758): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/SMSBackup( 6791): Checking restore status
,D/SMSBackup( 6791): Restore complete
D/SMSBackup( 6791): cancelCheckAlarm
,D/SMSBackup( 6791): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  968): killProcessQuiet, pid=6321
I/ActivityManager(  968): Killing 6321:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/VoldConnector(  968): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
W/ContextImpl( 6758): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6758): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/VoldConnector(  968): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/asset   ( 1628): Copying FileAsset 0x556ee8be70 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL true Token 3,
,D/PhoneApp( 1568): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1568): -- N1 =0
D/PhoneApp( 1568): -- N2 =0
D/PhoneApp( 1568): -- N3 =0
,E/Prism.WidgetManager( 1628): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1628): onLoadItems() -
I/Prism.ItemManager( 1628): loadItems() com.htc.launcher.pageview.WidgetManager@2b9b4915 -
,I/ActivityManager(  968): Recipient 6321,
,D/PMS     (  968): acquireWL(219ea0d9): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{1000},
V/AlarmManager(  968): sending alarm PendingIntent{1ca47f0b: PendingIntentRecord{1e41a1e8 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454419099294, Int=20000
,W/GAv4    ( 6758): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6758): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6758): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6758): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6758): [apache-http] Connection GC has been deprecated!
,D/Messaging( 6676): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6676): networkCode: 
,D/MessageCustFlag( 6676): sku_id=118
D/MmsConfig( 6676): SIE smsPri: null
D/MmsConfig( 6676): networkCode: 
,D/MmsConfig( 6676): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 6676): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 6676): 
D/MmsAsyncWorkHandler( 6676): HM tk = 20001
,D/ReportIndicatorCache( 6676): MSG_QUERY_REPORTS >>
D/SettingsManager( 6676): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2d8e2301
D/Messaging( 6676): mNeedToUpdateDate2 start
,D/DraftCache( 6676): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6676): [DraftCache/1] refresh
I/WebViewFactory( 6758): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/AccFlag ( 1568): sku_id=118
,I/Messaging( 6676): mccmnc> 
,D/DraftCache( 6676): [DraftCache/166] rebuildCache
D/MmsConfig( 6676): networkCode: 
,D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 98
,D/MmsSmsV2Provider( 1568):  slotId = -1000
D/MmsSmsV2Provider( 1568): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null,
,D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/MmsSmsV2Provider( 1568):  slotId = -1000
D/MmsSmsV2Provider( 1568): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6676): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
D/MmsSmsV2Provider( 1568):  slotId = -1000
D/MmsSmsV2Provider( 1568): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 6676): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/Jerry   ( 1568): URI_DRAFT
,D/MessageCustFlag( 6676): sense_version=6.0
D/Jerry   ( 6676): start to preload cursor >>>>>>>
D/DraftCache( 6676): hasDraft() = false mNeedNotifyChange = true
D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
D/MmsSmsV2Provider( 1568):  slotId = -1000
D/MmsSmsV2Provider( 1568): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 6676): [DraftCache/166] rebuildCache time: 8
D/MmsAsyncWorkHandler( 6676): 
D/MmsAsyncWorkHandler( 6676): HM tk = 20002
D/PhoneStorageUtil( 6676): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6676): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6676): createReceiver
,D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 98,
D/AccFlag ( 1568): sku_id=118
D/TelephUtils( 1568): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
V/MmsProvider( 1568): Update uri=content://mms, match=0
V/MmsProvider( 1568): selection=st=129 AND m_type!=134
D/Messaging( 6676): mNeedToUpdateDate2: false
,D/Messaging( 6676): Reset downloading state: 0
V/MmsSystemEventReceiver( 6676): TransactionService is going to be woken up.
,D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/MmsSmsV2Provider( 1568):  slotId = -1000
,V/TransactionService( 6676): 1-Creating TransactionService
,D/Messaging( 6676): ViewCache CreatePreload
,D/Messaging( 6676): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 98
D/AccFlag ( 1568): sku_id=118
I/LibraryLoader( 6758): Time to load native libraries: 20 ms (timestamps 8638-8658)
,I/LibraryLoader( 6758): Expected native library version number "",actual native library version number "",
,V/TransactionService( 6676): onStartCommand: 1
D/MmsSystemEventReceiver( 6676): unRegisterForConnectionStateChanges
V/TransactionService( 6676): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6676): Loading previous transactions.
D/Cust_MMSMS( 6676): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6676): def_index: 0,
D/MsgPreferenceUtils( 6676): globalIndex = 1
,D/TelephUtils( 1568): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/AccFlag ( 1568): device_type: 1
D/MsgPreferenceUtils( 6676): phone state: true
D/MsgPreferenceUtils( 6676): sd state: false
D/MsgPreferenceUtils( 6676): vIndex = 0
,D/TransactionService( 6676): Force clearing mTransactionList
,D/TransactionService( 6676): Force set service start id to 1
V/TransactionService( 6676): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6676): unRegisterForConnectionStateChanges
,D/TransactionService( 6676): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6676): Destroying TransactionService
,V/TransactionService( 6676): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/WebViewChromiumFactoryProvider( 6758): Binding Chromium to main looper Looper (main, tid 1) {214801af}
I/LibraryLoader( 6758): Expected native library version number "",actual native library version number ""
,I/chromium( 6758): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6758): Initializing chromium process, singleProcess=true
,W/art     ( 6758): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6758): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6758): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6758): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6758): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6758): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6758): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6758): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6758): Local Branch: 
I/Adreno-EGL( 6758): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6758): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6758):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6758): Requires BLUETOOTH permission,
,I/NSApplication( 6758): Starting up...,
,I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6888 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  968): killProcessQuiet, pid=5717
I/ActivityManager(  968): Killing 5717:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  968): Recipient 5717,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131168,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DefaultState,
E/WifiStateMachine(  968):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): handleMessage: X
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8,
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8
D/WIFI_ICON( 1221): WifiActivity: 2
E/WifiTrafficPoller(  968):  packet count Tx=151 Rx=238
E/WifiTrafficPoller(  968): notifying of data activity 2
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  968): releaseWL(238a96f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  968): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=73.5, 0.0, 0.0  rx=118.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1574813111] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=73.5, 0.0, 0.0  rx=118.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1574813109] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1320): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1320): environment dirty rate=0 [1][0][0]
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72,
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
E/WifiStateMachine(  968): BroadcastRSSIForIMS, newrssi =-59 , oldRssi= -200
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=38.75 txretriesrate=0.00 rxrate=60.00 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
,E/WifiStateMachine(  968): handleMessage: X
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,I/ActivityManager(  968): Killing 5471:com.htc.mediamanager/u0a28 (adj 15): empty #17,
D/Process (  968): killProcessQuiet, pid=5471
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/art     ( 6087): Suspending all threads took: 9.758ms,
,I/ActivityManager(  968): Recipient 5471
,E/WifiStateMachine(  968): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968): handleMessage: E msg.what=131143
D/PMS     (  968): releaseWL(219ea0d9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:83 rssi=-59 f=2412 sc=60 link=72 tx=38.8, 0.0, 0.0  rx=60.0 list=2412 [on:0 tx:0 rx:0 period:181] from screen [on:0 period:-1574812922]
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:83 rssi=-59 f=2412 sc=60 link=72 tx=38.8, 0.0, 0.0  rx=60.0 list=2412 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1574812920]
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=38.75 rxSuccessRate=60.00 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-59
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN with age=71981 interval=40000 maxinterval=300000
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN try full band scan age=71981 interval=40000 maxinterval=300000
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  968): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  968): has c0:ff:d4:d3:aa:48 freq=2412 age=188 ?=true
E/WifiStateMachine(  968): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1320): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1320): wpa_supplicant_scan enter
D/wpa_supplicant( 1320): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1320): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1320): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1320): WPS:  * Request Type
D/wpa_supplicant( 1320): WPS:  * Config Methods (4288)
,D/wpa_supplicant( 1320): WPS:  * UUID-E
D/wpa_supplicant( 1320): WPS:  * Primary Device Type
D/wpa_supplicant( 1320): WPS:  * RF Bands (3)
D/wpa_supplicant( 1320): WPS:  * Association State
D/wpa_supplicant( 1320): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1320): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1320): WPS:  * Manufacturer
D/wpa_supplicant( 1320): WPS:  * Model Name
D/wpa_supplicant( 1320): WPS:  * Model Number
D/wpa_supplicant( 1320): WPS:  * Device Name
D/wpa_supplicant( 1320): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1320): P2P: * P2P IE header
D/wpa_supplicant( 1320): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1320): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1320): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1320): wlan0: Add radio work 'scan'@0x559e12b680
D/wpa_supplicant( 1320): wlan0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1320): wlan0: Starting radio work 'scan'@0x559e12b680 after 0.000031 second wait
D/wpa_supplicant( 1320): wlan0: nl80211: scan request
D/wpa_supplicant( 1320): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1320): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1320): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1320): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1320): wlan0: Own scan request started a scan in 0.000060 seconds
I/wpa_supplicant( 1320): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  968): [1,454,419,100,427 ms] noteScanstart no scan source
E/WifiStateMachine(  968): handleMessage: X
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED ,
,D/wpa_supplicant( 1320): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1320): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1320): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1320): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1320): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1320): wlan0: Scan completed in 0.062187 seconds
D/wpa_supplicant( 1320): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1320): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1320): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1320): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1320): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1320): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1320): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1320): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-87
D/wpa_supplicant( 1320): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1320): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1320): wlan0: Scan-only results received
D/wpa_supplicant( 1320): wlan0: Radio work 'scan'@0x559e12b680 done in 0.062889 seconds
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  968): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  968): handleMessage: E msg.what=147461
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1320): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  968): [1,454,419,100,493 ms] noteScanEnd no scan source
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1320): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  968): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@29766114 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  968): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  968): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  968): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  968):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  968): 01ABC c2:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  968): Gonzos 38:f8:89:11:e9:11 rssi=-87 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  968): ageScanResultsOut delay 40000 size 4 now 1454419100495
E/WifiAutoJoinController (  968): newSupplicantResults size=4 known=1 true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1320): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  968): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  968): ssid=NG700
E/WifiAutoJoinController (  968): id=0
E/WifiAutoJoinController (  968): mode=station
E/WifiAutoJoinController (  968): pairwise_cipher=CCMP
E/WifiAutoJoinController (  968): group_cipher=CCMP
E/WifiAutoJoinController (  968): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  968): wpa_state=COMPLETED
E/WifiAutoJoinController (  968): ip_address=192.168.1.130
E/WifiAutoJoinController (  968): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  968): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  968): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  968): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  968): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-59,-127) num=(1,0)
E/WifiAutoJoinController (  968): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  968): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-59 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  968): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  968): Done attemptAutoJoin status=0
E/WifiConfigStore(  968):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  968): handleMessage: X
,I/jxcore-log( 6469): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6469): 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8
E/WifiTrafficPoller(  968):  packet count Tx=151 Rx=239
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  968): notifying of data activity 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 6469): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6469): 
,I/jxcore-log( 6469): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6469): 
,I/jxcore-log( 6469): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 6469): 
,I/jxcore-log( 6469): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6469): 
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
,D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8,
D/WIFI_ICON( 1221): WifiActivity: 2
E/WifiTrafficPoller(  968):  packet count Tx=152 Rx=239
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 2
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: true
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  968): acquireWL(ae9ac74): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/PMS     (  968): acquireWL(2dc1f59d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 968 1000 null
,D/PMS     (  968): releaseWL(2dc1f59d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  968): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ConnectivityHelper( 1628): [onReceive] WIFI(1): CONNECTED
D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,E/GpsLocationProvider(  968): No APN found to select.
,D/PMS     (  968): releaseWL(ae9ac74): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/HtcWifiWanDetect(  968): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
,I/NetworkMonitor( 6715): type=WIFI subType= reason=null isConnected=true,
,D/MdScPhnSt( 6580): [20.1.]  listen tmrbb8,
,V/MusicLeanback( 6715): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/AutoSetting( 1540): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6421): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6421): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1540): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1540): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1540): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1540): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1540): service - handleMessage() setting current location null
,D/PMS     (  968): acquireWL(282b5d3f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
D/MdScDataSum( 6580): [20.1.] summary 118:p1 ignore
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4465, uid=10024, userID:0
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1833): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1833): [NET] android_getaddrinfo_proxy+
D/libc    ( 1833): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605,
I/iu.Environment( 4465): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4465): num queued entries: 0
I/iu.UploadsManager( 4465): num updated entries: 0
,I/iu.SyncManager( 4465): NEXT; no task
,D/ChimeraCfgMgr( 4465): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4465): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/libc    ( 6638): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 6638): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6638): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6638): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 6638): [NET] android_getaddrinfo_proxy+
D/libc    ( 6638): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1833): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6638): [NET] android_getaddrinfo_proxy-, success,
,I/GLSUser ( 1833): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1833): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1833): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1833): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
,W/Kids    ( 4465): [AccountUtils] Account not ready,
W/Kids    ( 4465): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4465): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4465): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4465): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4465): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4465): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4465): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4465): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4465): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4465): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4465): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4465): 	at java.lang.Thread.run(Thread.java:818)
I/Babel   ( 6638): connection state changed from DISCONNECTED to CONNECTED
,D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1326): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
,D/GCM     ( 1833): Connected
D/PMS     (  968): acquireWL(3db13d10): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(282b5d3f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(3db13d10): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(f721009): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1833): Message class com.google.f.a.a.p
,D/PMS     (  968): releaseWL(f721009): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/Process (  968): killProcessQuiet, pid=6377
I/ActivityManager(  968): Killing 6377:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6377
,D/Process (  968): killProcessQuiet, pid=6612
I/ActivityManager(  968): Killing 6612:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8,
D/WIFI_ICON( 1221): WifiActivity: 3
E/WifiTrafficPoller(  968):  packet count Tx=166 Rx=253
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 3
,I/ActivityManager(  968): Recipient 6612
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=38.8, 0.0, 0.0  rx=60.0 bcn=0 [on:0 tx:0 rx:0 period:2816] from screen [on:0 period:-1574810100] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=38.8, 0.0, 0.0  rx=60.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1574810099] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1320): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1320): environment dirty rate=23 [17][4][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
,E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=27.38 txretriesrate=0.00 rxrate=37.50 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
E/WifiStateMachine(  968): handleMessage: X
,D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3,
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  968): acquireWL(3efc142f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6715 10159 null,
,I/PMS     (  968): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1fda091
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/PMN     (  968): goingToSleep
W/SensorService(  968): disable: get sensor name = Accelerometer Sensor
W/SensorService(  968): pid=968, uid=1000
W/SensorService(  968): Active sensors: size = 4
,W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1fda091, eanble = 0, strlen(mName) = 90
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  968): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@b0554d
W/SensorService(  968): Listener[1] = com.htc.smartdim.sensor_eye@31d33cfb
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/PMS     (  968): mWirelessDisplayManager is null
,D/PMS     (  968): acquireWL(1e3c74d4): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 968 1000 null
,W/PMS     (  968): mWirelessDisplayManager is still null
W/PMN     (  968): goingToSleep done
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/PMS     (  968): Sleeping (uid 1000)...
D/XAN-DPS (  968): prepareColorFade 1
D/PMS     (  968): releaseWL(1e3c74d4): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  968): ACTION_SCREEN_ON
W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/AlarmManager(  968): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  968): [AlarmQueuing] done recovering
I/AlarmManager(  968): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  968): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 25
,E/WifiTrafficPoller(  968):  packet count Tx=167 Rx=253
E/WifiTrafficPoller(  968): notifying of data activity 2
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=141 rxSum=123} preTxRxSum={txSum=141 rxSum=123}
,D/WifiDataStallTracker(  968): updateDataStallInfo: NONE
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  968): handleMessage: E msg.what=131167,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0,
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
I/Adreno-EGL(  968): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  968): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  968): Build Date: 03/09/15 Mon
I/Adreno-EGL(  968): Local Branch: 
I/Adreno-EGL(  968): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  968): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  968):                  d74aa161a12b9c6fc6332151
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  968): processMsg: DefaultState
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1320): SET_SCREEN_ON:On
I/wpa_supplicant( 1320): htc_wext_set_keepalive +
I/wpa_supplicant( 1320): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1320): getPrivFuncNum +	
I/wpa_supplicant( 1320): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1320): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1320): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1320): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1320): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  968): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  968): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  968): handleScreenStateChanged Exit: true
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131154
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1320): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1320): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131127
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131129
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
,E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1320): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1320): wlan0: BLACKLIST CLEAR 
E/WifiStateMachine(  968): handleMessage: X
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=52 dispatchEvent: BLACKLIST CLEAR 
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6715, uid=10159, userID:0
,V/SRS_Proc(  401): ParamSet string: screen_state=on
D/PMS     (  968): releaseWL(3efc142f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
I/MusicLeanback( 6715): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6715): Stop autocaching.
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
,D/WifiController(  968): handleMessage: E msg.what=155650
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,D/NetworkPolicy(  968): updateScreenOn: false
,V/NetworkPolicy(  968): updateIfacesLocked()
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WIFI_ICON( 1221): WifiActivity: 2
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/WearableService( 4929): callingUid 10024, callindPid: 4929,
I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false)
,D/PMS     (  968): acquireWL(354ad4ca): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1906 10024 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  968): prepareColorFade done
D/PMS     (  968): acquireWL(1bee563b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1906 10024 WorkSource{10024 com.google.android.gms}
D/XAN-DPS (  968): setBrightness to 0
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@b0554d,
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = CM32181 Light sensor
,I/DisplayManagerService(  968): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/DotMatrix( 1326): [EventService]  onDisplayChanged: 0
V/ActivityManager(  968): Display changed displayId=0
D/PMS     (  968): releaseWL(354ad4ca): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/SensorService(  968): pid=968, uid=1000
W/SensorService(  968): Active sensors: size = 3
D/DotMatrix( 1326): [EventService] mbHDMIConnect: false, mCoverOn:false
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@b0554d, eanble = 0, strlen(mName) = 65
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.smartdim.sensor_eye@31d33cfb
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  968): releaseWL(1bee563b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,I/ActivityManager(  968): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6947 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/AlarmManager(  968): ACTION_SCREEN_OFF,
I/AlarmManager(  968): [AlarmQueuing] screen off now: 
E/GmsUtils( 6715): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/AlarmManager(  968): [AlarmQueuing] data connection: true
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 26
I/AlarmManager(  968): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  968): stopDataStallAlarm 
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 4
E/GmsUtils( 6715): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/WifiStateMachine(  968): handleMessage: E msg.what=131167
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
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
D/wpa_supplicant( 1320): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1320): SET_SCREEN_ON:Off
I/wpa_supplicant( 1320): htc_wext_set_keepalive +
I/wpa_supplicant( 1320): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1320): getPrivFuncNum +	
I/wpa_supplicant( 1320): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1320): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1320): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1320): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1320): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  968): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  968): handleScreenStateChanged Exit: false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131154
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  968): handleMessage: X
V/SRS_Proc(  401): ParamSet string: screen_state=off
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  968): handleMessage: E msg.what=155651
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,D/NetworkPolicy(  968): updateScreenOn: false
V/NetworkPolicy(  968): updateIfacesLocked()
,D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@177ee84b, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  968): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  968): pid=1221, uid=10041,
W/SensorService(  968): Active sensors: size = 4
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@177ee84b, eanble = 1, strlen(mName) = 57
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  968): Listener[0] = com.htc.smartdim.sensor_eye@31d33cfb
W/SensorService(  968): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@177ee84b,
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1326): [EventService] getTotalRam: 1842 Mb
D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,W/ContextImpl( 6947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/ContactMessageStore( 1568): start background delete task...
I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1568): size: 0 , 0
D/ContactMessageStore( 1568): Background delete complete
,D/PMS     (  968): acquireWL(d621b17): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1906 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(d621b17): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 6947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  968): acquireWL(27f308ed): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1906 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(27f308ed): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 6947): MY_DEBUG = false,
,D/SmartSyncUtils( 6947): isEpsOn(), nState = 0,
,D/PMS     (  968): acquireWL(23813322): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6947 1000 null,
D/AutoSetting( 1540): service - mHandler: cancel location update
D/AutoSetting( 1540): service -           changes count: 0
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145)
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
I/RemoteViews( 1221): apply : com.htc.updater 0 11 0 36
,D/SurfaceControl(  968): Excessive delay in setPowerMode(): 292ms
D/PMS     (  968): Setting HAL interactive mode to false
D/PMS     (  968): Setting HAL interactive mode to false done
D/PMS     (  968): Setting HAL auto-suspend mode to true
D/PMS     (  968): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  968): screenObserver, isScreenOn=false,
D/SmartDim(  968): Init customizeScreenOffDelayClass error
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0,
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/InputMethodManagerService(  968): Disable input method client, pid=6469
I/InputMethodManager( 6469): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{32d08fe2 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@30030f2c
,D/HABCtrl (  968): TPE algorithm. remove timeout.
,D/PMS     (  968): acquireWL(29e351b3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
,I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(29e351b3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/InputManager(  968): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 5
D/PMS     (  968): OOBE c monitor 11
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/NfcService( 1586): ScreenObserver: OFF
D/PMS     (  968): releaseWL(23813322): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/NfcService( 1586): applyRouting - 0
I/HtcPowerSaver(  968): << updateStatus
,D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
D/PMS     (  968): acquireWL(3c208370): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1586 1027 null
D/NfcService( 1586): applyRouting -2
D/NfcService( 1586): applyRouting
D/NfcService( 1586): Ignore this applyRouting...
D/PMS     (  968): releaseWL(3c208370): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 27 num clients 8
,W/ContextImpl( 6947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUI ( 1221): closing low battery warning: level=100
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 6947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6947): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6947): isEpsOn(), nState = 0
,W/ContextImpl( 6947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@31d33cfb
,W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  968): disable: get sensor name = Accelerometer Sensor,
I/ClockController( 1221): stop clock update:screen off
I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/SensorService(  968): pid=968, uid=1000,
W/SensorService(  968): Active sensors: size = 3
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@31d33cfb, eanble = 0, strlen(mName) = 36
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@177ee84b
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  968): pid=968, uid=1000,
W/SensorService(  968): Active sensors: size = 2
E/ActivityThread(  968): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@38a7a118 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  968): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@38a7a118 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@31d33cfb, eanble = 0, strlen(mName) = 36
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@177ee84b
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  968): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@31d33cfb
,D/SmartSyncUtils( 6947): getMobilePolicyEnabled, result = true
,D/WifiService(  968): New client listening to asynchronous messages,
E/WifiTrafficPoller(  968): ADD_CLIENT: 9
,I/PowerUsageList:PowerUsageHelper( 6947): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6947): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:PowerUsageHelper( 6947): MY_DEBUG = false,
,D/Process (  968): killProcessQuiet, pid=6018,
I/ActivityManager(  968): Killing 6018:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6018
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 27 num clients 9
,D/PMS     (  968): releaseWL(1a96aacb): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1574807086] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1574807083] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): handleMessage: X,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:344] from screen [on:0 period:-1574806738] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1574806736] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): handleMessage: X
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,I/jxcore-log( 6469): Test app app.js loaded,
I/jxcore-log( 6469): 
,I/chromium( 6469): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6469): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f50df5 added. We now have 1 listener(s)
,D/BluetoothAdapter( 6469): 540601917: getState(). Returning 12
,I/jxcore-log( 6469): BLE advertisement is supported
I/jxcore-log( 6469): 
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 5,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/ActivityManager(  968): Killing 5626:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=5626
W/art     ( 5626): No such thread id for suspend: 17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5626,
,D/ContactMessageStore( 1568): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1568): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  968): acquireWL(3837560f): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
V/AlarmManager(  968): sending alarm PendingIntent{2a62669c: PendingIntentRecord{3fd168a5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142952, Int=0
,D/PMS     (  968): releaseWL(3837560f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/AutoSetting( 1540): service - handleMessage() stop self,
,D/AutoSetting( 1540): service - onDestroy() END,
D/AutoSetting( 1540): service - handleMessage() quit looper
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  968): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  968): acquireWL(eaa047a): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 968 1000 null
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 12(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  968): [handleDownloadXtraData] calling native_inject_xtra_data,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131165,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: DefaultState
,E/WifiStateMachine(  968):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): handleMessage: X
,D/GpsLocationProvider(  968): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  968): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  968):  [handleDownloadXtraData]inject done.
D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  968): acquireWL(2ec3ee46): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/PMS     (  968): releaseWL(eaa047a): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  968): releaseWL(2ec3ee46): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131326,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState what:131326 2 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  968): handleMessage: X
,D/PMS     (  968): acquireWL(2c29f807): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
,I/BatteryService(  968): n_update end
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): releaseWL(2c29f807): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  968): processMsg: DeviceActiveState
D/HtcPowerSaver(  968): updateBatteryInfo
D/WifiController(  968): processMsg: StaEnabledState
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: DefaultState
D/PMS     (  968): runPSCheck
D/WifiController(  968): handleMessage: X
D/HtcPowerSaver(  968): Checking...
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  968): >> updateStatus
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1568): switchBindHtcMsgCursor: null,
,D/PMS     (  968): acquireWL(33daed34): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
,V/AlarmManager(  968): sending alarm PendingIntent{20a6d473: PendingIntentRecord{3fb5af30 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=148951, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{32b5075d: PendingIntentRecord{e40a8d2 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454419157511, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{29640da3: PendingIntentRecord{ad3a8a0 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202851, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{253fbc59: PendingIntentRecord{d5c801e com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190636, Int=0
,D/PMS     (  968): acquireWL(149fe0ff): PARTIAL_WAKE_LOCK  *backup* 0x1 968 1000 null
,D/PMS     (  968): acquireWL(2daaecc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  968): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  968): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  968): releaseWL(149fe0ff): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  968): releaseWL(33daed34): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/art     (  968): Explicit concurrent mark sweep GC freed 41442(2MB) AllocSpace objects, 5(1100KB) LOS objects, 33% free, 18MB/28MB, paused 1.977ms total 165.765ms
D/PMS     (  968): acquireWL(1626c515): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2daaecc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  968): releaseWL(1626c515): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(27daf0f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(27daf0f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(3ae0b64): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(3ae0b64): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): acquireWL(beb81cd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(660ea82): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(28f279d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(beb81cd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1833): Vacuum at: now=1454419194380 tag=VacuumService,
,I/GoogleURLConnFactory( 1833): Using platform SSLCertificateSocketFactory,
,D/PMS     (  968): releaseWL(660ea82): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(32372cce): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1833): No account for auth token provided,
,D/PMS     (  968): releaseWL(32372cce): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(267907ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(267907ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1833): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1833): [NET] android_getaddrinfo_proxy+
D/libc    ( 1833): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1833): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1833): No account for auth token provided,
,W/Uploader( 1833): No account for auth token provided,
,W/Uploader( 1833):  no longer exists, so no auth token.,
,W/Uploader( 1833): No account for auth token provided
,I/GLSUser ( 1833): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1833): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1833): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1833): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40,
,D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1326): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1833): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1833): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1833): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1833): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1833): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1833): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  968): releaseWL(28f279d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(4f11983): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(4f11983): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(ebff700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(ebff700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
,D/HtcAppUPService( 1540): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@31259ffd
D/Process (  968): killProcessQuiet, pid=5938,
I/ActivityManager(  968): Killing 5938:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5938
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  968): acquireWL(efe5b39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(efe5b39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  968): updateBatteryInfo
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  968): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  968): >> updateStatus
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): processMsg: DeviceActiveState,
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  968): acquireWL(292e657e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(292e657e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): handleMessage: E msg.what=155652
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  968): processMsg: DefaultState
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): handleMessage: X
I/HtcPowerSaver(  968): << updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1320): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1320): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1320): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  968): acquireWL(2921cadf): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
V/AlarmManager(  968): sending alarm PendingIntent{20a6d473: PendingIntentRecord{3fb5af30 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=208952, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{25e071f5: PendingIntentRecord{1bc75b8a com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454419331979, Int=0
,D/WeatherUtility( 1221): Weather sync is On
D/PMS     (  968): releaseWL(2921cadf): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  968): acquireWL(288235fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(288235fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/HtcPowerSaver(  968): updateBatteryInfo
D/WifiController(  968): processMsg: DeviceActiveState
D/PMS     (  968): runPSCheck
D/WifiController(  968): processMsg: StaEnabledState
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): processMsg: DefaultState
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  968): acquireWL(2705a618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(2705a618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0,
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: StaEnabledState
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): processMsg: DefaultState
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): handleMessage: X
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  968): acquireWL(24933871): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(24933871): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
,D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PMS     (  968): runPSCheck
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  968): Checking...
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  968): >> updateStatus
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  968): battery changed pluggedType: 2
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): handleMessage: E msg.what=155652
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  968): acquireWL(647a656): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
,I/BatteryService(  968): n_update end
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): releaseWL(647a656): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  968): processMsg: DeviceActiveState
D/HtcPowerSaver(  968): updateBatteryInfo
D/WifiController(  968): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: DefaultState
D/PMS     (  968): runPSCheck
D/WifiController(  968): handleMessage: X
D/HtcPowerSaver(  968): Checking...
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  968): >> updateStatus
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1568): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1568): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1568): sku_id=118
,D/ContactMessageStore( 1568): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1568): start background delete task...
,D/ContactMessageStore( 1568): size: 0 , 0
,D/ContactMessageStore( 1568): Background delete complete
,D/PMS     (  968): acquireWL(3db436d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
,I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(3db436d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
,D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  968): updateBatteryInfo
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NotificationService(  968): plugged=true pluggin=true
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): Checking...,
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(2fbb0bc4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(2fbb0bc4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  968): updateBatteryInfo
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
D/NotificationService(  968): plugged=true pluggin=true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): processMsg: DefaultState
I/HtcPowerSaver(  968): << updateStatus
,D/WifiController(  968): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(2dd1eaad): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(2dd1eaad): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,D/PowerUI ( 1221): closing low battery warning: level=100
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  968): << updateStatus
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  968): acquireWL(26afd1e2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
V/AlarmManager(  968): sending alarm PendingIntent{20a6d473: PendingIntentRecord{3fb5af30 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=388952, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{19b6973: PendingIntentRecord{b3f2030 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941024, Int=0
,I/bt-btm  ( 3127): Received oneshot timer event complete
I/bt-btm  ( 3127): btm_ble_timeout
I/bt-btm  ( 3127): btm_gen_resolvable_private_addr
,D/PMS     (  968): acquireWL(1acf84a9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3127 1002 null
D/PMS     (  968): releaseWL(26afd1e2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1002}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/bt-btm  ( 3127): btm_ble_rand_enc_complete
I/bt-btm  ( 3127): btm_gen_resolve_paddr_low,
D/bt-smp  ( 3127): smp_encrypt_data
W/bt-smp  ( 3127): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3127): Plain text(LSB ~ MSB) = b8 d1 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3127): Encrypted text(LSB ~ MSB) = 3a 96 1b 4f d1 51 a6 1b 14 47 f8 11 66 e7 a0 fd 
I/bt-btm  ( 3127): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3127): Stopping oneshot timer
D/bt-btm  ( 3127): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  968): releaseWL(1acf84a9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  968): acquireWL(287d2a2e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(287d2a2e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  968): updateBatteryInfo
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
,D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  968): Checking...
I/HtcPowerSaver(  968): >> updateStatus
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  968): acquireWL(2db929cf): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{1000},
V/AlarmManager(  968): sending alarm PendingIntent{bf16f91: PendingIntentRecord{f0def6 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805055, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{20a6d473: PendingIntentRecord{3fb5af30 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=988951, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{7ae0f5c: PendingIntentRecord{af2c265 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1011451, Int=0
,I/ActivityManager(  968): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7005 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,V/AlarmManager(  968): sending alarm PendingIntent{1fb5bb3a: PendingIntentRecord{284893eb com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454419668608, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{16bac548: PendingIntentRecord{2d9fe095 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454419958483, Int=0,
,D/PMS     (  968): acquireWL(33521fe1): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(33521fe1): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  968): releaseWL(2db929cf): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PowerUsageList:PowerUsageHelper( 6947): MY_DEBUG = false
,D/PowerUsageService( 6947): repeat time = 1454420902578
,D/PMS     (  968): acquireWL(105aedf4): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1833): Message class com.google.f.a.a.i,
,D/PMS     (  968): releaseWL(105aedf4): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6947): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6947): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 7027): Error opening trace file: Permission denied (13),
I/dex2oat ( 7027): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7027): dex2oat: override thread count:4
,I/dex2oat ( 7027): dex2oat took 656.294ms (threads: 4),
,I/PushClient( 7005): ApplicationMonitor {11023632}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 7005): ApplicationMonitor {11023632}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 7005): ApplicationMonitor {11023632}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 7005): ApplicationMonitor {11023632}: logBasicAppInfo(): VersionCode:             148001224,
I/PushClient( 7005): ApplicationMonitor {11023632}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7005): ApplicationMonitor {11023632}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7005): ApplicationMonitor {11023632}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7005): ApplicationMonitor {11023632}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 7005): ApplicationMonitor {11023632}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7005): PnsModel {2038ee3d}: update(): Update registration caused by: alarm,
,I/PushClient( 7005): PnsConfigModel {2667d418}: <init>(): Use dm-client for provisioning.
,W/System.err( 7005): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 7005): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7005): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7005): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  968): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7034 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 7034): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7034 dbg=false s=true
,I/DeviceManagement( 7034): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 7034): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7034): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 7034): WorkflowService: Starting workflow service
,I/DeviceManagement( 7034): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2cd90be7] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7034): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7034): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7034): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7034): SessionStateController: Checking invariants...
,I/DeviceManagement( 7034): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,D/PMS     (  968): acquireWL(4320ed5): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{1000},
V/AlarmManager(  968): sending alarm PendingIntent{179366ea: PendingIntentRecord{361a4ddb com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454420004111, Int=0
,D/SmartSyncUtils( 6947): isEpsOn(), nState = 0
,D/PMS     (  968): releaseWL(4320ed5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  968): acquireWL(1f4e1078): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6947 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6947): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6947): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6947): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6947): SettingOnTime = 1454479200000, randomSettingOnTime = 1454478657000
,D/SmartSyncScreenOnOffTimeReceiver( 6947): SettingOffTime = 1454457600000, randomSettingOffTime = 1454460733000
D/SmartSyncScreenOnOffTimeReceiver( 6947): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6947): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6947): bNightModeTurnOffOnce = false
,D/PMS     (  968): releaseWL(1f4e1078): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/DeviceManagement( 7034): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7034): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7034): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2cd90be7],
,I/DeviceManagement( 7034): WorkflowService: Stopping workflow service
,D/Process (  968): killProcessQuiet, pid=6791,
I/ActivityManager(  968): Killing 6791:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6791,
,I/PushClient( 7005): PnsModel {2038ee3d}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  968): killProcessQuiet, pid=5994,
I/ActivityManager(  968): Killing 5994:com.android.settings/1000 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/WifiService(  968): Client connection lost with reason: 4
I/ActivityManager(  968): Recipient 5994
,D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0,
D/PMS     (  968): acquireWL(178fbc24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
D/UsbnetService(  968): BroadcastReceiver::onReceive+
I/BatteryService(  968): n_update end
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): releaseWL(178fbc24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED,
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  968): runPSCheck
D/WifiController(  968): handleMessage: E msg.what=155652
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): processMsg: DeviceActiveState,
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  968): acquireWL(3b5e438d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(3b5e438d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  968): updateBatteryInfo,
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
,D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): handleMessage: E msg.what=155652
,D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): processMsg: StaEnabledState
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(bc5e942): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(bc5e942): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  968): battery changed pluggedType: 2
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  968): handleMessage: E msg.what=155652
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): processMsg: DeviceActiveState
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(3b629d53): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(3b629d53): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  968): updateBatteryInfo
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
D/PMS     (  968): runPSCheck,
D/HtcPowerSaver(  968): Checking...
I/HtcPowerSaver(  968): >> updateStatus
,D/UsbnetService(  968): BroadcastReceiver::onReceive+,
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  968): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  968): << updateStatus
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  968): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
