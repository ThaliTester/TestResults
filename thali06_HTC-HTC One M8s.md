#### Test 58918757c0fcaf3_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiDataStallTracker(  952): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  952): updateDataStallInfo: mDataStallTxRxSum={txSum=129 rxSum=118} preTxRxSum={txSum=129 rxSum=118}
D/WifiDataStallTracker(  952): updateDataStallInfo: NONE
D/WifiDataStallTracker(  952): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/HtcModeClient( 3155): handler message = 4011
E/HtcModeClient( 3155): Check connection and retry 11 times.
E/cutils-trace( 6213): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6213): ====startRecUseTime====
D/htc.customization.log.level( 6213):  is 
W/CustomizationLogLevel( 6213): Level value is invalid, use default level 2
D/CustomizationManager( 6213):  Read ACC file spent 0.035 (s)
D/CIDMapFileReader( 6213): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6213): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6213): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6213): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6213): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6213): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6213): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6213): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6213): Parsing tag category name = system
I/CustomizationCIDLoader( 6213): Parsing tag category name = application
I/CustomizationCIDLoader( 6213): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6213): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6213): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6213): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6213): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6213): add string-array item, value = 42507
I/CustomizationCIDLoader( 6213): add string-array item, value = 21902
I/CustomizationCIDLoader( 6213): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6213): add string-array item, value = 23420
I/CustomizationCIDLoader( 6213): add string-array item, value = 22299
I/CustomizationCIDLoader( 6213): add string-array item, value = 24002
I/CustomizationCIDLoader( 6213): add string-array item, value = 23210
I/CustomizationCIDLoader( 6213): add string-array item, value = 23205
I/CustomizationCIDLoader( 6213): add string-array item, value = 23806
I/CustomizationCIDLoader( 6213): add string-array item, value = 23430
I/CustomizationCIDLoader( 6213): add string-array item, value = 23408
I/CustomizationCIDLoader( 6213): add string-array item, value = 27205
I/CustomizationCIDLoader( 6213): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6213): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6213):  Read CID file spent 0.073 (s)
D/CustomizationManager( 6213):  All configurations done spent 0.073 (s)
--------- beginning of system
I/ActivityManager(  952): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6213 on display 0
D/PMS     (  952): acquireHCC(a51993c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 952 1000 null
D/PMS     (  952): acquireHCC(1d6b6c5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 952 1000 null
W/asset   (  952): Copying FileAsset 0x5594de1820 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  952): acquireWL(203d0d28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 952 1000 null
I/AnimationUtil(  952): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1597): [onPause]
I/FeedProviderManager( 1597): onPause
I/FeedHostManager( 1597): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3a1c7d6f
I/SocialFeedProvider( 1597): +onPause
I/SocialFeedProvider( 1597): -onPause
W/HtcSystemUPManager(  952): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  952): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6231 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  952): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  952): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  952): hiding MENU key
W/asset   ( 6231): Copying FileAsset 0xac19b818 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1597): [trimMemory] 20
,I/WebViewFactory( 6231): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  952):  packet count Tx=147 Rx=249
E/WifiTrafficPoller(  952): notifying of data activity 0
D/WIFI_ICON( 1217): WifiActivity: 0
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/LibraryLoader( 6231): Time to load native libraries: 9 ms (timestamps 5187-5196)
I/LibraryLoader( 6231): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6231): Binding Chromium to main looper Looper (main, tid 1) {32f002a6}
I/LibraryLoader( 6231): Expected native library version number "",actual native library version number ""
I/chromium( 6231): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6231): Initializing chromium process, singleProcess=true
W/art     ( 6231): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6231): ApplicationContext is null in ApplicationStatus
D/PMS     (  952): acquireWL(11abdb35): PARTIAL_WAKE_LOCK  *alarm* 0x1 952 1000 WorkSource{10072}
V/AlarmManager(  952): sending alarm PendingIntent{22f4abca: PendingIntentRecord{16c0e13b com.android.vending startService}}, i=null, t=0, cnt=1, w=1455124041743, Int=0
V/AlarmManager(  952): sending alarm PendingIntent{23621058: PendingIntentRecord{2dcbf5b1 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455124044555, Int=536832000
V/AlarmManager(  952): sending alarm PendingIntent{1c5469bb: PendingIntentRecord{9ca2ed8 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455124038717, Int=20000
V/CheckinService( 4338): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
D/PMS     (  952): acquireWL(1c99ba96): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4338 10024 WorkSource{10024 com.google.android.gms}
W/chromium( 6231): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
E/WifiStateMachine(  952): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  952): handleMessage: E msg.what=131143
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:394 rssi=-62 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.5 list=2412 [on:0 tx:0 rx:0 period:1578] from screen [on:0 period:-869868760]
E/WifiStateMachine(  952): processMsg: L2ConnectedState
D/PMS     (  952): releaseWL(11abdb35): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  952):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):3 dur:394 rssi=-62 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.5 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-869868759]
E/WifiStateMachine(  952): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.22 rxSuccessRate=1.55 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-62
D/PMS     (  952): acquireWL(813da04): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4338 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  952): WifiStateMachine CMD_START_SCAN with age=57897 interval=60000 maxinterval=300000
E/WifiStateMachine(  952): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  952): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/libEGL  ( 6231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/WifiConfigStore(  952): has c0:ff:d4:d3:aa:48 freq=2412 age=1585 ?=true
E/libEGL  ( 6231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/WifiStateMachine(  952): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1353): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1353): wpa_supplicant_scan enter
D/wpa_supplicant( 1353): wlan0: Starting AP scan for wildcard SSID
D/PMS     (  952): releaseWL(1c99ba96): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1353): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1353): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1353): WPS:  * Request Type
D/wpa_supplicant( 1353): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1353): WPS:  * UUID-E
D/wpa_supplicant( 1353): WPS:  * Primary Device Type
D/wpa_supplicant( 1353): WPS:  * RF Bands (3)
D/wpa_supplicant( 1353): WPS:  * Association State
D/wpa_supplicant( 1353): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1353): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1353): WPS:  * Manufacturer
D/wpa_supplicant( 1353): WPS:  * Model Name
D/wpa_supplicant( 1353): WPS:  * Model Number
D/wpa_supplicant( 1353): WPS:  * Device Name
D/wpa_supplicant( 1353): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1353): P2P: * P2P IE header
D/wpa_supplicant( 1353): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1353): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1353): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1353): wlan0: Add radio work 'scan'@0x5575ebb680
D/wpa_supplicant( 1353): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1353): wlan0: Starting radio work 'scan'@0x5575ebb680 after 0.000191 second wait
D/wpa_supplicant( 1353): wlan0: nl80211: scan request
D/wpa_supplicant( 1353): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1353): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1353): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1353): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1353): wlan0: Own scan request started a scan in 0.000216 seconds
I/wpa_supplicant( 1353): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  952): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  952): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/Adreno-EGL( 6231): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6231): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6231): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6231): Local Branch: 
I/Adreno-EGL( 6231): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6231): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6231):                  d74aa161a12b9c6fc6332151
E/WifiStateMachine(  952): [1,455,124,044,589 ms] noteScanstart no scan source
E/WifiStateMachine(  952): handleMessage: X
I/CheckinService( 4338): Checking schedule, now: 1455124044609 next: 1455124044555
I/CheckinService( 4338): active receiver: enabled
I/PackageManager(  952):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4338, uid=10024, userID:0
I/CheckinService( 4338): Preparing to send checkin request
I/EventLogService( 4338): Accumulating logs since 1455124008852
I/CheckinRequestBuilder( 4338): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  952): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4338): Failed to find provider info for com.google.android.wearable.settings
D/wpa_supplicant( 1353): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1353): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1353): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1353): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1353): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1353): wlan0: Scan completed in 0.077504 seconds
D/wpa_supplicant( 1353): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1353): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1353): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1353): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1353): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1353): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-82
I/wpa_supplicant( 1353): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
I/wpa_supplicant( 1353): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-84
D/wpa_supplicant( 1353): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1353): BSS: last_scan_res_used=5/32
D/wpa_supplicant( 1353): wlan0: Scan-only results received
D/wpa_supplicant( 1353): wlan0: Radio work 'scan'@0x5575ebb680 done in 0.078967 seconds
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  952): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  952): handleMessage: E msg.what=147461
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
D/WifiStateMachine(  952): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1353): wlan0: Control interface command 'LIST_DONGLES'
W/System.err(  952): java.lang.Throwable: stack dump
W/System.err(  952): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/ContextImpl(  952): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
W/System.err(  952): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  952): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  952): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  952): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12288f2b:true
E/WifiStateMachine(  952): [1,455,124,044,672 ms] noteScanEnd no scan source
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1353): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  952): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@13f95cb2 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  952): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  952): NG700 c0:ff:d4:d3:aa:48 rssi=-62 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  952): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  952): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  952):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-62 freq=2412
E/WifiAutoJoinController (  952): UPC503894600 a0:c5:62:7a:49:97 rssi=-82 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  952): Gonzos 38:f8:89:11:e9:11 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  952): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-84 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P] is not scored
E/WifiAutoJoinController (  952): ageScanResultsOut delay 40000 size 5 now 1455124044676
E/WifiAutoJoinController (  952): newSupplicantResults size=5 known=1 true
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/BluetoothAdapter( 6231): 1040181379: getState(). Returning 12
D/wpa_supplicant( 1353): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  952): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  952): ssid=NG700
E/WifiAutoJoinController (  952): id=0
E/WifiAutoJoinController (  952): mode=station
E/WifiAutoJoinController (  952): pairwise_cipher=CCMP
E/WifiAutoJoinController (  952): group_cipher=CCMP
E/WifiAutoJoinController (  952): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  952): wpa_state=COMPLETED
E/WifiAutoJoinController (  952): ip_address=192.168.1.130
E/WifiAutoJoinController (  952): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  952): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  952): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  952): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  952): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-62,-127) num=(1,0)
E/WifiAutoJoinController (  952): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  952): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-62 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  952): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  952): Done attemptAutoJoin status=0
E/WifiConfigStore(  952):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  952): handleMessage: X
W/art     ( 6231): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6231): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6231): CordovaWebView is running on device made by: HTC
W/art     ( 6231): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6231): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6231): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/art     (  952): Explicit concurrent mark sweep GC freed 40431(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/25MB, paused 3.220ms total 197.792ms
D/FindExtension( 6231): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/GLSUser ( 1801): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1801): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1801): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1801): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/InputMethodManager( 6231): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3446452e, mServedView=org.apache.cordova.engine.SystemWebView{1a93a8cf VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2d68225c
V/GLSActivity( 1801): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/InputMethodManagerService(  952): Disable input method client, pid=1597
D/StatusBarManagerService(  952): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  952): Enable input method client, pid=6231
D/Finsky  ( 5875): [582] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5875): [1] 5.onFinished: Installation state replication succeeded.
D/PMS     (  952): releaseWL(203d0d28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  952): Displayed com.test.thalitest/.MainActivity: +893ms
W/CheckinRequestBuilder( 4338): awaiting user notification for token
I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1331): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1217): reapply : com.google.android.gms 2 40
I/ActivityManager(  952): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6282 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/XT9_C   ( 1391): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1391): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1391): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1391): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6231): Cannot call determinedVisibility() - never saw a connection for the pid: 6231
W/ResourcesManager( 6282): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6282): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6282): VM with version 2.1.0 has multidex support
I/MultiDex( 6282): install
I/MultiDex( 6282): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6282): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/JsMessageQueue( 6231): Set native->JS mode to OnlineEventsBridgeMode
W/System  ( 6282): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34b4d442: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 6282): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 6282): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1801): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1801): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4338): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 4703): callingUid 10024, callindPid: 4703
E/MDM     ( 1974): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/jxcore_app_log( 6231): JniHelper::setJavaVM(0xab02f8f8), pthread_self() = -1405610344
E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  952):  packet count Tx=147 Rx=249
I/PackageManager(  952):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4338, uid=10024, userID:0
I/WVCdm   (  403): CdmEngine::OpenSession
I/WVCdm   (  403): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  403): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/LocationInitializer( 4338): Restart initialization of location
D/DrmWidevineDash(  403): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  403): Service_Initialize: starts!
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
E/QSEECOMAPI: (  403): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  403): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
D/QSEECOMAPI: (  403): Loaded image: APP id = 8
D/DrmWidevineDash(  403): Service_Initialize: ends! returns 0
D/QSAPPSVER(  403): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  403): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d58000
E/DrmWidevineDash(  403): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d58000
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  543): got the req here! ret=0
D/DrmLibTime(  543): command id, time_cmd_id = 770
D/DrmLibTime(  543): time_getutcsec starts!
D/DrmLibTime(  543): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  543): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  543): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  543): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  543): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  543): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  543): QSEE Time Listener: Retrieved Android system time: 1455124045
D/DrmLibTime(  543): time_getutcsec returns 0, sec = 1455124045; nsec = 0
D/DrmLibTime(  543): time_getutcsec finished! 
D/DrmLibTime(  543): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  543): before calling ioctl to read the next time_cmd
E/QC-time-services(  452): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/chromium( 6231): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  403): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: starts! SID=0xffece388
D/DrmWidevineDash(  403): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: starts! randomData=0xab89f1b0, dataLength=8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab8a2cd0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  403): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  403): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  403): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  403): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: starts! deviceID=0xab76f2b0, idLength=0xf4f826f8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4f8270e, maximum = 0xf4f8270f
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4f8277c
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  403): PrepareKeyRequest: nonce=2986066514
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab76e820
D/DrmWidevineDash(  403): message_length=1611, signature=0xab7f7f20, signature_length=0xf4f826dc
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  403): CdmEngine::CloseSession
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  403): L3 Terminate.
D/DrmWidevineDash(  403): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): Service_Uninitialize: starts!
D/QSEECOMAPI: (  403): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  403): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  403): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  403): OEMCrypto_Terminate: ends! returns 0
I/WVCdm   (  403): CdmEngine::OpenSession
I/WVCdm   (  403): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  403): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  403): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  403): Service_Initialize: starts!
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
E/QSEECOMAPI: (  403): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  403): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
D/QSEECOMAPI: (  403): Loaded image: APP id = 9
D/DrmWidevineDash(  403): Service_Initialize: ends! returns 0
D/QSAPPSVER(  403): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  403): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d58000
E/DrmWidevineDash(  403): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d58000
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  543): got the req here! ret=0
D/DrmLibTime(  543): command id, time_cmd_id = 770
D/DrmLibTime(  543): time_getutcsec starts!
D/DrmLibTime(  543): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  543): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  543): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  543): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  543): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  543): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  543): QSEE Time Listener: Retrieved Android system time: 1455124045
D/DrmLibTime(  543): time_getutcsec returns 0, sec = 1455124045; nsec = 0
D/DrmLibTime(  543): time_getutcsec finished! 
D/DrmLibTime(  543): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  543): before calling ioctl to read the next time_cmd
E/QC-time-services(  452): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  403): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: starts! SID=0xffece388
D/DrmWidevineDash(  403): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: starts! randomData=0xab7f8058, dataLength=8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab782690, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  403): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  403): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  403): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  403): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: starts! deviceID=0xab76f2d0, idLength=0xf3d596f8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: starts!, current = 0xf3d5970e, maximum = 0xf3d5970f
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf3d5977c
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  403): PrepareKeyRequest: nonce=4032569914
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab76e820
D/DrmWidevineDash(  403): message_length=1646, signature=0xab7fe0a0, signature_length=0xf3d596dc
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  403): CdmEngine::CloseSession
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  403): L3 Terminate.
D/DrmWidevineDash(  403): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): Service_Uninitialize: starts!
D/QSEECOMAPI: (  403): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  403): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  403): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  403): OEMCrypto_Terminate: ends! returns 0
,E/WifiStateMachine(  952): handleMessage: E msg.what=131155,
E/WifiStateMachine(  952): processMsg: ConnectedState
,E/WifiStateMachine(  952):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1417] from screen [on:0 period:-869867338] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
,E/WifiStateMachine(  952):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-869867337] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  952):  get link layer stats 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1353): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  952): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  952): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.11 txretriesrate=0.00 rxrate=0.77 userTriggerdPenalty0
E/WifiStateMachine(  952):  good link -> stuck count =0
E/WifiStateMachine(  952):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  952):  isHighRSSI       ---> score=61
,E/WifiStateMachine(  952): handleMessage: X,
D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -62, 3
,E/cutils-trace( 6320): Error opening trace file: Permission denied (13)
I/dex2oat ( 6320): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6320): dex2oat: override thread count:4
,D/PMS     (  952): releaseHCC(a51993c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
,D/PMS     (  952): releaseHCC(1d6b6c5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/dex2oat ( 6320): dex2oat took 73.208ms (threads: 4),
,I/Adreno-EGL( 6282): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6282): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6282): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6282): Local Branch: 
I/Adreno-EGL( 6282): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6282): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6282):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6282): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6282): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6282): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6282): Local Branch: 
I/Adreno-EGL( 6282): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6282): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6282):                  d74aa161a12b9c6fc6332151
,I/CheckinRequestBuilder( 4338): Classify the device as Phone.,
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  952):  packet count Tx=147 Rx=250,
E/WifiTrafficPoller(  952): notifying of data activity 1
D/WIFI_ICON( 1217): WifiActivity: 1
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/libc    ( 4338): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4338): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4338): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4338): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 4338): [NET] android_getaddrinfo_proxy+
D/libc    ( 4338): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4338): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4338): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4338): [NET] android_getaddrinfofornet-, err=8
,W/jxcore-log( 6231): Initializing JXcore engine,
W/jxcore-log( 6231): JXcore engine is ready
,D/libc    ( 4338): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4338): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4338): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4338): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4338): Sending checkin request (8416 bytes),
,W/jxcore-log( 6231): Starting JXcore engine,
,W/jxcore-log( 6231): Platform android,
W/jxcore-log( 6231): 
W/jxcore-log( 6231): Process ARCH arm
W/jxcore-log( 6231): 
,I/jxcore-log( 6231): JXcore Cordova bridge is ready!,
I/jxcore-log( 6231): 
W/jxcore-log( 6231): JXcore engine is started
,I/CheckinRequestBuilder( 4338): Checkin reason type: 11 attempt count: 1,
I/ActivityManager(  952): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4338): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 6231): Toggling radios to true,
I/jxcore-log( 6231): 
,D/BluetoothAdapter( 6231): enable(): BT is already enabled..!,
,D/WifiManager( 6231): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  952): New client listening to asynchronous messages
E/WifiTrafficPoller(  952): ADD_CLIENT: 7
,D/WifiService(  952): setWifiEnabled: true pid=6231, uid=10366
W/Settings:Agent(  952): MONITOR_LOG
E/WifiService(  952): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  952): name: wifi_on
I/WifiService(  952): isSprintWifiRestricted(): false
W/Settings:Agent(  952): value: 2
I/WifiService(  952): isMdmWifiRestricted(): false
W/Settings:Agent(  952): >> traceCallingStack()
W/Settings:Agent(  952): Process.myPid(): 952
W/Settings:Agent(  952): Process.myTid(): 990
W/Settings:Agent(  952): Process.myUid(): 1000
W/Settings:Agent(  952): 
W/Settings:Agent(  952): 
W/System.err(  952): java.lang.Throwable: stack dump
,W/System.err(  952): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  952): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  952): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  952): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  952): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  952): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  952): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  952): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  952): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  952): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  952): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  952): 
W/Settings:Agent(  952): << traceCallingStack(): 12(ms)
D/WifiManager( 6231): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  952): handleMessage: E msg.what=155656
D/WifiController(  952): processMsg: DeviceActiveState
D/WifiController(  952): processMsg: StaEnabledState
D/WifiManager( 6231): reconnect: Base Package Name=com.test.thalitest, uid=10366
,D/WifiController(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131145
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1353): wlan0: Cancelling scan request
D/wpa_supplicant( 1353): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1353): TDLS: Tear down peers
D/wpa_supplicant( 1353): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6231): Radios toggled
I/jxcore-log( 6231): 
,I/jxcore-log( 6231): My device name is: HTC-HTC One M8s
I/jxcore-log( 6231): 
,I/GLSUser ( 1801): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1801): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1801): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1801): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1801): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/wpa_supplicant( 1353): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1353): wlan0: Deauthentication notification
D/wpa_supplicant( 1353): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1353): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1353): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1353): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1353): enter disconnect check
I/wpa_supplicant( 1353): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1353): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1353): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  952): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  952): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  952): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/Tethering(  952): interfaceLinkStateChanged wlan0, false
D/Tethering(  952): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  952): interfaceLinkStateChanged wlan0, false
D/Tethering(  952): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  952): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  952): TetherInterfaceSM: wlan0: exit InitialState
D/UsbDeviceManager(  952): [USBNET] bCheckSuppFunc: cdc_network
V/Tethering(  952): TetherInterfaceSM: wlan0: enter UnavailableState
D/PMS     (  952): acquireWL(3e57c0fb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 952 1000 null
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  952): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  952): BroadcastReceiver::onReceive+
D/UsbnetService(  952): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  952): BroadcastReceiver::onReceive-
,D/wpa_supplicant( 1353): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1353): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5575eb8f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1353):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1353): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1353): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1353): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1353): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1353): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1353): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1353): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1353): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1353): Wireless event: cmd=0x8b15 len=24
D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1353): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1353): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  952): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  952): handleMessage: new destination call exit/enter
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  952): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  952): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  952): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  952): invokeExitMethods: ConnectedState
E/WifiStateMachine(  952): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  952): release()
E/WifiStateMachine(  952): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  952): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  952): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  952): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit ,- invokeExitMethods
E/WifiStateMachine(  952): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  952): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  952): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  952): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1353): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1353): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1353): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1353): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1353): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  952): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1353): Power_Mode_Type mode = 0
I/wpa_supplicant( 1353): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  952): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  952): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  952): setDhcpActive: false
V/NativeCrypto( 1801): Read error: ssl=0x55948d39e0: I/O error during system call, Connection timed out
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
D/TetherSettings( 5846): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5846): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5846): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5846): Cust_ConnectToPC   : spcsc>false
D/        ( 5846): Cust_ConnectToPC   : IPT>true
D/        ( 5846): Cust_ConnectToPC   : Singel_USB>false
D/PMS     (  952): releaseWL(3e57c0fb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  952): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  952): setDetailed state send new extra info<unknown ssid>
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  952): acquireWL(22d771d7): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  952): NetworkAgent != null
V/NetworkPolicy(  952): updateNetworkEnabledLocked()
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  952): updateNotificationsLocked()
E/WifiTrafficPolle,r(  952): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/ConnectivityService(  952): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiTrafficPoller(  952):  packet count Tx=163 Rx=263
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  952): notifying of data activity 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/Settings( 5846): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WIFI_ICON( 1217): WifiActivity: 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NativeCrypto( 1801): SSL shutdown failed: ssl=0x55948d39e0: I/O error during system call, Broken pipe
V/NetworkPolicy(  952): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  952): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/SmartNS_Utility( 5846): hasRemovableStorageSlot: true
D/WifiDataStallTracker(  952): stopDataStallAlarm 
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/SmartNS_Utility( 5846): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5846): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiDataStallTracker(  952): ENABLE_DATA_MONITOR_POLL false Token 1
D/ConnectivityService(  952): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  952): autoRoamSetBSSID any key="NG700"WPA_PSK
D/ConnectivityService(  952): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiConfigStore(  952): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  952): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1353): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1353): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1353): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1353): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1353): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  952): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  952): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  952): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  952):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  952): Start Disconnecting Watchdog 1
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131146
E/WifiStateMachine(  952): processMsg: DisconnectingState
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): DefaultState{ when=-3ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): Forcing reevaluation
E/WifiStateMachine(  952):  DisconnectingState !CMD_RECONNECT 0 0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  952): processMsg: ConnectModeState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): Validated
E/WifiStateMachine(  952):  ConnectModeState !CMD_RECONNECT 0 0
D/PMS     (  952): releaseWL(22d771d7): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1353): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1353): wlan0: Selecting BSS from priority group 677
D/wpa_supplicant( 1353): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/wpa_supplicant( 1353): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1353): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1353): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-62 wps
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1353): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1353): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1353): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1353):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1353): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1353): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x5575ebac00  current_ssid=0x0
D/wpa_supplicant( 1353): wlan0: Request association with c0:ff:d4:d3:aa:48
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1353): wpa_supplicant_set_is_wep_security: 0
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1353): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1353): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1353): wlan0: Add radio work 'connect'@0x5575ebb680
D/wpa_supplicant( 1353): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1353): wlan0: Starting radio work 'connect'@0x5575ebb680 after 0.000136 second wait
I/wpa_supplicant( 1353): check if in concurrent case
I/wpa_supplicant( 1353): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147460
E/WifiStateMachine(  952): processMsg: DisconnectingState
D/WifiMonitor(  952): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=35 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  952):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=97966
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=97967
E/WifiStateMachine(  952): ConnectModeState: Network connection lost 
E/WifiStateMachine(  952): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  952): handleMessage: new destination call exit/enter
E/WifiStateMachine(  952): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  952): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  952): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  952): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  952): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  952): DisconnectedState call setCountryCode()
E/WifiStateMachine(  952):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1353): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1353): wlan0: Cancelling scan request
D/wpa_supplicant( 1353): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1353): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1353): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1353): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1353): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1353): RSN: PMKSA cache search - network_ctx=0x5575ebac00 try_opportunistic=0
D/wpa_supplicant( 1353): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1353): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1353): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1353): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1353): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1353): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1353): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1353): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1353): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1353): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): wlan0: State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1353): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1353): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1353): nl80211: Unsubscribe mgmt frames handle 0x888888ddfd632989 (mode change)
D/wpa_supplicant( 1353): nl80211: Subscribe to mgmt frames with non-AP handle 0x5575eba100
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=0104
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=040a
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=040b
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=040c
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=040d
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=090a
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=090b
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=090c
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=090d
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=0409506f9a09
,D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=7f506f9a09
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=0801
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=040e
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=06
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=0a07
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=0a11
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5575eba100 match=0a1a
D/wpa_supplicant( 1353): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1353):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353):   * freq=2412
D/wpa_supplicant( 1353):   * freq_hint=2412
D/wpa_supplicant( 1353):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1353):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1353):   * WPA Versions 0x2
D/wpa_supplicant( 1353):   * pairwise=0xfac04
D/wpa_supplicant( 1353):   * group=0xfac04
D/wpa_supplicant( 1353):   * akm=0xfac02
D/wpa_supplicant( 1353):   * Auth Type 0
D/wpa_supplicant( 1353): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5575ebac3a
D/wpa_supplicant( 1353): nl80211: Connect request send successfully
D/wpa_supplicant( 1353): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1353): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1353): EAPOL: External notification - EAP fail=0
D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
D/wpa_supplicant( 1353): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1353): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1353): Ongoing scan action - reject new request
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  952): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  952): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  952): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131101
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
W/ContextImpl( 5846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
I/SmartNS_Utility( 5846): setISNotification
E/WifiStateMachine(  952):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  952): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  952): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147462
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=97978  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  952): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  952): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=97979  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/SmartNS_Utility( 5846): usb_cable_connect = 1
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131212
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
D/SmartNS_Utility( 5846): usb_denied = 0
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  952): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131212
E/WifiStateMachine(  952): processMsg: DisconnectedState
I/SmartNS_PSService( 5846): usb notificaiton:true
E/WifiStateMachine(  952):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  952):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  952): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131212
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
I/ActionCombine( 5846): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
E/WifiStateMachine(  952):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  952): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  952): handleMessage: X
D/WifiNetworkAgent(  952): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  952): handleMessage: E msg.what=131213
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=97992
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=97993
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=97993
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=97993
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147462
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=97995  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  952): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  952): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  952): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  952): NetworkAgent == null
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  952): processMsg: ConnectModeState
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  952):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=98000  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  952): handleMessage: X
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/SmartNS_Utility( 5846): usb_cable_connect = 1
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/SmartNS_Utility( 5846): usb_denied = 0
I/SmartNS_PSService( 5846): usb notificaiton:true
I/QuickSettingWifi( 1217): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 14
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
W/CheckinRequestBuilder( 4338): awaiting user notification for token
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1217): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5846): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1331): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1217): reapply : com.google.android.gms 2 40
,D/ConnectivityService(  952): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  952): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  952):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  952): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/usbnet  (  952): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/Nat464Xlat(  952): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  952): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): Disconnected - quitting
D/ConnectivityService(  952): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  952): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  952): Removing idletimer
D/WIFI    (  952):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  952): acquireWL(30c31dad): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 952 1000 null
D/WIFI    (  952): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
,E/WifiStateMachine(  952): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/CSLegacyTypeTracker(  952): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  952): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  952): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  952): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy(  952): ensureActiveMobilePolicyLocked()
D/PMS     (  952): acquireWL(16ec88e2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 952 1000 null
D/Tethering(  952): Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
D/Tethering(  952): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  952): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524292
I/SecurityController( 1217): onLost 100
,D/NetworkPolicy(  952): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  952): updateNetworkEnabledLocked()
V/NetworkPolicy(  952): updateIfacesLocked()
V/NetworkPolicy(  952): updateNotificationsLocked(),
D/PMS     (  952): releaseWL(16ec88e2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/RemoteViews( 1217): reapply : com.android.settings 1 36
V/NetworkPolicy(  952): updateNetworkEnabledLocked()
V/NetworkPolicy(  952): updateNotificationsLocked()
D/NetworkManagementService(  952): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DATA_ICON( 1217): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,D/WISPrService( 5846): >>>>>WISPrService start isConnected = true<<<<<
D/DATA_ICON( 1217): dataConnected: false/false
I/CheckinRequestBuilder( 4338): Classify the device as Phone.
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiService(  952): New client listening to asynchronous messages
E/WifiTrafficPoller(  952): ADD_CLIENT: 8,
,E/WifiStateMachine(  952): handleMessage: E msg.what=131131
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine(  952): handleMessage: X
,W/WISPrService( 5846): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5846): trigger connection
D/WISPrService( 5846): continue
,I/ActivityManager(  952): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6341 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5846): start DataConnection
,D/libc    ( 5846): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5846): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/wpa_supplicant( 1353): Wireless event: cmd=0x8c02 len=271
D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
I/wpa_supplicant( 1353): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
,D/Tethering(  952): interfaceLinkStateChanged wlan0, false
D/Tethering(  952): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1353): Wireless event: cmd=0x8c02 len=46
I/wpa_supplicant( 1353): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1353): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1353): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
D/wpa_supplicant( 1353): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1353): nl80211: Connect event
D/wpa_supplicant( 1353): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1353): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1353): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1353): wlan0: Association info event
D/wpa_supplicant( 1353): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): wlan0: freq=2412 MHz
D/wpa_supplicant( 1353): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1353): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  952): interfaceLinkStateChanged wlan0, false
D/Tethering(  952): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1353): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1353): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1353): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1353): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1353): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1353): TDLS: Remove peers on association
D/wpa_supplicant( 1353): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1353): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1353): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1353): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1353): EAPOL: enable timer tick
D/wpa_supplicant( 1353): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1353): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1353): wlan0: Cancelling scan request
D/wpa_supplicant( 1353): wlan0: Process pending EAPOL frame that was received just before association notification
D/wpa_supplicant( 1353): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1353): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1353): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1353): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1353): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1353):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1353):   key_nonce - hexdump(len=32): 53 e0 d1 2b 71 62 76 8d fc 8f 32 c0 50 24 60 4a ed a8 61 b1 79 38 34 0d 44 5a 64 37 0b 91 60 0d
D/wpa_supplicant( 1353):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1353): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1353): RSN: msg 1/4 key data - hexdump(len=0):
D/Tethering(  952): interfaceLinkStateChanged wlan0, false
D/Tethering(  952): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/libc    ( 5846): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5846): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5846): [NET] android_getaddrinfo_proxy+
D/wpa_supplicant( 1353): WPA: Renewed SNonce - hexdump(len=32): 74 ca e9 f9 f6 49 c3 09 42 cf 28 8f 44 00 5c 8d ed 38 f7 10 d8 e4 e9 b9 a4 53 72 a1 a6 2d 70 94
D/wpa_supplicant( 1353): WPA: Nonce1 - hexdump(len=32): 74 ca e9 f9 f6 49 c3 09 42 cf 28 8f 44 00 5c 8d ed 38 f7 10 d8 e4 e9 b9 a4 53 72 a1 a6 2d 70 94
D/wpa_supplicant( 1353): WPA: Nonce2 - hexdump(len=32): 53 e0 d1 2b 71 62 76 8d fc 8f 32 c0 50 24 60 4a ed a8 61 b1 79 38 34 0d 44 5a 64 37 0b 91 60 0d
D/wpa_supplicant( 1353): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1353): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1353): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1353): wlan0: WPA: Sending EAPOL-Key 2/4
D/Tethering(  952): interfaceLinkStateChanged wlan0, true
D/wpa_supplicant( 1353): WPA: KCK - hexdump(len=16): [REMOVED]
D/Tethering(  952): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1353): WPA: Derived Key MIC - hexdump(len=16): 61 43 46 0c 7f 87 18 df c6 3f 59 8c db 6a c2 75
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
I/wpa_supplicant( 1353): htc_wext_set_keepalive +
I/wpa_supplicant( 1353): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1353): getPrivFuncNum +	
D/libc    ( 5846): [NET] android_getaddrinfo_proxy get netid:0
I/wpa_supplicant( 1353): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1353): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1353): htc_wext_set_keepalive - ret = 0
V/Tethering(  952): TetherInterfaceSM: wlan0: enter InitialState
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  952): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5846): [NET] android_getaddrinfo_proxy-, NODATA
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange(): SSIDNG700,
D/WifiMonitor(  952): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  952): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  952): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  952): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  952): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  952): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  952): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  952): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  952): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/WifiMonitor(  952): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  952): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1353): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1353): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1353): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1353): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1353):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1353):   key_nonce - hexdump(len=32): 53 e0 d1 2b 71 62 76 8d fc 8f 32 c0 50 24 60 4a ed a8 61 b1 79 38 34 0d 44 5a 64 37 0b 91 60 0d
D/wpa_supplicant( 1353):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_rsc - hexdump(len=8): f7 38 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_mic - hexdump(len=16): 37 38 f2 7d 36 3f 1e b6 a1 8f 06 7b 63 51 11 f5
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1353): RSN: encrypted key data - hexdump(len=56): 0b 2d 1a ce 13 36 00 29 af ce 10 19 4c 32 f6 7a 75 48 0f 1a ba cd af 15 a5 7d eb 5a dc 06 71 de ...
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1353): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1353): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/HTCRequest(  952): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1353): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1353): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 23 6c ...
D/wpa_supplicant( 1353): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1353): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1353): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1353): WPA: Derived Key MIC - hexdump(len=16): 3f 4d 1a 7a cd 52 e5 5e dd e7 c7 f2 7d a8 6e b4
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1353): wlan0: WPA: Installing PTK to the driver
D/WifiMonitor(  952): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5575ebb390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1353): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1353): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1353):    addr=c0:ff:d4:d3:aa:48
E/WifiStateMachine(  952): handleMessage: E msg.what=147462
E/WifiStateMachine(  952): processMsg: DisconnectedState
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1353): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1353): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1353): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1353): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1353): WPA: RSC - hexdump(len=6): f7 38 00 00 00 00
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x557255ce68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1353): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1353): nl80211: KEY_SEQ - hexdump(len=6): f7 38 00 00 00 00
D/wpa_supplicant( 1353):    broadcast key
E/WifiStateMachine(  952):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=98092  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  952): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  952): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  952): setDetailed state send new extra info0x
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 1353): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  952): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1353): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1353): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1353): wlan0: Radio work 'connect'@0x5575ebb680 done in 0.128842 seconds
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1353): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1353): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  952): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  952): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  952): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  952): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=42 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  952): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/wpa_supplicant( 1353): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 1353): set send_ind_to_ndc = 0
I/wpa_supplicant( 1353): htc_wext_set_TX_TRACKING (1)+
D/WifiMonitor(  952): Event [IFNAME=wlan0 Connect to SSID: NG700]
I/wpa_supplicant( 1353): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1353): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1353): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1353): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1353): EAP: EAP entering state DISABLED
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=44 dispatchEvent: Connect to SSID: NG700
D/wpa_supplicant( 1353): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1353): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1353): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
W/WifiMonitor(  952): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  952): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1353): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1353): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1353): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/Tethering(  952): interfaceLinkStateChanged wlan0, true
D/Tethering(  952): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  952): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  952):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=98099  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147500
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  952): Enter handleAssociatedWithEvent
D/WifiStateMachine(  952): Associated
D/WifiStateMachine(  952): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  952): Exit handleAssociatedWithEvent
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147462
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=98101  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  952): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  952): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  952): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  952): NetworkAgent == null
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=98110  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147462
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=98111  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  952): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  952): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=98112  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147459
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=98112
D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  952): processMsg: ConnectModeState
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/Tethering(  952): sendTetherStateChangedBroadcast 1, 0, 0
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  952):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=98113
E/WifiStateMachine(  952): Network connection established
D/WifiStateMachine(  952): fetchFrequency(), freq = 2412
E/WifiStateMachine(  952): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 18
D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
E/WifiStateMachine(  952): NetworkAgent == null
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetService(  952): BroadcastReceiver::onReceive+
D/PMS     (  952): acquireWL(e775565): PARTIAL_WAKE_LOCK  NetworkStats 0x1 952 1000 null
D/UsbnetService(  952): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbDeviceManager(  952): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  952): BroadcastReceiver::onReceive-
D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  952): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  952): handleMessage: new destination call exit/enter
D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
E/WifiStateMachine(  952): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
E/WifiStateMachine(  952): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  952): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  952): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  952): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  952): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  952): invokeEnterMethods: L2ConnectedState
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 20
E/WifiStateMachine(  952): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  952): NetworkAgent == null
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/CheckinTask( 4338): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/PMS     (  952): releaseWL(e775565): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  952): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  952): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  952): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  952): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  952): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1353): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1353): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1353): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/ConnectivityService(  952): Got NetworkAgent Messenger
D/ConnectivityService(  952): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  952): NetworkAgent connected
D/wpa_supplicant( 1353): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1353): CTRL_IFACE: SAVE_CONFIG - Configuration updated
V/NetworkPolicy(  952): updateNetworkEnabledLocked()
V/NetworkPolicy(  952): updateNotificationsLocked()
E/WifiStateMachine(  952): invokeEnterMethods: ObtainingIpState
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  952): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  952): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  952): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  952): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  952): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1353): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1353): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SAVE_CONFIG'
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1353): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1353): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1353): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  952): Start Dhcp Watchdog 2
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147462
E/WifiStateMachine(  952): processMsg: ObtainingIpState
E/WifiStateMachine(  952):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=98140  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=98140  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=98141  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  952): handleMessage: X
D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    ( 5846): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5846): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5846): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
I/ActivityManager(  952): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6366 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
I/CheckinService( 4338): Checking schedule, now: 1455124047432 next: 1455660879394
I/CheckinService( 4338): active receiver: disabled
D/WISPrService( 5846): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  952): handleMessage: E msg.what=131101
E/WifiStateMachine(  952): processMsg: ObtainingIpState
E/WifiStateMachine(  952):  ObtainingIpState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
I/PackageManager(  952):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4338, uid=10024, userID:0
E/WifiStateMachine(  952):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  952): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  952): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131155
E/WifiStateMachine(  952): processMsg: ObtainingIpState
E/WifiStateMachine(  952):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1413] from screen [on:0 period:-869865908] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL false Token 22 num clients 8
E/WifiStateMachine(  952):  L2ConnectedState !CMD_RSSI_POLL 2, 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-869865907] gl hn u24 rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  952):  get link layer stats 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SIGNAL_POLL'
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
I/wpa_supplicant( 1353): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  952): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
,D/WISPrService( 5846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  952): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=82.00 txretriesrate=0.00 rxrate=131.50 userTriggerdPenalty0
E/WifiStateMachine(  952):  good link -> stuck count =0
E/WifiStateMachine(  952):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  952):  isHighRSSI       ---> score=65
E/WifiStateMachine(  952): calculateWifiScore() report new score 60
,I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
,E/WifiStateMachine(  952): handleMessage: X
D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -62, 3
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED -1 -> 3
I/art     (  411): Explicit concurrent mark sweep GC freed 8686(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 177us total 22.163ms
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  952): handleMessage: E msg.what=131212
E/WifiStateMachine(  952): processMsg: ObtainingIpState
D/ConnectivityService(  952): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  952):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  952): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  952): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  952): handleMessage: X
D/ConnectivityService(  952): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,E/WifiStateMachine(  952): handleMessage: E msg.what=196612
E/WifiStateMachine(  952): processMsg: ObtainingIpState
E/WifiStateMachine(  952):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=164,0,0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
,E/WifiStateMachine(  952):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=164,0,0
D/WifiStateMachine(  952): handlePreDhcpSetup Held wake lock during DHCP
D/WifiDataStallTracker(  952): setDhcpActive: true
D/PMS     (  952): acquireWL(1e11c460): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 952 1000 null
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiStateMachine(  952): handlePreDhcpSetup mBluetoothConnectionActive: false
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
,E/WifiStateMachine(  952): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  952): do suspend false
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1353): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1353): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1353): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  952): Unexpected BatchedScanResults :null
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  952): noteBatchedScanstop()
E/WifiStateMachine(  952): handleMessage: X
,D/WifiP2pService(  952): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3113da84 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  952): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3113da84 target=com.android.internal.util.StateMachine$SmHandler }
,I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 170us total 17.165ms
,D/PMS     (  952): releaseWL(813da04): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun,
I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 149us total 20.239ms,
W/ResourcesManager( 6366): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
D/WifiService(  952): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,I/ActivityManager(  952): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6387 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/CalendarProvider2( 6366): Created com.android.providers.calendar.CalendarAlarmManager@313675e8(com.htc.providers.calendar.HtcCalendarProvider@258d1401),
,D/CalendarProvider2( 6366): wait start:true
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 6366): wait end:false
,D/MdScPhnSt( 6387): [5fc.2.]  listen tmrbb8
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,E/dhcpcd  ( 6416): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6416): version 5.5.6 starting,
E/dhcpcd  ( 6416): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6416): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6416): autoip env[11]:autoip=DISABLE
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/TetherSettings( 5846): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5846): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5846): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5846): Cust_ConnectToPC   : spcsc>false
D/        ( 5846): Cust_ConnectToPC   : IPT>true
D/        ( 5846): Cust_ConnectToPC   : Singel_USB>false,
W/Settings( 5846): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5846): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5846): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5846): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 ,
I/SmartNS_Utility( 5846): setISNotification
D/SmartNS_Utility( 5846): usb_cable_connect = 1
D/SmartNS_Utility( 5846): usb_denied = 0
I/SmartNS_PSService( 5846): usb notificaiton:true
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/MdProvGlob( 6341): remove item 101 (p2d27in202) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 6387): [5fc.2.] summary 118:p2 ignore
,D/SmartNS_Utility( 5846): usb_cable_connect = 1
D/SmartNS_Utility( 5846): usb_denied = 0
I/SmartNS_PSService( 5846): usb notificaiton:true
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/dhcpcd  ( 6416): wlan0: rebinding lease of 192.168.1.130
I/RemoteViews( 1217): reapply : com.android.settings 1 36
I/dhcpcd  ( 6416): wlan0: sending REQUEST (xid 0x129cb679), next in 0.28 seconds
,D/SmartNS_NSReceiver( 5846): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1217): reapply : com.android.settings 1 36
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,I/ActivityManager(  952): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6428 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/PhoneMonitor( 6428): Register our PhoneStateListener
,V/SetupWizard( 6428): Connected to Gservices successfully,
D/Process (  952): killProcessQuiet, pid=5398,
I/ActivityManager(  952): Killing 5398:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 6428): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 6428): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,I/ActivityManager(  952): Recipient 5398
,D/MediaRouterService(  952): Client com.google.android.music (pid 5398): Died!
,D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/Kids    ( 4338): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false,
,D/PMS     (  952): acquireWL(301f6a45): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1801 10024 WorkSource{10024 com.google.android.gms},
D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/GCM     ( 1801): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1801): [NET] android_getaddrinfofornet-, err=8
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1801): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1801): [NET] android_getaddrinfo_proxy+
D/libc    ( 1801): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1801): [NET] android_getaddrinfo_proxy-, NODATA
W/ContextImpl(  952): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/PMS     (  952): acquireWL(301f6a45): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1801): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  952): releaseWL(301f6a45): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/FlexNetS( 6366): updateSvcAllowedInSettings:false
,I/dhcpcd  ( 6416): wlan0: sending REQUEST (xid 0x129cb679), next in 2.32 seconds,
,I/dhcpcd  ( 6416): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL false Token 22 num clients 8,
,I/dhcpcd  ( 6416): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6416): autoip env[11]:autoip=DISABLE
,D/libc    (  952): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  952): handleMessage: E msg.what=131212
E/WifiStateMachine(  952): processMsg: ObtainingIpState
E/WifiStateMachine(  952):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  952): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  952): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  952): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  952): handleMessage: X
,D/wpa_supplicant( 1353): EAPOL: startWhen --> 0
D/wpa_supplicant( 1353): EAPOL: disable timer tick
,I/dhcpcd  ( 6416): bind_interface: daemonise,
,D/libc    (  952): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  952): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  952): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  952): releaseWL(1e11c460): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/libc    (  952): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  952): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  952): handleMessage: E msg.what=196613
E/WifiStateMachine(  952): processMsg: ObtainingIpState
E/WifiStateMachine(  952):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  952): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1353): Power_Mode_Type mode = 0
I/wpa_supplicant( 1353): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  952): setDhcpActive: false
E/WifiStateMachine(  952): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  952): WifiStateMachine DHCP successful
E/WifiStateMachine(  952): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  952): link address 192.168.1.130/24
E/WifiStateMachine(  952): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  952): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov,
E/WifiStateMachine(  952): gateway: /192.168.1.1
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1353): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  952): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131210
E/WifiStateMachine(  952): processMsg: ObtainingIpState
E/WifiStateMachine(  952):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1353): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  952): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1353): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1353): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  952): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=46 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  952): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  952): NetworkAgent != null
D/ConnectivityService(  952): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
V/NetworkPolicy(  952): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  952): Adding iface wlan0 to network 101
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  952): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  952): WAN detection
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED connected
D/HtcWifiWanDetect(  952): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL true Token 22
E/WifiTrafficPoller(  952):  packet count Tx=165 Rx=264
E/WifiStateMachine(  952): transitionTo: destState=ConnectedState
E/WifiDataStallTracker(  952): ENABLE_DATA_MONITOR_POLL true Token 2
E/WifiStateMachine(  952): handleMessage: new destination call exit/enter
E/WifiStateMachine(  952): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  952): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  952): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  952): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  952): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  952): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  952): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/NetworkPolicy(  952): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL true Token 23
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5846): >>>>>WISPrService start isConnected = true<<<<<
,E/WifiTrafficPoller(  952):  packet count Tx=165 Rx=264
E/WifiTrafficPoller(  952): notifying of data activity 0
D/WifiDataStallTracker(  952): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  952): updateDataStallInfo: NONE
D/WifiDataStallTracker(  952): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiDataStallTracker(  952): DATA_MONITOR_POLL true Token 3
,E/ConnectivityService(  952): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  952): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  952): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  952): ConnectedState Enter  mScreenOn=true scanperiod=20000
E/WifiStateMachine(  952): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
E/WifiStateMachine(  952): handleMessage: X
D/ConnectivityService(  952): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,E/WifiStateMachine(  952): handleMessage: E msg.what=131131
,E/WifiStateMachine(  952): processMsg: ConnectedState
D/ConnectivityService(  952): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  952):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  952): processMsg: L2ConnectedState
,E/WifiStateMachine(  952):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/Nat464Xlat(  952): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
,E/WifiStateMachine(  952): processMsg: ConnectModeState
D/ConnectivityService(  952): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  952): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  952): rematching NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  952):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  952):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  952): handleMessage: X
D/ConnectivityService(  952):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/ConnectivityService(  952):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  952): currentScore = 0, newScore = 20
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  952):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): Connected
D/ConnectivityService(  952): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  952): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): Validated
D/ConnectivityService(  952): sendGeneralBroadcast, restrictEnable=false
D/usbnet  (  952): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  952): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/usbnet  (  952):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  952): sendGeneralBroadcastDelayed, restrictEnable=false
D/usbnet  (  952): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  952): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WIFI    (  952): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/PMS     (  952): acquireWL(562ecb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 952 1000 null
D/WIFI    (  952):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  952): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/WIFI    (  952): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
V/NetworkPolicy(  952): ensureActiveMobilePolicyLocked()
D/Tethering(  952): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/DATA_ICON( 1217): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/Tethering(  952): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  952): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/WISPrService( 5846): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  952): Validated
D/ConnectivityService(  952): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  952): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  952): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524290
D/ConnectivityService(  952):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  952):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  952): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  952): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  952): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/usbnet  (  952):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  952): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  952): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  952): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
I/SecurityController( 1217): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkPolicy(  952): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524290
V/NetworkPolicy(  952): updateNetworkEnabledLocked()
,D/WIFI    (  952): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  952): updateIfacesLocked()
D/WIFI    (  952):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  952): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  952): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  952): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  952): Validated NetworkAgentInfo [WIFI () - 101]
V/NetworkPolicy(  952): updateNotificationsLocked()
D/ConnectivityService(  952): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  952):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  952):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  952): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  952): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  952): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkManagementService(  952): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DATA_ICON( 1217): dataConnected: false/false
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  952): releaseWL(562ecb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/DATA_ICON( 1217): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
I/SecurityController( 1217): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524290
,I/SecurityController( 1217): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1217): dataConnected: false/false
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/QuickSettingWifi( 1217): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,V/NetworkPolicy(  952): updateNetworkEnabledLocked()
V/NetworkPolicy(  952): updateNotificationsLocked()
,I/QuickSettingWifi( 1217): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/CalendarProvider2( 6366): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6366): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  952): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6480 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/Process (  952): killProcessQuiet, pid=5711,
I/ActivityManager(  952): Killing 5711:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  412): Explicit concurrent mark sweep GC freed 8659(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 342us total 18.093ms
,I/art     (  412): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 221us total 14.745ms
,I/art     (  412): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 216us total 14.074ms,
,I/ActivityManager(  952): Recipient 5711,
,D/libc    (  952): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  952): handleMessage: E msg.what=131212
E/WifiStateMachine(  952): processMsg: ConnectedState
,I/HtcModeClient( 3155): handler message = 4011
E/WifiStateMachine(  952):  ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/HtcModeClient( 3155): Check connection and retry 12 times.,
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  952): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0},
E/WifiStateMachine(  952): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  952): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  952): identical MTU - not setting
D/Nat464Xlat(  952): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  952): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ],
,D/ConnectivityService(  952): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  952): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524295
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  952):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  952): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524295
,E/WifiStateMachine(  952): handleMessage: X
,W/ResourcesManager( 6480): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/CalendarApplication( 6480): onCreate
D/ProviderChangeReceiver( 6480): ---------------------------------------------------
D/ProviderChangeReceiver( 6480): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
D/Process (  952): killProcessQuiet, pid=5823
I/ActivityManager(  952): Killing 5823:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 6480): start to updateAlertNotification!
,I/ActivityManager(  952): Recipient 5823
,D/HtcAlertService( 6480): No fired or scheduled alerts
D/HtcAlertUtils( 6480): -- cancelReminderNotification --
,D/HtcAlertUtils( 6480): broadcastExistReminder!
,D/DotMatrix( 1331): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  952): handleMessage: E msg.what=131155,
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=82.0, 0.0, 0.0  rx=131.5 bcn=0 [on:0 tx:0 rx:0 period:1577] from screen [on:0 period:-869864320] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=82.0, 0.0, 0.0  rx=131.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-869864319] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952): handleMessage: X
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1217): WifiActivity: 3
E/WifiTrafficPoller(  952):  packet count Tx=166 Rx=265
E/WifiTrafficPoller(  952): notifying of data activity 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  952): releaseWL(30c31dad): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  952): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/Process (  952): killProcessQuiet, pid=6102,
I/ActivityManager(  952): Killing 6102:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/ConnectivityService(  952): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  952): Recipient 6102
,D/GpsLocationProvider(  952): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  952): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  952): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  952): acquireWL(22f5f6a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 952 1000 null
D/GpsLocationProvider(  952): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/htcCheckinService(  952): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/ConnectivityHelper( 1597): [onReceive] WIFI(1): CONNECTED
,E/WifiStateMachine(  952): handleMessage: E msg.what=131155
,E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=82.0, 0.0, 0.0  rx=131.5 bcn=0 [on:0 tx:0 rx:0 period:1419] from screen [on:0 period:-869862899] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
,E/WifiStateMachine(  952):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=82.0, 0.0, 0.0  rx=131.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-869862897] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952):  get link layer stats 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1353): wlan0: Control interface command 'SIGNAL_POLL'
,I/ActivityManager(  952): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6505 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/wpa_supplicant( 1353): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72,
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  952): BroadcastRSSIForIMS, newrssi =-62 , oldRssi= -200
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiConfigStore(  952): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3,
D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -62, 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  952): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=42.00 txretriesrate=0.00 rxrate=66.75 userTriggerdPenalty0
E/WifiStateMachine(  952):  good link -> stuck count =0
E/WifiStateMachine(  952):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  952):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -62, 3
E/WifiStateMachine(  952): handleMessage: X
,D/MdScPhnSt( 6387): [1ea.1.]  listen tmrbb8
,D/MdScDataSum( 6387): [1ea.1.] summary 118:p1 ignore,
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8,
D/WIFI_ICON( 1217): WifiActivity: 0
E/WifiTrafficPoller(  952):  packet count Tx=166 Rx=265
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  952): notifying of data activity 0
,I/art     (  952): Explicit concurrent mark sweep GC freed 59573(3MB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 17MB/25MB, paused 2.575ms total 157.211ms
,E/GpsLocationProvider(  952): No APN found to select.
,D/PMS     (  952): releaseWL(22f5f6a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
D/PMS     (  952): acquireWL(274d9cfd): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 952 1000 null
D/PMS     (  952): releaseWL(274d9cfd): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  952): Killing 6125:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
D/Process (  952): killProcessQuiet, pid=6125
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  952): Recipient 6125
,I/MusicStore( 6505): Database version: 120,
,D/Process (  952): killProcessQuiet, pid=5916
,I/ActivityManager(  952): Killing 5916:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  952): Recipient 5916
,D/VoldConnector(  952): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 6505): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  952): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6505): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  952): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6505): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6505): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6505): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6505): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6505): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6505): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24b58b1c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6505): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6505): GMSCore installation verified
,I/ConfigStore( 6505): Config Database version: 1,
,I/PackageManager(  952):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6505, uid=10159, userID:0
,I/art     ( 1801): Explicit concurrent mark sweep GC freed 9810(516KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 609us total 34.413ms
,D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
,D/MediaRouterService(  952): Client com.google.android.music (pid 6505): Registered
,D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
,D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
,I/MediaRouter( 6505): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6505): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6505): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6505): type=WIFI subType= reason=null isConnected=true,
,D/AutoSetting( 1649): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 6428): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
I/PackageManager(  952):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6505, uid=10159, userID:0
D/MobileConnectivityChangeReceiver( 6428): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1649): service - onCreate()
,D/AutoSetting( 1649): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,I/GHttpClientFactory( 6505): Using our fixed implementation of GMSCore's GoogleHttpClient
D/AutoSetting( 1649): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1649): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1649): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1649): service - handleMessage() setting current location null
,D/LocationManagerService(  952): request 16edcb7b passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  952): provider request: passive ProviderRequest[ON interval=0]
,I/GoogleURLConnFactory( 6505): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4338): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/libc    (  952): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
,D/libc    (  952): [NET] android_getaddrinfofornet-, err=8
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  952): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  952): [NET] android_getaddrinfo_proxy+
D/libc    (  952): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
,D/libc    (  397): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    ( 5678): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5678): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 5678): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5678): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5678): [NET] android_getaddrinfo_proxy+
D/libc    ( 5678): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/ActivityManager(  952): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6552 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  952):  packet count Tx=169 Rx=266
E/WifiTrafficPoller(  952): notifying of data activity 3
D/WIFI_ICON( 1217): WifiActivity: 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  952): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  952): [AlarmQueuing] connectivity wifi: true
,D/GpsLocationProvider(  952): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  952): acquireWL(18c3b37c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 952 1000 null
D/PMS     (  952): acquireWL(39eb6405): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 952 1000 null
,D/PMS     (  952): releaseWL(39eb6405): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/htcCheckinService(  952): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/ConnectivityHelper( 1597): [onReceive] WIFI(1): CONNECTED
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
I/NetworkMonitor( 6505): type=WIFI subType= reason=null isConnected=true
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/GpsLocationProvider(  952): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  952): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/libc    ( 5678): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/HtcWifiWanDetect(  952): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  952): [NET] android_getaddrinfo_proxy-, success
,E/GpsLocationProvider(  952): No APN found to select.
,D/PMS     (  952): releaseWL(18c3b37c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6387): [aa8.1.]  listen tmrbb8
,D/MdScDataSum( 6387): [aa8.1.] summary 118:p1 ignore,
,D/Process (  952): killProcessQuiet, pid=6155,
I/ActivityManager(  952): Killing 6155:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  952): Recipient 6155
,D/VoldConnector(  952): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/ContextImpl( 6552): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6552): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6552):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6552):   adb logcat -s GAv4
,D/VoldConnector(  952): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6552): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  952): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6552): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  952): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
W/ContextImpl( 6552): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/GAv4    ( 6552): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6552): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6552): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6552): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6552): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6552): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6552): Time to load native libraries: 1 ms (timestamps 2761-2762),
I/LibraryLoader( 6552): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6552): Binding Chromium to main looper Looper (main, tid 1) {eb0ee45},
,I/LibraryLoader( 6552): Expected native library version number "",actual native library version number ""
,I/chromium( 6552): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6552): Initializing chromium process, singleProcess=true
,W/art     ( 6552): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6552): ApplicationContext is null in ApplicationStatus
,W/chromium( 6552): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6552): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6552): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6552): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6552): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6552): Build Date: 03/09/15 Mon,
I/Adreno-EGL( 6552): Local Branch: 
I/Adreno-EGL( 6552): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6552): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6552):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6552): Requires BLUETOOTH permission,
,I/NSApplication( 6552): Starting up...,
,I/ActivityManager(  952): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6615 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  952): Killing 5943:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  952): killProcessQuiet, pid=5943
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiStateMachine(  952): handleMessage: E msg.what=131168,
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  952): handleMessage: X
,I/ActivityManager(  952): Recipient 5943
,D/PMS     (  952): acquireWL(12845d86): PARTIAL_WAKE_LOCK  *alarm* 0x1 952 1000 WorkSource{10024}
,V/AlarmManager(  952): sending alarm PendingIntent{127ed647: PendingIntentRecord{7350e74 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=102988, Int=0
V/AlarmManager(  952): sending alarm PendingIntent{1c5469bb: PendingIntentRecord{9ca2ed8 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455124048721, Int=20000
,I/ActivityManager(  952): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6638 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Process (  952): killProcessQuiet, pid=5790
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  952): Killing 5790:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  952):  packet count Tx=173 Rx=272
,I/ActivityManager(  952): Recipient 5790
,W/ResourcesManager( 6638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6231): 
,D/Process (  952): killProcessQuiet, pid=5478
I/ActivityManager(  952): Killing 5478:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  952): Recipient 5478
,V/MusicLeanback( 6505): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/AutoSetting( 1649): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6428): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6428): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1649): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1649): Util - check NLP state, Allowned:false, Enabled:false,
D/AutoSetting( 1649): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1649): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1649): service - handleMessage() setting current location null
,I/PackageManager(  952):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4338, uid=10024, userID:0
,D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4338): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
,D/PMS     (  952): acquireWL(106a473f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1801 10024 WorkSource{10024 com.google.android.gms},
,E/WifiStateMachine(  952): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: ,
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
E/WifiStateMachine(  952): handleMessage: E msg.what=131143
D/PMS     (  952): releaseWL(12845d86): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  952): processMsg: ConnectedState
D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1801): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1801): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1801): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1801): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:101, mark:917605
E/WifiStateMachine(  952):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:83 rssi=-62 f=2412 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=66.8 list=2412 [on:0 tx:0 rx:0 period:2717] from screen [on:0 period:-869860162]
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:83 rssi=-62 f=2412 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=66.8 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-869860161]
E/WifiStateMachine(  952): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=42.00 rxSuccessRate=66.75 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-62
E/WifiStateMachine(  952): WifiStateMachine CMD_START_SCAN with age=66495 interval=40000 maxinterval=300000
E/WifiStateMachine(  952): WifiStateMachine CMD_START_SCAN try full band scan age=66495 interval=40000 maxinterval=300000
E/WifiStateMachine(  952): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  952): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=42.00 rx=66.75
E/WifiStateMachine(  952): handleMessage: X
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1801): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1801): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1801): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  952): acquireWL(38afb80c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1801 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1801): Connected
,D/PMS     (  952): releaseWL(106a473f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(38afb80c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(122d3555): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1801): Message class com.google.f.a.a.p
D/PMS     (  952): releaseWL(122d3555): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  952): handleMessage: E msg.what=131155,
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=66.8 bcn=0 [on:0 tx:0 rx:0 period:281] from screen [on:0 period:-869859879] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
,E/WifiStateMachine(  952):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=66.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-869859878] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  952):  get link layer stats 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1353): environment dirty rate=0 [19][0][0]
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  952): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  952): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=30.50 txretriesrate=0.00 rxrate=41.88 userTriggerdPenalty0
E/WifiStateMachine(  952):  good link -> stuck count =0
E/WifiStateMachine(  952):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  952):  isHighRSSI       ---> score=65
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -62, 3
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -62, 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  952): handleMessage: X
,E/WifiDataStallTracker(  952): DATA_MONITOR_POLL true Token 3,
,D/WifiDataStallTracker(  952): updateDataStallInfo: mDataStallTxRxSum={txSum=159 rxSum=143} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  952): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  952): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  952):  packet count Tx=185 Rx=282
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6231): 
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6231): 
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6231): 
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 6231): 
,I/HtcModeClient( 3155): handler message = 4011,
,E/HtcModeClient( 3155): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3155): Don't start project servcice,
D/HtcModeClient( 3155): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3155): connectState: CONNECTION_READY = false
D/SilentMusic( 3155): call stop
D/HtcModeClient( 3155): close connection
W/HtcModeClient( 3155): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3155): read the terminate packet, so break
,D/Process (  952): killProcessQuiet, pid=3155,
I/ActivityManager(  952): Killing 3155:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6231): 
,I/ActivityManager(  952): Recipient 3155
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1217): WifiActivity: 0
E/WifiTrafficPoller(  952):  packet count Tx=185 Rx=282
E/WifiTrafficPoller(  952): notifying of data activity 0
,D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/SystemReader(  952): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1761): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
D/PMS     (  952): acquireWL(3143df37): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5678 10112 null
,W/ResourcesManager(  952): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/AccTypeManager( 1761): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1597): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
W/Prism.AllAppsManager( 1597): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1597): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1597): Deferring update until onResume
D/Launcher( 1597): waitUntilResume // bindAppsUpdated
,I/ActivityManager(  952): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6679 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/AccTypeManager( 1761): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  952): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6692 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  952): acquireWL(2c950427): PARTIAL_WAKE_LOCK  *alarm* 0x1 952 1000 WorkSource{10076}
V/AlarmManager(  952): sending alarm PendingIntent{2277bb72: PendingIntentRecord{1443bbc3 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455124054725, Int=60000
,D/PhoneApp( 1539): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  952): releaseWL(3143df37): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,E/ExternalAccountType( 1761): Unsupported attribute readOnly,
,W/ResourcesManager( 5678): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5678): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/PackageManager(  952): Unable to load service info ResolveInfo{2ccd8570 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  952): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  952): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  952): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  952): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  952): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  952): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  952): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  952): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  952): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  952): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  952): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/SMSBackup( 6692): SMSBackupAgentService started
D/SMSBackup( 6692): Checking restore status
,D/SMSBackup( 6692): Restore complete,
D/SMSBackup( 6692): cancelCheckAlarm
,D/SMSBackup( 6692): SMSBackupAgentService completed: completed in 0.0 seconds
,V/GmsNetworkLocationProvi( 1974): DISABLE,
,I/GCoreNlp( 1974): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  952): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/PMS     (  952): acquireWL(379599b6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1974 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(379599b6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  952): releaseWL(2c950427): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/PMS     (  952): acquireWL(246a298e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1974 10024 WorkSource{10024 com.google.android.gms}
D/LocationProviderProxy(  952): applying state to connected service,
D/PMS     (  952): releaseWL(246a298e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/LocationProviderProxy(  952): applying state to connected service
,D/PMS     (  952): acquireWL(bb125af): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1974 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(8428dbc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1974 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(bb125af): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  952): releaseWL(8428dbc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationManagerService(  952): getProviders()=[passive],
,I/ActivityManager(  952): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6731 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/[PluginManager]RegisterService( 1649): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1649): handle notify Blinkfeed plugin client changed,
,I/ActivityManager(  952): Killing 5340:com.htc.mediamanager/u0a28 (adj 15): empty #17
,D/Process (  952): killProcessQuiet, pid=5340
,D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/art     (  952): Explicit concurrent mark sweep GC freed 31314(1730KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 1.567ms total 142.289ms,
,I/ActivityManager(  952): Recipient 5340
,D/PackageBroadcastService( 4338): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4338): Null package name or gms related package.  Ignoreing.
,D/PMS     (  952): acquireWL(157125c0): PARTIAL_WAKE_LOCK  Icing 0x1 4338 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(d2dc2f9): PARTIAL_WAKE_LOCK  AsyncService 0x1 6638 10167 null
,I/Icing   ( 4338): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  952): acquireWL(167cd89f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6638 10167 null
,D/PMS     (  952): releaseWL(d2dc2f9): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/UpdateIcingCorporaServi( 6679): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  952): releaseWL(157125c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(167cd89f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 6679): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1217): WifiActivity: 1
,E/WifiTrafficPoller(  952):  packet count Tx=185 Rx=283
E/WifiTrafficPoller(  952): notifying of data activity 1
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/Prism.ItemManager( 1597): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1597): loadItems() com.htc.launcher.pageview.WidgetManager@57aea15 +
I/Prism.WidgetManager( 1597): onLoadItems() +
,W/ResourcesManager( 1597): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/PMS     (  952): acquireWL(201144a): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6505 10159 null,
,I/PackageManager(  952):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6505, uid=10159, userID:0
,D/WearableService( 4703): callingUid 10024, callindPid: 4703
,I/MusicLeanback( 6505): Conditions not met for autocaching. okToAttempt=false
D/PMS     (  952): releaseWL(201144a): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6505): Stop autocaching.
,E/GmsUtils( 6505): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6505): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ResourcesManager( 1597): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/WifiStateMachine(  952): handleMessage: E msg.what=131155,
E/WifiStateMachine(  952): processMsg: ConnectedState
,E/WifiStateMachine(  952):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=30.5, 0.0, 0.0  rx=41.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-869856868] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
,E/WifiStateMachine(  952):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=30.5, 0.0, 0.0  rx=41.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-869856867] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952):  get link layer stats 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1353): environment dirty rate=0 [2][0][0]
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
,E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
E/WifiConfigStore(  952): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -61, 3
E/WifiStateMachine(  952): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=15.75 txretriesrate=0.00 rxrate=21.44 userTriggerdPenalty0
E/WifiStateMachine(  952):  good link -> stuck count =0
E/WifiStateMachine(  952):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  952):  isHighRSSI       ---> score=65
,E/WifiStateMachine(  952): handleMessage: X
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -61, 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  952):  packet count Tx=186 Rx=283
,D/WIFI_ICON( 1217): WifiActivity: 2
E/WifiTrafficPoller(  952): notifying of data activity 2
,D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,W/asset   ( 1597): Copying FileAsset 0x5594da9bf0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1597): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1597): onLoadItems() -
I/Prism.ItemManager( 1597): loadItems() com.htc.launcher.pageview.WidgetManager@57aea15 -
,D/PhoneApp( 1539): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1539): -- N1 =0
,D/PhoneApp( 1539): -- N2 =0
,D/PhoneApp( 1539): -- N3 =0
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  952):  packet count Tx=187 Rx=283,
,E/WifiDataStallTracker(  952): DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  952): updateDataStallInfo: mDataStallTxRxSum={txSum=159 rxSum=143} preTxRxSum={txSum=159 rxSum=143}
D/WifiDataStallTracker(  952): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  952): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1217): WifiActivity: 0
E/WifiTrafficPoller(  952):  packet count Tx=187 Rx=283
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  952): notifying of data activity 0
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 6231): 
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 6231): 
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
I/jxcore-log( 6231): 
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 6231): 
,I/jxcore-log( 6231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6231): 
,E/WifiStateMachine(  952): handleMessage: E msg.what=131155,
E/WifiStateMachine(  952): processMsg: ConnectedState
,E/WifiStateMachine(  952):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=15.8, 0.0, 0.0  rx=21.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-869853856] gl hn u24 rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
,E/WifiStateMachine(  952):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=15.8, 0.0, 0.0  rx=21.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-869853854] gl hn u24 rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  952):  get link layer stats 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/PMS     (  952): Going to sleep due to screen timeout (uid 1000)...
D/wpa_supplicant( 1353): wlan0: Control interface command 'SIGNAL_POLL'
I/SensorManager(  952): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@29be7b00
W/SensorService(  952): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  952): disable: get sensor name = Accelerometer Sensor
,I/wpa_supplicant( 1353): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  952): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
,W/SensorService(  952): pid=952, uid=1000
,W/SensorService(  952): Active sensors: size = 4
W/PMN     (  952): goingToSleep
W/SensorService(  952): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  952): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  952): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  952): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  952): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@29be7b00, eanble = 0, strlen(mName) = 91
W/SensorService(  952): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  952): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1ff68e13
W/SensorService(  952): Listener[1] = com.htc.smartdim.sensor_eye@12f85b64
W/SensorService(  952): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/WifiStateMachine(  952): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.38 txretriesrate=0.00 rxrate=10.72 userTriggerdPenalty0
E/WifiStateMachine(  952):  good link -> stuck count =0
E/WifiStateMachine(  952):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  952):  isHighRSSI       ---> score=65
,W/PMS     (  952): mWirelessDisplayManager is null,
D/PMS     (  952): acquireWL(27c15625): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 952 1000 null
W/PMS     (  952): mWirelessDisplayManager is still null
,W/PMN     (  952): goingToSleep done
,E/WifiStateMachine(  952): handleMessage: X
E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL true Token 24 num clients 8
W/HtcLockScreen( 1217): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/HtcSystemUPManager(  952): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/PMS     (  952): Sleeping (uid 1000)...
D/XAN-DPS (  952): prepareColorFade 1
,E/WifiTrafficPoller(  952):  packet count Tx=187 Rx=283
D/AlarmManager(  952): ACTION_SCREEN_ON
D/WifiWatchdogStateMachine(  952): RSSI current: 3 new: -62, 3
,D/PMS     (  952): releaseWL(27c15625): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/AlarmManager(  952): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  952): [AlarmQueuing] done recovering
I/AlarmManager(  952): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  952): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL true Token 24
,E/WifiTrafficPoller(  952):  packet count Tx=187 Rx=283
,I/Adreno-EGL(  952): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  952): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  952): Build Date: 03/09/15 Mon
I/Adreno-EGL(  952): Local Branch: 
I/Adreno-EGL(  952): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  952): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  952):                  d74aa161a12b9c6fc6332151
,E/WifiDataStallTracker(  952): ENABLE_DATA_MONITOR_POLL true Token 3
,D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  952): handleMessage: E msg.what=131167
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  952): processMsg: DefaultState
,E/WifiStateMachine(  952):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  952):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1353): SET_SCREEN_ON:On
I/wpa_supplicant( 1353): htc_wext_set_keepalive +
,D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
I/wpa_supplicant( 1353): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1353): getPrivFuncNum +	
I/wpa_supplicant( 1353): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1353): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1353): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1353): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1353): htc_wext_set_TX_TRACKING - ret = 0
D/WifiDataStallTracker(  952): updateDataStallInfo: mDataStallTxRxSum={txSum=159 rxSum=143} preTxRxSum={txSum=159 rxSum=143}
D/WifiDataStallTracker(  952): updateDataStallInfo: NONE
D/WifiDataStallTracker(  952): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  952): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
,D/WifiStateMachine(  952): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  952): handleScreenStateChanged Exit: true
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131154
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1353): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  952): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  952): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131127
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131129
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1353): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1353): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  952): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  952): handleMessage: X
V/SRS_Proc(  403): ParamSet string: screen_state=on
E/audio_a2dp_hw(  403): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  952): handleMessage: E msg.what=155650
D/WifiController(  952): processMsg: DeviceActiveState
D/WifiController(  952): processMsg: StaEnabledState
D/WifiController(  952): processMsg: DefaultState
D/WifiController(  952): handleMessage: X
,D/NetworkPolicy(  952): updateScreenOn: false
V/NetworkPolicy(  952): updateIfacesLocked()
,D/NetworkManagementService(  952): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1331): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/GpsLocationProvider(  952): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/ActivityManager(  952): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6776 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/IntentController( 1217): receive(android.intent.action.SCREEN_ON,1,false)
,D/XAN-DPS (  952): prepareColorFade done
,D/XAN-DPS (  952): setBrightness to 0
I/ActivityManager(  952): Killing 6282:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  952): killProcessQuiet, pid=6282
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/SensorManager(  952): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@1ff68e13
,I/DisplayManagerService(  952): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  952): Following SensorService logs are not warning, just make sure they are printed
V/ActivityManager(  952): Display changed displayId=0
W/SensorService(  952): disable: get sensor name = CM32181 Light sensor
D/DotMatrix( 1331): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1331): [EventService] mbHDMIConnect: false, mCoverOn:false
E/qdutils (  389): int qdutils::getHDMINode(): Failed to open fb node 2
W/SensorService(  952): pid=952, uid=1000
,W/SensorService(  952): Active sensors: size = 3
E/qdutils (  389): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  952): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  952): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  952): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  952): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@1ff68e13, eanble = 0, strlen(mName) = 67
W/SensorService(  952): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  952): Listener[0] = com.htc.smartdim.sensor_eye@12f85b64
W/SensorService(  952): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  952): Recipient 6282
,D/PMS     (  952): acquireWL(283e7987): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1974 10024 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6776): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  952): acquireWL(310b10b4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1974 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(283e7987): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  952): releaseWL(310b10b4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6776): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6776): MY_DEBUG = false
,D/SmartSyncUtils( 6776): isEpsOn(), nState = 0,
,I/ActivityManager(  952): Killing 6480:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  952): killProcessQuiet, pid=6480
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  952): acquireWL(1bff2723): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6776 1000 null
,D/PMS     (  952): releaseWL(1bff2723): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  952): Recipient 6480
,D/AlarmManager(  952): ACTION_SCREEN_OFF
,I/AlarmManager(  952): [AlarmQueuing] screen off now: ,
I/AlarmManager(  952): [AlarmQueuing] data connection: true
I/AlarmManager(  952): [AlarmQueuing] wifi connection: true
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/WifiDataStallTracker(  952): stopDataStallAlarm 
E/WifiDataStallTracker(  952): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  952): handleMessage: E msg.what=131167
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  952):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1353): SET_SCREEN_ON:Off,
I/wpa_supplicant( 1353): htc_wext_set_keepalive +
I/wpa_supplicant( 1353): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1353): getPrivFuncNum +	
I/wpa_supplicant( 1353): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1353): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1353): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1353): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1353): htc_wext_set_keepalive - ret = 0
V/SRS_Proc(  403): ParamSet string: screen_state=off
E/audio_a2dp_hw(  403): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  952): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
D/WifiStateMachine(  952): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  952): handleScreenStateChanged Exit: false
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131154
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  952): handleMessage: X
D/WifiController(  952): handleMessage: E msg.what=155651
D/WifiController(  952): processMsg: DeviceActiveState
D/WifiController(  952): processMsg: StaEnabledState
D/WifiController(  952): processMsg: DefaultState
D/WifiController(  952): handleMessage: X
D/NetworkPolicy(  952): updateScreenOn: false
V/NetworkPolicy(  952): updateIfacesLocked()
,D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NetworkManagementService(  952): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/ContextImpl(  952): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  952): Init customizeScreenOffDelayClass error
D/DotMatrix( 1331): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  952): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/SensorManager( 1217): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@dd08c5, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
W/SensorService(  952): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  952): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  952): pid=1217, uid=10041
W/SensorService(  952): Active sensors: size = 4
W/SensorService(  952): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  952): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  952): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  952): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  952): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@dd08c5, eanble = 1, strlen(mName) = 55
W/SensorService(  952): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  952): Listener[0] = com.htc.smartdim.sensor_eye@12f85b64
W/SensorService(  952): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@dd08c5
W/SensorService(  952): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/ContextImpl( 6776): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6776): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/ContactMessageStore( 1539): start background delete task...
,D/SmartSyncUtils( 6776): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6776): isEpsOn(), nState = 0
,D/ContactMessageStore( 1539): size: 0 , 0
,D/ContactMessageStore( 1539): Background delete complete
I/IntentController( 1217): receive(android.intent.action.SCREEN_OFF,1,false)
,W/ContextImpl( 6776): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  952): acquireWL(173431d9): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1974 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  952): releaseWL(173431d9): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(3b93127f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1974 10024 WorkSource{10024 com.google.android.gms}
D/SurfaceControl(  952): Excessive delay in setPowerMode(): 292ms
E/qdutils (  389): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  389): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  952): Setting HAL interactive mode to false
D/PMS     (  952): Setting HAL interactive mode to false done
D/PMS     (  952): Setting HAL auto-suspend mode to true
D/PMS     (  952): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  952): screenObserver, isScreenOn=false
D/StatusBarManagerService(  952): swetImeWindowStatus vis=0 backDisposition=0
D/HABCtrl (  952): TPE algorithm. remove timeout.
I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
I/InputMethodManagerService(  952): Disable input method client, pid=6231
,I/InputMethodManager( 6231): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{1a93a8cf VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@c40e26d
D/PMS     (  952): OOBE c monitor 11
,W/HtcSystemUPManager(  952): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  952): releaseWL(3b93127f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  952): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  952): acquireWL(3a7bc24c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 952 1000 null
,I/BatteryService(  952): n_update end
,D/PMS     (  952): releaseWL(3a7bc24c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NfcService( 1558): ScreenObserver: OFF
I/SensorManager(  952): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@12f85b64
,W/SensorService(  952): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  952): disable: get sensor name = Accelerometer Sensor
,D/NfcService( 1558): applyRouting - 0
,W/SensorService(  952): pid=952, uid=1000
,D/PMS     (  952): acquireWL(2ead1295): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1558 1027 null
W/SensorService(  952): Active sensors: size = 3
W/SensorService(  952): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  952): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  952): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  952): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@12f85b64, eanble = 0, strlen(mName) = 36
W/SensorService(  952): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  952): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@dd08c5
W/SensorService(  952): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  952): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  952): disable: get sensor name = CM36686 Proximity sensor
D/PMS     (  952): releaseWL(2ead1295): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/NfcService( 1558): applyRouting -2
D/NfcService( 1558): applyRouting
D/NfcService( 1558): Ignore this applyRouting...
,W/SensorService(  952): pid=952, uid=1000
W/SensorService(  952): Active sensors: size = 2
W/SensorService(  952): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  952): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  952): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@12f85b64, eanble = 0, strlen(mName) = 36
,W/SensorService(  952): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  952): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@dd08c5
D/HtcPowerSaver(  952): updateBatteryInfo
W/SensorService(  952): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  952): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@12f85b64
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
E/ActivityThread(  952): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@12ef91cd that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  952): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@12ef91cd that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  952): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  952): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
,E/ActivityThread(  952): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  952): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  952): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  952): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  952): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  952): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  952): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  952): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  952): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  952): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  952): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  952): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  952): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  952): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  952): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  952): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  952): plugged=true pluggin=true
D/DotMatrix( 1331): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  952): runPSCheck
D/HeadsetStateMachine( 3077): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  952): Checking...
D/UsbnetService(  952): BroadcastReceiver::onReceive+
,I/HtcPowerSaver(  952): >> updateStatus
D/UsbnetService(  952): onReceive BATTERY_CHANGED
D/WifiController(  952): battery changed pluggedType: 2
D/UsbnetService(  952):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  952): BroadcastReceiver::onReceive-
D/WifiController(  952): handleMessage: E msg.what=155652
D/WifiController(  952): processMsg: DeviceActiveState
D/WifiController(  952): processMsg: StaEnabledState
D/WifiController(  952): processMsg: DefaultState
D/WifiController(  952): handleMessage: X
I/HtcPowerSaver(  952): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  952): << updateStatus
,I/RemoteViews( 1217): setHTCTheme(com.htc.updater,true,33751145),
D/SmartSyncUtils( 6776): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1649): service - mHandler: cancel location update
D/AutoSetting( 1649): service -           changes count: 0
,D/WifiService(  952): New client listening to asynchronous messages
,I/InputManager(  952): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/IntentController( 1217): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,E/WifiTrafficPoller(  952): ADD_CLIENT: 9
I/PowerUsageList:PowerUsageHelper( 6776): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/RemoteViews( 1217): apply : com.htc.updater 1 11 1 36
,D/PowerUI ( 1217): closing low battery warning: level=100,
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PowerUsageList:BatterySipperExt( 6776): gen(), null == sipper.uidObj, userId = 0,
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,I/ClockController( 1217): stop clock update:screen off
,D/PowerUsageList:PowerUsageHelper( 6776): MY_DEBUG = false,
,I/jxcore-log( 6231): Test app app.js loaded,
I/jxcore-log( 6231): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): 	Bluetooth MAC address: 90:E7:C4:F6:69:77, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): 	Scan mode: 1
,I/chromium( 6231): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6231): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ebcea2 added. We now have 1 listener(s)
D/BluetoothAdapter( 6231): 1040181379: getState(). Returning 12
I/jxcore-log( 6231): BLE advertisement is supported
I/jxcore-log( 6231): 
,I/ActivityManager(  952): Killing 6387:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17,
D/Process (  952): killProcessQuiet, pid=6387
,D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL false Token 26 num clients 9,
,E/WifiTrafficPoller(  952): TRAFFIC_STATS_POLL false Token 26 num clients 9
,I/ActivityManager(  952): Recipient 6387
,D/PMS     (  952): releaseWL(1b7e2106): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,E/WifiStateMachine(  952): handleMessage: E msg.what=131155,
E/WifiStateMachine(  952): processMsg: ConnectedState
,E/WifiStateMachine(  952):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2982] from screen [on:0 period:-869850826] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  952): processMsg: L2ConnectedState
,E/WifiStateMachine(  952):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-869850824] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  952): handleMessage: X
,E/WifiStateMachine(  952): handleMessage: E msg.what=131155
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:65] from screen [on:0 period:-869850757] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-869850754] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  952): handleMessage: X
,D/HtcUPManager( 1217): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  952): DATA_MONITOR_POLL false Token 5,
,E/WifiDataStallTracker(  952): DATA_MONITOR_POLL false Token 5,
,D/ContactMessageStore( 1539): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1539): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  447): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  952): killProcessQuiet, pid=5527
I/ActivityManager(  952): Killing 5527:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  952): Recipient 5527,
,W/Atfwd_Sendcmd(  447): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/WifiStateMachine(  952): handleMessage: E msg.what=131165,
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0,
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  952): handleMessage: X
,D/PMS     (  952): acquireWL(f987faa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 952 1000 WorkSource{1000}
,V/AlarmManager(  952): sending alarm PendingIntent{104a8da: PendingIntentRecord{d0a810b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=130733, Int=0
V/AlarmManager(  952): sending alarm PendingIntent{250579b: PendingIntentRecord{13c8b738 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140849, Int=0
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/PMS     (  952): releaseWL(f987faa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/AutoSetting( 1649): service - handleMessage() stop self,
,D/AutoSetting( 1649): service - onDestroy() END
D/AutoSetting( 1649): service - handleMessage() quit looper
,W/Atfwd_Sendcmd(  447): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  952): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  952): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  952): acquireWL(1994311): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 952 1000 null
,D/libc    (  952): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  952): [NET] android_getaddrinfofornet-, err=8,
,D/libc    (  952): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  952): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  952): [NET] android_getaddrinfo_proxy+
D/libc    (  952): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  952): [NET] android_getaddrinfo_proxy-, success
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  952): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  952): [reportHTCStatus] eventMask = 3 , status = 0,
,D/GpsLocationProvider(  952): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  952):  [handleDownloadXtraData]inject done.
D/PMS     (  952): acquireWL(1a3dff4d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 952 1000 null
D/GpsLocationProvider(  952): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  952): releaseWL(1994311): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  952): releaseWL(1a3dff4d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/WifiStateMachine(  952): handleMessage: E msg.what=131326,
E/WifiStateMachine(  952): processMsg: ConnectedState
E/WifiStateMachine(  952):  ConnectedState what:131326 2 0
E/WifiStateMachine(  952): processMsg: L2ConnectedState
E/WifiStateMachine(  952):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  952): handleMessage: X
,W/ContextImpl(  952): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  447): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  952): acquireWL(12bd5a02): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 952 1000 null,
I/BatteryService(  952): n_update end
D/PMS     (  952): releaseWL(12bd5a02): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  952): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  952): updateBatteryInfo
D/UsbnetService(  952): onReceive BATTERY_CHANGED
D/NotificationService(  952): plugged=true pluggin=true
D/UsbnetService(  952):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  952): runPSCheck
D/UsbnetService(  952): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  952): Checking...
D/WifiController(  952): handleMessage: E msg.what=155652
I/HtcPowerSaver(  952): >> updateStatus
,D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  952): battery changed pluggedType: 2
D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1331): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  952): processMsg: DeviceActiveState
D/WifiController(  952): processMsg: StaEnabledState
D/WifiController(  952): processMsg: DefaultState
D/WifiController(  952): handleMessage: X
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  952): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  952): << updateStatus
D/HeadsetStateMachine( 3077): Disconnected process message: 10, size: 0
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1539): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  447): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  952): acquireWL(b981f13): PARTIAL_WAKE_LOCK  *alarm* 0x1 952 1000 WorkSource{1000},
D/PMS     (  952): acquireWL(24ef3550): PARTIAL_WAKE_LOCK  *backup* 0x1 952 1000 null
,V/AlarmManager(  952): sending alarm PendingIntent{27f84349: PendingIntentRecord{3cab144e android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455124114912, Int=0
V/AlarmManager(  952): sending alarm PendingIntent{104a8da: PendingIntentRecord{d0a810b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=190733, Int=0
,V/AlarmManager(  952): sending alarm PendingIntent{375b996f: PendingIntentRecord{159a567c android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=199726, Int=0
V/AlarmManager(  952): sending alarm PendingIntent{18f8cb05: PendingIntentRecord{3aa8275a com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=188508, Int=0
,W/BackupManagerService(  952): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  952): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  952): acquireWL(3f325d8b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  952): releaseWL(24ef3550): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  952): releaseWL(b981f13): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/WeatherUtility( 1217): Weather sync is On
,W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/PMS     (  952): acquireWL(25745e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(3f325d8b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1801): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  952): releaseWL(25745e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(15c447b2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(15c447b2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  952): acquireWL(3816f303): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(3816f303): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(17229280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(315b90b9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(2e8bbc5f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(17229280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1801): Vacuum at: now=1455124149230 tag=VacuumService
,I/GoogleURLConnFactory( 1801): Using platform SSLCertificateSocketFactory
,D/PMS     (  952): releaseWL(315b90b9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  952): acquireWL(2c9b7f75): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(2c9b7f75): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(33b19df1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(33b19df1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1801): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1801): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1801): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1801): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1801): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1217): reapply : com.google.android.gms 4 40
,D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1331): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1801): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1801): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1801): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1801): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1801): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1801): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1801): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1801): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1801): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1801): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1801): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1801): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
,E/Uploader( 1801): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1801): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1801): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1801): [NET] android_getaddrinfo_proxy+
D/libc    ( 1801): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1801): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1801): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1801): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1801): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1801): No account for auth token provided,
,W/Uploader( 1801): No account for auth token provided,
,W/Uploader( 1801): No account for auth token provided,
,W/Uploader( 1801):  no longer exists, so no auth token.,
,W/Uploader( 1801): No account for auth token provided,
,D/PMS     (  952): releaseWL(2e8bbc5f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  952): acquireWL(1b4c2fe5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(1b4c2fe5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  952): acquireWL(6265aba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(6265aba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1649): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2f935043
I/ActivityManager(  952): Killing 6428:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  952): killProcessQuiet, pid=6428
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  952): Recipient 6428
,W/Atfwd_Sendcmd(  447): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  952): acquireWL(33d57d6b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 952 1000 null
I/BatteryService(  952): n_update end
D/PMS     (  952): releaseWL(33d57d6b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  952): updateBatteryInfo,
D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  952): plugged=true pluggin=true
D/UsbnetService(  952): BroadcastReceiver::onReceive+
D/PMS     (  952): runPSCheck
D/UsbnetService(  952): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  952): Checking...
D/UsbnetService(  952):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  952): >> updateStatus
D/UsbnetService(  952): BroadcastReceiver::onReceive-
D/WifiController(  952): battery changed pluggedType: 2
D/WifiController(  952): handleMessage: E msg.what=155652
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  952): processMsg: DeviceActiveState
D/WifiController(  952): processMsg: StaEnabledState
D/WifiController(  952): processMsg: DefaultState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  952): handleMessage: X
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1331): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3077): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  952): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  952): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  447): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  447): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6231): --= Surplus to requirements =--,
I/jxcore-log( 6231): 
I/jxcore-log( 6231): ****TEST TOOK:  ms ****
I/jxcore-log( 6231): ,
I/jxcore-log( 6231): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6231): 
,E/cutils-trace( 6830): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 6830): ====startRecUseTime====,
,D/htc.customization.log.level( 6830):  is 
W/CustomizationLogLevel( 6830): Level value is invalid, use default level 2
,D/CustomizationManager( 6830):  Read ACC file spent 0.045 (s)
,D/CIDMapFileReader( 6830): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 6830): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6830): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6830): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6830): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6830): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6830): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6830): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 6830): Parsing tag category name = system
,I/CustomizationCIDLoader( 6830): Parsing tag category name = application
,I/CustomizationCIDLoader( 6830): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 6830): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6830): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6830): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6830): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 6830): add string-array item, value = 42507
I/CustomizationCIDLoader( 6830): add string-array item, value = 21902
I/CustomizationCIDLoader( 6830): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6830): add string-array item, value = 23420
,I/CustomizationCIDLoader( 6830): add string-array item, value = 22299
I/CustomizationCIDLoader( 6830): add string-array item, value = 24002
I/CustomizationCIDLoader( 6830): add string-array item, value = 23210
I/CustomizationCIDLoader( 6830): add string-array item, value = 23205
I/CustomizationCIDLoader( 6830): add string-array item, value = 23806
I/CustomizationCIDLoader( 6830): add string-array item, value = 23430
I/CustomizationCIDLoader( 6830): add string-array item, value = 23408
,I/CustomizationCIDLoader( 6830): add string-array item, value = 27205
I/CustomizationCIDLoader( 6830): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 22299:D:0:0
,I/CustomizationCIDLoader( 6830): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6830): add string-array item, value = 27205:C:1:0
,D/CustomizationManager( 6830):  Read CID file spent 0.092 (s)
D/CustomizationManager( 6830):  All configurations done spent 0.092 (s)
,D/PackageManager(  952): deletePackageAsUser: pkg=com.test.thalitest, pid=6830, uid=2000 userid=0,
,D/Process (  952): killProcessQuiet, pid=6231
I/ActivityManager(  952): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  952): Killing 6231:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
,D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  952): Skipping PackageSetting{21670c30 com.example.hello/10374} due to missing metadata
,I/ActivityManager(  952): Recipient 6231
I/WindowState(  952): WIN DEATH: Window{2e8f991b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  952): Client connection lost with reason: 4
,E/InputEventReceiver( 1391): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1b62182 uid 10366 pid 6231} (c)'
,I/ActivityManager(  952):   Force finishing activity ActivityRecord{157a081a u0 com.test.thalitest/.MainActivity t8},
,I/ActivityManager(  952): Force stopping com.test.thalitest appid=10366 user=0: pkg removed,
,I/ActivityManager(  952):   Force finishing activity ActivityRecord{157a081a u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  952): Duplicate finish request for ActivityRecord{157a081a u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  952): Spurious death for ProcessRecord{9df30c8 6231:com.test.thalitest/u0a366}, curProc for 6231: null
,D/DotMatrix( 1331): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1331): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1331): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/PMS     (  952): acquireWL(3794e561): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1974 10024 WorkSource{10024 com.google.android.gms}
,W/SystemReader(  952): Cannot find grip_rejection_width, use default value instead
,W/GeofencerStateMachine( 1974): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  952): releaseWL(3794e561): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 1761): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1761): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1761): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/VoicemailCleanupService( 1711): Cleaning up data for package: com.test.thalitest
,D/PhoneApp( 1539): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1649): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/art     ( 1597): Explicit concurrent mark sweep GC freed 24407(1458KB) AllocSpace objects, 5(356KB) LOS objects, 34% free, 30MB/46MB, paused 957us total 106.698ms
D/Prism.PackageStateRece_( 1597): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1597): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1597): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,E/ExternalAccountType( 1761): Unsupported attribute readOnly
I/[PluginManager]RegisterService( 1649): handle notify Blinkfeed plugin client changed
,I/Launcher( 1597): Deferring update until onResume
D/Launcher( 1597): waitUntilResume // bindAppsRemoved
I/ActivityManager(  952): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6850 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/InputMethodManagerService(  952): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
W/PackageManager(  952): Unable to load service info ResolveInfo{c7fcd2f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  952): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  952): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  952): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  952): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  952): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  952): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  952): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  952): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  952): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  952): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  952): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
,W/PackageManager(  952): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/JobSchedulerService(  952): Receieved: android.intent.action.PACKAGE_REMOVED,
,D/TaskPersister(  952): removeObsoleteFile: deleting file=8_task.xml,
D/TaskPersister(  952): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/art     (  952): Explicit concurrent mark sweep GC freed 46956(2MB) AllocSpace objects, 7(1212KB) LOS objects, 33% free, 19MB/28MB, paused 2.138ms total 195.244ms,
,W/asset   (  952): Copying FileAsset 0x5594a0cbc0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,D/StatusBarManagerService(  952): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  952): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  952): hiding MENU key
,D/StatusBarManagerService(  952): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  952): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  952): hiding MENU key
,W/ContextImpl( 6850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,W/ResourcesManager(  952): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/FindExtension( 1597): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/ThreadedRenderer( 1597): Defer allocateBuffers to drawing time
,W/InputMethodManagerService(  952): Got RemoteException sending setActive(false) notification to pid 6231 uid 10366
,D/StatusBarManagerService(  952): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
,I/ActivityManager(  952): Killing 6552:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
,D/Process (  952): killProcessQuiet, pid=6552
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/NetworkScheduler.SchedulerReceiver( 1801): Invalid parameter app,
E/NetworkScheduler.SchedulerReceiver( 1801): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  952): acquireWL(15517a94): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1801 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  952): Recipient 6552,
,D/PMS     (  952): releaseWL(15517a94): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PackageBroadcastService( 4338): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4338): Module APK com.google.android.play.games already loaded,
,D/AccountUtils( 4338): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4338): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  952): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6882 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/LocationSettingsChecker( 4338): Removing dialog suppression flag for package com.test.thalitest
,I/art     (  411): Explicit concurrent mark sweep GC freed 8646(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 262us total 35.807ms
,D/GOOGLEHELP_CompatibleDatabase( 4338): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4338): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2,
D/gH_MetricsDatabase( 4338): 0 metrics were deleted when clearing package com.test.thalitest.,
D/GOOGLEHELP_CompatibleDatabase( 4338): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 233us total 24.868ms
,D/GOOGLEHELP_CompatibleDatabase( 4338): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 4338): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4338): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4338): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 206us total 27.118ms
D/GOOGLEHELP_CompatibleDatabase( 4338): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 4338): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4338): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4338): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4338): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/PMS     (  952): acquireWL(2f33083a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4338 10024 null
,I/ConfigService( 1801): onCreate
,I/ConfigFetchService( 4338): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/PMS     (  952): releaseWL(2f33083a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,W/BaseAppContext( 4338): Using Auth Proxy for data requests.
,W/BaseAppContext( 4338): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 4338): CP2 sync disabled
,I/PackageManager(  952):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4338, uid=10024, userID:0
,D/PMS     (  952): acquireWL(1117e63): PARTIAL_WAKE_LOCK  Icing 0x1 4338 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4338): doRemovePackageData com.test.thalitest
,D/PMS     (  952): releaseWL(1117e63): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/DriveInitializer( 4338): Awaiting to be initialized,
,W/DriveInitializer( 4338): Background init thread started,
,E/SQLiteLog( 4338): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
,E/SQLiteDBG( 4338): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55948e87a0
,E/DocListDatabase( 4338): Failed to delete from ContentFileDeletionLock112
,E/DocListDatabase( 4338): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4338): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4338): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/DocListDatabase( 4338): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4338): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
,E/DocListDatabase( 4338): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/DocListDatabase( 4338): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 4338): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 4338): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 4338): Background init thread ended
E/SQLiteLog( 4338): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4338): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55948e87a0
,E/AndroidRuntime( 4338): FATAL EXCEPTION: Background initialization thread,
E/AndroidRuntime( 4338): Process: com.google.android.gms, PID: 4338
E/AndroidRuntime( 4338): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4338): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4338): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 4338): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4338): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4338): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 4338): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 4338): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 4338): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/ActivityManager(  952): App crashed! Process: com.google.android.gms
E/DriveAsyncService( 4338): disk I/O error (code 3850),
E/DriveAsyncService( 4338): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4338): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4338): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4338): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4338): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4338): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4338): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/DriveAsyncService( 4338): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4338): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 4338): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4338): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4338): 	at com.google.android.gms.common.service.g.run(SourceFile:178),
E/DriveAsyncService( 4338): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4338): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4338): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 4338): killProcess, pid=4338
,I/DropBoxManagerService(  952): Usage (1281) > Quota (1280)
,D/Process ( 4338): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  952): Can't write tombstone file,
E/DropBoxManagerService(  952): java.io.FileNotFoundException: /data/system/dropbox/SYSTEM_TOMBSTONE@1454936305933.lost: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  952): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  952): 	at com.android.server.DropBoxManagerService$EntryFile.<init>(DropBoxManagerService.java:531)
E/DropBoxManagerService(  952): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:804)
E/DropBoxManagerService(  952): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:197)
E/DropBoxManagerService(  952): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  952): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  952): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  952): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  952): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  952): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  952): 	... 7 more
E/DropBoxManagerService(  952): Can't write: system_app_crash
E/DropBoxManagerService(  952): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  952): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  952): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  952): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  952): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  952): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  952): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  952): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  952): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  952): 	... 5 more
,I/GAv4    ( 6882): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6882):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6882):   adb logcat -s GAv4
,W/GAv4    ( 6882): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6882): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 6882): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 6882): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 6882): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
E/SharedPreferencesImpl( 6882): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 6882): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,E/SQLiteDatabase( 6882): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6882): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6882): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6882): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6882): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6882): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6882): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6882): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6882): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 6882): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 6882): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 6882): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 6882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6882): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6882): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6882): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6882): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6882): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6882): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6882): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6882): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6882): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6882): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 6882): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GAv4    ( 6882): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6882): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6882): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 6882): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 6882): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 6882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6882): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6882): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6882): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6882): 	at aen.run(PG:536)
,E/lowmemorykiller(  385): Error writing /proc/4338/oom_score_adj; errno=22,
E/JavaBinder(  952): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  952): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,I/ActivityManager(  952): Recipient 4338
D/WifiService(  952): Client connection lost with reason: 4
,I/ActivityManager(  952): Process com.google.android.gms (pid 4338) has died
I/ConfigService( 1801): onDestroy
W/ActivityManager(  952): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10993ms
W/ActivityManager(  952): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10993ms
W/ActivityManager(  952): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10992ms
,D/VoldConnector(  952): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 6882): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,E/SQLiteDatabase( 6882): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6882): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6882): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6882): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6882): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6882): 	at aej.c(PG:139)
E/SQLiteDatabase( 6882): 	at aej.b(PG:398)
E/SQLiteDatabase( 6882): 	at agf.f(PG:417)
E/SQLiteDatabase( 6882): 	at oe.run(PG:1112)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6882): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 6882): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 6882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6882): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6882): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6882): ,	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6882): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6882): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 6882): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 6882): 	,at oe.run(PG:1112)
E/AbstractDatabaseInstance( 6882): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 6882): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6882): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6882): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6882): 	at java.lang.Thread.run(Thread.java:818)
D/PMS     (  952): acquireWL(389de124): PARTIAL_WAKE_LOCK  AsyncService 0x1 6638 10167 null,
,D/PMS     (  952): acquireWL(6d51642): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6638 10167 null
D/PMS     (  952): releaseWL(389de124): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/ResourcesManager( 6882): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6882): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  952): releaseWL(6d51642): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 6679): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,I/ActivityManager(  952): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6932 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,V/JNIHelp ( 6882): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 6679): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 6679): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55947af7b0
,I/ActivityManager(  952): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=6953 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,E/SharedPreferencesImpl( 6679): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
E/AndroidRuntime( 6679): FATAL EXCEPTION: IntentService[UpdateCorporaService]
,E/AndroidRuntime( 6679): Process: com.google.android.googlequicksearchbox:search, PID: 6679
E/AndroidRuntime( 6679): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6679): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6679): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 6679): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6679): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6679): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 6679): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 6679): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 6679): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 6679): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 6679): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 6679): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 6679): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 6679): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 6679): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 6679): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 6679): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 6679): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6679): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6679): 	,at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6679): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  952): App crashed! Process: com.google.android.googlequicksearchbox:search
,D/Process ( 6679): killProcess, pid=6679,
,E/DropBoxManagerService(  952): Can't write: system_app_crash
E/DropBoxManagerService(  952): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  952): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  952): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  952): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  952): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  952): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  952): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  952): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  952): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  952): 	... 5 more
,D/Process ( 6679): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
,W/System  ( 6882): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6882): Installed default security provider GmsCore_OpenSSL
I/DeviceManagement( 6932): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6932 dbg=false s=true
I/DeviceManagement( 6932): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 6932): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,E/SQLiteDatabase( 6882): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6882): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6882): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6882): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6882): 	at aej.c(PG:139)
E/SQLiteDatabase( 6882): 	at aej.a(PG:358)
E/SQLiteDatabase( 6882): 	at aej.a(PG:345)
E/SQLiteDatabase( 6882): 	at agf.c(PG:884)
E/SQLiteDatabase( 6882): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 6882): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6882): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6882): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6882): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 6882): Failed to query Account133 object
E/AbstractDatabaseInstance( 6882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDataba,seInstance( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6882): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6882): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6882): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6882): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6882): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 6882): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 6882): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 6882): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 6882): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 6882): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6882): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 6882): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6882): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6882): 	at java.lang.Thread.run(Thread.java:818)
I/DeviceManagement( 6932): WorkflowService: Starting workflow service
,I/DeviceManagement( 6932): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@363e4e7] args=[Bundle[mParcelledData.dataSize=112]]
,I/DeviceManagement( 6932): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 6932): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 6932): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 6932): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  952): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6981 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
,V/GLSActivity( 1801): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/SharedPreferencesImpl( 6882): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,I/DeviceManagement( 6932): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 6932): SessionStateController: Checking invariants...,
,I/ActivityManager(  952): Recipient 6679,
,I/ActivityManager(  952): Process com.google.android.googlequicksearchbox:search (pid 6679) has died
W/ActivityManager(  952): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10655ms
,E/SQLiteDatabase( 6981): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 6981): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6981): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6981): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6981): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6981): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6981): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 6981): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 6981): ,	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 6981): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 6981): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 6981): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 6981): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144),
E/SQLiteDatabase( 6981): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 6981): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6981): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6981): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6981): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6981): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6981): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6981): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6981): FATAL EXCEPTION: main
E/AndroidRuntime( 6981): Process: com.android.documentsui, PID: 6981
E/AndroidRuntime( 6981): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6981): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 6981): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 6981): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 6981): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6981): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6981): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6981): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6981): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6981): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6981): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6981): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6981): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6981): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6981): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6981): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
,E/AndroidRuntime( 6981): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 6981): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 6981): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 6981): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 6981): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 6981): 	... 9 more
,I/ActivityManager(  952): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=7005 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  952): Start proc com.google.android.gms for service com.google.android.gms/.feedback.FeedbackService: pid=7025 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/ActivityManager(  952): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=7047 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a,
E/ActivityManager(  952): App crashed! Process: com.android.documentsui
D/ErrorReport(  952): HtcErrorReportManager Begin---add error logs to dropbox,
,W/System.err(  952): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system),
W/System.err(  952): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  952): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  952): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  952): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  952): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  952): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  952): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  952): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  952): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  952): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  952): 	at libcore.io.Posix.open(Native Method)
W/System.err(  952): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  952): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  952): 	... 12 more
E/SQLiteDatabase( 6932): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 6932): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6932): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6932): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 6932): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 6932): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 6932): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 6932): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:,28)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 6932): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 6932): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 6932): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 6932): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 6932): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 6932): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 6932): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6932): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6932): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6932): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(  952): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  952): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  952): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  952): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  952): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  952): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  952): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  952): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  952): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  952): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  952): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
,W/System.err(  952): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  952): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  952): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  952): 	at libcore.io.Posix.open(Native Method)
W/System.err(  952): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  952): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  952): 	... 14 more
I/DeviceManagement( 6932): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 6932): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 6932): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 6932): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 6932): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6932): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6932): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6932): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 6932): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 6932): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate,(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 6932): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 6932): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 6932): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 6932): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6932): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6932): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 6932): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@363e4e7]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/DeviceManagement( 6932): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
W/DeviceManagement( 6932): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/DeviceManagement( 6932): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 6932): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 6932): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 6932): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 6932): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 6932): 	at com.h,tc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 6932): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 6932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 6932): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 6932): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  952): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  952): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  952): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  952): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  952): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  952): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  952): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  952): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  952): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  952): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  952): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  952): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  952): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  952): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  952): 	at libcore.io.Posix.open(Native Method)
W/System.err(  952): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  952): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  952): 	... 14 more
I/DeviceManagement( 6932): WorkflowService: Stopping workflow service
I/ActivityManager(  952): Killing 6615:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  952): killProcessQuiet, pid=6615
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager( 7005): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/ErrorReport(  952): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  952): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455124209903.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  952): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  952): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  952): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  952): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  952): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  952): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  952): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  952): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  952): 	... 4 more
W/ResourcesManager( 7025): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7025): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7025): VM with version 2.1.0 has multidex support
I/MultiDex( 7025): install
I/MultiDex( 7025): VM has multidex support, MultiDex support library is disabled.
,I/Prism.ItemManager( 1597): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1597): loadItems() com.htc.launcher.pageview.WidgetManager@57aea15 +
I/Prism.WidgetManager( 1597): onLoadItems() +
,I/ActivityManager(  952): Recipient 6615
,W/ResourcesManager( 1597): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  952): Killing 5678:com.google.android.talk/u0a112 (adj 15): empty #17,
D/Process (  952): killProcessQuiet, pid=5678
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,I/ActivityManager(  952): Recipient 5678,
,W/ResourcesManager( 1597): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,

```
