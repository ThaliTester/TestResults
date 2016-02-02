#### Test 575312435db8e90_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiDataStallTracker(  949): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  949): updateDataStallInfo: mDataStallTxRxSum={txSum=191 rxSum=170} preTxRxSum={txSum=191 rxSum=170}
D/WifiDataStallTracker(  949): updateDataStallInfo: NONE
D/WifiDataStallTracker(  949): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  949):  packet count Tx=211 Rx=311
I/HtcModeClient( 3140): handler message = 4011
E/HtcModeClient( 3140): Check connection and retry 12 times.
,E/WifiStateMachine(  949): handleMessage: E msg.what=131155
E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1581596160] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581596159] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  949):  get link layer stats 0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  949): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  949): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.16 txretriesrate=0.00 rxrate=1.01 userTriggerdPenalty0
E/WifiStateMachine(  949):  good link -> stuck count =0
E/WifiStateMachine(  949):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  949):  isHighRSSI       ---> score=61
E/WifiStateMachine(  949): handleMessage: X
--------- beginning of system
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  949): RSSI current: 3 new: -60, 3
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/cutils-trace( 6401): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6401): ====startRecUseTime====
D/htc.customization.log.level( 6401):  is 
W/CustomizationLogLevel( 6401): Level value is invalid, use default level 2
D/CustomizationManager( 6401):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 6401): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6401): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6401): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6401): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6401): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6401): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6401): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6401): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6401): Parsing tag category name = system
I/CustomizationCIDLoader( 6401): Parsing tag category name = application
I/CustomizationCIDLoader( 6401): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6401): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6401): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6401): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6401): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6401): add string-array item, value = 42507
I/CustomizationCIDLoader( 6401): add string-array item, value = 21902
I/CustomizationCIDLoader( 6401): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6401): add string-array item, value = 23420
I/CustomizationCIDLoader( 6401): add string-array item, value = 22299
I/CustomizationCIDLoader( 6401): add string-array item, value = 24002
I/CustomizationCIDLoader( 6401): add string-array item, value = 23210
I/CustomizationCIDLoader( 6401): add string-array item, value = 23205
I/CustomizationCIDLoader( 6401): add string-array item, value = 23806
I/CustomizationCIDLoader( 6401): add string-array item, value = 23430
I/CustomizationCIDLoader( 6401): add string-array item, value = 23408
I/CustomizationCIDLoader( 6401): add string-array item, value = 27205
I/CustomizationCIDLoader( 6401): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6401): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6401):  Read CID file spent 0.103 (s)
D/CustomizationManager( 6401):  All configurations done spent 0.104 (s)
D/PMS     (  949): acquireHCC(263c4721): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 949 1000 null
I/ActivityManager(  949): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6401 on display 0
D/PMS     (  949): acquireHCC(9dc8746): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 949 1000 null
W/asset   (  949): Copying FileAsset 0x55adb089c0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  949): acquireWL(2075345d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 949 1000 null
I/AnimationUtil(  949): isHTCRecent(ThaliTest/Recent screens.)/10
I/FeedHostManager( 1590): [onPause]
I/FeedProviderManager( 1590): onPause
I/FeedHostManager( 1590): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42bdfa8
I/SocialFeedProvider( 1590): +onPause
I/SocialFeedProvider( 1590): -onPause
W/HtcSystemUPManager(  949): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  949): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6419 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  455): Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 260us total 20.178ms
I/art     (  455): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 266us total 15.802ms
I/TrimMemoryManager( 1590): [trimMemory] 20
I/art     (  455): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 541us total 19.243ms
W/asset   ( 6419): Copying FileAsset 0xac46a6f0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/StatusBarManagerService(  949): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  949): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  949): hiding MENU key
E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  949):  packet count Tx=211 Rx=312
E/WifiTrafficPoller(  949): notifying of data activity 1
D/WIFI_ICON( 1214): WifiActivity: 1
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/WebViewFactory( 6419): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6419): Time to load native libraries: 10 ms (timestamps 1793-1803)
I/LibraryLoader( 6419): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6419): Binding Chromium to main looper Looper (main, tid 1) {24317c18}
I/LibraryLoader( 6419): Expected native library version number "",actual native library version number ""
I/chromium( 6419): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6419): Initializing chromium process, singleProcess=true
W/art     ( 6419): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6419): ApplicationContext is null in ApplicationStatus
W/chromium( 6419): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6419): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6419): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6419): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6419): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6419): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6419): Local Branch: 
I/Adreno-EGL( 6419): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6419): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6419):                  d74aa161a12b9c6fc6332151
D/BluetoothManagerService(  949): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  949): java.lang.Throwable: stack dump
D/BluetoothManagerService(  949): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a065382:true
W/System.err(  949): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  949): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  949): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  949): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6419): 47071684: getState(). Returning 12
W/art     ( 6419): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6419): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6419): CordovaWebView is running on device made by: HTC
W/art     ( 6419): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6419): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6419): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6419): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6419): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2b0d571d, mServedView=org.apache.cordova.engine.SystemWebView{22a71d92 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1d164363
I/InputMethodManagerService(  949): Disable input method client, pid=1590
D/StatusBarManagerService(  949): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  949): Enable input method client, pid=6419
I/PhoneStatusBar( 1214): setImeWindowStatus(false,false)
D/PMS     (  949): releaseWL(2075345d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  949): Displayed com.test.thalitest/.MainActivity: +832ms
W/XT9_C   ( 1400): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1400): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6419): Cannot call determinedVisibility() - never saw a connection for the pid: 6419
D/JsMessageQueue( 6419): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6419): JniHelper::setJavaVM(0xab2fe8f8), pthread_self() = -1402904488
,I/chromium( 6419): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1214): WifiActivity: 0
E/WifiTrafficPoller(  949):  packet count Tx=211 Rx=312
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  949): notifying of data activity 0
,D/PMS     (  949): releaseHCC(263c4721): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  949): releaseHCC(9dc8746): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6419): Initializing JXcore engine
W/jxcore-log( 6419): JXcore engine is ready
,W/jxcore-log( 6419): Starting JXcore engine,
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  949):  packet count Tx=211 Rx=312
,W/jxcore-log( 6419): Platform android,
W/jxcore-log( 6419): 
W/jxcore-log( 6419): Process ARCH arm
W/jxcore-log( 6419): 
,E/WifiStateMachine(  949): handleMessage: E msg.what=131155,
E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581593139] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581593138] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  949):  get link layer stats 0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  949): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  949): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.08 txretriesrate=0.00 rxrate=1.51 userTriggerdPenalty0
E/WifiStateMachine(  949):  good link -> stuck count =0
E/WifiStateMachine(  949):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  949):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  949): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  949): handleMessage: X
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 6419): JXcore Cordova bridge is ready!,
I/jxcore-log( 6419): 
W/jxcore-log( 6419): JXcore engine is started
,I/jxcore-log( 6419): Toggling radios to true,
I/jxcore-log( 6419): 
,D/BluetoothAdapter( 6419): enable(): BT is already enabled..!,
,D/WifiService(  949): New client listening to asynchronous messages
,E/WifiTrafficPoller(  949): ADD_CLIENT: 7
D/WifiManager( 6419): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  949): setWifiEnabled: true pid=6419, uid=10366
W/Settings:Agent(  949): MONITOR_LOG
E/WifiService(  949): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings:Agent(  949): name: wifi_on
I/WifiService(  949): isSprintWifiRestricted(): false
W/Settings:Agent(  949): value: 2
I/WifiService(  949): isMdmWifiRestricted(): false
W/Settings:Agent(  949): >> traceCallingStack()
W/Settings:Agent(  949): Process.myPid(): 949
W/Settings:Agent(  949): Process.myTid(): 2120
W/Settings:Agent(  949): Process.myUid(): 1000,
W/Settings:Agent(  949): 
W/Settings:Agent(  949): 
W/System.err(  949): java.lang.Throwable: stack dump
,W/System.err(  949): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  949): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  949): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  949): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  949): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  949): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  949): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  949): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  949): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  949): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  949): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  949): 
W/Settings:Agent(  949): << traceCallingStack(): 16(ms)
,D/WifiController(  949): handleMessage: E msg.what=155656
D/WifiController(  949): processMsg: DeviceActiveState
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): handleMessage: X
D/WifiManager( 6419): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  949): handleMessage: E msg.what=131145
D/WifiManager( 6419): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1324): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1324): wlan0: Cancelling scan request
D/wpa_supplicant( 1324): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1324): TDLS: Tear down peers
,D/wpa_supplicant( 1324): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 6419): Radios toggled
I/jxcore-log( 6419): 
,I/jxcore-log( 6419): My device name is: HTC-HTC One M8s,
I/jxcore-log( 6419): 
,D/wpa_supplicant( 1324): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1324): wlan0: Deauthentication notification
D/wpa_supplicant( 1324): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1324): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1324): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1324): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,E/wpa_supplicant( 1324): enter disconnect check
I/wpa_supplicant( 1324): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1324): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1324): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/Tethering(  949): interfaceLinkStateChanged wlan0, false
D/Tethering(  949): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  949): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  949): interfaceLinkStateChanged wlan0, false
D/Tethering(  949): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  949): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  949): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  949): TetherInterfaceSM: wlan0: enter UnavailableState
D/HTCRequest(  949): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  949): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/Tethering(  949): sendTetherStateChangedBroadcast 0, 0, 0
D/PMS     (  949): acquireWL(1d85248a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 949 1000 null
D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  949): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  949): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1324): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1324): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1324): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1324): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1324): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55935fff88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1324):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1324): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1324): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1324): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1324): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1324): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1324): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1324): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1324): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1324): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1324): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1324): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1324): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1324): EAPOL: External notification - portEnabled=0
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1324): EAPOL: External notification - portValid=0
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1324): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/HTCRequest(  949): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiDisplayAdapter(  949): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  949):     Client/Owner: Client
D/WifiDisplayAdapter(  949):     GroupId: 
D/WifiDisplayAdapter(  949):     Passphrase: 
D/WifiDisplayAdapter(  949):     SessionId: 0
D/WifiDisplayAdapter(  949):     IP Address: }
D/wpa_supplicant( 1324): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1324): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1324): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1324): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  949): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  949): handleMessage: new destination call exit/enter
E/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  949): invokeExitMethods: ConnectedState
E/WifiStateMachine(  949): WifiStateMachine: Leaving Connected state
D/WifiMonitor(  949): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState, =DISCONNECTED
D/WifiPerfLock(  949): release()
E/WifiStateMachine(  949): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  949): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  949): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  949): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  949): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  949): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  949): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  949): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1324): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1324): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1324): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1324): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1324): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  949): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1324): Power_Mode_Type mode = 0
I/wpa_supplicant( 1324): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  949): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  949): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1324): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  949): setDhcpActive: false
,D/PMS     (  949): releaseWL(1d85248a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  949): updateNetworkEnabledLocked()
V/NetworkPolicy(  949): updateNotificationsLocked()
,V/NativeCrypto( 1962): Read error: ssl=0x55ad36c930: I/O error during system call, Connection timed out
,D/libc    (  949): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
,D/TetherSettings( 5903): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5903): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5903): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5903): Cust_ConnectToPC   : spcsc>false
D/        ( 5903): Cust_ConnectToPC   : IPT>true
D/        ( 5903): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5903): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/libc    (  949): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  949): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  949): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  949): NetworkAgent != null
D/ConnectivityService(  949): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/SmartNS_Utility( 5903): hasRemovableStorageSlot: true
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/SmartNS_Utility( 5903): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/WIFI_ICON( 1214): WifiActivity: 1
D/SmartNS_NSReceiver( 5903): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  949):  packet count Tx=211 Rx=313
E/WifiTrafficPoller(  949): notifying of data activity 1
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ContextImpl( 5903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/ConnectivityService(  949): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  949): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  949): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  949): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1324): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1324): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1324): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WifiDataStallTracker(  949): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  949): stopDataStallAlarm 
D/wpa_supplicant( 1324): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1324): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  949): invokeEnterMethods: DisconnectingState
E/WifiDataStallTracker(  949): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiStateMachine(  949):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  949): Start Disconnecting Watchdog 1
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131146
E/WifiStateMachine(  949): processMsg: DisconnectingState
E/WifiStateMachine(  949):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1324): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1324): Fast associate: Old scan results
D/wpa_supplicant( 1324): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1324): wpa_supplicant_scan enter
D/wpa_supplicant( 1324): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1324): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1324): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1324): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1324): WPS:  * Request Type
D/wpa_supplicant( 1324): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1324): WPS:  * UUID-E
D/wpa_supplicant( 1324): WPS:  * Primary Device Type
D/wpa_supplicant( 1324): WPS:  * RF Bands (3)
D/wpa_supplicant( 1324): WPS:  * Association State
D/wpa_supplicant( 1324): WPS:  * Configuration Error (0),
D/wpa_supplicant( 1324): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1324): WPS:  * Manufacturer
D/wpa_supplicant( 1324): WPS:  * Model Name
D/wpa_supplicant( 1324): WPS:  * Model Number
D/wpa_supplicant( 1324): WPS:  * Device Name
D/wpa_supplicant( 1324): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1324): P2P: * P2P IE header
D/wpa_supplicant( 1324): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1324): P2P: * Listen Channel: Regulatory Class 81 Channel 6
E/WifiStateMachine(  949): handleMessage: X
D/wpa_supplicant( 1324): wlan0: Add radio work 'scan'@0x5593602680
D/wpa_supplicant( 1324): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  949): handleMessage: E msg.what=147460
E/WifiStateMachine(  949): processMsg: DisconnectingState
D/wpa_supplicant( 1324): wlan0: Starting radio work 'scan'@0x5593602680 after 0.000062 second wait
D/wpa_supplicant( 1324): wlan0: nl80211: scan request
D/wpa_supplicant( 1324): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1324): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1324): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1324): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1324): wlan0: Own scan request started a scan in 0.000123 seconds
E/WifiStateMachine(  949):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=104385
I/wpa_supplicant( 1324): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  949): processMsg: ConnectModeState
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  949): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  949):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=104386
E/WifiStateMachine(  949): ConnectModeState: Network connection lost 
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange(): SSID
E/WifiStateMachine(  949): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  949): handleMessage: new destination call exit/enter
D/WifiMonitor(  949): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  949): invokeExitMethods: DisconnectingState
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  949): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  949): DisconnectedState call setCountryCode()
E/WifiMonitor(  949): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  949): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  949):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1324): Pending scan scheduled - reject new request
E/WifiStateMachine(  949): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
D/WifiDisplayAdapter(  949): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  949):     Client/Owner: Client
D/WifiDisplayAdapter(  949):     GroupId: 
D/WifiDisplayAdapter(  949):     Passphrase: 
D/WifiDisplayAdapter(  949):     SessionId: 0
D/WifiDisplayAdapter(  949):     IP Address: }
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131101
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  949): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  949): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=147462
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=104392  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  949): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  949): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=104392  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131212
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  949): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131212
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  949): processMsg: DefaultState
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  949):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  949): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131212
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  949): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  949): handleMessage: X
D/WifiNetworkAgent(  949): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  949): handleMessage: E msg.what=147462
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=104412  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  949): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  949): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  949): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  949): NetworkAgent == null
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=104415  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  949): handleMessage: X
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/QuickSettingWifi( 1214): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/ConnectivityService(  949): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  949): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  949): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  949): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  949): Disconnected - quitting
D/Nat464Xlat(  949): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/WIFI    (  949): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  949): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  949):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  949): Removing idletimer
D/WIFI    (  949): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/PMS     (  949): acquireWL(2f8ecafb): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 949 1000 null
D/usbnet  (  949):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/CSLegacyTypeTracker(  949): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
E/WifiStateMachine(  949): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/usbnet  (  949): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  949): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1214): CM callback handler got msg 524292
E/ConnectivityService(  949): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/SecurityController( 1214): onLost 100
D/PMS     (  949): acquireWL(3ac71718): PARTIAL_WAKE_LOCK  NetworkStats 0x1 949 1000 null
I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:1
D/DATA_ICON( 1214): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/Tethering(  949): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/DATA_ICON( 1214): dataConnected: false/false
D/Tethering(  949): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  949): releaseWL(3ac71718): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:0
,I/art     (  949): Explicit concurrent mark sweep GC freed 51429(3MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 16MB/25MB, paused 1.559ms total 183.280ms
,D/PMS     (  949): acquireWL(245e5571): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
V/NetworkPolicy(  949): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/SmartNS_Utility( 5903): setISNotification
V/NetworkPolicy(  949): ensureActiveMobilePolicyLocked()
D/SmartNS_Utility( 5903): usb_cable_connect = 1
,V/NativeCrypto( 1962): SSL shutdown failed: ssl=0x55ad36c930: I/O error during system call, Broken pipe
D/NetworkPolicy(  949): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/SmartNS_Utility( 5903): usb_denied = 0
V/NetworkPolicy(  949): updateNetworkEnabledLocked()
I/SmartNS_PSService( 5903): usb notificaiton:true
V/NetworkPolicy(  949): updateIfacesLocked()
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
V/NetworkPolicy(  949): updateNotificationsLocked()
,V/NetworkPolicy(  949): updateNetworkEnabledLocked()
,I/ActionCombine( 5903): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,V/NetworkPolicy(  949): updateNotificationsLocked()
D/NetworkManagementService(  949): isBandwidthControlEnabled: doneSignal.getCount()= 0,
D/PMS     (  949): releaseWL(245e5571): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/SmartNS_Utility( 5903): usb_cable_connect = 1
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/SmartNS_Utility( 5903): usb_denied = 0
I/SmartNS_PSService( 5903): usb notificaiton:true
I/ActivityManager(  949): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6482 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/SmartNS_NSReceiver( 5903): Tethered state change:false isNSOpening:false,
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,I/RemoteViews( 1214): reapply : com.android.settings 3 36,
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency,
I/RemoteViews( 1214): reapply : com.android.settings 1 36
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/WISPrService( 5903): >>>>>WISPrService start isConnected = true<<<<<
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri,
E/WifiTrafficPoller(  949): ADD_CLIENT: 8
D/WifiService(  949): New client listening to asynchronous messages
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,E/WifiStateMachine(  949): handleMessage: E msg.what=131131
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  949): handleMessage: X
,W/WISPrService( 5903): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5903): trigger connection
D/WISPrService( 5903): continue
I/ActivityManager(  949): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6506 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms,
,D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5903): start DataConnection
D/libc    ( 5903): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5903): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5903): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5903): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5903): [NET] android_getaddrinfo_proxy+
D/libc    ( 5903): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  401): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  401): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5903): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL false Token 16 num clients 8,
,I/ActivityManager(  949): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6530 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/libc    ( 5903): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5903): [NET] android_getaddrinfofornet-, err=8
,D/WifiService(  949): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/WISPrService( 5903): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname,
,D/Process (  949): killProcessQuiet, pid=6158,
I/ActivityManager(  949): Killing 6158:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/ResourcesManager( 6506): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  949): Recipient 6158
,I/CalendarProvider2( 6506): Created com.android.providers.calendar.CalendarAlarmManager@108a377d(com.htc.providers.calendar.HtcCalendarProvider@f6fe672),
,D/CalendarProvider2( 6506): wait start:true
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false,
,D/CalendarProvider2( 6506): wait end:false
,I/ActivityManager(  949): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6559 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/MdScPhnSt( 6530): [841.2.]  listen tmrbb8
,D/MdProvGlob( 6482): add item 101 (2:g3d19) for 15:android.intent.action.ANY_DATA_STATE,
,W/ResourcesManager( 6559): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/MdProvGlob( 6482): remove item 101 (p3d6in59) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6530): [841.2.] summary 118:p3 ignore,
,D/MdProvGlob( 6482): remove item 101 (p3in12) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6482): remove item 101 (p3in6) for 15:android.intent.action.ANY_DATA_STATE
,D/Process (  949): killProcessQuiet, pid=6231,
I/ActivityManager(  949): Killing 6231:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 6231,
,I/Babel_SMS( 6559): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 6559): MmsConfig.loadMmsSettings
,I/ActivityManager(  949): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6591 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6559, uid=10112, userID:0
,W/HtcWrapAdjustableCursorFactory( 6591): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 6591): onCreate
,V/GetPrviateResource( 6591): GetPrviateResource
,V/GetPrviateResource( 6591): GetPrviateResource
D/MmsCustomizationProvider( 6591): query uri: content://htc-mms-customization/mms-ua/ua_string
,W/Settings( 6559): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
D/MessageCustFlag( 6591): sense_version=6.0
D/MmsCustomizationProvider( 6591): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/BTAccessoryUtil( 6591): createReceiver
,D/BTAccessoryUtil( 6591): registerReceiver return intent = null
,I/Babel_SMS( 6559): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6559): MmsConfig.loadFromDatabase
,D/MessageCustFlag( 6591): sku_id=118,
,D/HtcBuildUtils( 6591): getRATByHtcTelephonyCapability:1,
,W/SystemReader( 6591): Cannot find qct_8960_interface, use default value instead
,I/Babel_Crash( 6559): startup - clean
,E/Babel_SMS( 6559): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6559): MmsConfig.loadFromResources
,E/Babel_SMS( 6559): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6559): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel   ( 6559): deleted: false for 0
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL false Token 16 num clients 8,
,E/WifiDataStallTracker(  949): DATA_MONITOR_POLL false Token 2,
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6559, uid=10112, userID:0,
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6559, uid=10112, userID:0
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6559, uid=10112, userID:0
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6559, uid=10112, userID:0
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6559, uid=10112, userID:0,
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false
,W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc,
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false,
W/VideoCapabilities( 6559): Unsupported mime video/x-ms-wmv
,W/Utils   ( 6559): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 6559): Unsupported mime audio/qcelp,
D/FlexNetS( 6506): updateSvcAllowedInSettings:false
,W/AudioCapabilities( 6559): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6559): Unsupported mime audio/qcelp,
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false
,W/VideoCapabilities( 6559): Unsupported mime video/x-ms-wmv,
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6506): updateSvcAllowedInSettings:false
,I/VideoCapabilities( 6559): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc
,D/Process (  949): killProcessQuiet, pid=6255
I/ActivityManager(  949): Killing 6255:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 6255
,D/Process (  949): killProcessQuiet, pid=5737
I/ActivityManager(  949): Killing 5737:com.google.android.gm/u0a106 (adj 15): empty #18
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/HtcModeClient( 3140): handler message = 4011
,E/HtcModeClient( 3140): Check connection and retry 12 times. Stop service and kill this process.
,I/ActivityManager(  949): Recipient 5737
,D/PMS     (  949): acquireWL(baf6051): PARTIAL_WAKE_LOCK  *alarm* 0x1 949 1000 WorkSource{10024}
,D/HtcModeClient( 3140): Don't start project servcice
V/AlarmManager(  949): sending alarm PendingIntent{38aae0b6: PendingIntentRecord{33fd51b7 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=105648, Int=0
D/HtcModeClient( 3140): setEject: MEDIA_EJECT_STATE = true
D/PMS     (  949): acquireWL(3c4bbd24): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
I/vclib   ( 6559): onServiceConnected
W/Babel   ( 6559): Attempted to change video mute state without an active call.
D/HtcModeClient( 3140): connectState: CONNECTION_READY = false
D/SilentMusic( 3140): call stop
D/HtcModeClient( 3140): close connection
W/HtcModeClient( 3140): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3140): read the terminate packet, so break
,D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1962): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1962): [NET] android_getaddrinfo_proxy+
D/libc    ( 1962): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  949): releaseWL(baf6051): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  401): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  401): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1962): [NET] android_getaddrinfo_proxy-, NODATA
I/ActivityManager(  949): Killing 3140:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  949): killProcessQuiet, pid=3140
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  949): acquireWL(3c4bbd24): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  949): releaseWL(3c4bbd24): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/CalendarProvider2( 6506): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6506): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  949): Recipient 3140,
,I/ActivityManager(  949): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6621 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  949): Killing 5881:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  949): killProcessQuiet, pid=5881
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  949): Recipient 5881
,W/ResourcesManager( 6621): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6621): onCreate,
D/ProviderChangeReceiver( 6621): ---------------------------------------------------
D/ProviderChangeReceiver( 6621): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!,
I/ActivityManager(  949): Killing 6286:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  949): killProcessQuiet, pid=6286
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 6621): start to updateAlertNotification!
,I/ActivityManager(  949): Recipient 6286
,I/ActivityManager(  949): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6644 uid=10076 gids={50076, 9997} abi=arm64-v8a,
,D/PMS     (  949): acquireWL(177c5242): PARTIAL_WAKE_LOCK  *alarm* 0x1 949 1000 WorkSource{10076}
D/wpa_supplicant( 1324): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,V/AlarmManager(  949): sending alarm PendingIntent{20b5253: PendingIntentRecord{11198790 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454412322676, Int=60000
D/wpa_supplicant( 1324): wlan0: nl80211: New scan results available
D/PMS     (  949): releaseWL(177c5242): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/wpa_supplicant( 1324): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1324): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1324): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1324): wlan0: Scan completed in 2.047292 seconds
W/ContextImpl(  949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1324): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1324): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1324): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1324): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1324): wlan0: BSS: Add new id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 1324): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1324): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1324): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 c2:ff:d4:d3:aa:48]
D/wpa_supplicant( 1324): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1324): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1324): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1324): wlan0: Radio work 'scan'@0x5593602680 done in 2.049203 seconds
D/wpa_supplicant( 1324): wlan0: Selecting BSS from priority group 588
D/wpa_supplicant( 1324): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-52 wps
D/wpa_supplicant( 1324): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1324): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1324): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 1324): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1324): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1324): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1324):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1324): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
E/WifiMonitor(  949): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1324): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x5593601c00  current_ssid=0x0
D/wpa_supplicant( 1324): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1324): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1324): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1324): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1324): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1324): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1324): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 ,00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/WifiMonitor(  949): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiStateMachine(  949): handleMessage: E msg.what=147461
D/wpa_supplicant( 1324): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1324): TDLS: TDLS is allowed in the target BSS
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=37 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1324): wlan0: Add radio work 'connect'@0x5593602680
E/WifiStateMachine(  949): processMsg: DisconnectedState
D/wpa_supplicant( 1324): wlan0: First radio work item in the queue - schedule start immediately
W/WifiMonitor(  949): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1324): wlan0: Starting radio work 'connect'@0x5593602680 after 0.000149 second wait
I/wpa_supplicant( 1324): check if in concurrent case
I/wpa_supplicant( 1324): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  949):  DisconnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:79 bcn=0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:79 bcn=0
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:79 bcn=0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:79 bcn=0
D/WifiStateMachine(  949): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiMonitor(  949): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=38 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1324): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1324): wlan0: Cancelling scan request
D/wpa_supplicant( 1324): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1324): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1324): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1324): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1324): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1324): RSN: PMKSA cache search - network_ctx=0x5593601c00 try_opportunistic=0
D/wpa_supplicant( 1324): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1324): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1324): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1324): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1324): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1324): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1324): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1324): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1324): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1324): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1324): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1324): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1324): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1324): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1324): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1324): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1324): nl80211: Unsubscribe mgmt frames handle 0x888888dd1be89989 (mode change)
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 st,ate=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  949): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1324): nl80211: Subscribe to mgmt frames with non-AP handle 0x5593601100
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=0104
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=040a
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=040b
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=040c
D/WifiMonitor(  949): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=040d
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=090a
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=090b
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=090c
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=090d
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=0409506f9a09
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=7f506f9a09
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=0801
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=040e
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=06
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=0a07
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=0a11
D/wpa_supplicant( 1324): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593601100 match=0a1a
D/wpa_supplicant( 1324): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1324):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324):   * freq=2412
D/wpa_supplicant( 1324):   * freq_hint=2412
D/wpa_supplicant( 1324):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1324):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1324):   * WPA Versions 0x2
D/wpa_supplicant( 1324):   * pairwise=0xfac04
D/wpa_supplicant( 1324):   * group=0xfac04
D/wpa_supplicant( 1324):   * akm=0xfac02
D/wpa_supplicant( 1324):   * Auth Type 0
D/wpa_supplicant( 1324): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5593601c3a
D/wpa_supplicant( 1324): nl80211: Connect request send successfully
D/wpa_supplicant( 1324): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1324): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1324): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1324): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1324): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  949): [1,454,412,322,758 ms] noteScanEnd no scan source
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1324): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  949): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2f8dbb4a sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  949): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  949): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  949): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  949): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  949):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  949): Gonzos 38:f8:89:11:e9:11 rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  949): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  949): ageScanResultsOut delay 40000 size 4 now 1454412322764
E/WifiAutoJoinController (  949): newSupplicantResults size=4 known=1 true
D/HtcAlertService( 6621): No fired or scheduled alerts
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/HtcAlertUtils( 6621): -- cancelReminderNotification --
D/wpa_supplicant( 1324): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  949): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  949): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  949): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  949): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  949): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  949):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131213
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106456
E/WifiStateMachine(  949): processMsg: ConnectModeState
D/HtcAlertUtils( 6621): broadcastExistReminder!
E/WifiStateMachine(  949):  ConnectModeState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106457
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106457
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106459
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=147462
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=106460  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  949): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  949): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  949): setDetailed state send new extra info0x
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  949): NetworkAgent == null
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  949):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=106472  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  949): handleMessage: X
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:0
,D/SMSBackup( 6644): SMSBackupAgentService started,
D/SMSBackup( 6644): Checking restore status
,D/SMSBackup( 6644): Restore complete,
D/SMSBackup( 6644): cancelCheckAlarm
,D/SMSBackup( 6644): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  949): killProcessQuiet, pid=6310,
I/ActivityManager(  949): Killing 6310:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/wpa_supplicant( 1324): Wireless event: cmd=0x8c02 len=271
,I/wpa_supplicant( 1324): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1324): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1324): Wireless event: cmd=0x8c02 len=46
I/wpa_supplicant( 1324): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1324): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1324): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1324): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1324): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1324): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
D/Tethering(  949): interfaceLinkStateChanged wlan0, false
D/Tethering(  949): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  949): interfaceLinkStateChanged wlan0, false
D/Tethering(  949): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1324): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1324): nl80211: Connect event
D/Tethering(  949): interfaceLinkStateChanged wlan0, false
D/Tethering(  949): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1324): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1324): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1324): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1324): wlan0: Association info event
D/wpa_supplicant( 1324): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1324): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1324): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1324): wlan0: freq=2412 MHz
D/wpa_supplicant( 1324): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1324): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1324): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1324): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1324): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1324): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/Tethering(  949): interfaceLinkStateChanged wlan0, true
D/Tethering(  949): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1324): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1324): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
I/wpa_supplicant( 1324): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1324): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1324): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1324): TDLS: Remove peers on association
D/wpa_supplicant( 1324): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1324): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1324): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1324): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1324): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1324): EAPOL: enable timer tick
D/wpa_supplicant( 1324): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1324): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wp,a_supplicant( 1324): wlan0: Cancelling scan request
D/wpa_supplicant( 1324): wlan0: Process pending EAPOL frame that was received just before association notification
D/wpa_supplicant( 1324): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1324): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1324): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1324): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1324): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1324):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1324):   key_nonce - hexdump(len=32): 83 0e f5 18 cd 96 85 2d 79 03 c0 e3 f8 b3 f2 b7 84 77 fb 88 d3 59 50 86 61 52 ce bd d6 25 03 31
D/wpa_supplicant( 1324):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1324):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1324):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1324):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1324): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
V/Tethering(  949): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1324): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1324): RSN: msg 1/4 key data - hexdump(len=0):
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1324): WPA: Renewed SNonce - hexdump(len=32): 8a 4f d8 5c f7 e3 b6 13 7e da 95 02 07 0a cb 48 b9 56 62 70 b2 76 22 21 09 5e ca 94 ff 77 d0 f0
D/wpa_supplicant( 1324): WPA: Nonce1 - hexdump(len=32): 8a 4f d8 5c f7 e3 b6 13 7e da 95 02 07 0a cb 48 b9 56 62 70 b2 76 22 21 09 5e ca 94 ff 77 d0 f0
D/wpa_supplicant( 1324): WPA: Nonce2 - hexdump(len=32): 83 0e f5 18 cd 96 85 2d 79 03 c0 e3 f8 b3 f2 b7 84 77 fb 88 d3 59 50 86 61 52 ce bd d6 25 03 31
D/wpa_supplicant( 1324): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1324): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1324): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1324): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1324): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1324): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1324): WPA: Derived Key MIC - hexdump(len=16): a0 3e c8 73 4a d9 8c 32 4e 1b 17 99 6f 09 12 7a
I/wpa_supplicant( 1324): htc_wext_set_keepalive +
I/wpa_supplicant( 1324): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1324): getPrivFuncNum +	
I/wpa_supplicant( 1324): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  949): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  949): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/WifiStateMachine(  949): handleMessage: E msg.what=147462
E/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiMonitor(  949): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=41 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  949): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  949): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  949): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  949): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  949):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=106607  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  949): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  949): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  949): processMsg: ConnectModeState
D/HTCRequest(  949): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  949): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  949): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  949): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  949): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  949): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  949):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=106608  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=147500
D/WifiMonitor(  949): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  949): Enter handleAssociatedWithEvent
D/WifiStateMachine(  949): Associated
,D/wpa_supplicant( 1324): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1324): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1324): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1324): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1324):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1324):   key_nonce - hexdump(len=32): 83 0e f5 18 cd 96 85 2d 79 03 c0 e3 f8 b3 f2 b7 84 77 fb 88 d3 59 50 86 61 52 ce bd d6 25 03 31
D/wpa_supplicant( 1324):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1324):   key_rsc - hexdump(len=8): a7 42 01 00 00 00 00 00
D/wpa_supplicant( 1324):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1324):   key_mic - hexdump(len=16): 45 c4 88 17 4d ee 98 df 31 62 46 2d 0e 85 f0 88
D/wpa_supplicant( 1324): RSN: encrypted key data - hexdump(len=56): 08 96 a1 ca 5b 46 b1 81 e1 cf 92 38 60 ce ce ac 26 82 ea 91 da 75 04 c1 12 fb e9 bf 9a e1 ca 50 ...
D/wpa_supplicant( 1324): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1324): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1324): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1324): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 c6 33 ...
D/wpa_supplicant( 1324): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1324): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1324): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1324): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1324): WPA: Derived Key MIC - hexdump(len=16): 79 db 33 2c dc f7 35 96 90 85 99 f0 dd 78 30 8a
D/wpa_supplicant( 1324): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1324): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5593602390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1324): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1324): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1324):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1324): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1324): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1324): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1324): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1324): WPA: RSC - hexdump(len=6): a7 42 01 00 00 00
D/wpa_supplicant( 1324): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x558b433e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1324): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1324): nl80211: KEY_SEQ - hexdump(len=6): a7 42 01 00 00 00
D/wpa_supplicant( 1324):    broadcast key
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 1324): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1324): wlan0: Cancelling authentication timeout
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1324): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  949): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1324): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1324): wlan0: Radio work 'connect'@0x5593602680 done in 0.181972 sec,onds
I/wpa_supplicant( 1324): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1324): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  949): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  949): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=44 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  949): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  949): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=45 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  949): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1324): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1324): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1324): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  949): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=47 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  949): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1324): set send_ind_to_ndc = 0
I/wpa_supplicant( 1324): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1324): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1324): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1324): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1324): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1324): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1324): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1324): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1324): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1324): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/Tethering(  949): interfaceLinkStateChanged wlan0, true
D/Tethering(  949): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1324): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1324): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1324): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1324): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  949): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  949): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  949): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,I/ActivityManager(  949): Recipient 6310
,D/Tethering(  949): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine(  949): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  949): Exit handleAssociatedWithEvent
E/WifiStateMachine(  949): handleMessage: X
D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/PMS     (  949): acquireWL(1f37ffc1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 949 1000 null
D/UsbDeviceManager(  949): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  949): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
,D/UsbnetService(  949): BroadcastReceiver::onReceive-
E/WifiStateMachine(  949): handleMessage: E msg.what=147462
E/WifiStateMachine(  949): processMsg: DisconnectedState
D/TetherSettings( 5903): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
W/ContextImpl( 5903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 5903): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5903): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5903): Cust_ConnectToPC   : spcsc>false
D/        ( 5903): Cust_ConnectToPC   : IPT>true
,D/PMS     (  949): releaseWL(1f37ffc1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/        ( 5903): Cust_ConnectToPC   : Singel_USB>false
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/Settings( 5903): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/SmartNS_Utility( 5903): hasRemovableStorageSlot: true
V/NetworkPolicy(  949): updateNetworkEnabledLocked()
D/SmartNS_Utility( 5903): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
V/NetworkPolicy(  949): updateNotificationsLocked()
D/SmartNS_NSReceiver( 5903): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  949):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=106654  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  949): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  949): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  949): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  949): NetworkAgent == null
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/SmartNS_Utility( 5903): setISNotification
D/SmartNS_Utility( 5903): usb_cable_connect = 1
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  949): processMsg: ConnectModeState
D/SmartNS_Utility( 5903): usb_denied = 0
I/SmartNS_PSService( 5903): usb notificaiton:true
E/WifiStateMachine(  949):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=106660  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=147462
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=106661  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  949): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  949): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=106662  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=147459
E/WifiStateMachine(  949): processMsg: DisconnectedState
E/WifiStateMachine(  949):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=106663
E/WifiStateMachine(  949): processMsg: ConnectModeState
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  949):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=106663
,E/WifiStateMachine(  949): Network connection established
D/WifiStateMachine(  949): fetchFrequency(), freq = 2412
E/WifiStateMachine(  949): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  949): NetworkAgent == null
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  949): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  949): handleMessage: new destination call exit/enter
E/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  949): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  949): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  949): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  949):     Client/Owner: Client
D/WifiDisplayAdapter(  949):     GroupId: 
D/WifiDisplayAdapter(  949):     Passphrase: 
D/WifiDisplayAdapter(  949):     SessionId: 0
D/WifiDisplayAdapter(  949):     IP Address: }
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 21
,D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  949): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  949): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  949): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  949): NetworkAgent == null
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 22
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_Utility( 5903): usb_cable_connect = 1
D/ConnectivityService(  949): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  949): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  949): Got NetworkAgent Messenger
,E/WifiStateMachine(  949): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  949): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  949): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  949): NetworkAgent connected
W/WifiHW  (  949): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/SmartNS_Utility( 5903): usb_denied = 0
D/wpa_supplicant( 1324): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1324): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
I/SmartNS_PSService( 5903): usb notificaiton:true
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1324): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiStateMachine(  949): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1324): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1324): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  949): invokeEnterMethods: ObtainingIpState
,E/WifiStateMachine(  949): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  949): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  949): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  949): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  949): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1324): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1324): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1324): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1324): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1324): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/libc    (  949): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
I/RemoteViews( 1214): reapply : com.android.settings 1 36
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  949): Start Dhcp Watchdog 2
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=147462
E/WifiStateMachine(  949): processMsg: ObtainingIpState
D/SmartNS_NSReceiver( 5903): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  949):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=106682  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=106682  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=106683  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131101
E/WifiStateMachine(  949): processMsg: ObtainingIpState
E/WifiStateMachine(  949):  ObtainingIpState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
,E/WifiStateMachine(  949):  L2ConnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  949): processMsg: DriverStartedState
,E/WifiStateMachine(  949):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
,E/WifiStateMachine(  949):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  949): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  949): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  949): handleMessage: X
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,E/WifiStateMachine(  949): handleMessage: E msg.what=131155
E/WifiStateMachine(  949): processMsg: ObtainingIpState
E/WifiStateMachine(  949):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2789] from screen [on:0 period:-1581590343] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581590342] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  949):  get link layer stats 0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,I/wpa_supplicant( 1324): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  949): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  949): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=106.00 txretriesrate=0.00 rxrate=156.50 userTriggerdPenalty0
,E/WifiStateMachine(  949):  good link -> stuck count =0
D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  949):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  949):  isHighRSSI       ---> score=65
E/WifiStateMachine(  949): calculateWifiScore() report new score 60
,D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiWatchdogStateMachine(  949): RSSI current: 3 new: -60, 3
D/ConnectivityService(  949): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=196612
E/WifiStateMachine(  949): processMsg: ObtainingIpState
E/WifiStateMachine(  949):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=212,0,0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
I/RemoteViews( 1214): reapply : com.android.settings 2 36
E/WifiStateMachine(  949):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=212,0,0
D/WifiStateMachine(  949): handlePreDhcpSetup Held wake lock during DHCP
,D/PMS     (  949): acquireWL(1ecbe8b5): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 949 1000 null
D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  949): setDhcpActive: true
D/WifiStateMachine(  949): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1324): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
,D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  949): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/native  (  949): do suspend false
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1324): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1324): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1324): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1324): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1324): wlan0: Event DRIVER_GTK_REKEY (37) received
D/WifiP2pService(  949): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@193ae152 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1324): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  949): Unexpected BatchedScanResults :null
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/WifiP2pService(  949): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@193ae152 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1324): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  949): noteBatchedScanstop()
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131212
E/WifiStateMachine(  949): processMsg: ObtainingIpState
E/WifiStateMachine(  949):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  949): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  949): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  949): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  949): handleMessage: X
D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WISPrService( 5903): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5903): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:3
I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1214): receive.wifiConnect:false wifiAPname:null elapse:0
,E/WifiStateMachine(  949): handleMessage: E msg.what=131155,
E/WifiStateMachine(  949): processMsg: ObtainingIpState
,E/WifiStateMachine(  949):  ObtainingIpState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=106.0, 0.0, 0.0  rx=156.5 bcn=0 [on:0 tx:0 rx:0 period:205] from screen [on:0 period:-1581590131] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=106.0, 0.0, 0.0  rx=156.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581590130] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  949): handleMessage: X
,E/dhcpcd  ( 6670): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6670): version 5.5.6 starting
,E/dhcpcd  ( 6670): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6670): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6670): autoip env[11]:autoip=DISABLE
,I/dhcpcd  ( 6670): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6670): wlan0: sending REQUEST (xid 0x3ee47daf), next in 0.37 seconds
,D/Messaging( 6591): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6591): networkCode: ,
D/MessageCustFlag( 6591): sku_id=118
D/MmsConfig( 6591): SIE smsPri: null
D/MmsConfig( 6591): networkCode: 
D/MmsConfig( 6591): packageName: com.htc.vvm.att does not exist
,D/Messaging( 6591): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 6591): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 6591): ,
D/MmsAsyncWorkHandler( 6591): HM tk = 20001
D/ReportIndicatorCache( 6591): MSG_QUERY_REPORTS >>
D/SettingsManager( 6591): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@f715671
,D/DraftCache( 6591): [DraftCache/1] DraftCache.constructor
D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1542):  slotId = -1000
D/MmsSmsV2Provider( 1542): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/DraftCache( 6591): [DraftCache/1] refresh
,D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/MmsSmsV2Provider( 1542):  slotId = -1000
D/MmsSmsV2Provider( 1542): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 6591): mccmnc> 
,D/MmsConfig( 6591): networkCode: 
D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1542): sku_id=118
,D/Messaging( 6591): ViewCache CreatePreloadOnlyConversationList
,I/dhcpcd  ( 6670): wlan0: sending REQUEST (xid 0x3ee47daf), next in 2.25 seconds
D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/MmsSmsV2Provider( 1542):  slotId = -1000
D/MmsSmsV2Provider( 1542): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/DraftCache( 6591): [DraftCache/161] rebuildCache
,D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1542):  slotId = -1000
D/MmsSmsV2Provider( 1542): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 6591): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Messaging( 6591): mNeedToUpdateDate2: false
,D/PhoneStorageUtil( 6591): HtcWrapEnvironment.getSupportedStorages() >1,
D/PhoneStorageUtil( 6591): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6591): createReceiver
,D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/Jerry   ( 1542): URI_DRAFT
,D/DraftCache( 6591): hasDraft() = false mNeedNotifyChange = true,
D/DraftCache( 6591): [DraftCache/161] rebuildCache time: 8
D/MmsAsyncWorkHandler( 6591): 
D/MmsAsyncWorkHandler( 6591): HM tk = 20002
D/TelephUtils( 1542): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
V/MmsProvider( 1542): Update uri=content://mms, match=0
V/MmsProvider( 1542): selection=st=129 AND m_type!=134
,D/Messaging( 6591): Reset downloading state: 0,
D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1542): sku_id=118
V/MmsSystemEventReceiver( 6591): TransactionService is going to be woken up.
,D/MessageCustFlag( 6591): sense_version=6.0
,D/Jerry   ( 6591): start to preload cursor >>>>>>>
,V/TransactionService( 6591): 1-Creating TransactionService
,D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
,I/AlarmManager(  949): [AlarmQueuing] connectivity wifi: false
I/dhcpcd  ( 6670): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
D/htcCheckinService(  949): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  949): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/ConnectivityHelper( 1590): [onReceive] WIFI(1): DISCONNECTED
D/GpsLocationProvider(  949): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/MmsSmsV2Provider( 1542):  slotId = -1000
,D/PMS     (  949): acquireWL(298fd4d9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 949 1000 null
,D/GpsLocationProvider(  949): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  949): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
V/TransactionService( 6591): onStartCommand: 1
D/MmsSystemEventReceiver( 6591): unRegisterForConnectionStateChanges
V/TransactionService( 6591): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6591): Loading previous transactions.
,D/Messaging( 6591): ViewCache CreatePreload
D/Messaging( 6591): ViewCache CreatePreloadOnlyMultipleOpsList
,I/ActivityManager(  949): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6689 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Cust_MMSMS( 6591): _has_set_default_values_2=true
,D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1542): device_type: 1
D/AccFlag ( 1542): sku_id=118
,D/MsgPreferenceUtils( 6591): def_index: 0
,D/TransactionService( 6591): Force clearing mTransactionList
,D/TransactionService( 6591): Force set service start id to 1
V/TransactionService( 6591): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 6591): unRegisterForConnectionStateChanges
D/MsgPreferenceUtils( 6591): globalIndex = 1
D/TransactionService( 6591): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6591): Destroying TransactionService
,V/TransactionService( 6591): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 6591): phone state: true
D/MsgPreferenceUtils( 6591): sd state: false
D/MsgPreferenceUtils( 6591): vIndex = 0
,E/GpsLocationProvider(  949): No APN found to select.
,D/PMS     (  949): releaseWL(298fd4d9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6530): [93d.1.]  listen tmrbb8,
,D/MdScDataSum( 6530): [93d.1.] summary 118:p1 ignore
,I/dhcpcd  ( 6670): wlan0: leased 192.168.1.130 for 86400 seconds
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
I/dhcpcd  ( 6670): autoip env[11]:autoip=DISABLE
,E/WifiStateMachine(  949): handleMessage: E msg.what=131212
E/WifiStateMachine(  949): processMsg: ObtainingIpState
D/ConnectivityService(  949): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  949):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  949): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  949): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  949): handleMessage: X
,D/wpa_supplicant( 1324): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1324): EAPOL: disable timer tick
,I/dhcpcd  ( 6670): bind_interface: daemonise,
,I/MusicStore( 6689): Database version: 120,
,D/libc    (  949): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS,
E/WifiStateMachine(  949): handleMessage: E msg.what=196613
E/WifiStateMachine(  949): processMsg: ObtainingIpState
E/WifiStateMachine(  949):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  949): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0",
D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1324): Power_Mode_Type mode = 0
I/wpa_supplicant( 1324): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER BTCOEXMODE 2',
D/wpa_supplicant( 1324): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  949): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  949): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  949): setDhcpActive: false
D/PMS     (  949): releaseWL(1ecbe8b5): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  949): handlePostDhcpSetup release wake lock during DHCP
D/ConnectivityService(  949): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  949): WifiStateMachine DHCP successful
E/WifiStateMachine(  949): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  949): link address 192.168.1.130/24
E/WifiStateMachine(  949): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  949): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  949): gateway: /192.168.1.1
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1324): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1324): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  949): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131210
,E/WifiStateMachine(  949): processMsg: ObtainingIpState
E/WifiStateMachine(  949):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  949): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
D/wpa_supplicant( 1324): wlan0: Control interface command 'BLACKLIST clear'
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/wpa_supplicant( 1324): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  949): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=49 dispatchEvent: BLACKLIST CLEAR 
D/ConnectivityService(  949): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  949): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  949): NetworkAgent != null
D/WifiWatchdogStateMachine(  949): RSSI current: 3 new: -59, 3
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  949): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  949): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,V/NetworkPolicy(  949): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL true Token 23
D/HtcWifiWanDetect(  949): WAN detection
D/HtcWifiWanDetect(  949): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
D/ConnectivityService(  949): Adding iface wlan0 to network 101
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  949):  packet count Tx=213 Rx=315
E/WifiTrafficPoller(  949): notifying of data activity 3
,I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  949): transitionTo: destState=ConnectedState
E/WifiStateMachine(  949): handleMessage: new destination call exit/enter
E/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  949): invokeExitMethods: ObtainingIpState
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  949): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  949): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
V/NetworkPolicy(  949): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  949): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiDataStallTracker(  949): ENABLE_DATA_MONITOR_POLL true Token 2
,E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL true Token 24
D/WifiDataStallTracker(  949): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  949): updateDataStallInfo: NONE
D/WifiDataStallTracker(  949): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiTrafficPoller(  949):  packet count Tx=213 Rx=315
E/WifiTrafficPoller(  949): notifying of data activity 0
D/WIFI_ICON( 1214): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/IntentController( 1214): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WIFI_ICON( 1214): WifiActivity: 3
,D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1214): WifiActivity: 0
,D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5903): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  949): Unexpected mtu value: 0, wlan0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/ConnectivityService(  949): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  949): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  949): ConnectedState Enter  mScreenOn=true scanperiod=20000
E/WifiStateMachine(  949): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
E/WifiStateMachine(  949): handleMessage: X
D/WifiDisplayAdapter(  949): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  949):     Client/Owner: Client
D/WifiDisplayAdapter(  949):     GroupId: 
D/WifiDisplayAdapter(  949):     Passphrase: 
D/WifiDisplayAdapter(  949):     SessionId: 0
D/WifiDisplayAdapter(  949):     IP Address: }
E/WifiStateMachine(  949): handleMessage: E msg.what=131131
D/ConnectivityService(  949): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
E/WifiStateMachine(  949): processMsg: ConnectedState
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  949):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  949): processMsg: L2ConnectedState
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  949):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  949): handleMessage: X
D/ConnectivityService(  949): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  949): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  949): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  949): Connected
D/ConnectivityService(  949): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  949): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  949): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/WISPrService( 5903): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  949): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  949): Validated
D/ConnectivityService(  949):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  949): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  949):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  949):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  949): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  949): currentScore = 0, newScore = 20
D/WIFI    (  949): new score 20 for exisiti,ng request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):    accepting network in place of null
D/WIFI    (  949):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  949): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  949): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  949): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/Tethering(  949): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  949): sendGeneralBroadcast, restrictEnable=false
D/Tethering(  949): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  949): sendGeneralBroadcastDelayed, restrictEnable=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  949): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  949): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  949): Validated
D/PMS     (  949): acquireWL(15d6e29b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 949 1000 null
D/ConnectivityManager.CallbackHandler( 1214): CM callback handler got msg 524290
D/ConnectivityService(  949): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/SecurityController( 1214): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  949): ensureActiveMobilePolicyLocked()
D/usbnet  (  949): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  949):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  949): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1214): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  949): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): Validated NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  949): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  949): rematching NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  949):   my score=60, my filter=[ Transpo,rts: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  949):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  949): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  949):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  949): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkPolicy(  949): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  949): updateNetworkEnabledLocked()
V/NetworkPolicy(  949): updateIfacesLocked()
D/ConnectivityManager.CallbackHandler( 1214): CM callback handler got msg 524290
D/ConnectivityService(  949): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
V/NetworkPolicy(  949): updateNotificationsLocked()
D/ConnectivityService(  949): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  949):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  949): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkManagementService(  949): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/SecurityController( 1214): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1214): dataConnected: false/false
D/ConnectivityManager.CallbackHandler( 1214): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/SecurityController( 1214): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  949): releaseWL(15d6e29b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1214): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
V/NetworkPolicy(  949): updateNetworkEnabledLocked()
V/NetworkPolicy(  949): updateNotificationsLocked()
D/DATA_ICON( 1214): dataConnected: false/false
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/QuickSettingWifi( 1214): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I/QuickSettingWifi( 1214): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/VoldConnector(  949): SND -> {29 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  949): SND -> {30 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  949): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6689): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6689): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6689): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/libc    (  949): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/ConnectivityService(  949): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  949): identical MTU - not setting
E/WifiStateMachine(  949): handleMessage: E msg.what=131212
D/Nat464Xlat(  949): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
E/WifiStateMachine(  949): processMsg: ConnectedState
D/ConnectivityService(  949): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  949):  ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  949): processMsg: L2ConnectedState
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  949):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns,
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  949): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  949): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
E/WifiStateMachine(  949): handleMessage: X
,D/ConnectivityService(  949): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  949): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1214): CM callback handler got msg 524295
D/ConnectivityService(  949): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1214): CM callback handler got msg 524295
,W/ActivityThread( 6689): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6689): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39f240e1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6689): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6689): GMSCore installation verified
,I/ConfigStore( 6689): Config Database version: 1
,D/PMS     (  949): acquireWL(33413b4e): PARTIAL_WAKE_LOCK  *alarm* 0x1 949 1000 WorkSource{10024},
V/AlarmManager(  949): sending alarm PendingIntent{1f2c346f: PendingIntentRecord{33fd51b7 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=108011, Int=0
V/AlarmManager(  949): sending alarm PendingIntent{11899fb0: PendingIntentRecord{1860ce29 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454412324262, Int=20000
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6689, uid=10159, userID:0,
,D/WifiDisplayAdapter(  949): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  949):     Client/Owner: Client
D/WifiDisplayAdapter(  949):     GroupId: 
D/WifiDisplayAdapter(  949):     Passphrase: 
D/WifiDisplayAdapter(  949):     SessionId: 0
D/WifiDisplayAdapter(  949):     IP Address: }
,I/art     (  949): Explicit concurrent mark sweep GC freed 43418(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.393ms total 145.504ms,
,D/MediaRouterService(  949): Client com.google.android.music (pid 6689): Registered
,D/WifiDisplayAdapter(  949): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  949):     Client/Owner: Client
D/WifiDisplayAdapter(  949):     GroupId: 
D/WifiDisplayAdapter(  949):     Passphrase: 
D/WifiDisplayAdapter(  949):     SessionId: 0
D/WifiDisplayAdapter(  949):     IP Address: }
,I/MediaRouter( 6689): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6689): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6689): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6689): type=WIFI subType= reason=null isConnected=true,
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6689, uid=10159, userID:0
,D/AutoSetting( 1625): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,I/ActivityManager(  949): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6766 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/AutoSetting( 1625): service - onCreate(),
,D/AutoSetting( 1625): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1625): Util - check NLP state, Allowned:false, Enabled:false,
D/AutoSetting( 1625): service - requestNLP() NetworkLocationProvider not enabled
D/LocationManagerService(  949): request 1ed224e6 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/AutoSetting( 1625): service - onStartCommand() REMOVE current location bundle
D/LocationManagerService(  949): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1625): service - handleMessage() setting current location null
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 12483(678KB) AllocSpace objects, 5(420KB) LOS objects, 48% free, 4MB/8MB, paused 692us total 37.324ms
,I/GHttpClientFactory( 6689): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6689): Using platform SSLCertificateSocketFactory,
,D/PhoneMonitor( 6766): Register our PhoneStateListener,
,D/MobileConnectivityChangeReceiver( 6766): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6766): onReceive CONNECTIVITY_CHANGE networkType=1
,D/PhoneMonitor( 6766): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,I/ActivityManager(  949): Killing 6338:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
D/Process (  949): killProcessQuiet, pid=6338
,D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PhoneMonitor( 6766): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,I/ActivityManager(  949): Recipient 6338,
,I/ActivityManager(  949): Killing 4968:com.google.android.gms.wearable/u0a24 (adj 15): empty #17,
D/Process (  949): killProcessQuiet, pid=4968,
D/PMS     (  949): acquireWL(3b7da0c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4327 10024 WorkSource{10024 com.google.android.gms}
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 4968
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL true Token 25 num clients 8,
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL true Token 25 num clients 8
,D/WIFI_ICON( 1214): WifiActivity: 3
E/WifiTrafficPoller(  949):  packet count Tx=215 Rx=316
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  949): notifying of data activity 3
,D/PMS     (  949): releaseWL(2f8ecafb): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  949): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/PMS     (  949): acquireWL(707bd6a): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4327 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): releaseWL(3b7da0c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4327): Checking schedule, now: 1454412325089 next: 1454412317946
,I/CheckinService( 4327): active receiver: enabled
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4327, uid=10024, userID:0
,I/CheckinService( 4327): Preparing to send checkin request
,I/EventLogService( 4327): Accumulating logs since 1454412280243,
,D/ChimeraCfgMgr( 4327): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4327): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  949): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6798 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 6559): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6559): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6559): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6559): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6559): [NET] android_getaddrinfo_proxy+
D/libc    ( 6559): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/CheckinRequestBuilder( 4327): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  949): Cannot resolve ContentProvider=com.google.android.wearable.settings,
E/ActivityThread( 4327): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6559): [NET] android_getaddrinfo_proxy-, success
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Kids    ( 4327): [AccountUtils] Account not ready
W/Kids    ( 4327): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4327): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4327): ,	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4327): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4327): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4327): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4327): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4327): 	at java.lang.Thread.run(Thread.java:818)
,I/RemoteViews( 1214): reapply : com.google.android.gms 3 40
,I/Babel   ( 6559): connection state changed from UNKNOWN to CONNECTED
,D/VoldConnector(  949): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6798): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 6798): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files,
D/VoldConnector(  949): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,I/GAv4    ( 6798): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6798):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6798):   adb logcat -s GAv4
D/VoldConnector(  949): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6798): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  949): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6798): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6798): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 6798): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6798): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/CheckinRequestBuilder( 4327): awaiting user notification for token
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1214): reapply : com.google.android.gms 2 40
,I/ActivityManager(  949): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6829 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 6829): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6829): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/global  ( 6798): [apache-http] Connection GC has been deprecated!
,W/global  ( 6798): [apache-http] Connection GC has been deprecated!
,I/MultiDex( 6829): VM with version 2.1.0 has multidex support,
I/MultiDex( 6829): install
I/MultiDex( 6829): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6829): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6829): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6829): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c73f0ef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6829): Installed default security provider GmsCore_OpenSSL
,I/WebViewFactory( 6798): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6798): Time to load native libraries: 2 ms (timestamps 9284-9286),
I/LibraryLoader( 6798): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6798): Binding Chromium to main looper Looper (main, tid 1) {a8994a6}
,I/LibraryLoader( 6798): Expected native library version number "",actual native library version number ""
,I/chromium( 6798): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6798): Initializing chromium process, singleProcess=true,
,W/art     ( 6798): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6798): ApplicationContext is null in ApplicationStatus
,W/chromium( 6798): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6798): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6798): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 6798): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6798): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6798): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6798): Local Branch: 
I/Adreno-EGL( 6798): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6798): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6798):                  d74aa161a12b9c6fc6332151
,E/WifiStateMachine(  949): handleMessage: E msg.what=131168
,E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  949): processMsg: ConnectModeState
,E/WifiStateMachine(  949):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  949): handleMessage: X
,I/WVCdm   (  445): CdmEngine::OpenSession,
I/WVCdm   (  445): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  445): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  445): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  445): Service_Initialize: starts!
D/QSEECOMAPI: (  445): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  445): App is not loaded in QSEE
E/QSEECOMAPI: (  445): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  445): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  445): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  445): App is not loaded in QSEE
,D/QSEECOMAPI: (  445): Loaded image: APP id = 8,
D/DrmWidevineDash(  445): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  445): qsapps_get_capabilities: Capability from secure side: 0x0
,D/QSAPPSVER(  445): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  445): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4762000
E/DrmWidevineDash(  445): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4762000
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  534): got the req here! ret=0,
D/DrmLibTime(  534): command id, time_cmd_id = 770
D/DrmLibTime(  534): time_getutcsec starts!
D/DrmLibTime(  534): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  534): QSEE Time Listener: get_utc_seconds,
D/DrmLibTime(  534): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  534): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  534): Receive Passed == base = 13, unit = 1, operation = 2, result = 0,
D/DrmLibTime(  534): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  534): QSEE Time Listener: Retrieved Android system time: 1454412325
D/DrmLibTime(  534): time_getutcsec returns 0, sec = 1454412325; nsec = 0
D/DrmLibTime(  534): time_getutcsec finished! 
D/DrmLibTime(  534): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  534): before calling ioctl to read the next time_cmd
E/QC-time-services(  474): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): hlos api version =  9
D/DrmWidevineDash(  445): tz api version =  9
D/DrmWidevineDash(  445): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  445): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/AudioManagerAndroid( 6798): Requires BLUETOOTH permission,
I/NSApplication( 6798): Starting up...
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  445): OEMCrypto_IsKeyboxValid: ends! returns 0
I/ActivityManager(  949): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6884 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/WVCdm   (  445): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  445): OEMCrypto_OpenSession: starts! SID=0xf498e928,
D/DrmWidevineDash(  445): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  445): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_GetRandom: starts! randomData=0xab33c228, dataLength=8
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab224f90, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  445): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  445): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  445): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  445): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  445): OEMCrypto_GetDeviceID: starts! deviceID=0xab20c138, idLength=0xf488e6f8
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  445): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  445): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_GetHDCPCapability: starts!, current = 0xf488e70e, maximum = 0xf488e70f
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): hlos api version =  9
D/DrmWidevineDash(  445): tz api version =  9
D/DrmWidevineDash(  445): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  445): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf488e77c
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  445): PrepareKeyRequest: nonce=3160752576
D/DrmWidevineDash(  445): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab226b00
D/DrmWidevineDash(  445): message_length=1611, signature=0xab2fce10, signature_length=0xf488e6dc
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  445): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  445): CdmEngine::CloseSession
D/DrmWidevineDash(  445): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  445): L3 Terminate.
D/DrmWidevineDash(  445): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): Service_Uninitialize: starts!
D/QSEECOMAPI: (  445): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  445): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  445): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  445): OEMCrypto_Terminate: ends! returns 0
,E/WifiStateMachine(  949): handleMessage: E msg.what=131155,
E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=106.0, 0.0, 0.0  rx=156.5 bcn=0 [on:0 tx:0 rx:0 period:2794] from screen [on:0 period:-1581587335] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=106.0, 0.0, 0.0  rx=156.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581587334] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  949):  get link layer stats 0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1324): environment dirty rate=12 [8][1][0]
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiStateMachine(  949): BroadcastRSSIForIMS, newrssi =-60 , oldRssi= -200
E/WifiConfigStore(  949): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,D/WifiWatchdogStateMachine(  949): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  949): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=57.00 txretriesrate=0.00 rxrate=81.75 userTriggerdPenalty0
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  949):  good link -> stuck count =0
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  949):  badRSSI count0 lowRSSI count0 --> score 60
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  949):  isHighRSSI       ---> score=65
E/WifiStateMachine(  949): handleMessage: X
D/WifiWatchdogStateMachine(  949): RSSI current: 3 new: -60, 3
,I/WVCdm   (  445): CdmEngine::OpenSession
I/WVCdm   (  445): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  445): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  445): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  445): Service_Initialize: starts!
D/QSEECOMAPI: (  445): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  445): App is not loaded in QSEE
E/QSEECOMAPI: (  445): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  445): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  445): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  445): App is not loaded in QSEE
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL true Token 25 num clients 8,
E/WifiTrafficPoller(  949):  packet count Tx=220 Rx=320
D/QSEECOMAPI: (  445): Loaded image: APP id = 9
,D/DrmWidevineDash(  445): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  445): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  445): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  445): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4762000
E/DrmWidevineDash(  445): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4762000
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  534): got the req here! ret=0
D/DrmLibTime(  534): command id, time_cmd_id = 770
D/DrmLibTime(  534): time_getutcsec starts!
D/DrmLibTime(  534): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  534): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  534): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  534): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  534): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  534): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  534): QSEE Time Listener: Retrieved Android system time: 1454412326
D/DrmLibTime(  534): time_getutcsec returns 0, sec = 1454412326; nsec = 0,
D/DrmLibTime(  534): time_getutcsec finished! 
D/DrmLibTime(  534): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  534): before calling ioctl to read the next time_cmd
E/QC-time-services(  474): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_APIVersion: starts!
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): hlos api version =  9
D/DrmWidevineDash(  445): tz api version =  9
D/DrmWidevineDash(  445): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  445): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  445): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  445): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  445): OEMCrypto_OpenSession: starts! SID=0xf498e928
D/DrmWidevineDash(  445): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  445): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_GetRandom: starts! randomData=0xab224980, dataLength=8
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab21a7e8, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  445): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  445): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  445): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  445): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  445): OEMCrypto_GetDeviceID: starts! deviceID=0xab20c158, idLength=0xffca33a8
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  445): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  445): OEMCrypto_SupportsUsageTable: starts!
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  445): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  445): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_GetHDCPCapability: starts!, current = 0xffca33be, maximum = 0xffca33bf
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  445): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  445): hlos api version =  9
D/DrmWidevineDash(  445): tz api version =  9
D/DrmWidevineDash(  445): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  445): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffca342c
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  445): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  445): PrepareKeyRequest: nonce=3526968374
D/DrmWidevineDash(  445): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab2fc920
D/DrmWidevineDash(  445): message_length=1646, signature=0xab227178, signature_length=0xffca338c
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/art     ( 5996): Suspending all threads took: 5.203ms,
,I/ActivityManager(  949): Killing 5852:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
,D/Process (  949): killProcessQuiet, pid=5852
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  445): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  445): CdmEngine::CloseSession,
D/DrmWidevineDash(  445): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  445): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  445): L3 Terminate.
D/DrmWidevineDash(  445): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  445): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  445): Service_Uninitialize: starts!
D/QSEECOMAPI: (  445): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  445): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  445): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  445): OEMCrypto_Terminate: ends! returns 0
,W/art     ( 5996): Suspending all threads took: 6.087ms
,I/ActivityManager(  949): Recipient 5852
,E/cutils-trace( 6915): Error opening trace file: Permission denied (13),
I/dex2oat ( 6915): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6915): dex2oat: override thread count:4
,I/dex2oat ( 6915): dex2oat took 43.177ms (threads: 4),
,E/WifiStateMachine(  949): WiFiStateMachine SCAN ALARM
D/PMS     (  949): acquireWL(2c6fa41e): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  949): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  949): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  949):     Client/Owner: Client
D/WifiDisplayAdapter(  949):     GroupId: 
D/WifiDisplayAdapter(  949):     Passphrase: 
D/WifiDisplayAdapter(  949):     SessionId: 0
D/WifiDisplayAdapter(  949):     IP Address: }
E/WifiStateMachine(  949): processMsg: ConnectedState
D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  949):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):0 dur:79 rssi=-60 f=2412 sc=60 link=72 tx=57.0, 0.0, 0.0  rx=81.8 list=2412 [on:0 tx:0 rx:0 period:444] from screen [on:0 period:-1581586884]
E/WifiStateMachine(  949): processMsg: L2ConnectedState
D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1962): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1962): [NET] android_getaddrinfo_proxy+
D/libc    ( 1962): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
E/WifiStateMachine(  949):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:79 rssi=-60 f=2412 sc=60 link=72 tx=57.0, 0.0, 0.0  rx=81.8 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581586883]
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
E/WifiStateMachine(  949): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=57.00 rxSuccessRate=81.75 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  949): WifiStateMachine CMD_START_SCAN with age=32533 interval=40000 maxinterval=300000
E/WifiStateMachine(  949): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  949): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=57.00 rx=81.75
D/PMS     (  949): releaseWL(33413b4e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  949): handleMessage: X
I/Adreno-EGL( 6829): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6829): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6829): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6829): Local Branch: 
I/Adreno-EGL( 6829): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6829): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6829):                  d74aa161a12b9c6fc6332151
D/GCM     ( 1962): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1962): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4327): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1962): [NET] android_getaddrinfo_proxy-, success
,I/ActivityManager(  949): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6925 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4327, uid=10024, userID:0
,I/art     (  454): Explicit concurrent mark sweep GC freed 8659(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 177us total 20.542ms,
,D/LocationInitializer( 4327): Restart initialization of location,
,I/jxcore-log( 6419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6419): 
,I/art     (  454): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 139us total 15.966ms
W/ResourcesManager( 6925): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
,I/Adreno-EGL( 6829): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6829): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6829): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6829): Local Branch: 
I/Adreno-EGL( 6829): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6829): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6829):                  d74aa161a12b9c6fc6332151
,I/MultiDex( 6925): VM with version 2.1.0 has multidex support
,I/MultiDex( 6925): install
I/MultiDex( 6925): VM has multidex support, MultiDex support library is disabled.
I/art     (  454): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 146us total 30.819ms
,V/JNIHelp ( 6925): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
,W/ActivityThread( 6925): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6925): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c73f0ef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6925): Installed default security provider GmsCore_OpenSSL
,I/CheckinRequestBuilder( 4327): Classify the device as Phone.
,D/WearableService( 6925): callingUid 10024, callindPid: 6925
,D/AuthorizationBluetoothService( 1962): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1962): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GmsCoreStatsServiceLauncher( 4327): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,E/MDM     ( 1811): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4327, uid=10024, userID:0
D/libc    ( 4327): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4327): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4327): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4327): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4327): [NET] android_getaddrinfo_proxy+
D/libc    ( 4327): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/MDM     ( 1811): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4327): Restart initialization of location
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 4327): [NET] android_getaddrinfo_proxy-, success
,D/GCM     ( 1962): Connected,
D/PMS     (  949): acquireWL(3bcace82): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  949): releaseWL(2c6fa41e): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 4327): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/PMS     (  949): releaseWL(3bcace82): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 4327): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  949): acquireWL(3ad1b993): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): acquireWL(c88fdd0): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1962): Message class com.google.f.a.a.p,
I/GCM     ( 4327): Message from null null
E/GCM     ( 4327): Dropping message from null
,D/PMS     (  949): releaseWL(3ad1b993): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): releaseWL(c88fdd0): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 4327): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4327): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4327): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4327): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4327): Sending checkin request (8450 bytes),
,D/libc    (  949): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  949): [NET] android_getaddrinfofornet-, err=8
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  949): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  949): [NET] android_getaddrinfo_proxy+
D/libc    (  949): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL true Token 25 num clients 8,
E/WifiTrafficPoller(  949):  packet count Tx=247 Rx=342
,D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  949): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  949): [AlarmQueuing] connectivity wifi: true
D/GpsLocationProvider(  949): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  949): acquireWL(3289a1c9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 949 1000 null
D/GpsLocationProvider(  949): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  949): acquireWL(1e5b50ce): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 949 1000 null
I/NetworkMonitor( 6689): type=WIFI subType= reason=null isConnected=true
D/PMS     (  949): releaseWL(1e5b50ce): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ConnectivityHelper( 1590): [onReceive] WIFI(1): CONNECTED
,D/htcCheckinService(  949): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  949): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,E/GpsLocationProvider(  949): No APN found to select.
,D/PMS     (  949): releaseWL(3289a1c9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,V/MusicLeanback( 6689): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/HtcWifiWanDetect(  949): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  949): [NET] android_getaddrinfo_proxy-, success
,D/MdScPhnSt( 6530): [273.1.]  listen tmrbb8,
D/AutoSetting( 1625): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6766): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6766): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1625): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/MdScDataSum( 6530): [273.1.] summary 118:p1 ignore
,I/CheckinRequestBuilder( 4327): Checkin reason type: 8 attempt count: 1,
I/ActivityManager(  949): Cannot resolve ContentProvider=com.google.android.wearable.settings,
E/ActivityThread( 4327): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  949): Explicit concurrent mark sweep GC freed 20153(975KB) AllocSpace objects, 3(188KB) LOS objects, 33% free, 16MB/25MB, paused 2.735ms total 162.498ms
,D/PMS     (  949): acquireWL(c6eb6e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4327 10024 WorkSource{10024 com.google.android.gms}
D/AutoSetting( 1625): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1625): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1625): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1625): service - handleMessage() setting current location null
,D/PMS     (  949): releaseWL(c6eb6e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4327, uid=10024, userID:0
,D/ChimeraCfgMgr( 4327): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4327): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4327): [AccountUtils] Account not ready
W/Kids    ( 4327): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4327): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4327): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4327): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4327): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4327): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4327): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4327): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/jxcore-log( 6419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6419): 
I/RemoteViews( 1214): reapply : com.google.android.gms 1 40,
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6419): 
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 16267(910KB) AllocSpace objects, 9(628KB) LOS objects, 49% free, 4MB/8MB, paused 888us total 52.079ms
,I/jxcore-log( 6419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6419): 
,I/jxcore-log( 6419): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6419): 
,W/CheckinRequestBuilder( 4327): awaiting user notification for token
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1214): reapply : com.google.android.gms 1 40
,I/CheckinRequestBuilder( 4327): Classify the device as Phone.
,I/CheckinTask( 4327): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4327): Checking schedule, now: 1454412327566 next: 1454949159561
I/CheckinService( 4327): active receiver: disabled
I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4327, uid=10024, userID:0
,I/CheckinService( 4327): Checking schedule, now: 1454412327584 next: 1454949159561
,I/CheckinService( 4327): active receiver: disabled
I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4327, uid=10024, userID:0
,D/PMS     (  949): releaseWL(707bd6a): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,V/SetupWizard( 6766): Connected to Gservices successfully,
,D/ChimeraCfgMgr( 4327): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/GCM     ( 1962): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4327): [AccountUtils] Account not ready
W/Kids    ( 4327): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4327): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4327): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4327): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4327): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4327): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4327): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4327): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4327): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1214): reapply : com.google.android.gms 1 40
,I/PMS     (  949): Going to sleep due to screen timeout (uid 1000)...
,I/SensorManager(  949): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@36ce640a
W/SensorService(  949): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  949): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  949): pid=949, uid=1000
W/PMN     (  949): goingToSleep
W/SensorService(  949): Active sensors: size = 4
W/SensorService(  949): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  949): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  949): CM36686 Proximity sensor (handle=0x00000004, connections=1),
W/SensorService(  949): Significant Motion (handle=0x0000000d, connections=1)
,W/PMS     (  949): mWirelessDisplayManager is null
W/SensorService(  949): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@36ce640a, eanble = 0, strlen(mName) = 91
I/PMS     (  949): Sleeping (uid 1000)...
W/SensorService(  949): Active Listeners: mActiveListeners.size() = 2
W/PMS     (  949): mWirelessDisplayManager is still null
W/SensorService(  949): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@245546cb
D/PMS     (  949): acquireWL(edbb5e2): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 949 1000 null
W/SensorService(  949): Listener[1] = com.htc.smartdim.sensor_eye@170461d1
W/PMN     (  949): goingToSleep done
W/SensorService(  949): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/XAN-DPS (  949): prepareColorFade 1
W/HtcLockScreen( 1214): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
D/AlarmManager(  949): ACTION_SCREEN_ON
W/HtcSystemUPManager(  949): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  949): releaseWL(edbb5e2): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL true Token 25
I/AlarmManager(  949): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  949): [AlarmQueuing] done recovering
E/WifiTrafficPoller(  949):  packet count Tx=250 Rx=346
I/AlarmManager(  949): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  949): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiDataStallTracker(  949): ENABLE_DATA_MONITOR_POLL true Token 3
E/WifiStateMachine(  949): handleMessage: E msg.what=131167
E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiDataStallTracker(  949): updateDataStallInfo: mDataStallTxRxSum={txSum=222 rxSum=195} preTxRxSum={txSum=222 rxSum=195}
D/WifiDataStallTracker(  949): updateDataStallInfo: NONE
D/WifiDataStallTracker(  949): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  949):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
V/SRS_Proc(  445): ParamSet string: screen_state=on
E/audio_a2dp_hw(  445): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  949):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1324): SET_SCREEN_ON:On
I/wpa_supplicant( 1324): htc_wext_set_keepalive +
I/wpa_supplicant( 1324): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1324): getPrivFuncNum +	
I/wpa_supplicant( 1324): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1324): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1324): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  949): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiController(  949): handleMessage: E msg.what=155650
D/WifiController(  949): processMsg: DeviceActiveState
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
D/WifiController(  949): handleMessage: X
D/WifiDisplayAdapter(  949): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  949):     Client/Owner: Client
D/WifiDisplayAdapter(  949):     GroupId: 
D/WifiDisplayAdapter(  949):     Passphrase: 
D/WifiDisplayAdapter(  949):     SessionId: 0
D/WifiDisplayAdapter(  949):     IP Address: }
D/WifiStateMachine(  949): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  949): handleScreenStateChanged Exit: true
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131154
E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
D/NetworkPolicy(  949): updateScreenOn: false
I/wpa_supplicant( 1324): environment dirty rate=0 [30][0][0]
V/NetworkPolicy(  949): updateIfacesLocked()
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiStateMachine(  949): fetchRssiLinkSpeedAndFrequenc,yNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  949): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131127
E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
D/NetworkManagementService(  949): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  949):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131129
E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiWatchdogStateMachine(  949): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  949):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1324): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1324): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  949): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=50 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  949): handleMessage: X
,D/GpsLocationProvider(  949): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/Adreno-EGL(  949): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  949): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  949): Build Date: 03/09/15 Mon
I/Adreno-EGL(  949): Local Branch: 
I/Adreno-EGL(  949): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  949): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  949):                  d74aa161a12b9c6fc6332151
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
,I/ActivityManager(  949): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6978 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/IntentController( 1214): receive(android.intent.action.SCREEN_ON,1,false)
,D/XAN-DPS (  949): prepareColorFade done
D/XAN-DPS (  949): setBrightness to 0
,I/SensorManager(  949): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@245546cb
W/SensorService(  949): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  949): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  949): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  949): Display changed displayId=0
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
W/SensorService(  949): pid=949, uid=1000
W/SensorService(  949): Active sensors: size = 3
W/SensorService(  949): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  949): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  949): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  949): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@245546cb, eanble = 0, strlen(mName) = 67
W/SensorService(  949): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  949): Listener[0] = com.htc.smartdim.sensor_eye@170461d1
W/SensorService(  949): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,W/ContextImpl( 6978): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false,
,W/ContextImpl( 6978): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6978): MY_DEBUG = false
,D/PMS     (  949): acquireWL(1cfa1f3a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): acquireWL(2cdf27eb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/SmartSyncUtils( 6978): isEpsOn(), nState = 0
,D/PMS     (  949): releaseWL(1cfa1f3a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): acquireWL(23efc948): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6978 1000 null
,D/PMS     (  949): releaseWL(2cdf27eb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  949): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  949): Init customizeScreenOffDelayClass error
,D/PMS     (  949): releaseWL(23efc948): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL true Token 26 num clients 8
D/AlarmManager(  949): ACTION_SCREEN_OFF
,I/AlarmManager(  949): [AlarmQueuing] screen off now: 
I/AlarmManager(  949): [AlarmQueuing] data connection: true
I/AlarmManager(  949): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  949): ENABLE_TRAFFIC_STATS_POLL false Token 26
D/WifiDataStallTracker(  949): stopDataStallAlarm 
,E/WifiDataStallTracker(  949): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  949): handleMessage: E msg.what=131167
E/WifiStateMachine(  949): processMsg: ConnectedState
,E/WifiStateMachine(  949):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  445): ParamSet string: screen_state=off
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/audio_a2dp_hw(  445): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  949):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  949):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  949): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiDisplayAdapter(  949): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  949):     Client/Owner: Client
D/WifiDisplayAdapter(  949):     GroupId: 
D/WifiDisplayAdapter(  949):     Passphrase: 
D/WifiDisplayAdapter(  949):     SessionId: 0
D/WifiDisplayAdapter(  949):     IP Address: }
D/WifiController(  949): handleMessage: E msg.what=155651
D/NetworkPolicy(  949): updateScreenOn: false
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_SCREEN_ON 0'
V/NetworkPolicy(  949): updateIfacesLocked()
,I/wpa_supplicant( 1324): SET_SCREEN_ON:Off
I/wpa_supplicant( 1324): htc_wext_set_keepalive +
I/wpa_supplicant( 1324): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1324): getPrivFuncNum +	
I/wpa_supplicant( 1324): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1324): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1324): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1324): htc_wext_set_keepalive - ret = 0
D/WifiController(  949): processMsg: DeviceActiveState
D/NetworkManagementService(  949): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
E/WifiStateMachine(  949): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiController(  949): handleMessage: X
D/WifiStateMachine(  949): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  949): handleScreenStateChanged Exit: false
E/WifiStateMachine(  949): handleMessage: X
E/WifiStateMachine(  949): handleMessage: E msg.what=131154
,E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  949): handleMessage: X
,I/SensorManager( 1214): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@2b896f14, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  949): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  949): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  949): pid=1214, uid=10041
W/SensorService(  949): Active sensors: size = 4
,W/SensorService(  949): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  949): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  949): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  949): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  949): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@2b896f14, eanble = 1, strlen(mName) = 57
W/SensorService(  949): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  949): Listener[0] = com.htc.smartdim.sensor_eye@170461d1
W/SensorService(  949): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@2b896f14
W/SensorService(  949): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  949): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,W/ContextImpl( 6978): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/DotMatrix( 1311): [EventService] getTotalRam: 1842 Mb
,W/ContextImpl( 6978): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/ContactMessageStore( 1542): start background delete task...
,I/IntentController( 1214): receive(android.intent.action.SCREEN_OFF,1,false)
,D/SmartSyncUtils( 6978): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6978): isEpsOn(), nState = 0
D/ContactMessageStore( 1542): size: 0 , 0
D/ContactMessageStore( 1542): Background delete complete
,W/ContextImpl( 6978): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  949): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  949): acquireWL(2f8657c7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  949): releaseWL(2f8657c7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/SensorManager(  949): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@170461d1,
W/SensorService(  949): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  949): disable: get sensor name = Accelerometer Sensor
,D/PMS     (  949): acquireWL(15dc31f4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): releaseWL(15dc31f4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
W/SensorService(  949): pid=949, uid=1000
W/SensorService(  949): Active sensors: size = 3
W/SensorService(  949): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  949): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  949): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  949): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@170461d1, eanble = 0, strlen(mName) = 36
W/SensorService(  949): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  949): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2b896f14
W/SensorService(  949): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  949): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  949): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  949): pid=949, uid=1000
W/SensorService(  949): Active sensors: size = 2
W/SensorService(  949): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  949): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  949): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@170461d1, eanble = 0, strlen(mName) = 36
W/SensorService(  949): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  949): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2b896f14
W/SensorService(  949): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  949): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@170461d1
,E/ActivityThread(  949): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1b518436 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  949): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1b518436 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  949): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  949): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  949): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  949): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  949): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  949): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  949): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  949): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  949): ,	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  949): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  949): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  949): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  949): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  949): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  949): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  949): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  949): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029),
,E/ActivityThread(  949): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/PowerUsageList:PowerUsageHelper( 6978): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/SmartSyncUtils( 6978): getMobilePolicyEnabled, result = true
,I/RemoteViews( 1214): setHTCTheme(com.htc.updater,true,33751145)
D/AutoSetting( 1625): service - mHandler: cancel location update
D/WifiService(  949): New client listening to asynchronous messages
,D/AutoSetting( 1625): service -           changes count: 0
E/WifiTrafficPoller(  949): ADD_CLIENT: 9
I/RemoteViews( 1214): apply : com.htc.updater 0 11 1 36
,D/PowerUsageList:BatterySipperExt( 6978): gen(), null == sipper.uidObj, userId = 0
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  949): Excessive delay in setPowerMode(): 288ms
D/PMS     (  949): Setting HAL interactive mode to false
W/HtcSystemUPManager(  949): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  949): Setting HAL interactive mode to false done
D/PMS     (  949): Setting HAL auto-suspend mode to true
,D/PMS     (  949): Setting HAL auto-suspend mode done
I/InputManager(  949): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/InputMethodManagerService(  949): screenObserver, isScreenOn=false
D/StatusBarManagerService(  949): swetImeWindowStatus vis=0 backDisposition=0
I/IntentController( 1214): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  949): Disable input method client, pid=6419
I/PhoneStatusBar( 1214): setImeWindowStatus(false,false)
D/HABCtrl (  949): TPE algorithm. remove timeout.
D/PMS     (  949): OOBE c monitor 11
,I/InputMethodManager( 6419): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{22a71d92 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3ed7c35c
,D/PMS     (  949): acquireWL(3cb1cd1d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null,
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(3cb1cd1d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  949): updateBatteryInfo
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NfcService( 1556): ScreenObserver: OFF
D/NfcService( 1556): applyRouting - 0
,D/NotificationService(  949): plugged=true pluggin=true
D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
D/PMS     (  949): runPSCheck
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  949): Checking...
D/UsbnetService(  949): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  949): >> updateStatus
D/WifiController(  949): handleMessage: E msg.what=155652
D/WifiController(  949): battery changed pluggedType: 2
D/WifiController(  949): processMsg: DeviceActiveState
D/WifiController(  949): processMsg: StaEnabledState
,D/WifiController(  949): processMsg: DefaultState
D/WifiController(  949): handleMessage: X
D/PMS     (  949): acquireWL(5a15b92): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1556 1027 null
,D/NfcService( 1556): applyRouting -2
D/NfcService( 1556): applyRouting
D/NfcService( 1556): Ignore this applyRouting...
,D/PMS     (  949): releaseWL(5a15b92): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  949): << updateStatus
,D/PowerUsageList:PowerUsageHelper( 6978): MY_DEBUG = false,
I/ClockController( 1214): stop clock update:screen off
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  949): Killing 5782:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  949): killProcessQuiet, pid=5782
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 5782
,E/WifiTrafficPoller(  949): TRAFFIC_STATS_POLL false Token 27 num clients 9,
,D/PMS     (  949): releaseWL(d5e2b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,E/WifiStateMachine(  949): handleMessage: E msg.what=131155,
E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2555] from screen [on:0 period:-1581584326] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581584323] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  949): handleMessage: X
,E/WifiDataStallTracker(  949): DATA_MONITOR_POLL false Token 5,
,D/PMS     (  949): acquireWL(a847960): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6689 10159 null,
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6689, uid=10159, userID:0
,I/MusicLeanback( 6689): Conditions not met for autocaching. okToAttempt=false
,D/PMS     (  949): releaseWL(a847960): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6689): Stop autocaching.
,E/GmsUtils( 6689): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6689): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/WifiStateMachine(  949): handleMessage: E msg.what=131155,
E/WifiStateMachine(  949): processMsg: ConnectedState,
,E/WifiStateMachine(  949):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1726] from screen [on:0 period:-1581582596] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1581582594] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  949): handleMessage: X
,D/HtcUPManager( 1214): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,D/Process (  949): killProcessQuiet, pid=5438
,I/ActivityManager(  949): Killing 5438:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 5438
,I/ActivityManager(  949): Killing 5927:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  949): killProcessQuiet, pid=5927
,D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 5927
,D/Process (  949): killProcessQuiet, pid=6621
,I/ActivityManager(  949): Killing 6621:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 6621,
,E/WifiDataStallTracker(  949): DATA_MONITOR_POLL false Token 5,
,I/jxcore-log( 6419): Test app app.js loaded
I/jxcore-log( 6419): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6419): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@348c6665 added. We now have 1 listener(s)
D/BluetoothAdapter( 6419): 47071684: getState(). Returning 12
I/jxcore-log( 6419): BLE advertisement is supported
I/jxcore-log( 6419): 
,I/chromium( 6419): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/AccTypeManager( 1733): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  949): Cannot find grip_rejection_width, use default value instead
,D/PMS     (  949): acquireWL(1fb57b8e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6559 10112 null
,D/AccTypeManager( 1733): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/Prism.AllAppsManager( 1590): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false,
,W/ResourcesManager(  949): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Launcher( 1590): Deferring update until onResume
D/Launcher( 1590): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1733): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  949): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7025 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
D/PhoneApp( 1542): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1733): Unsupported attribute readOnly
,D/PMS     (  949): releaseWL(1fb57b8e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null,
,W/ResourcesManager( 6559): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6559): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/PackageManager(  949): Unable to load service info ResolveInfo{a3f5025 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  949): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  949): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  949): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331),
W/PackageManager(  949): ,	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  949): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  949): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  949): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  949): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  949): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  949): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  949): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  949): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  949): 	at java.lang.reflect.Method.invoke(Native Method),
W/PackageManager(  949): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  949): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  949): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1811): DISABLE
,I/GCoreNlp( 1811): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  949): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LocationProviderProxy(  949): applying state to connected service,
,D/PMS     (  949): acquireWL(3d393410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): releaseWL(3d393410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  949): applying state to connected service
,D/PMS     (  949): acquireWL(2065813c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1811 10024 WorkSource{10024 com.google.android.gms},
D/LocationManagerService(  949): getProviders()=[passive]
,D/PMS     (  949): releaseWL(2065813c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): acquireWL(1efb5d27): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): releaseWL(1efb5d27): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,V/JNIHelp ( 6559): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/ActivityManager(  949): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7053 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,I/[PluginManager]RegisterService( 1625): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1625): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  949): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7074 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/System  ( 6559): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6559): Installed default security provider GmsCore_OpenSSL
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7074, uid=10072, userID:0,
,I/art     (  949): Explicit concurrent mark sweep GC freed 34401(1959KB) AllocSpace objects, 7(1232KB) LOS objects, 33% free, 18MB/28MB, paused 1.593ms total 179.291ms,
,D/PMS     (  949): acquireWL(449c140): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): releaseWL(449c140): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/global  ( 7074): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 7074): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 7074): [apache-http] Connection GC has been deprecated!
,W/global  ( 7074): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7074): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  949): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7117 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7074): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 7074): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7074, uid=10072, userID:0,
,D/Finsky  ( 7074): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7074): [1] 2.run: Finished loading 1 libraries.
,W/ResourcesManager( 7117): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7117): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  949): Killing 6644:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  949): killProcessQuiet, pid=6644
,D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/MultiDex( 7117): VM with version 2.1.0 has multidex support
I/MultiDex( 7117): install
I/MultiDex( 7117): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  949): Recipient 6644
,D/Finsky  ( 7074): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 4327): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4327): Null package name or gms related package.  Ignoreing.,
V/JNIHelp ( 7117): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PMS     (  949): acquireWL(effa70): PARTIAL_WAKE_LOCK  Icing 0x1 4327 10024 WorkSource{10024 com.google.android.gms}
,D/Finsky  ( 7074): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4327): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  949): acquireWL(271bf1e9): PARTIAL_WAKE_LOCK  AsyncService 0x1 5996 10167 null
,D/PMS     (  949): releaseWL(271bf1e9): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  949): acquireWL(154a790f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5996 10167 null
,D/PMS     (  949): releaseWL(154a790f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/PMS     (  949): releaseWL(effa70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/UpdateIcingCorporaServi( 7025): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ActivityThread( 7117): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7117): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c73f0ef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7117): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1962): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1962): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4327): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4327, uid=10024, userID:0
,D/WearableService( 6925): callingUid 10024, callindPid: 6925,
,D/LocationInitializer( 4327): Restart initialization of location,
,E/MDM     ( 1811): [131] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,I/UpdateIcingCorporaServi( 7025): UpdateCorporaTask done [took 153 ms] updated apps [took 152 ms] ,
,V/Finsky  ( 7074): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1590): loadItems() com.htc.launcher.pageview.WidgetManager@8a035a4 +
I/Prism.WidgetManager( 1590): onLoadItems() +
,W/ResourcesManager( 1590): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/PMS     (  949): acquireWL(a41c3ff): PARTIAL_WAKE_LOCK  *alarm* 0x1 949 1000 WorkSource{10072}
V/AlarmManager(  949): sending alarm PendingIntent{3df255cc: PendingIntentRecord{1f3be844 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454412336785, Int=0
D/PMS     (  949): releaseWL(a41c3ff): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 7074): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 7074): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ResourcesManager( 1590): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7074): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/PhoneApp( 1542): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1542): -- N1 =0
,D/PhoneApp( 1542): -- N2 =0,
,D/PhoneApp( 1542): -- N3 =0
,W/asset   ( 1590): Copying FileAsset 0x55ad7d8d00 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/AndroidHttpClient( 7074): Leak found
E/AndroidHttpClient( 7074): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 7074): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 7074): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 7074): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 7074): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 7074): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 7074): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 7074): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 7074): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 7074): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 7074): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 7074): 	,at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 7074): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 7074): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 7074): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 7074): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 7074): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/Prism.WidgetManager( 1590): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1590): onLoadItems() -
I/Prism.ItemManager( 1590): loadItems() com.htc.launcher.pageview.WidgetManager@8a035a4 -,
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7074): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 7074): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 7074): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7074): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1811): client connected with version: 7571000,
,I/ActivityManager(  949): Killing 6591:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  949): killProcessQuiet, pid=6591
,D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 6591
,D/Process (  949): killProcessQuiet, pid=6482
,I/ActivityManager(  949): Killing 6482:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 6482
,I/ActivityManager(  949): Killing 6530:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
,D/Process (  949): killProcessQuiet, pid=6530
,D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 6530
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Process (  949): killProcessQuiet, pid=5521
,I/ActivityManager(  949): Killing 5521:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 5521
,D/PMS     (  949): acquireWL(153cf65c): PARTIAL_WAKE_LOCK  *alarm* 0x1 949 1000 WorkSource{10109},
V/AlarmManager(  949): sending alarm PendingIntent{52d1d65: PendingIntentRecord{14487a3a com.htc.backup startService}}, i=contextual_reminder_observer_START, t=0, cnt=1, w=1454412345982, Int=0
D/PMS     (  949): releaseWL(153cf65c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10109}
,D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  949): acquireWL(bd11c48): PARTIAL_WAKE_LOCK  *alarm* 0x1 949 1000 WorkSource{10072}
V/AlarmManager(  949): sending alarm PendingIntent{26572ae1: PendingIntentRecord{2d340006 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454412352172, Int=0
,V/AlarmManager(  949): sending alarm PendingIntent{21ca06c7: PendingIntentRecord{35ffb4f4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141808, Int=0
,D/PMS     (  949): releaseWL(bd11c48): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/AutoSetting( 1625): service - handleMessage() stop self
,D/AutoSetting( 1625): service - handleMessage() quit looper
D/AutoSetting( 1625): service - onDestroy() END
,D/Finsky  ( 7074): [702] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 7074): [1] 5.onFinished: Installation state replication succeeded.,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  949): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  949): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  949): acquireWL(fba941d): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 949 1000 null
,D/libc    (  949): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  949): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  949): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  949): [NET] android_getaddrinfo_proxy+
D/libc    (  949): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  401): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  949): [NET] android_getaddrinfo_proxy-, success,
D/libc    (  949): [NET] android_getaddrinfofornet+,hn 12(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  949): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  949): [handleDownloadXtraData] calling native_inject_xtra_data,
,E/WifiStateMachine(  949): handleMessage: E msg.what=131165
,E/WifiStateMachine(  949): processMsg: ConnectedState
E/WifiStateMachine(  949):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  949): processMsg: ConnectModeState
E/WifiStateMachine(  949):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  949): processMsg: DriverStartedState
E/WifiStateMachine(  949):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  949): processMsg: SupplicantStartedState
E/WifiStateMachine(  949):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  949): processMsg: DefaultState
E/WifiStateMachine(  949):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  949): handleMessage: X
,D/GpsLocationProvider(  949): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  949): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  949): acquireWL(1ff15519): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 949 1000 null
D/GpsLocationProvider(  949):  [handleDownloadXtraData]inject done.
D/PMS     (  949): releaseWL(fba941d): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  949): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  949): releaseWL(1ff15519): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/WifiStateMachine(  949): handleMessage: E msg.what=131326,
E/WifiStateMachine(  949): processMsg: ConnectedState
,E/WifiStateMachine(  949):  ConnectedState what:131326 2 0
E/WifiStateMachine(  949): processMsg: L2ConnectedState
E/WifiStateMachine(  949):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  949): handleMessage: X
,D/PMS     (  949): acquireWL(c0509de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(c0509de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  949): updateBatteryInfo
D/PMS     (  949): runPSCheck
D/HtcPowerSaver(  949): Checking...
I/HtcPowerSaver(  949): >> updateStatus
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  949): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  949): << updateStatus
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/NotificationService(  949): plugged=true pluggin=true
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  949): battery changed pluggedType: 2
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  949): handleMessage: E msg.what=155652
D/WifiController(  949): processMsg: DeviceActiveState
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
D/WifiController(  949): handleMessage: X
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1542): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  949): acquireWL(26db07bf): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 949 1000 WorkSource{1000}
V/AlarmManager(  949): sending alarm PendingIntent{1190c35: PendingIntentRecord{3f6088ca android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=143688, Int=0
V/AlarmManager(  949): sending alarm PendingIntent{458ae8c: PendingIntentRecord{2b3929d5 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454412395692, Int=0,
V/AlarmManager(  949): sending alarm PendingIntent{1d3e5ea: PendingIntentRecord{144260db android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203863, Int=0
V/AlarmManager(  949): sending alarm PendingIntent{1e282778: PendingIntentRecord{11ef8e51 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189992, Int=0
D/PMS     (  949): acquireWL(40276b6): PARTIAL_WAKE_LOCK  *backup* 0x1 949 1000 null
,D/PMS     (  949): acquireWL(3bfc2fb7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  949): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  949): Requested init for com.google.android.gms.backup.BackupTransportService but not found,
D/PMS     (  949): releaseWL(40276b6): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  949): releaseWL(26db07bf): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1214): Weather sync is On
W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data
,D/PMS     (  949): acquireWL(3f744324): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): releaseWL(3bfc2fb7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  949): releaseWL(3f744324): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): acquireWL(1bf5a68e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): releaseWL(1bf5a68e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): acquireWL(202b5eaf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): releaseWL(202b5eaf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  949): acquireWL(13aad2bc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): acquireWL(25593245): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): acquireWL(275936cb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): releaseWL(13aad2bc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1962): Vacuum at: now=1454412420457 tag=VacuumService
,D/PMS     (  949): releaseWL(25593245): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): acquireWL(24dfadc1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1962): Using platform SSLCertificateSocketFactory,
,D/PMS     (  949): releaseWL(24dfadc1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  949): acquireWL(3e73f966): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1962): No account for auth token provided
,D/PMS     (  949): releaseWL(3e73f966): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1962): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1962): [NET] android_getaddrinfo_proxy+
D/libc    ( 1962): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1962): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1962): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1962): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1962): No account for auth token provided,
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
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1214): reapply : com.google.android.gms 3 40
,W/Uploader( 1962): No account for auth token provided,
,W/Uploader( 1962): No account for auth token provided,
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
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
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1214): reapply : com.google.android.gms 5 40,
,D/PMS     (  949): releaseWL(275936cb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): acquireWL(f782384): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): releaseWL(f782384): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): acquireWL(2d11876d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): releaseWL(2d11876d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1214): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcAppUPService( 1625): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@18aa4273
I/ActivityManager(  949): Killing 6798:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
,D/HtcUPManager( 1214): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/Process (  949): killProcessQuiet, pid=6798
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 6798
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  949): acquireWL(33080fa2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(33080fa2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1214): closing low battery warning: level=100
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  949): updateBatteryInfo
D/UsbnetService(  949): BroadcastReceiver::onReceive+
,D/NotificationService(  949): plugged=true pluggin=true
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/PMS     (  949): runPSCheck
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/HtcPowerSaver(  949): Checking...
D/UsbnetService(  949): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  949): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  949): battery changed pluggedType: 2
D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
,D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  949): handleMessage: E msg.what=155652
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  949): processMsg: DeviceActiveState
I/HtcPowerSaver(  949): << updateStatus
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState,
D/WifiController(  949): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  949): acquireWL(287e3433): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(287e3433): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  949): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1214): closing low battery warning: level=100
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  949): plugged=true pluggin=true
D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
,D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/PMS     (  949): runPSCheck
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  949): Checking...
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  949): >> updateStatus
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/WifiController(  949): battery changed pluggedType: 2
D/WifiController(  949): handleMessage: E msg.what=155652
D/WifiController(  949): processMsg: DeviceActiveState
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
D/WifiController(  949): handleMessage: X
,I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  949): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1324): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  949): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  949): acquireWL(415f3f0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 949 1000 WorkSource{1000},
V/AlarmManager(  949): sending alarm PendingIntent{1190c35: PendingIntentRecord{3f6088ca android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=263688, Int=0
,V/AlarmManager(  949): sending alarm PendingIntent{337b83ee: PendingIntentRecord{5dde08f com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454412577319, Int=0
,D/PMS     (  949): releaseWL(415f3f0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1214): Weather sync is On
,W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  949): acquireWL(177e5f1c): PARTIAL_WAKE_LOCK  *alarm* 0x1 949 1000 WorkSource{1000}
,V/AlarmManager(  949): sending alarm PendingIntent{2682ad38: PendingIntentRecord{27bb0111 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=376793, Int=0
D/PMS     (  949): acquireWL(2d713725): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 949 1000 null
D/PMS     (  949): acquireWL(239ff0fa): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 949 1000 null
,D/PMS     (  949): releaseWL(177e5f1c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  949): releaseWL(2d713725): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null,
,D/PMS     (  949): releaseWL(239ff0fa): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1962): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1962): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1962): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1962): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1962): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1962): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1962): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1962): 	,at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1962): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1962): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1962): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1214): reapply : com.google.android.gms 4 40
,E/PlayEventLogger( 7074): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7074): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7074): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7074): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7074): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7074): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7074): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 7074): Ignoring header User-Agent because its value was null.,
,D/libc    ( 7074): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7074): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7074): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7074): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7074): [NET] android_getaddrinfo_proxy+
D/libc    ( 7074): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  401): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7074): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  949): acquireWL(525c74c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(525c74c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  949): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  949): updateBatteryInfo,
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/NotificationService(  949): plugged=true pluggin=true
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  949): runPSCheck
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  949): Checking...
D/WifiController(  949): handleMessage: E msg.what=155652
I/HtcPowerSaver(  949): >> updateStatus
D/WifiController(  949): processMsg: DeviceActiveState
D/PowerUI ( 1214): closing low battery warning: level=100,
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  949): battery changed pluggedType: 2
D/WifiController(  949): processMsg: StaEnabledState
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  949): processMsg: DefaultState
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  949): handleMessage: X
I/HtcPowerSaver(  949): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  949): acquireWL(24973395): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(24973395): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  949): updateBatteryInfo,
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  949): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  949): runPSCheck
D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  949): Checking...
D/UsbnetService(  949): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  949): >> updateStatus
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  949): battery changed pluggedType: 2
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  949): handleMessage: E msg.what=155652
D/WifiController(  949): processMsg: DeviceActiveState
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
D/WifiController(  949): handleMessage: X
,D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  949): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  949): acquireWL(20568caa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(20568caa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  949): updateBatteryInfo
D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  949): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  949): runPSCheck
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  949): Checking...
D/UsbnetService(  949): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  949): >> updateStatus
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  949): BroadcastReceiver::onReceive-
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  949): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  949): << updateStatus
D/WifiController(  949): processMsg: DeviceActiveState
D/WifiController(  949): battery changed pluggedType: 2
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
D/WifiController(  949): handleMessage: X
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1542): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1542): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1542): sku_id=118,
D/ContactMessageStore( 1542): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1542): start background delete task...
,D/ContactMessageStore( 1542): size: 0 , 0
,D/ContactMessageStore( 1542): Background delete complete
,D/PMS     (  949): acquireWL(1931e09b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(1931e09b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
D/PowerUI ( 1214): closing low battery warning: level=100
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  949): plugged=true pluggin=true
D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/WifiController(  949): battery changed pluggedType: 2
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  949): updateBatteryInfo
,D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/PMS     (  949): runPSCheck
D/WifiController(  949): handleMessage: E msg.what=155652
D/HtcPowerSaver(  949): Checking...
D/WifiController(  949): processMsg: DeviceActiveState
I/HtcPowerSaver(  949): >> updateStatus
D/WifiController(  949): processMsg: StaEnabledState
,D/WifiController(  949): processMsg: DefaultState,
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  949): handleMessage: X
I/HtcPowerSaver(  949): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  949): acquireWL(3f8e0c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
I/BatteryService(  949): n_update end
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  949): releaseWL(3f8e0c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  949): plugged=true pluggin=true
D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  949): updateBatteryInfo
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/PMS     (  949): runPSCheck
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/WifiController(  949): handleMessage: E msg.what=155652
D/WifiController(  949): processMsg: DeviceActiveState
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
,I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  949): battery changed pluggedType: 2
D/WifiController(  949): handleMessage: X
D/HtcPowerSaver(  949): Checking...
I/HtcPowerSaver(  949): >> updateStatus
,D/PowerUI ( 1214): closing low battery warning: level=100
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  949): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  949): acquireWL(2847411): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 949 1000 WorkSource{1000}
V/AlarmManager(  949): sending alarm PendingIntent{1190c35: PendingIntentRecord{3f6088ca android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=383688, Int=0
V/AlarmManager(  949): sending alarm PendingIntent{2302db0f: PendingIntentRecord{390079c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805097, Int=0
V/AlarmManager(  949): sending alarm PendingIntent{3e8c976: PendingIntentRecord{1ec3eb77 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941083, Int=0
,I/ActivityManager(  949): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7188 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  949): sending alarm PendingIntent{2033b3e4: PendingIntentRecord{3d2b404d com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454412784792, Int=0
,I/ActivityManager(  949): Start proc com.htc.cs.dm for service com.htc.cs.dm/com.htc.cs.util.workflow.WorkflowService: pid=7201 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,V/AlarmManager(  949): sending alarm PendingIntent{1900702: PendingIntentRecord{3a01c813 com.htc.cs.dm startService}}, i=com.htc.cs.action.EXECUTE_WORKFLOW, t=1, cnt=1, w=1454412822306, Int=0
,I/bt-btm  ( 3042): Received oneshot timer event complete
,I/bt-btm  ( 3042): btm_ble_timeout
D/PMS     (  949): releaseWL(2847411): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1002}
I/bt-btm  ( 3042): btm_gen_resolvable_private_addr
,D/WeatherUtility( 1214): Weather sync is On
,W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data
,I/art     (  949): Explicit concurrent mark sweep GC freed 36397(1809KB) AllocSpace objects, 5(328KB) LOS objects, 33% free, 18MB/28MB, paused 1.876ms total 169.650ms
D/PMS     (  949): acquireWL(f6a2a50): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3042 1002 null
,D/bt-btm  ( 3042): btm_ble_rand_enc_complete
I/bt-btm  ( 3042): btm_gen_resolve_paddr_low
D/bt-smp  ( 3042): smp_encrypt_data
W/bt-smp  ( 3042): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3042): Plain text(LSB ~ MSB) = 28 41 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3042): Encrypted text(LSB ~ MSB) = 66 24 a8 8a c6 c0 8f 87 c7 0f 48 52 26 53 0c 96 
I/bt-btm  ( 3042): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3042): Stopping oneshot timer
D/bt-btm  ( 3042): Starting oneshot timer type:103 timeout:900s
,I/DeviceManagement( 7201): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7201 dbg=false s=true
,I/DeviceManagement( 7201): WorkflowService: Starting workflow service,
I/DeviceManagement( 7201): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@31862f40] args=[Bundle[mParcelledData.dataSize=56]]
,I/DeviceManagement( 7201): UpdateWorkflow: ==================================================
I/DeviceManagement( 7201): UpdateWorkflow: TTL update...
I/DeviceManagement( 7201): UpdateWorkflow: ==================================================
,I/DeviceManagement( 7201): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7201): SessionStateController: Checking invariants...
,E/cutils-trace( 7232): Error opening trace file: Permission denied (13)
I/dex2oat ( 7232): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7232): dex2oat: override thread count:4
,I/DeviceManagement( 7201): BackgroundController: Invariants are unchanged.,
,I/DeviceManagement( 7201): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7201): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7201): Perf: *** Cache update - start...
,I/DeviceManagement( 7201): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 7201): EnabledAppController: *** Updating enabled app database...
,I/DeviceManagement( 7201): Perf: *** Enabled app cache update - complete: 2 ms
I/DeviceManagement( 7201): Perf: *** Config cache update - start...
,I/DeviceManagement( 7201): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 7201): ConfigCacheController: *** Updating stale config cache entries...
,I/art     ( 7201): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,I/art     ( 7201): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,W/System.err( 7201): Starting the internal HTTP client,
,I/DeviceManagement( 7201): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg,
,I/DeviceManagement( 7201): DeviceClientResource: Active network...,
I/DeviceManagement( 7201):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BuildInfo( 7201): Created new instance: com.htc.cs.lib.hms.BuildInfo@1f7a03b4,
I/DeviceManagement( 7201): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
,D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 7201): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7201): [NET] android_getaddrinfo_proxy+
D/libc    ( 7201): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7201): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 7201): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    ( 7201): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7201): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7201): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  401): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/dex2oat ( 7232): dex2oat took 668.920ms (threads: 4),
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7201): [NET] android_getaddrinfo_proxy-, success
,I/PushClient( 7188): ApplicationMonitor {340cf7e2}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 7188): ApplicationMonitor {340cf7e2}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 7188): ApplicationMonitor {340cf7e2}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7188): ApplicationMonitor {340cf7e2}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7188): ApplicationMonitor {340cf7e2}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7188): ApplicationMonitor {340cf7e2}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7188): ApplicationMonitor {340cf7e2}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7188): ApplicationMonitor {340cf7e2}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7188): ApplicationMonitor {340cf7e2}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,D/PMS     (  949): releaseWL(f6a2a50): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/PushClient( 7188): PnsModel {2b73e8ad}: update(): Update registration caused by: alarm
,I/PushClient( 7188): PnsConfigModel {19881b48}: <init>(): Use dm-client for provisioning.
,W/System.err( 7188): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 7188): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7188): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7188): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/DeviceManagement( 7201): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 7201): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7201): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 7201): DMServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 7201): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 7201): DeviceClientResourceController: handleDirectives: []
,I/System.out( 7201): isCompatible false
,I/System.out( 7201): createObjectMapper
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false,
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/DeviceManagement( 7201): ConfigCacheController: Getting config update from server: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.sense.socialnetwork.facebook/versions/2adae5da-a4df-4cc3-b772-ea9aaa6301b2/cid/MDowOjIwMTUtMDQtMTVUMDk6MDM6NTguMjk2Wg
,I/DeviceManagement( 7201): DeviceClientResource: Active network...,
I/DeviceManagement( 7201):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 7201): [NET] android_getaddrinfofornet-, err=8
,I/DeviceManagement( 7201): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 7201): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 7201): DeviceClientResourceController: handleDirectives: [],
I/System.out( 7201): isCompatible false
I/System.out( 7201): createObjectMapper
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false,
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/DeviceManagement( 7201): ConfigCacheController: Getting config update from server: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.identity/versions/887a7f5610a36712ed50f1fb1911e4b5da8368ea/cid/MDoyOjIwMTUtMTItMjNUMDM6MjM6MTIuMzY4Wg,
,I/DeviceManagement( 7201): DeviceClientResource: Active network...
I/DeviceManagement( 7201):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 7201): [NET] android_getaddrinfofornet-, err=8
,I/DeviceManagement( 7201): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 7201): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 7201): DeviceClientResourceController: handleDirectives: []
I/System.out( 7201): isCompatible false,
I/System.out( 7201): createObjectMapper
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/DeviceManagement( 7201): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pns/versions/55580870d4ecef7adc0bfac442bc01d880550489/cid/MDoxOjIwMTQtMTAtMjNUMDI6MDc6MTQuNTA0Wg,
,I/DeviceManagement( 7201): DeviceClientResource: Active network...
I/DeviceManagement( 7201):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 7201): [NET] android_getaddrinfofornet-, err=8
,I/DeviceManagement( 7201): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 7201): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 7201): DeviceClientResourceController: handleDirectives: []
I/System.out( 7201): isCompatible false,
I/System.out( 7201): createObjectMapper
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false,
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false,
,I/DeviceManagement( 7201): ConfigCacheController: Getting config update from server: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.csrecommend/versions/f26b54be-e9ca-4494-ba25-56712573f3ab/cid/MDoxMDoyMDE1LTA4LTI2VDEwOjE0OjI0LjczNVo,
I/DeviceManagement( 7201): DeviceClientResource: Active network...,
I/DeviceManagement( 7201):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 7201): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7201): [NET] android_getaddrinfo_proxy+
D/libc    ( 7201): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
,D/libc    (  401): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7201): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4
,D/libc    ( 7201): [NET] android_getaddrinfofornet-, err=8
,I/DeviceManagement( 7201): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 7201): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 7201): DeviceClientResourceController: handleDirectives: []
I/System.out( 7201): isCompatible false
,I/System.out( 7201): createObjectMapper
I/System.out( 7201): isCompatible false
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/DeviceManagement( 7201): ConfigCacheController: Getting config update from server: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.dm/versions/b5b04a47-d585-4433-9a63-6f3f39989144/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNjA2Wg
,I/DeviceManagement( 7201): DeviceClientResource: Active network...
I/DeviceManagement( 7201):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 7201): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7201): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    ( 7201): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7201): [NET] android_getaddrinfo_proxy+
D/libc    ( 7201): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7201): [NET] android_getaddrinfo_proxy-, success
,I/DeviceManagement( 7201): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 7201): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 7201): DeviceClientResourceController: handleDirectives: []
I/System.out( 7201): isCompatible false
,I/System.out( 7201): createObjectMapper
I/System.out( 7201): isCompatible false
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/System.out( 7201): isCompatible false
I/System.out( 7201): isCompatible false
,I/DeviceManagement( 7201): ConfigCacheController: *** Update config cache: updating 6 entries...,
I/DeviceManagement( 7201): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, statusCode=0, authCode=0>
,I/DeviceManagement( 7201): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, statusCode=0, authCode=0>,
,I/DeviceManagement( 7201): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, statusCode=0, authCode=0>,
,I/DeviceManagement( 7201): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, statusCode=0, authCode=0>,
,I/DeviceManagement( 7201): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, statusCode=0, authCode=0>,
,I/DeviceManagement( 7201): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, statusCode=0, authCode=0>
,I/DeviceManagement( 7201): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 7201): AlarmController: Scheduling TTL alarm for: 2016.02.02 at 13:14:26.788 CET (due to: com.htc.launcher),
,I/PackageManager(  949):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=7201, uid=10099, userID:0,
,I/DeviceManagement( 7201): Perf: *** Config cache update - complete: 3557 ms
,I/DeviceManagement( 7201): Perf: *** Cache update - complete: 3567 ms,
,I/DeviceManagement( 7201): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@31862f40]
,I/DeviceManagement( 7201): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@181aa5ba] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7201): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7201): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7201): SessionStateController: Checking invariants...
,I/DeviceManagement( 7201): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7201): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@181aa5ba]
,I/DeviceManagement( 7201): WorkflowService: Stopping workflow service,
,D/Process (  949): killProcessQuiet, pid=6884
I/ActivityManager(  949): Killing 6884:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 7188): PnsModel {2b73e8ad}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  949): Recipient 6884,
,I/ActivityManager(  949): Killing 6766:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  949): killProcessQuiet, pid=6766
,D/Process (  949): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  949): Recipient 6766
,D/PMS     (  949): acquireWL(1999d6bd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null,
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(1999d6bd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
D/PowerUI ( 1214): closing low battery warning: level=100
D/UsbnetService(  949): BroadcastReceiver::onReceive+
,D/NotificationService(  949): plugged=true pluggin=true
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/WifiController(  949): battery changed pluggedType: 2
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  949): updateBatteryInfo
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/PMS     (  949): runPSCheck
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  949): Checking...
D/WifiController(  949): handleMessage: E msg.what=155652
I/HtcPowerSaver(  949): >> updateStatus
D/WifiController(  949): processMsg: DeviceActiveState
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
D/WifiController(  949): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  949): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  949): acquireWL(191c34b2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 949 1000 WorkSource{1000}
,V/AlarmManager(  949): sending alarm PendingIntent{1190c35: PendingIntentRecord{3f6088ca android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=983688, Int=0
,V/AlarmManager(  949): sending alarm PendingIntent{3cbcdc03: PendingIntentRecord{14c4c780 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454413107905, Int=1800000
,V/AlarmManager(  949): sending alarm PendingIntent{199221b9: PendingIntentRecord{3794e9fe com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1010488, Int=0,
V/AlarmManager(  949): sending alarm PendingIntent{227355f: PendingIntentRecord{2a59922c com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454413183801, Int=0
,D/PMS     (  949): acquireWL(36edbac): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4327 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  949): acquireWL(751a80a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4327 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  949): releaseWL(36edbac): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1214): Weather sync is On
,W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data
,I/EventLogService( 4327): Aggregate from 1454412325151 (log), 1454411307854 (data)
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 42544(2MB) AllocSpace objects, 14(1068KB) LOS objects, 47% free, 4MB/8MB, paused 5.036ms total 74.616ms,
D/PMS     (  949): acquireWL(116a3ad6): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): releaseWL(116a3ad6): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  949): releaseWL(751a80a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
W/ContextImpl( 6978): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  949): releaseWL(191c34b2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6978): MY_DEBUG = false,
,D/PowerUsageService( 6978): repeat time = 1454414126936
,D/PMS     (  949): acquireWL(73ef444): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1962): Message class com.google.f.a.a.i
,D/PMS     (  949): releaseWL(73ef444): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 6978): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6978): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  949): acquireWL(34d2e92d): PARTIAL_WAKE_LOCK  *alarm* 0x1 949 1000 WorkSource{1000},
V/AlarmManager(  949): sending alarm PendingIntent{6a72e62: PendingIntentRecord{71ccbf3 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454413228090, Int=0
,D/SmartSyncUtils( 6978): isEpsOn(), nState = 0,
,D/PMS     (  949): releaseWL(34d2e92d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  949): acquireWL(3e5910b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6978 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6978): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6978): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6978): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6978): SettingOnTime = 1454479200000, randomSettingOnTime = 1454478802000
,D/SmartSyncScreenOnOffTimeReceiver( 6978): SettingOffTime = 1454457600000, randomSettingOffTime = 1454462991000
,D/SmartSyncScreenOnOffTimeReceiver( 6978): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6978): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6978): bNightModeTurnOffOnce = false,
,D/PMS     (  949): releaseWL(3e5910b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  949): acquireWL(721eb29): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null,
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(721eb29): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1214): closing low battery warning: level=100
D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  949): updateBatteryInfo
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/NotificationService(  949): plugged=true pluggin=true
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  949): runPSCheck
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  949): Checking...
,D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  949): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  949): battery changed pluggedType: 2
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  949): handleMessage: E msg.what=155652
D/WifiController(  949): processMsg: DeviceActiveState
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  949): handleMessage: X
I/HtcPowerSaver(  949): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  949): acquireWL(29cdceae): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(29cdceae): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  949): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  949): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  949): runPSCheck
D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  949): Checking...
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  949): >> updateStatus
D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/WifiController(  949): battery changed pluggedType: 2
,D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/WifiController(  949): handleMessage: E msg.what=155652
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  949): processMsg: DeviceActiveState
I/HtcPowerSaver(  949): << updateStatus
D/WifiController(  949): processMsg: StaEnabledState
D/WifiController(  949): processMsg: DefaultState
D/WifiController(  949): handleMessage: X
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  949): acquireWL(a2e344f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 949 1000 null
I/BatteryService(  949): n_update end
D/PMS     (  949): releaseWL(a2e344f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  949): BroadcastReceiver::onReceive+
D/NotificationService(  949): plugged=true pluggin=true
D/UsbnetService(  949): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  949): updateBatteryInfo
D/UsbnetService(  949):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1214): closing low battery warning: level=100
D/UsbnetService(  949): BroadcastReceiver::onReceive-
D/WifiController(  949): battery changed pluggedType: 2
D/WifiController(  949): handleMessage: E msg.what=155652
D/PMS     (  949): runPSCheck
D/WifiController(  949): processMsg: DeviceActiveState
D/HtcPowerSaver(  949): Checking...
D/HeadsetStateMachine( 3042): Disconnected process message: 10, size: 0
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  949): processMsg: StaEnabledState
I/HtcPowerSaver(  949): >> updateStatus
D/WifiController(  949): processMsg: DefaultState
D/WifiController(  949): handleMessage: X
,I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  949): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  949): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  949): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
