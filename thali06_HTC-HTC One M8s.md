#### Test 58751238ee11130_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  947): handleMessage: E msg.what=131155
E/WifiStateMachine(  947): processMsg: ConnectedState
,E/WifiStateMachine(  947):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-966193751] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-966193750] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947):  get link layer stats 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  947): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-64 "NG700"WPA_PSK
E/WifiStateMachine(  947): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.24 txretriesrate=0.00 rxrate=1.17 userTriggerdPenalty0
E/WifiStateMachine(  947):  good link -> stuck count =0
E/WifiStateMachine(  947):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  947):  isHighRSSI       ---> score=61
E/WifiStateMachine(  947): handleMessage: X
--------- beginning of system
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -65, 3
E/cutils-trace( 6330): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6330): ====startRecUseTime====
D/htc.customization.log.level( 6330):  is 
W/CustomizationLogLevel( 6330): Level value is invalid, use default level 2
D/PMS     (  947): acquireWL(a595294): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000}
V/AlarmManager(  947): sending alarm PendingIntent{20cfb878: PendingIntentRecord{27764b51 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=95005, Int=0
D/PMS     (  947): releaseWL(a595294): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
I/ClockController( 1221): schedule update now=1455027720049 next=59951
D/CustomizationManager( 6330):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 6330): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6330): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6330): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6330): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6330): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6330): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6330): Parsing tag item name = HTC__031
I/Clock   ( 1221): updateClock:15:22 Europe/Warsaw
I/Clock   ( 1221): updateClock:15:22 Europe/Warsaw
I/Clock   ( 1221): updateClock:15:22 Europe/Warsaw
V/CustomizationCIDLoader( 6330): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6330): Parsing tag category name = system
I/CustomizationCIDLoader( 6330): Parsing tag category name = application
I/CustomizationCIDLoader( 6330): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6330): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6330): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6330): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6330): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6330): add string-array item, value = 42507
I/CustomizationCIDLoader( 6330): add string-array item, value = 21902
I/CustomizationCIDLoader( 6330): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6330): add string-array item, value = 23420
I/CustomizationCIDLoader( 6330): add string-array item, value = 22299
I/CustomizationCIDLoader( 6330): add string-array item, value = 24002
I/CustomizationCIDLoader( 6330): add string-array item, value = 23210
I/CustomizationCIDLoader( 6330): add string-array item, value = 23205
I/CustomizationCIDLoader( 6330): add string-array item, value = 23806
I/CustomizationCIDLoader( 6330): add string-array item, value = 23430
I/CustomizationCIDLoader( 6330): add string-array item, value = 23408
I/CustomizationCIDLoader( 6330): add string-array item, value = 27205
I/CustomizationCIDLoader( 6330): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6330): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6330):  Read CID file spent 0.101 (s)
D/CustomizationManager( 6330):  All configurations done spent 0.101 (s)
I/ActivityManager(  947): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6330 on display 0
D/PMS     (  947): acquireHCC(11a9713d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 947 1000 null
D/PMS     (  947): acquireHCC(37d3fd32): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 947 1000 null
W/asset   (  947): Copying FileAsset 0x55ba86cd80 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  947): acquireWL(2f40e439): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 947 1000 null
I/AnimationUtil(  947): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1580): [onPause]
I/FeedProviderManager( 1580): onPause
I/FeedHostManager( 1580): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@167e0a86
I/SocialFeedProvider( 1580): +onPause
I/SocialFeedProvider( 1580): -onPause
W/HtcSystemUPManager(  947): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  947): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6348 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  408): Explicit concurrent mark sweep GC freed 8680(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 271us total 25.091ms
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 248us total 16.555ms
D/StatusBarManagerService(  947): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  947): hiding MENU key
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 307us total 16.190ms
W/asset   ( 6348): Copying FileAsset 0xac3d4ee0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1580): [trimMemory] 20
D/PMS     (  947): acquireWL(2b9d87d7): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{10072}
V/AlarmManager(  947): sending alarm PendingIntent{38c088c4: PendingIntentRecord{1f3e23ad com.android.vending startService}}, i=null, t=0, cnt=1, w=1455027717536, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{12216e2: PendingIntentRecord{3348ca73 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455027720297, Int=536832000
V/AlarmManager(  947): sending alarm PendingIntent{e238b6a: PendingIntentRecord{1798d85b android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455027713751, Int=20000
V/CheckinService( 4442): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
D/PMS     (  947): acquireWL(b9f6d30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4442 10024 WorkSource{10024 com.google.android.gms}
E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  947):  packet count Tx=133 Rx=197
E/WifiTrafficPoller(  947): notifying of data activity 1
D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
E/WifiStateMachine(  947): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  947): handleMessage: E msg.what=131143
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:2127 rssi=-65 f=2412 sc=60 link=65 tx=0.2, 0.0, 0.0  rx=1.2 fiv=60000 [on:0 tx:0 rx:0 period:719] from screen [on:0 period:-966193012]
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:2127 rssi=-65 f=2412 sc=60 link=65 tx=0.2, 0.0, 0.0  rx=1.2 fiv=60000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-966193010]
D/PMS     (  947): releaseWL(2b9d87d7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  947): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.24 rxSuccessRate=1.17 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-65
D/PMS     (  947): acquireWL(384ebf2e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4442 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  947): WifiStateMachine CMD_START_SCAN with age=19809 interval=60000 maxinterval=300000
D/PMS     (  947): releaseWL(b9f6d30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  947): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  947): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  947): has c0:ff:d4:d3:aa:48 freq=2412 age=724 ?=true
E/WifiStateMachine(  947): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1324): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1324): wpa_supplicant_scan enter
D/wpa_supplicant( 1324): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1324): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1324): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1324): WPS:  * Request Type
D/wpa_supplicant( 1324): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1324): WPS:  * UUID-E
D/wpa_supplicant( 1324): WPS:  * Primary Device Type
D/wpa_supplicant( 1324): WPS:  * RF Bands (3)
D/wpa_supplicant( 1324): WPS:  * Association State
D/wpa_supplicant( 1324): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1324): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1324): WPS:  * Manufacturer
D/wpa_supplicant( 1324): WPS:  * Model Name
D/wpa_supplicant( 1324): WPS:  * Model Number
D/wpa_supplicant( 1324): WPS:  * Device Name
D/wpa_supplicant( 1324): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1324): P2P: * P2P IE header
D/wpa_supplicant( 1324): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1324): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1324): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1324): wlan0: Add radio work 'scan'@0x5567850680
D/wpa_supplicant( 1324): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1324): wlan0: Starting radio work 'scan'@0x5567850680 after 0.000037 second wait
D/wpa_supplicant( 1324): wlan0: nl80211: scan request
D/wpa_supplicant( 1324): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1324): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1324): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1324): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1324): wlan0: Own scan request started a scan in 0.000076 seconds
I/wpa_supplicant( 1324): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  947): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  947): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  947): [1,455,027,720,337 ms] noteScanstart no scan source
E/WifiStateMachine(  947): handleMessage: X
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/CheckinService( 4442): Checking schedule, now: 1455027720357 next: 1455027720297
I/CheckinService( 4442): active receiver: enabled
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4442, uid=10024, userID:0
,D/wpa_supplicant( 1324): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1324): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1324): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1324): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1324): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1324): wlan0: Scan completed in 0.044900 seconds
D/wpa_supplicant( 1324): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1324): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1324): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-65
I/wpa_supplicant( 1324): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-65
I/wpa_supplicant( 1324): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1324): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1324): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1324): BSS: last_scan_res_used=5/32,
D/wpa_supplicant( 1324): wlan0: Scan-only results received
D/wpa_supplicant( 1324): wlan0: Radio work 'scan'@0x5567850680 done in 0.045605 seconds
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  947): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  947): handleMessage: E msg.what=147461
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
,E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
D/WifiStateMachine(  947): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1324): wlan0: Control interface command 'LIST_DONGLES',
W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
,E/WifiStateMachine(  947): [1,455,027,720,410 ms] noteScanEnd no scan source
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1324): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,I/CheckinService( 4442): Preparing to send checkin request
E/WifiStateMachine(  947): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2921ad3f sup_state=COMPLETED debouncing=false
I/EventLogService( 4442): Accumulating logs since 1455027685502
E/WifiAutoJoinController (  947): NG7005g c0:ff:d4:d3:aa:4a rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  947): NG700 c0:ff:d4:d3:aa:48 rssi=-65 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  947): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
,E/WifiConfigStore(  947): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  947):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-65 freq=2412
E/WifiAutoJoinController (  947): 01ABC c2:ff:d4:d3:aa:48 rssi=-65 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  947): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  947): Gonzos 38:f8:89:11:e9:11 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  947): ageScanResultsOut delay 40000 size 5 now 1455027720413
E/WifiAutoJoinController (  947): newSupplicantResults size=5 known=1 true
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1324): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  947): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  947): ssid=NG700
E/WifiAutoJoinController (  947): id=0
E/WifiAutoJoinController (  947): mode=station,
E/WifiAutoJoinController (  947): pairwise_cipher=CCMP
E/WifiAutoJoinController (  947): group_cipher=CCMP
E/WifiAutoJoinController (  947): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  947): wpa_state=COMPLETED
E/WifiAutoJoinController (  947): ip_address=192.168.1.130
E/WifiAutoJoinController (  947): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  947): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  947): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  947): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  947): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-65,-127) num=(1,0)
E/WifiAutoJoinController (  947): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  947): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-65 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  947): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiAutoJoinController (  947): Done attemptAutoJoin status=0
E/WifiConfigStore(  947):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  947): handleMessage: X
,I/WebViewFactory( 6348): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/CheckinRequestBuilder( 4442): Checkin reason type: 11 attempt count: 1
,I/ActivityManager(  947): Cannot resolve ContentProvider=com.google.android.wearable.settings,
E/ActivityThread( 4442): Failed to find provider info for com.google.android.wearable.settings
,I/LibraryLoader( 6348): Time to load native libraries: 13 ms (timestamps 5478-5491),
,I/LibraryLoader( 6348): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6348): Binding Chromium to main looper Looper (main, tid 1) {3717b092}
,I/LibraryLoader( 6348): Expected native library version number "",actual native library version number ""
,I/chromium( 6348): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6348): Initializing chromium process, singleProcess=true,
,W/art     ( 6348): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6348): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6348): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6348): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6348): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6348): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6348): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6348): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6348): Local Branch: 
I/Adreno-EGL( 6348): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6348): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6348):                  d74aa161a12b9c6fc6332151
I/art     (  947): Explicit concurrent mark sweep GC freed 42932(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/25MB, paused 1.593ms total 164.186ms
W/System.err(  947): java.lang.Throwable: stack dump
W/System.err(  947): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  947): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  947): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  947): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  947): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ac1fc92:true
D/BluetoothAdapter( 6348): 519848926: getState(). Returning 12
D/Finsky  ( 5971): [597] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5971): [1] 5.onFinished: Installation state replication succeeded.
W/art     ( 6348): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6348): onDetachedFromWindow called when already detached. Ignoring
I/GLSUser ( 1961): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1961): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1961): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1961): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SystemWebViewEngine( 6348): CordovaWebView is running on device made by: HTC
W/art     ( 6348): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6348): Attempt to remove local handle scope entry from IRT, ignoring
W/CheckinRequestBuilder( 4442): awaiting user notification for token
D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
I/ActivityManager(  947): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6394 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/chromium( 6348): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/ResourcesManager( 6394): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6394): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6394): VM with version 2.1.0 has multidex support
I/MultiDex( 6394): install
I/MultiDex( 6394): VM has multidex support, MultiDex support library is disabled.
D/FindExtension( 6348): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
V/JNIHelp ( 6394): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 6394): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6394): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@51f128f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6394): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1961): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1961): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/InputMethodManager( 6348): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3f6b90af, mServedView=org.apache.cordova.engine.SystemWebView{1d3c1cbc VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@38c1b445
I/InputMethodManagerService(  947): Disable input method client, pid=1580
D/StatusBarManagerService(  947): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  947): Enable input method client, pid=6348
V/GmsCoreStatsServiceLauncher( 4442): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  947): Displayed com.test.thalitest/.MainActivity: +849ms
D/PMS     (  947): releaseWL(2f40e439): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/WearableService( 5130): callingUid 10024, callindPid: 5130
E/MDM     ( 1834): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
W/XT9_C   ( 1404): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1404): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1404): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1404): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6348): Cannot call determinedVisibility() - never saw a connection for the pid: 6348
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4442, uid=10024, userID:0
I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
D/LocationInitializer( 4442): Restart initialization of location
D/QSEECOMAPI: (  401): Loaded image: APP id = 8
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b32000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b32000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  493): got the req here! ret=0
D/DrmLibTime(  493): command id, time_cmd_id = 770
D/DrmLibTime(  493): time_getutcsec starts!
D/DrmLibTime(  493): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  493): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  493): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  493): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  493): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  493): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  493): QSEE Time Listener: Retrieved Android system time: 1455027721
D/DrmLibTime(  493): time_getutcsec returns 0, sec = 1455027721; nsec = 0
D/DrmLibTime(  493): time_getutcsec finished! 
D/DrmLibTime(  493): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  493): before calling ioctl to read the next time_cmd
E/QC-time-services(  431): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/JsMessageQueue( 6348): Set native->JS mode to OnlineEventsBridgeMode
D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xffb43d18
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab9b1cf0, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab9c5e38, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab93f9a8, idLength=0xf40736f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf407370e, maximum = 0xf407370f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf407377c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=2275826734
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab90bbb8
D/DrmWidevineDash(  401): message_length=1611, signature=0xab9c6c78, signature_length=0xf40736dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  947):  packet count Tx=133 Rx=197
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  947): notifying of data activity 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/jxcore_app_log( 6348): JniHelper::setJavaVM(0xab2688f8), pthread_self() = -1403522856
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
I/art     ( 6348): Background sticky concurrent mark sweep GC freed 25025(1708KB) AllocSpace objects, 3(48KB) LOS objects, 17% free, 3MB/4MB, paused 6.808ms total 39.696ms
I/chromium( 6348): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/cutils-trace( 6431): Error opening trace file: Permission denied (13)
I/dex2oat ( 6431): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6431): dex2oat: override thread count:4
I/dex2oat ( 6431): dex2oat took 58.068ms (threads: 4)
I/Adreno-EGL( 6394): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6394): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6394): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6394): Local Branch: 
I/Adreno-EGL( 6394): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6394): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6394):                  d74aa161a12b9c6fc6332151
I/Adreno-EGL( 6394): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6394): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6394): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6394): Local Branch: 
I/Adreno-EGL( 6394): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6394): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6394):                  d74aa161a12b9c6fc6332151
I/HtcModeClient( 3278): handler message = 4011
E/HtcModeClient( 3278): Check connection and retry 11 times.
I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
D/QSEECOMAPI: (  401): Loaded image: APP id = 9
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b32000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b32000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  493): got the req here! ret=0
D/DrmLibTime(  493): command id, time_cmd_id = 770
D/DrmLibTime(  493): time_getutcsec starts!
D/DrmLibTime(  493): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  493): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  493): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  493): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  493): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  493): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  493): QSEE Time Listener: Retrieved Android system time: 1455027721
D/DrmLibTime(  493): time_getutcsec returns 0, sec = 1455027721; nsec = 0
D/DrmLibTime(  493): time_getutcsec finished! 
D/DrmLibTime(  493): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  493): before calling ioctl to read the next time_cmd
E/QC-time-services(  431): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xffb43d18
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab90c330, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab9c5e38, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab93f9c8, idLength=0xf4c5c6f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4c5c70e, maximum = 0xf4c5c70f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4c5c77c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=533861930
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab95bf20
D/DrmWidevineDash(  401): message_length=1646, signature=0xab9c64b0, signature_length=0xf4c5c6dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
I/CheckinRequestBuilder( 4442): Classify the device as Phone.
D/libc    ( 4442): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4442): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4442): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4442): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4442): [NET] android_getaddrinfo_proxy+
D/libc    ( 4442): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4442): [NET] android_getaddrinfo_proxy-, success
D/PMS     (  947): releaseHCC(11a9713d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  947): releaseHCC(37d3fd32): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
D/libc    ( 4442): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4442): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4442): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4442): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4442): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4442): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4442): Sending checkin request (8411 bytes)
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  947):  packet count Tx=148 Rx=207
E/WifiTrafficPoller(  947): notifying of data activity 3
D/WIFI_ICON( 1221): WifiActivity: 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/jxcore-log( 6348): Initializing JXcore engine
W/jxcore-log( 6348): JXcore engine is ready
,W/jxcore-log( 6348): Starting JXcore engine
,W/jxcore-log( 6348): Platform android
W/jxcore-log( 6348): 
,W/jxcore-log( 6348): Process ARCH arm
W/jxcore-log( 6348): 
,E/WifiStateMachine(  947): handleMessage: E msg.what=131155
E/WifiStateMachine(  947): processMsg: ConnectedState
,E/WifiStateMachine(  947):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:2277] from screen [on:0 period:-966190729] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
,E/WifiStateMachine(  947):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-966190727] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947):  get link layer stats 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [15][0][0]
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiConfigStore(  947): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  947): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=7.62 txretriesrate=0.00 rxrate=6.09 userTriggerdPenalty0
E/WifiStateMachine(  947):  good link -> stuck count =0
E/WifiStateMachine(  947):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  947):  isHighRSSI       ---> score=65
E/WifiStateMachine(  947): handleMessage: X
D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -65, 3
,I/jxcore-log( 6348): JXcore Cordova bridge is ready!
I/jxcore-log( 6348): 
,W/jxcore-log( 6348): JXcore engine is started
,E/jxcore  ( 6348): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6348): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6348): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,W/PluginManager( 6348): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 50ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  947): acquireWL(220e9984): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 947 1000 null,
,W/HtcSystemUPManager(  947): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1580): [onResume]
I/FeedProviderManager( 1580): onResume
I/SocialFeedProvider( 1580): +onResume
,I/SocialFeedProvider( 1580): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1580): -onResume
,D/StatusBarManagerService(  947): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  947): hiding MENU key
,D/FindExtension( 1580): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1580): Defer allocateBuffers to drawing time,
,I/InputMethodManagerService(  947): Disable input method client, pid=6348
,D/StatusBarManagerService(  947): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  947): Enable input method client, pid=1580
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
W/IInputConnectionWrapper( 6348): reportFullscreenMode on inactive InputConnection
,I/CheckinRequestBuilder( 4442): Checkin reason type: 11 attempt count: 1,
I/ActivityManager(  947): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4442): Failed to find provider info for com.google.android.wearable.settings,
,D/PMS     (  947): releaseWL(220e9984): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  947): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  947): hiding MENU key
,I/GLSUser ( 1961): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1961): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1961): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1961): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4442): awaiting user notification for token
,D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,I/CheckinRequestBuilder( 4442): Classify the device as Phone.,
,I/CheckinTask( 4442): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4442): Checking schedule, now: 1455027723327 next: 1455564555320,
I/CheckinService( 4442): active receiver: disabled
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4442, uid=10024, userID:0
E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  947):  packet count Tx=150 Rx=211
,D/PMS     (  947): releaseWL(384ebf2e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  947): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6448 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/PhoneMonitor( 6448): Register our PhoneStateListener
,V/SetupWizard( 6448): Connected to Gservices successfully,
,D/ChimeraCfgMgr( 4442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4442): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
D/PhoneMonitor( 6448): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6448): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/GCM     ( 1961): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,W/OpenGLRenderer( 1580): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,E/WifiDataStallTracker(  947): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  947): updateDataStallInfo: mDataStallTxRxSum={txSum=132 rxSum=117} preTxRxSum={txSum=115 rxSum=103},
D/WifiDataStallTracker(  947): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  947): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  947):  packet count Tx=150 Rx=211
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  947): notifying of data activity 0
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  947):  packet count Tx=150 Rx=211
,E/WifiStateMachine(  947): handleMessage: E msg.what=131155,
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=7.6, 0.0, 0.0  rx=6.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-966187706] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=7.6, 0.0, 0.0  rx=6.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-966187705] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  947):  get link layer stats 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [2][0][0],
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  947): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  947): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.81 txretriesrate=0.00 rxrate=5.04 userTriggerdPenalty0
E/WifiStateMachine(  947):  good link -> stuck count =0
,E/WifiStateMachine(  947):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  947):  isHighRSSI       ---> score=61
E/WifiStateMachine(  947): handleMessage: X
D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -65, 3
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/Process (  947): killProcessQuiet, pid=5794
,I/ActivityManager(  947): Killing 5794:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 5794
,I/ActivityManager(  947): Killing 5761:com.google.android.talk/u0a112 (adj 15): empty #17,
D/Process (  947): killProcessQuiet, pid=5761
,D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  947):  packet count Tx=150 Rx=211
,I/ActivityManager(  947): Recipient 5761
,D/Process (  947): killProcessQuiet, pid=5836
I/ActivityManager(  947): Killing 5836:com.htc.calendar/u0a10 (adj 15): empty #18
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 5836
,I/HtcModeClient( 3278): handler message = 4011,
,E/HtcModeClient( 3278): Check connection and retry 12 times.,
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 3
E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=214
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  947): notifying of data activity 3
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=214
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  947): notifying of data activity 0
,E/WifiDataStallTracker(  947): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  947): updateDataStallInfo: mDataStallTxRxSum={txSum=134 rxSum=118} preTxRxSum={txSum=132 rxSum=117},
D/WifiDataStallTracker(  947): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  947): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  947): handleMessage: E msg.what=131155
E/WifiStateMachine(  947): processMsg: ConnectedState
,E/WifiStateMachine(  947):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=4.8, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-966184685] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=4.8, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-966184684] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947):  get link layer stats 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [3][0][0],
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  947): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  947): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=3.41 txretriesrate=0.00 rxrate=4.52 userTriggerdPenalty0,
E/WifiStateMachine(  947):  good link -> stuck count =0
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  947):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  947):  isHighRSSI       ---> score=61
E/WifiStateMachine(  947): handleMessage: X
D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -65, 3
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=217
E/WifiTrafficPoller(  947): notifying of data activity 1,
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=217
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
E/WifiTrafficPoller(  947): notifying of data activity 0
,D/AccTypeManager( 1750): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,W/SystemReader(  947): Cannot find grip_rejection_width, use default value instead
,I/Prism.ItemManager( 1580): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1580): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1580): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
D/AccTypeManager( 1750): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  947): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6474 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/PhoneApp( 1537): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,W/ResourcesManager(  947): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1750): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,E/ExternalAccountType( 1750): Unsupported attribute readOnly
W/ResourcesManager( 6474): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/PackageManager(  947): Unable to load service info ResolveInfo{6e094bd com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  947): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  947): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  947): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  947): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  947): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  947): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  947): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  947): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  947): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  947): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  947): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  947): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/GmsNetworkLocationProvi( 1834): DISABLE,
I/GCoreNlp( 1834): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  947): applying state to connected service
D/PMS     (  947): acquireWL(15a8eecc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(15a8eecc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  947): applying state to connected service
,D/PMS     (  947): acquireWL(2f780515): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(2f780515): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(ae4c02a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(ae4c02a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel_SMS( 6474): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6474): MmsConfig.loadMmsSettings
,I/ActivityManager(  947): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6504 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6474, uid=10112, userID:0
,I/art     (  947): Explicit concurrent mark sweep GC freed 29463(1664KB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 18MB/28MB, paused 1.441ms total 149.346ms
,W/Settings( 6474): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/HtcWrapAdjustableCursorFactory( 6504): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
I/Babel_Crash( 6474): startup - clean
,D/MessageFrequencyProvider( 6504): onCreate
,V/GetPrviateResource( 6504): GetPrviateResource
,V/GetPrviateResource( 6504): GetPrviateResource
D/MmsCustomizationProvider( 6504): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 6504): query uri: content://htc-mms-customization/mms-ua/ua_profile,
,D/MessageCustFlag( 6504): sense_version=6.0
,I/Babel_SMS( 6474): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 6474): MmsConfig.loadFromDatabase
,I/Babel   ( 6474): deleted: false for 0
,D/BTAccessoryUtil( 6504): createReceiver
D/BTAccessoryUtil( 6504): registerReceiver return intent = null
,D/MessageCustFlag( 6504): sku_id=118,
,D/HtcBuildUtils( 6504): getRATByHtcTelephonyCapability:1
,W/SystemReader( 6504): Cannot find qct_8960_interface, use default value instead
,E/Babel_SMS( 6474): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6474): MmsConfig.loadFromResources
,E/Babel_SMS( 6474): canonicalizeMccMnc: invalid mccmnc nullnull,
,I/Babel_SMS( 6474): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6474, uid=10112, userID:0
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6474, uid=10112, userID:0
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6474, uid=10112, userID:0
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6474, uid=10112, userID:0
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6474, uid=10112, userID:0
,D/PMS     (  947): acquireWL(16aba2fc): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6474 10112 null,
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc,
,I/[PluginManager]RegisterService( 1654): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1654): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4442): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4442): Null package name or gms related package.  Ignoreing.
,D/PMS     (  947): acquireWL(280b45e7): PARTIAL_WAKE_LOCK  Icing 0x1 4442 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(33c35594): PARTIAL_WAKE_LOCK  AsyncService 0x1 6040 10167 null
,D/PMS     (  947): releaseWL(33c35594): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,D/PMS     (  947): acquireWL(201d3832): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6040 10167 null,
,W/VideoCapabilities( 6474): Unsupported mime video/x-ms-wmv
,I/Icing   ( 4442): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  947): releaseWL(201d3832): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,W/Utils   ( 6474): could not parse size range '64x64-1920X1080'
I/UpdateIcingCorporaServi( 5888): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/AudioCapabilities( 6474): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6474): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6474): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6474): Unsupported mime video/x-ms-wmv,
,D/PMS     (  947): releaseWL(280b45e7): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/VideoCapabilities( 6474): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
,I/UpdateIcingCorporaServi( 5888): UpdateCorporaTask done [took 48 ms] updated apps [took 48 ms] 
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6474): onServiceConnected,
W/Babel   ( 6474): Attempted to change video mute state without an active call.
,D/PMS     (  947): releaseWL(16aba2fc): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6474): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6474): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6474): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6474): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6474): Installed default security provider GmsCore_OpenSSL
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=217
,E/WifiStateMachine(  947): handleMessage: E msg.what=131155,
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.4, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-966181662] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState,
E/WifiStateMachine(  947):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.4, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-966181661] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947):  get link layer stats 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
,E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  947): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
,E/WifiStateMachine(  947): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.70 txretriesrate=0.00 rxrate=3.26 userTriggerdPenalty0
E/WifiStateMachine(  947):  good link -> stuck count =0
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  947):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  947):  isHighRSSI       ---> score=61,
E/WifiStateMachine(  947): handleMessage: X
D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -65, 3
,I/HtcModeClient( 3278): handler message = 4011
,E/HtcModeClient( 3278): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3278): Don't start project servcice
D/HtcModeClient( 3278): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3278): connectState: CONNECTION_READY = false
D/SilentMusic( 3278): call stop
D/HtcModeClient( 3278): close connection
,W/HtcModeClient( 3278): leaveProjectMode: It does not enter ProjectMode,
W/CANMesgAgentLocalSocket( 3278): read the terminate packet, so break
,D/Process (  947): killProcessQuiet, pid=3278
I/ActivityManager(  947): Killing 3278:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 3278,
,I/Prism.ItemManager( 1580): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1580): loadItems() com.htc.launcher.pageview.WidgetManager@38052c73 +
I/Prism.WidgetManager( 1580): onLoadItems() +
,W/ResourcesManager( 1580): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1580): Copying FileAsset 0x55ba872470 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=217
,E/Prism.WidgetManager( 1580): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1580): onLoadItems() -
,I/Prism.ItemManager( 1580): loadItems() com.htc.launcher.pageview.WidgetManager@38052c73 -
,D/PhoneApp( 1537): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1537): -- N1 =0
,D/PhoneApp( 1537): -- N2 =0
,D/PhoneApp( 1537): -- N3 =0,
,D/Messaging( 6504): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6504): networkCode: 
D/MessageCustFlag( 6504): sku_id=118
D/MmsConfig( 6504): SIE smsPri: null,
D/MmsConfig( 6504): networkCode: 
,D/MmsConfig( 6504): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 6504): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 6504): ,
D/MmsAsyncWorkHandler( 6504): HM tk = 20001
D/ReportIndicatorCache( 6504): MSG_QUERY_REPORTS >>
D/SettingsManager( 6504): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@fceda63
,D/Messaging( 6504): mNeedToUpdateDate2 start
,D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 76
D/AccFlag ( 1537): sku_id=118,
,D/DraftCache( 6504): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6504): [DraftCache/1] refresh
,D/DraftCache( 6504): [DraftCache/161] rebuildCache,
D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/MmsSmsV2Provider( 1537):  slotId = -1000
D/MmsSmsV2Provider( 1537): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 6504): mccmnc> 
,D/MmsConfig( 6504): networkCode: 
,D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/MmsSmsV2Provider( 1537):  slotId = -1000
D/MmsSmsV2Provider( 1537): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/MmsSmsV2Provider( 1537):  slotId = -1000
D/MmsSmsV2Provider( 1537): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6504): mNeedToUpdateDate2: false
D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1537):  slotId = -1000
,D/MmsSmsV2Provider( 1537): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 6504): ViewCache CreatePreloadOnlyConversationList
,D/Messaging( 6504): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/Jerry   ( 1537): URI_DRAFT
,D/DraftCache( 6504): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 6504): [DraftCache/161] rebuildCache time: 18
D/MmsAsyncWorkHandler( 6504): 
D/MmsAsyncWorkHandler( 6504): HM tk = 20002
D/MessageCustFlag( 6504): sense_version=6.0
D/Jerry   ( 6504): start to preload cursor >>>>>>>
,D/PhoneStorageUtil( 6504): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6504): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6504): createReceiver
,D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1537): sku_id=118
,D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1537):  slotId = -1000
,D/TelephUtils( 1537): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
V/MmsProvider( 1537): Update uri=content://mms, match=0
V/MmsProvider( 1537): selection=st=129 AND m_type!=134
D/Messaging( 6504): Reset downloading state: 0
D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1537): sku_id=118
,D/Messaging( 6504): ViewCache CreatePreload,
D/Messaging( 6504): ViewCache CreatePreloadOnlyMultipleOpsList
,V/MmsSystemEventReceiver( 6504): TransactionService is going to be woken up.,
,D/Cust_MMSMS( 6504): _has_set_default_values_2=true,
V/TransactionService( 6504): 1-Creating TransactionService
,V/TransactionService( 6504): onStartCommand: 1
D/MmsSystemEventReceiver( 6504): unRegisterForConnectionStateChanges
V/TransactionService( 6504): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6504): Loading previous transactions.
,D/TelephUtils( 1537): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/AccFlag ( 1537): device_type: 1
,D/TransactionService( 6504): Force clearing mTransactionList,
D/TransactionService( 6504): Force set service start id to 1
V/TransactionService( 6504): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6504): unRegisterForConnectionStateChanges
D/TransactionService( 6504): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6504): Destroying TransactionService
D/MsgPreferenceUtils( 6504): def_index: 0
,V/TransactionService( 6504): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 6504): globalIndex = 1,
,D/MsgPreferenceUtils( 6504): phone state: true,
,D/MsgPreferenceUtils( 6504): sd state: false
D/MsgPreferenceUtils( 6504): vIndex = 0
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=217
,E/WifiDataStallTracker(  947): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  947): updateDataStallInfo: mDataStallTxRxSum={txSum=134 rxSum=118} preTxRxSum={txSum=134 rxSum=118}
,D/WifiDataStallTracker(  947): updateDataStallInfo: NONE
D/WifiDataStallTracker(  947): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  947): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6568 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  947): acquireWL(3572bade): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{10076}
V/AlarmManager(  947): sending alarm PendingIntent{1c7d64bf: PendingIntentRecord{d0478c com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455027733621, Int=60000
D/PMS     (  947): releaseWL(3572bade): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6568): SMSBackupAgentService started,
D/SMSBackup( 6568): Checking restore status
,D/SMSBackup( 6568): Restore complete,
D/SMSBackup( 6568): cancelCheckAlarm
,D/SMSBackup( 6568): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  947): killProcessQuiet, pid=5925
I/ActivityManager(  947): Killing 5925:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 5925
,D/PMS     (  947): acquireWL(12eba6ea): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{1000}
,D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
E/WifiStateMachine(  947): WiFiStateMachine SCAN ALARM,
V/AlarmManager(  947): sending alarm PendingIntent{e238b6a: PendingIntentRecord{1798d85b android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455027733751, Int=20000
E/WifiStateMachine(  947): handleMessage: E msg.what=131143
D/PMS     (  947): releaseWL(12eba6ea): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  947): processMsg: ConnectedState
,E/WifiStateMachine(  947):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:73 rssi=-65 f=2412 sc=60 link=65 tx=1.7, 0.0, 0.0  rx=3.3 list=2412 [on:0 tx:0 rx:0 period:2107] from screen [on:0 period:-966179536]
E/WifiStateMachine(  947): processMsg: L2ConnectedState
,E/WifiStateMachine(  947):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:73 rssi=-65 f=2412 sc=60 link=65 tx=1.7, 0.0, 0.0  rx=3.3 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-966179535]
E/WifiStateMachine(  947): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.70 rxSuccessRate=3.26 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-65
E/WifiStateMachine(  947): WifiStateMachine CMD_START_SCAN with age=33285 interval=60000 maxinterval=300000
E/WifiStateMachine(  947): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  947): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  947): has c0:ff:d4:d3:aa:48 freq=2412 age=2112 ?=true
E/WifiStateMachine(  947): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1324): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1324): wpa_supplicant_scan enter
D/wpa_supplicant( 1324): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1324): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1324): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1324): WPS:  * Request Type
D/wpa_supplicant( 1324): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1324): WPS:  * UUID-E
D/wpa_supplicant( 1324): WPS:  * Primary Device Type
D/wpa_supplicant( 1324): WPS:  * RF Bands (3)
D/wpa_supplicant( 1324): WPS:  * Association State
D/wpa_supplicant( 1324): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1324): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1324): WPS:  * Manufacturer
D/wpa_supplicant( 1324): WPS:  * Model Name
,D/wpa_supplicant( 1324): WPS:  * Model Number
D/wpa_supplicant( 1324): WPS:  * Device Name
D/wpa_supplicant( 1324): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1324): P2P: * P2P IE header
D/wpa_supplicant( 1324): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1324): P2P: * Listen Channel: Regulatory Class 81 Channel 1
,D/wpa_supplicant( 1324): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1324): wlan0: Add radio work 'scan'@0x5567850680
D/wpa_supplicant( 1324): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1324): wlan0: Starting radio work 'scan'@0x5567850680 after 0.000037 second wait
D/wpa_supplicant( 1324): wlan0: nl80211: scan request
D/wpa_supplicant( 1324): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1324): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1324): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1324): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1324): wlan0: Own scan request started a scan in 0.000084 seconds
,I/wpa_supplicant( 1324): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  947): [1,455,027,733,812 ms] noteScanstart no scan source
E/WifiStateMachine(  947): handleMessage: X
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  947): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  947): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1324): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1324): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1324): nl80211: Scan included frequencies: 2412
,D/wpa_supplicant( 1324): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1324): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1324): wlan0: Scan completed in 0.048742 seconds
D/wpa_supplicant( 1324): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1324): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1324): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-65
I/wpa_supplicant( 1324): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-65
I/wpa_supplicant( 1324): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1324): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1324): wlan0: BSS: Start scan result update 6
W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1324): BSS: last_scan_res_used=5/32
D/wpa_supplicant( 1324): wlan0: Scan-only results received
D/wpa_supplicant( 1324): wlan0: Radio work 'scan'@0x5567850680 done in 0.049686 seconds
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  947): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  947): handleMessage: E msg.what=147461
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
D/WifiStateMachine(  947): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1324): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  947): [1,455,027,733,867 ms] noteScanEnd no scan source
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1324): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  947): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2921ad3f sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  947): NG7005g c0:ff:d4:d3:aa:4a rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  947): NG700 c0:ff:d4:d3:aa:48 rssi=-65 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  947): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  947): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  947):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-65 freq=2412
E/WifiAutoJoinController (  947): 01ABC c2:ff:d4:d3:aa:48 rssi=-65 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  947): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  947): Gonzos 38:f8:89:11:e9:11 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  947): ageScanResultsOut delay 40000 size 5 now 1455027733869
E/WifiAutoJoinController (  947): newSupplicantResults size=5 known=1 true
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1324): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  947): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  947): ssid=NG700
E/WifiAutoJoinController (  947): id=0
E/WifiAutoJoinController (  947): mode=station
E/WifiAutoJoinController (  947): pairwise_cipher=CCMP
E/WifiAutoJoinController (  947): group_cipher=CCMP
E/WifiAutoJoinController (  947): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  947): wpa_state=COMPLETED
E/WifiAutoJoinController (  947): ip_address=192.168.1.130
E/WifiAutoJoinController (  947): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  947): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  947): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  947): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  947): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-65,-127) num=(1,0)
E/WifiAutoJoinController (  947): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  947): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-65 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  947): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  947): Done attemptAutoJoin status=0
E/WifiConfigStore(  947):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  947): handleMessage: X
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=217
,E/WifiStateMachine(  947): handleMessage: E msg.what=131155,
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.7, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:889] from screen [on:0 period:-966178642] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
,E/WifiStateMachine(  947):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.7, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-966178641] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947):  get link layer stats 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  947): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
,E/WifiStateMachine(  947): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.85 txretriesrate=0.00 rxrate=1.63 userTriggerdPenalty0
E/WifiStateMachine(  947):  good link -> stuck count =0
E/WifiStateMachine(  947):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  947):  isHighRSSI       ---> score=61
E/WifiStateMachine(  947): handleMessage: X
D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -65, 3
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=217
,I/ActivityManager(  947): Killing 6217:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=6217
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 6217
,D/Process (  947): killProcessQuiet, pid=6243,
I/ActivityManager(  947): Killing 6243:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=218,
E/WifiTrafficPoller(  947): notifying of data activity 1
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  947): Recipient 6243,
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=218
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  947): notifying of data activity 0
,E/WifiStateMachine(  947): handleMessage: E msg.what=131155,
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-966175621] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-966175620] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947):  get link layer stats 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  947): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  947): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.43 txretriesrate=0.00 rxrate=1.32 userTriggerdPenalty0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  947):  good link -> stuck count =0
E/WifiStateMachine(  947):  badRSSI count0 lowRSSI count0 --> score 56
,E/WifiStateMachine(  947):  isHighRSSI       ---> score=61
E/WifiStateMachine(  947): handleMessage: X
D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -65, 3
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=219
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  947): notifying of data activity 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  947): Going to sleep due to screen timeout (uid 1000)...,
I/SensorManager(  947): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@30c6c6f6
,D/ActivityManager(  947): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{1e2d8ddb #7 A=.Prism U=0 sz=1}
,W/PMS     (  947): mWirelessDisplayManager is null
W/SensorService(  947): Following SensorService logs are not warning, just make sure they are printed,
,W/PMS     (  947): mWirelessDisplayManager is still null
W/SensorService(  947): disable: get sensor name = Accelerometer Sensor
W/SensorService(  947): pid=947, uid=1000
I/PMS     (  947): Sleeping (uid 1000)...
W/SensorService(  947): Active sensors: size = 4
D/XAN-DPS (  947): prepareColorFade 1
W/SensorService(  947): Accelerometer Sensor (handle=0x00000000, connections=1)
,W/PMN     (  947): goingToSleep
W/SensorService(  947): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  947): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  947): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  947): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@30c6c6f6, eanble = 0, strlen(mName) = 91
W/SensorService(  947): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  947): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3ccdd3dc
W/SensorService(  947): Listener[1] = com.htc.smartdim.sensor_eye@14ce7951
W/SensorService(  947): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  947): acquireWL(d005078): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 947 1000 null
,W/PMN     (  947): goingToSleep done
I/FeedHostManager( 1580): [onPause]
I/FeedProviderManager( 1580): onPause
I/FeedHostManager( 1580): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@167e0a86
I/SocialFeedProvider( 1580): +onPause
I/SocialFeedProvider( 1580): -onPause
,I/ActivityManager(  947): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6590 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/AlarmManager(  947): ACTION_SCREEN_ON
,I/AlarmManager(  947): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  947): [AlarmQueuing] done recovering
I/AlarmManager(  947): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  947): [AlarmQueuing] done EPS screen off alarm recovering
,W/HtcSystemUPManager(  947): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,E/WifiDataStallTracker(  947): DATA_MONITOR_POLL true Token 1
D/PMS     (  947): releaseWL(d005078): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/Adreno-EGL(  947): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  947): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  947): Build Date: 03/09/15 Mon
I/Adreno-EGL(  947): Local Branch: 
I/Adreno-EGL(  947): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  947): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  947):                  d74aa161a12b9c6fc6332151
,E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL true Token 11
,E/WifiTrafficPoller(  947):  packet count Tx=152 Rx=219
E/WifiTrafficPoller(  947): notifying of data activity 0
D/WIFI_ICON( 1221): WifiActivity: 0
D/WifiDataStallTracker(  947): updateDataStallInfo: mDataStallTxRxSum={txSum=134 rxSum=118} preTxRxSum={txSum=134 rxSum=118}
,D/WifiDataStallTracker(  947): updateDataStallInfo: NONE
D/WifiDataStallTracker(  947): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,E/WifiDataStallTracker(  947): ENABLE_DATA_MONITOR_POLL true Token 1
,E/WifiStateMachine(  947): handleMessage: E msg.what=131167
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
,E/WifiStateMachine(  947):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  947): processMsg: DefaultState
D/WifiDataStallTracker(  947): updateDataStallInfo: mDataStallTxRxSum={txSum=134 rxSum=118} preTxRxSum={txSum=134 rxSum=118}
D/WifiDataStallTracker(  947): updateDataStallInfo: NONE
D/WifiDataStallTracker(  947): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  947):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  947):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
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
E/WifiStateMachine(  947): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
D/WifiStateMachine(  947): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  947): handleScreenStateChanged Exit: true
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131154
E/WifiStateMachine(  947): processMsg: ConnectedState
V/SRS_Proc(  401): ParamSet string: screen_state=on
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  947): handleMessage: E msg.what=155650
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
D/WifiController(  947): handleMessage: X
E/WifiStateMachine(  947):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,D/NetworkPolicy(  947): updateScreenOn: false
V/NetworkPolicy(  947): updateIfacesLocked()
,I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  947): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131127,
,E/WifiStateMachine(  947): processMsg: ConnectedState
D/NetworkManagementService(  947): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  947):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
,E/WifiStateMachine(  947):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131129
E/WifiStateMachine(  947): processMsg: ConnectedState
,E/WifiStateMachine(  947):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1324): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1324): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  947): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=35 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  947): handleMessage: X
,D/GpsLocationProvider(  947): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/ResourcesManager( 6590): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false),
,I/CalendarProvider2( 6590): Created com.android.providers.calendar.CalendarAlarmManager@d68561d(com.htc.providers.calendar.HtcCalendarProvider@3717b092)
,D/PMS     (  947): acquireWL(8b1978e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(159efbaf): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(8b1978e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 6590): wait start:true
,D/PMS     (  947): releaseWL(159efbaf): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/AlarmManager(  947): ACTION_SCREEN_OFF
,I/AlarmManager(  947): [AlarmQueuing] screen off now: 
I/AlarmManager(  947): [AlarmQueuing] data connection: true
I/AlarmManager(  947): [AlarmQueuing] wifi connection: true
,D/XAN-DPS (  947): prepareColorFade done
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  947): stopDataStallAlarm 
E/WifiDataStallTracker(  947): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  947): handleMessage: E msg.what=131167
D/XAN-DPS (  947): setBrightness to 0
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  947):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1324): SET_SCREEN_ON:Off
I/wpa_supplicant( 1324): htc_wext_set_keepalive +
I/wpa_supplicant( 1324): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1324): getPrivFuncNum +	
I/wpa_supplicant( 1324): getPrivFuncNum -, cmd = 0x8bf6
D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
I/wpa_supplicant( 1324): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1324): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1324): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1324): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  947): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
V/SRS_Proc(  401): ParamSet string: screen_state=off
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  947): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  947): handleScreenStateChanged Exit: false
E/WifiStateMachine(  947): handleMessage: X
,E/WifiStateMachine(  947): handleMessage: E msg.what=131154
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
D/WifiController(  947): handleMessage: E msg.what=155651
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
D/NetworkPolicy(  947): updateScreenOn: false
E/WifiStateMachine(  947): handleMessage: X
V/NetworkPolicy(  947): updateIfacesLocked()
D/WifiController(  947): handleMessage: X
,D/NetworkManagementService(  947): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/SensorManager(  947): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@3ccdd3dc
W/SensorService(  947): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  947): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  947): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  947): Display changed displayId=0
D/DotMatrix( 1332): [EventService]  onDisplayChanged: 0
W/SensorService(  947): pid=947, uid=1000
,W/SensorService(  947): Active sensors: size = 3
W/SensorService(  947): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  947): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  947): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  947): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@3ccdd3dc, eanble = 0, strlen(mName) = 67
W/SensorService(  947): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  947): Listener[0] = com.htc.smartdim.sensor_eye@14ce7951
W/SensorService(  947): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1332): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/CalendarProvider2( 6590): wait end:false
,I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@288990a3, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  947): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  947): enable: get sensor name = hTC Gesture Motion HIDI
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,W/SensorService(  947): pid=1221, uid=10041
W/SensorService(  947): Active sensors: size = 4
W/SensorService(  947): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  947): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  947): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  947): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  947): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@288990a3, eanble = 1, strlen(mName) = 57
W/SensorService(  947): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  947): Listener[0] = com.htc.smartdim.sensor_eye@14ce7951
W/SensorService(  947): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@288990a3
W/SensorService(  947): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  947): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6622 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
D/GpsLocationProvider(  947): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1332): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1537): start background delete task...,
I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1537): size: 0 , 0
,D/ContactMessageStore( 1537): Background delete complete
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145),
,I/RemoteViews( 1221): apply : com.htc.updater 0 11 1 36
,W/ContextImpl( 6622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  947): acquireWL(1aecb1a7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): releaseWL(1aecb1a7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(2312b654): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(2312b654): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 6622): MY_DEBUG = false,
W/ContextImpl( 6622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6622): isEpsOn(), nState = 0
,D/PMS     (  947): acquireWL(15f66f2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6622 1000 null
,D/PMS     (  947): releaseWL(15f66f2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  947): Init customizeScreenOffDelayClass error
,W/ContextImpl( 6622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 6622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 6622): isEpsOn(), nState = 0,
,D/SmartSyncUtils( 6622): isEpsOn(), nState = 0
,W/ContextImpl( 6622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
I/SensorManager(  947): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@14ce7951
W/SensorService(  947): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  947): disable: get sensor name = Accelerometer Sensor,
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2,
D/PMS     (  947): Setting HAL interactive mode to false
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  947): Setting HAL interactive mode to false done
D/SurfaceControl(  947): Excessive delay in setPowerMode(): 301ms
D/PMS     (  947): Setting HAL auto-suspend mode to true
W/HtcSystemUPManager(  947): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  947): Setting HAL auto-suspend mode done
I/InputMethodManagerService(  947): screenObserver, isScreenOn=false
D/StatusBarManagerService(  947): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  947): Disable input method client, pid=1580
D/HABCtrl (  947): TPE algorithm. remove timeout.
D/PMS     (  947): OOBE c monitor 11
,W/SensorService(  947): pid=947, uid=1000
W/SensorService(  947): Active sensors: size = 3
W/SensorService(  947): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  947): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  947): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  947): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@14ce7951, eanble = 0, strlen(mName) = 36
W/SensorService(  947): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  947): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@288990a3
W/SensorService(  947): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  947): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  947): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  947): pid=947, uid=1000
W/SensorService(  947): Active sensors: size = 2
W/SensorService(  947): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  947): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  947): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@14ce7951, eanble = 0, strlen(mName) = 36
W/SensorService(  947): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  947): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@288990a3
W/SensorService(  947): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  947): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@14ce7951
D/PMS     (  947): acquireWL(333ba8f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(333ba8f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NfcService( 1556): ScreenObserver: OFF
D/NfcService( 1556): applyRouting - 0
,D/PMS     (  947): acquireWL(2779003e): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1556 1027 null
D/NfcService( 1556): applyRouting -2
D/NfcService( 1556): applyRouting
,D/NfcService( 1556): Ignore this applyRouting...
D/PMS     (  947): releaseWL(2779003e): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ActivityManager(  947): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6654 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/InputManager(  947): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
E/ActivityThread(  947): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@2a8685b6 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  947): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@2a8685b6 that was originally registered here. Are you missing a call to unregisterReceiver()?
,E/ActivityThread(  947): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  947): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  947): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  947): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  947): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  947): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  947): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  947): 	at android.app.Service.onStartCommand(Service.java:458)
,E/ActivityThread(  947): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  947): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  947): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470),
E/ActivityThread(  947): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  947): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  947): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  947): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  947): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  947): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  947): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
,E/ActivityThread(  947): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  947): plugged=true pluggin=true
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  947): Checking...
,D/UsbnetService(  947): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/PowerUsageList:PowerUsageHelper( 6622): PowerProfile::POWER_SCREEN_FULL = 154.8,
,I/ClockController( 1221): stop clock update:screen off,
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
D/PowerUsageList:BatterySipperExt( 6622): gen(), null == sipper.uidObj, userId = 0
,D/SmartSyncUtils( 6622): getMobilePolicyEnabled, result = true
I/ActivityManager(  947): Killing 6013:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  947): killProcessQuiet, pid=6013
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/WifiService(  947): New client listening to asynchronous messages
E/WifiTrafficPoller(  947): ADD_CLIENT: 7
,I/ActivityManager(  947): Recipient 6013
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,D/PowerUsageList:PowerUsageHelper( 6622): MY_DEBUG = false,
,D/Process (  947): killProcessQuiet, pid=6273
I/ActivityManager(  947): Killing 6273:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL false Token 13 num clients 7
,I/ActivityManager(  947): Recipient 6273
,D/PMS     (  947): releaseWL(b444ba1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/CalendarProvider2( 6590): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6590): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar),
,I/ActivityManager(  947): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6678 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
D/Process (  947): killProcessQuiet, pid=5388
I/ActivityManager(  947): Killing 5388:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 5388
,W/ResourcesManager( 6678): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6678): onCreate
,D/ProviderChangeReceiver( 6678): ---------------------------------------------------
D/ProviderChangeReceiver( 6678): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/ActivityManager(  947): Killing 5443:com.htc.mediamanager/u0a28 (adj 15): empty #17
,D/Process (  947): killProcessQuiet, pid=5443
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6678): start to updateAlertNotification!
,I/ActivityManager(  947): Recipient 5443
,D/HtcAlertService( 6678): No fired or scheduled alerts
D/HtcAlertUtils( 6678): -- cancelReminderNotification --
,D/HtcAlertUtils( 6678): broadcastExistReminder!
,D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  947): handleMessage: E msg.what=131155
E/WifiStateMachine(  947): processMsg: ConnectedState
,E/WifiStateMachine(  947):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-966172601] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-966172599] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947): handleMessage: X
,E/WifiStateMachine(  947): handleMessage: E msg.what=131155,
E/WifiStateMachine(  947): processMsg: ConnectedState
,E/WifiStateMachine(  947):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:870] from screen [on:0 period:-966171728] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-966171726] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  947): handleMessage: X
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  947): DATA_MONITOR_POLL false Token 3,
,E/WifiDataStallTracker(  947): DATA_MONITOR_POLL false Token 3,
,D/ContactMessageStore( 1537): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1537): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  947): killProcessQuiet, pid=5611
I/ActivityManager(  947): Killing 5611:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 5611
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  947): acquireWL(1a8c2e9f): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{10024}
,V/AlarmManager(  947): sending alarm PendingIntent{31de7bec: PendingIntentRecord{a04dbb5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143998, Int=0
,D/PMS     (  947): releaseWL(1a8c2e9f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  947): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  947): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  947): acquireWL(2200e24a): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 947 1000 null
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  947): [NET] android_getaddrinfofornet-, err=8
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  947): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  947): [NET] android_getaddrinfo_proxy+
D/libc    (  947): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
,D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    (  947): [NET] android_getaddrinfo_proxy-, success
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  947): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  947): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  947): acquireWL(2272d916): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 947 1000 null
D/GpsLocationProvider(  947): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  947): releaseWL(2200e24a): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  947):  [handleDownloadXtraData]inject done.
D/GpsLocationProvider(  947): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  947): releaseWL(2272d916): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1537): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1537): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  947): acquireWL(260f5297): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
,D/UsbnetService(  947): BroadcastReceiver::onReceive+
I/BatteryService(  947): n_update end
D/UsbnetService(  947): onReceive BATTERY_CHANGED
,D/PMS     (  947): releaseWL(260f5297): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive-
,D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  947): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): processMsg: StaEnabledState
D/HtcPowerSaver(  947): updateBatteryInfo
D/WifiController(  947): processMsg: DefaultState
D/PMS     (  947): runPSCheck
D/WifiController(  947): handleMessage: X
D/HtcPowerSaver(  947): Checking...
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  947): >> updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1537): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  947): acquireWL(177a5c84): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000}
V/AlarmManager(  947): sending alarm PendingIntent{20cfb878: PendingIntentRecord{27764b51 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=155005, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{1961cc6d: PendingIntentRecord{243b70a2 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455027790697, Int=0,
V/AlarmManager(  947): sending alarm PendingIntent{8ec8133: PendingIntentRecord{3c82bcf0 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=199791, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{2adbc269: PendingIntentRecord{3b03f4ee com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190042, Int=0
D/PMS     (  947): acquireWL(3363fd8f): PARTIAL_WAKE_LOCK  *backup* 0x1 947 1000 null
,D/PMS     (  947): acquireWL(46eb81c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  947): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  947): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  947): releaseWL(3363fd8f): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  947): releaseWL(177a5c84): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  947): acquireWL(20e51c25): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): releaseWL(46eb81c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1961): Explicit concurrent mark sweep GC freed 12842(688KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 1.253ms total 50.746ms,
,D/PMS     (  947): releaseWL(20e51c25): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(c540f87): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): releaseWL(c540f87): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): acquireWL(25efeeb4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(25efeeb4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  947): acquireWL(151baadd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(2ec54652): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(12f74220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(151baadd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1961): Vacuum at: now=1455027825162 tag=VacuumService
,I/GoogleURLConnFactory( 1961): Using platform SSLCertificateSocketFactory,
D/PMS     (  947): releaseWL(2ec54652): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(314d759e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1961): No account for auth token provided,
,D/PMS     (  947): releaseWL(314d759e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): acquireWL(2e05687f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(2e05687f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1961): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1961): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1961): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1961): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1961): [NET] android_getaddrinfo_proxy+
D/libc    ( 1961): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1961): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1961): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1961): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1961): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1961): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1961): No account for auth token provided,
,W/Uploader( 1961): No account for auth token provided,
,W/Uploader( 1961): No account for auth token provided,
,W/Uploader( 1961):  no longer exists, so no auth token.,
,W/Uploader( 1961): No account for auth token provided,
,I/art     (  947): Explicit concurrent mark sweep GC freed 36484(1999KB) AllocSpace objects, 4(1064KB) LOS objects, 33% free, 18MB/28MB, paused 2.060ms total 195.379ms
,I/GLSUser ( 1961): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1961): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1961): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1961): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1221): reapply : com.google.android.gms 4 40
D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/Uploader( 1961): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1961): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1961): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1961): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1961): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1961): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1961): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1961): No account for auth token provided
,D/PMS     (  947): releaseWL(12f74220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(1bef7350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(1bef7350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): acquireWL(19f6a949): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(19f6a949): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1654): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@264a914c
,D/Process (  947): killProcessQuiet, pid=6348
,I/ActivityManager(  947): Killing 6348:com.test.thalitest/u0a366 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 6348
,E/InputEventReceiver( 1404): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{11182a7 uid 10366 pid 6348} (c)'
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  947): acquireWL(2d10824e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  947): n_update end
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/PMS     (  947): releaseWL(2d10824e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
,D/PMS     (  947): runPSCheck
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState,
D/WifiController(  947): handleMessage: X
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  947): acquireWL(e0f6f6f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  947): n_update end
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  947): releaseWL(e0f6f6f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): battery changed pluggedType: 2
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/PMS     (  947): runPSCheck
D/WifiController(  947): handleMessage: E msg.what=155652
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): processMsg: DeviceActiveState
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1324): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
,D/wpa_supplicant( 1324): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
,D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
,D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 4 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  947): acquireWL(f60747c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000},
V/AlarmManager(  947): sending alarm PendingIntent{20cfb878: PendingIntentRecord{27764b51 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=215005, Int=0
,V/AlarmManager(  947): sending alarm PendingIntent{16f6755a: PendingIntentRecord{3c4d938b com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1455027967327, Int=0
,D/PMS     (  947): releaseWL(f60747c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  947): acquireWL(387e5c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(387e5c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): >> updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  947): battery changed pluggedType: 2
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState,
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1961): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1961): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1961): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1961): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1961): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1961): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1961): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1961): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1961): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1961): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1961): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5971): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5971): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5971): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5971): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5971): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5971): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5971): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1332): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1332): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 5 40
,W/System  ( 5971): Ignoring header User-Agent because its value was null.
,D/libc    ( 5971): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5971): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5971): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5971): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5971): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5971): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5971): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  947): acquireWL(3406e90a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(3406e90a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  947): updateBatteryInfo,
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  947): plugged=true pluggin=true
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  947): runPSCheck
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): handleMessage: X
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  947): acquireWL(9ae757b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  947): releaseWL(9ae757b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  947): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
,D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: E msg.what=155652
D/PMS     (  947): runPSCheck,
D/WifiController(  947): processMsg: DeviceActiveState
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): processMsg: StaEnabledState
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): battery changed pluggedType: 2,
D/WifiController(  947): handleMessage: X
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): << updateStatus
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  947): acquireWL(1f35af98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(1f35af98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PMS     (  947): runPSCheck
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  947): >> updateStatus
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  947): << updateStatus
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: E msg.what=155652
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  947): acquireWL(cec43f1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
D/UsbnetService(  947): BroadcastReceiver::onReceive+
I/BatteryService(  947): n_update end
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PMS     (  947): releaseWL(cec43f1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  947): plugged=true pluggin=true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  947): runPSCheck
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  947): >> updateStatus
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1537): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1537): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1537): sku_id=118
D/ContactMessageStore( 1537): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1537): start background delete task...
,D/ContactMessageStore( 1537): size: 0 , 0
,D/ContactMessageStore( 1537): Background delete complete
,D/PMS     (  947): acquireWL(3ab28bd6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(3ab28bd6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  947): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  947): runPSCheck
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): >> updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  947): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  947): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  947): << updateStatus
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(2224ee57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(2224ee57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  947): updateBatteryInfo
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  947): plugged=true pluggin=true
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): onReceive BATTERY_CHANGED
,I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  947): battery changed pluggedType: 2
,D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(38a22d44): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(38a22d44): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  947): updateBatteryInfo
D/PMS     (  947): runPSCheck
D/HtcPowerSaver(  947): Checking...
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  947): >> updateStatus
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
,D/WifiController(  947): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(d702e2d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(d702e2d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HtcPowerSaver(  947): updateBatteryInfo
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
,D/PMS     (  947): runPSCheck
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): Checking...,
,D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): >> updateStatus
,D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
,D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  947): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: X
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(aa38f62): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(aa38f62): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  947): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: X
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(252018f3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000}
V/AlarmManager(  947): sending alarm PendingIntent{20cfb878: PendingIntentRecord{27764b51 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=395004, Int=0
,I/bt-btm  ( 3129): Received oneshot timer event complete,
,V/AlarmManager(  947): sending alarm PendingIntent{1536d9b0: PendingIntentRecord{cce8029 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=942069, Int=0
I/bt-btm  ( 3129): btm_ble_timeout
D/PMS     (  947): acquireWL(27af3fae): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3129 1002 null
I/bt-btm  ( 3129): btm_gen_resolvable_private_addr
,D/PMS     (  947): releaseWL(252018f3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/bt-btm  ( 3129): btm_ble_rand_enc_complete
I/bt-btm  ( 3129): btm_gen_resolve_paddr_low
D/bt-smp  ( 3129): smp_encrypt_data
W/bt-smp  ( 3129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 3129): Plain text(LSB ~ MSB) = cc 2c 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3129): Encrypted text(LSB ~ MSB) = d6 80 75 30 b1 0e cc ed a6 eb 95 bd bc 2d 8a 30 
I/bt-btm  ( 3129): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3129): Stopping oneshot timer
D/bt-btm  ( 3129): Starting oneshot timer type:103 timeout:900s
D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  947): releaseWL(27af3fae): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  947): acquireWL(3999514f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(3999514f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  947): updateBatteryInfo,
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
,D/WifiController(  947): processMsg: DefaultState,
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: X
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(2f27e0dc): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{10024}
,V/AlarmManager(  947): sending alarm PendingIntent{a5f5e5: PendingIntentRecord{2bb3a8ba com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937762, Int=0
,D/PMS     (  947): acquireWL(12c3b36b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(12c3b36b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  947): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6715 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  947): sending alarm PendingIntent{dc02ec8: PendingIntentRecord{1fc50b61 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1455028284431, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{1568bca6: PendingIntentRecord{157716e7 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805678, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{3e639686: PendingIntentRecord{2d61ac0a com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455028591371, Int=0
,W/ContextImpl( 6622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  947): releaseWL(2f27e0dc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6622): MY_DEBUG = false,
,D/PowerUsageService( 6622): repeat time = 1455029491436,
,I/PowerUsageList:PowerUsageHelper( 6622): PowerProfile::POWER_SCREEN_FULL = 154.8
,E/cutils-trace( 6738): Error opening trace file: Permission denied (13),
D/PowerUsageList:BatterySipperExt( 6622): gen(), null == sipper.uidObj, userId = 0,
,I/dex2oat ( 6738): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6738): dex2oat: override thread count:4
,D/PMS     (  947): acquireWL(2565fc9d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1961 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1961): Message class com.google.f.a.a.i
,D/PMS     (  947): releaseWL(2565fc9d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/dex2oat ( 6738): dex2oat took 568.550ms (threads: 4),
,I/PushClient( 6715): ApplicationMonitor {38a3788c}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6715): ApplicationMonitor {38a3788c}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6715): ApplicationMonitor {38a3788c}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6715): ApplicationMonitor {38a3788c}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6715): ApplicationMonitor {38a3788c}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6715): ApplicationMonitor {38a3788c}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6715): ApplicationMonitor {38a3788c}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6715): ApplicationMonitor {38a3788c}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6715): ApplicationMonitor {38a3788c}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6715): PnsModel {29cab9bf}: update(): Update registration caused by: alarm,
,I/PushClient( 6715): PnsConfigModel {19e96242}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6715): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6715): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6715): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6715): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  947): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6747 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6747): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6747 dbg=false s=true,
,I/DeviceManagement( 6747): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6747): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6747): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6747): WorkflowService: Starting workflow service
,I/DeviceManagement( 6747): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1efc43de] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6747): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6747): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6747): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6747): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6747): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6747): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6747): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6747): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1efc43de]
,I/DeviceManagement( 6747): WorkflowService: Stopping workflow service
,D/Process (  947): killProcessQuiet, pid=6448
I/ActivityManager(  947): Killing 6448:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6715): PnsModel {29cab9bf}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  947): Recipient 6448,
,D/Process (  947): killProcessQuiet, pid=6394
I/ActivityManager(  947): Killing 6394:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 6394
,D/PMS     (  947): acquireWL(2cd68ed1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000}
V/AlarmManager(  947): sending alarm PendingIntent{20cfb878: PendingIntentRecord{27764b51 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=995005, Int=0
,V/AlarmManager(  947): sending alarm PendingIntent{3d84ad36: PendingIntentRecord{c086437 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455028639058, Int=0
,D/SmartSyncUtils( 6622): isEpsOn(), nState = 0,
,D/PMS     (  947): acquireWL(27a59da4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6622 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6622): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6622): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/PMS     (  947): releaseWL(2cd68ed1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 6622): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6622): SettingOnTime = 1455084000000, randomSettingOnTime = 1455082295000
D/SmartSyncScreenOnOffTimeReceiver( 6622): SettingOffTime = 1455062400000, randomSettingOffTime = 1455065013000
D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 6622): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6622): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6622): bNightModeTurnOffOnce = false
,D/PMS     (  947): releaseWL(27a59da4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  947): acquireWL(2864470d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
,I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(2864470d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  947): updateBatteryInfo
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PMS     (  947): runPSCheck
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  947): Checking...
,I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState,
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(16666c2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(16666c2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  947): updateBatteryInfo
D/PMS     (  947): runPSCheck
D/HtcPowerSaver(  947): Checking...
I/HtcPowerSaver(  947): >> updateStatus
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/UsbnetService(  947): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  947): << updateStatus
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  947): plugged=true pluggin=true
,D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/HeadsetStateMachine( 3129): Disconnected process message: 10, size: 0
D/PMS     (  947): acquireWL(7f50cd3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  947): n_update end
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  947): releaseWL(7f50cd3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1332): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1332): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1),
,I/HtcPowerSaver(  947): << updateStatus,
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  947): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
