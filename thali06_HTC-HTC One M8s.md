#### Test 5761781115ba656_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  953): handleMessage: E msg.what=131155
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1937743483] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1937743482] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1414): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1414): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.27 txretriesrate=0.00 rxrate=2.45 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -59, 3
E/WifiStateMachine(  953): handleMessage: X
--------- beginning of system
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
E/WifiStateMachine(  953): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  953): handleMessage: E msg.what=131143
E/WifiStateMachine(  953): processMsg: ConnectedState
D/PMS     (  953): acquireWL(39c27fc5): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1000}
V/AlarmManager(  953): sending alarm PendingIntent{8fab9b8: PendingIntentRecord{13a75391 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454056170100, Int=20000
D/PMS     (  953): releaseWL(39c27fc5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  953):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:87 rssi=-59 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.5 list=2412 [on:0 tx:0 rx:0 period:219] from screen [on:0 period:-1937743240]
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):4 dur:87 rssi=-59 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.5 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1937743239]
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.27 rxSuccessRate=2.45 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-59
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN with age=32566 interval=60000 maxinterval=300000
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  953): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  953): has c0:ff:d4:d3:aa:48 freq=2412 age=228 ?=true
E/WifiStateMachine(  953): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1414): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1414): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1414): wpa_supplicant_scan enter
D/wpa_supplicant( 1414): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1414): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1414): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1414): WPS:  * Request Type
D/wpa_supplicant( 1414): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1414): WPS:  * UUID-E
D/wpa_supplicant( 1414): WPS:  * Primary Device Type
D/wpa_supplicant( 1414): WPS:  * RF Bands (3)
D/wpa_supplicant( 1414): WPS:  * Association State
D/wpa_supplicant( 1414): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1414): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1414): WPS:  * Manufacturer
D/wpa_supplicant( 1414): WPS:  * Model Name
D/wpa_supplicant( 1414): WPS:  * Model Number
D/wpa_supplicant( 1414): WPS:  * Device Name
D/wpa_supplicant( 1414): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1414): P2P: * P2P IE header
D/wpa_supplicant( 1414): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1414): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1414): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1414): wlan0: Add radio work 'scan'@0x5577205680
D/wpa_supplicant( 1414): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1414): wlan0: Starting radio work 'scan'@0x5577205680 after 0.000041 second wait
D/wpa_supplicant( 1414): wlan0: nl80211: scan request
D/wpa_supplicant( 1414): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1414): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1414): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1414): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1414): wlan0: Own scan request started a scan in 0.000082 seconds
I/wpa_supplicant( 1414): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  953): [1,454,056,170,107 ms] noteScanstart no scan source
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  953): handleMessage: X
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  953): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  953): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=241 rxSum=197} preTxRxSum={txSum=241 rxSum=197}
D/WifiDataStallTracker(  953): updateDataStallInfo: NONE
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/wpa_supplicant( 1414): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1414): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1414): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1414): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1414): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1414): wlan0: Scan completed in 0.074218 seconds
D/wpa_supplicant( 1414): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1414): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1414): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1414): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1414): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-56
I/wpa_supplicant( 1414): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1414): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1414): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1414): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1414): wlan0: Scan-only results received
D/wpa_supplicant( 1414): wlan0: Radio work 'scan'@0x5577205680 done in 0.075021 seconds
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  953): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  953): handleMessage: E msg.what=147461
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1414): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  953): [1,454,056,170,188 ms] noteScanEnd no scan source
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1414): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  953): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3f990a53 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  953): NG7005g c0:ff:d4:d3:aa:4a rssi=-56 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  953): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  953): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  953):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  953): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): ageScanResultsOut delay 40000 size 3 now 1454056170190
E/WifiAutoJoinController (  953): newSupplicantResults size=3 known=1 true
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1414): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  953): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  953): ssid=NG700
E/WifiAutoJoinController (  953): id=0
E/WifiAutoJoinController (  953): mode=station
E/WifiAutoJoinController (  953): pairwise_cipher=CCMP
E/WifiAutoJoinController (  953): group_cipher=CCMP
E/WifiAutoJoinController (  953): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  953): wpa_state=COMPLETED
E/WifiAutoJoinController (  953): ip_address=192.168.1.130
E/WifiAutoJoinController (  953): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  953): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  953): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  953): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  953): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-59,-127) num=(1,0)
E/WifiAutoJoinController (  953): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  953): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-59 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  953): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  953): Done attemptAutoJoin status=0
E/WifiConfigStore(  953):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  953): handleMessage: X
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  953):  packet count Tx=261 Rx=319
E/WifiTrafficPoller(  953): notifying of data activity 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/Prism.ItemManager( 1505): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1505): loadItems() com.htc.launcher.pageview.WidgetManager@eb8d36b +
I/Prism.WidgetManager( 1505): onLoadItems() +
W/ResourcesManager( 1505): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/cutils-trace( 6509): Error opening trace file: Permission denied (13)
W/asset   ( 1505): Copying FileAsset 0x559f21ca80 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
D/CustomizationManager( 6509): ====startRecUseTime====
D/htc.customization.log.level( 6509):  is 
W/CustomizationLogLevel( 6509): Level value is invalid, use default level 2
E/Prism.WidgetManager( 1505): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1505): onLoadItems() -
I/Prism.ItemManager( 1505): loadItems() com.htc.launcher.pageview.WidgetManager@eb8d36b -
D/CustomizationManager( 6509):  Read ACC file spent 0.043 (s)
D/CIDMapFileReader( 6509): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6509): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6509): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6509): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6509): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6509): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6509): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6509): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6509): Parsing tag category name = system
I/CustomizationCIDLoader( 6509): Parsing tag category name = application
I/CustomizationCIDLoader( 6509): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6509): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6509): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6509): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6509): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6509): add string-array item, value = 42507
I/CustomizationCIDLoader( 6509): add string-array item, value = 21902
I/CustomizationCIDLoader( 6509): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6509): add string-array item, value = 23420
I/CustomizationCIDLoader( 6509): add string-array item, value = 22299
I/CustomizationCIDLoader( 6509): add string-array item, value = 24002
I/CustomizationCIDLoader( 6509): add string-array item, value = 23210
I/CustomizationCIDLoader( 6509): add string-array item, value = 23205
I/CustomizationCIDLoader( 6509): add string-array item, value = 23806
I/CustomizationCIDLoader( 6509): add string-array item, value = 23430
I/CustomizationCIDLoader( 6509): add string-array item, value = 23408
I/CustomizationCIDLoader( 6509): add string-array item, value = 27205
I/CustomizationCIDLoader( 6509): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6509): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6509):  Read CID file spent 0.086 (s)
D/CustomizationManager( 6509):  All configurations done spent 0.086 (s)
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=261 Rx=319
I/ActivityManager(  953): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6509 on display 0
D/PMS     (  953): acquireHCC(321c9d1a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 953 1000 null
D/PMS     (  953): acquireHCC(2a29004b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 953 1000 null
D/PMS     (  953): acquireWL(36d770e6): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 953 1000 null
I/AnimationUtil(  953): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1505): [onPause]
I/FeedProviderManager( 1505): onPause
I/FeedHostManager( 1505): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@1f0ce7b6
I/SocialFeedProvider( 1505): +onPause
I/SocialFeedProvider( 1505): -onPause
W/HtcSystemUPManager(  953): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  953): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6527 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PhoneApp( 1444): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1444): -- N1 =0
D/PhoneApp( 1444): -- N2 =0
D/PhoneApp( 1444): -- N3 =0
I/art     (  407): Explicit concurrent mark sweep GC freed 8670(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 289us total 18.308ms
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 285us total 15.918ms
I/TrimMemoryManager( 1505): [trimMemory] 20
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 307us total 21.037ms
D/StatusBarManagerService(  953): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
I/WebViewFactory( 6527): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6527): Time to load native libraries: 9 ms (timestamps 1295-1304)
I/LibraryLoader( 6527): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6527): Binding Chromium to main looper Looper (main, tid 1) {98480d1}
I/LibraryLoader( 6527): Expected native library version number "",actual native library version number ""
I/chromium( 6527): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6527): Initializing chromium process, singleProcess=true
W/art     ( 6527): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6527): ApplicationContext is null in ApplicationStatus
W/chromium( 6527): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6527): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6527): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6527): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6527): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6527): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6527): Local Branch: 
I/Adreno-EGL( 6527): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6527): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6527):                  d74aa161a12b9c6fc6332151
I/art     (  953): Explicit concurrent mark sweep GC freed 34846(1916KB) AllocSpace objects, 4(272KB) LOS objects, 33% free, 16MB/25MB, paused 1.661ms total 164.963ms
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  953): java.lang.Throwable: stack dump
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b53df96:true
W/System.err(  953): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  953): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  953): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  953): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6527): 117397773: getState(). Returning 12
W/art     ( 6527): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6527): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6527): CordovaWebView is running on device made by: HTC
W/art     ( 6527): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6527): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6527): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6527): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  953):  packet count Tx=261 Rx=320
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  953): notifying of data activity 1
I/InputMethodManager( 6527): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4ab2e72, mServedView=org.apache.cordova.engine.SystemWebView{335b2c3 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@26b740
I/InputMethodManagerService(  953): Disable input method client, pid=1505
D/StatusBarManagerService(  953): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  953): Enable input method client, pid=6527
D/PMS     (  953): releaseWL(36d770e6): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  953): Displayed com.test.thalitest/.MainActivity: +953ms
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
W/XT9_C   ( 1381): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1381): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1381): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1381): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6527): Cannot call determinedVisibility() - never saw a connection for the pid: 6527
,D/JsMessageQueue( 6527): Set native->JS mode to OnlineEventsBridgeMode,
,I/PMS     (  953): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  953): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@25895247,
W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed
W/PMN     (  953): goingToSleep
W/SensorService(  953): disable: get sensor name = Accelerometer Sensor
W/SensorService(  953): pid=953, uid=1000
W/SensorService(  953): Active sensors: size = 4
W/SensorService(  953): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  953): CM32181 Light sensor (handle=0x00000003, connections=1),
W/SensorService(  953): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@25895247, eanble = 0, strlen(mName) = 91
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  953): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@31fe8460
W/SensorService(  953): Listener[1] = com.htc.smartdim.sensor_eye@b8fefd3
W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  953): mWirelessDisplayManager is null
D/PMS     (  953): acquireWL(f25b4a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 953 1000 null
W/PMS     (  953): mWirelessDisplayManager is still null
,I/PMS     (  953): Sleeping (uid 1000)...
D/XAN-DPS (  953): prepareColorFade 1
,W/PMN     (  953): goingToSleep done,
,W/HtcSystemUPManager(  953): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/Adreno-EGL(  953): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  953): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  953): Build Date: 03/09/15 Mon
I/Adreno-EGL(  953): Local Branch: 
I/Adreno-EGL(  953): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  953): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  953):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  953): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6579 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/PMS     (  953): releaseWL(f25b4a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  953): ACTION_SCREEN_ON
,I/AlarmManager(  953): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  953): [AlarmQueuing] done recovering
,I/AlarmManager(  953): [AlarmQueuing] recover EPS screen off blocked alarms
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL true Token 11,
I/AlarmManager(  953): [AlarmQueuing] done EPS screen off alarm recovering
E/WifiTrafficPoller(  953):  packet count Tx=261 Rx=320
E/WifiTrafficPoller(  953): notifying of data activity 0
D/WIFI_ICON( 1221): WifiActivity: 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiDataStallTracker(  953): ENABLE_DATA_MONITOR_POLL true Token 1,
,E/WifiStateMachine(  953): handleMessage: E msg.what=131167
,E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1414): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1414): SET_SCREEN_ON:On
I/wpa_supplicant( 1414): htc_wext_set_keepalive +
I/wpa_supplicant( 1414): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1414): getPrivFuncNum +	
I/wpa_supplicant( 1414): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1414): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1414): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1414): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1414): htc_wext_set_TX_TRACKING - ret = 0
V/SRS_Proc(  400): ParamSet string: screen_state=on
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
E/WifiStateMachine(  953): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  953): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  953): handleScreenStateChanged Exit: true
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131154
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1414): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiController(  953): handleMessage: E msg.what=155650
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=241 rxSum=197} preTxRxSum={txSum=241 rxSum=197}
D/WifiDataStallTracker(  953): updateDataStallInfo: NONE
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/wpa_supplicant( 1414): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131127
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131129
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
D/NetworkPolicy(  953): updateScreenOn: false
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
V/NetworkPolicy(  953): updateIfacesLocked()
,D/wpa_supplicant( 1414): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1414): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  953): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=33 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  953): handleMessage: X
D/GpsLocationProvider(  953): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/NetworkManagementService(  953): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/ResourcesManager( 6579): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false)
,D/PMS     (  953): acquireWL(919ca1b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(277177b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
,D/jxcore_app_log( 6527): JniHelper::setJavaVM(0xaadc88f8), pthread_self() = -1408384432,
D/PMS     (  953): releaseWL(919ca1b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/CalendarProvider2( 6579): Created com.android.providers.calendar.CalendarAlarmManager@98480d1(com.htc.providers.calendar.HtcCalendarProvider@1f50b736)
,D/XAN-DPS (  953): prepareColorFade done,
D/PMS     (  953): releaseWL(277177b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/XAN-DPS (  953): setBrightness to 0
,I/DisplayManagerService(  953): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/CalendarProvider2( 6579): wait start:true
,I/SensorManager(  953): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@31fe8460
W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  953): disable: get sensor name = CM32181 Light sensor
,W/SensorService(  953): pid=953, uid=1000
W/SensorService(  953): Active sensors: size = 3
W/SensorService(  953): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  953): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@31fe8460, eanble = 0, strlen(mName) = 67
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  953): Listener[0] = com.htc.smartdim.sensor_eye@b8fefd3
W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1312): [EventService]  onDisplayChanged: 0
V/ActivityManager(  953): Display changed displayId=0
,D/DotMatrix( 1312): [EventService] mbHDMIConnect: false, mCoverOn:false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/AlarmManager(  953): ACTION_SCREEN_OFF
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  953): stopDataStallAlarm 
I/AlarmManager(  953): [AlarmQueuing] screen off now: 
I/AlarmManager(  953): [AlarmQueuing] data connection: true
I/AlarmManager(  953): [AlarmQueuing] wifi connection: true
,E/WifiDataStallTracker(  953): ENABLE_DATA_MONITOR_POLL false Token 2
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
,E/WifiStateMachine(  953): handleMessage: E msg.what=131167
D/NetworkPolicy(  953): updateScreenOn: false
E/WifiStateMachine(  953): processMsg: ConnectedState
V/NetworkPolicy(  953): updateIfacesLocked()
E/WifiStateMachine(  953):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
D/NetworkManagementService(  953): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1414): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1414): SET_SCREEN_ON:Off
I/wpa_supplicant( 1414): htc_wext_set_keepalive +
I/wpa_supplicant( 1414): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1414): getPrivFuncNum +	
I/wpa_supplicant( 1414): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1414): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1414): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1414): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1414): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  953): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  953): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  953): handleScreenStateChanged Exit: false
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131154
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
,E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
V/SRS_Proc(  400): ParamSet string: screen_state=off
E/WifiStateMachine(  953): handleMessage: X
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  953): handleMessage: E msg.what=155651
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
I/chromium( 6527): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/CalendarProvider2( 6579): wait end:false
,I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@2a7b0911, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  953): enable: get sensor name = hTC Gesture Motion HIDI
,I/ActivityManager(  953): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6611 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
W/SensorService(  953): pid=1221, uid=10041
W/SensorService(  953): Active sensors: size = 4
W/SensorService(  953): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  953): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  953): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@2a7b0911, eanble = 1, strlen(mName) = 57
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  953): Listener[0] = com.htc.smartdim.sensor_eye@b8fefd3
W/SensorService(  953): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@2a7b0911
W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  953): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1312): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1444): start background delete task...
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false),
,D/ContactMessageStore( 1444): size: 0 , 0
D/ContactMessageStore( 1444): Background delete complete
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155
,E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2776] from screen [on:0 period:-1937740460] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState,
,E/WifiStateMachine(  953):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1937740459] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): handleMessage: X
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145),
,I/RemoteViews( 1221): apply : com.htc.updater 0 9 0 36
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  953): acquireWL(3c1f3da): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1823 10024 WorkSource{10024 com.google.android.gms},
W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  953): releaseWL(3c1f3da): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 6611): MY_DEBUG = false
D/PMS     (  953): acquireWL(f0e3ee8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1823 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): releaseWL(f0e3ee8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/SmartSyncUtils( 6611): isEpsOn(), nState = 0
,D/PMS     (  953): acquireWL(faba901): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6611 1000 null
,D/PMS     (  953): releaseWL(faba901): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  953): Init customizeScreenOffDelayClass error
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6611): isEpsOn(), nState = 0,
D/SmartSyncUtils( 6611): isEpsOn(), nState = 0
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  953): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@b8fefd3
W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  953): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  953): pid=953, uid=1000
W/SensorService(  953): Active sensors: size = 3
,W/SensorService(  953): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  953): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@b8fefd3, eanble = 0, strlen(mName) = 35
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  953): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2a7b0911
W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  953): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  953): pid=953, uid=1000
W/SensorService(  953): Active sensors: size = 2
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  953): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@b8fefd3, eanble = 0, strlen(mName) = 35
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  953): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2a7b0911
W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  953): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@b8fefd3
,E/ActivityThread(  953): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@178d9710 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  953): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@178d9710 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  953): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  953): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  953): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  953): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  953): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  953): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  953): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  953): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  953): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  953): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  953): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  953): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  953): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  953): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  953): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  953): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  953): Excessive delay in setPowerMode(): 316ms
D/PMS     (  953): Setting HAL interactive mode to false
D/PMS     (  953): Setting HAL interactive mode to false done
D/PMS     (  953): Setting HAL auto-suspend mode to true
D/PMS     (  953): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  953): screenObserver, isScreenOn=false
D/StatusBarManagerService(  953): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  953): Disable input method client, pid=6527
W/HtcSystemUPManager(  953): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/InputMethodManager( 6527): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{335b2c3 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1baa6659
D/HABCtrl (  953): TPE algorithm. remove timeout.
D/PMS     (  953): OOBE c monitor 11
I/InputManager(  953): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
D/NfcService( 1468): ScreenObserver: OFF
D/NfcService( 1468): applyRouting - 0
D/PMS     (  953): acquireWL(10fc6194): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1468 1027 null
D/NfcService( 1468): applyRouting -2
I/ActivityManager(  953): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6642 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/PMS     (  953): acquireWL(2da8d43d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(2da8d43d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  953): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  953): plugged=true pluggin=true
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  953): >> updateStatus
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/PMS     (  953): releaseWL(10fc6194): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WifiController(  953): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): processMsg: DeviceActiveState
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/WifiController(  953): handleMessage: X
D/NfcService( 1468): applyRouting
D/NfcService( 1468): Ignore this applyRouting...
I/PowerUsageList:PowerUsageHelper( 6611): PowerProfile::POWER_SCREEN_FULL = 154.8
D/PowerUsageList:BatterySipperExt( 6611): gen(), null == sipper.uidObj, userId = 0
,I/ClockController( 1221): stop clock update:screen off,
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/SmartSyncUtils( 6611): getMobilePolicyEnabled, result = true
,D/WifiService(  953): New client listening to asynchronous messages
,E/WifiTrafficPoller(  953): ADD_CLIENT: 8
,D/PowerUsageList:PowerUsageHelper( 6611): MY_DEBUG = false,
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL false Token 13 num clients 8
,D/PMS     (  953): releaseHCC(321c9d1a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  953): releaseHCC(2a29004b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL false Token 13 num clients 8,
,W/jxcore-log( 6527): Initializing JXcore engine
,W/jxcore-log( 6527): JXcore engine is ready
,W/jxcore-log( 6527): Starting JXcore engine
,W/jxcore-log( 6527): Platform android
W/jxcore-log( 6527): 
W/jxcore-log( 6527): Process ARCH arm,
W/jxcore-log( 6527): 
,I/CalendarProvider2( 6579): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6579): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar),
,I/ActivityManager(  953): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6667 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/Process (  953): killProcessQuiet, pid=5925
,I/ActivityManager(  953): Killing 5925:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  953): releaseWL(1ac3b95d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/ActivityManager(  953): Recipient 5925,
,W/ResourcesManager( 6667): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/jxcore-log( 6527): JXcore Cordova bridge is ready!
I/jxcore-log( 6527): 
W/jxcore-log( 6527): JXcore engine is started
,E/jxcore  ( 6527): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6527): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/CalendarApplication( 6667): onCreate
,D/ProviderChangeReceiver( 6667): ---------------------------------------------------
,D/ProviderChangeReceiver( 6667): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/chromium( 6527): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/HtcAlertService( 6667): start to updateAlertNotification!
,D/Process (  953): killProcessQuiet, pid=6313,
I/ActivityManager(  953): Killing 6313:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  953): Recipient 6313
,D/Process (  953): killProcessQuiet, pid=6338,
I/ActivityManager(  953): Killing 6338:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
W/PluginManager( 6527): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 236ms. Plugin should use CordovaInterface.getThreadPool().
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  953): Recipient 6338
,D/Process (  953): killProcessQuiet, pid=6365
,I/ActivityManager(  953): Killing 6365:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 6365,
,D/Process (  953): killProcessQuiet, pid=5739,
,I/ActivityManager(  953): Killing 5739:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5739,
,D/HtcAlertService( 6667): No fired or scheduled alerts
,D/HtcAlertUtils( 6667): -- cancelReminderNotification --
,D/HtcAlertUtils( 6667): broadcastExistReminder!,
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL false Token 3
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
,E/WifiStateMachine(  953):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2689] from screen [on:0 period:-1937737769] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
,E/WifiStateMachine(  953):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1937737768] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): handleMessage: X
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL false Token 3
,D/ContactMessageStore( 1444): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1444): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/Process (  953): killProcessQuiet, pid=5589
I/ActivityManager(  953): Killing 5589:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5589
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  953): acquireWL(5bb2432): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000}
,V/AlarmManager(  953): sending alarm PendingIntent{31826d87: PendingIntentRecord{f51f4b4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=139706, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{2661d583: PendingIntentRecord{d080300 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142688, Int=0
,D/WeatherUtility( 1221): Weather sync is On
,D/PMS     (  953): releaseWL(5bb2432): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  953): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  953): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  953): acquireWL(f537739): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 953 1000 null
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  953): [NET] android_getaddrinfofornet-, err=8
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  953): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  953): [NET] android_getaddrinfo_proxy+
D/libc    (  953): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  953): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  953): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  953): [reportHTCStatus] eventMask = 3 , status = 0
D/PMS     (  953): acquireWL(c6b4df5): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 953 1000 null
D/GpsLocationProvider(  953): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  953): releaseWL(f537739): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/GpsLocationProvider(  953):  [handleDownloadXtraData]inject done.
D/PMS     (  953): releaseWL(c6b4df5): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  953): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  953): acquireWL(3bef078a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/PMS     (  953): releaseWL(3bef078a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  953): onReceive BATTERY_CHANGED
,D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/PMS     (  953): runPSCheck
D/HtcPowerSaver(  953): Checking...
I/HtcPowerSaver(  953): >> updateStatus
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1444): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  953): acquireWL(37ce71fb): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1000}
V/AlarmManager(  953): sending alarm PendingIntent{cc33218: PendingIntentRecord{3eefd471 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454056229560, Int=0
D/PMS     (  953): acquireWL(1f3e1256): PARTIAL_WAKE_LOCK  *backup* 0x1 953 1000 null
V/AlarmManager(  953): sending alarm PendingIntent{31826d87: PendingIntentRecord{f51f4b4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199706, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{3b8832d7: PendingIntentRecord{1c557c4 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202366, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{75c46ad: PendingIntentRecord{16a0fde2 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189200, Int=0
,D/PMS     (  953): acquireWL(2eb32573): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  953): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  953): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  953): releaseWL(1f3e1256): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/WeatherUtility( 1221): Weather sync is On
D/PMS     (  953): releaseWL(37ce71fb): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  953): acquireWL(21a22c30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(2eb32573): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  953): releaseWL(21a22c30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(1f20673a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): releaseWL(1f20673a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(311bcfeb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(311bcfeb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(1cf35148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(1c0dbbe1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(3ee57fc7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): releaseWL(1cf35148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1934): Vacuum at: now=1454056262925 tag=VacuumService
,I/GoogleURLConnFactory( 1934): Using platform SSLCertificateSocketFactory
D/PMS     (  953): releaseWL(1c0dbbe1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(18c9351d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1934): No account for auth token provided,
,D/PMS     (  953): releaseWL(18c9351d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(d48a392): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(d48a392): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1934): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1934): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1934): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1934): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1934): [NET] android_getaddrinfo_proxy+
D/libc    ( 1934): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1934): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1934): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1934): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1934): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1934): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1934): No account for auth token provided
,W/Uploader( 1934): No account for auth token provided
,W/Uploader( 1934):  no longer exists, so no auth token.
,W/Uploader( 1934): No account for auth token provided
,I/GLSUser ( 1934): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1934): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1934): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1934): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,E/Uploader( 1934): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1934): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1934): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1934): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1934): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1934): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1934): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1934): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1934): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1934): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1934): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1934): ,	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1934): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  953): releaseWL(3ee57fc7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(2767e8b7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(2767e8b7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(24b00824): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(24b00824): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1573): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@542e6d0
D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  953): Killing 5430:com.htc.mediamanager/u0a28 (adj 15): empty #17
,D/Process (  953): killProcessQuiet, pid=5430
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5430
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  953): acquireWL(31469f8d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
D/UsbnetService(  953): BroadcastReceiver::onReceive+
I/BatteryService(  953): n_update end
D/UsbnetService(  953): onReceive BATTERY_CHANGED
,D/PMS     (  953): releaseWL(31469f8d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiController(  953): handleMessage: E msg.what=155652
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  953): battery changed pluggedType: 2
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): runPSCheck
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): processMsg: DeviceActiveState
I/HtcPowerSaver(  953): >> updateStatus
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  953): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  953): acquireWL(33bd1542): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  953): n_update end
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): releaseWL(33bd1542): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  953): BroadcastReceiver::onReceive+
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: StaEnabledState
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1414): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1414): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  953): acquireWL(17085953): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000},
V/AlarmManager(  953): sending alarm PendingIntent{31826d87: PendingIntentRecord{f51f4b4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259706, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{388aa789: PendingIntentRecord{2f0b438e com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454056401407, Int=0,
,D/PMS     (  953): releaseWL(17085953): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1934): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1934): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1934): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1934): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1934): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1934): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1934): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1934): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1934): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1934): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1934): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1221): reapply : com.google.android.gms 4 40
E/PlayEventLogger( 5978): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5978): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5978): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5978): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5978): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5978): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5978): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5978): Ignoring header User-Agent because its value was null.
,D/libc    ( 5978): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5978): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5978): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5978): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5978): [NET] android_getaddrinfo_proxy+
D/libc    ( 5978): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5978): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  953): acquireWL(2f78afc0): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1000},
V/AlarmManager(  953): sending alarm PendingIntent{2b6af5e5: PendingIntentRecord{2794a8ba android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=376361, Int=0
D/PMS     (  953): acquireWL(2a6f84f9): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 953 1000 null
D/PMS     (  953): acquireWL(1d95ac3e): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 953 1000 null
D/PMS     (  953): releaseWL(2f78afc0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/PMS     (  953): releaseWL(2a6f84f9): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  953): releaseWL(1d95ac3e): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  953): acquireWL(29296a9f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(29296a9f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1221): closing low battery warning: level=100
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  953): plugged=true pluggin=true
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  953): >> updateStatus
,D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  953): acquireWL(3b1907ec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(3b1907ec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): >> updateStatus
,D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: StaEnabledState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): handleMessage: X
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  953): acquireWL(169a77b5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(169a77b5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  953): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  953): plugged=true pluggin=true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): runPSCheck
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  953): Checking...
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  953): >> updateStatus
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  953): processMsg: DeviceActiveState
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1444): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1444): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1444): sku_id=118
,D/ContactMessageStore( 1444): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1444): start background delete task...
,D/ContactMessageStore( 1444): size: 0 , 0
,D/ContactMessageStore( 1444): Background delete complete
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  953): acquireWL(3b3c4e4a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  953): n_update end
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/PMS     (  953): releaseWL(3b3c4e4a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/PMS     (  953): runPSCheck
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): Checking...
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  953): acquireWL(2fc411bb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  953): n_update end
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): releaseWL(2fc411bb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  953): updateBatteryInfo
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PMS     (  953): runPSCheck
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  953): acquireWL(584b6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(584b6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  953): updateBatteryInfo
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PMS     (  953): runPSCheck
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState,
D/WifiController(  953): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  953): acquireWL(c47da31): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  953): n_update end
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): releaseWL(c47da31): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): battery changed pluggedType: 2
,D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): handleMessage: X
I/HtcPowerSaver(  953): << updateStatus
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  953): acquireWL(11f90516): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000}
,V/AlarmManager(  953): sending alarm PendingIntent{31826d87: PendingIntentRecord{f51f4b4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379707, Int=0
,I/bt-btm  ( 3114): Received oneshot timer event complete
V/AlarmManager(  953): sending alarm PendingIntent{b980e97: PendingIntentRecord{23fa6884 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941643, Int=0
I/bt-btm  ( 3114): btm_ble_timeout
I/bt-btm  ( 3114): btm_gen_resolvable_private_addr
,D/PMS     (  953): acquireWL(378ee86d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3114 1002 null
,D/bt-btm  ( 3114): btm_ble_rand_enc_complete
I/bt-btm  ( 3114): btm_gen_resolve_paddr_low
D/bt-smp  ( 3114): smp_encrypt_data
W/bt-smp  ( 3114): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3114): Plain text(LSB ~ MSB) = 4f c8 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3114): Encrypted text(LSB ~ MSB) = 43 0a de a8 08 76 67 3b 67 8f 48 6f 1b 81 cf c6 
I/bt-btm  ( 3114): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3114): Stopping oneshot timer
D/bt-btm  ( 3114): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  953): releaseWL(11f90516): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  953): releaseWL(378ee86d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  953): acquireWL(23f85ca2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
,D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
I/BatteryService(  953): n_update end
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/PMS     (  953): releaseWL(23f85ca2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/PMS     (  953): runPSCheck
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): Checking...
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  953): >> updateStatus
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  953): battery changed pluggedType: 2
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  953): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: DeviceActiveState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): processMsg: StaEnabledState
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): processMsg: DefaultState
,D/WifiController(  953): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  953): acquireWL(444fd33): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{10024}
V/AlarmManager(  953): sending alarm PendingIntent{1ef788f0: PendingIntentRecord{34be9e69 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454056615604, Int=1800000
V/AlarmManager(  953): sending alarm PendingIntent{37a3a0ee: PendingIntentRecord{31c8398f com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937434, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{295f1464: PendingIntentRecord{3f0a56cd android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805634, Int=0
,I/ActivityManager(  953): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6705 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  953): sending alarm PendingIntent{764441c: PendingIntentRecord{3c19b825 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454057005125, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{3eacddfa: PendingIntentRecord{323c02c4 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454057026565, Int=0
,D/PMS     (  953): acquireWL(498dfab): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4430 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(d52b1a1): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(d52b1a1): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): acquireWL(21dadfc6): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4430 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): releaseWL(498dfab): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  953): releaseWL(444fd33): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6611): MY_DEBUG = false
,D/PowerUsageService( 6611): repeat time = 1454057926661
,I/EventLogService( 4430): Aggregate from 1454056159458 (log), 1454054815567 (data)
,D/PMS     (  953): acquireWL(12370e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1934): Message class com.google.f.a.a.i
,D/PMS     (  953): releaseWL(12370e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(21dadfc6): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 6611): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6611): gen(), null == sipper.uidObj, userId = 0,
,I/art     (  953): Explicit concurrent mark sweep GC freed 39640(2MB) AllocSpace objects, 11(1868KB) LOS objects, 33% free, 18MB/28MB, paused 1.641ms total 167.061ms,
,D/StatusBarManagerService(  953): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
,D/StatusBarManagerService(  953): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
,D/FindExtension( 1505): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1505): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  953): Disable input method client, pid=6527
D/StatusBarManagerService(  953): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6527): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false),
,E/cutils-trace( 6729): Error opening trace file: Permission denied (13),
I/dex2oat ( 6729): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6729): dex2oat: override thread count:4
,I/dex2oat ( 6729): dex2oat took 920.173ms (threads: 4),
,I/PushClient( 6705): ApplicationMonitor {2636ed3}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
I/PushClient( 6705): ApplicationMonitor {2636ed3}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6705): ApplicationMonitor {2636ed3}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6705): ApplicationMonitor {2636ed3}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6705): ApplicationMonitor {2636ed3}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6705): ApplicationMonitor {2636ed3}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6705): ApplicationMonitor {2636ed3}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6705): ApplicationMonitor {2636ed3}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6705): ApplicationMonitor {2636ed3}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6705): PnsModel {34e910c2}: update(): Update registration caused by: alarm
,I/PushClient( 6705): PnsConfigModel {6d64041}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6705): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6705): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6705): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6705): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  953): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6736 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6736): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6736 dbg=false s=true,
,I/DeviceManagement( 6736): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6736): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6736): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6736): WorkflowService: Starting workflow service
,I/DeviceManagement( 6736): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@34e910c2] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6736): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6736): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6736): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6736): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6736): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6736): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6736): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6736): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@34e910c2],
,I/DeviceManagement( 6736): WorkflowService: Stopping workflow service,
,D/Process (  953): killProcessQuiet, pid=5700
I/ActivityManager(  953): Killing 5700:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5700,
,I/PushClient( 6705): PnsModel {34e910c2}: update(): The registration record has not expired yet. No need to update.
,D/Process (  953): killProcessQuiet, pid=6422
,I/ActivityManager(  953): Killing 6422:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 6422
,D/PMS     (  953): acquireWL(93c78e4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000},
V/AlarmManager(  953): sending alarm PendingIntent{31826d87: PendingIntentRecord{f51f4b4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=979707, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{3fed214d: PendingIntentRecord{6aad402 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454057073018, Int=0
,D/SmartSyncUtils( 6611): isEpsOn(), nState = 0
,D/PMS     (  953): releaseWL(93c78e4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  953): acquireWL(1ee11113): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6611 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6611): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6611): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6611): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6611): SettingOnTime = 1454133600000, randomSettingOnTime = 1454131855000
D/SmartSyncScreenOnOffTimeReceiver( 6611): SettingOffTime = 1454112000000, randomSettingOffTime = 1454113498000
,D/SmartSyncScreenOnOffTimeReceiver( 6611): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6611): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6611): bNightModeTurnOffOnce = false
,D/PMS     (  953): releaseWL(1ee11113): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): acquireWL(ba3f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/BatteryService(  953): n_update end
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  953): releaseWL(ba3f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
I/HtcPowerSaver(  953): >> updateStatus,
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): handleMessage: X
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  953): acquireWL(16778549): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
,D/PMS     (  953): releaseWL(16778549): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953): onReceive BATTERY_CHANGED,
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
I/HtcPowerSaver(  953): >> updateStatus
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  953): acquireWL(1af62e4e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
,D/PMS     (  953): releaseWL(1af62e4e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/PMS     (  953): runPSCheck
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): handleMessage: E msg.what=155652
D/HtcPowerSaver(  953): Checking...
,D/WifiController(  953): processMsg: DeviceActiveState
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  953): handleMessage: X
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  953): acquireWL(1b41ab6f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(1b41ab6f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): battery changed pluggedType: 2
,D/WifiController(  953): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): handleMessage: X
I/HtcPowerSaver(  953): << updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  953): User[0] Flushing usage stats to disk
,D/PMS     (  953): acquireWL(240c007c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(240c007c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  953): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PMS     (  953): runPSCheck
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  953): >> updateStatus
,D/WifiController(  953): handleMessage: E msg.what=155652,
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState
,D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  953): acquireWL(1d2a2d05): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(1d2a2d05): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  953): BroadcastReceiver::onReceive+
,D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  953): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/WifiController(  953): handleMessage: X
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  953): << updateStatus
D/HeadsetStateMachine( 3114): Disconnected process message: 10, size: 0
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms)
```
