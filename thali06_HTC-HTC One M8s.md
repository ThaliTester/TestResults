#### Test 58259810381ca4f_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  944):  packet count Tx=199 Rx=308
,--------- beginning of system
D/PMS     (  944): acquireWL(2fa5fff5): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10072}
V/AlarmManager(  944): sending alarm PendingIntent{a28d18a: PendingIntentRecord{1df573fb com.android.vending startService}}, i=null, t=0, cnt=1, w=1454578940688, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{39fb0c18: PendingIntentRecord{2023a671 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454578942420, Int=536832000
V/AlarmManager(  944): sending alarm PendingIntent{97db69f: PendingIntentRecord{362563ec android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454578933752, Int=20000
V/CheckinService( 4527): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
D/PMS     (  944): acquireWL(384a7c56): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4527 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  944): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiStateMachine(  944): handleMessage: E msg.what=131143
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:88 rssi=-56 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 list=2412 [on:0 tx:0 rx:0 period:584] from screen [on:0 period:-1414970891]
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):3 dur:88 rssi=-56 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 list=2412 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1414970889]
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.37 rxSuccessRate=1.38 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-56
D/PMS     (  944): releaseWL(2fa5fff5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN with age=59953 interval=60000 maxinterval=300000
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  944): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  944): has c0:ff:d4:d3:aa:48 freq=2412 age=593 ?=true
E/WifiStateMachine(  944): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1344): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1344): wpa_supplicant_scan enter
D/wpa_supplicant( 1344): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1344): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1344): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1344): WPS:  * Request Type
D/wpa_supplicant( 1344): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1344): WPS:  * UUID-E
D/wpa_supplicant( 1344): WPS:  * Primary Device Type
D/wpa_supplicant( 1344): WPS:  * RF Bands (3)
D/wpa_supplicant( 1344): WPS:  * Association State
D/wpa_supplicant( 1344): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1344): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1344): WPS:  * Manufacturer
D/wpa_supplicant( 1344): WPS:  * Model Name
D/wpa_supplicant( 1344): WPS:  * Model Number
D/wpa_supplicant( 1344): WPS:  * Device Name
D/wpa_supplicant( 1344): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1344): P2P: * P2P IE header
D/wpa_supplicant( 1344): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1344): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1344): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1344): wlan0: Add radio work 'scan'@0x55a5c08860
D/wpa_supplicant( 1344): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1344): wlan0: Starting radio work 'scan'@0x55a5c08860 after 0.000089 second wait
D/wpa_supplicant( 1344): wlan0: nl80211: scan request
D/wpa_supplicant( 1344): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1344): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1344): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1344): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1344): wlan0: Own scan request started a scan in 0.000174 seconds
I/wpa_supplicant( 1344): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  944): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  944): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  944): [1,454,578,942,460 ms] noteScanstart no scan source
E/WifiStateMachine(  944): handleMessage: X
D/PMS     (  944): acquireWL(13a0d1c4): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4527 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(384a7c56): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4527): Checking schedule, now: 1454578942481 next: 1454578942420
I/CheckinService( 4527): active receiver: enabled
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4527, uid=10024, userID:0
I/CheckinService( 4527): Preparing to send checkin request
I/EventLogService( 4527): Accumulating logs since 1454578905679
D/wpa_supplicant( 1344): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1344): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1344): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1344): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1344): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1344): wlan0: Scan completed in 0.072621 seconds
D/wpa_supplicant( 1344): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1344): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1344): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1344): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1344): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1344): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1344): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1344): [NULL] 00:37:b7:9d:3e:73 freq=5500 level=-87
I/wpa_supplicant( 1344): [NULL] a0:c5:62:7a:49:97 freq=5180 level=-88
D/wpa_supplicant( 1344): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1344): BSS: last_scan_res_used=6/32
D/wpa_supplicant( 1344): wlan0: Scan-only results received
D/wpa_supplicant( 1344): wlan0: Radio work 'scan'@0x55a5c08860 done in 0.073883 seconds
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  944): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  944): handleMessage: E msg.what=147461
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
E/WifiStateMachine(  944): processMsg: DriverStartedState
W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  944):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
D/WifiStateMachine(  944): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1344): wlan0: Control interface command 'LIST_DONGLES'
I/CheckinRequestBuilder( 4527): Checkin reason type: 11 attempt count: 1
E/WifiStateMachine(  944): [1,454,578,942,537 ms] noteScanEnd no scan source
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1344): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  944): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@333a7773 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  944): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): NG700 c0:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  944): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  944): updateSavedNetworkHistory: HTC improve mode
I/ActivityManager(  944): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/WifiConfigStore(  944):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-56 freq=2412
E/WifiAutoJoinController (  944): Gonzos 38:f8:89:11:e9:11 rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/ActivityThread( 4527): Failed to find provider info for com.google.android.wearable.settings
E/WifiAutoJoinController (  944): UPC503894600 a0:c5:62:7a:49:97 rssi=-88 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): FunBox2-3E72 00:37:b7:9d:3e:73 rssi=-87 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): 01ABC c2:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  944): ageScanResultsOut delay 40000 size 6 now 1454578942541
E/WifiAutoJoinController (  944): newSupplicantResults size=6 known=1 true
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1344): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  944): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  944): ssid=NG700
E/WifiAutoJoinController (  944): id=0
E/WifiAutoJoinController (  944): mode=station
E/WifiAutoJoinController (  944): pairwise_cipher=CCMP
E/WifiAutoJoinController (  944): group_cipher=CCMP
E/WifiAutoJoinController (  944): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  944): wpa_state=COMPLETED
E/WifiAutoJoinController (  944): ip_address=192.168.1.130
E/WifiAutoJoinController (  944): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  944): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  944): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  944): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  944): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-56,-127) num=(1,0)
E/WifiAutoJoinController (  944): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  944): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-56 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  944): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  944): Done attemptAutoJoin status=0
E/WifiConfigStore(  944):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  944): handleMessage: X
E/cutils-trace( 6662): Error opening trace file: Permission denied (13)
I/GLSUser ( 1846): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1846): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1846): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1846): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/CustomizationManager( 6662): ====startRecUseTime====
D/htc.customization.log.level( 6662):  is 
W/CustomizationLogLevel( 6662): Level value is invalid, use default level 2
V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/CheckinRequestBuilder( 4527): awaiting user notification for token
I/RemoteViews( 1221): reapply : com.google.android.gms 1 40
D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/CustomizationManager( 6662):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 6662): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6662): Parsing tag item name = HTC__102
I/ActivityManager(  944): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6679 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/CIDMapFileReader( 6662): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6662): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6662): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6662): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6662): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6662): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6662): Parsing tag category name = system
I/CustomizationCIDLoader( 6662): Parsing tag category name = application
I/CustomizationCIDLoader( 6662): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6662): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6662): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6662): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6662): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6662): add string-array item, value = 42507
I/CustomizationCIDLoader( 6662): add string-array item, value = 21902
I/CustomizationCIDLoader( 6662): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6662): add string-array item, value = 23420
I/CustomizationCIDLoader( 6662): add string-array item, value = 22299
I/CustomizationCIDLoader( 6662): add string-array item, value = 24002
I/CustomizationCIDLoader( 6662): add string-array item, value = 23210
I/CustomizationCIDLoader( 6662): add string-array item, value = 23205
I/CustomizationCIDLoader( 6662): add string-array item, value = 23806
I/CustomizationCIDLoader( 6662): add string-array item, value = 23430
I/CustomizationCIDLoader( 6662): add string-array item, value = 23408
I/CustomizationCIDLoader( 6662): add string-array item, value = 27205
I/CustomizationCIDLoader( 6662): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6662): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6662):  Read CID file spent 0.107 (s)
D/CustomizationManager( 6662):  All configurations done spent 0.107 (s)
I/ActivityManager(  944): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6662 on display 0
D/PMS     (  944): acquireHCC(143e33f4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 944 1000 null
D/PMS     (  944): acquireHCC(3508a71d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 944 1000 null
W/asset   (  944): Copying FileAsset 0x5583887a60 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  944): acquireWL(1a049b60): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 944 1000 null
I/AnimationUtil(  944): isHTCRecent(ThaliTest/Recent screens.)/5
W/art     ( 6662): No such thread id for suspend: 17
D/Finsky  ( 6169): [617] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6169): [1] 5.onFinished: Installation state replication succeeded.
I/art     (  944): Explicit concurrent mark sweep GC freed 36238(2MB) AllocSpace objects, 5(164KB) LOS objects, 33% free, 16MB/25MB, paused 1.375ms total 177.230ms
I/FeedHostManager( 1606): [onPause]
I/FeedProviderManager( 1606): onPause
W/ResourcesManager( 6679): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6679): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/FeedHostManager( 1606): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@61a403a
I/SocialFeedProvider( 1606): +onPause
I/SocialFeedProvider( 1606): -onPause
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  944): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6704 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/MultiDex( 6679): VM with version 2.1.0 has multidex support
I/MultiDex( 6679): install
I/MultiDex( 6679): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6679): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/StatusBarManagerService(  944): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
,W/asset   ( 6704): Copying FileAsset 0xab3bd4c8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/ActivityThread( 6679): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6679): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@108593c3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6679): Installed default security provider GmsCore_OpenSSL
I/TrimMemoryManager( 1606): [trimMemory] 20
D/GCM     ( 1846): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1846): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4527): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WearableService( 5210): callingUid 10024, callindPid: 5210
E/WifiTrafficPoller(  944):  packet count Tx=199 Rx=309
E/WifiTrafficPoller(  944): notifying of data activity 1
E/MDM     ( 1817): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/WebViewFactory( 6704): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4527, uid=10024, userID:0
I/WVCdm   (  398): CdmEngine::OpenSession
I/WVCdm   (  398): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  398): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/LocationInitializer( 4527): Restart initialization of location
D/DrmWidevineDash(  398): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  398): Service_Initialize: starts!
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
E/QSEECOMAPI: (  398): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  398): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
I/LibraryLoader( 6704): Time to load native libraries: 15 ms (timestamps 7837-7852)
I/LibraryLoader( 6704): Expected native library version number "",actual native library version number ""
D/QSEECOMAPI: (  398): Loaded image: APP id = 8
D/DrmWidevineDash(  398): Service_Initialize: ends! returns 0
D/QSAPPSVER(  398): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  398): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48a4000
E/DrmWidevineDash(  398): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48a4000
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  463): got the req here! ret=0
D/DrmLibTime(  463): command id, time_cmd_id = 770
D/DrmLibTime(  463): time_getutcsec starts!
D/DrmLibTime(  463): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  463): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  463): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  463): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  463): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  463): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  463): QSEE Time Listener: Retrieved Android system time: 1454578943
E/QC-time-services(  420): Daemon: Time-services: Waiting to acceptconnection
D/DrmLibTime(  463): time_getutcsec returns 0, sec = 1454578943; nsec = 0
D/DrmLibTime(  463): time_getutcsec finished! 
D/DrmLibTime(  463): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  463): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
V/WebViewChromiumFactoryProvider( 6704): Binding Chromium to main looper Looper (main, tid 1) {7b84ad6}
I/LibraryLoader( 6704): Expected native library version number "",actual native library version number ""
I/chromium( 6704): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  398): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: starts! SID=0xffade948
D/DrmWidevineDash(  398): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: starts! randomData=0xab315208, dataLength=8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab2df818, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  398): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  398): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  398): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  398): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: starts! deviceID=0xab314b78, idLength=0xf4bd06f8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/BrowserStartupController( 6704): Initializing chromium process, singleProcess=true
W/art     ( 6704): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6704): ApplicationContext is null in ApplicationStatus
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4bd070e, maximum = 0xf4bd070f
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4bd077c
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  398): PrepareKeyRequest: nonce=1396309270
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab421528
D/DrmWidevineDash(  398): message_length=1611, signature=0xab421b78, signature_length=0xf4bd06dc
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/chromium( 6704): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6704): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6704): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  398): CdmEngine::CloseSession
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  398): L3 Terminate.
D/DrmWidevineDash(  398): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): Service_Uninitialize: starts!
D/QSEECOMAPI: (  398): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  398): QSEECom_shutdown_app, app_id = 8
I/Adreno-EGL( 6704): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6704): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6704): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6704): Local Branch: 
I/Adreno-EGL( 6704): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6704): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6704):                  d74aa161a12b9c6fc6332151
D/DrmWidevineDash(  398): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  398): OEMCrypto_Terminate: ends! returns 0
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c286da8:true
W/System.err(  944): java.lang.Throwable: stack dump
W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6704): 1002847842: getState(). Returning 12
E/cutils-trace( 6748): Error opening trace file: Permission denied (13)
I/dex2oat ( 6748): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6748): dex2oat: override thread count:4
I/dex2oat ( 6748): dex2oat took 43.413ms (threads: 4)
I/Adreno-EGL( 6679): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6679): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6679): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6679): Local Branch: 
I/Adreno-EGL( 6679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6679): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6679):                  d74aa161a12b9c6fc6332151
W/art     ( 6704): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6704): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6704): CordovaWebView is running on device made by: HTC
W/art     ( 6704): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6704): Attempt to remove local handle scope entry from IRT, ignoring
I/Adreno-EGL( 6679): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6679): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6679): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6679): Local Branch: 
I/Adreno-EGL( 6679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6679): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6679):                  d74aa161a12b9c6fc6332151
W/chromium( 6704): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6704): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/WVCdm   (  398): CdmEngine::OpenSession
I/WVCdm   (  398): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  398): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  398): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  398): Service_Initialize: starts!
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
E/QSEECOMAPI: (  398): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  398): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  398): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  398): App is not loaded in QSEE
D/QSEECOMAPI: (  398): Loaded image: APP id = 9
D/DrmWidevineDash(  398): Service_Initialize: ends! returns 0
D/QSAPPSVER(  398): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  398): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48a4000
E/DrmWidevineDash(  398): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48a4000
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  463): got the req here! ret=0
D/DrmLibTime(  463): command id, time_cmd_id = 770
D/DrmLibTime(  463): time_getutcsec starts!
D/DrmLibTime(  463): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  463): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  463): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  463): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  463): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  463): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  463): QSEE Time Listener: Retrieved Android system time: 1454578943
D/DrmLibTime(  463): time_getutcsec returns 0, sec = 1454578943; nsec = 0
D/DrmLibTime(  463): time_getutcsec finished! 
D/DrmLibTime(  463): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  463): before calling ioctl to read the next time_cmd
E/QC-time-services(  420): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  398): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: starts! SID=0xf4ad0928
D/DrmWidevineDash(  398): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  398): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: starts! randomData=0xab421918, dataLength=8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab2df818, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/InputMethodManager( 6704): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@13e67e3, mServedView=org.apache.cordova.engine.SystemWebView{7cb95e0 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@24994099
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  398): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  398): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  398): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  398): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: starts! deviceID=0xab314b98, idLength=0xf49d06f8
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/InputMethodManagerService(  944): Disable input method client, pid=1606
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  944): Enable input method client, pid=6704
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/PMS     (  944): releaseWL(1a049b60): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  944): Displayed com.test.thalitest/.MainActivity: +916ms
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  398): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: starts!, current = 0xf49d070e, maximum = 0xf49d070f
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): hlos api version =  9
D/DrmWidevineDash(  398): tz api version =  9
D/DrmWidevineDash(  398): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf49d077c
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  398): PrepareKeyRequest: nonce=1481710259
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab424a20
D/DrmWidevineDash(  398): message_length=1646, signature=0xab425098, signature_length=0xf49d06dc
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/XT9_C   ( 1398): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1398): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1398): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1398): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6704): Cannot call determinedVisibility() - never saw a connection for the pid: 6704
E/WifiDataStallTracker(  944): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  944): updateDataStallInfo: mDataStallTxRxSum={txSum=177 rxSum=170} preTxRxSum={txSum=177 rxSum=170}
D/WifiDataStallTracker(  944): updateDataStallInfo: NONE
D/WifiDataStallTracker(  944): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  398): CdmEngine::CloseSession
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  398): L3 Terminate.
D/DrmWidevineDash(  398): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  398): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  398): Service_Uninitialize: starts!
D/QSEECOMAPI: (  398): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  398): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  398): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  398): OEMCrypto_Terminate: ends! returns 0
D/JsMessageQueue( 6704): Set native->JS mode to OnlineEventsBridgeMode
I/CheckinRequestBuilder( 4527): Classify the device as Phone.
E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  944):  packet count Tx=199 Rx=309
E/WifiTrafficPoller(  944): notifying of data activity 0
D/WIFI_ICON( 1221): WifiActivity: 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    ( 4527): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4527): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4527): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4527): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4527): [NET] android_getaddrinfo_proxy+
D/libc    ( 4527): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4527): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4527): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4527): [NET] android_getaddrinfofornet-, err=8
D/jxcore_app_log( 6704): JniHelper::setJavaVM(0xab34d8f8), pthread_self() = -1402402000
I/chromium( 6704): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/libc    ( 4527): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4527): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4527): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4527): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4527): Sending checkin request (8439 bytes)
,D/PMS     (  944): releaseHCC(143e33f4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  944): releaseHCC(3508a71d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155,
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:2409] from screen [on:0 period:-1414968474] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1414968473] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  944):  get link layer stats 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1344): environment dirty rate=5 [19][1][0]
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
I/CheckinRequestBuilder( 4527): Checkin reason type: 11 attempt count: 1
E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=9.69 txretriesrate=0.00 rxrate=8.19 userTriggerdPenalty0
E/WifiStateMachine(  944):  good link -> stuck count =0
E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 60
,E/WifiStateMachine(  944):  isHighRSSI       ---> score=65
I/ActivityManager(  944): Cannot resolve ContentProvider=com.google.android.wearable.settings
,D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -56, 3
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/ActivityThread( 4527): Failed to find provider info for com.google.android.wearable.settings
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  944): handleMessage: X
,I/art     ( 1846): Explicit concurrent mark sweep GC freed 8243(419KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 771us total 39.950ms
,I/GLSUser ( 1846): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1846): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1846): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1846): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4527): awaiting user notification for token
,D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,I/CheckinRequestBuilder( 4527): Classify the device as Phone.
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 3
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=323
,E/WifiTrafficPoller(  944): notifying of data activity 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/CheckinTask( 4527): Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,I/CheckinService( 4527): Checking schedule, now: 1454578945207 next: 1455115777189,
I/CheckinService( 4527): active receiver: disabled
W/jxcore-log( 6704): Initializing JXcore engine
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4527, uid=10024, userID:0
W/jxcore-log( 6704): JXcore engine is ready
,D/PMS     (  944): releaseWL(13a0d1c4): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6782 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,W/jxcore-log( 6704): Starting JXcore engine
,D/PhoneMonitor( 6782): Register our PhoneStateListener
,V/SetupWizard( 6782): Connected to Gservices successfully
,D/ChimeraCfgMgr( 4527): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4527): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PhoneMonitor( 6782): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/GCM     ( 1846): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PhoneMonitor( 6782): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/jxcore-log( 6704): Platform android
W/jxcore-log( 6704): 
W/jxcore-log( 6704): Process ARCH arm
W/jxcore-log( 6704): 
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/jxcore-log( 6704): JXcore Cordova bridge is ready!
I/jxcore-log( 6704): 
,W/jxcore-log( 6704): JXcore engine is started
,E/jxcore  ( 6704): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6704): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6704): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PMS     (  944): acquireWL(20735b23): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 944 1000 null
,W/PluginManager( 6704): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 47ms. Plugin should use CordovaInterface.getThreadPool().
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1606): [onResume]
I/FeedProviderManager( 1606): onResume,
I/SocialFeedProvider( 1606): +onResume
I/SocialFeedProvider( 1606): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1606): -onResume
,D/StatusBarManagerService(  944): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
D/FindExtension( 1606): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1606): Defer allocateBuffers to drawing time,
,I/InputMethodManagerService(  944): Disable input method client, pid=6704
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  944): Enable input method client, pid=1606
W/IInputConnectionWrapper( 6704): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,D/PMS     (  944): releaseWL(20735b23): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  944): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  944): hiding MENU key,
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=324
E/WifiTrafficPoller(  944): notifying of data activity 1
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 3314): handler message = 4011,
E/HtcModeClient( 3314): Check connection and retry 12 times.
,W/OpenGLRenderer( 1606): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
,D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=324
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  944): notifying of data activity 0
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155,
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=9.7, 0.0, 0.0  rx=8.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1414965464] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
,E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=9.7, 0.0, 0.0  rx=8.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1414965463] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  944):  get link layer stats 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1344): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
,E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.84 txretriesrate=0.00 rxrate=4.59 userTriggerdPenalty0,
E/WifiStateMachine(  944):  good link -> stuck count =0
E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  944):  isHighRSSI       ---> score=61
E/WifiStateMachine(  944): handleMessage: X
D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -56, 3
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=324
,D/Process (  944): killProcessQuiet, pid=6484
I/ActivityManager(  944): Killing 6484:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6484,
,I/ActivityManager(  944): Killing 5760:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=5760
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5760
,D/Process (  944): killProcessQuiet, pid=6506
I/ActivityManager(  944): Killing 6506:com.htc.providers.settings:remote/u0a13 (adj 15): empty #18
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6506,
,E/WifiDataStallTracker(  944): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  944): updateDataStallInfo: mDataStallTxRxSum={txSum=196 rxSum=184} preTxRxSum={txSum=177 rxSum=170},
D/WifiDataStallTracker(  944): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  944): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=325
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  944): notifying of data activity 1
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=325
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  944): notifying of data activity 0
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155,
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1414962443] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1414962442] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944):  get link layer stats 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1344): environment dirty rate=0 [0][0][0],
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.42 txretriesrate=0.00 rxrate=2.80 userTriggerdPenalty0
E/WifiStateMachine(  944):  good link -> stuck count =0
E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  944):  isHighRSSI       ---> score=61
E/WifiStateMachine(  944): handleMessage: X
D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -56, 3
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=325,
,I/HtcModeClient( 3314): handler message = 4011,
E/HtcModeClient( 3314): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3314): Don't start project servcice,
,D/HtcModeClient( 3314): setEject: MEDIA_EJECT_STATE = true,
D/HtcModeClient( 3314): connectState: CONNECTION_READY = false
D/SilentMusic( 3314): call stop
D/HtcModeClient( 3314): close connection
W/HtcModeClient( 3314): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3314): read the terminate packet, so break
,D/Process (  944): killProcessQuiet, pid=3314
I/ActivityManager(  944): Killing 3314:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3314
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=326
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  944): notifying of data activity 1
,I/ActivityManager(  944): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6809 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  944): acquireWL(3ee11711): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10076}
V/AlarmManager(  944): sending alarm PendingIntent{3043076: PendingIntentRecord{d0c677 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454578952401, Int=60000
D/PMS     (  944): releaseWL(3ee11711): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,I/art     (  404): Explicit concurrent mark sweep GC freed 8649(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 228us total 30.171ms
,D/SMSBackup( 6809): SMSBackupAgentService started
I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 201us total 24.364ms,
D/SMSBackup( 6809): Checking restore status
I/ActivityManager(  944): Killing 6211:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/SMSBackup( 6809): Restore complete
D/SMSBackup( 6809): cancelCheckAlarm
D/SMSBackup( 6809): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  944): killProcessQuiet, pid=6211
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  404): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 186us total 23.977ms
,I/ActivityManager(  944): Recipient 6211
,D/AccTypeManager( 1760): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
W/SystemReader(  944): Cannot find grip_rejection_width, use default value instead
,I/Prism.ItemManager( 1606): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1606): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1606): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,D/AccTypeManager( 1760): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  944): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6831 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager(  944): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneApp( 1555): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,D/AccTypeManager( 1760): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,E/ExternalAccountType( 1760): Unsupported attribute readOnly
,W/ResourcesManager( 6831): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/PackageManager(  944): Unable to load service info ResolveInfo{114d6e29 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  944): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  944): ,	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  944): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  944): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  944): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  944): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  944): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  944): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  944): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  944): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1817): DISABLE
,I/GCoreNlp( 1817): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  944): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LocationProviderProxy(  944): applying state to connected service,
D/PMS     (  944): acquireWL(2ad4b1b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1817 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(2ad4b1b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,D/LocationProviderProxy(  944): applying state to connected service
,D/PMS     (  944): acquireWL(18cb7df7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1817 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(18cb7df7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(15a0edce): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1817 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(15a0edce): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel_SMS( 6831): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6831): MmsConfig.loadMmsSettings
,I/ActivityManager(  944): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6861 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6831, uid=10112, userID:0,
,W/Settings( 6831): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 6831): startup - clean,
W/HtcWrapAdjustableCursorFactory( 6861): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 6861): onCreate
,V/GetPrviateResource( 6861): GetPrviateResource
,V/GetPrviateResource( 6861): GetPrviateResource
D/MmsCustomizationProvider( 6861): query uri: content://htc-mms-customization/mms-ua/ua_string
I/Babel   ( 6831): deleted: false for 0
,D/MmsCustomizationProvider( 6861): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 6831): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
I/Babel_SMS( 6831): MmsConfig.loadFromDatabase
D/MessageCustFlag( 6861): sense_version=6.0
D/BTAccessoryUtil( 6861): createReceiver
,D/BTAccessoryUtil( 6861): registerReceiver return intent = null,
D/MessageCustFlag( 6861): sku_id=118
,D/HtcBuildUtils( 6861): getRATByHtcTelephonyCapability:1
,W/SystemReader( 6861): Cannot find qct_8960_interface, use default value instead
,E/Babel_SMS( 6831): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6831): MmsConfig.loadFromResources
,E/Babel_SMS( 6831): canonicalizeMccMnc: invalid mccmnc nullnull,
I/Babel_SMS( 6831): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6831, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6831, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6831, uid=10112, userID:0,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6831, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6831, uid=10112, userID:0
,D/PMS     (  944): acquireWL(1ed1d000): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6831 10112 null,
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc
,I/[PluginManager]RegisterService( 1633): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1633): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4527): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4527): Null package name or gms related package.  Ignoreing.,
,W/VideoCapabilities( 6831): Unsupported mime video/x-ms-wmv
,W/Utils   ( 6831): could not parse size range '64x64-1920X1080',
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=326
E/WifiTrafficPoller(  944): notifying of data activity 0
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/AudioCapabilities( 6831): Unsupported mime audio/qcelp,
,W/AudioCapabilities( 6831): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6831): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6831): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 6831): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6831): onServiceConnected
W/Babel   ( 6831): Attempted to change video mute state without an active call.
,W/ResourcesManager( 6831): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6831): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  944): Explicit concurrent mark sweep GC freed 25302(1410KB) AllocSpace objects, 4(144KB) LOS objects, 33% free, 19MB/28MB, paused 2.600ms total 155.379ms
D/PMS     (  944): acquireWL(2982c756): PARTIAL_WAKE_LOCK  AsyncService 0x1 6239 10167 null
D/PMS     (  944): acquireWL(7ef43d7): PARTIAL_WAKE_LOCK  Icing 0x1 4527 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(2982c756): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  944): releaseWL(1ed1d000): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  944): acquireWL(1fdc3fad): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6239 10167 null
I/Icing   ( 4527): updateResources: need to parse f{com.google.android.gms},
,D/PMS     (  944): releaseWL(1fdc3fad): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 6085): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,V/JNIHelp ( 6831): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/PMS     (  944): releaseWL(7ef43d7): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/UpdateIcingCorporaServi( 6085): UpdateCorporaTask done [took 48 ms] updated apps [took 48 ms] 
,W/System  ( 6831): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6831): Installed default security provider GmsCore_OpenSSL
,E/WifiStateMachine(  944): WiFiStateMachine SCAN ALARM
D/PMS     (  944): acquireWL(28a8d6cf): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000}
E/WifiStateMachine(  944): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
,D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiStateMachine(  944): processMsg: ConnectedState
V/AlarmManager(  944): sending alarm PendingIntent{97db69f: PendingIntentRecord{362563ec android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454578953752, Int=20000
E/WifiStateMachine(  944):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:77 rssi=-56 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.8 list=2412 [on:0 tx:0 rx:0 period:2836] from screen [on:0 period:-1414959589]
D/PMS     (  944): releaseWL(28a8d6cf): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:77 rssi=-56 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.8 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1414959588]
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.42 rxSuccessRate=2.80 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-56
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN with age=71253 interval=60000 maxinterval=300000
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN try full band scan age=71253 interval=60000 maxinterval=300000
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN bump interval =90000
,W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1344): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1344): wpa_supplicant_scan enter
D/wpa_supplicant( 1344): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1344): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1344): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1344): WPS:  * Request Type
D/wpa_supplicant( 1344): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1344): WPS:  * UUID-E
D/wpa_supplicant( 1344): WPS:  * Primary Device Type
D/wpa_supplicant( 1344): WPS:  * RF Bands (3)
D/wpa_supplicant( 1344): WPS:  * Association State
D/wpa_supplicant( 1344): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1344): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1344): WPS:  * Manufacturer
D/wpa_supplicant( 1344): WPS:  * Model Name
D/wpa_supplicant( 1344): WPS:  * Model Number
D/wpa_supplicant( 1344): WPS:  * Device Name
D/wpa_supplicant( 1344): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1344): P2P: * P2P IE header
D/wpa_supplicant( 1344): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1344): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1344): wlan0: Add radio work 'scan'@0x55a5c08860
D/wpa_supplicant( 1344): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1344): wlan0: Starting radio work 'scan'@0x55a5c08860 after 0.000037 second wait
D/wpa_supplicant( 1344): wlan0: nl80211: scan request
D/wpa_supplicant( 1344): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1344): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1344): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1344): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1344): wlan0: Own scan request started a scan in 0.000083 seconds
I/wpa_supplicant( 1344): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  944): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  944): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  944): [1,454,578,953,758 ms] noteScanstart no scan source
E/WifiStateMachine(  944): handleMessage: X
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155,
E/WifiStateMachine(  944): processMsg: ConnectedState
,E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:161] from screen [on:0 period:-1414959424] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1414959423] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944):  get link layer stats 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
,E/WifiDataStallTracker(  944): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  944): updateDataStallInfo: mDataStallTxRxSum={txSum=196 rxSum=184} preTxRxSum={txSum=196 rxSum=184},
D/WifiDataStallTracker(  944): updateDataStallInfo: NONE
D/WifiDataStallTracker(  944): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=326
,I/Prism.ItemManager( 1606): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1606): loadItems() com.htc.launcher.pageview.WidgetManager@2a515ddc +
I/Prism.WidgetManager( 1606): onLoadItems() +
,E/Prism.WidgetManager( 1606): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1606): onLoadItems() -
,I/Prism.ItemManager( 1606): loadItems() com.htc.launcher.pageview.WidgetManager@2a515ddc -
,I/wpa_supplicant( 1344): environment dirty rate=0 [0][0][0],
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.21 txretriesrate=0.00 rxrate=1.90 userTriggerdPenalty0
E/WifiStateMachine(  944):  good link -> stuck count =0
,E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  944):  isHighRSSI       ---> score=61
E/WifiStateMachine(  944): handleMessage: X
D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -57, 3
,D/PhoneApp( 1555): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1555): -- N1 =0
,D/PhoneApp( 1555): -- N2 =0
,D/PhoneApp( 1555): -- N3 =0
,D/Messaging( 6861): supportCMAS(SIE)/init? false/true,
,D/MmsConfig( 6861): networkCode: 
,D/MessageCustFlag( 6861): sku_id=118
,D/MmsConfig( 6861): SIE smsPri: null
D/MmsConfig( 6861): networkCode: 
,D/MmsConfig( 6861): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 6861): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 6861): 
D/MmsAsyncWorkHandler( 6861): HM tk = 20001
D/ReportIndicatorCache( 6861): MSG_QUERY_REPORTS >>
,D/SettingsManager( 6861): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@27c94157
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91,
D/AccFlag ( 1555): sku_id=118
,D/Messaging( 6861): mNeedToUpdateDate2 start,
,D/DraftCache( 6861): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6861): [DraftCache/1] refresh
,D/DraftCache( 6861): [DraftCache/171] rebuildCache,
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1555):  slotId = -1000
D/MmsSmsV2Provider( 1555): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
,D/MmsSmsV2Provider( 1555):  slotId = -1000
D/MmsSmsV2Provider( 1555): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 6861): mccmnc> 
,D/MmsConfig( 6861): networkCode: ,
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1555):  slotId = -1000
D/MmsSmsV2Provider( 1555): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/MmsSmsV2Provider( 1555):  slotId = -1000
D/MmsSmsV2Provider( 1555): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 6861): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Messaging( 6861): ViewCache CreatePreloadOnlyConversationList
,D/Messaging( 6861): mNeedToUpdateDate2: false
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/Jerry   ( 1555): URI_DRAFT
,D/DraftCache( 6861): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 6861): [DraftCache/171] rebuildCache time: 15,
D/MmsAsyncWorkHandler( 6861): 
D/MmsAsyncWorkHandler( 6861): HM tk = 20002
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/AccFlag ( 1555): sku_id=118
,D/MessageCustFlag( 6861): sense_version=6.0
D/Jerry   ( 6861): start to preload cursor >>>>>>>
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1555):  slotId = -1000
D/PhoneStorageUtil( 6861): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6861): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6861): createReceiver
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1555): sku_id=118
,D/Messaging( 6861): ViewCache CreatePreload
D/Messaging( 6861): ViewCache CreatePreloadOnlyMultipleOpsList
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=326
,D/TelephUtils( 1555): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
V/MmsProvider( 1555): Update uri=content://mms, match=0
V/MmsProvider( 1555): selection=st=129 AND m_type!=134
D/Messaging( 6861): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6861): TransactionService is going to be woken up.
,D/Cust_MMSMS( 6861): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6861): def_index: 0
,V/TransactionService( 6861): 1-Creating TransactionService
,D/MsgPreferenceUtils( 6861): globalIndex = 1,
,D/MsgPreferenceUtils( 6861): phone state: true
D/MsgPreferenceUtils( 6861): sd state: false
D/MsgPreferenceUtils( 6861): vIndex = 0,
,V/TransactionService( 6861): onStartCommand: 1,
D/MmsSystemEventReceiver( 6861): unRegisterForConnectionStateChanges
V/TransactionService( 6861): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6861): Loading previous transactions.
,D/TelephUtils( 1555): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1555): device_type: 1
,D/TransactionService( 6861): Force clearing mTransactionList
,D/TransactionService( 6861): Force set service start id to 1
,V/TransactionService( 6861): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6861): unRegisterForConnectionStateChanges
D/TransactionService( 6861): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6861): Destroying TransactionService
,V/TransactionService( 6861): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/wpa_supplicant( 1344): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1344): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1344): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1344): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1344): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1344): wlan0: Scan completed in 2.166871 seconds
D/wpa_supplicant( 1344): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1344): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1344): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1344): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1344): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1344): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1344): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-83
,I/wpa_supplicant( 1344): [NULL] 00:37:b7:9d:3e:73 freq=5500 level=-88
I/wpa_supplicant( 1344): [NULL] a0:c5:62:7a:49:97 freq=5180 level=-89
D/wpa_supplicant( 1344): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1344): BSS: last_scan_res_used=6/32
D/wpa_supplicant( 1344): wlan0: Scan-only results received
D/wpa_supplicant( 1344): wlan0: Radio work 'scan'@0x55a5c08860 done in 2.168070 seconds
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  944): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  944): handleMessage: E msg.what=147461
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
E/WifiStateMachine(  944): processMsg: DriverStartedState
E/WifiStateMachine(  944):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 bcn=0
D/WifiStateMachine(  944): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1344): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  944): [1,454,578,955,932 ms] noteScanEnd no scan source
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1344): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  944): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@333a7773 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  944): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  944): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  944): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  944):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2412
E/WifiAutoJoinController (  944): Gonzos 38:f8:89:11:e9:11 rssi=-83 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  944): UPC503894600 a0:c5:62:7a:49:97 rssi=-89 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): FunBox2-3E72 00:37:b7:9d:3e:73 rssi=-88 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): 01ABC c2:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  944): ageScanResultsOut delay 40000 size 6 now 1454578955936
E/WifiAutoJoinController (  944): newSupplicantResults size=6 known=1 true
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1344): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  944): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  944): ssid=NG700
E/WifiAutoJoinController (  944): id=0
E/WifiAutoJoinController (  944): mode=station
E/WifiAutoJoinController (  944): pairwise_cipher=CCMP
E/WifiAutoJoinController (  944): group_cipher=CCMP
E/WifiAutoJoinController (  944): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  944): wpa_state=COMPLETED
E/WifiAutoJoinController (  944): ip_address=192.168.1.130
E/WifiAutoJoinController (  944): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  944): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  944): uuid=1,2345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  944): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  944): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-57,-127) num=(1,0)
E/WifiAutoJoinController (  944): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  944): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-57 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  944): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  944): Done attemptAutoJoin status=0
E/WifiConfigStore(  944):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  944): handleMessage: X
D/WifiManager( 1817): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=326
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=326
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@213ec69a,
I/PMS     (  944): Going to sleep due to screen timeout (uid 1000)...
D/ActivityManager(  944): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{1173fa53 #7 A=.Prism U=0 sz=1}
W/PMS     (  944): mWirelessDisplayManager is null
W/PMS     (  944): mWirelessDisplayManager is still null
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  944): pid=944, uid=1000
W/PMN     (  944): goingToSleep
W/SensorService(  944): Active sensors: size = 4
I/PMS     (  944): Sleeping (uid 1000)...
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
D/XAN-DPS (  944): prepareColorFade 1
W/SensorService(  944): CM32181 Light sensor (handle=0x00000003, connections=1)
D/PMS     (  944): acquireWL(33d90f90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 944 1000 null
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@213ec69a, eanble = 0, strlen(mName) = 91
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  944): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1c35d300
W/SensorService(  944): Listener[1] = com.htc.smartdim.sensor_eye@9c31872
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  944): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  944): Build Date: 03/09/15 Mon
I/Adreno-EGL(  944): Local Branch: 
I/Adreno-EGL(  944): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  944): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  944):                  d74aa161a12b9c6fc6332151
,W/PMN     (  944): goingToSleep done,
I/FeedHostManager( 1606): [onPause]
,I/FeedProviderManager( 1606): onPause
I/FeedHostManager( 1606): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@61a403a
I/SocialFeedProvider( 1606): +onPause
,I/SocialFeedProvider( 1606): -onPause
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  944): releaseWL(33d90f90): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  944): ACTION_SCREEN_ON
,I/AlarmManager(  944): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done recovering
,I/AlarmManager(  944): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  944): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiTrafficPoller(  944):  packet count Tx=218 Rx=326
E/WifiDataStallTracker(  944): ENABLE_DATA_MONITOR_POLL true Token 1
E/WifiStateMachine(  944): handleMessage: E msg.what=131167
E/WifiStateMachine(  944): processMsg: ConnectedState
,E/WifiStateMachine(  944):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: DriverStartedState
E/WifiStateMachine(  944):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
D/WifiDataStallTracker(  944): updateDataStallInfo: mDataStallTxRxSum={txSum=196 rxSum=184} preTxRxSum={txSum=196 rxSum=184}
D/WifiDataStallTracker(  944): updateDataStallInfo: NONE
D/WifiDataStallTracker(  944): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
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
E/WifiStateMachine(  944): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  944): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  944): handleScreenStateChanged Exit: true
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0,
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
V/SRS_Proc(  398): ParamSet string: screen_state=on
E/audio_a2dp_hw(  398): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  944): handleMessage: E msg.what=155650
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
,D/WifiController(  944): processMsg: DefaultState
,D/NetworkPolicy(  944): updateScreenOn: false
I/wpa_supplicant( 1344): environment dirty rate=0 [0][0][0]
V/NetworkPolicy(  944): updateIfacesLocked()
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131127
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
,E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131129
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1344): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1344): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  944): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=36 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  944): handleMessage: X
D/WifiController(  944): handleMessage: X
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/ActivityManager(  944): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6930 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/XAN-DPS (  944): prepareColorFade done,
D/XAN-DPS (  944): setBrightness to 0
,W/ContextImpl( 6930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@1c35d300,
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
I/DisplayManagerService(  944): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  944): disable: get sensor name = CM32181 Light sensor
V/ActivityManager(  944): Display changed displayId=0
D/DotMatrix( 1330): [EventService]  onDisplayChanged: 0,
D/DotMatrix( 1330): [EventService] mbHDMIConnect: false, mCoverOn:false
E/qdutils (  384): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  384): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
,W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@1c35d300, eanble = 0, strlen(mName) = 67
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@9c31872
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_ON
,W/ContextImpl( 6930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6930): MY_DEBUG = false
,D/SmartSyncUtils( 6930): isEpsOn(), nState = 0
,D/PMS     (  944): acquireWL(4492f9a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6930 1000 null,
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false),
D/PMS     (  944): acquireWL(ac660cb): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1817 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(2ff740a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1817 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(4492f9a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  944): releaseWL(ac660cb): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(2ff740a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/AlarmManager(  944): ACTION_SCREEN_OFF
,I/AlarmManager(  944): [AlarmQueuing] screen off now: 
I/AlarmManager(  944): [AlarmQueuing] data connection: true
I/AlarmManager(  944): [AlarmQueuing] wifi connection: true
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  944): Init customizeScreenOffDelayClass error
I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@ddee74a, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
E/WifiTrafficPoller(  944): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  944): stopDataStallAlarm 
,E/WifiDataStallTracker(  944): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  944): handleMessage: E msg.what=131167
,E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: DriverStartedState
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): enable: get sensor name = hTC Gesture Motion HIDI
E/WifiStateMachine(  944):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
,V/SRS_Proc(  398): ParamSet string: screen_state=off
E/audio_a2dp_hw(  398): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  944):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1344): SET_SCREEN_ON:Off
I/wpa_supplicant( 1344): htc_wext_set_keepalive +
I/wpa_supplicant( 1344): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1344): getPrivFuncNum +	
I/wpa_supplicant( 1344): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1344): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1344): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1344): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1344): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  944): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
,D/WifiController(  944): handleMessage: E msg.what=155651
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
D/WifiStateMachine(  944): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  944): handleScreenStateChanged Exit: false
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: ConnectedState
D/NetworkPolicy(  944): updateScreenOn: false
E/WifiStateMachine(  944):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
V/NetworkPolicy(  944): updateIfacesLocked()
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131155
E/WifiStateMachine(  944): processMsg: ConnectedState
D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
E/WifiStateMachine(  944):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1414955625] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1414955624] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,W/SensorService(  944): pid=1221, uid=10041
W/SensorService(  944): Active sensors: size = 4
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@ddee74a, eanble = 1, strlen(mName) = 56
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2,
W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@9c31872
W/SensorService(  944): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@ddee74a
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1330): [EventService] getTotalRam: 1842 Mb
E/WifiStateMachine(  944): handleMessage: X
,W/ContextImpl( 6930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6930): isEpsOn(), nState = 0,
,D/SmartSyncUtils( 6930): isEpsOn(), nState = 0
W/ContextImpl( 6930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@9c31872
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  944): pid=944, uid=1000,
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1),
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@9c31872, eanble = 0, strlen(mName) = 35,
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@ddee74a
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = CM36686 Proximity sensor
W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 2,
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@9c31872, eanble = 0, strlen(mName) = 35
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@ddee74a
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@9c31872
,I/ActivityManager(  944): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6962 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/ActivityThread(  944): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@33b054c3 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  944): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@33b054c3 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  944): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  944): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
,E/ActivityThread(  944): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  944): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  944): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  944): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  944): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  944): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  944): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  944): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  944): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  944): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  944): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  944): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  944): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  944): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  944): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/ContactMessageStore( 1555): start background delete task...
D/ContactMessageStore( 1555): size: 0 , 0
D/ContactMessageStore( 1555): Background delete complete
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false),
D/PMS     (  944): acquireWL(276c3efd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1817 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(276c3efd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(38f617f2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1817 10024 WorkSource{10024 com.google.android.gms}
I/PowerUsageList:PowerUsageHelper( 6930): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PMS     (  944): releaseWL(38f617f2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:BatterySipperExt( 6930): gen(), null == sipper.uidObj, userId = 0
,E/qdutils (  384): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  944): Setting HAL interactive mode to false
E/qdutils (  384): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  944): Setting HAL interactive mode to false done
D/SurfaceControl(  944): Excessive delay in setPowerMode(): 286ms
D/PMS     (  944): Setting HAL auto-suspend mode to true
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  944): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  944): screenObserver, isScreenOn=false
,D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/HABCtrl (  944): TPE algorithm. remove timeout.
D/PMS     (  944): OOBE c monitor 11
I/InputMethodManagerService(  944): Disable input method client, pid=1606
,I/InputManager(  944): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  944): acquireWL(33401e43): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
,I/BatteryService(  944): n_update end
,D/PMS     (  944): releaseWL(33401e43): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/NfcService( 1571): ScreenObserver: OFF
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
D/NfcService( 1571): applyRouting - 0
I/RemoteViews( 1221): apply : com.htc.updater 0 15 1 36
,D/NfcService( 1571): applyRouting -2
D/PMS     (  944): acquireWL(6577cc0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1571 1027 null
D/NfcService( 1571): applyRouting
,D/NfcService( 1571): Ignore this applyRouting...
,D/PMS     (  944): releaseWL(6577cc0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/SmartSyncUtils( 6930): getMobilePolicyEnabled, result = true
,I/ActivityManager(  944): Killing 6533:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=6533
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/PowerUI ( 1221): closing low battery warning: level=100
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiService(  944): New client listening to asynchronous messages,
E/WifiTrafficPoller(  944): ADD_CLIENT: 7
,I/ClockController( 1221): stop clock update:screen off,
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  944): Recipient 6533,
,D/PowerUsageList:PowerUsageHelper( 6930): MY_DEBUG = false
,D/Process (  944): killProcessQuiet, pid=5998
,I/ActivityManager(  944): Killing 5998:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL false Token 13 num clients 7
,I/ActivityManager(  944): Recipient 5998
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,D/Process (  944): killProcessQuiet, pid=6573
I/ActivityManager(  944): Killing 6573:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6573
,D/Process (  944): killProcessQuiet, pid=6603
I/ActivityManager(  944): Killing 6603:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6603
,D/PMS     (  944): releaseWL(10422ccd): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,E/WifiDataStallTracker(  944): DATA_MONITOR_POLL false Token 3
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2675] from screen [on:0 period:-1414952943] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1414952941] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): handleMessage: X
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  944): DATA_MONITOR_POLL false Token 3
,D/ContactMessageStore( 1555): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1555): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Process (  944): killProcessQuiet, pid=5812
I/ActivityManager(  944): Killing 5812:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5812
,D/PMS     (  944): acquireWL(17c2cdf9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000},
,V/AlarmManager(  944): sending alarm PendingIntent{2c90fbaf: PendingIntentRecord{3ec4abbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=134555, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{49c13e: PendingIntentRecord{c3c5b9f com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142389, Int=0
,D/WeatherUtility( 1221): Weather sync is On
D/PMS     (  944): releaseWL(17c2cdf9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  944): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  944): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  944): acquireWL(1597a4ec): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 944 1000 null
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  944): [NET] android_getaddrinfo_proxy+
D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  944): [NET] android_getaddrinfo_proxy-, success
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  944): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  944): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  944): [reportHTCStatus] eventMask = 3 , status = 0
D/PMS     (  944): acquireWL(5d023d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 944 1000 null
D/GpsLocationProvider(  944): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  944): releaseWL(1597a4ec): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  944):  [handleDownloadXtraData]inject done.
D/PMS     (  944): releaseWL(5d023d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  944): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/ContactMessageStore( 1555): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1555): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  944): acquireWL(359b4331): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0,
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): releaseWL(359b4331): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): updateBatteryInfo
D/WifiController(  944): processMsg: DeviceActiveState
D/PMS     (  944): runPSCheck
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): handleMessage: X
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1555): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  944): acquireWL(a7aba16): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000}
,D/PMS     (  944): acquireWL(1df81f97): PARTIAL_WAKE_LOCK  *backup* 0x1 944 1000 null
V/AlarmManager(  944): sending alarm PendingIntent{220fa584: PendingIntentRecord{d2fe16d android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454579012953, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{2c90fbaf: PendingIntentRecord{3ec4abbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=194556, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{3b6061a2: PendingIntentRecord{b151e33 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=201158, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{35a395f0: PendingIntentRecord{15f62769 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191369, Int=0
,W/BackupManagerService(  944): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  944): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  944): acquireWL(3e06f5ee): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  944): releaseWL(1df81f97): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/PMS     (  944): releaseWL(a7aba16): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  944): acquireWL(2bf96a8f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3e06f5ee): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  944): releaseWL(2bf96a8f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(3ad25aa1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3ad25aa1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  944): acquireWL(1cb3d4c6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(1cb3d4c6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(1a8a1c87): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(38e977b4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(5887752): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(1a8a1c87): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1846): Vacuum at: now=1454579046836 tag=VacuumService
,D/PMS     (  944): releaseWL(38e977b4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(16805b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(16805b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  944): acquireWL(b2abcd9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(b2abcd9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(5887752): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): acquireWL(2f92b69e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(2f92b69e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(1150157f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(1150157f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(24e0094c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(33014d95): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(24e0094c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1846): Using platform SSLCertificateSocketFactory
,W/Uploader( 1846): No account for auth token provided
,D/libc    ( 1846): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1846): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1846): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1846): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1846): [NET] android_getaddrinfo_proxy+
D/libc    ( 1846): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  392): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1846): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1846): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1846): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1846): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1846): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1846): No account for auth token provided,
,W/Uploader( 1846): No account for auth token provided,
,W/Uploader( 1846):  no longer exists, so no auth token.,
,W/Uploader( 1846): No account for auth token provided
,I/GLSUser ( 1846): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1846): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1846): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1846): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,E/Uploader( 1846): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1846): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1846): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1846): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1846): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1846): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1846): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1846): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1846): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1846): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1846): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1846): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1846): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  944): releaseWL(33014d95): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(13df5c6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(13df5c6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(311e5d7c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(311e5d7c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1633): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@a69f01b
D/Process (  944): killProcessQuiet, pid=5614
I/ActivityManager(  944): Killing 5614:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5614
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  944): acquireWL(3451c605): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
I/BatteryService(  944): n_update end
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): releaseWL(3451c605): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944): onReceive BATTERY_CHANGED
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
,D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): handleMessage: E msg.what=155652
D/PMS     (  944): runPSCheck
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): Checking...
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): acquireWL(1e05065a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  944): n_update end
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): releaseWL(1e05065a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): runPSCheck
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1344): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1344): wlan0: BSS: Remove id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1344): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1344): wlan0: BSS: Remove id 4 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1344): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:37:b7:9d:3e:73]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:37:b7:9d:3e:73
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  944): acquireWL(13af508b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(13af508b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  944): Checking...
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  944): acquireWL(22b1d568): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
,V/AlarmManager(  944): sending alarm PendingIntent{2c90fbaf: PendingIntentRecord{3ec4abbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=254556, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{24fd2e26: PendingIntentRecord{3b406a67 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454579203532, Int=0
,D/PMS     (  944): releaseWL(22b1d568): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1846): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1846): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1846): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1846): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1846): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1846): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1846): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1846): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1846): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1846): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1846): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6169): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6169): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6169): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6169): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6169): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6169): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6169): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1330): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1330): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,I/art     (  944): Explicit concurrent mark sweep GC freed 38805(2MB) AllocSpace objects, 6(1208KB) LOS objects, 33% free, 18MB/28MB, paused 2.123ms total 186.594ms
,W/System  ( 6169): Ignoring header User-Agent because its value was null.
,D/libc    ( 6169): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 6169): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6169): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6169): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6169): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6169): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  392): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6169): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  944): acquireWL(136008f1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{2c90fbaf: PendingIntentRecord{3ec4abbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=374555, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{3d1639f3: PendingIntentRecord{d10e6b0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=378732, Int=0
,D/PMS     (  944): acquireWL(1e036cd6): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 944 1000 null
,D/PMS     (  944): acquireWL(1622bb57): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 944 1000 null,
,D/PMS     (  944): releaseWL(1e036cd6): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null,
,D/PMS     (  944): releaseWL(1622bb57): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/WeatherUtility( 1221): Weather sync is On,
D/PMS     (  944): releaseWL(136008f1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  944): acquireWL(3e287644): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(3e287644): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  944): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  944): acquireWL(7db432d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(7db432d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  944): BroadcastReceiver::onReceive+,
,D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: DefaultState
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): << updateStatus
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  417): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  385): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1555): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1555): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1555): sku_id=118
,D/ContactMessageStore( 1555): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1555): start background delete task...
,D/ContactMessageStore( 1555): size: 0 , 0
,D/ContactMessageStore( 1555): Background delete complete
,D/PMS     (  944): acquireWL(8a18062): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(8a18062): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  944): << updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  944): acquireWL(fadb5f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
,I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(fadb5f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): battery changed pluggedType: 2
,D/WifiController(  944): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  944): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: StaEnabledState
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  944): processMsg: DefaultState
I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): handleMessage: X
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  944): acquireWL(758b2b0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000},
V/AlarmManager(  944): sending alarm PendingIntent{2c90fbaf: PendingIntentRecord{3ec4abbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=434556, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{7e70939: PendingIntentRecord{1d447b7e android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805076, Int=0
,I/ActivityManager(  944): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7005 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  944): sending alarm PendingIntent{b55e529: PendingIntentRecord{261b40ae com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454579420642, Int=0
,D/PMS     (  944): releaseWL(758b2b0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,E/cutils-trace( 7026): Error opening trace file: Permission denied (13),
I/dex2oat ( 7026): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7026): dex2oat: override thread count:4
,I/dex2oat ( 7026): dex2oat took 603.097ms (threads: 4),
,I/PushClient( 7005): ApplicationMonitor {17b6a0b0}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 7005): ApplicationMonitor {17b6a0b0}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 7005): ApplicationMonitor {17b6a0b0}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7005): ApplicationMonitor {17b6a0b0}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7005): ApplicationMonitor {17b6a0b0}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 7005): ApplicationMonitor {17b6a0b0}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7005): ApplicationMonitor {17b6a0b0}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7005): ApplicationMonitor {17b6a0b0}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7005): ApplicationMonitor {17b6a0b0}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7005): PnsModel {3c369bf3}: update(): Update registration caused by: alarm,
,I/PushClient( 7005): PnsConfigModel {3d71586}: <init>(): Use dm-client for provisioning.,
,W/System.err( 7005): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 7005): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 7005): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7005): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  944): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7033 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7033): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7033 dbg=false s=true,
,I/DeviceManagement( 7033): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 7033): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7033): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 7033): WorkflowService: Starting workflow service,
,I/DeviceManagement( 7033): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3bc63e62] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 7033): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7033): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7033): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7033): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7033): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7033): SessionStateController: Checking invariants...
,I/DeviceManagement( 7033): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7033): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3bc63e62]
,I/DeviceManagement( 7033): WorkflowService: Stopping workflow service
,D/Process (  944): killProcessQuiet, pid=6782
I/ActivityManager(  944): Killing 6782:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6782,
I/PushClient( 7005): PnsModel {3c369bf3}: update(): The registration record has not expired yet. No need to update.
,I/ActivityManager(  944): Killing 6679:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=6679
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6679,
,D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0,
D/PMS     (  944): acquireWL(35b001e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  944): n_update end,
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): releaseWL(35b001e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): runPSCheck
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): Checking...
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: StaEnabledState
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  944): processMsg: DefaultState
I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  944): acquireWL(151627e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
,V/AlarmManager(  944): sending alarm PendingIntent{2c90fbaf: PendingIntentRecord{3ec4abbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=854555, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{31d56a99: PendingIntentRecord{9af315e com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941238, Int=0,
I/bt-btm  ( 3236): Received oneshot timer event complete
I/bt-btm  ( 3236): btm_ble_timeout
I/bt-btm  ( 3236): btm_gen_resolvable_private_addr
D/PMS     (  944): acquireWL(d56d93f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3236 1002 null
,D/PMS     (  944): releaseWL(151627e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
D/bt-btm  ( 3236): btm_ble_rand_enc_complete
I/bt-btm  ( 3236): btm_gen_resolve_paddr_low
D/bt-smp  ( 3236): smp_encrypt_data
W/bt-smp  ( 3236): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3236): Plain text(LSB ~ MSB) = 64 37 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3236): Encrypted text(LSB ~ MSB) = 31 9d da 28 8e 97 0d d8 ff c4 8d c3 c2 d9 93 5f 
I/bt-btm  ( 3236): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3236): Stopping oneshot timer
D/bt-btm  ( 3236): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  944): releaseWL(d56d93f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  944): acquireWL(29e5e20c): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10024}
V/AlarmManager(  944): sending alarm PendingIntent{3091755: PendingIntentRecord{30b9056a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937071, Int=0
,D/PMS     (  944): acquireWL(3869ca5b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(3869ca5b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=7060 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  944): sending alarm PendingIntent{1e1512f8: PendingIntentRecord{1e90d3d1 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
V/AlarmManager(  944): sending alarm PendingIntent{8da0e36: PendingIntentRecord{274d07c7 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454579811990, Int=0,
,W/ContextImpl( 6930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  944): releaseWL(29e5e20c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 6930): MY_DEBUG = false
,D/PowerUsageService( 6930): repeat time = 1454580712054,
,I/ImageRamCache( 7060): create image Cache, size: 31457280.,
I/ImageRamCache( 7060): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 7060): create image Cache, size: 31457280.
,I/FeedSettings( 7060): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 7060): GroupBudget 0.500000 0.380000
I/FeedSettings( 7060): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 7060): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 7060): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 7060): loadGridSize() with Alternative
,I/PowerUsageList:PowerUsageHelper( 6930): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6930): gen(), null == sipper.uidObj, userId = 0
,D/libc    ( 7060): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4,
,D/libc    ( 7060): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7060): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    ( 7060): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7060): [NET] android_getaddrinfo_proxy+
D/libc    ( 7060): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  392): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    (  392): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  392): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  392): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7060): [NET] android_getaddrinfo_proxy-, success
D/PMS     (  944): acquireWL(2d59d1a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1846 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1846): Message class com.google.f.a.a.i
,D/PMS     (  944): releaseWL(2d59d1a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  944): killProcessQuiet, pid=6704,
I/ActivityManager(  944): Killing 6704:com.test.thalitest/u0a366 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6704
,E/InputEventReceiver( 1398): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2e9dac31 uid 10366 pid 6704} (c)'
,W/SQLiteConnectionPool( 7060): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,D/PMS     (  944): acquireWL(26ee004b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
,V/AlarmManager(  944): sending alarm PendingIntent{2c90fbaf: PendingIntentRecord{3ec4abbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=974555, Int=0
D/SmartSyncUtils( 6930): isEpsOn(), nState = 0
V/AlarmManager(  944): sending alarm PendingIntent{1c6f2a28: PendingIntentRecord{3d1d5341 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454579857740, Int=0,
,D/PMS     (  944): acquireWL(1a2070e6): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6930 1000 null
,D/PMS     (  944): releaseWL(26ee004b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6930): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6930): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6930): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6930): SettingOnTime = 1454652000000, randomSettingOnTime = 1454649192000
,D/SmartSyncScreenOnOffTimeReceiver( 6930): SettingOffTime = 1454630400000, randomSettingOffTime = 1454635192000
D/SmartSyncScreenOnOffTimeReceiver( 6930): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6930): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6930): bNightModeTurnOffOnce = false
,D/PMS     (  944): releaseWL(1a2070e6): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): acquireWL(3a1a5627): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(3a1a5627): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): runPSCheck
D/WifiController(  944): processMsg: DeviceActiveState
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: StaEnabledState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): battery changed pluggedType: 2
,D/WifiController(  944): handleMessage: X
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  944): acquireWL(ca0c0d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(ca0c0d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): Checking...
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): >> updateStatus
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  944): << updateStatus
,D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  944): acquireWL(132ae27d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(132ae27d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
,D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
,D/UsbnetService(  944): BroadcastReceiver::onReceive+,
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  944): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  944): << updateStatus
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true,
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
,D/WifiController(  944): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  385): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  944): User[0] Flushing usage stats to disk
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): acquireWL(23f2b572): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  944): n_update end
D/DotMatrix( 1330): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): releaseWL(23f2b572): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1330): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/HeadsetStateMachine( 3236): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
,D/WifiController(  944): handleMessage: E msg.what=155652,
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
