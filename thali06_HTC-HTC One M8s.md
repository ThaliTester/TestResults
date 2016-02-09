#### Test 587523534d3a10e_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  929): handleMessage: E msg.what=131155
E/WifiStateMachine(  929): processMsg: ConnectedState
E/WifiStateMachine(  929):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-964498146] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-964498144] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  929):  get link layer stats 0
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1351): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
--------- beginning of system
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiConfigStore(  929): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  929): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.06 txretriesrate=0.00 rxrate=0.95 userTriggerdPenalty0
E/WifiStateMachine(  929):  good link -> stuck count =0
E/WifiStateMachine(  929):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  929):  isHighRSSI       ---> score=61
E/WifiStateMachine(  929): handleMessage: X
D/WifiWatchdogStateMachine(  929): RSSI current: 3 new: -65, 3
,E/WifiDataStallTracker(  929): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  929): updateDataStallInfo: mDataStallTxRxSum={txSum=102 rxSum=97} preTxRxSum={txSum=102 rxSum=97}
D/WifiDataStallTracker(  929): updateDataStallInfo: NONE
D/WifiDataStallTracker(  929): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=175
E/WifiStateMachine(  929): WiFiStateMachine SCAN ALARM
D/PMS     (  929): acquireWL(31e3ea4e): PARTIAL_WAKE_LOCK  *alarm* 0x1 929 1000 WorkSource{1000}
E/WifiStateMachine(  929): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  929): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  929):     Client/Owner: Client
D/WifiDisplayAdapter(  929):     GroupId: 
D/WifiDisplayAdapter(  929):     Passphrase: 
D/WifiDisplayAdapter(  929):     SessionId: 0
D/WifiDisplayAdapter(  929):     IP Address: }
E/WifiStateMachine(  929): processMsg: ConnectedState
V/AlarmManager(  929): sending alarm PendingIntent{10167aad: PendingIntentRecord{1c121e2 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455029416135, Int=20000
E/WifiStateMachine(  929):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2062 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.9 fiv=60000 [on:0 tx:0 rx:0 period:793] from screen [on:0 period:-964497206]
D/PMS     (  929): releaseWL(31e3ea4e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:2062 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.9 fiv=60000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-964497205]
E/WifiStateMachine(  929): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.06 rxSuccessRate=0.95 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-65
E/WifiStateMachine(  929): WifiStateMachine CMD_START_SCAN with age=16953 interval=60000 maxinterval=300000
E/WifiStateMachine(  929): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  929): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  929): has c0:ff:d4:d3:aa:48 freq=2412 age=797 ?=true
E/WifiStateMachine(  929): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1351): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1351): wpa_supplicant_scan enter
D/wpa_supplicant( 1351): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1351): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1351): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1351): WPS:  * Request Type
D/wpa_supplicant( 1351): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1351): WPS:  * UUID-E
D/wpa_supplicant( 1351): WPS:  * Primary Device Type
D/wpa_supplicant( 1351): WPS:  * RF Bands (3)
D/wpa_supplicant( 1351): WPS:  * Association State
D/wpa_supplicant( 1351): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1351): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1351): WPS:  * Manufacturer
D/wpa_supplicant( 1351): WPS:  * Model Name
D/wpa_supplicant( 1351): WPS:  * Model Number
D/wpa_supplicant( 1351): WPS:  * Device Name
D/wpa_supplicant( 1351): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1351): P2P: * P2P IE header
D/wpa_supplicant( 1351): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1351): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1351): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1351): wlan0: Add radio work 'scan'@0x5572e77680
D/wpa_supplicant( 1351): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1351): wlan0: Starting radio work 'scan'@0x5572e77680 after 0.000038 second wait
D/wpa_supplicant( 1351): wlan0: nl80211: scan request
E/WifiStateMachine(  929): [1,455,029,416,140 ms] noteScanstart no scan source
D/wpa_supplicant( 1351): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1351): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1351): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1351): wlan0: Own scan request started a scan in 0.000135 seconds
I/wpa_supplicant( 1351): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  929): handleMessage: X
D/WifiMonitor(  929): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  929): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  929): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  929): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/cutils-trace( 6083): Error opening trace file: Permission denied (13)
D/wpa_supplicant( 1351): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1351): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1351): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1351): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1351): wlan0: Scan completed in 0.094499 seconds
D/wpa_supplicant( 1351): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1351): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1351): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1351): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
I/wpa_supplicant( 1351): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-65
I/wpa_supplicant( 1351): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
D/wpa_supplicant( 1351): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1351): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1351): wlan0: Scan-only results received
D/wpa_supplicant( 1351): wlan0: Radio work 'scan'@0x5572e77680 done in 0.095444 seconds
E/WifiMonitor(  929): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  929): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  929): handleMessage: E msg.what=147461
E/WifiStateMachine(  929): processMsg: ConnectedState
E/WifiStateMachine(  929):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  929): processMsg: ConnectModeState
E/WifiStateMachine(  929):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  929): processMsg: DriverStartedState
E/WifiStateMachine(  929):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  929): processMsg: SupplicantStartedState
E/WifiStateMachine(  929):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  929): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1351): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  929): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  929): [1,455,029,416,241 ms] noteScanEnd no scan source
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1351): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  929): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@29556844 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  929): NG7005g c0:ff:d4:d3:aa:4a rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  929): NG700 c0:ff:d4:d3:aa:48 rssi=-65 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  929): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  929): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  929):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-65 freq=2412
E/WifiAutoJoinController (  929): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  929): ageScanResultsOut delay 40000 size 3 now 1455029416243
E/WifiAutoJoinController (  929): newSupplicantResults size=3 known=1 true
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1351): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  929): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  929): ssid=NG700
E/WifiAutoJoinController (  929): id=0
E/WifiAutoJoinController (  929): mode=station
E/WifiAutoJoinController (  929): pairwise_cipher=CCMP
E/WifiAutoJoinController (  929): group_cipher=CCMP
E/WifiAutoJoinController (  929): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  929): wpa_state=COMPLETED
E/WifiAutoJoinController (  929): ip_address=192.168.1.130
E/WifiAutoJoinController (  929): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  929): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  929): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  929): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  929): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-65,-127) num=(1,0)
E/WifiAutoJoinController (  929): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  929): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-65 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  929): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  929): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  929): Done attemptAutoJoin status=0
E/WifiConfigStore(  929):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  929): handleMessage: X
D/CustomizationManager( 6083): ====startRecUseTime====
D/htc.customization.log.level( 6083):  is 
W/CustomizationLogLevel( 6083): Level value is invalid, use default level 2
D/CustomizationManager( 6083):  Read ACC file spent 0.033 (s)
D/CIDMapFileReader( 6083): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6083): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6083): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6083): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6083): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6083): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6083): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6083): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6083): Parsing tag category name = system
I/CustomizationCIDLoader( 6083): Parsing tag category name = application
I/CustomizationCIDLoader( 6083): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6083): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6083): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6083): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6083): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6083): add string-array item, value = 42507
I/CustomizationCIDLoader( 6083): add string-array item, value = 21902
I/CustomizationCIDLoader( 6083): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6083): add string-array item, value = 23420
I/CustomizationCIDLoader( 6083): add string-array item, value = 22299
I/CustomizationCIDLoader( 6083): add string-array item, value = 24002
I/CustomizationCIDLoader( 6083): add string-array item, value = 23210
I/CustomizationCIDLoader( 6083): add string-array item, value = 23205
I/CustomizationCIDLoader( 6083): add string-array item, value = 23806
I/CustomizationCIDLoader( 6083): add string-array item, value = 23430
I/CustomizationCIDLoader( 6083): add string-array item, value = 23408
I/CustomizationCIDLoader( 6083): add string-array item, value = 27205
I/CustomizationCIDLoader( 6083): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6083): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6083):  Read CID file spent 0.085 (s)
D/CustomizationManager( 6083):  All configurations done spent 0.085 (s)
D/PMS     (  929): acquireHCC(35c2b76f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 929 1000 null
I/ActivityManager(  929): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6083 on display 0
D/PMS     (  929): acquireHCC(6a61c7c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 929 1000 null
W/asset   (  929): Copying FileAsset 0x55a8329320 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  929): acquireWL(3fed5b8b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 929 1000 null
I/AnimationUtil(  929): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1489): [onPause]
I/FeedProviderManager( 1489): onPause
I/FeedHostManager( 1489): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@55b42f3
I/SocialFeedProvider( 1489): +onPause
I/SocialFeedProvider( 1489): -onPause
W/HtcSystemUPManager(  929): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  929): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6102 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  929): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  929): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  929): hiding MENU key
W/asset   ( 6102): Copying FileAsset 0xac060690 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1489): [trimMemory] 20
I/WebViewFactory( 6102): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6102): Time to load native libraries: 9 ms (timestamps 2898-2907)
I/LibraryLoader( 6102): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6102): Binding Chromium to main looper Looper (main, tid 1) {202b528a}
I/LibraryLoader( 6102): Expected native library version number "",actual native library version number ""
I/chromium( 6102): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6102): Initializing chromium process, singleProcess=true
W/art     ( 6102): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6102): ApplicationContext is null in ApplicationStatus
W/chromium( 6102): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6102): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6102): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6102): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6102): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6102): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6102): Local Branch: 
I/Adreno-EGL( 6102): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6102): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6102):                  d74aa161a12b9c6fc6332151
W/System.err(  929): java.lang.Throwable: stack dump
D/BluetoothManagerService(  929): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  929): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c624d75:true
W/System.err(  929): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  929): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  929): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  929): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6102): 846466390: getState(). Returning 12
E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=175
W/art     ( 6102): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6102): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6102): CordovaWebView is running on device made by: HTC
W/art     ( 6102): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6102): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6102): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/art     (  929): Explicit concurrent mark sweep GC freed 45476(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 17MB/25MB, paused 1.718ms total 158.917ms
D/FindExtension( 6102): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6102): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@6111ec7, mServedView=org.apache.cordova.engine.SystemWebView{2194ecf4 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@25536c1d
I/InputMethodManagerService(  929): Disable input method client, pid=1489
D/StatusBarManagerService(  929): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  929): Enable input method client, pid=6102
D/PMS     (  929): releaseWL(3fed5b8b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  929): Displayed com.test.thalitest/.MainActivity: +934ms
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
W/XT9_C   ( 1378): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1378): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1378): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1378): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6102): Cannot call determinedVisibility() - never saw a connection for the pid: 6102
D/JsMessageQueue( 6102): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6102): JniHelper::setJavaVM(0xaaef38f8), pthread_self() = -1407137416,
,I/chromium( 6102): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=175
,E/WifiStateMachine(  929): handleMessage: E msg.what=131155
,E/WifiStateMachine(  929): processMsg: ConnectedState
,E/WifiStateMachine(  929):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:2208] from screen [on:0 period:-964494995] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  929): processMsg: L2ConnectedState,
,E/WifiStateMachine(  929):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-964494993] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  929):  get link layer stats 0
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1351): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  929): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
,E/WifiStateMachine(  929): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.03 txretriesrate=0.00 rxrate=0.47 userTriggerdPenalty0
E/WifiStateMachine(  929):  good link -> stuck count =0
E/WifiStateMachine(  929):  badRSSI count0 lowRSSI count0 --> score 56
,E/WifiStateMachine(  929):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  929): RSSI current: 3 new: -65, 3
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  929): handleMessage: X
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 3109): handler message = 4011
,E/HtcModeClient( 3109): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3109): Don't start project servcice
,D/HtcModeClient( 3109): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3109): connectState: CONNECTION_READY = false
D/SilentMusic( 3109): call stop
D/HtcModeClient( 3109): close connection
W/HtcModeClient( 3109): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3109): read the terminate packet, so break
I/ActivityManager(  929): Killing 3109:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  929): killProcessQuiet, pid=3109
,D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  929): Recipient 3109
,D/PMS     (  929): releaseHCC(35c2b76f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
,D/PMS     (  929): releaseHCC(6a61c7c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6102): Initializing JXcore engine
,W/jxcore-log( 6102): JXcore engine is ready
,W/jxcore-log( 6102): Starting JXcore engine
,W/jxcore-log( 6102): Platform android
W/jxcore-log( 6102): 
,W/jxcore-log( 6102): Process ARCH arm
W/jxcore-log( 6102): 
,E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=175
,I/jxcore-log( 6102): JXcore Cordova bridge is ready!
I/jxcore-log( 6102): 
W/jxcore-log( 6102): JXcore engine is started
,E/jxcore  ( 6102): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6102): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6102): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PMS     (  929): acquireWL(33d536e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 929 1000 null
,W/PluginManager( 6102): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 48ms. Plugin should use CordovaInterface.getThreadPool().
,W/HtcSystemUPManager(  929): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1489): [onResume]
,I/FeedProviderManager( 1489): onResume
I/SocialFeedProvider( 1489): +onResume
I/SocialFeedProvider( 1489): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1489): -onResume
,D/StatusBarManagerService(  929): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  929): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  929): hiding MENU key
,D/FindExtension( 1489): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1489): Defer allocateBuffers to drawing time,
,I/InputMethodManagerService(  929): Disable input method client, pid=6102
D/StatusBarManagerService(  929): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
I/InputMethodManagerService(  929): Enable input method client, pid=1489
,W/IInputConnectionWrapper( 6102): reportFullscreenMode on inactive InputConnection
,D/PMS     (  929): releaseWL(33d536e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  929): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  929): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  929): hiding MENU key
,D/Process (  929): killProcessQuiet, pid=5260
I/ActivityManager(  929): Killing 5260:com.google.android.setupwizard/u0a77 (adj 15): empty #17,
,D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 ,
,I/ActivityManager(  929): Recipient 5260
,W/OpenGLRenderer( 1489): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=176
E/WifiTrafficPoller(  929): notifying of data activity 1
,D/WIFI_ICON( 1222): WifiActivity: 1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  929): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6158 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  929): acquireWL(89b1536): PARTIAL_WAKE_LOCK  *alarm* 0x1 929 1000 WorkSource{10076}
V/AlarmManager(  929): sending alarm PendingIntent{842ac37: PendingIntentRecord{3e6645a4 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455029420354, Int=60000
,D/PMS     (  929): releaseWL(89b1536): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6158): SMSBackupAgentService started,
D/SMSBackup( 6158): Checking restore status
,D/SMSBackup( 6158): Restore complete,
D/SMSBackup( 6158): cancelCheckAlarm
,D/SMSBackup( 6158): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  929): killProcessQuiet, pid=5597
I/ActivityManager(  929): Killing 5597:com.google.android.gm/u0a106 (adj 15): empty #17
,D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  929): Recipient 5597
,E/WifiDataStallTracker(  929): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  929): updateDataStallInfo: mDataStallTxRxSum={txSum=102 rxSum=97} preTxRxSum={txSum=102 rxSum=97},
D/WifiDataStallTracker(  929): updateDataStallInfo: NONE
D/WifiDataStallTracker(  929): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1222): WifiActivity: 0
,E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=176
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  929): notifying of data activity 0
,E/WifiStateMachine(  929): handleMessage: E msg.what=131155,
E/WifiStateMachine(  929): processMsg: ConnectedState
,E/WifiStateMachine(  929):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-964491974] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-964491972] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  929):  get link layer stats 0
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1351): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  929): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
,E/WifiStateMachine(  929): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.02 txretriesrate=0.00 rxrate=0.74 userTriggerdPenalty0,
E/WifiStateMachine(  929):  good link -> stuck count =0
E/WifiStateMachine(  929):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  929):  isHighRSSI       ---> score=61
E/WifiStateMachine(  929): handleMessage: X
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiWatchdogStateMachine(  929): RSSI current: 3 new: -65, 3
,E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=176
,E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=177
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  929): notifying of data activity 1
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1222): WifiActivity: 0
,E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=177
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  929): notifying of data activity 0
,E/WifiStateMachine(  929): handleMessage: E msg.what=131155,
E/WifiStateMachine(  929): processMsg: ConnectedState
E/WifiStateMachine(  929):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-964488951] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-964488950] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  929):  get link layer stats 0
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1351): environment dirty rate=0 [0][0][0],
,E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  929): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  929): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.01 txretriesrate=0.00 rxrate=0.87 userTriggerdPenalty0
E/WifiStateMachine(  929):  good link -> stuck count =0
E/WifiStateMachine(  929):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  929):  isHighRSSI       ---> score=61
,E/WifiStateMachine(  929): handleMessage: X
D/WifiWatchdogStateMachine(  929): RSSI current: 3 new: -64, 3
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=177
,I/SensorManager(  929): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1ec26fa
,I/PMS     (  929): Going to sleep due to screen timeout (uid 1000)...
W/SensorService(  929): Following SensorService logs are not warning, just make sure they are printed
D/ActivityManager(  929): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{b7b4ec2 #7 A=.Prism U=0 sz=1}
W/SensorService(  929): disable: get sensor name = Accelerometer Sensor
W/PMS     (  929): mWirelessDisplayManager is null
W/PMS     (  929): mWirelessDisplayManager is still null
W/SensorService(  929): pid=929, uid=1000
W/PMN     (  929): goingToSleep
W/SensorService(  929): Active sensors: size = 4
D/PMS     (  929): acquireWL(218bd4d3): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 929 1000 null
W/SensorService(  929): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  929): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  929): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  929): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  929): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1ec26fa, eanble = 0, strlen(mName) = 90
W/SensorService(  929): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  929): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3fe2c8bd
W/SensorService(  929): Listener[1] = com.htc.smartdim.sensor_eye@20b5df2c
W/SensorService(  929): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/HtcLockScreen( 1222): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMN     (  929): goingToSleep done
,I/FeedHostManager( 1489): [onPause]
I/PMS     (  929): Sleeping (uid 1000)...
I/FeedProviderManager( 1489): onPause
D/XAN-DPS (  929): prepareColorFade 1
I/FeedHostManager( 1489): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@55b42f3
I/SocialFeedProvider( 1489): +onPause
I/SocialFeedProvider( 1489): -onPause
,I/ActivityManager(  929): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6181 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/Adreno-EGL(  929): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
,I/Adreno-EGL(  929): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  929): Build Date: 03/09/15 Mon
I/Adreno-EGL(  929): Local Branch: 
I/Adreno-EGL(  929): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  929): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  929):                  d74aa161a12b9c6fc6332151
,D/AlarmManager(  929): ACTION_SCREEN_ON
I/AlarmManager(  929): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  929): [AlarmQueuing] done recovering
I/AlarmManager(  929): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  929): [AlarmQueuing] done EPS screen off alarm recovering
,W/HtcSystemUPManager(  929): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
E/WifiTrafficPoller(  929): ENABLE_TRAFFIC_STATS_POLL true Token 11
,E/WifiTrafficPoller(  929):  packet count Tx=117 Rx=177
,D/PMS     (  929): releaseWL(218bd4d3): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiDataStallTracker(  929): ENABLE_DATA_MONITOR_POLL true Token 1
,E/WifiStateMachine(  929): handleMessage: E msg.what=131167
,E/WifiStateMachine(  929): processMsg: ConnectedState
D/WifiDataStallTracker(  929): updateDataStallInfo: mDataStallTxRxSum={txSum=102 rxSum=97} preTxRxSum={txSum=102 rxSum=97}
D/WifiDataStallTracker(  929): updateDataStallInfo: NONE
E/WifiStateMachine(  929):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
D/WifiDataStallTracker(  929): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  929): processMsg: ConnectModeState
V/SRS_Proc(  417): ParamSet string: screen_state=on,
E/audio_a2dp_hw(  417): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiDisplayAdapter(  929): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  929):     Client/Owner: Client
D/WifiDisplayAdapter(  929):     GroupId: 
D/WifiDisplayAdapter(  929):     Passphrase: 
D/WifiDisplayAdapter(  929):     SessionId: 0
D/WifiDisplayAdapter(  929):     IP Address: }
E/WifiStateMachine(  929):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  929): processMsg: DriverStartedState
E/WifiStateMachine(  929):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  929): processMsg: SupplicantStartedState
E/WifiStateMachine(  929):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  929): processMsg: DefaultState
E/WifiStateMachine(  929):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  929):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1351): SET_SCREEN_ON:On
I/wpa_supplicant( 1351): htc_wext_set_keepalive +
I/wpa_supplicant( 1351): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1351): getPrivFuncNum +	
I/wpa_supplicant( 1351): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1351): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1351): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1351): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1351): htc_wext_set_TX_TRACKING - ret = 0
D/WifiController(  929): handleMessage: E msg.what=155650
D/WifiController(  929): processMsg: DeviceActiveState
D/WifiController(  929): processMsg: StaEnabledState
D/WifiController(  929): processMsg: DefaultState
E/WifiStateMachine(  929): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  929): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  929): handleScreenStateChanged Exit: true
E/WifiStateMachine(  929): handleMessage: X
E/WifiStateMachine(  929): handleMessage: E msg.what=131154
E/WifiStateMachine(  929): processMsg: ConnectedState
E/WifiStateMachine(  929):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiController(  929): handleMessage: X
D/NetworkPolicy(  929): updateScreenOn: false
V/NetworkPolicy(  929): updateIfacesLocked()
D/NetworkManagementService(  929): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/wpa_supplicant( 1351): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  929): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  929): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  929): handleMessage: X
E/WifiStateMachine(  929): handleMessage: E msg.what=131127
E/WifiStateMachine(  929): processMsg: ConnectedState
E/WifiStateMachine(  929):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  929): processMsg: ConnectModeState
E/WifiStateMachine(  929):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  929): handleMessage: X
E/WifiStateMachine(  929): handleMessage: E msg.what=131129
E/WifiStateMachine(  929): processMsg: ConnectedState
E/WifiStateMachine(  929):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  929): processMsg: ConnectModeState
E/WifiStateMachine(  929):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1351): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1351): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  929): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  929): WifiMonitor:wlan0 cnt=34 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  929): handleMessage: X
,W/ResourcesManager( 6181): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/XAN-DPS (  929): prepareColorFade done,
D/XAN-DPS (  929): setBrightness to 0
,I/SensorManager(  929): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@3fe2c8bd,
I/DisplayManagerService(  929): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  929): Following SensorService logs are not warning, just make sure they are printed
V/ActivityManager(  929): Display changed displayId=0
W/SensorService(  929): disable: get sensor name = CM32181 Light sensor
D/DotMatrix( 1307): [EventService]  onDisplayChanged: 0
I/CalendarProvider2( 6181): Created com.android.providers.calendar.CalendarAlarmManager@202b528a(com.htc.providers.calendar.HtcCalendarProvider@65460fb)
W/SensorService(  929): pid=929, uid=1000
W/SensorService(  929): Active sensors: size = 3
W/SensorService(  929): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  929): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  929): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  929): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@3fe2c8bd, eanble = 0, strlen(mName) = 67
W/SensorService(  929): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  929): Listener[0] = com.htc.smartdim.sensor_eye@20b5df2c
W/SensorService(  929): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
,D/CalendarProvider2( 6181): wait start:true,
,D/DotMatrix( 1307): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/CalendarProvider2( 6181): wait end:false,
,I/ActivityManager(  929): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6211 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,W/ContextImpl( 6211): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6211): MY_DEBUG = false,
,W/ContextImpl( 6211): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/GpsLocationProvider(  929): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  929): acquireWL(284398c3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6211 1000 null
,D/SmartSyncUtils( 6211): isEpsOn(), nState = 0
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  929): Setting HAL interactive mode to false
D/SurfaceControl(  929): Excessive delay in setPowerMode(): 298ms
D/PMS     (  929): Setting HAL interactive mode to false done
W/HtcSystemUPManager(  929): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  929): Setting HAL auto-suspend mode to true
D/PMS     (  929): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  929): screenObserver, isScreenOn=false
D/StatusBarManagerService(  929): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  929): Disable input method client, pid=1489
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,D/PMS     (  929): acquireWL(2725a540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
,I/BatteryService(  929): n_update end
D/PMS     (  929): releaseWL(2725a540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HABCtrl (  929): TPE algorithm. remove timeout.
D/PMS     (  929): OOBE c monitor 11
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): onReceive BATTERY_CHANGED
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  929): updateBatteryInfo
D/WifiController(  929): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NfcService( 1458): ScreenObserver: OFF
D/PMS     (  929): runPSCheck
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  929): Checking...
D/WifiController(  929): processMsg: DeviceActiveState
I/HtcPowerSaver(  929): >> updateStatus
D/WifiController(  929): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  929): processMsg: DefaultState
,D/PMS     (  929): releaseWL(284398c3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/WifiController(  929): handleMessage: X
D/WifiController(  929): battery changed pluggedType: 2
D/NfcService( 1458): applyRouting - 0
,D/PMS     (  929): acquireWL(32e10c79): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1458 1027 null
D/NfcService( 1458): applyRouting -2
D/NfcService( 1458): applyRouting
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
D/NfcService( 1458): Ignore this applyRouting...
I/HtcPowerSaver(  929): << updateStatus
,D/PMS     (  929): releaseWL(32e10c79): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/IntentController( 1222): receive(android.intent.action.SCREEN_ON,1,false)
,D/PMS     (  929): acquireWL(1a355dbe): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): acquireWL(2a3cfe1f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): releaseWL(2a3cfe1f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  929): releaseWL(1a355dbe): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl(  929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartDim(  929): Init customizeScreenOffDelayClass error,
,I/InputManager(  929): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1222): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false),
,D/AlarmManager(  929): ACTION_SCREEN_OFF,
,I/AlarmManager(  929): [AlarmQueuing] screen off now: ,
I/AlarmManager(  929): [AlarmQueuing] data connection: true
I/AlarmManager(  929): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  929): ENABLE_TRAFFIC_STATS_POLL false Token 12
,W/ContextImpl( 6211): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
D/WifiDataStallTracker(  929): stopDataStallAlarm 
D/WifiDisplayAdapter(  929): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  929):     Client/Owner: Client
D/WifiDisplayAdapter(  929):     GroupId: 
D/WifiDisplayAdapter(  929):     Passphrase: 
D/WifiDisplayAdapter(  929):     SessionId: 0
D/WifiDisplayAdapter(  929):     IP Address: }
E/WifiDataStallTracker(  929): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  929): handleMessage: E msg.what=131167
E/WifiStateMachine(  929): processMsg: ConnectedState
E/WifiStateMachine(  929):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  929): processMsg: ConnectModeState
E/WifiStateMachine(  929):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  929): processMsg: DriverStartedState
E/WifiStateMachine(  929):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  929): processMsg: SupplicantStartedState
E/WifiStateMachine(  929):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  929): processMsg: DefaultState
E/WifiStateMachine(  929):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  929):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  929): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1351): SET_SCREEN_ON:Off
I/wpa_supplicant( 1351): htc_wext_set_keepalive +
,I/wpa_supplicant( 1351): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1351): getPrivFuncNum +	
I/wpa_supplicant( 1351): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1351): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1351): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1351): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1351): htc_wext_set_keepalive - ret = 0
V/SRS_Proc(  417): ParamSet string: screen_state=off
E/WifiStateMachine(  929): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/audio_a2dp_hw(  417): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  929): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  929): handleScreenStateChanged Exit: false
E/WifiStateMachine(  929): handleMessage: X
,E/WifiStateMachine(  929): handleMessage: E msg.what=131154
E/WifiStateMachine(  929): processMsg: ConnectedState
E/WifiStateMachine(  929):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
D/NetworkPolicy(  929): updateScreenOn: false
E/WifiStateMachine(  929): handleMessage: X
V/NetworkPolicy(  929): updateIfacesLocked()
D/WifiController(  929): handleMessage: E msg.what=155651
D/WifiController(  929): processMsg: DeviceActiveState
D/WifiController(  929): processMsg: StaEnabledState
D/WifiController(  929): processMsg: DefaultState
D/WifiController(  929): handleMessage: X
,D/GpsLocationProvider(  929): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/NetworkManagementService(  929): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/ContextImpl( 6211): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/PowerUsageList:PowerUsageHelper( 6211): PowerProfile::POWER_SCREEN_FULL = 154.8
E/WifiDataStallTracker(  929): DATA_MONITOR_POLL false Token 3
,D/SmartSyncUtils( 6211): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6211): isEpsOn(), nState = 0
,W/ContextImpl( 6211): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  929): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  929): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@20b5df2c
W/SensorService(  929): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  929): disable: get sensor name = Accelerometer Sensor
,I/SensorManager( 1222): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@a8eaf6c, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  929): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  929): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  929): pid=929, uid=1000
W/SensorService(  929): Active sensors: size = 2
W/SensorService(  929): CM36686 Proximity sensor (handle=0x00000004, connections=1)
,W/SensorService(  929): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  929): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@20b5df2c, eanble = 0, strlen(mName) = 36
W/SensorService(  929): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  929): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  929): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  929): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  929): pid=929, uid=1000
W/SensorService(  929): Active sensors: size = 1
W/SensorService(  929): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  929): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@20b5df2c, eanble = 0, strlen(mName) = 36
W/SensorService(  929): Active Listeners: mActiveListeners.size() = 0,
W/SensorService(  929): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/SensorService(  929): pid=1222, uid=10041
,W/SensorService(  929): Active sensors: size = 2
W/SensorService(  929): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  929): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  929): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@a8eaf6c, eanble = 1, strlen(mName) = 56
W/SensorService(  929): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  929): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@a8eaf6c
W/SensorService(  929): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  929): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@20b5df2c
D/PowerUsageList:BatterySipperExt( 6211): gen(), null == sipper.uidObj, userId = 0
,I/ActivityManager(  929): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6243 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL false Token 13 num clients 6
E/ActivityThread(  929): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1f779df5 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  929): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1f779df5 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  929): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  929): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  929): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  929): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  929): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  929): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  929): 	,at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  929): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  929): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  929): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  929): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  929): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  929): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  929): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  929): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  929): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  929): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  929): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  929): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ClockController( 1222): stop clock update:screen off
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1438): start background delete task...
,I/IntentController( 1222): receive(android.intent.action.SCREEN_OFF,1,false),
,D/PMS     (  929): acquireWL(c2adc58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms},
D/ContactMessageStore( 1438): size: 0 , 0
D/ContactMessageStore( 1438): Background delete complete
,D/PMS     (  929): releaseWL(c2adc58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  446): Explicit concurrent mark sweep GC freed 8668(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 197us total 27.886ms
D/PMS     (  929): acquireWL(172d1b1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): releaseWL(172d1b1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 146us total 22.060ms,
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 157us total 18.110ms,
,I/RemoteViews( 1222): setHTCTheme(com.htc.updater,true,33751145),
,I/RemoteViews( 1222): apply : com.htc.updater 0 11 0 36,
,D/PMS     (  929): releaseWL(31a72953): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,D/SmartSyncUtils( 6211): getMobilePolicyEnabled, result = true
,D/Process (  929): killProcessQuiet, pid=5291
I/ActivityManager(  929): Killing 5291:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/WifiService(  929): New client listening to asynchronous messages
E/WifiTrafficPoller(  929): ADD_CLIENT: 7
,I/ActivityManager(  929): Recipient 5291
,D/PowerUsageList:PowerUsageHelper( 6211): MY_DEBUG = false
,D/Process (  929): killProcessQuiet, pid=5750
I/ActivityManager(  929): Killing 5750:com.google.android.partnersetup/u0a27 (adj 15): empty #17
E/WifiTrafficPoller(  929): TRAFFIC_STATS_POLL false Token 13 num clients 7
,D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  929): Recipient 5750
,I/CalendarProvider2( 6181): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6181): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  929): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6268 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  929): killProcessQuiet, pid=5970
I/ActivityManager(  929): Killing 5970:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  929): Recipient 5970
,W/ResourcesManager( 6268): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6268): onCreate
,D/ProviderChangeReceiver( 6268): ---------------------------------------------------
D/ProviderChangeReceiver( 6268): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  929): killProcessQuiet, pid=5993,
I/ActivityManager(  929): Killing 5993:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/HtcAlertService( 6268): start to updateAlertNotification!
D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  929): Recipient 5993,
,D/HtcAlertService( 6268): No fired or scheduled alerts,
D/HtcAlertUtils( 6268): -- cancelReminderNotification --
,D/HtcAlertUtils( 6268): broadcastExistReminder!,
,D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  929): handleMessage: E msg.what=131155
,E/WifiStateMachine(  929): processMsg: ConnectedState
,E/WifiStateMachine(  929):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-964485929] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-964485927] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  929): handleMessage: X
,E/WifiStateMachine(  929): handleMessage: E msg.what=131155,
E/WifiStateMachine(  929): processMsg: ConnectedState
,E/WifiStateMachine(  929):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1005] from screen [on:0 period:-964484921] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  929): processMsg: L2ConnectedState
E/WifiStateMachine(  929):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-964484918] gl hn u24 rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  929): handleMessage: X
,D/HtcUPManager( 1222): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  929): DATA_MONITOR_POLL false Token 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  929): killProcessQuiet, pid=5196
I/ActivityManager(  929): Killing 5196:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  929): Recipient 5196
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  929): acquireWL(39ad6696): PARTIAL_WAKE_LOCK  *alarm* 0x1 929 1000 WorkSource{1000}
,V/AlarmManager(  929): sending alarm PendingIntent{121a9217: PendingIntentRecord{229d6604 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455029450960, Int=0
V/AlarmManager(  929): sending alarm PendingIntent{1d31d7ed: PendingIntentRecord{c515622 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142218, Int=0
D/PMS     (  929): acquireWL(72c38b3): PARTIAL_WAKE_LOCK  *backup* 0x1 929 1000 null
,D/PMS     (  929): releaseWL(39ad6696): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
W/BackupManagerService(  929): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  929): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  929): releaseWL(72c38b3): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  929): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  929): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  929): acquireWL(148cde70): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 929 1000 null
,D/libc    (  929): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  929): [NET] android_getaddrinfofornet-, err=8
D/libc    (  929): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  929): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  929): [NET] android_getaddrinfo_proxy+
D/libc    (  929): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  929): [NET] android_getaddrinfo_proxy-, success
D/libc    (  929): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  929): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  929): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  929): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  929): acquireWL(2cb9719c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 929 1000 null
D/GpsLocationProvider(  929): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  929): releaseWL(148cde70): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  929):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  929): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  929): releaseWL(2cb9719c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  929): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  929): acquireWL(63b17a5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
I/BatteryService(  929): n_update end
D/PMS     (  929): releaseWL(63b17a5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  929): updateBatteryInfo
D/PMS     (  929): runPSCheck
D/HtcPowerSaver(  929): Checking...
,I/HtcPowerSaver(  929): >> updateStatus
,D/UsbnetService(  929): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  929): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  929): << updateStatus
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/WifiController(  929): battery changed pluggedType: 2
D/WifiController(  929): handleMessage: E msg.what=155652
,D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  929): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  929): processMsg: StaEnabledState
D/WifiController(  929): processMsg: DefaultState
D/WifiController(  929): handleMessage: X
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1438): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  929): acquireWL(16fb877a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 929 1000 WorkSource{1000}
V/AlarmManager(  929): sending alarm PendingIntent{2b01d108: PendingIntentRecord{11a6a0a1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=146161, Int=0
V/AlarmManager(  929): sending alarm PendingIntent{2ebc0b2b: PendingIntentRecord{3fba0b88 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=199592, Int=0
V/AlarmManager(  929): sending alarm PendingIntent{4ea8921: PendingIntentRecord{3e2aa146 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455029480469, Int=1800000
V/AlarmManager(  929): sending alarm PendingIntent{376e2f07: PendingIntentRecord{12a85834 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189242, Int=0
,D/PMS     (  929): acquireWL(28c5965d): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2167 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  929): acquireWL(a34b4a3): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2167 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  929): acquireWL(8cc3a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  929): releaseWL(16fb877a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
D/PMS     (  929): releaseWL(28c5965d): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 2167): Aggregate from 1455029378041 (log), 1455027680363 (data),
,D/PMS     (  929): acquireWL(a8a79cc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  929): releaseWL(8cc3a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  929): releaseWL(a34b4a3): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Ads     ( 2167): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication,
,D/PMS     (  929): acquireWL(de0deef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  929): releaseWL(a8a79cc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): releaseWL(de0deef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  929): acquireWL(885edfc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  929): releaseWL(885edfc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  929): acquireWL(3c714c85): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): acquireWL(356c4ada): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): acquireWL(3441ede8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  929): releaseWL(3c714c85): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1880): Vacuum at: now=1455029513874 tag=VacuumService
,D/PMS     (  929): releaseWL(356c4ada): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  929): acquireWL(8d43aa6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1880): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1880): No account for auth token provided
,D/PMS     (  929): releaseWL(8d43aa6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  929): acquireWL(2e9fbce7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): releaseWL(2e9fbce7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1880): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 1880): [NET] android_getaddrinfo_proxy+
D/libc    ( 1880): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1880): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1880): No account for auth token provided,
,W/Uploader( 1880): No account for auth token provided
,W/Uploader( 1880):  no longer exists, so no auth token.,
,W/Uploader( 1880): No account for auth token provided,
,I/art     ( 1880): Explicit concurrent mark sweep GC freed 32638(1801KB) AllocSpace objects, 1(40KB) LOS objects, 47% free, 4MB/8MB, paused 1.761ms total 103.171ms
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 4 40,
E/Uploader( 1880): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1880): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1880): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
,E/Uploader( 1880): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1880): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1880): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1880): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1880): No account for auth token provided
,D/PMS     (  929): releaseWL(3441ede8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  929): acquireWL(23b03cfb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): releaseWL(23b03cfb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  929): acquireWL(9c0a118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): releaseWL(9c0a118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1578): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1edc5f6d
,D/Process (  929): killProcessQuiet, pid=5838
,I/ActivityManager(  929): Killing 5838:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  929): Recipient 5838
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  929): acquireWL(8aa1771): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
I/BatteryService(  929): n_update end
D/PMS     (  929): releaseWL(8aa1771): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  929): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  929): plugged=true pluggin=true
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  929): runPSCheck
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  929): Checking...
D/UsbnetService(  929): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  929): >> updateStatus
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  929): battery changed pluggedType: 2
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/WifiController(  929): handleMessage: E msg.what=155652
D/WifiController(  929): processMsg: DeviceActiveState
D/WifiController(  929): processMsg: StaEnabledState
D/WifiController(  929): processMsg: DefaultState
D/WifiController(  929): handleMessage: X
,I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  929): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1351): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  929): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  929): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  929): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  929): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
,D/PMS     (  929): acquireWL(15f69956): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
I/BatteryService(  929): n_update end
,D/PMS     (  929): releaseWL(15f69956): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  929): updateBatteryInfo
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/UsbnetService(  929): onReceive BATTERY_CHANGED
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  929): runPSCheck
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/WifiController(  929): handleMessage: E msg.what=155652
D/HtcPowerSaver(  929): Checking...
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  929): >> updateStatus
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiController(  929): battery changed pluggedType: 2
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  929): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  929): processMsg: StaEnabledState
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  929): processMsg: DefaultState
I/HtcPowerSaver(  929): << updateStatus
D/WifiController(  929): handleMessage: X
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  929): acquireWL(2b3badd7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null,
,D/UsbnetService(  929): BroadcastReceiver::onReceive+
I/BatteryService(  929): n_update end
D/UsbnetService(  929): onReceive BATTERY_CHANGED
D/PMS     (  929): releaseWL(2b3badd7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  929): updateBatteryInfo
D/WifiController(  929): handleMessage: E msg.what=155652
D/PMS     (  929): runPSCheck
D/WifiController(  929): processMsg: DeviceActiveState
D/WifiController(  929): battery changed pluggedType: 2
D/WifiController(  929): processMsg: StaEnabledState
D/HtcPowerSaver(  929): Checking...
D/WifiController(  929): processMsg: DefaultState
I/HtcPowerSaver(  929): >> updateStatus
D/WifiController(  929): handleMessage: X
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  929): << updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1880): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1880): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1880): 	,at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1880): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1880): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5797): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5797): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5797): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889),
E/PlayEventLogger( 5797): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5797): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5797): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5797): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,W/System  ( 5797): Ignoring header User-Agent because its value was null.
,D/libc    ( 5797): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5797): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5797): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5797): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5797): [NET] android_getaddrinfo_proxy+
D/libc    ( 5797): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5797): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  929): acquireWL(65ebee1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 929 1000 WorkSource{1000},
V/AlarmManager(  929): sending alarm PendingIntent{2b01d108: PendingIntentRecord{11a6a0a1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=206161, Int=0
,D/PMS     (  929): releaseWL(65ebee1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  929): acquireWL(17860406): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
I/BatteryService(  929): n_update end
D/PMS     (  929): releaseWL(17860406): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  929): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  929): runPSCheck
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  929): Checking...
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  929): >> updateStatus
,D/UsbnetService(  929): BroadcastReceiver::onReceive+,
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  929): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  929): << updateStatus
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/WifiController(  929): battery changed pluggedType: 2
D/WifiController(  929): handleMessage: E msg.what=155652
D/WifiController(  929): processMsg: DeviceActiveState
D/WifiController(  929): processMsg: StaEnabledState
D/WifiController(  929): processMsg: DefaultState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  929): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  929): acquireWL(300b58f4): PARTIAL_WAKE_LOCK  *alarm* 0x1 929 1000 WorkSource{10109},
V/AlarmManager(  929): sending alarm PendingIntent{2aa7681d: PendingIntentRecord{e6e5a92 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1455029671182, Int=0
,I/ActivityManager(  929): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6304 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  929): sending alarm PendingIntent{23813c63: PendingIntentRecord{15ff1060 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1455029734318, Int=0
,D/PMS     (  929): releaseWL(300b58f4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10071}
,I/art     (  448): Explicit concurrent mark sweep GC freed 8666(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 689us total 51.720ms,
,I/art     (  448): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 410us total 24.707ms
,I/art     (  448): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 415us total 27.912ms,
,E/cutils-trace( 6325): Error opening trace file: Permission denied (13),
I/dex2oat ( 6325): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6325): dex2oat: override thread count:4
,I/dex2oat ( 6325): dex2oat took 697.987ms (threads: 4)
,I/PushClient( 6304): ApplicationMonitor {31e74ac4}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6304): ApplicationMonitor {31e74ac4}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6304): ApplicationMonitor {31e74ac4}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6304): ApplicationMonitor {31e74ac4}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6304): ApplicationMonitor {31e74ac4}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6304): ApplicationMonitor {31e74ac4}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
I/PushClient( 6304): ApplicationMonitor {31e74ac4}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6304): ApplicationMonitor {31e74ac4}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6304): ApplicationMonitor {31e74ac4}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6304): PnsModel {3dfe11d7}: update(): Update registration caused by: alarm
,I/PushClient( 6304): PnsConfigModel {2c85723a}: <init>(): Use dm-client for provisioning.
,W/System.err( 6304): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 6304): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6304): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6304): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  929): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6333 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/art     (  929): Explicit concurrent mark sweep GC freed 40722(2MB) AllocSpace objects, 8(1272KB) LOS objects, 33% free, 18MB/28MB, paused 1.979ms total 199.780ms
,I/DeviceManagement( 6333): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6333 dbg=false s=true
,I/DeviceManagement( 6333): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6333): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6333): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6333): WorkflowService: Starting workflow service
,I/DeviceManagement( 6333): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3dfe11d7] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6333): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6333): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6333): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6333): SessionStateController: Checking invariants...
,I/DeviceManagement( 6333): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6333): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6333): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6333): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3dfe11d7],
,I/DeviceManagement( 6333): WorkflowService: Stopping workflow service,
,D/Process (  929): killProcessQuiet, pid=5772
I/ActivityManager(  929): Killing 5772:com.android.settings/1000 (adj 15): empty #17
,D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  929): Recipient 5772
,I/PushClient( 6304): PnsModel {3dfe11d7}: update(): The registration record has not expired yet. No need to update.,
I/ActivityManager(  929): Killing 6025:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  929): killProcessQuiet, pid=6025
,D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  929): Recipient 6025
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  929): acquireWL(2c97928d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
I/BatteryService(  929): n_update end
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/PMS     (  929): releaseWL(2c97928d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  929): onReceive BATTERY_CHANGED
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/WifiController(  929): battery changed pluggedType: 2
D/WifiController(  929): handleMessage: E msg.what=155652
D/HtcPowerSaver(  929): updateBatteryInfo
D/WifiController(  929): processMsg: DeviceActiveState
D/PMS     (  929): runPSCheck
D/WifiController(  929): processMsg: StaEnabledState
D/HtcPowerSaver(  929): Checking...
D/WifiController(  929): processMsg: DefaultState
I/HtcPowerSaver(  929): >> updateStatus
D/WifiController(  929): handleMessage: X
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  929): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/UsbnetService(  929): BroadcastReceiver::onReceive+,
D/PMS     (  929): acquireWL(113e8c42): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
D/UsbnetService(  929): onReceive BATTERY_CHANGED
I/BatteryService(  929): n_update end
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  929): releaseWL(113e8c42): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/NotificationService(  929): plugged=true pluggin=true
D/WifiController(  929): handleMessage: E msg.what=155652
D/WifiController(  929): battery changed pluggedType: 2
D/WifiController(  929): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  929): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  929): processMsg: DefaultState
,D/HtcPowerSaver(  929): updateBatteryInfo
D/WifiController(  929): handleMessage: X
D/PMS     (  929): runPSCheck
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  929): Checking...
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  929): >> updateStatus
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  929): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  929): acquireWL(236a0453): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null,
I/BatteryService(  929): n_update end
D/PMS     (  929): releaseWL(236a0453): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  929): updateBatteryInfo
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  929): plugged=true pluggin=true
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  929): runPSCheck
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  929): Checking...
D/UsbnetService(  929): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  929): >> updateStatus
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/WifiController(  929): battery changed pluggedType: 2
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  929): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  929): processMsg: DeviceActiveState
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  929): processMsg: StaEnabledState
I/HtcPowerSaver(  929): << updateStatus
D/WifiController(  929): processMsg: DefaultState
,D/WifiController(  929): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1438): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1438): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1438): sku_id=118
,D/ContactMessageStore( 1438): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1438): start background delete task...
,D/ContactMessageStore( 1438): size: 0 , 0
,D/ContactMessageStore( 1438): Background delete complete
,D/PMS     (  929): acquireWL(ca75190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
I/BatteryService(  929): n_update end,
D/PMS     (  929): releaseWL(ca75190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  929): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  929): onReceive BATTERY_CHANGED
D/PMS     (  929): runPSCheck
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  929): Checking...
D/UsbnetService(  929): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  929): >> updateStatus
D/WifiController(  929): handleMessage: E msg.what=155652
D/WifiController(  929): battery changed pluggedType: 2
D/WifiController(  929): processMsg: DeviceActiveState
D/WifiController(  929): processMsg: StaEnabledState
D/WifiController(  929): processMsg: DefaultState
D/WifiController(  929): handleMessage: X
,I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  929): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/PMS     (  929): acquireWL(377ca89): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
D/UsbnetService(  929): onReceive BATTERY_CHANGED
I/BatteryService(  929): n_update end
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  929): releaseWL(377ca89): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/NotificationService(  929): plugged=true pluggin=true
D/WifiController(  929): handleMessage: E msg.what=155652
D/WifiController(  929): battery changed pluggedType: 2
D/WifiController(  929): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  929): processMsg: StaEnabledState
D/HtcPowerSaver(  929): updateBatteryInfo
D/WifiController(  929): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  929): handleMessage: X
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  929): runPSCheck
D/HtcPowerSaver(  929): Checking...
I/HtcPowerSaver(  929): >> updateStatus
,I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  929): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  929): acquireWL(28ad2a8e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
I/BatteryService(  929): n_update end
D/PMS     (  929): releaseWL(28ad2a8e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  929): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  929): plugged=true pluggin=true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/PMS     (  929): runPSCheck
D/UsbnetService(  929): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  929): Checking...
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  929): >> updateStatus
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/WifiController(  929): handleMessage: E msg.what=155652
,D/WifiController(  929): battery changed pluggedType: 2
,D/WifiController(  929): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  929): processMsg: StaEnabledState
D/WifiController(  929): processMsg: DefaultState
D/WifiController(  929): handleMessage: X
,I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  929): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  929): acquireWL(c8692af): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 929 1000 WorkSource{1000}
V/AlarmManager(  929): sending alarm PendingIntent{2b01d108: PendingIntentRecord{11a6a0a1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=446161, Int=0
V/AlarmManager(  929): sending alarm PendingIntent{3857f6bc: PendingIntentRecord{1c098645 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940390, Int=0
I/bt-btm  ( 3033): Received oneshot timer event complete
I/bt-btm  ( 3033): btm_ble_timeout
I/bt-btm  ( 3033): btm_gen_resolvable_private_addr
,D/PMS     (  929): acquireWL(3555619a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3033 1002 null
,D/bt-btm  ( 3033): btm_ble_rand_enc_complete,
I/bt-btm  ( 3033): btm_gen_resolve_paddr_low
D/bt-smp  ( 3033): smp_encrypt_data
W/bt-smp  ( 3033): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3033): Plain text(LSB ~ MSB) = da 92 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3033): Encrypted text(LSB ~ MSB) = 73 7b b5 ae 48 5d 8a d2 a0 01 4e dc 28 ed cb 73 
I/bt-btm  ( 3033): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3033): Stopping oneshot timer
D/bt-btm  ( 3033): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  929): releaseWL(c8692af): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  929): releaseWL(3555619a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  929): acquireWL(1033aacb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
I/BatteryService(  929): n_update end
D/PMS     (  929): releaseWL(1033aacb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  929): updateBatteryInfo
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  929): plugged=true pluggin=true,
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/PMS     (  929): runPSCheck
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  929): Checking...
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  929): >> updateStatus
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
,D/UsbnetService(  929): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  929): << updateStatus
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/WifiController(  929): battery changed pluggedType: 2
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  929): handleMessage: E msg.what=155652
D/WifiController(  929): processMsg: DeviceActiveState
D/WifiController(  929): processMsg: StaEnabledState
D/WifiController(  929): processMsg: DefaultState
D/WifiController(  929): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  929): acquireWL(80bc2a8): PARTIAL_WAKE_LOCK  *alarm* 0x1 929 1000 WorkSource{10024}
V/AlarmManager(  929): sending alarm PendingIntent{384141c1: PendingIntentRecord{3217fd66 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=971184, Int=0
,V/AlarmManager(  929): sending alarm PendingIntent{352c3077: PendingIntentRecord{d9f14e4 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805362, Int=0
,V/AlarmManager(  929): sending alarm PendingIntent{65028a7: PendingIntentRecord{3f3a37c1 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455030274165, Int=0
D/PMS     (  929): acquireWL(34ae6154): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  929): releaseWL(34ae6154): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): acquireWL(2adf38fd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6211): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  929): releaseWL(80bc2a8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6211): MY_DEBUG = false,
,D/PowerUsageService( 6211): repeat time = 1455031185064,
,D/PMS     (  929): acquireWL(3bcca843): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  929): releaseWL(2adf38fd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  929): acquireWL(386b67f9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1880): Message class com.google.f.a.a.i
,D/PMS     (  929): releaseWL(386b67f9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1880): Using platform SSLCertificateSocketFactory,
,I/PowerUsageList:PowerUsageHelper( 6211): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6211): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  929): releaseWL(3bcca843): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  929): acquireWL(3b7d1d31): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): releaseWL(3b7d1d31): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  929): acquireWL(38108c16): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): releaseWL(38108c16): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  929): acquireWL(18be8997): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 929 1000 WorkSource{1000},
V/AlarmManager(  929): sending alarm PendingIntent{2b01d108: PendingIntentRecord{11a6a0a1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=986161, Int=0
,V/AlarmManager(  929): sending alarm PendingIntent{18d6c784: PendingIntentRecord{18555b6d com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455030325971, Int=0
,D/SmartSyncUtils( 6211): isEpsOn(), nState = 0,
,D/PMS     (  929): releaseWL(18be8997): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  929): acquireWL(18153a2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6211 1000 null
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6211): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6211): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6211): AlarmOnTime = -1,
,D/SmartSyncScreenOnOffTimeReceiver( 6211): SettingOnTime = 1455084000000, randomSettingOnTime = 1455083035000
D/SmartSyncScreenOnOffTimeReceiver( 6211): SettingOffTime = 1455062400000, randomSettingOffTime = 1455067570000
D/SmartSyncScreenOnOffTimeReceiver( 6211): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6211): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6211): bNightModeTurnOffOnce = false
,D/PMS     (  929): releaseWL(18153a2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  929): acquireWL(1cd82833): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null,
I/BatteryService(  929): n_update end
,D/PMS     (  929): releaseWL(1cd82833): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/UsbnetService(  929): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  929): updateBatteryInfo
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  929): runPSCheck
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  929): Checking...
D/WifiController(  929): handleMessage: E msg.what=155652
I/HtcPowerSaver(  929): >> updateStatus
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  929): processMsg: DeviceActiveState
D/WifiController(  929): battery changed pluggedType: 2
,D/WifiController(  929): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  929): processMsg: DefaultState
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  929): handleMessage: X
,I/HtcPowerSaver(  929): << updateStatus
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  929): acquireWL(2ebad7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
I/BatteryService(  929): n_update end
,D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/PMS     (  929): releaseWL(2ebad7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  929): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  929): updateBatteryInfo
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): BroadcastReceiver::onReceive-
D/PMS     (  929): runPSCheck
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  929): Checking...
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  929): >> updateStatus
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  929): battery changed pluggedType: 2
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  929): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  929): processMsg: DeviceActiveState
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  929): processMsg: StaEnabledState
I/HtcPowerSaver(  929): << updateStatus
,D/WifiController(  929): processMsg: DefaultState
D/WifiController(  929): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  929): User[0] Flushing usage stats to disk,
,TIME-OUT KILL (timeout was 1200000ms),I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  929): acquireWL(6f94169): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 929 1000 null
D/HeadsetStateMachine( 3033): Disconnected process message: 10, size: 0
I/BatteryService(  929): n_update end
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  929): releaseWL(6f94169): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  929): updateBatteryInfo
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  929): plugged=true pluggin=true
D/UsbnetService(  929): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  929): onReceive BATTERY_CHANGED
D/PMS     (  929): runPSCheck
D/UsbnetService(  929):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  929): Checking...
D/UsbnetService(  929): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  929): >> updateStatus
D/WifiController(  929): handleMessage: E msg.what=155652
D/WifiController(  929): processMsg: DeviceActiveState
D/WifiController(  929): processMsg: StaEnabledState
D/WifiController(  929): processMsg: DefaultState
D/WifiController(  929): battery changed pluggedType: 2
D/WifiController(  929): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  929): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  929): << updateStatus
I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 6370): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6370): ====startRecUseTime====
D/htc.customization.log.level( 6370):  is 
W/CustomizationLogLevel( 6370): Level value is invalid, use default level 2
D/CustomizationManager( 6370):  Read ACC file spent 0.043 (s)
D/CIDMapFileReader( 6370): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6370): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6370): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6370): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6370): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6370): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6370): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6370): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6370): Parsing tag category name = system
I/CustomizationCIDLoader( 6370): Parsing tag category name = application
I/CustomizationCIDLoader( 6370): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6370): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6370): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6370): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6370): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6370): add string-array item, value = 42507
I/CustomizationCIDLoader( 6370): add string-array item, value = 21902
I/CustomizationCIDLoader( 6370): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6370): add string-array item, value = 23420
I/CustomizationCIDLoader( 6370): add string-array item, value = 22299
I/CustomizationCIDLoader( 6370): add string-array item, value = 24002
I/CustomizationCIDLoader( 6370): add string-array item, value = 23210
I/CustomizationCIDLoader( 6370): add string-array item, value = 23205
I/CustomizationCIDLoader( 6370): add string-array item, value = 23806
I/CustomizationCIDLoader( 6370): add string-array item, value = 23430
I/CustomizationCIDLoader( 6370): add string-array item, value = 23408
I/CustomizationCIDLoader( 6370): add string-array item, value = 27205
I/CustomizationCIDLoader( 6370): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6370): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6370):  Read CID file spent 0.090 (s)
D/CustomizationManager( 6370):  All configurations done spent 0.090 (s)
D/PackageManager(  929): deletePackageAsUser: pkg=com.test.thalitest, pid=6370, uid=2000 userid=0
I/ActivityManager(  929): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  929): Killing 6102:com.test.thalitest/u0a366 (adj 11): stop com.test.thalitest
D/Process (  929): killProcessQuiet, pid=6102
D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  929): Skipping PackageSetting{1af3ef92 com.example.hello/10374} due to missing metadata
I/ActivityManager(  929): Recipient 6102
E/InputEventReceiver( 1378): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1bc21361 uid 10366 pid 6102} (c)'
W/ActivityManager(  929): Spurious death for ProcessRecord{2a4507ee 6102:com.test.thalitest/u0a366}, curProc for 6102: null
I/ActivityManager(  929): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/PMS     (  929): acquireWL(17e3148f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  929): releaseWL(17e3148f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1814): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1714): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  929): Cannot find grip_rejection_width, use default value instead
I/art     ( 5718): Explicit concurrent mark sweep GC freed 18777(1194KB) AllocSpace objects, 0(0B) LOS objects, 45% free, 2MB/4MB, paused 618us total 75.718ms
D/AccTypeManager( 1714): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1689): Cleaning up data for package: com.test.thalitest
I/[PluginManager]RegisterService( 1578): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/PhoneApp( 1438): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/AccTypeManager( 1714): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/art     ( 1489): Explicit concurrent mark sweep GC freed 69969(4MB) AllocSpace objects, 39(3MB) LOS objects, 34% free, 30MB/46MB, paused 1.206ms total 127.935ms
D/Prism.PackageStateRece_( 1489): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1489): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1489): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/[PluginManager]RegisterService( 1578): handle notify Blinkfeed plugin client changed
E/ExternalAccountType( 1714): Unsupported attribute readOnly
I/ActivityManager(  929): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6390 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/Launcher( 1489): Deferring update until onResume
D/Launcher( 1489): waitUntilResume // bindAppsRemoved
W/PackageManager(  929): Unable to load service info ResolveInfo{35109f77 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  929): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  929): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  929): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  929): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  929): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  929): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  929): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  929): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  929): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  929): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  929): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  929): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  929): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  929): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  929): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  929): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/art     (  929): Explicit concurrent mark sweep GC freed 25200(1816KB) AllocSpace objects, 9(828KB) LOS objects, 33% free, 18MB/28MB, paused 1.657ms total 213.649ms
W/asset   (  929): Copying FileAsset 0x55a7e82fb0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/JobSchedulerService(  929): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  929): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  929): removeObsoleteFile: deleting file=8_task_thumbnail.png
W/ContextImpl( 6390): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
I/ActivityManager(  929): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6415 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/InputMethodManagerService(  929): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/ResourcesManager(  929): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6415): -onCreate()
V/Settings:HtcSettingsApplication( 6415): [6415/6415] onCreate()
D/Process (  929): killProcessQuiet, pid=5446
I/ActivityManager(  929): Killing 5446:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  929): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/Settings:HtcWirelessFeatureFlags( 6415): id/is att sku: 118/false
I/ActivityManager(  929): Recipient 5446
E/Settings:HtcWrapHeaderInfo( 6415): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6415): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 6415): updateDevelopment, bPrefShow = true
E/SQLiteLog( 1880): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1880): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x55a76413d0
E/Settings:HtcUmcWidgetEnabler( 6415): isSupportMusicChannel(): false
E/AndroidRuntime( 1880): FATAL EXCEPTION: main
E/AndroidRuntime( 1880): Process: com.google.process.gapps, PID: 1880
E/AndroidRuntime( 1880): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1880): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1880): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1880): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1880): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1880): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1880): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1880): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1880): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1880): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1880): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1880): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1880): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1880): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1880): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1880): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1880): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1880): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1880): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1880): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1880): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1880): 	... 9 more
E/ActivityManager(  929): App crashed! Process: com.google.process.gapps
D/Process ( 1880): killProcess, pid=1880
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]support         :false
E/DropBoxManagerService(  929): Can't write: system_app_crash
E/DropBoxManagerService(  929): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  929): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  929): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  929): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  929): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  929): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  929): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  929): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  929): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  929): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  929): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  929): 	... 5 more
D/Process ( 1880): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  929): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 6415): isSupportVoWifi: null
E/ActivityThread( 6415): Failed to find provider info for com.htc.vowifi
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6415): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 6415): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 6415): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6415): [supportHomeButton]support         :false
I/ActivityManager(  929): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6415): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 6415): isSupportVoWifi: null
I/ActivityManager(  929): Recipient 1880
I/ActivityManager(  929): Process com.google.process.gapps (pid 1880) has died
W/ActivityManager(  929): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
W/ActivityManager(  929): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
W/RocketImpressions( 2167): ClearcutLogger connection suspended: 1
I/Prism.ItemManager( 1489): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1489): loadItems() com.htc.launcher.pageview.WidgetManager@1850c27e +
I/Prism.WidgetManager( 1489): onLoadItems() +
W/ResourcesManager( 1489): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.

```
